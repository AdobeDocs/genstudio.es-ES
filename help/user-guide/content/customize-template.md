---
title: Personalizar plantillas
description: Obtenga información sobre cómo crear una plantilla personalizada para GenStudio.
level: Intermediate
feature: Templates, Content
source-git-commit: 6870f1b7056219d03cabbcc4e5ddbfa436b1a56d
workflow-type: tm+mt
source-wordcount: '788'
ht-degree: 0%

---


# Personalizar plantillas

Puede adaptar las plantillas de HTML para GenStudio mediante el lenguaje de plantilla _Handlebars_. La sintaxis de Handlebars utiliza texto normal con llaves dobles como marcadores de posición de contenido. Consulte [`What is Handlebars?`](https://handlebarsjs.com/guide/#what-is-handlebars) en la _Guía de idioma de Handlebars_ para aprender a preparar la plantilla.

<!-- This is for email. In the future, maybe use tabs to provide guidance for other template types.
-->If you do not have an HTML template ready to use in GenStudio, you can start by defining the structure of your email using HTML tags: `DOCTYPE`, `html`, `head`, and `body`. You can include CSS styles to customize the appearance of your email.

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

Ver [ejemplos de plantillas](#template-examples).

>[!TIP]
>
>En las siguientes secciones, añada marcadores de posición de contenido para campos de correo electrónico, consulte plantillas de ejemplo, ocultar elementos innecesarios de la vista previa y administrar vínculos a contenido estático. Una vez que la plantilla esté lista, puedes [cargarla en GenStudio](use-templates.md#upload-a-template) y empezar a generar correos electrónicos personalizados basados en la plantilla personalizada.

## Marcadores de contenido

Dentro del encabezado o del cuerpo de una plantilla, puede utilizar la sintaxis de Handlebars para insertar marcadores de posición de contenido donde necesite que GenStudio rellene la plantilla con contenido real. GenStudio reconoce e interpreta los marcadores de posición de contenido automáticamente en función del nombre del campo.

Por ejemplo, puede usar `{{ headline }}` para indicar dónde se debe colocar el titular del correo electrónico:

```handlebars
<div>{{ headline }}</div>
```

### Nombres de campo

El número máximo de campos permitidos en una plantilla personalizada es de veinte.

#### Nombres de campo reconocidos

En la tabla siguiente se enumeran los nombres de campo reconocidos por GenStudio para su rellenado en plantillas.

| Campo | Función | Plantilla de canal |
| -------------- | ---------------------- | -------------------- |
| `pre_header` | Encabezado previo | correo electrónico (recomendado) |
| `headline` | Titular | correo electrónico (recomendado)<br>Meta ad |
| `body` | Copia de cuerpo | correo electrónico (recomendado)<br>Meta ad |
| `cta` | Llamada a la acción | correo electrónico (recomendado)<br>Meta ad |
| `on_image_text` | En texto de imagen | Meta anuncio (recomendado) |
| `image` | Imagen | correo electrónico (recomendado)<br>Meta ad (recomendado) |
| `brand_logo` | Logotipo de la marca seleccionada | Meta anuncio |

GenStudio rellena automáticamente ciertos campos en las plantillas, por lo que no es necesario incluirlos en sus diseños de plantilla:

* Campo `subject` (plantilla de correo electrónico)
* Campos de `headline`, `body` y `CTA` (plantilla de anuncio meta)

>[!WARNING]
>
>En el caso de los anuncios de Instagram, el titular generado no aparece en la experiencia final.

#### Nombres de campo manuales

Todos los demás nombres de campo se tratan como campos rellenados manualmente. Si desea que una sección pueda editarse, agregue corchetes dobles alrededor de la sección que desee editar.

> Ejemplo: ``{{customVariable}}`` (customVariable es la sección editable manualmente)

## Secciones o grupos

_Las secciones_ informan a GenStudio de que los campos de esta sección requieren un alto grado de coherencia. El establecimiento de esta relación ayuda a la IA a generar contenido que coincida con los elementos creativos de la sección.

Utilice un prefijo de su elección en el nombre del campo para indicar que un campo forma parte de una sección o grupo.

Por ejemplo, es posible que desee resaltar el contenido que aparece en un área resaltada:

* `spotlight_headline`
* `spotlight_body`

Cada sección solo puede tener uno de cada tipo de campo. En el ejemplo anterior, el prefijo `spotlight` solo puede tener un campo `spotlight_headline`.

Una plantilla puede incluir hasta tres secciones:

* `headline`
* `body`
* `spotlight_headline`
* `spotlight_body`
* `news_headline`
* `news_body`

GenStudio entiende que `spotlight_headline` está más relacionado con `spotlight_body` que con `news_body`.

## Ejemplos de plantillas

+++Ejemplo: Plantilla de correo electrónico con una sección

El siguiente es un ejemplo básico de una plantilla de HTML para un correo electrónico que contiene una sección. El encabezado contiene CSS en línea simple para el estilo. El cuerpo contiene `pre-header`, `headline` y `image` [marcador de posición](#content-placeholders) que GenStudio usará para insertar contenido durante el proceso de generación de correo electrónico.

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

+++Ejemplo: Plantilla de correo electrónico con varias secciones

La siguiente es la misma plantilla de HTML en el ejemplo anterior, pero con dos secciones más. El encabezado contiene CSS en línea para aplicar estilo a un grupo. El cuerpo usa dos grupos con [marcadores de posición de contenido](#content-placeholders) con un prefijo.

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

+++Ejemplo: plantilla de meta-anuncio

El siguiente es un ejemplo básico de una plantilla de publicidad Meta. El encabezado contiene CSS en línea para el estilo. El cuerpo usa [marcadores de posición de contenido](#content-placeholders) con un prefijo.

```handlebars {line-numbers="true" highlight="33"}
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Adobe</title>
    <style>
        .ad-container {
            width: 300px;
            border: 1px solid #ddd;
            padding: 16px;
            font-family: Arial, sans-serif;
        }
        .ad-image {
            width: 100%;
            height: auto;
        }
        .ad-headline {
            font-size: 18px;
            font-weight: bold;
            margin: 12px 0;
        }
        .ad-body {
            font-size: 14px;
            margin: 12px 0;
        }
        .ad-cta {
            display: inline-block;
            padding: 10px 20px;
            background-color: #007bff;
            color: #fff;
            text-decoration: none;
            border-radius: 4px;
            text-align: center;
        }
    </style>
</head>
<body>
<div class="ad-container">
    <img src="{{ image }}" alt="Ad Image" class="ad-image">
    <div class="ad-headline">"{{ headline }}"</div>
    <div class="ad-body">"{{ body }}"</div>
    <a href="(https://example.com)" class="ad-cta">"{{ CTA }}"</a>
</div>

</body>
</html>
```

+++

## Previsualización de plantilla

Controle la visibilidad del contenido especial mediante los Ayudantes integrados (expresiones especiales en el lenguaje de plantilla Handlebars que realizan determinadas acciones). Por ejemplo, puede añadir parámetros de seguimiento a los vínculos en la plantilla exportada mientras mantiene limpios los vínculos de vista previa.

El valor `_genStudio.browser` se establece al procesar una plantilla y el valor `genStudio.export` se establece al exportar una plantilla. Puede decidir incluir cierto contenido en la parte superior de un correo electrónico mediante un envoltorio condicional, por ejemplo, cuando la plantilla se utiliza para la exportación:

```handlebars
{{#if _genStudio.export}}
<%@ include view='emailParent' %>
{{/if}}
```

Otro ejemplo puede ser evitar el uso de códigos de seguimiento al obtener una vista previa de una plantilla en GenStudio. Este ejemplo muestra cómo añadir parámetros de seguimiento a los vínculos en la plantilla exportada, manteniendo limpios los vínculos de vista previa:

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
