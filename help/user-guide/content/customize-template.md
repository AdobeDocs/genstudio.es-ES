---
title: Personalizar plantillas
description: Obtenga información sobre cómo crear una plantilla personalizada para GenStudio.
level: Intermediate
feature: Templates, Content
source-git-commit: 423956d6fdbf5b31041d44eb434f90d55a87d7c0
workflow-type: tm+mt
source-wordcount: '784'
ht-degree: 0%

---


# Personalizar plantillas

Puede adaptar las plantillas de HTML para GenStudio mediante el lenguaje de plantilla _Handlebars_. La sintaxis de Handlebars utiliza texto normal con llaves dobles como marcadores de posición de contenido. Consulte [`What is Handlebars?`](https://handlebarsjs.com/guide/#what-is-handlebars) en la _Guía de idioma de Handlebars_ para aprender a preparar la plantilla.

## Estructura de plantilla

<!-- This is for email. In the future, maybe use tabs to provide guidance for other template types.
-->

Si no tiene una plantilla de HTML lista para usar en GenStudio, puede empezar por definir la estructura del correo electrónico con las etiquetas de HTML: `DOCTYPE`, `html`, `head` y `body`. Puede incluir estilos CSS para personalizar el aspecto del correo electrónico.

```html
<!DOCTYPE html>
<html>
<head>
    <title>Title</title>
    <style>
    </style>
</head>
<body>
</body>
</html>
```

>[!TIP]
>
>En las siguientes secciones, añada marcadores de posición de contenido para campos de correo electrónico, oculte elementos innecesarios de la vista previa y administre vínculos a contenido estático. Una vez que la plantilla esté lista, puedes [cargarla en GenStudio](use-templates.md#upload-a-template) y empezar a generar correos electrónicos personalizados basados en la plantilla personalizada.

## Marcadores de contenido

Dentro del encabezado o del cuerpo de la plantilla, puede utilizar la sintaxis de Handlebars para insertar marcadores de posición de contenido donde requiera que GenStudio rellene el correo electrónico con contenido real. GenStudio reconoce e interpreta los marcadores de posición de contenido automáticamente en función del nombre del campo.

Por ejemplo, puede usar `{{ headline }}` para indicar dónde se debe colocar el titular del correo electrónico:

```handlebars
<div>{{ headline }}</div>
```

El número máximo de campos permitidos en una plantilla personalizada es de veinte.

**Nombres de campo reconocidos**:

| Campo | Función | Plantilla de canal |
| -------------- | ---------------------- | -------------------- |
| `pre_header` | Encabezado previo | email |
| `headline` | Titular | correo electrónico<br>anuncio social |
| `body` | Copia de cuerpo | correo electrónico<br>anuncio social |
| `cta` | Llamada a la acción | correo electrónico<br>anuncio social |
| `on_image_text` | En texto de imagen | anuncio social |
| `image` | Imagen | correo electrónico<br>anuncio social |
| `brand_logo` | Logotipo de la marca seleccionada | anuncio social |

>[!IMPORTANT]
>
>GenStudio proporciona automáticamente a la plantilla de correo electrónico un campo `subject` durante el proceso [!DNL Create], por lo que no es necesario incluir el campo de asunto en la plantilla.

+++Ejemplo: Plantilla básica

El siguiente es un ejemplo básico de una plantilla de HTML para correo electrónico. El encabezado contiene CSS en línea simple para el estilo. El cuerpo contiene un marcador de posición `pre-header`, `headline` y `image` que GenStudio usará para insertar contenido durante el proceso de generación de correo electrónico.

```handlebars {line-numbers="true" highlight="13"}
<!DOCTYPE html>
<html>
<head>
    <title>Adobe</title>
    <style>
        .container {
            width: 100%;
            padding: 20px;
            font-family: Arial, sans-serif;
        }
    </style>
</head>
<body>{{ pre_header }}
    <div class="container">
        <h1>{{ headline }}</h1>
        <p><img alt="{{ headline }}"
                src="{{ image }}"
                width="600" height="600"
                border="0"/></p>
        <p>{{ body }}</p>
    </div>
</body>
</html>
```

+++

### Imagen de fondo

Al diseñar un anuncio para Meta, es importante utilizar una imagen de fondo complementada por texto y una superposición de logotipo de marca. Para garantizar la escala adecuada de la imagen, las plantillas de publicidad Meta requieren que se especifique un `aspect ratio`. En este contexto, solo se puede proporcionar un campo de imagen.

## Secciones o grupos

_Las secciones_ proporcionan una forma de informar a GenStudio de que los campos que pertenecen a una sección requieren un alto grado de coherencia. El establecimiento de esta relación ayuda a la IA a generar contenido que coincida con los elementos creativos de la sección. Una plantilla puede incluir hasta tres secciones.

Utilice un prefijo de su elección en el nombre del campo para indicar que este campo forma parte de una sección o grupo. Por ejemplo, es posible que desee resaltar el contenido que aparece en un área resaltada. Puede elegir identificar el contenido de esta área con un prefijo común:

- `spotlight_headline`
- `spotlight_body`

Cada sección solo puede tener una de un tipo de campo. Por ejemplo, el grupo de ejemplo anterior con el prefijo `spotlight` solo puede tener un campo `spotlight_headline`.

Cuando tiene varias secciones (tres como máximo):

- `headline`
- `body`
- `spotlight_headline`
- `spotlight_body`
- `news_headline`
- `news_body`

GenStudio entiende que `spotlight_headline` está más relacionado con `spotlight_body` que con `news_body`.

+++Ejemplo: Plantilla con varias secciones

La siguiente es la misma plantilla de HTML en el ejemplo anterior, pero con dos secciones más. El encabezado contiene CSS en línea para aplicar estilo a un pod. El cuerpo utiliza dos pods con marcadores de posición de contenido con un prefijo.

```handlebars {line-numbers="true" highlight="33"}
<!DOCTYPE html>
<html>
<head>
    <title>Adobe</title>
    <style>
        .container {
            width: 100%;
            padding: 20px;
            font-family: Arial, sans-serif;
        }
        .pod {
            background-color: #f8f8f8;
            margin: 10px;
            padding: 20px;
            border-radius: 5px;
        }
        .pod h2 {
            color: #333;
        }
        .pod p {
            color: #666;
        }
    </style>
</head>
<body>{{ pre_header }}
    <div class="container">
        <h1>{{ headline }}</h1>
        <p><img alt="{{ headline }}"
                src="{{ image }}"
                width="600" height="600"
                border="0"/></p>
        <p>{{ body }}</p>
        <div class="pod">
            <h2>{{ pod1_headline }}</h2>
            <p>This is Pod 1 content.</p>
        </div>
        <div class="pod">
            <h2>{{ pod2_headline }}</h2>
            <p>This is Pod 2 content.</p>
        </div>
    </div>
</body>
</html>
```

+++

## Previsualización de plantilla

Las plantillas de correo electrónico a veces contienen contenido especial que no es necesario para la vista previa en GenStudio. Puede controlar la visibilidad de este contenido mediante los Ayudantes integrados, que son expresiones especiales en el lenguaje de plantilla Handlebars que ayudan a realizar determinadas acciones.

El valor `_genStudio.browser` se establece al procesar una plantilla y el valor `genStudio.export` se establece al exportar una plantilla. Puede decidir incluir cierto contenido en la parte superior de los correos electrónicos mediante un envoltorio condicional, por ejemplo, cuando la plantilla se utiliza para la exportación:

```handlebars
{{#if _genStudio.export}}
<%@ include view='emailParent' %>
{{/if}}
```

Otro ejemplo puede ser evitar el uso de códigos de seguimiento al obtener una vista previa de una plantilla de correo electrónico en GenStudio. Este ejemplo muestra cómo añadir parámetros de seguimiento a los vínculos en la plantilla exportada, manteniendo limpios los vínculos de vista previa:

```handlebars
<a class="button" {{#if _genStudio.browser }}
   href="{{ link }}"{{/if}}{{#if _genStudio.export }}
   href="{{ link }}?trackingid=<%=getTrackingId()%>&mv=email"{{/if}}
   target="_blank">{{ cta }}</a>
```

## Contenido estático

Las plantillas de correo electrónico y metadatos suelen vincularse a imágenes y archivos CSS alojados fuera de GenStudio. Cuando GenStudio genera miniaturas para estas plantillas o las experiencias derivadas de ellas, puede ignorar estos recursos externos si no tienen los encabezados correctos de Intercambio de recursos de origen cruzado (CORS).

Para asegurarse de que estos recursos están disponibles durante el proceso de generación de miniaturas, tenga en cuenta dos opciones:

1. **Usar encabezados CORS**: El servidor host debe enviar respuestas con un encabezado `Access-Control-Allow-Origin` establecido en `https://experience.adobe.com` como valor para entornos de producción. Este método permite a GenStudio acceder a los recursos e incluirlos.
1. **Usar URL de datos**: incruste los recursos externos directamente en la plantilla mediante URL de datos. Este método evita las restricciones CORS y garantiza que los recursos estén disponibles durante la generación de miniaturas.
