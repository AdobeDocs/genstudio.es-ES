---
title: Notas de la versión de Adobe GenStudio for Performance Marketers Beta
description: Obtenga información sobre las últimas funciones y mejoras de Adobe GenStudio para especialistas en marketing de rendimiento.
exl-id: 2ae60dcb-ac95-4ed4-bceb-84b396f7fa4e
source-git-commit: 2861dd76dde9428e0c39af18c1d5e21dc2b32b91
workflow-type: tm+mt
source-wordcount: '710'
ht-degree: 0%

---

# Notas de la versión de Adobe GenStudio for Performance Marketers Beta

Estas notas resaltan los Adobes GenStudio significativos que suponen las correcciones y mejoras realizadas por los especialistas en marketing de rendimiento durante la semana que finalizó el 6 de septiembre.

## Nuevas funciones

* GenStudio ahora admite la opción de obtener una vista previa de los recursos multimedia en [!DNL Insights] vistas de tabla y galería. Las miniaturas de vídeo incluyen un botón **Reproducir** con la opción silenciar. <!-- GS-4398 -->

## Problemas conocidos

Los siguientes problemas conocidos están programados para su resolución en la versión de GenStudio for Performance Marketers GA.

* Los editores encuentran ocasionalmente un mensaje de error &quot;Se produjo un error&quot; en [!DNL Create Canvas] durante la generación de la imagen. **Solución alternativa**: si el error se repite, el usuario puede cerrar la sesión y luego volver a iniciarla en GenStudio y volver a generar la imagen.  <!-- GS-4813 -->

* [!DNL Create Canvas] procesa las imágenes de los anuncios Meta incorrectamente. <!-- GS-4864 -->

* Las plantillas se pueden cargar, pero no ver. <!-- GS-4815 -->

* Existe discrepancia entre las vistas previas del lienzo de MetaAds y las vistas exportadas. <!-- GS-4492 4401 -->

* Faltan miniaturas de campaña en [!DNL Insights]. <!-- GS-4648 -->

* Actualmente, los usuarios pueden seleccionar recursos pequeños que requieren cambiar de tamaño, pero no se admite la ampliación de dichos recursos. <!-- GS-3131 -->

* Los usuarios deben iniciar sesión dos veces en una cuenta de Meta Ads de canal cuando también inicien sesión en Facebook. **Solución alternativa**: cierre la sesión de Facebook antes de iniciar sesión en una cuenta de Meta Ads de canal.

* Las imágenes cargadas no siempre incluyen las etiquetas inteligentes esperadas. <!-- GS-4856 -->

### Mejoras adicionales y problemas corregidos

* La ventana emergente _Agregar Assets_ ahora está localizada según lo esperado. <!-- GS-3834 -->

* Se han resuelto los problemas con la escala de la plantilla de experiencia Meta ads. <!-- GS-4174 -->

* Los campos de texto del archivo de exportación CSV para correos electrónicos de varias partes ahora se ordenan según lo esperado. <!-- GS-4013 -->

* El campo de búsqueda [!DNL Content] ya no desaparece cuando un usuario presiona repetidamente la tecla **Retroceso** para borrar el texto del campo de búsqueda.  <!-- GS-4543 -->

* GenStudio ahora carga a los usuarios como se espera cuando un colaborador agrega una mención @ a un comentario. Anteriormente, GenStudio no cargaba usuarios y mostraba este error: `Unable to load users. Refresh the page`. <!-- GS-4113 -->

* GenStudio ya no muestra el mensaje **Se produjo un error** cuando un editor hace clic en **Seleccionar contenido** durante la creación del correo electrónico en el área de mensajes. <!-- GS-4879 -->

## Versiones anteriores de Beta

Las versiones anteriores de Beta incluían los siguientes aspectos destacados y correcciones.

### Características destacadas

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

* **Cambio de tamaño de metadatos de anuncios**: los editores pueden cambiar el tamaño de las proporciones de aspecto de metadatos de anuncios. (fijo: 16/8)

* **Cuentas limitadas de inicio de sesión de [!DNL Insights]**: el inicio de sesión de [!DNL Insights] ahora solo admite una cuenta por cliente. (fijo: 16/8)

### Mejoras adicionales y problemas corregidos

* El nombre de la ubicación de la fuente de página _Detalles de experiencia_ ahora especifica la fuente de Facebook o Instagram. (fijo: 16/8)

* Ahora, el recorte de imágenes y vídeos de mayor tamaño es coherente cuando el usuario navega de la vista _Información general del recurso_ a la vista _Detalle del recurso_. (fijo: 16/8)

* El recuento de resultados de búsqueda de la pantalla Atributos ya no muestra `0 of` antes de que un usuario inicie sesión. (corregido el 16 de agosto) <!-- GS-3665 -->

* Al hacer clic en el campo de recuento **[!UICONTROL [!DNL Insights]]** > **[!UICONTROL Recurso]**, ya no se borra la configuración de búsqueda y filtrado. (corregido el 16 de agosto) <!-- GS-3476 -->

### Problemas conocidos resueltos en versiones anteriores de Beta

* GenStudio muestra un error cuando un usuario intenta escribir credenciales en la vista [!DNL Insights]. (corregido el 29 de agosto) <!-- GS-4689 -->

* La carga de las directrices de marca falla debido a problemas con la plataforma de almacenamiento de ACP. (corregido el 22 de agosto) <!-- GS-4369 -->

* El menú desplegable del área Preguntar [!DNL Brands] muestra un control de número al final de la lista [!DNL Brands] durante la creación del correo electrónico. (corregido el 22 de agosto) <!-- GS-4077 -->
