---
title: Trabajo con plantillas
description: Descubra cómo utilizar las plantillas de forma eficaz para optimizar el proceso creativo en Adobe GenStudio para los especialistas en marketing de rendimiento.
feature: Templates, Content
source-git-commit: 192568a65bbd5c8c2e9cfc050462eb2c3465245d
workflow-type: tm+mt
source-wordcount: '682'
ht-degree: 1%

---


# Trabajo con plantillas

GenStudio para especialistas en marketing de rendimiento permite a los creadores de contenido producir rápidamente contenido de marketing coherente dentro de la marca mediante _plantillas_. Una plantilla reduce significativamente el tiempo y el esfuerzo necesarios para generar contenido nuevo al proporcionar un punto de partida que incluye diseños y elementos de diseño preconfigurados.

## Elementos de plantilla

Una plantilla es un conjunto de instrucciones definidas con HTML y CSS en línea que se pueden utilizar para generar una experiencia de correo electrónico o Meta ad.

A continuación se muestra una lista de los elementos que se utilizan en las plantillas y algunos detalles sobre sus características.

- **Encabezado previo**

   - Actúa como una línea de asunto secundaria en un correo electrónico, mejorando la línea de asunto principal
   - Entre 40 y 50 caracteres
   - Visible en la bandeja de entrada junto al asunto antes de abrir el correo electrónico
   - Se utiliza en plantillas de correo electrónico

- **Encabezado**

   - Sección superior del correo electrónico que ve el destinatario al abrir el correo electrónico
   - Establece el tono y proporciona contexto para el contenido incluido
   - Se utiliza en plantillas de correo electrónico

- **Titular**

   - Primer contenido que ve el destinatario
   - Debería ser convincente para captar interés
   - Se utiliza en plantillas de metadatos

- **Cuerpo**

   - Área de contenido principal donde se transmite el mensaje principal
   - Capaz de incluir texto, imágenes y otros medios
   - Se utiliza en plantillas de correo electrónico y metadatos.

- **CTA (llamada a la acción)**

   - Anima al destinatario a realizar una acción específica, como hacer clic en un vínculo o realizar una compra
   - Se utiliza en plantillas de correo electrónico y metadatos.

- **Imágenes**

   - Aumenta el atractivo visual
   - Dividir texto
   - Apoyar el mensaje
   - Debe ser de alta calidad y llamativo
   - Se utiliza en plantillas de correo electrónico y metadatos.

- **Pie de página**

   - Sección inferior que contiene contenido adicional, como detalles de contacto, vínculos de medios sociales, exenciones de responsabilidad legal y opciones de cancelación de suscripción
   - Se utiliza en plantillas de correo electrónico

- **Superposición de texto**

   - Texto en una imagen
   - Utilice para apoyar y mejorar el titular y el cuerpo
   - Se utiliza en plantillas de metadatos

>[!TIP]
>
>Vea los [nombres de campo reconocidos](customize-template.md#recognized-field-names) que GenStudio para especialistas en marketing de rendimiento admite para plantillas de cada tipo de canal.

## Configuración de directrices de canal

Se recomienda configurar [directrices de canal](../guidelines/brands.md#channel-guidelines) para cada marca antes de usar las plantillas en GenStudio para especialistas en marketing de rendimiento. Las directrices de canal influyen directamente en el tipo de contenido generado al utilizar la plantilla. Por ejemplo, puede establecer límites de caracteres en el cuerpo de un correo electrónico.

![Especificaciones del cuerpo](/help/assets/channel-email-body.png)

## Personalizar plantilla

Usted [personaliza su plantilla](customize-template.md) para usarla en GenStudio para especialistas en marketing de rendimiento mediante la inserción de marcadores de posición de contenido, o campos, que la inteligencia artificial aplicada generativa utiliza para insertar contenido. GenStudio para especialistas en marketing de rendimiento reconoce ciertos campos, como el campo `body`, y cumple las directrices de canal configuradas para la marca seleccionada.

>[!TIP]
>
>Siga [las directrices de accesibilidad para crear plantillas](accessibility-for-templates.md) para que pueda llegar a una mayor audiencia y proporcionar una experiencia óptima.

## Cargar una plantilla

Use [Personalizar plantillas](customize-template.md) como guía al preparar una plantilla para GenStudio para especialistas en marketing de rendimiento. Consulte [directrices de accesibilidad para plantillas](accessibility-for-templates.md) para obtener instrucciones sobre cómo proporcionar una mejor experiencia a todas las audiencias.

**Para agregar una plantilla**:

1. En _[!DNL Content]_, seleccione la sección **[!UICONTROL Plantillas]**.

1. Haga clic en **[!UICONTROL Agregar plantilla]**.

1. En el panel _[!UICONTROL Agregar la plantilla aprobada]_, busque el archivo de plantilla de HTML o arrastre el archivo de plantilla de HTML al espacio de colocación. Haga clic en **[!UICONTROL Siguiente]**.

1. En el panel _[!UICONTROL Revisar campos detectados]_, revise los campos detectados. Compruebe que está utilizando la plantilla correcta y que todos los detalles son los esperados. Haga clic en **[!UICONTROL Siguiente]**.

   Ejemplo de previsualización para una plantilla de correo electrónico:

   ![Campos de vista previa detectados](../../assets/template-detected-fields.png){width="650"}

   >[!TIP]
   >
   >Si la plantilla no es correcta, haga clic en **[!UICONTROL Atrás]** y vuelva al paso anterior. Cargue el archivo de plantilla corregido.

1. En el panel _[!UICONTROL Proporcionar detalles de plantilla y cargar]_, asigne un nombre a la plantilla y seleccione un tipo de **[!UICONTROL canal]**.

   El nombre de la plantilla y el tipo de canal son obligatorios. Los requisitos adicionales pueden incluir:

   - **Meta**: requiere proporción de aspecto
   <!-- - **Display ads**: requires Dimensions -->

1. Añada tantos detalles como pueda para mejorar la identificación de la plantilla en las búsquedas y el filtrado.

1. Haga clic en **[!UICONTROL Listo]**.

## Creación con una plantilla

Busque y utilice una plantilla existente en GenStudio para especialistas en marketing de rendimiento para crear más experiencias.

**Para crear una experiencia con una plantilla**:

1. En _[!DNL Content]_, seleccione la sección **[!UICONTROL Plantillas]**.

   ![Lista de plantillas de contenido](../../assets/content-templates.png){width="650" zoomable="yes"}

1. Seleccione una plantilla para una vista completa y una lista de detalles.

1. Haga clic en **[!UICONTROL Crear experiencia]** (pincel) en la esquina superior derecha para usar la plantilla.

1. Continúe con [tutoriales](/help/tutorials/tutorials.md) para crear una experiencia.
