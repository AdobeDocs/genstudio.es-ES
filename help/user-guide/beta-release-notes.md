---
title: Notas de la versión de Adobe GenStudio for Performance Marketers Beta
description: Obtenga información sobre las últimas funciones y mejoras de Adobe GenStudio.
source-git-commit: 382026b07e123a1e49813b766f69496f6a8f38eb
workflow-type: tm+mt
source-wordcount: '392'
ht-degree: 2%

---


# Notas de la versión de Adobe GenStudio for Performance Marketers Beta

Estas notas destacan las correcciones y mejoras significativas de los Adobes GenStudio realizadas durante la semana que finalizó el 16 de agosto.

## Características destacadas

El desarrollo de funciones de GenStudio es rápido y continuo. Entre las nuevas funciones destacables se incluyen:

### Marca

El panel de validación de marca se mejoró para mejorar la experiencia del usuario, incluidos estos cambios:

* _Puntuación de validación basada en porcentajes_: La validación de marca ahora muestra la puntuación de validación de marca como un porcentaje en lugar de un valor de aprobado/suspenso.

* _Interfaz de extracción de marca actualizada_: La extracción de marca ahora muestra la finalización del proceso de extracción como porcentaje.

* _Carga incremental de la marca durante la extracción_: Las directrices de marca ahora se cargan gradualmente en la interfaz de usuario.

* _Simplificación del esquema de copia de directrices_: los campos `unique attributes` y `frequent keywords` se han eliminado del esquema de copia de directrices, lo que simplifica el proceso de configuración de las directrices.

* _Generación de imágenes: Selección de categorías_: Los usuarios ahora pueden seleccionar las directrices de imágenes específicas para sus necesidades de regeneración de imágenes.

### Crear

* **Creación de correo electrónico de varias secciones**: los usuarios ahora pueden crear correos electrónicos compuestos por titulares, imágenes, cuerpos y elementos de CTA independientes.

* **Cambio de tamaño de metadatos de anuncios**: los creadores pueden cambiar el tamaño de las proporciones de aspecto de metadatos de anuncios.

### Perspectivas

* **Cuentas de inicio de sesión con información limitada**: el inicio de sesión con información ahora solo admite una cuenta por cliente.

## Mejoras y problemas corregidos

Esta versión incluye las siguientes correcciones adicionales.

### Perspectivas

* El nombre de la ubicación de la fuente de página _Detalles de experiencia_ ahora especifica la fuente de Facebook o Instagram.

* Ahora, el recorte de imágenes y vídeos de mayor tamaño es coherente cuando el usuario navega de la vista _Información general del recurso_ a la vista _Detalles del recurso_.

* El recuento de resultados de búsqueda de la pantalla Atributos ya no muestra `0 of` antes de que un usuario inicie sesión. <!-- GS- 3665 -->

* Al hacer clic en el campo de recuento **[!UICONTROL Insight]** > **[!UICONTROL Asset]**, ya no se borra la configuración de búsqueda y filtrado. <!-- GS-3476 -->

## Problemas conocidos

Los siguientes problemas conocidos se resolverán en la versión de GenStudio for Performance Marketers GA.

### Análisis

* Las acciones activadas por los botones **[!UICONTROL Agregar plantillas]** y **[!UICONTROL Cargar]** no se rastrean actualmente. <!-- GS-3505 -->

### Marca

* Un creador puede publicar correctamente una marca, pero los miembros de la organización no pueden ver la marca. <!-- XI-2197 -->

### Crear

* El recorte de imágenes en los anuncios Meta es inconsistente. <!-- GS-3739 -->

* Las plantillas compuestas de varios grupos de elementos de página no superan la validación de marca. <!-- GS-4037 -->

### Perspectivas

* Los errores de acceso denegado se producen con el extremo `/admin/addOffer` (servicio de aprovisionamiento). **Resuelto el 12/8**. <!-- GS-4047 -->

* **Los valores de gasto a nivel de campaña** no son precisos. Actualmente, los datos no son coherentes entre el Administrador de Facebook Ads y el lago de datos. <!-- GS-3202 -->

### Revisiones y aprobaciones

* Los creadores pueden cambiar los recursos después de la aprobación antes de publicarlos. Estos cambios no se notifican a los aprobadores.
