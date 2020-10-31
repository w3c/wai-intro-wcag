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
  <p><strong>Date: DRAFT in-progress</strong> Updated 31 October 2020. </p>
  <p><strong>Editor:</strong> <a href="http://www.w3.org/People/Shawn/">Shawn Lawton Henry</a>. Contributors: Jeanne Spellman.</p>
  <p>Developed with input from the Accessibility Guidelines Working Group (<a href="https://www.w3.org/WAI/about/groups/agwg/">AG WG</a>), Silver Task Force, Silver Community Group, and the Education and Outreach Working Group (<a href="https://www.w3.org/WAI/about/groups/eowg/">EOWG</a>).</p>

inline_css: |
  #toc li {
    padding-top:0; padding-bottom:0;
    margin-top:0; margin-bottom:0;  }
  .smalltext {
    font-size: .875rem;
  }

---

{::nomarkdown}
{% include box.html type="start" h="2" title="Summary" class="full" %}
{:/}

This page introduces the [W3C Accessibility Guidelines (WCAG) 3.0 Working Draft](https://www.w3.org/TR/WCAG30). It explains how WCAG 3 is related to WCAG 2. It helps you get started learning about WCAG 3.

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
{:.no_toc}

The WCAG documents explain how to make websites, web apps, tools, and documents more accessible to people with disabilities. _(The rest of this page uses “website” for simplicity, yet WCAG applies more broadly than websites.)_

WCAG is developed through the [W3C process](https://www.w3.org/WAI/standards-guidelines/w3c-process/) in cooperation with individuals and organizations around the world, to provide a single shared standard for website accessibility that meets the needs of individuals, organizations, and governments internationally.

The current version, WCAG 2, is introduced in the [Web Content Accessibility Guidelines (WCAG) Overview](https://www.w3.org/WAI/standards-guidelines/wcag/).

## Status: Draft for Review

W3C Accessibility Guidelines (WCAG) 3 is currently an incomplete, unpolished Working Draft. It includes:
* proposed structure
* proposed conformance model
* 5 draft example guidelines

<div style="float: right; margin-left: 2rem; width: 30%; max-width: 220px">
<svg id="dialog" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 150 150">
<path d="M82,82v4c0,3.3-2.7,6-6,6H40.4H39L38,92.8l-13,10V96v-4h-4h-4c-3.3,0-6-2.7-6-6V44c0-3.3,2.7-6,6-6h23v-4H17  c-5.5,0-10,4.5-10,10v42c0,5.5,4.5,10,10,10h4v15l19.4-15H76c5.5,0,10-4.5,10-10v-4H82z" fill="#005A6A"/>
<path d="M111,22c3.3,0,6,2.7,6,6v42c0,3.3-2.7,6-6,6h-4h-4v4v6.9l-13-10L89,76h-1.4H52c-3.3,0-6-2.7-6-6V28  c0-3.3,2.7-6,6-6H111 M111,18H52c-5.5,0-10,4.5-10,10v42c0,5.5,4.5,10,10,10h35.6L107,95V80h4c5.5,0,10-4.5,10-10V28  C121,22.5,116.5,18,111,18L111,18z" fill="#003366"/>
</svg>
</div>

We are seeking input from evaluators, developers, designers, project managers, policy makers, people with disabilities, and others &mdash; particularly on:
* Is this structure clear?
* How does this conformance model work in practice?
* And specific questions in [WCAG 3.0 FPWD Review Guidance](@@).

It will take some time to understand the proposed new structure and conformance model in this  WCAG 3 draft.
* If you are interested in helping shape WCAG 3, we encourage you to spend time reviewing this draft and submit comments 21@@ January 2021.
* If you want to wait until WCAG 3 is more polished and stable to start learning it, you can read later drafts in 2021.

Later drafts of WCAG 3 will have most of the accessibility requirements (“success criteria”) from WCAG 2 and will have additional accessibility requirements, including some from <abbr title="Authoring Tool Accessibility Guidelines">[ATAG](https://www.w3.org/WAI/standards-guidelines/atag/)</abbr> and <abbr title="User Agent Accessibility Guidelines">[UAAG](https://www.w3.org/TR/UAAG20/)</abbr>.

## Approach

_Reminder that WCAG 3 applies to websites, web apps, tools, documents, and such digital technology. Most of this page uses “website” for simplicity._

<div style="float: right; margin-left: 2rem; width: 30%; max-width: 220px">
<svg id="brain" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 150 150"><defs><style>.cls-1{fill:#005A6A;}</style></defs><path class="cls-1" d="M81,133h-.22a2.5,2.5,0,0,1-2.28-2.7c.36-4.07,1.46-9.76,4.73-13.79,4.9-6.06,17.17-5.92,21.2-5.88h.55c2.54,0,4.24-.73,5.19-2.23.65-1,.45-1.5,0-2.66a8.83,8.83,0,0,1-.59-1.84c-.28-1.68.68-3.24,1.7-4.9.29-.47.73-1.18,1-1.69a8.37,8.37,0,0,0-2-.61,2.5,2.5,0,0,1,0-4.93,19.22,19.22,0,0,0,3.35-.86c-.08-.32-.19-.71-.28-1a17.72,17.72,0,0,1-.68-3.06c-.32-2.85,2.32-4,3.73-4.53,1.94-.81,2.56-1.24,2.65-2.34.17-2.12-2.38-5.61-4.24-8.16-1.51-2.06-2.7-3.69-3.11-5.18a21.39,21.39,0,0,1-.26-5.5c.08-4.31.21-10.21-1.82-15.92-1.61-4.55-11.33-27-44.29-22.26C53.71,24.58,44.71,29.8,39.26,38s-6.92,18.82-4.07,29.82a31.75,31.75,0,0,0,5.94,11.63c3.33,4.6,6.78,9.36,5.94,19.92a56.45,56.45,0,0,1-4.32,17.39c-.33.84-.62,1.56-.81,2.12a2.5,2.5,0,1,1-4.74-1.59c.23-.69.54-1.47.9-2.38a51,51,0,0,0,4-15.94c.69-8.72-1.82-12.19-5-16.58a36.6,36.6,0,0,1-6.73-13.32c-3.21-12.39-1.52-24.41,4.75-33.84S51.55,19.84,64.56,18c36.81-5.31,47.87,20.33,49.71,25.52,2.33,6.58,2.2,13.28,2.1,17.71a23.36,23.36,0,0,0,.1,4.07,21.08,21.08,0,0,0,2.31,3.55c2.46,3.36,5.52,7.54,5.2,11.52-.36,4.31-3.84,5.76-5.72,6.54l-.53.23c.1.46.23.91.36,1.36.43,1.48.87,3,.24,4.59a3.58,3.58,0,0,1-1.56,1.78,3.84,3.84,0,0,1,.54,1.5c.26,1.83-.81,3.58-1.85,5.27a17.24,17.24,0,0,0-1,1.67c.06.17.15.37.22.54a7.2,7.2,0,0,1-.38,7.25c-1.32,2.07-4,4.54-9.41,4.54h-.6c-11.49-.1-15.72,2.12-17.27,4-2.59,3.21-3.38,8.31-3.62,11.07A2.51,2.51,0,0,1,81,133Zm32.69-41.61Zm.43-.75Z"/><path class="cls-1" d="M62.5,93.41h-.08l-3.21-.11a2.5,2.5,0,0,1-1.93-1,2.54,2.54,0,0,1-.4-2.15c1.45-5.23,2.06-9.71,1.75-12.75A16.83,16.83,0,0,1,46,73.8c-4.14-3.42-6.52-8.93-6.52-15.11a28.8,28.8,0,0,1,8.61-20.14c4.39-4.41,12.32-9.66,25.09-9.66,20.93,0,30.35,12.54,30.35,21.44,0,13.19-10.76,14.59-17.15,14.74a11.84,11.84,0,0,1-4.94,7.28,10.69,10.69,0,0,1-8.32,1.15C70,77.17,67.62,83.7,64.87,91.72A2.51,2.51,0,0,1,62.5,93.41ZM60.59,72.09A2.51,2.51,0,0,1,63,73.78a18.32,18.32,0,0,1,.71,6.65c2-5,4.17-8.89,7-11.56a2.5,2.5,0,0,1,2.5-.56c2.32.77,4.22.71,5.64-.19,1.6-1,2.71-3.14,3.07-5.85a2.49,2.49,0,0,1,2.48-2.18c9.21,0,14.21-1.56,14.21-9.76,0-6.63-8.06-16.44-25.35-16.44-11.06,0-17.83,4.45-21.56,8.19a23.8,23.8,0,0,0-7.14,16.6c0,4.7,1.71,8.8,4.7,11.26,2.76,2.28,6.53,3,10.9,2.19A2.56,2.56,0,0,1,60.59,72.09Z"/></svg>
</div>

### Goals, Similar, Different {#compare}

**Goals** for WCAG 3 include:
* be easier to understand
* cover more user needs, including more needs of people with cognitive disabilities
* be flexible to address different types of websites, apps, tools, and organizations

<span style="font-style:italic; margin-left:22px;">(More goals are a [blog post](https://www.@@) and [spec requirements doc](https://www.@@).)</span>

WCAG 3 is **similar** to previous versions in some ways. It has similar:
* goal of providing guidance on making websites, apps, etc. accessible to people with disabilities
* fundamental and specific accessibility requirements

WCAG 3 is very **different** from previous versions in some ways. It has:
* different structure
* different conformance model
* broader scope, beyond just web content

### Structure

WCAG 3 has:
* **Guidelines**
   * Solutions to accessibility problems
   * More **granular** than the guidelines in WCAG 2
* **Outcomes**
   * Testable statements
   * Similar to **success criteria** in WCAG 2
   * Each outcome includes:
      * Critical errors
      * Rating scale

{::nomarkdown}
{% include box.html type="start" class="simple aside" %}
{:/}

_Draft example:_

Guideline: Structured content
* Outcome: Headings organize content
* Outcome: Uses visually distinct headings
* Outcome: Conveys hierarchy with semantic structure
* Outcome: …

{::nomarkdown}
{% include box.html type="end" %}
{:/}


WCAG 3 supporting material includes:
* **Methods**
   * Technology-specific ways to achieve an outcome
   * Tests for the outcome
   * Similar to **Techniques** for WCAG 2
* **How-To documents**
   * Explain more about each outcome??guideline, such as how it addresses accessibility needs
   * Similar to the **Understanding** documents for WCAG 2
* Functional Needs
   * Lists needs of people with disabilities

### Conformance Model {#model}

The “conformance model” is the way to determine and communicate how well a website meets WCAG. The WCAG 3 conformance model has been @@re-imagined to encourage more accessible user experiences and to be more flexible for organizations (that is, owners/developers of websites, apps, etc.).

<s>
With WCAG 2, the success criteria is basically pass or fail. If a website does not pass all success criteria at the set level, then the website does not conform to WCAG 2. For example, if one inconsequential image on an unimportant, rarely-visited page is missing alt text, then technically the website as a whole does not pass WCAG 2 Level A. Yet, in this example, that one missing alt has essentially no impact on the accessibility of the website for users. Whereas, missing alt elsewhere on the website could significantly impact accessibility.
</s>

The WCAG 3 conformance model is an effort to address situations such as @@that example &mdash; to benefit both users and website providers. @@Some new aspects of the proposed WCAG 3 conformance model:
* Conformance is more focused on **[processes](@@)** (which are tasks such as ordering an item or registering for a class), rather than web pages.
* Outcomes can be rated, beyond just pass or fail.
* @@ more here…

<span class="smalltext" style="padding-bottom:0; margin-bottom:0;"><em>Draft example: </em>Rating scale for the outcome "Conveys hierarchy with semantic structure":
</span>
<table class="dense quiet smalltext rating-table">
  <thead>
    <tr>
      <th scope="col">Rating</th>
      <th scope="col">Criteria</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th scope="row"> 0</th>
      <td>25% or less of the visual headings are correctly semantically coded (including level) OR there is a <a href="#dfn-critical-error" class="internalDFN" data-link-type="dfn" id="ref-for-dfn-critical-error-18" title="An accessibility problem that will stop a user from being able to complete a process.">critical error</a> in the <a href="#dfn-process" class="internalDFN" data-link-type="dfn" id="ref-for-dfn-process-19" title="A sequence of steps that need to be completed in order to accomplish an activity / task from end-to-end.">process</a></td>
    </tr>
    <tr>
      <th scope="row"> 1</th>
      <td>26-50% or less of the visual headings are correctly semantically coded (including level) AND no <a href="#dfn-critical-error" class="internalDFN" data-link-type="dfn" id="ref-for-dfn-critical-error-19" title="An accessibility problem that will stop a user from being able to complete a process.">critical errors</a> in the <a href="#dfn-process" class="internalDFN" data-link-type="dfn" id="ref-for-dfn-process-20" title="A sequence of steps that need to be completed in order to accomplish an activity / task from end-to-end.">process</a></td>
    </tr>
    <tr>
      <th scope="row"> 2</th>
      <td>51-80% or less of the visual headings are correctly semantically coded (including level) AND no <a href="#dfn-critical-error" class="internalDFN" data-link-type="dfn" id="ref-for-dfn-critical-error-20" title="An accessibility problem that will stop a user from being able to complete a process.">critical errors</a> in the <a href="#dfn-process" class="internalDFN" data-link-type="dfn" id="ref-for-dfn-process-21" title="A sequence of steps that need to be completed in order to accomplish an activity / task from end-to-end.">process</a></td>
    </tr>
    <tr>
      <th scope="row"> 3</th>
      <td>81-95% or less of the visual headings are correctly semantically coded (including level) AND no <a href="#dfn-critical-error" class="internalDFN" data-link-type="dfn" id="ref-for-dfn-critical-error-21" title="An accessibility problem that will stop a user from being able to complete a process.">critical errors</a> in the <a href="#dfn-process" class="internalDFN" data-link-type="dfn" id="ref-for-dfn-process-22" title="A sequence of steps that need to be completed in order to accomplish an activity / task from end-to-end.">process</a></td>
    </tr>
    <tr>
      <th scope="row"> 4</th>
      <td>96-100% or less of the visual headings are correctly semantically coded (including level) AND no <a href="#dfn-critical-error" class="internalDFN" data-link-type="dfn" id="ref-for-dfn-critical-error-22" title="An accessibility problem that will stop a user from being able to complete a process.">critical errors</a> in the <a href="#dfn-process" class="internalDFN" data-link-type="dfn" id="ref-for-dfn-process-23" title="A sequence of steps that need to be completed in order to accomplish an activity / task from end-to-end.">process</a></td>
    </tr>
  </tbody>
</table>

## Development

You can learn about the WCAG 3 goals, user research, development process, and more from this blog post:<br>[WCAG 3.0 Background — How we got from Silver to the First Public Working Draft](https://www.@@)

### WCAG 3 Name (formerly "Silver" project)

WCAG 3 developed from the “Silver” project. The name “W3C Accessibility Guidelines (WCAG)” was chosen:
* because of wide-spread familiarity with the “WCAG” acronym
* to encompass the broader scope beyond “content” &mdash; WCAG 3 includes web authoring tools and web browsers

### Timeline

2020: The First Public Working Draft of WCAG 3.0 was published in November 2020.

2021-2022: Work will first focus on refining the structure and conformance model. Once that is more stable, the accessibility requirements (guidelines, outcomes, etc.) will be developed. A complete draft may be available in late 2022.

2023: WCAG 3.0 may be published as a final standard in late 2023.

WCAG 3 will not supersede WCAG 2 and WCAG 2 will not be deprecated for at least several years.

### Who Develops WCAG 3

The WCAG technical documents are developed by the Accessibility Guidelines Working Group ([AG WG](https://www.w3.org/WAI/GL/)) with the AG WG Silver Task Force and the Silver Community Group. These Groups are part of the World Wide Web Consortium ([W3C](http://www.w3.org)) Web Accessibility Initiative ([WAI](https://www.w3.org/WAI/)).

We welcome your [comments](/standards-guidelines/wcag/commenting/) on the WCAG 3 Working Drafts, per [Status: Draft for Review above](#status-draft-for-review).

Opportunities for contributing more directly to WCAG and other WAI work are introduced in [[Participating in WAI]](/about/participating/).

{% include_cached excol.html type="start" id="background" %}

### Background: How we got from Silver to the First Public Working Draft

This section explains more about the goals, user research, development process, and example guidelines.

{% include_cached excol.html type="middle" %}

#### Research with People Who Use WCAG

In 20@@, project “Silver” was launched to explore a new approach to accessibility guidelines, through the AG WG Silver Task Force and the Silver Community Group. The groups conducted 18 months of research to identify stakeholders and understand their needs for accessibility guidance. The results where that generally WCAG users {@@liked the guidance that is in WCAG 2}, yet many users thought that WCAG 2 {@@grammar fix needed}:
*  difficult to understand
* too restrictive to include some requirements to address the needs of some people with disabilities, particularly cognitive disabilities
* conformance model didn’t meet their organization’s specific needs

Silver held a Design Sprint in 2018 with 27 industry leaders across a variety of accessibility stakeholders. The two-day workshop took the problem statements identified by the research, and challenged participants to come up with innovative solutions. Silver made many prototypes of possible solutions and iterated through options with input from AG WG participants.

The results form the basis of the WCAG 3.0 Working Draft.

#### Goals {#goalsmore}

From the WCAG-user research, Silver defined goals for next generation of accessibility guidelines from W3C WAI. They include:
* Able to address more needs of people with disabilities
* Account for the different impacts of specific accessibility issues on the real-world user experiences of people with disabilities
* Easier to understand and easier to use, especially by people who are not technical
* Flexible conformance model to work well for very different types of websites, apps, tools, &mdash; as well as organizations and people with disabilities
* Enable minor bugs and oversight by content authors that do not significantly impact the accessible user experience to not invalidate conformance to WCAG
* Encourage organizations to continue to improve accessibility (rather than stopping with WCAG 2 Level AA)

#### Development Process

In defining the accessibility requirements in WCAG 3.0, Silver started fresh with a list of accessibility needs of people with disabilities. Development goes through this process:
1. From a specific user need, write an outcome to meet that user need.
2. Define tests to determine if the outcome is met.
3. Write the method to meet the outcome.
4. Group the outcomes under guidelines. [@@correct?]
5. Write the How-To support information.

#### _Examples_ {#eg-guidelines}

The draft guidelines included in the First Public Working Draft were selected to illustrate specific aspects of the proposed structure of WCAG 3 and relationship with WCAG 2.
* Migrating a WCAG 2 success criterion as is into a WCAG 3 outcome: [Text alternatives]( https://w3c.github.io/silver/guidelines/#text-alternatives)
* Merging multiple AA and AAA success criteria into a single WCAG 3 guideline: [Visual contrast of text]( https://w3c.github.io/silver/guidelines/#visual-contrast-of-text)
* Adding new accessibility requirements that did not fit the parameters for being included in WCAG 2: [Clear words](https://w3c.github.io/silver/guidelines/#clear-words)
* Integrating WCAG 2 content with significant updates: [Structured content](https://w3c.github.io/silver/guidelines/#structured-content)
* Adapting WCAG 2 success criteria to emerging technologies, such as virtual reality: [Captions](https://w3c.github.io/silver/guidelines/#captions)

These guidelines are rough draft examples, and will be refined and edited in future Working Drafts.

{% include_cached excol.html type="end" %}
