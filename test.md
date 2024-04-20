---
title: "next*"
subtitle: "Projektmanagementplan"
author: [Lisa Liegenschaft]
date: "2017-02-20"
keywords: [Markdown, Example]
titlepage: true
numbersections: true
documentclass: scrartcl

toc: true
toc-own-page: true
colorlinks: true

fontsize: 10pt
office-name: "Amt für Geoinformation"
office-street: "Rötistrasse 4"
office-place: "4502 Solothurn"
office-phone: "032 627 75 96"
office-mail: "agi@bd.so.ch"
office-web: "agi.so.ch"
version: "0.0.1"
---

# Foo

## Bar
Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo _dolores et ea rebum._ Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet.

- eins
- zwei
- drei
  * foo
  * bar

Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo _dolores et ea rebum._ Stet clita kasd gubergren, See table \ref{my_table} no sea takimata sanctus est Lorem ipsum dolor sit amet.

| Month    | Savings |
| -------- | ------- |
| January  | $250    |
| February | $80     |
| March    | $420    |

Table: Ich bin der Tabellenname \label{my_table}

## Gaga {#gaga}
Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet. Lorem ipsum dolor sit amet, `consetetur sadipscing` elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo **dolores et ea rebum**. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet.

```java
System.out.println "Hallo Welt";

try {
    Ili2db.runImport(config, "")
} catch (Ili2dbException e) {
    logger.severe e.getMessage()
    response.sendError(HttpServletResponse.SC_INTERNAL_SERVER_ERROR, e.getMessage())
    return
}
```
Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo _dolores et ea rebum._ Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet.

![Nam liber tempor cum soluta nobis eleifend option congue nihil imperdiet doming id quod mazim placerat facer possim assum. Lorem ipsum dolor sit amet, consectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat volutpat.](image.png)

Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo _dolores et ea rebum._ Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet.


| Month    | Savings |
| -------- | ------- |
| January  | $250    |
| February | $80     |
| March    | $420    |


Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo _dolores et ea rebum._ Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet. [Link to zum Kapitel Gaga](#gaga).


