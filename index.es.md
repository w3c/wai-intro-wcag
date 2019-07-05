---
# Translation info https://www.w3.org/wiki/WAI/Website/Translate

title: "Web Content Accessibility Guidelines (WCAG) Overview"
nav_title: "Web Content – WCAG"

description: Introduces the Web Content Accessibility Guidelines (WCAG) international standard, including WCAG 2.0 and WCAG 2.1. WCAG documents explain how to make web content more accessible to people with disabilities.

lang: en
last_updated: 2018-06-22
permalink: /standards-guidelines/wcag/

github:
  repository: w3c/wai-intro-wcag
  path: "index.md"

footer: >
  <p><strong>Date:</strong> Updated 22 June 2018. First published July 2005.</p>
  <p><strong>Editor:</strong> <a href="http://www.w3.org/People/Shawn/">Shawn Lawton Henry</a>.</p>
  <p>Developed with input from the Education and Outreach Working Group (<a href="https://www.w3.org/WAI/about/groups/eowg/">EOWG</a>) and the Accessibility Guidelines Working Group (<a href="https://www.w3.org/WAI/about/groups/agwg/">AG WG</a>).</p>
image: /content-images/wai-intro-wcag/wcag-intro-social.jpg
feedbackmail: wai@w3.org  
ref: /standards-guidelines/wcag/
---

{::nomarkdown}
{% include box.html type="start" h="2" title="Summary" class="full" %}
{:/}

Introducing the Web Content Accessibility Guidelines (WCAG), including WCAG 2.0 and WCAG 2.1.

Quick links to resources:
* [How to Meet WCAG 2 (Quick Reference)](http://www.w3.org/WAI/WCAG21/quickref/)
* [WCAG 2.1 Standard](http://www.w3.org/TR/WCAG21/)
* [WCAG 2.0 Standard](http://www.w3.org/TR/WCAG20/)

{::nomarkdown}
{% include box.html type="end" %}
{:/}

{::nomarkdown}
{% include_cached toc.html type="start" title="Page Contents" class="simple" %}
{:/}

{::options toc_levels="2" /}

-   This text will be replaced by the TOC.
{:toc}

{::nomarkdown}
{% include_cached toc.html type="end" %}
{:/}

## Introducción {#intro}

Las pautas de accesibilidad para el contenido web (WCAG) se desarrollan a través del [proceso del W3C](/standards-guidelines/w3c-process/) en cooperación con personas y organizaciones de todo el mundo, con el fin de ofrecer un estándar único y compartido que satisfaga las necesidades de las personas, organizaciones y gobiernos a nivel internacional.

Los documentos WCAG explican cómo hacer el contenido web más accesible para las personas con discapacidad. Por “contenido” web se hace referencia, generalmente, a la información que se puede encontrar en una página o aplicación web, lo cual incluye:

-   información natural como textos, imágenes y sonidos.
-   código o marcado que define la estructura, la presentación, etc.

## WCAG 2.0 y 2.1 {#versions}

WCAG 2.0 se publicó el 11 de diciembre del 2008. WCAG 2.1 se publicó el 5 de junio del 2018.

Todos los requisitos (criterios de conformidad) de la versión 2.0 están incluidos en 2.1. Los criterios de conformidad 2.0 son exactamente iguales (literalmente) en 2.1.

Hay criterios de conformidad adicionales en 2.1 que no existen en 2.0. Se hace una presentación de ellos en las [[novedades de WCAG 2.1]](/standards-guidelines/wcag/new-in-21/).

**El contenido que es conforme con WCAG 2.1 también lo es con WCAG 2.0** (se suele decir que se da “retrocompatibilidad”). Un sitio web que cumpla con WCAG 2.1 cumpliría con los requisitos de las políticas que hacen referencia a WCAG 2.0.

Dicho de otra forma: si se desea cumplir tanto con WCAG 2.0 y 2.1, se pueden usar los recursos de 2.1 y no sería necesario consultar los relativos a 2.0.

Tanto WCAG 2.0 como 2.1 son estándares actuales. WCAG 2.1 no deja WCAG 2.0 obsoleto ni lo sustituye. Desde W3C se anima a usar la versión más reciente de WCAG al desarrollar o actualizar contenido o políticas de accesibilidad.

## Destinatarios de WCAG {#for}

WCAG se dirige principalmente a:

-   Desarrolladores de contenido web (autores de páginas, diseñadores de sitios, etc.)
-   Desarrolladores de programas de autor
-   Desarrolladores de herramientas para la evaluación de la accesibilidad web
-   Otros que quieran o necesiten un estándar para la accesibilidad web, incluyendo la accesibilidad móvil

Los recursos relacionados se dirigen a cubrir las necesidades de diferentes personas, entre ellas legisladores, directores, investigadores y otros.

WCAG es un estándar técnico, no una introducción a la accesibilidad. Si busca material introductorio, consulte  [“¿Dónde debería empezar?” en las FAQ](/standards-guidelines/wcag/faq/#start).

## Contenido de los documentos de las WCAG 2 {#whatis2}

**[WCAG 2.0](https://www.w3.org/TR/WCAG20/)** y **[WCAG 2.1](https://www.w3.org/TR/WCAG21/)** son estándares técnicos estables y de referencia. Contienen 12-13 pautas que se agrupan en [cuatro principios: perceptible, operable, comprensible y robusto](https://www.w3.org/WAI/WCAG21/Understanding/intro#understanding-the-four-principles-of-accessibility). Cada pauta incluye *criterios de conformidad*, que se pueden comprobar y que se clasifican en [tres niveles: A, AA y AAA](https://www.w3.org/WAI/WCAG21/Understanding/conformance#levels).

Puede leer un resumen breve sobre las WCAG 2 consultando **[[WCAG 2.1 de un vistazo]](/standards-guidelines/wcag/glance/)**.

Si desea aprender sobre principios y directrices de accesibilidad web, consulte **[[Principios de Accesibilidad]](/fundamentals/accessibility-principles/)**.

Los materiales de apoyo de las WCAG 2 comprenden:

-   [**Cómo cumplir con las WCAG 2**: Una guía de referencia rápida y personalizable que incluye los requisitos (criterios de conformidad) y técnicas de las Pautas de Accesibilidad para el Contenido Web](http://www.w3.org/WAI/WCAG21/quickref/) que es, en esencia, [la lista de control de WCAG 2](http://www.w3.org/WAI/WCAG21/quickref/). La mayoría de la gente utiliza esta guía de referencia rápida como herramienta principal para trabajar con las WCAG.
-   **Técnicas para las WCAG 2** ([Técnicas 2.1](https://www.w3.org/WAI/WCAG21/Techniques/), [Técnicas 2.0](https://www.w3.org/TR/WCAG20-TECHS/)) proporcionan información específica para desarrollar contenido accesible, como por ejemplo fragmentos de código HTML. Las técnicas son “informativas”, lo cual quiere decir que no tiene por qué usarlas. La base para determinar la conformidad con WCAG 2 reside en los *criterios de conformidad* del texto WCAG 2 estándar y no en las técnicas. Lea más sobre las [Técnicas en el FAQ](/standards-guidelines/wcag/faq/#techs).
-  **Comprender las WCAG 2** ([Comprender 2.1](https://www.w3.org/WAI/WCAG21/Understanding/), [Comprender 2.0](https://www.w3.org/TR/UNDERSTANDING-WCAG20/)) contiene asistencia adicional para aprender e implementar WCAG 2 dirigida a aquellas personas que quieran comprender las pautas y criterios de conformidad en profundidad.

Puede obtener más información sobre cómo estos documentos se relacionan entre sí consultando los **[[Documentos WCA 2]](/standards-guidelines/wcag/docs/)**.

### Traducciones

Las traducciones de WCAG 2 autorizadas y las no oficiales se enumeran en [[Traducciones de WCAG 2]](/standards-guidelines/wcag/translations/).

### Formato de documento técnico

Los documentos de las WCAG, Técnicas y Comprender siguen el formato para informes técnicos del W3C, que contiene varias secciones al principio, incluyendo enlaces a versiones diferentes, editores, resumen y estado.

### Orientación suplementaria {#supplement}

La orientación suplementaria proporciona información adicional que va más allá de lo requerido en las WCAG 2.0 y 2.1. Trata de mejorar la accesibilidad para las personas con discapacidad cognitiva y visión baja. En el futuro, enlaces a información suplementaria serán añadidos en esta sección.

## WCAG 2.0 es ISO/IEC 40500 {#iso}

Las WCAG 2.0 están aprobadas como un estándar ISO: ISO/IEC 40500:2012. Éste es exactamente igual que las WCAG 2.0 originales, que se presentan arriba junto con los recursos de apoyo.

El contenido de ISO/IEC 40500 está disponible gratuitamente en [www.w3.org/TR/WCAG20](http://www.w3.org/TR/WCAG20/); también está disponible para ser comprado en el [catálogo ISO {% include_cached external.html %}](http://www.iso.org/iso/iso_catalogue/catalogue_tc/catalogue_detail.htm?csnumber=58625).

Los beneficios de tener las WCAG como un estándar ISO se resumen en las [FAQ sobre ISO](/standards-guidelines/wcag/faq/#iso). Se puede encontrar más información sobre W3C y el proceso ISO en las [FAQ de W3C PAS](http://www.w3.org/2010/04/pasfaq).

## Otras pautas {#components}

Las WCAG forman parte de una serie de pautas de accesibilidad, que incluye a las pautas de accesibilidad para las herramientas de creación de contenido (ATAG) y las pautas de accesibilidad para el agente de usuario (UAAG). Los [[componentes esenciales de la accesibilidad web]](/fundamentals/components/) explican la relación entre estas pautas diferentes.

## Who develops WCAG {#wg}

The WCAG technical documents are developed by the Accessibility Guidelines Working Group ([AG WG](https://www.w3.org/WAI/GL/)) *(formerly the Web Content Accessibility Guidelines Working Group)*, which is part of the World Wide Web Consortium ([W3C](http://www.w3.org)) Web Accessibility Initiative ([WAI](https://www.w3.org/WAI/)).

WAI updates Techniques for WCAG 2 and Understanding WCAG 2 periodically. We welcome [comments](/standards-guidelines/wcag/commenting/) and [submission of new techniques](http://www.w3.org/WAI/GL/WCAG20/TECHS-SUBMIT/).

Opportunities for contributing to WCAG and other WAI work are introduced in [[Participating in WAI]](/about/participating/).

## More Information {#more}

See the [[WCAG 2 FAQ]](/standards-guidelines/wcag/faq/) for more information on:

-   **WCAG 2 coverage of [mobile accessibility](/standards-guidelines/wcag/faq/#mobile)**
-   **WCAG 2 applicability to [non-W3C technologies](/standards-guidelines/wcag/faq/#othertechs)**
-   and more...
