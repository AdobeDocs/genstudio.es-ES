---
title: Notas de la versión de Adobe GenStudio for Performance Marketers Beta
description: Obtenga información sobre las últimas funciones y mejoras de Adobe GenStudio para especialistas en marketing de rendimiento.
source-git-commit: cbae3aeb1b8282fb64f2a6405a7ad9e07a48dbbd
workflow-type: tm+mt
source-wordcount: '347'
ht-degree: 0%

---


# Notas de la versión de Adobe GenStudio for Performance Marketers Beta

Estas notas destacan las correcciones y mejoras significativas de los Adobes GenStudio realizadas durante la semana que finalizó el 16 de agosto.

## Características destacadas

El desarrollo de funciones es rápido y continuo. Entre las nuevas funciones destacables se incluyen:

### [!DNL Brands]

El panel de validación [!DNL Brand] se mejoró para mejorar la experiencia del usuario, incluidos estos cambios:

* **Puntuación de validación basada en porcentajes**: La validación de marca ahora muestra la puntuación de validación de marca como un porcentaje en lugar de un valor de aprobado/suspenso.

* **Interfaz de extracción de marca actualizada**: La extracción de marca ahora muestra la finalización del proceso de extracción como porcentaje.

* **Carga incremental de la marca durante la extracción**: Las directrices de marca ahora se cargan gradualmente en la interfaz de usuario.

* **Simplificación del esquema de copia de directrices**: los campos `unique attributes` y `frequent keywords` se han eliminado del esquema de copia de directrices, lo que simplifica el proceso de configuración de las directrices.

### [!DNL Create]

* **Creación de correo electrónico de varias secciones**: los usuarios ahora pueden crear correos electrónicos compuestos por titulares, imágenes, cuerpos y elementos de CTA independientes.

* **Cambio de tamaño de metadatos de anuncios**: los creadores pueden cambiar el tamaño de las proporciones de aspecto de metadatos de anuncios.

### [!DNL Insights]

* **Cuentas de inicio de sesión con información limitada**: el inicio de sesión con información ahora solo admite una cuenta por cliente.

## Mejoras y problemas corregidos

Esta versión incluye las siguientes correcciones adicionales.

### [!DNL Insights]

* El nombre de la ubicación de la fuente de página _Detalles de experiencia_ ahora especifica la fuente de Facebook o Instagram.

* Ahora, el recorte de imágenes y vídeos de mayor tamaño es coherente cuando el usuario navega de la vista _Información general del recurso_ a la vista _Detalles del recurso_.

* El recuento de resultados de búsqueda de la pantalla Atributos ya no muestra `0 of` antes de que un usuario inicie sesión. <!-- GS- 3665 -->

* Al hacer clic en el campo de recuento **[!UICONTROL [!DNL Insights]]** > **[!UICONTROL Recurso]**, ya no se borra la configuración de búsqueda y filtrado. <!-- GS-3476 -->

## Problemas conocidos

Los siguientes problemas conocidos se resolverán en la versión de GenStudio for Performance Marketers GA.

### Análisis

* Las acciones activadas por los botones **[!UICONTROL Agregar plantillas]** y **[!UICONTROL Cargar]** no se rastrean actualmente. <!-- GS-3505 -->

### [!DNL Insights]

* No se pueden reproducir vídeos de _Assets_. <!-- GS-3846 -->

* Los usuarios deben iniciar sesión dos veces cuando también hayan iniciado sesión en Facebook. **Solución alternativa**: cierre la sesión de Facebook antes de iniciar sesión en [!DNL Insights].

* **Los valores de gasto a nivel de campaña** no son precisos. Actualmente, los datos no son coherentes entre el Administrador de Facebook Ads y el lago de datos. <!-- GS-3202 -->

### [!DNL Reviews and Approvals]

* Los creadores pueden cambiar los recursos después de aprobarlos antes de publicarlos. Estos cambios no se notifican a los aprobadores.

