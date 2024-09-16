---
title: Notas de la versión de Adobe GenStudio for Performance Marketers Beta
description: Obtenga información sobre las últimas funciones y mejoras de Adobe GenStudio para especialistas en marketing de rendimiento.
exl-id: 2ae60dcb-ac95-4ed4-bceb-84b396f7fa4e
source-git-commit: d1904bfe6e5775f71290c2fc7aa185ac2a4a4668
workflow-type: tm+mt
source-wordcount: '0'
ht-degree: 0%

---

# Notas de la versión de Adobe GenStudio for Performance Marketers Beta

Estas notas resaltan los Adobes GenStudio significativos que suponen las correcciones y mejoras realizadas por los especialistas en marketing de rendimiento durante la semana que finalizó el 13 de septiembre.

## Mejoras

* El selector de contenido [!DNL Create] se ha refactorizado para mejorar la carga de recursos. <!-- GS-2586 -->

## Problemas conocidos

Los siguientes problemas conocidos están programados para su resolución en la versión de GenStudio for Performance Marketers GA.

* Los problemas de latencia intermitente afectan algunas operaciones de lienzo de [!DNL Create]. <!-- GS-5203 -->

* La generación de correo electrónico genera un correo electrónico incompleto. **Solución alternativa**: Actualice la página y vuelva a crearla. <!-- GS-5209 -->

* Las plantillas se pueden cargar, pero no ver. **Solución alternativa**: cree o cargue un recurso e introduzca un nombre de grupo de recursos en el campo **[!UICONTROL Campañas]**. Al asignar el recurso a [!DNL Campaign] se agrega el valor de metadatos del nombre del grupo. A continuación, vuelva a cargar la plantilla. <!-- GS-4815 -->

* Faltan miniaturas de campaña en [!DNL Insights]. <!-- GS-4648 -->

* Los usuarios deben iniciar sesión dos veces en una cuenta de Meta Ads de canal cuando también inicien sesión en Facebook. **Solución alternativa**: cierre la sesión de Facebook antes de iniciar sesión en una cuenta de Meta Ads de canal. <!-- GS-4806 -->

### Mejoras adicionales y problemas corregidos

* El lienzo [!DNL Create] ahora procesa correctamente las imágenes de los Meta Ads. <!-- GS-4864 -->

* Aunque pueden existir discrepancias entre las vistas previas del lienzo de Meta Ads y las vistas exportadas, las experiencias exportadas funcionan según lo esperado. <!-- GS-4492 4401 -->

* Las imágenes cargadas ahora incluyen las etiquetas inteligentes esperadas. <!-- GS-4856 -->

* El archivo CSV de exportación de Meta Ads ahora contiene imágenes según lo esperado. Anteriormente, el archivo ZIP contenía el archivo de exportación CSV y archivos NULL en lugar de imágenes.  <!-- GS-5107 -->

* Los usuarios ahora pueden escribir texto en el campo **[!UICONTROL Cargado por]** de la vista de detalles de la plantilla según lo esperado. Anteriormente, el icono de carga impedía que los usuarios introdujeran texto. <!-- GS-4887 -->

* Una vez eliminada la marca, los usuarios ya no se redirigen a la Vista de detalles. <!-- GS-2663 -->

* Los editores ya no reciben el siguiente error al enviar variantes para su revisión y aprobación: `You have no access to view comments on this Object`. <!-- GS-5140 -->

* Se ha actualizado la plantilla de correo electrónico utilizada por el flujo de trabajo de revisión y aprobaciones. <!-- GS-5239 -->

* GenStudio ahora muestra un mensaje de error cuando se produce un error de red durante la carga del selector de plantillas. <!-- GS-4682 -->

* Se han resuelto problemas al navegar desde un recurso, experiencia o tarjeta de plantilla al objeto seleccionado. <!-- GS-4390 -->

* La ventana emergente _Agregar Assets_ ahora está localizada cuando se abre desde Crear lienzo.  <!-- GS-4867 -->

* La validación de marca ahora se activa para las variantes regeneradas. Anteriormente, si un editor regeneraba las variantes de un borrador existente, la validación no se activaba. <!-- GS-3971 -->

## Versiones anteriores de Beta

Las versiones anteriores de Beta incluían los siguientes aspectos destacados y correcciones.

### Características destacadas

* GenStudio ahora admite la opción de obtener una vista previa de los recursos multimedia en [!DNL Insights] vistas de tabla y galería. Las miniaturas de vídeo incluyen un botón **Reproducir** con la opción silenciar. <!-- GS-4398 -->

* Las directrices de canal de instagram y Facebook se han combinado en las directrices de marca Meta.

* [!DNL Create] Los elementos de navegación de lienzo se han optimizado. La página de aterrizaje [!DNL Create] muestra el panel de navegación izquierdo, pero los usuarios ahora usan el botón **[!UICONTROL Atrás]** para desplazarse a este espacio desde otras [!DNL Create] áreas de trabajo.

* Los elementos de navegación se han mejorado para permitir el enfoque del usuario mientras realiza tareas en todo el producto, incluidas estas áreas de producto:

   * Detalles de recurso, experiencia y plantilla en [!DNL Content]
   * Detalles de experiencia, recurso y atributo en [!DNL Insights]
   * Detalles de marca en [!DNL Brands]
   * Detalles de producto y persona en Productos y personas

* Los usuarios ya no necesitan hacer clic en el botón **[!UICONTROL Actualizar]** para ver las actualizaciones de las experiencias en [!DNL Content].

* La página _Detalles de la experiencia_ ahora procesa las miniaturas de recursos externos como HTML.

* Se ha mejorado la latencia de la interfaz de usuario después de agregar o eliminar Assets y Experiencias.

* Las vistas previas de plantilla ahora incluyen texto predeterminado más descriptivo. Ver [Personalizar una plantilla](https://experienceleague.adobe.com/en/docs/genstudio/user-guide/content/templates/customize-template#template-preview).

* **Puntuación de validación basada en porcentajes**: La validación de marca ahora muestra la puntuación de validación de marca como un porcentaje en lugar de un valor de aprobado/suspenso. (fijo: 16/8)

* **Interfaz de extracción de marca actualizada**: La extracción de marca ahora muestra la finalización del proceso de extracción como porcentaje. (fijo: 16/8)

* **Carga incremental de la marca durante la extracción**: Las directrices de marca ahora se cargan gradualmente en la interfaz de usuario. (fijo: 16/8)

* **Creación de correo electrónico de varias secciones**: los usuarios ahora pueden crear correos electrónicos compuestos por titulares, imágenes, cuerpos y elementos de CTA independientes. (fijo: 16/8)

* **Cambio de tamaño de MetaAds**: los editores pueden cambiar el tamaño de las proporciones de aspecto de MetaAd. (fijo: 16/8)

* **Cuentas limitadas de inicio de sesión de [!DNL Insights]**: el inicio de sesión de [!DNL Insights] ahora solo admite una cuenta por cliente. (fijo: 16/8)

### Mejoras adicionales y problemas corregidos

* La ventana emergente _Agregar Assets_ ahora está localizada según lo esperado. <!-- GS-3834 -->

* Se han resuelto los problemas con la escala de la plantilla de experiencia Meta ads. <!-- GS-4174 -->

* Los campos de texto del archivo de exportación CSV para correos electrónicos de varias partes ahora se ordenan según lo esperado. <!-- GS-4013 -->

* El campo de búsqueda [!DNL Content] ya no desaparece cuando un usuario presiona repetidamente la tecla **Retroceso** para borrar el texto del campo de búsqueda.  <!-- GS-4543 -->

* GenStudio para especialistas en marketing de rendimiento ahora carga a los usuarios como se espera cuando un colaborador agrega una mención `@` a un comentario. Anteriormente, no se cargaban los usuarios y se mostraba un error: `Unable to load users. Refresh the page`. <!-- GS-4113 -->

* GenStudio ya no muestra el mensaje **Se produjo un error** cuando un editor hace clic en **Seleccionar contenido** durante la creación del correo electrónico en el área de mensajes. <!-- GS-4879 -->

* El nombre de la ubicación de la fuente de página _Detalles de experiencia_ ahora especifica la fuente de Facebook o Instagram. (fijo: 16/8)

* Ahora, el recorte de imágenes y vídeos de mayor tamaño es coherente cuando el usuario navega de la vista _Información general del recurso_ a la vista _Detalle del recurso_. (fijo: 16/8)

* El recuento de resultados de búsqueda de la pantalla Atributos ya no muestra `0 of` antes de que un usuario inicie sesión. (corregido el 16 de agosto) <!-- GS-3665 -->

* Al hacer clic en el campo de recuento **[!UICONTROL [!DNL Insights]]** > **[!UICONTROL Recurso]**, ya no se borra la configuración de búsqueda y filtrado. (corregido el 16 de agosto) <!-- GS-3476 -->

* GenStudio muestra un error cuando un usuario intenta escribir credenciales en la vista [!DNL Insights]. (corregido el 29 de agosto) <!-- GS-4689 -->

* La carga de las directrices de marca falla debido a problemas con la plataforma de almacenamiento de ACP. (corregido el 22 de agosto) <!-- GS-4369 -->

* El menú desplegable del área Preguntar [!DNL Brands] muestra un control de número al final de la lista [!DNL Brands] durante la creación del correo electrónico. (corregido el 22 de agosto) <!-- GS-4077 -->
