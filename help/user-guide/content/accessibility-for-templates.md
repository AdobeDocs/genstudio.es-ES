---
title: Creación de plantillas accesibles
description: Genere plantillas que puedan llegar a todas las audiencias para utilizarlas en Adobe GenStudio para especialistas en marketing de rendimiento.
feature: Templates, Content
source-git-commit: 26d1b9c7b392e93e87ffcd9444f391c2980d1c3c
workflow-type: tm+mt
source-wordcount: '257'
ht-degree: 0%

---


# Creación de plantillas accesibles

El Adobe se compromete a proporcionar una experiencia óptima para todas las audiencias. Consulte [Iniciativas de accesibilidad en el Adobe](https://www.adobe.com/trust/accessibility/initiatives.html) para obtener más información.

En GenStudio para especialistas en marketing de rendimiento, puede cargar recursos y plantillas que permitan la creación de contenido para diversas experiencias. El cumplimiento de los estándares de accesibilidad ayuda a que el contenido llegue a la audiencia máxima deseada.

Utilice las siguientes recomendaciones para preparar sus plantillas con los estándares de accesibilidad óptimos.

## Texto alternativo

Proporcione alternativas textuales para el contenido no textual, como las imágenes.

```html
<img alt="Collage of ideas, books, man holding giant pencil, computer" src="card-create-assets.png">
```

![Collage de ideas, libros, hombre con lápiz gigante, equipo](../../assets/card-create-assets.png){width="400"}

## Objetivo del vínculo (solo vínculo)

Cree un texto de vínculo claro que describa el propósito y la ubicación del vínculo.

Por ejemplo, el uso de texto de vínculo como &quot;Haga clic aquí&quot; o &quot;Más información&quot; no describe claramente el propósito del vínculo:

```html
<a href="product-site.html">Click here</a>
```

Se recomienda utilizar texto que describa claramente hacia dónde va el vínculo. Un ejemplo mejor podría utilizar el título de la fuente del vínculo y el propósito:

```html
<a href="product-site.html">Explore Product Site</a>
```

## Idioma

Muchos productos y servicios utilizan el lenguaje de una manera creativa o única. Evite la jerga, las frases largas y las frases complejas. Utilice un lenguaje claro, conciso y fácil de leer, compatible con su público objetivo.

- Utilice descripciones claras, definiciones en línea o ejemplos relacionados cuando sea posible. Puede ser difícil traducir un vernáculo único.

- Escriba o vincule a una definición para las primeras instancias de un acrónimo o abreviatura. Puede ser difícil traducir abreviaturas.

- Utilice elementos visuales para complementar texto o ideas complejas cuando sea posible.
