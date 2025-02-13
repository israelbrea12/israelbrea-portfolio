---
title: XML processing with DOM and SAX
description: Academic project | Processing RSS(XML) feeds with DOM and SAX technologies and generating XML and JSON outputs
slug: xml-processing
date: 2025-02-02 00:00:00+0000
image: domsax_en.png
categories:
- Backend Development
- Cloud Computing
tags:
- Java
- XML
- JSON
- DOM
- SAX
- GSON

weight: 1 # You can add weight to some posts to override the default sorting (date descending)
---

This project was developed for the subject of Server-Side Technologies: Cloud Computing as part of the official university master's degree in Mobile Computing (MIMO).

The main objective was to implement a **Java** application capable of processing a news channel in **RSS (XML) format** and generating **XML and JSON output files**, applying modern processing techniques and specific tools.

## Main functionalities
**1. XML processing**:

Implementation of two versions of RSS file processing:
- **DOM (Document Object Model)**: Loads the entire document into memory and allows structured navigation.
- **SAX (Simple API for XML)**: Sequential reading of the file, more efficient for large volumes of data.

Extraction and presentation of key information:
- **From the channel**: Title, URL, description.
- **From the news**: Title, URL, description, publication date and category.

**2. Output file generation**:

**XML**: Structured file with the news titles in the format:
``` xml
<news channel="channel title">
    <news>news title 1</news>
    <news>news title 2</news>
</news>
```
**JSON**: Equivalent file, generated with the format:
``` json
{
    "news": [
        {"news": "news title 1"},
        {"news": "news title 2"}
    ]
}
```

**3. Conversion with GSON**:

Use of the GSON library for serialization and deserialization between Java objects and JSON, ensuring simple and efficient data manipulation.

[View GitHub repository for DOM processing](https://github.com/israelbrea12/Procesamiento-DOM-JAVA.git)

[View GitHub repository for SAX processing](https://github.com/israelbrea12/Procesamiento-SAX-JAVA.git)