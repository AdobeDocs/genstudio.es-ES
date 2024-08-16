---
title: Adobe GenStudio para revisiones y aprobaciones de especialistas en marketing de rendimiento
description: Obtenga información acerca del proceso de revisión y aprobación de GenStudio para especialistas en marketing de rendimiento.
feature: Approval
source-git-commit: c9d09801f0bd3732611b01d4a98cc7ebf38884d7
workflow-type: tm+mt
source-wordcount: '631'
ht-degree: 0%

---


# Adobe GenStudio para revisiones y aprobaciones de especialistas en marketing de rendimiento

El flujo de trabajo de revisión y aprobaciones de GenStudio para especialistas en marketing de rendimiento garantiza que todas las partes interesadas, desde equipos creativos hasta expertos legales, puedan revisar y aprobar de forma eficaz los componentes de la campaña, incluidos los activos de marca generados a partir de IA.

## [!DNL Review and Approval] ventajas de flujo de trabajo

* **Compatibilidad con la creación de contenido de IA generativo, iterativo y robusto**. La creación e implementación de contenido alineado con la marca en una organización es un proceso altamente iterativo. Las capacidades generativas de IA de GenStudio para especialistas en marketing de rendimiento admiten la creación rápida de cientos de variantes de recursos. Cada revisor puede solicitar varios cambios en un borrador de recurso antes de aprobarlo. Cuantos más revisores haya, mayor será el número de iteraciones potenciales antes de que todas las partes interesadas acuerden una variante final.

* **Soporte para la integridad creativa**. Las aprobaciones salvaguardan la integridad creativa de los activos de su marca al mantener a los creadores de contenido involucrados en el proceso de aprobación. Al involucrar a las partes interesadas creativas (por ejemplo, creadores de contenido y directores creativos) en el proceso de revisión y aprobación, se asegura de que el resultado final se ajuste a su visión y a la identidad de su marca.

* **Cumplimiento de los objetivos de la campaña y los requisitos legales**. El proceso de aprobación ayuda a comprobar que el contenido admite los objetivos de la campaña. Garantiza que el contenido cumpla con la autenticidad legal, lo que minimiza los riesgos y los posibles problemas legales.

## Ciclo de vida de revisión y aprobación

Las fases principales del flujo de trabajo de revisión y aprobación incluyen:

* [Solicitar revisión y aprobación del contenido que ha creado](./request-review.md)
* [Revisar y editar contenido](./review-and-edit.md)
* [Aprobar contenido](./approve-content.md)
* [Contenido de Publish](./publish-content.md)

## ¿Quién puede solicitar una revisión o aprobar contenido?

Si ha creado un recurso o una experiencia, puede pedir a otras personas de la cadena de aprobación de su organización que revisen formalmente su trabajo y lo comenten. Solo estos aprobadores designados pueden revisar el borrador.

## Acerca de [!DNL Content] borradores

_Borradores_ son versiones preliminares de recursos o experiencias que no han pasado por el proceso de revisión y aprobación. El estado del borrador indica dónde se encuentra el borrador en el proceso de revisión y aprobación. Un ID de borrador único identifica cada borrador. Este identificador es válido hasta que se apruebe un borrador y se publique en [!DNL Content]. Los comentarios de revisión y las aprobaciones de un borrador están asociados a este ID de borrador individual.

Cuando un borrador completa el proceso de revisión y aprobación y se publica en [!DNL Content], el ID del borrador caduca y GenStudio para especialistas en marketing de rendimiento no guarda los comentarios asociados ni los estados de aprobación. El borrador de URL ya no es válido.

El estado del borrador captura el estado del borrador de contenido a medida que se desplaza por el proceso de revisión y aprobación. Se notifica a todos los revisores designados de los cambios en el estado del contenido que están revisando. Los revisores cambian el estado de borrador para indicar si un borrador necesita una revisión adicional o si se puede aprobar. Todos los aprobadores designados deben aprobar un recurso o una experiencia para que se pueda publicar.

Estados de borrador disponibles:

**Notificado**: el creador de contenido ha iniciado el proceso de revisión notificando a los revisores que un borrador está listo para revisarse.
**Necesita trabajo**: indica que uno o más revisores han solicitado cambios en el borrador de contenido. El contenido en este estado no se puede guardar en [!DNL Content].
**Aprobado**: todos los aprobadores designados han aprobado el recurso o la experiencia. El creador de contenido ahora puede agregar metadatos al recurso o la experiencia y guardarlos en [!DNL Content].

## Notificaciones

Las notificaciones internas de GenStudio para especialistas en marketing de rendimiento actualizan a los aprobadores y creadores de contenido en tiempo real de los cambios de estado de los recursos y revisan los comentarios. Las notificaciones admiten la iteración rápida a través de varios ciclos de revisión, edición y aprobación.

Las acciones realizadas por los participantes de la aprobación almacenan en déclencheur las notificaciones automáticas internas del producto y las notificaciones por correo electrónico. Al iniciar un proceso de aprobación, los aprobadores designados reciben notificaciones por correo electrónico y dentro del producto. Se le mantienen en el bucle con notificaciones internas del producto cada vez que un aprobador agrega comentarios o aprueba. Las notificaciones incluyen vínculos al borrador de contenido.

Si ha iniciado el proceso de revisión y aprobación de contenido, se le notifican todas las aprobaciones y comentarios de revisión. Sin embargo, a los aprobadores solo se les notifican los comentarios que los incluyen con un `@mention`.
