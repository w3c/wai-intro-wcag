---
# Translation info https://www.w3.org/wiki/WAI/Website/Translate

title: "Web Content Accessibility Guidelines (WCAG) Overview"
nav_title: "Web Content – WCAG"

description: Introduces the Web Content Accessibility Guidelines (WCAG) international standard, including WCAG 2.0 and WCAG 2.1. WCAG documents explain how to make web content more accessible to people with disabilities.

lang: en
last_updated: 2022-02-01

permalink: /standards-guidelines/wcag/

github:
  repository: w3c/wai-intro-wcag
  path: 'content/index.md'

footer: >
  <p><strong>Date:</strong> Updated 1 February 2022. First published July 2005.</p>
  <p><strong>Editor:</strong> <a href="http://www.w3.org/People/Shawn/">Shawn Lawton Henry</a>.</p>
  <p>Developed with input from the Education and Outreach Working Group (<a href="https://www.w3.org/WAI/about/groups/eowg/">EOWG</a>) and the Accessibility Guidelines Working Group (<a href="https://www.w3.org/WAI/about/groups/agwg/">AG WG</a>).</p>
image: /content-images/wai-intro-wcag/wcag-intro-social.jpg
feedbackmail: wai@w3.org  
ref: /standards-guidelines/wcag/

---

{::nomarkdown}
{% include box.html type="start" h="2" title="Summary" class="full" %}
{:/}

This page introduces the Web Content Accessibility Guidelines (WCAG), including WCAG 2.0, WCAG 2.1, and WCAG 2.2.

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

## Introduction {#intro}

Web Content Accessibility Guidelines (WCAG) is developed through the [W3C process](/standards-guidelines/w3c-process/) in cooperation with individuals and organizations around the world, with a goal of providing a single shared standard for web content accessibility that meets the needs of individuals, organizations, and governments internationally.

The WCAG documents explain how to make web content more accessible to people with disabilities. Web "content" generally refers to the information in a web page or web application, including:

-   natural information such as text, images, and sounds
-   code or markup that defines structure, presentation, etc.

## WCAG 2.0, 2.1, 2.2  {#versions}

The Web Content Accessibility Guidelines (WCAG) standards are stable and referenceable; they do not change after they are published.

**[WCAG 2.0](https://www.w3.org/TR/WCAG20/)** was published on 11 December 2008. <br>**[WCAG 2.1](https://www.w3.org/TR/WCAG21/)**  was published on 5 June 2018. <br>WCAG 2.2 is scheduled to be published by June 2022.

All requirements ("success criteria") from 2.0 are included in 2.1. The 2.0 success criteria are exactly the same (verbatim, word-for-word) in 2.1. <br>All requirements in 2.0 and 2.1 will be included in 2.2. The wording of the 2.0 and 2.1 success criteria will be exactly the same in 2.2.

There are additional success criteria in 2.1 that are not in 2.0. They are introduced in [[What's New in WCAG 2.1]](/standards-guidelines/wcag/new-in-21/). <br>The proposed new success criteria in 2.2 are introduced in [[What's New in WCAG 2.2 Working Draft]](/standards-guidelines/wcag/new-in-22/).

**Content that conforms to WCAG 2.1 also conforms to WCAG 2.0**.<br>And content that conforms to WCAG 2.2 will also conform to 2.1 and 2.0. (This is often called “backwards compatible”.) A website that meets WCAG 2.1 or 2.2 should meet the requirements of policies that reference WCAG 2.0. To put it another way: If you want to meet both WCAG 2.0 and WCAG 2.1, you can use the 2.1 resources and you don't need to bother looking at 2.0.

WCAG 2.0 and WCAG 2.1 are both existing standards. WCAG 2.1 does not deprecate or supersede WCAG 2.0. W3C encourages you to use the most recent version of WCAG when developing or updating content or accessibility policies.

## Who WCAG is for {#for}

WCAG is for those who want a technical standard. It is not an introduction to accessibility. **For links to introductory material, see [“Where should I start?” in the FAQ](/standards-guidelines/wcag/faq/#start).**

WCAG is primarily intended for:

-   Web content developers (page authors, site designers, etc.)
-   Web authoring tool developers
-   Web accessibility evaluation tool developers
-   Others who want or need a standard for web accessibility, including for mobile accessibility

To meet the needs of others &mdash; including policy makers, managers, and researchers &mdash; there are many different [[WAI Resources]](/resources/).

## What is in WCAG 2 {#whatis2}

The WCAG standards have 12-13 guidelines. The guidelines are organized under [4 principles: perceivable, operable, understandable, and robust](https://www.w3.org/WAI/WCAG21/Understanding/intro#understanding-the-four-principles-of-accessibility).

For each guideline, there are testable *success criteria*. The success criteria are at [three levels: A, AA, and AAA](https://www.w3.org/WAI/WCAG21/Understanding/conformance#levels).

The success criteria are what determine "conformance" to WCAG. That is, in order to meet WCAG, the content needs to meet the success criteria.

For a short summary of the WCAG 2 guidelines, see **[[WCAG 2 at a Glance]](/standards-guidelines/wcag/glance/)**.

### Supporting material and supplemental guidance {#supplement}

These resources help you understand and implement WCAG, and improve accessibility beyond WCAG:
* Quick Reference / How to Meet WCAG 2 / Checklist
* Understanding WCAG 2
* Techniques for WCAG 2
* Test Rules for WCAG 2
* Supplemental Guidance

**Learn more about these WCAG 2 resources from [WCAG 2 Guidance Documents](/standards-guidelines/wcag/docs/).**

## Translations

Authorized Translations and unofficial translations of WCAG 2 are listed in [[WCAG 2 Translations]](/standards-guidelines/wcag/translations/).

## WCAG 2.0 is ISO/IEC 40500 {#iso}

WCAG 2.0 is approved as an ISO standard: ISO/IEC 40500:2012. ISO/IEC 40500 is exactly the same as the original WCAG 2.0, which is introduced above along with supporting resources.

The content of ISO/IEC 40500 is freely available from [www.w3.org/TR/WCAG20](http://www.w3.org/TR/WCAG20/); it is available for purchase from the [ISO catalogue {% include_cached external.html %}](http://www.iso.org/iso/iso_catalogue/catalogue_tc/catalogue_detail.htm?csnumber=58625).

Benefits of WCAG 2.0 as an ISO standard are summarized in [ISO in the FAQ](/standards-guidelines/wcag/faq/#iso). More information on W3C and the ISO process is in the [W3C PAS FAQ](http://www.w3.org/2010/04/pasfaq).

## Who develops WCAG {#wg}

The WCAG technical documents are developed by the Accessibility Guidelines Working Group ([AG WG](https://www.w3.org/WAI/GL/)) *(formerly the Web Content Accessibility Guidelines Working Group)*, which is part of the World Wide Web Consortium ([W3C](http://www.w3.org)) Web Accessibility Initiative ([WAI](https://www.w3.org/WAI/)).

WAI updates Techniques for WCAG 2 and Understanding WCAG 2 periodically. We welcome [comments](/standards-guidelines/wcag/commenting/) and [submission of new techniques](http://www.w3.org/WAI/GL/WCAG20/TECHS-SUBMIT/).

Opportunities for contributing to WCAG and other WAI work are introduced in [[Participating in WAI]](/about/participating/).

## More Information {#more}

WCAG is part of a series of accessibility guidelines, including the Authoring Tool Accessibility Guidelines (ATAG) and the User Agent Accessibility Guidelines (UAAG). [[Essential Components of Web Accessibility]](/fundamentals/components/) explains the relationship between the different guidelines.

See the [[WCAG 2 FAQ]](/standards-guidelines/wcag/faq/) for more information on:

-   **WCAG 2 coverage of [mobile accessibility](/standards-guidelines/wcag/faq/#mobile)**
-   **WCAG 2 applicability to [non-W3C technologies](/standards-guidelines/wcag/faq/#othertechs)**
-   **[WCAG 3.0 ("Silver")](/standards-guidelines/wcag/faq/#next)**
-   and more...
