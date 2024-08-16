---
title: Preparar una plantilla de anuncio Meta para el Adobe GenStudio de los especialistas en marketing de rendimiento
description: Aprenda a crear una plantilla de anuncio Meta personalizada para Adobe GenStudio para especialistas en marketing de rendimiento.
level: Intermediate
feature: Templates, Content
source-git-commit: c9d09801f0bd3732611b01d4a98cc7ebf38884d7
workflow-type: tm+mt
source-wordcount: '423'
ht-degree: 0%

---


# Preparar metaplantilla de anuncio para el Adobe GenStudio de los especialistas en marketing de rendimiento

La creación de una plantilla de Meta ad implica un enfoque estructurado adaptado a los medios sociales. Después de diseñar y probar una plantilla de anuncio Meta, puede prepararla para su carga y uso en GenStudio para especialistas en marketing de rendimiento.

## Adición de directrices

Antes de preparar una plantilla de anuncio Meta, asegúrese de haber agregado [directrices](/help/user-guide/guidelines/overview.md) a su GenStudio para especialistas en marketing de rendimiento y de haberlas rellenado con información completa para las marcas relevantes. Las [directrices de marca](/help/user-guide/guidelines/brands.md) influyen directamente en el contenido generado.

**Ejemplo**: Si desea que el cuerpo de una plantilla de Meta ad no tenga más de 500 caracteres, agregue ese requisito a las [directrices de canal](/help/user-guide/guidelines/brands.md#channel-guidelines) para el campo &quot;cuerpo&quot;.

Si no se agregan directrices a GenStudio para especialistas en marketing de rendimiento, se utilizan los valores predeterminados.

## Diseño de una plantilla

Normalmente, un diseñador crea el diseño visual de una plantilla en un programa de diseño como Adobe XD.

Ver [Anatomía de una plantilla](/help/user-guide/content/use-templates.md#anatomy-of-a-template) y [ejemplos de plantilla](/help/user-guide/content/customize-template.md#template-examples).

### Especificaciones del anuncio

GenStudio para especialistas en marketing de rendimiento admite estas relaciones de aspecto para los anuncios Meta:

* Cuadrado (1:1): 1080 x 1080 píxeles
* Vertical (4:5): 1080 x 1350 píxeles
* Historia (9:16): 1080 x 1920 píxeles

Si el anuncio no está diseñado en ninguna de estas relaciones de aspecto, GenStudio para especialistas en marketing de rendimiento recorta automáticamente la imagen en el tamaño adecuado.

## Prueba de una plantilla de publicidad Meta

Pruebe la plantilla con Creative Hub de Meta para ver el aspecto del anuncio en diferentes ubicaciones, como en una fuente o como una historia.

Utilice la plataforma de envío o prueba de correo electrónico para probar el correo electrónico y comprobar que se procesa correctamente en diferentes clientes y dispositivos de correo electrónico.

## Definir áreas de contenido generadas

Defina las áreas en la plantilla de correo electrónico que deben rellenarse dinámicamente con contenido de GenStudio para especialistas en marketing de rendimiento.

Para definir áreas de contenido generadas:

* Identifique los elementos de texto de la plantilla que los especialistas en marketing de rendimiento de GenStudio deben generar automáticamente, como el titular o CTA.
* Adapte la plantilla del HTML insertando marcadores de posición dentro de ella mediante la sintaxis Handblebars.

Consulte [Marcadores de posición de contenido](/help/user-guide/content/customize-template.md#content-placeholders).

## Previsualización de la plantilla

Controle la visibilidad de áreas de contenido específicas mediante el uso de Ayudantes integrados. Por ejemplo, puede incluir parámetros de seguimiento en vínculos en una plantilla exportada mientras mantiene los vínculos de vista previa limpios.

Ver [vista previa de plantilla](/help/user-guide/content/customize-template.md#template-preview).

## Cargar y utilizar plantilla

Una vez que la plantilla esté diseñada, codificada, probada y vista previa, puede cargarla en GenStudio para especialistas en marketing de rendimiento para utilizarla en la generación de contenido de marketing completamente nuevo.

Consulte [Uso de plantillas](use-templates.md).
