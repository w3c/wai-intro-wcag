---
# Translation info https://www.w3.org/wiki/WAI/Website/Translate

title: "WCAG 3 Introduction"
nav_title: "WCAG 3 Draft"

description: Introduces the W3C Accessibility Guidelines (WCAG) 3.0 Working Draft. WCAG documents explain how to make the web more accessible to people with disabilities.
image: /content-images/wai-intro-wcag/wcag3_social.png

lang: en

last_updated: 2022-06-01
permalink: /standards-guidelines/wcag/wcag3-intro/

github:
  repository: w3c/wai-intro-wcag
  path: 'content/wcag3-intro.md'

ref: /standards-guidelines/wcag/wcag3-intro/

feedbackmail: wai@w3.org
footer: >
  <p><strong>Date: </strong>Updated 1 June 2022.</p>
  <p><strong>Editor:</strong> <a href="http://www.w3.org/People/Shawn/">Shawn Lawton Henry</a>. Contributors: Rachael Bradley Montgomery and Jeanne Spellman.</p>
  <p>Developed with input from the Education and Outreach Working Group (<a href="https://www.w3.org/WAI/about/groups/eowg/">EOWG</a>), Accessibility Guidelines Working Group (<a href="https://www.w3.org/WAI/about/groups/agwg/">AG WG</a>), Silver Task Force, and Silver Community Group.</p>

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

This page introduces the in-progress [W3C Accessibility Guidelines (WCAG) 3.0 Working **Draft**](https://www.w3.org/TR/wcag-3.0/). It explains how WCAG 3 is related to WCAG 2.<br>This page is the starting point for information about WCAG 3 now and in the future.

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

WCAG 3 is currently an incomplete draft. It is intended to develop into a W3C Standard **in a few years**. The current standard, Web Content Accessibiilty Guidelines (WCAG 2), is introduced in the [WCAG 2 Overview](https://www.w3.org/WAI/standards-guidelines/wcag/).

The WCAG 3 documents explain how to make the web more accessible to people with disabilities. WCAG 3 applies to web content, apps, tools, publishing, and emerging technologies on the web. 

This page will be updated regularly as work on the WCAG 3 Draft progresses.

## Status: Draft for Review

The first **incomplete, unpolished Draft**, [W3C Accessibility Guidelines (WCAG) 3.0 Working Draft](https://www.w3.org/TR/wcag-3.0/), was published in December 2021. It included:
* proposed structure
* draft [conformance model](#model)
* 5 [draft example guidelines](#eg-guidelines)

The **[latest incomplete, unapproved Editors' Draft](https://w3c.github.io/silver/guidelines/)** is available.

<img src="{{ "/content-images/wai-intro-wcag/dialogs2.svg" | relative_url }}" alt="" style="float: right; margin-left: 2rem; width: 30%; max-width: 220px">

We received a lot feedback and are using that to rewrite the approach. We will use an interative approach to create WCAG 3, that makes content visible at various states of maturity.
Each normative section is given a status. This status indicates how far along in the development process this section is, how ready it is for experimental adoption, and what kind of feedback we are looking for.
* **Placeholder:** This content is temporary. It shows the type of content or section to expect. Placeholder text will be replaced. It is hidden by default in the Editor's draft. No feedback is needed on placeholder content.
* **Exploratory:** The Working Group is exploring what direction to take with this section. This content is not refined; details and definitions may be missing. It is hidden by default in the Editor's draft. We invite feedback on the proposed direction.
* **Developing:** There is rough agreement on what is needed for this section, although not all high-level concerns have been settled. Details are included, yet they are not all agreed on. We invite general feedback on how understandable, usable, and reasonable the section.
* **Refining:** The Working Group has reach consensus on this section. It is ready for broad public review and experimental adoption.  We seek feedback on feasibility and issues with implementations.
* **Mature:** The Working Group thinks this content is ready for the final standard. Feedback should be focused on edge case scenarios the Working Group might not have anticipated.

We seek input from evaluators, developers, designers, project managers, policy makers, people with disabilities, and others.

We also welcome comments on the goals and parameters in [Requirements for WCAG 3.0](https://www.w3.org/TR/wcag-3.0-requirements/).

The best way to provide this feedback is by opening new [GitHub issues](https://github.com/w3c/silver/issues). Alternatively, e-mail public-silver@w3.org

Additionally, we welcome comments on ways that the Accessibility Guidelines Working Group can better support your review, feedback, or inclusion in the process of creating WCAG 3. Please e-mail these to group-ag-chairs@w3.org

## WCAG 3 Draft Approach

<img src="{{ "/content-images/wai-intro-wcag/brain-icon.svg" | relative_url }}" alt="" style="float: right; margin-left: 2rem; width: 30%; max-width: 220px">

### Some Similar, Some Different {#compare}

**Goals** for WCAG 3 include:
* be easier to understand
* cover more user needs, including more needs of people with cognitive disabilities
* be flexible to address different types of web content, apps, tools, and organizations

<span style="font-style:italic; margin-left:22px;">(More goals are later on this page, in the [Background section](#background).)</span>

WCAG 3 is **similar** to previous versions in some ways. It has similar:
* goal of providing guidance on making web content and apps accessible to people with disabilities
* fundamental and specific accessibility requirements

WCAG 3 is very **different** from previous versions in some ways. It has:
* different structure
* different conformance model
* broader scope

### Structure

This WCAG 3 draft has:
* **Guidelines**
   * Solutions to accessibility problems
   * More **granular** than the guidelines in WCAG 2
   * Each guideline has outcomes
* **Outcomes**
   * Testable statements
   * Similar to **success criteria** in WCAG 2, more granular and more focused on desired outcomes than technical means for achieving those outcomes.

More _granular_ means they are more specific, instead of broad. That generally makes them simpler. It also means there will be more of WCAG 3 outcomes than WCAG 2 success criteria.

WCAG 3 supporting material includes:
* **Methods**
   * Technology-specific ways to achieve an outcome
   * Tests for the outcome
   * Similar to **Techniques** for WCAG 2
* **How-To documents**
   * Explain more about each guideline, such as how it addresses accessibility needs <!-- @@ each outcome or each guideline ? -->
   * Information for designers, developers, people new to accessibility, and project planners
   * Similar to the  **Understanding** documents for WCAG 2
* **Functional categories** of **functional needs**
   * Categorized list of needs of people with disabilities

### Draft Conformance Model {#model}

The _conformance model_ is the way to determine and communicate how well a website (or app, tool, etc.) meets WCAG. The conformance model in this draft of WCAG 3 is very different from WCAG 2. It is intended to:
* be more flexible for organizations (that is, owners and developers of websites, apps, tools, etc.)
* encourage more accessible user experiences

We are reworking the conformance model based on feedback and encourage feedback as we iterate. 

## Development

### Timeline

<img src="{{ "/content-images/wai-intro-wcag/calandara.svg" | relative_url }}" alt="" style="float: right; margin-left: 2rem; width: 20%; max-width: 111px">

The First Public Working Draft of WCAG 3.0 was published on 21 January 2021. It is the first of many drafts. 

The Working Draft published on 07 December 2021 has minor changes. **Many [issues are still open](https://github.com/w3c/silver/issues), including testing and conformance.**

The Working Group will focus on refining the structure and conformance model, and will provide updated drafts for review. Once that is more stable, the Group will focus on developing the accessibility requirements (guidelines, outcomes, and support material). After WCAG 3 is more stable, we will provide material to help those wanting to transition to WCAG 3; for example, mapping between WCAG 2 and 3 requirements.

**WCAG 3 is not expected to be a completed W3C standard for a few more years.** WCAG 3 will not supersede WCAG 2, and WCAG 2 will not be deprecated, for at least several years after WCAG 3 is finalized.

We will update this section with more specific timeline information as it is available.

### WCAG 3 Name (formerly "Silver" project)

The name of WCAG 3 is different from WCAG 2:
* WCAG **3** is W3C Accessibility Guidelines
* WCAG **2** is Web Content Accessibility Guidelines
 
“W3C Accessibility Guidelines (WCAG) 3.0” was chosen:
* because of wide-spread familiarity with the “WCAG” acronym
* to encompass the broader scope beyond “content”

### Who Develops WCAG 3

The WCAG technical documents are developed by the Accessibility Guidelines Working Group ([AG WG](https://www.w3.org/WAI/GL/)) with the AG WG Silver Task Force and the Silver Community Group. These Groups are part of the World Wide Web Consortium ([W3C](http://www.w3.org)) Web Accessibility Initiative ([WAI](https://www.w3.org/WAI/)). You can learn about the development process from [[How WAI Develops Accessibility Standards through the W3C Process: Milestones and Opportunities to Contribute]](/standards-guidelines/w3c-process/).

We welcome your [comments on the WCAG 3 Working Drafts](#comments).

Opportunities for contributing more directly to WCAG and other WAI work are introduced in [[Participating in WAI]](/about/participating/).

{% include_cached excol.html type="start" id="background" %}
