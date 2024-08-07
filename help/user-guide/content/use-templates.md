---
title: Trabajo con plantillas
description: Aprenda a utilizar las plantillas para crear experiencias atractivas en GenStudio.
feature: Templates, Content
source-git-commit: 6870f1b7056219d03cabbcc4e5ddbfa436b1a56d
workflow-type: tm+mt
source-wordcount: '443'
ht-degree: 2%

---


# Trabajo con plantillas

Las plantillas de GenStudio son esenciales para permitir que los creadores de contenido produzcan rápidamente contenido de marketing coherente en la marca. El uso de plantillas reduce significativamente el tiempo y el esfuerzo necesarios para generar contenido nuevo al proporcionar un punto de partida que incluye diseños y elementos de diseño preconfigurados.

Esta guía proporciona información detallada sobre cómo:

* Preparar una [plantilla de correo electrónico](email-template.md) o plantilla de anuncio meta
* [Personalizar plantillas](customize-template.md) para GenStudio
* [Cargar plantillas](#upload-a-template) en GenStudio
* [Uso de plantillas para crear experiencias](#use-a-template)

## Estructura de una plantilla

El diseño de plantilla básico incluye los siguientes elementos:

| Elemento | Función | Plantilla de canal |
| ------------ | ---------------------- | -------------------- |
| Preencabezado | Entre 40 y 50 caracteres <br>Actúa como línea de asunto secundaria y mejora la línea de asunto principal <br>Visible en la bandeja de entrada junto al asunto antes de que se abra el correo electrónico | email |
| Encabezado | La sección superior del destinatario del correo electrónico ve al abrir el correo electrónico <br>Establece el tono y proporciona contexto para el contenido incluido | email |
| Titular | El primer destinatario de contenido <br> debe ser convincente para captar el interés | Meta anuncio |
| Cuerpo | Área de contenido principal donde se transmite el mensaje principal <br>Puede incluir texto, imágenes y otros elementos multimedia | correo electrónico<br>Meta anuncio |
| CTA | Llamada a acción que anima al destinatario a realizar acciones específicas, como hacer clic en un vínculo o realizar una compra | correo electrónico<br>Meta anuncio |
| Imágenes | Mejora el atractivo visual <br>Divide el texto <br>Admite el mensaje <br>Debe ser de alta calidad y atractivo | correo electrónico<br>Meta anuncio |
| Pie de página | Contiene información adicional, como detalles de contacto, vínculos de medios sociales, exenciones de responsabilidad y opciones de cancelación de suscripción | email |
| Superposición de texto | El texto de una imagen <br> debe admitir y mejorar el titular y el cuerpo | Meta anuncio |

>[!NOTE]
> 
>Se recomienda incluir campos específicos en el contenido de cada canal para garantizar que GenStudio pueda generar texto para los marcadores de posición de contenido. Consulte [Nombres de campo reconocidos](customize-template.md#recognized-field-names) para ver qué campos se recomiendan para su inclusión.

## Cargar una plantilla

GenStudio acepta plantillas en formato de HTML.

**Para agregar una plantilla**:

1. En _[!DNL Content]_, seleccione la sección **[!UICONTROL Plantillas]**.

1. Haga clic en **[!UICONTROL Agregar plantilla]**.

1. En el panel _[!UICONTROL Agregar la plantilla aprobada]_, busque el archivo de plantilla de HTML o arrastre el archivo de plantilla de HTML al espacio de colocación. Haga clic en **[!UICONTROL Siguiente]**.

1. En el panel _[!UICONTROL Revisar detalles de estructura]_, compruebe que está utilizando la plantilla correcta y que todos los detalles son los esperados. Haga clic en **[!UICONTROL Siguiente]**.

1. En el panel _[!UICONTROL Agregar los detalles de la plantilla]_, asigne un nombre a la plantilla y seleccione un tipo de **[!UICONTROL canal]**.

   El nombre de la plantilla y el tipo de canal son obligatorios.

   * **Meta**: requiere proporción de aspecto
   <!-- **Display ads**: requires Dimensions -->

1. Añada tantos detalles como pueda para mejorar la identificación de la plantilla en las búsquedas y el filtrado.

1. Haga clic en **[!UICONTROL Listo]**.

## Uso de una plantilla

Busque y utilice una plantilla existente para crear experiencias.

**Para crear una experiencia con una plantilla**:

1. En _[!DNL Content]_, seleccione la sección **[!UICONTROL Plantillas]**.

   ![Lista de plantillas de contenido](../../assets/content-templates.png)

1. Seleccione una plantilla para una vista completa y una lista de detalles.

>[!TIP]
>
>Consulte [[!DNL Create] una experiencia de correo electrónico](/help/tutorials/create-email-experience.md) o [[!DNL Create] una experiencia de Meta ad](/help/tutorials/create-meta-ad.md) para ver tutoriales completos con plantillas.

<!--  The create button in Content Template view does not work yet.
1. Click **[!UICONTROL Create Experience]** (paintbrush) from the upper right corner to use the template.
-->
