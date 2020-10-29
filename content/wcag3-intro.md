---
# Translation info https://www.w3.org/wiki/WAI/Website/Translate

title: "[DRAFT] WCAG 3 Introduction"
nav_title: "3.0 Intro"

description: Introduces the W3C Accessibility Guidelines (WCAG) 3.0 Working Draft. WCAG documents explain how to make the web more accessible to people with disabilities.

lang: en
last_updated: 2020-10-28
permalink: /standards-guidelines/wcag/wcag3-intro/

github:
  repository: w3c/wai-intro-wcag
  path: 'content/wcag3-intro.md'

ref: /standards-guidelines/wcag/wcag3-intro/

feedbackmail: wai@w3.org
footer: >
  <p><strong>Date: DRAFT in-progress</strong> Updated 29 October 2020. </p>
  <p><strong>Editor:</strong> <a href="http://www.w3.org/People/Shawn/">Shawn Lawton Henry</a>. Contributors: Jeanne Spellman.</p>
  <p>Developed with input from the Accessibility Guidelines Working Group (<a href="https://www.w3.org/WAI/about/groups/agwg/">AG WG</a>), Silver Task Force, Silver Community Group, and the Education and Outreach Working Group (<a href="https://www.w3.org/WAI/about/groups/eowg/">EOWG</a>).</p>

inline_css: |
  #toc {
    line-height:1;
  }
  #toc li {
    padding-top:0; padding-bottom:0;
    margin-top:0; margin-bottom:0;  }
  .smalltabletext {
    font-size: .875rem;
  }



---

{::nomarkdown}
{% include box.html type="start" h="2" title="Summary" class="full" %}
{:/}

This page introduces the W3C Accessibility Guidelines (WCAG) 3.0 Working Draft. It explains how WCAG 3 is related to WCAG 2.

{::nomarkdown}
{% include box.html type="end" %}
{:/}

{::nomarkdown}
{% include_cached toc.html type="start" title="Page Contents" class="simple" %}
{:/}

{::options toc_levels="2,3" /}

-   This text will be replaced by the TOC.
{:toc}

{::nomarkdown}
{% include_cached toc.html type="end" %}
{:/}

## Introduction

The WCAG documents explain how to make websites, web apps, tools, and documents more accessible to people with disabilities. _(The rest of this page uses “website” for simplicity, yet WCAG applies more broadly than websites.)_

WCAG is developed through the [W3C process](https://www.w3.org/WAI/standards-guidelines/w3c-process/) in cooperation with individuals and organizations around the world, to provide a single shared standard for website accessibility that meets the needs of individuals, organizations, and governments internationally.

WCAG 2 is introduced in the [Web Content Accessibility Guidelines (WCAG) Overview](https://www.w3.org/WAI/standards-guidelines/wcag/).

### Status: For Review

W3C Accessibility Guidelines (WCAG) 3 is currently an early Working Draft. It includes:
* proposed structure
* proposed conformance model
* 5 draft example guidelines

Later drafts of WCAG 3 will have most of the accessibility requirements (“success criteria”) from WCAG 2 and will have additional accessibility requirements, including some from <abbr title="Authoring Tool Accessibility Guidelines">[ATAG](https://www.w3.org/WAI/standards-guidelines/atag/)</abbr> and <abbr title="User Agent Accessibility Guidelines">[UAAG](https://www.w3.org/TR/UAAG20/)</abbr>.

Guidance on reviewing this draft is in [WCAG 3.0 FPWD Review Questions](@@).


### Better, Similar, Different {#compare}

WCAG 3 is intended to be **better** than previous versions. It strives to:
* be easier to understand
* cover more user needs, including more needs of people with cognitive disabilities
* work better for a wide range of websites and situations

WCAG 3 is **similar** to previous versions in some ways. It has similar:
* goal of providing guidance on making websites, apps, etc. accessible to people with disabilities
* fundamental and specific accessibility requirements

WCAG 3 is **different** from previous versions. It has:
* different structure
* different conformance model
* broader scope, beyond just web content

## Approach

### Structure
WCAG 3 has:
* **Guidelines**
   * Solutions to accessibility problems
   * More **granular** than the guidelines in WCAG 2
* **Outcomes**
   * Testable statements
   * Similar to **success criteria** in WCAG 2

WCAG 3 supporting material includes:
* **Methods**
   * Technology-specific ways to achieve an outcome
   * Ways to rate how well a website meets an outcome
   * Similar to **techniques** for WCAG 2
* **How-To documents**
   * Explain more about each outcome??guideline and how to apply them
   * Similar to the **understanding** documents for WCAG 2
* Functional Needs
   * Lists needs of people with diabilities

### Conformance Model {#model}

The “conformance model” is the way to determine and communicate how well a website meets WCAG. The WCAG 3 conformance model has been re-imagined to better support people with disabilities and organizations (that is, owners/developers of websites, apps, etc.).

{::nomarkdown}
{% include box.html type="start" h="4" title="@@probably shouldn’t have this section highlighting WCAG 2 challenges" class="" %}
{:/}

With WCAG 2, the success criteria is basically pass or fail. If a website does not pass all success criteria at the set level, then the website does not conform to WCAG 2. For example, if one inconsequential image on an unimportant, rarely-visited page is missing alt text, then technically the website as a whole does not pass WCAG 2 Level A. Yet, in this example, that one missing alt has essentially no impact on the accessibility of the website for users. Whereas, missing alt elsewhere on the website could significantly impact accessibility.

{::nomarkdown}
{% include box.html type="end" %}
{:/}

The WCAG 3 conformance model is an effort to address situations such as that example &mdash; to benefit both users and website providers. Some new aspects of the proposed WCAG 3 conformance model:
* Conformance is at the level of "[views](@@)" (e.g., a web page) and "[processes](@@)" (which are tasks such as ordering an item or registering for a class).
* Outcomes can be rated, beyond just pass or fail. For example, ratings for the outcome "Luminance contrast between background and text":

<table class="dense quiet smalltabletext">
  <thead>
    <tr>
      <th scope="col">Rating</th>
      <th scope="col">Criteria</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th scope=“row”>Rating 0</th>
      <td>Any failures on the Advanced Perceptual Contrast Algorithm (APCA) lookup table or the lowest APCA value is more than 15% below the values on the APCA lookup table</td>
    </tr>
    <tr>
      <th scope=“row”>Rating 1</th>
      <td>The lowest APCA value is 10-15% below the values on the APCA lookup table</td>
    </tr>
    <tr>
      <th scope=“row”>Rating 2</th>
      <td>The lowest APCA value is 5-9% below the values on the APCA lookup table</td>
    </tr>
    <tr>
      <th scope=“row”>Rating 3</th>
      <td>The lowest APCA value is 1-4% below the values on the APCA lookup table</td>
    </tr>
    <tr>
      <th scope=“row”>Rating 4</th>
      <td>All reading text meets or exceeds the values on the APCA lookup table </td>
    </tr>
  </tbody>
</table>


## Development

You can learn about the WCAG 3 goals, user research, development process, and more from this blog post: [@@title](https://www.w3.org/blog/@@).

_Reminder that WCAG 3 applies to websites, web apps, tools, documents, and such digital technology. (Most of this page uses “website” for simplicity.)_

### WCAG 3 Name (formerly "Silver" project)

WCAG 3.0 developed from the “Silver” project. The name “W3C Accessibility Guidelines (WCAG)” was chosen:
* because of wide-spread familiarity with the “WCAG” acronym
* to encompass the broader scope beyond “content”

### Timeline

We published the First Public Working Draft of WCAG 3.0 in November 2020. We expect the final WCAG 3.0 standard to be completed after 2022.

WCAG 3 will not supersede WCAG 2 and WCAG 2 will not be deprecated for at least several years.

### Who Develops WCAG 3

The WCAG technical documents are developed by the Accessibility Guidelines Working Group ([AG WG](https://www.w3.org/WAI/GL/)) with the AG WG Silver Task Force and the Silver Community Group. These Groups are part of the World Wide Web Consortium ([W3C](http://www.w3.org)) Web Accessibility Initiative ([WAI](https://www.w3.org/WAI/)).

We welcome your [comments](/standards-guidelines/wcag/commenting/) on the WCAG 3 Working Drafts.

Opportunities for contributing more directly to WCAG and other WAI work are introduced in [[Participating in WAI]](/about/participating/).
