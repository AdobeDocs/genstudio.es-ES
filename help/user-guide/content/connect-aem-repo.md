---
title: Conectarse a un repositorio de AEM Assets Content Hub
description: Aprenda a conectar GenStudio para especialistas en marketing de rendimiento a un repositorio de Adobe Experience Manager AEM () Content Hub y a aprovechar el contenido aprobado existente.
level: Experienced
feature: Assets, Content
source-git-commit: dc438085cfe7c93b20dc7fb0d5919d2dc8b3dcde
workflow-type: tm+mt
source-wordcount: '268'
ht-degree: 0%

---

# Conectar a un repositorio [!DNL AEM Assets Content Hub]

Si tiene recursos en Adobe Experience Manager AEM (), puede seguir estos pasos para que estén accesibles en GenStudio para especialistas en marketing de rendimiento.

>[!BEGINSHADEBOX]

**Requisitos previos**:

Los siguientes pasos requieren acceso administrativo a Admin Console y AEM Assets as a Cloud Service.

>[!ENDSHADEBOX]

## Paso 1: Habilitar [!DNL AEM Assets Content Hub]

Siga el proceso de autoservicio **Implementar Content Hub** para habilitar [!DNL Content Hub] para su AEM Assets existente en Cloud Manager. Ver [Implementar [!DNL Content Hub]](https://experienceleague.adobe.com/en/docs/experience-manager-cloud-service/content/assets/content-hub/deploy-content-hub) en la documentación de _AEM as a Cloud Service_.

Después de habilitar [!DNL AEM Assets Content Hub], tiene una nueva instancia con el sufijo `contenthub` en [!DNL AEM Assets as a Cloud Service] en el Admin Console.

## Paso 2: Incorporar usuarios de GenStudio

En [!DNL Admin Console], agregue usuarios o grupos de usuarios de GenStudio a los perfiles de producto de [!DNL AEM Assets Content Hub]. Los usuarios de [!DNL AEM Assets Content Hub] pueden ver los recursos, pero no pueden agregarlos ni modificar los recursos existentes.

- [Incorporado [!DNL Content Hub] administrador](https://experienceleague.adobe.com/en/docs/experience-manager-cloud-service/content/assets/content-hub/deploy-content-hub#onboard-content-hub-administrator)
- [Incorporar [!DNL Content Hub] usuarios](https://experienceleague.adobe.com/en/docs/experience-manager-cloud-service/content/assets/content-hub/deploy-content-hub#onboard-content-hub-users)

## Paso 3: Aprobar los recursos

Apruebe los recursos para usarlos en [!DNL AEM Assets Content Hub], de modo que estén disponibles en GenStudio para especialistas en marketing de rendimiento. Consulte [Aprobar recursos en el Experience Manager](https://experienceleague.adobe.com/en/docs/experience-manager-cloud-service/content/assets/dynamicmedia/dynamic-media-open-apis/approve-assets) en la documentación de _AEM as a Cloud Service_.

## Paso 4: Configurar la visibilidad de los recursos

En las opciones de configuración de _[!DNL AEM Assets Content Hub]_, revise cada conjunto de opciones de configuración para ver los filtros, los detalles de recursos, la búsqueda y la personalización de marca. Consulte [Configuración de la interfaz de usuario de Content Hub](https://experienceleague.adobe.com/en/docs/experience-manager-cloud-service/content/assets/content-hub/configure-content-hub-ui-options) en la documentación de_ AEM as a Cloud Service _.

## Paso 5: Verificar la conexión

En el contenido de GenStudio para especialistas en marketing de rendimiento, la lista _[!UICONTROL Ubicación]_ está disponible encima de la galería, en el lado derecho. La lista no está disponible si no tiene acceso o si su organización no ha implementado y conectado un repositorio [!DNL AEM Assets Content Hub].
