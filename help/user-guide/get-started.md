---
title: Introducción a GenStudio
description: Aprenda a configurar su GenStudio para generar nuevo contenido de marketing alineado con la marca.
level: Beginner
feature: Prompt, Brands Service, Personas Service, Products Service, Generative AI, Guidelines
source-git-commit: 2501d1e36f76d1534a735b9147fb42f762a665e8
workflow-type: tm+mt
source-wordcount: '1066'
ht-degree: 1%

---


# Introducción a GenStudio

GenStudio es una plataforma completa para crear, evaluar y administrar experiencias de marketing que reflejen y se adhieran a la identidad de su marca.

El acceso de las partes interesadas a sus numerosas funciones está controlado por las funciones de usuario asignadas. La función de usuario asignada determina las tareas que se pueden realizar en GenStudio. Un administrador de GenStudio establece los permisos, que se definen en el correo electrónico de bienvenida.

Si no tiene experiencia previa con herramientas generativas basadas en IA o simplemente siente curiosidad por conocer los principios básicos de GenStudio, consulte [conceptos de GenStudio](concepts.md) y [Escribir mensajes efectivos](effective-prompts.md).

## Funciones de usuario de GenStudio

La creación e implementación de campañas de marketing modernas requieren la colaboración entre partes interesadas con diversas responsabilidades y conjuntos de habilidades.

Existen tres tipos de funciones de usuario de GenStudio que admiten esta diversidad de funciones organizativas. Los permisos se adaptan a cada uno de estos tipos de usuarios y admiten las responsabilidades de cada usuario en la organización de marketing.

**Los tres tipos de roles de usuario son**:

* **Creadores** utilizan las capacidades de IA generativa de GenStudio para crear recursos de campañas de marketing, solicitar la revisión y aprobación del contenido y publicar borradores aprobados de este contenido. Todos los usuarios de GensStudio pueden acceder y utilizar un recurso una vez que su creador lo haya guardado en el Contenido.

* **Los colaboradores** son la gama más amplia de usuarios de GenStudio. Los colaboradores pueden ver y aprobar el contenido de GenStudio, y son una parte esencial del flujo de trabajo para garantizar que el contenido que genere coincida con las necesidades y los estándares de su organización.

* **Los administradores del sistema** tienen el conjunto más amplio de permisos en GenStudio. Los administradores del sistema pueden agregar y eliminar usuarios y contenido de Genstudio. Los administradores realizan la tarea de incorporación esencial de establecer las barreras fundamentales para la creación y la implementación de recursos de la campaña. Los administradores implementan estas protecciones cargando información específica de la marca y de la organización, como [directrices de marca](/help/user-guide/guidelines/overview.md).

>[!NOTE]
>Antes de aprovisionar usuarios en estas funciones, se debe designar un administrador como superusuario en la Admin Console de Adobe para realizar tareas de configuración únicas. Esta función de superusuario solo funciona en el contexto de Adobe Admin Console. No tiene función en la interfaz de la plataforma GenStudio. No existe el concepto de superusuario en las asignaciones de funciones de GenStudio.

### Creadores

**Los creadores** tienen los permisos básicos necesarios para crear los recursos de GenStudio [!DNL Brands], [!DNL Campaigns] y [!DNL Content]. También pueden editar y eliminar los recursos que han creado. GenStudio permite crear rápidamente cientos de fragmentos de contenido. Estos usuarios pueden generar fragmentos de contenido o experiencias completas que organicen fragmentos discretos de contenido aprobado para satisfacer las necesidades de campañas de marketing específicas.

Los creadores interactúan con las tecnologías de IA generativa de GenStudio mediante _prompting_. El área de mensajes de GenStudio en el lienzo proporciona herramientas para colocar mensajes en el contexto de las directrices de una campaña específica. Como resultado, la calidad y el éxito del contenido generado dependen parcialmente de la calidad de las directrices de marca que su organización ha cargado y de la especificidad del mensaje.

Consulte [Escribir mensajes efectivos](effective-prompts.md).

La siguiente tabla muestra los permisos de creador predeterminados de GenStudio:

| Funcionalidad | Crear | Actualizar | Eliminar | Ver |
|-----------|----------------|----------------|----------------|----------------|
| [!DNL Brands] | no | no | no | yes |
| [!DNL Campaigns] | yes | yes | yes | yes |
| [!DNL Content] | yes | yes | yes | yes |
| [!DNL Insights] | solo puede configurar conectores de publicidad |    |     | yes |
| [!DNL Personas] | yes | yes | yes | yes |
| [!DNL Products] | yes | yes | yes | yes |
| [!DNL Reviews and approvals] | yes | yes | yes | yes |

### Colaboradores

**Los colaboradores** pueden ver los recursos en GenStudio, pero no crearlos, editarlos o eliminarlos. Los colaboradores incluyen partes interesadas que son esenciales para el éxito del proceso de revisión y aprobación del contenido de GenStudio, pero que no necesitan crear ni editar contenido directamente. Los expertos legales y los gestores de los creadores son ejemplos de colaboradores potenciales. Los colaboradores de GenStudio pueden tener permisos para crear y ver recursos en otros productos de Creative Cloud.

En la tabla siguiente se muestran los permisos de colaborador predeterminados de GenStudio:

| Funcionalidad | Crear | Actualizar | Eliminar | Ver |
|-----------|----------------|----------------|----------------|----------------|
| [!DNL Brands] | yes | yes | yes | yes |
| [!DNL Campaigns] | yes | yes | yes | yes |
| [!DNL Content] | yes | yes | yes | yes |
| [!DNL Insights] | no | no | no | yes |
| [!DNL Personas] | yes | yes | yes | yes |
| [!DNL Products] | yes | yes | yes | yes |
| [!DNL Reviews and approvals] | no | no | no | yes |

### Administradores

Los usuarios administradores crean y asignan usuarios a cualquiera de las funciones compatibles con GenStudio. Pueden asignar nuevos permisos a creadores o colaboradores individuales según sea necesario. Su trabajo más crítico es completar las tareas de incorporación iniciales que preparan a su organización para implementar GenStudio.

La siguiente tabla muestra los permisos predeterminados de administrador del sistema de GenStudio:

| Funcionalidad | Crear | Actualizar | Eliminar | Ver |
|-----------|----------------|----------------|----------------|----------------|
| [!DNL Brands] | yes | yes | yes | yes |
| [!DNL Campaigns] | yes | yes | yes | yes |
| [!DNL Content] | yes | yes | yes | yes |
| [!DNL Insights] | yes | yes | yes | yes |
| [!DNL Personas] | yes | yes | yes | yes |
| [!DNL Products] | yes | yes | yes | yes |
| [!DNL Reviews and approvals] | yes | yes | yes | yes |


## Preparación de GenStudio para generar contenido

Los administradores de sistemas preparan el entorno de GenStudio de su organización para que los creadores y colaboradores creen recursos de campaña. Estas tareas preliminares de configuración incluyen:

1. [Configurar directrices](./guidelines/overview.md) para [!DNL Brands], [!DNL Products] y [!DNL Personas]. Configurando los componentes clave de la marca **[Agregar directrices](./guidelines/overview.md)** ([!DNL Brands], [!DNL Products] y [!DNL Personas]) de su organización a GenStudio. La configuración de los componentes clave de la identidad de marca de su organización es un requisito previo esencial para el trabajo de los creadores y colaboradores de GenStudio. Puede cargar documentos de directrices de marca o introducir manualmente información de marca.
   * **Prepare sus documentos de directrices**. Cuanto más descriptivas y completas sean las directrices de marca, mejor será el resultado de GenStudio. Incluya ejemplos breves de las funciones que considera esenciales para su marca y agregue descripciones del comportamiento que desea excluir de la creación de contenido de GenStudio. GenStudio extrae información de estos documentos cargados y comienza a crear su marca. La información, como las directrices de voz, canal e imagen de la marca, se rellenan a medida que GenStudio organiza cada directriz a partir de los documentos cargados.
   * **Edite o complete los campos de las directrices de marca según sea necesario**. Las directrices de marca completas forman la base de la comprensión por parte de GenStudio de la marca de su organización. Una vez que GenStudio ha extraído la información que necesita de los documentos de directrices de marca, se le pedirá que edite o complete manualmente los campos de información extraída. Especifique áreas de enfoque de producto individuales para la creación de contenido agregando [!DNL Product]. Las directrices de [!DNL Personas] ayudan a adaptar la creación de contenido para segmentos de clientes definidos.

   Aunque la configuración de las directrices de marca de una organización puede ser una acción única, es posible que tenga que revisar y mejorar estas directrices en función de la volatilidad, el crecimiento y las circunstancias cambiantes del mercado de su organización.

1. **[Cargar plantillas](./content/use-templates.md)**. Las plantillas proporcionan métodos abreviados de teclado y aceleran la creación de contenido. Una plantilla contiene funciones aprobadas, como encabezados y pies de página, y establece protecciones para la creación de contenido. Los administradores suelen cargar y administrar plantillas para su organización. Los creadores utilizan plantillas para impulsar el proceso de creación de contenido dentro de los límites establecidos de la marca de la organización.

1. **[Cargar recursos aprobados](./content/manage-assets.md)**. Los recursos aprobados en GenStudio [!DNL Content] están disponibles para todos los creadores de GenStudio. Puede inicializar [!DNL Content] con recursos que los creadores pueden usar para crear experiencias o recursos nuevos.

1. **[Conectarse a una cuenta de Meta (Facebook)](./insights/connect-channel.md)**. Debe configurar una conexión entre GenStudio y las cuentas sociales de su organización para recibir datos de sus campañas de marketing, recursos y experiencias activos. GenStudio [Insights](./insights/overview.md) proporciona herramientas para analizar datos derivados del canal.
