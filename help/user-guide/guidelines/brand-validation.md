---
title: Validación de marca en GenStudio
description: Descubra cómo funciona el sistema de validación de marca integrado en GenStudio.
feature: Brands Service, Guidelines
source-git-commit: c8fa0cf1633a5ca0ab94d9a0f33d9b7e7d6d61ed
workflow-type: tm+mt
source-wordcount: '599'
ht-degree: 0%

---


# Validación de marca

En GenStudio, la validación de marca es un componente esencial que funciona en colaboración con la funcionalidad y las directrices generativas de IA: [[!DNL Brands]](/help/user-guide/guidelines/brands.md), [[!DNL Products]](/help/user-guide/guidelines/products.md) y [[!DNL Personas]](/help/user-guide/guidelines/personas.md). Garantiza que todo el contenido se ajuste a la identidad de su marca.

GenStudio valida la marca en varios aspectos, entre ellos:

* Directrices de marca específicas para cada cliente
* Copiar directrices para diferentes plataformas de canal
* Consideraciones éticas relacionadas con el género, la etnia, la raza, el estado de discapacidad y la edad en el contenido generado por IA

## Comprobación de directrices de marca

Se puede acceder a un resumen de la información de validación de marca de cada variante de contenido generada a través del icono _Comprobación de las directrices de marca_ junto a cada variante en el lienzo.

La _comprobación de directrices de marca_ muestra el porcentaje de cumplimiento de la [marca](brands.md). El porcentaje se calcula como el número de [directrices](overview.md) que superaron la validación en comparación con el número de directrices probadas.

Haga clic en el icono para ver qué directrices son compatibles con su marca y cuáles deben revisarse.

Ver [Mejorar la alineación de la marca](#improve-brand-alignment).

## Panel de validación de marca

El _panel de validación de marca_ proporciona información detallada sobre la validación de marca e ilustra las oportunidades de mejora para cada fragmento de variante.

El _panel de validación de marca_ muestra información para:

* **Correo electrónico**:
   * Fragmento de línea de asunto
   * Fragmento de preencabezado
   * Fragmento de encabezado
   * Fragmento de cuerpo
   * Fragmento CTA (llamada a la acción)
   * Directrices de voz de marca
* **Meta ad**:
   * Fragmento de titular
   * Fragmento de copia de cuerpo
   * Fragmento CTA (llamada a la acción)
   * Fragmento de texto en imagen

Ver [Mejorar la alineación de la marca](#improve-brand-alignment).

### Filter

En el _panel de validación de marca_ puede filtrar qué directrices se muestran. Haga clic en el icono de filtro en la parte superior del panel para ver:

* **Directrices con errores**—_Mostrar directrices con errores_ solo muestra las directrices que no superaron la validación de marca.
* **Todas las directrices**—_Se han producido errores al mostrar y se han aprobado las directrices_. Muestra todas las directrices para las que se miden las variantes.
* **Directrices aprobadas**—_Mostrar las directrices aprobadas_ solo muestra las directrices que han superado la validación de marca.

<!-- The _Brand validation panel_ has different areas of focus for each content channel:

* Email - brand voice and channel compliance
* Images - application photography restrictions and other considerations -->

## Mejorar la alineación de marca

Para maximizar la eficacia del contenido generado y mantener una identidad de marca coherente, use _Comprobación de las directrices de marca_ y el _Panel de validación de marca_. Puede modificar manualmente fragmentos específicos para alinearlos con las [directrices de marca](brands.md).

**Para mejorar la alineación de marca de las variantes de contenido generadas**:

1. Haga clic en el icono **[!UICONTROL [!DNL Brand]directrices para comprobar]** de una variante individual.

   Vea un resumen del rendimiento de esa variante específica (directrices que aprueban la validación de la marca y las que necesitan revisión) cuando se compara con su marca.

1. Para obtener los detalles de los fragmentos y las directrices que deben mejorarse, haga clic en **[!UICONTROL Revisar]** _o_ haga clic en el icono Validación de marca en la barra de menú superior para abrir el _Panel de validación de marca_.

   Vea todos los fragmentos y directrices de marca que requieren su atención. El fragmento resaltado en el panel corresponde al fragmento resaltado en la variante generada en el lienzo.

   >[!NOTE]
   >
   > La directriz _Brand voice_ indicada en el _panel de validación de marca_ se aplica a toda la variante, no a un fragmento individual. Se resalta toda la variante de contenido para sugerir mejoras.

1. Revise manualmente los fragmentos de variante para lograr la alineación más sólida con su marca.

1. Después de hacer las revisiones necesarias, haz clic en **[!UICONTROL Volver a comprobar]** para validar los cambios y asegurarte de que estén más alineados con la identidad de tu marca.

   El proceso de validación de marca se volverá a ejecutar. Si el fragmento o la guía supera la validación, aparecerá una marca de verificación verde para ese fragmento en el _panel de validación de marca_. El porcentaje del icono _Comprobación de la directriz de marca_ para la variante revisada también muestra su progreso.

1. Continúe revisando los fragmentos para asegurarse de que toda la variante aprueba la validación de marca.

   Desplácese entre las directrices del _panel de validación de marca_ con los botones **[!UICONTROL Siguiente]** y **[!UICONTROL Anterior]**.

1. En la parte superior del _panel de validación de marca_, desplácese por cada variante con las flechas (por ejemplo, use la flecha para pasar de `Email 1` a `Email 2`) y continúe revisando los fragmentos para adherirse mejor a su marca.

   Consulte [Directrices de voz de marca](/help/user-guide/guidelines/brands.md#brand-voice-guidelines) para obtener más información sobre las directrices consideradas.
