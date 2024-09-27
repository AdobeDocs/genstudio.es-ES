---
title: Notas de la versión de Adobe GenStudio for Performance Marketing Beta
description: Obtenga información sobre las últimas funciones y mejoras de Adobe GenStudio for Performance Marketing.
exl-id: 2ae60dcb-ac95-4ed4-bceb-84b396f7fa4e
source-git-commit: c95a99d4fa8030a35b7fe3690235102e1827422f
workflow-type: tm+mt
source-wordcount: '606'
ht-degree: 0%

---

# Notas de la versión de Adobe GenStudio for Performance Marketing Beta

Estas notas destacan las correcciones y mejoras significativas de Adobe GenStudio for Performance Marketing para la semana que finalizó el 27 de septiembre.

## Nuevas funciones y mejoras

* GenStudio ahora puede extraer información de personas y productos de un PDF cargado y rellenar campos relacionados. <!-- GS-3806 -->

* Los usuarios ahora pueden filtrar [!DNL Content] recursos y experiencias por el nombre del usuario que cargó el recurso. <!-- GS-1808 -->

* El flujo de inicio de sesión Meta ahora incluye un botón **[!UICONTROL Actualizar]** que permite a los usuarios desbloquear elementos emergentes durante el inicio de sesión.

* Se ha eliminado la sección [!DNL Additional details] de la página de detalles [!DNL Persona]. <!-- GS-5133 5134 -->

* Se cambió el nombre de la sección [!DNL Additional details] a [!DNL Messaging preferences] en la página de detalles [!DNL Products]. <!-- GS-5133 5134 -->

* Se ha agregado un botón [!DNL Add persona] a la página _Agregar su primera persona_. <!-- GS-5132 -->

## Problemas conocidos

Los siguientes problemas conocidos están programados para su resolución en la versión de GenStudio for Performance Marketing GA.

* Las plantillas se pueden cargar, pero no ver. **Solución alternativa**: cargue un recurso con el campo **[!UICONTROL Campañas]** rellenado. A continuación, vuelva a cargar la plantilla. <!-- GS-4815 5650-->

* Los usuarios no pueden recortar manualmente los anuncios Meta después de cambiar su tamaño. <!-- GS-5871 -->

* Los usuarios pueden crear un nuevo [!DNL Campaign] a partir de [!DNL Content] flujos de trabajo. <!-- GS-5650 -->

* Los usuarios deben iniciar sesión dos veces en una cuenta de Meta ads de canal cuando también inician sesión en Facebook. Solución alternativa: cierre la sesión de Facebook antes de iniciar sesión en una cuenta de meta ads de canal. <!-- GS-3009 -->

### Mejoras adicionales y problemas corregidos

* Se han resuelto problemas de latencia intermitente con algunas [!DNL Create] operaciones de lienzo. <!-- GS-5203 -->

* Los usuarios ya no tienen que iniciar sesión dos veces en una cuenta de Meta ads de canal cuando también inician sesión en Facebook. <!-- GS-4806 -->

* La generación de correo electrónico ahora ya no genera un correo electrónico incompleto. <!-- GS-5209 -->

* Al crear una campaña en el flujo de trabajo de plantillas, ahora se almacenan los ID según lo esperado.  <!-- GS-4923 -->

* El selector de varios repositorios ahora enumera los repositorios en orden alfabético. <!-- GS-5553 -->

* Se han resuelto los problemas con los formatos de archivo de exportación de CSV para idiomas que no son el inglés. <!-- GS-5141 -->

* Los usuarios ahora pueden hacer clic en el botón [!DNL Create] _Trabajo reciente_ del área **[!UICONTROL Ver todos los borradores]** mientras se cargan los borradores. Anteriormente, al hacer clic en este botón antes de que se cargaran todos los borradores, solo se cargaban unos pocos, y el botón **[!UICONTROL Ver todos los borradores]** dejaba de estar disponible. <!-- GS-3938 -->

* El lienzo [!DNL Create] ahora muestra el botón **[!UICONTROL Ver todos los borradores]** como se espera cuando el lienzo muestra más de cuatro borradores. <!-- GS-5588 -->

* La búsqueda ahora funciona según lo esperado en la ficha _Atributos_. <!-- GS-5658 -->

* La animación Shimmer ahora se escala correctamente durante la carga de la experiencia. <!-- GS-5574 -->

* Las vistas previas de miniaturas de los correos electrónicos de varias partes ahora se representan como se espera en [!DNL Content]. <!-- GS-5258 -->

* Se ha corregido un problema relacionado con Workfront con el botón **[!UICONTROL Enviar para aprobación]**. <!-- GS-5847 -->

* Se corrigieron los problemas con el reflejo de carga en la vista de trabajo reciente de [!DNL Create]. <!-- GS-5589 -->

* La introducción de un término de búsqueda ahora solo da como resultado una llamada de búsqueda según lo esperado.  <!-- GS-2999 -->

* Se ha corregido la representación de imágenes generadas por metadatos después de la exportación. <!-- GS-5749 -->

* El símbolo `%` ahora se representa correctamente en las configuraciones regionales DEU, FRA y ESP cuando los usuarios amplían o alejan las variantes de correo electrónico en el lienzo C[!DNL Create]. <!-- GS-5007 -->


#### Localización

Esta versión incluye mejoras en la localización en toda la interfaz del producto, especialmente en [!DNL Create]. Se han localizado los siguientes componentes de la interfaz: <!-- GS-5295 -->

* Todas las cadenas en el área _Prompt_ (Título de parámetros, nombres de opciones de menú desplegable y texto de marcador de posición de solicitud) <!-- GS-5027 -->

* Todas las cadenas en la ventana _Resize_ para los anuncios Meta generados en [!DNL Create] <!-- GS-5035 -->

* Todas las cadenas en el área _Trabajo reciente_ en [!DNL Create] <!-- GS-5037 -->

* Las cadenas de opciones del menú desplegable Marcas, Personas y Producto en el área de Preguntar <!-- GS-5293 -->

* El **zoom para ajustar a la pantalla** cadena mostrada durante el correo electrónico y la generación del anuncio Meta <!-- GS-5063 -->

* Formatos de fecha y hora, cadena **Borrador sin título** y mensajes de error en los nombres de los anuncios de correo electrónico y metadatos <!-- GS-5023 5022 5048-->

* [!DNL Content] _Assets_ cadenas de vista de galería de fichas y símbolo de porcentaje (%) <!-- GS-4983 4984-->

* El símbolo de porcentaje (%) usado en la tasa de pulsaciones de Insights > Experiencias <!-- GS-4279 -->

* Se muestra un mensaje de error cuando se produce un error del sistema durante la creación de correo electrónico o Meta ads<!-- GS-5061 -->

* Separador decimal para la frase &quot;Recuento de palabras por frase&quot; en la página de detalles de la experiencia de perspectivas <!-- GS-4986 -->

* Cadenas en el menú Exportar para un anuncio Meta generado con una plantilla. <!-- GS-5031 -->

