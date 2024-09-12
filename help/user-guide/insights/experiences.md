---
title: Resumen de experiencias
description: Consulte una descripción general de la participación del cliente, el presupuesto y los gastos para obtener experiencias y el rendimiento de los recursos en Adobe GenStudio para especialistas en marketing de rendimiento.
feature: Insights, Experiences
source-git-commit: 70ce82b026b2ee1f088cda75caa22bbb1b9c5ef3
workflow-type: tm+mt
source-wordcount: '708'
ht-degree: 0%

---


# Resumen de experiencias

La vista [!DNL Insights] _[!UICONTROL Experiencias]_ muestra una lista de anuncios y experiencias para la cuenta de anuncio de canal conectada.

La tabla [!UICONTROL Experiencias] está organizada con [!UICONTROL nombres de anuncios]. El icono de filtro (canal) situado encima de la parte izquierda de la tabla abre el menú **[!UICONTROL Filtro]**, en el que puede seleccionar entre las listas [!UICONTROL Cuenta] y [!UICONTROL Campaña] para filtrar los nombres de los anuncios de la tabla.

![Filtro y tabla de experiencias](../../assets/insights-experiences-filter.png)

## Detalles del anuncio

Al seleccionar un nombre de anuncio, puede ver las métricas y los atributos de rendimiento del anuncio, que le permiten analizar las métricas de una experiencia en función de su ubicación en un intervalo de fechas especificado.

La vista de detalles incluye un anuncio general de métricas `click-through rate`, `cost per click` y la cantidad del presupuesto que se ha `spent` en el anuncio. Dado que los anuncios pueden tener varias ubicaciones, como una fuente o un banner, puede ver un desglose de las mismas métricas para cada ubicación de publicidad. Utilice las flechas izquierda y derecha debajo de **[!UICONTROL Rendimiento por ubicación del anuncio]** para recorrer las métricas de ubicación del anuncio.

![Detalles de anuncios con métricas y ubicaciones de anuncios](../../assets/insights-ad-details.png)

### Atributos de texto

Debajo de la vista previa del anuncio hay una lista de [!UICONTROL atributos de texto] asociados con el anuncio. Cuando los recursos y las experiencias se aprueban y almacenan en [!DNL Content], GenStudio para especialistas en marketing de rendimiento genera etiquetas en función de sus características inherentes. Consulte [Detalles del recurso](../content/asset-details.md#system-metadata) para obtener detalles acerca de los metadatos del sistema.

### Ubicaciones de anuncios

En el momento en que creó una campaña con Meta Ads, es posible que haya seleccionado dónde ejecutar los anuncios en función del [objetivo](channels.md#objectives) de la campaña. Las ubicaciones de anuncios amplían el alcance de audiencia de su anuncio.

GenStudio para especialistas en marketing de rendimiento admite formatos de anuncio como fuentes de recursos, anuncios de vínculos y una sola imagen o vídeo. A continuación se muestra una lista de formatos de anuncios por plataforma:

| Instagram | Facebook/Meta | Messenger | Audience Network |
| --- | --- | --- | --- |
| Explorar<br>Explorar la página principal<br>Explorar la página principal de Grid<br>Feed<br>Carretes<br>Fuente de perfiles<br>Buscar<br>Tienda<br>Historias | Exploración empresarial<br>Fuente<br>Vídeo en el flujo<br>Mercado<br>Carretes<br>Superposición de carretes<br>Columna derecha<br>Buscar<br>Historias<br>Fuentes de vídeo<br>Anuncios en carretes de Facebook | Bandeja de entrada<br>Historias | Nativo, titular e intersticial<br>Nativo<br>Vídeo con recompensa |

## Métricas

Las métricas de perspectivas pueden ayudarle a evaluar qué experiencias contribuyen al éxito de una campaña y qué ubicaciones de anuncios son las más efectivas.

### Detalles de métricas

La siguiente tabla proporciona definiciones y perspectivas para métricas clave de marketing digital en la vista [!UICONTROL Experiencias]. Cada métrica incluye una breve definición en relación con los nombres de los anuncios, cómo se calcula la métrica y una o más perspectivas para ayudar a comprender su importancia e impacto en una experiencia.

| Métrica | Definición | Insight |
| ---------------------- | ----------------------------- | -------------------------------- |
| **[!UICONTROL Campaña]** | Una campaña es un conjunto de experiencias y anuncios diseñados para lograr un objetivo específico. | |
| **[!UICONTROL Ubicaciones de anuncios]** | Un recuento de ubicaciones de anuncios para la publicidad o experiencia. | Las ubicaciones de anuncios aumentan el alcance de audiencia. |
| **[!UICONTROL Assets]** | Un recuento de los recursos utilizados en el anuncio o la experiencia. | |
| **[!UICONTROL Impresiones]** | Las impresiones se contabilizan cada vez que el contenido se carga en pantalla, independientemente de la interacción o la visualización. | Un recuento alto de impresiones puede indicar una visibilidad amplia, pero para obtener una perspectiva de rendimiento real, considere la posibilidad de con otras métricas de participación. |
| **[!UICONTROL Clics]** | Número de veces que los usuarios interactúan con un elemento en el que se puede hacer clic en un anuncio. Los clics pueden incluir hacer clic en un perfil de página o una imagen, publicar reacciones, compartir, comentar o expandir medios a pantalla completa. | Un alto número de clics indica un fuerte interés y participación en el contenido, que puede ser eficaz y llegar a la audiencia adecuada. |
| **[!UICONTROL CTR]** | Porcentaje (%) de usuarios que hicieron clic en un anuncio.<br>**Cálculo**: `clicks` dividido por `impressions` | Una alta tasa de clics indica que el contenido es muy relevante y motivador para la audiencia en cuanto a mensajería y diseño, y que se dirige de manera efectiva a los intereses de la audiencia. |
| **[!UICONTROL CPM]** | Medición del rendimiento del coste ($) por cada mil impresiones de publicidad.<br>**Cálculo**: importe total `spent` dividido por alcance y luego multiplicado por 1000 | Un valor bajo puede indicar una visibilidad rentable, especialmente cuando se asocia con una tasa de pulsaciones alta. |
| **[!UICONTROL CPC]** | Coste promedio ($) asociado con cada clic en una experiencia.<br>**Cálculo**: importe total `spent` dividido entre `clicks` | Unos costes medios menores pueden indicar un gasto publicitario rentable, especialmente en comparación con un aumento de las conversiones. |
| **[!UICONTROL Gasto]** | La cantidad gastada del presupuesto durante un período de tiempo determinado. | Un gasto elevado en un período corto puede indicar un uso rápido, lo que podría dar lugar a un agotamiento prematuro de los recursos. Realice un seguimiento de la cantidad gastada con métricas de rendimiento clave para ayudar a monitorizar la rentabilidad general de la inversión. |
