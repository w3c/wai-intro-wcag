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

## Who WCAG is for {#for}

WCAG is primarily intended for:

-   Web content developers (page authors, site designers, etc.)
-   Web authoring tool developers
-   Web accessibility evaluation tool developers
-   Others who want or need a standard for web accessibility, including for mobile accessibility

Related resources are intended to meet the needs of many different people, including policy makers, managers, researchers, and others.

WCAG is a technical standard, not an introduction to accessibility. For introductory material, see [“Where should I start?” in the FAQ](/standards-guidelines/wcag/faq/#start).

## What is in the WCAG 2 Documents {#whatis2}

**[WCAG 2.0](https://www.w3.org/TR/WCAG20/)** and **[WCAG 2.1](https://www.w3.org/TR/WCAG21/)** are stable, referenceable technical standards. They have 12-13 guidelines that are organized under [4 principles: perceivable, operable, understandable, and robust](https://www.w3.org/WAI/WCAG21/Understanding/intro#understanding-the-four-principles-of-accessibility). For each guideline, there are testable *success criteria*, which are at [three levels: A, AA, and AAA](https://www.w3.org/WAI/WCAG21/Understanding/conformance#levels).

For a short summary of the WCAG 2 guidelines, see **[[WCAG 2 at a Glance]](/standards-guidelines/wcag/glance/)**.

To learn about web accessibility principles and guidelines, see **[[Accessibility Principles]](/fundamentals/accessibility-principles/)**.

The WCAG 2 supporting technical materials include:

-   [**How to Meet WCAG 2**: A customizable quick reference to Web Content Accessibility Guidelines 2 requirements (success criteria) and techniques](http://www.w3.org/WAI/WCAG21/quickref/) is essentially the [WCAG 2 checklist](http://www.w3.org/WAI/WCAG21/quickref/). Most people use this quick references as the main resource for working with WCAG.
-   **Techniques for WCAG 2** ([2.1 Techniques](https://www.w3.org/WAI/WCAG21/Techniques/), [2.0 Techniques](https://www.w3.org/TR/WCAG20-TECHS/)) gives you specific details on how to develop accessible web content, such as HTML code examples. The techniques are "informative", that is, you do not have to use them. The basis for determining conformance to WCAG 2 is the *success criteria* from the WCAG 2 standard, not the techniques. Read more in [Techniques in the FAQ](/standards-guidelines/wcag/faq/#techs).
-  **Understanding WCAG 2** ([2.1 Understanding](https://www.w3.org/WAI/WCAG21/Understanding/), [2.0 Understanding](https://www.w3.org/TR/UNDERSTANDING-WCAG20/)) has additional guidance on learning and implementing WCAG 2 for people who want to understand the guidelines and success criteria more thoroughly.

For more details on how these document are related and how they are linked, see **[[The WCAG 2 Documents]](/standards-guidelines/wcag/docs/)**.

### Translations

Authorized Translations and unofficial translations of WCAG 2 are listed in [[WCAG 2 Translations]](/standards-guidelines/wcag/translations/).

### Technical document format

The WCAG, Techniques, and Understanding documents follow the W3C format for technical reports, which has several sections at the beginning, including links to different versions, editors, abstract, and status.

### Supplemental guidance {#supplement}

Supplemental guidance provides additional information beyond what is required in WCAG 2.0 and 2.1. It addresses improving accessibility for people with cognitive disabilities and people with low vision. Links to supplemental guidance will be added to this section in the future.

## WCAG 2.0 is ISO/IEC 40500 {#iso}

WCAG 2.0 is approved as an ISO standard: ISO/IEC 40500:2012. ISO/IEC 40500 is exactly the same as the original WCAG 2.0, which is introduced above along with supporting resources.

The content of ISO/IEC 40500 is freely available from [www.w3.org/TR/WCAG20](http://www.w3.org/TR/WCAG20/); it is available for purchase from the [ISO catalogue {% include_cached external.html %}](http://www.iso.org/iso/iso_catalogue/catalogue_tc/catalogue_detail.htm?csnumber=58625).

Benefits of WCAG 2.0 as an ISO standard are summarized in [ISO in the FAQ](/standards-guidelines/wcag/faq/#iso). More information on W3C and the ISO process is in the [W3C PAS FAQ](http://www.w3.org/2010/04/pasfaq).

## Other guidelines {#components}

WCAG is part of a series of accessibility guidelines, including the Authoring Tool Accessibility Guidelines (ATAG) and the User Agent Accessibility Guidelines (UAAG). [[Essential Components of Web Accessibility]](/fundamentals/components/) explains the relationship between the different guidelines.

## Who develops WCAG {#wg}

The WCAG technical documents are developed by the Accessibility Guidelines Working Group ([AG WG](https://www.w3.org/WAI/GL/)) *(formerly the Web Content Accessibility Guidelines Working Group)*, which is part of the World Wide Web Consortium ([W3C](http://www.w3.org)) Web Accessibility Initiative ([WAI](https://www.w3.org/WAI/)).

WAI updates Techniques for WCAG 2 and Understanding WCAG 2 periodically. We welcome [comments](/standards-guidelines/wcag/commenting/) and [submission of new techniques](http://www.w3.org/WAI/GL/WCAG20/TECHS-SUBMIT/).

Opportunities for contributing to WCAG and other WAI work are introduced in [[Participating in WAI]](/about/participating/).

## More Information {#more}

See the [[WCAG 2 FAQ]](/standards-guidelines/wcag/faq/) for more information on:

-   **WCAG 2 coverage of [mobile accessibility](/standards-guidelines/wcag/faq/#mobile)**
-   **WCAG 2 applicability to [non-W3C technologies](/standards-guidelines/wcag/faq/#othertechs)**
-   and more...
