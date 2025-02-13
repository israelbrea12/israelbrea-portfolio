---
title: Procesamiento de XML con DOM y SAX
description: Proyecto académico | Procesamiento de canales RSS(XML) con las tecnologías de DOM y SAX y generación de salidas en XML y JSON
slug: procesamiento-xml
date: 2025-02-02 00:00:00+0000
image: domsax.png
categories:
    - Desarrollo Backend
    - Cloud Computing
tags:
    - Java
    - XML
    - JSON
    - DOM
    - SAX
    - GSON

weight: 1       # You can add weight to some posts to override the default sorting (date descending)
---

Este proyecto fue desarrollado para la asignatura de Tecnologías del lado del servidor: Cloud Computing como parte del máster universitario oficial en Informática Móvil (MIMO).

El objetivo principal fue implementar una aplicación en **Java** capaz de procesar un canal de noticias en **formato RSS (XML)** y generar **archivos de salida en XML y JSON**, aplicando técnicas modernas de procesamiento y herramientas específicas.

## Funcionalidades principales
**1. Procesamiento de XML**:

Implementación de dos versiones del procesamiento del archivo RSS:
- **DOM (Document Object Model)**: Carga el documento completo en memoria y permite una navegación estructurada.
- **SAX (Simple API for XML)**: Lectura secuencial del archivo, más eficiente para grandes volúmenes de datos.

Extracción y presentación de la información clave:
- **Del canal**: Título, URL, descripción.
- **De las noticias**: Título, URL, descripción, fecha de publicación y categoría.
    
**2. Generación de archivos de salida**:

**XML**: Archivo estructurado con los títulos de las noticias en el formato:
``` xml
<noticias canal="título del canal">
  <noticia>título noticia 1</noticia>
  <noticia>título noticia 2</noticia>
</noticias>
```
**JSON**: Archivo equivalente, generado con el formato:
``` json
{
  "noticias": [
    {"noticia": "título noticia 1"},
    {"noticia": "título noticia 2"}
  ]
}
```

**3. Conversión con GSON**:

Uso de la librería GSON para la serialización y deserialización entre objetos Java y JSON, asegurando una manipulación sencilla y eficiente de los datos.

[Ver repositorio en GitHub de procesamiento con DOM](https://github.com/israelbrea12/Procesamiento-DOM-JAVA.git)

[Ver repositorio en GitHub de procesamiento con SAX](https://github.com/israelbrea12/Procesamiento-SAX-JAVA.git)