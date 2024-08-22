---
title: Preparar una plantilla de correo electrónico de Adobe GenStudio para especialistas en marketing de rendimiento
description: Obtenga información sobre cómo crear una plantilla de correo electrónico personalizada para Adobe GenStudio para especialistas en marketing de rendimiento.
level: Intermediate
feature: Templates, Content
source-git-commit: 5bbc089fa7441ad8ce4cd84dd92889d1a22c0f61
workflow-type: tm+mt
source-wordcount: '383'
ht-degree: 0%

---


# Preparar plantilla de correo electrónico para Adobe GenStudio para especialistas en marketing de rendimiento

Normalmente, un diseñador crea el diseño visual de una plantilla en un programa de diseño como Adobe XD. Una vez diseñada, codificada y probada una plantilla de correo electrónico, puede prepararla para su carga y uso en GenStudio para especialistas en marketing de rendimiento.

Ver [Estructura de una plantilla](/help/user-guide/content/use-templates.md#anatomy-of-a-template).

## Adición de directrices

Antes de preparar una plantilla de anuncio Meta, asegúrese de haber agregado [directrices](/help/user-guide/guidelines/overview.md) a su GenStudio para especialistas en marketing de rendimiento y de haberlas rellenado con información completa para las marcas relevantes. Las [directrices de marca](/help/user-guide/guidelines/brands.md) influyen directamente en el contenido generado.

**Ejemplo**: Si desea que el cuerpo de una plantilla de correo electrónico no tenga más de 500 caracteres, agregue ese requisito a las [directrices de canal](/help/user-guide/guidelines/brands.md#channel-guidelines) para el campo &quot;cuerpo&quot;.

Si no se agregan directrices a GenStudio para especialistas en marketing de rendimiento, se utilizan los valores predeterminados.

## Codifique una plantilla de correo electrónico

Una vez diseñada una plantilla, se codifica con HTML y CSS en línea. El código debe ser limpio y adaptable para varios dispositivos.

Ver [ejemplos de plantillas](/help/user-guide/content/customize-template.md#template-examples).

## Prueba de una plantilla de correo electrónico

Utilice la plataforma de envío o prueba de correo electrónico para probar el correo electrónico y comprobar que se procesa correctamente en diferentes clientes y dispositivos de correo electrónico.

Pruebe para asegurarse de que la plantilla de correo electrónico cumple lo siguiente:

* El diseño se ajusta para diferentes tamaños de pantalla mediante consultas de medios CSS
* Se puede hacer clic en los botones y desplazarse hasta el lugar deseado
* La plantilla de correo electrónico se puede leer y utilizar en dispositivos móviles

## Definir áreas de contenido generadas

Defina las áreas en la plantilla de correo electrónico que deben rellenarse dinámicamente con contenido de GenStudio para especialistas en marketing de rendimiento.

Para definir áreas de contenido generadas:

* Identifique los elementos de texto de la plantilla que los especialistas en marketing de rendimiento de GenStudio deben generar automáticamente, como el titular o CTA.
* Adapte la plantilla de HTML insertando marcadores de posición dentro de ella mediante la sintaxis Handlebars.

Consulte [Marcadores de posición de contenido](/help/user-guide/content/customize-template.md#content-placeholders).

## Previsualización de la plantilla

Controle la visibilidad de áreas de contenido específicas con los ayudantes integrados. Por ejemplo, puede incluir parámetros de seguimiento en vínculos en una plantilla exportada mientras mantiene los vínculos de vista previa limpios.

Ver [vista previa de plantilla](/help/user-guide/content/customize-template.md#template-preview).

## Cargar y utilizar plantilla

Una vez que la plantilla esté diseñada, codificada, probada y vista previa, puede cargarla en GenStudio para especialistas en marketing de rendimiento para utilizarla en la generación de contenido de marketing completamente nuevo.

Consulte [Uso de plantillas](use-templates.md).
