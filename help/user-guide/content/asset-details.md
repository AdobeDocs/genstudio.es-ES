---
title: Detalles del recurso
description: GenStudio almacena contenido aprobado con metadatos enriquecidos para permitir búsquedas y realizar un seguimiento del rendimiento.
feature: Attributes, Assets
source-git-commit: c8fa0cf1633a5ca0ab94d9a0f33d9b7e7d6d61ed
workflow-type: tm+mt
source-wordcount: '402'
ht-degree: 1%

---


# Detalles del recurso

GenStudio almacena contenido aprobado con metadatos enriquecidos para facilitar la detección y el seguimiento del rendimiento.

Cada recurso (incluidas experiencias y plantillas) tiene _detalles_ asociados (metadatos) que ayudan a identificar, rastrear, utilizar y aprender del rendimiento del contenido.

Los tipos de metadatos de recursos incluyen [metadatos del sistema](#system-metadata) y [metadatos definidos por el usuario](#user-defined-metadata).

## Metadatos del sistema

Algunos metadatos de recursos se recopilan automáticamente cuando se carga un recurso. No puede editar los metadatos predeterminados del sistema.

Los metadatos predeterminados que se almacenan y capturan para un recurso incluyen el nombre del archivo, sus dimensiones, el origen, etc.

### Etiquetas generadas

Cuando los recursos se aprueban y almacenan en [!DNL Content], GenStudio utiliza la IA y las capacidades de aprendizaje automático de Adobe para generar etiquetas basadas en las características del recurso, como el color y el tono, o en palabras clave que identifican las características del recurso. No puede editar etiquetas.

### Metadatos de contenido generados

La información utilizada para generar un nuevo recurso o experiencia se convierte en metadatos, como el mensaje que se utilizó. No puede editar el mensaje una vez aprobado el contenido, pero puede utilizarlo como punto de partida para generar algo nuevo.

## Metadatos definidos por el usuario

Los metadatos definidos por el usuario añaden contexto de marketing al contenido del recurso, lo que permite a los especialistas en marketing comprender mejor cómo utilizar el recurso y interactuar con él.

Al [cargar un recurso](/help/user-guide/content/manage-assets.md#add-assets), puede definir un conjunto de detalles de recurso opcionales que existen en GenStudio como metadatos.

### Detalles de metadatos

La siguiente tabla detalla los metadatos (detalles del recurso) que puede definir al crear un recurso.

| Campo | Descripción | Editable | Requerido |
| ------------- | ----------- | -------- | -------- |
| Nombre de la campaña (nombre del proyecto) | Metadatos predeterminados capturados y almacenados con el recurso | Y | N |
| Nombre de marca | [[!DNL Brands]](/help/user-guide/guidelines/brands.md) se agregó a GenStudio y se publicó para su uso | Y | N |
| [!DNL Products] | [[!DNL Products]](/help/user-guide/guidelines/products.md) se agregó a GenStudio para su uso | Y | N |
| [!DNL Personas] | [[!DNL Personas]](/help/user-guide/guidelines/personas.md) se agregó a GenStudio para su uso | Y | N |
| Canales | Tipos de contenido en GenStudio para los que se utiliza el recurso, como correo electrónico y anuncios Meta | Y | N |
| Periodo de tiempo | Periodo de tiempo para el que se utiliza el recurso, como trimestre, temporada, año, etc. Ejemplo: `Winter 2023` | Y | N |
| Región | Regiones para las que se utiliza el recurso. Ejemplos: `North America`, `APAC`, `Italy` | Y | N |
| Idioma | Idiomas para los que se utiliza el recurso. Ejemplo: `Spanish` | Y | N |
| Palabras clave | Palabras clave utilizadas para identificar el propósito del recurso | Y | N |

## Ver detalles del recurso

**Para ver los detalles del recurso**:

1. En _[!DNL Content]_, seleccione un recurso.

1. En la vista de recursos, revise la sección _[!UICONTROL Detalles]_ a la derecha.

   Si la sección _[!UICONTROL Detalles]_ no está visible, haga clic en el icono **[!UICONTROL Información]** (i).

>[!TIP]
>
>También puede ver detalles de recursos de [!DNL Insights]. [!DNL Insights] proporciona estadísticas de uso y contexto de rendimiento en todas las experiencias. En _[!DNL Insights]_, seleccione la sección **[!UICONTROL Assets]**.

<!-- ## History

Expand the _[!UICONTROL History]_ section to view a timeline of approvals and activity.

list other activity, show screenshot?
-->
