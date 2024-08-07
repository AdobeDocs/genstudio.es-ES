---
title: Escribir indicadores efectivos
description: Aprenda a escribir mensajes efectivos para GenStudio.
feature: Prompt, Generative AI, Brands Service, Personas Service, Products Service, Guidelines
source-git-commit: d7de679ce310dcdcec4a1b5ea814b2ca8b1fc413
workflow-type: tm+mt
source-wordcount: '484'
ht-degree: 0%

---


# Escribir indicadores efectivos

La comunicación con la IA generativa es esencial para trabajar de forma eficaz en GenStudio.

GenStudio proporciona un aviso de IA generativo cada vez que se ofrece la oportunidad de crear o modificar un recurso. Los componentes de un mensaje eficaz deben incluir lenguaje descriptivo, ejemplos e información que no se proporciona a través de las directrices configuradas.

Como práctica recomendada, proporcione a GenStudio su información de marca mediante [directrices](/help/user-guide/guidelines/overview.md) para que pueda aprovechar al máximo la IA generativa a fin de producir contenido alineado con la marca.

## Lenguaje descriptivo

Puede utilizar el lenguaje natural para articular sus ideas y crear experiencias. El mensaje guía la IA para generar contenido de canal personalizado e imágenes que complementen su visión. Cuantos más detalles proporcione, mayores serán las posibilidades de producir una imagen o una experiencia que satisfaga sus necesidades. Utilice un lenguaje claro y descriptivo para proporcionar tantos detalles como sea posible:

- Para **imágenes**, usa palabras que describan ambiente, humor, color, composición y estilo.
- Para **copiar**, usa palabras que describan la audiencia, el propósito, las nuevas descripciones de características, los ejemplos y las acciones.

A continuación se muestra un ejemplo de mensaje que articula información sobre la intención, la audiencia de destino y el estilo.

```bash
Write an email to motivate infrequent users of Photoshop to follow an in-app tutorial that teaches them to combine elements of two photos into a beautiful work of art. Highlight the generative AI capabilities of Photoshop and use references to natural imagery.
```

+++Ver resultados de ejemplo

![tres correos electrónicos generados](/help/assets/sample-email.png)

+++

## Criterios de solicitud

En GenStudio [[!DNL Create]](/help/user-guide/create/overview.md), puede usar **[!UICONTROL Criterios de solicitud]** ([_Parámetros_](/help/user-guide/create/overview.md#parameters) y un mensaje) en el área de solicitud para agregar detalles mediante la selección y mejorar la interpretación de IA.

Para [correos electrónicos](/help/tutorials/create-email-experience.md), los criterios de solicitud pueden incluir la adición de [directrices](/help/user-guide/guidelines/overview.md) en _Parámetros_, la carga de un recurso para utilizarlo en las variantes de correo electrónico y una solicitud descriptiva. Para un [Meta ad](/help/tutorials/create-meta-ad.md), los criterios de solicitud pueden incluir una directriz de marca en _Parámetros_, la selección o carga de un recurso existente, la configuración relacionada con imágenes o recursos como la proporción de aspecto y un mensaje. El verdadero poder comienza con [configurar las directrices de GenStudio](/help/user-guide/guidelines/add-guidelines.md).

>[!NOTE]
>
>Si se agregan directrices en _Parameters_ en el área de solicitud, no necesita incluir referencias a ellas en la solicitud. GenStudio aprovechará [!DNL Brands], [!DNL Products] y [!DNL Personas] en la generación de contenido.

### Directrices

Las directrices de GenStudio ayudan a la IA generativa a personalizar la composición de los recursos de GenStudio. Cuando se le presenten criterios de solicitud, puede elegir un [[!DNL Brand]](/help/user-guide/guidelines/brands.md), un [[!DNL Persona]](/help/user-guide/guidelines/personas.md) y un [[!DNL Product]](/help/user-guide/guidelines/products.md) de entre las directrices configuradas.

>[!TIP]
>
>Usted controla cómo y cuándo GenStudio usa sus directrices de [!DNL Brand]. Consulte [Directrices](/help/user-guide/guidelines/overview.md) para obtener información sobre cómo configurar y administrar las directrices de marca.

## Inténtelo de nuevo

La solicitud es un proceso iterativo. Si los resultados no cumplen con sus expectativas, revise el mensaje y realice algunos cambios o agregue más detalles. Puede restringir el mensaje proporcionando una dirección URL como ejemplo o una fuente para obtener más información.

```bash
Write an email to motivate infrequent users of Photoshop to follow an in-app tutorial that teaches them to combine elements of two photos into a beautiful work of art. Highlight the generative AI capabilities of Photoshop and use references to natural imagery.

Use information from https://www.adobe.com/products/photoshop.html to inspire users with the latest features.
```

O bien, puede pegar en secciones de un informe de campaña. Incluso puede solicitar que GenStudio evite determinadas palabras, elementos o temáticas.

## Prácticas recomendadas

Algunas prácticas recomendadas sencillas para crear indicadores eficaces en GenStudio:

- Sea específico y proporcione detalles sobre qué hacer y qué no hacer.
- Proporcionar contexto mediante referencias externas.
- Aproveche las directrices de GenStudio.
- Revise y ajuste las directrices regularmente.
- Iterar y refinar.
- Aprenda con la experimentación.
