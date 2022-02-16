---
# Translation info https://www.w3.org/wiki/WAI/Website/Translate

title: "testing- WCAG 3 Introduction"
nav_title: "WCAG 3 Draft"

description: Introduces the W3C Accessibility Guidelines (WCAG) 3.0 Working Draft. WCAG documents explain how to make the web more accessible to people with disabilities.
image: /content-images/wai-intro-wcag/wcag3_social.png

lang: en

last_updated: 2021-06-08
permalink: /standards-guidelines/wcag/wcag3-intro/

github:
  repository: w3c/wai-intro-wcag
  path: 'content/wcag3-intro.md'

ref: /standards-guidelines/wcag/wcag3-intro/

feedbackmail: wai@w3.org
footer: >
  <p><strong>Date: </strong>Updated 8 June 2021.</p>
  <p><strong>Editor:</strong> <a href="http://www.w3.org/People/Shawn/">Shawn Lawton Henry</a>. Contributors: Jeanne Spellman.</p>
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

WCAG 3 is currently an incomplete draft. It is intended to develop into a W3C Standard **in a few years**. The current standard, WCAG 2, is introduced in the [Web Content Accessibility Guidelines (WCAG) Overview](https://www.w3.org/WAI/standards-guidelines/wcag/).

The WCAG 3 documents explain how to make the web more accessible to people with disabilities. WCAG 3 applies to web content, apps, tools, publishing, and emerging technologies on the web. _(The rest of this page uses “website” for simplicity, yet WCAG applies more broadly than websites.)_

This page will be updated regularly as work on the WCAG 3 Draft progresses.

## Status: Draft for Review

[W3C Accessibility Guidelines (WCAG) 3.0 Working Draft](https://www.w3.org/TR/wcag-3.0/) is currently an **incomplete, unpolished Draft**. It includes:
* proposed structure
* draft [conformance model](#model)
* 5 [draft example guidelines](#eg-guidelines)

<img src="{{ "/content-images/wai-intro-wcag/dialogs2.svg" | relative_url }}" alt="" style="float: right; margin-left: 2rem; width: 30%; max-width: 220px">

We are seeking input from evaluators, developers, designers, project managers, policy makers, people with disabilities, and others &mdash; particularly on:
* Is this structure clear and useful?
* How well does this draft conformance model work across different situations?
* Other specific questions throughout the draft.

We also welcome comments on the goals and parameters in [Requirements for WCAG 3.0](https://www.w3.org/TR/wcag-3.0-requirements/).

Additionally, we welcome comments on ways that the Accessibility Guidelines Working Group can better support your review, feedback, or inclusion in the process of creating WCAG 3. 

It will take you some time to understand the proposed new structure and conformance model in this WCAG 3 draft.
* If you are interested in helping shape WCAG 3, we encourage you spend time reviewing this draft and submit comments. Before you review and comment on the Working Draft, please read through this page, including the [background](#background) and [review and commenting](#comments) sections near the end.
* If you want to wait until WCAG 3 is more polished and stable to start learning it, you can read later drafts in 2021 or 2022.

Later drafts of WCAG 3 will have most of the accessibility requirements (“success criteria”) from WCAG 2 and will have additional accessibility requirements, including some from <abbr title="Authoring Tool Accessibility Guidelines">[ATAG](https://www.w3.org/WAI/standards-guidelines/atag/)</abbr> and <abbr title="User Agent Accessibility Guidelines">[UAAG](https://www.w3.org/WAI/standards-guidelines/uaag/)</abbr>.

## WCAG 3 Draft Approach

_Reminder that WCAG 3 applies to web content, apps, tools, publishing, and emerging technologies on the web. Most of this page uses “website” for simplicity._

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
* broader scope, beyond just web content

### Structure

<div style="float: right; margin-left: 2rem; width: 40%; max-width: 444px">

{% include box.html type="start" class="simple aside" %}

<p><em>Draft example:</em></p>
<p style="padding-bottom:0; margin-bottom:0;"><em>Guideline</em>: Structured content</p>
<ul style="padding-top:0; margin-top:0;">
  <li><em>Outcome</em>: Headings organize content</li>
  <li><em>Outcome</em>: Uses visually distinct headings</li>
  <li><em>Outcome</em>: Conveys hierarchy with semantic structure</li>
  <li><em>Outcome</em>: … </li>
</ul>

{% include box.html type="end" %}

</div>

This WCAG 3 draft has:
* **Guidelines**
   * Solutions to accessibility problems
   * More **granular** than the guidelines in WCAG 2
   * Each guideline has outcomes
* **Outcomes**
   * Testable statements
   * Similar to **success criteria** in WCAG 2, more granular
   * Outcomes include:
      * Critical errors
      * Rating scale

More _granular_ means they are more specific, instead of broad. That generally makes them simpler. And it means there will be more of them.

WCAG 3 supporting material includes:
* **Methods**
   * Technology-specific ways to achieve an outcome
   * Tests for the outcome
   * Similar to **Techniques** for WCAG 2
* **How-To documents**
   * Explain more about each guideline, such as how it addresses accessibility needs <!-- @@ each outcome or each guideline ? -->
   * Similar to the **Understanding** documents for WCAG 2
* **Functional categories** of **functional needs**
   * Categorized list of needs of people with disabilities

### Draft Conformance Model {#model}

The _conformance model_ is the way to determine and communicate how well a website (or app, tool, etc.) meets WCAG. The conformance model in this draft of WCAG 3 is very different from WCAG 2. It is intended to:
* be more flexible for organizations (that is, owners and developers of websites, apps, tools, etc.)
* encourage more accessible user experiences

The conformance model in the WCAG 3 First Public Working Draft is a starting point for feedback.

There are several different aspects of this draft WCAG 3 conformance model:
* Conformance is more focused on **[processes](https://www.w3.org/TR/wcag-3.0/#processes)** (tasks such as ordering an item or registering for a class), rather than web pages.
* Outcomes can be **rated**, beyond just pass or fail. Rating scale is 0-4.
* The ratings are averaged for a total score. There is also a **score for each functional category** (e.g., vision, hearing, memory, etc.).

The levels are different, too:
* Conformance levels are Bronze, Silver, Gold.
   * In WCAG 2, they are Level A, Level AA, Level AAA.
   * Bronze is similar to WCAG 2 Level AA, although not fully equivalent.
* Bronze conformance requires:
   * No critical errors
   * Total score of 3.5 or higher
   * Score of 3.5 or higher in each functional category
* Silver and Gold levels require “holistic tests” such as assistive technology testing and usability testing with participants with disabilities.

<span class="smalltext" style="padding-bottom:0; margin-bottom:0;"><em>Draft example: </em>Ratings for the outcome "Text alternative available":
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
      <th scope="row">0</th>
      <td>Less than 60% of all images have appropriate text alternatives <em><strong>or</strong></em> there is a critical error in the process</td>
    </tr>
    <tr>
      <th scope="row">1</th>
      <td>60% - 69% of all images have appropriate text alternatives <em><strong>and</strong></em> no critical errors in the process</td>
    </tr>
    <tr>
      <th scope="row">2</th>
      <td>70%-79% of all images have appropriate text alternatives <em><strong>and</strong></em> no critical errors in the process</td>
    </tr>
    <tr>
      <th scope="row">3</th>
      <td>80%-94% of all images have appropriate text alternatives <em><strong>and</strong></em> no critical errors in the process</td>
    </tr>
    <tr>
      <th scope="row">4</th>
      <td>95% to 100% of all images have appropriate text alternatives <em><strong>and</strong></em> no critical errors in the process</td>
    </tr>
  </tbody>
</table>

The conformance model in the 2021 Working Drafts will likely change in future iterations and drafts. It may change a little or may change substantively.

## Development

### Timeline (_updated 8 June 2021_)

<img src="{{ "/content-images/wai-intro-wcag/calandara.svg" | relative_url }}" alt="" style="float: right; margin-left: 2rem; width: 20%; max-width: 111px">

The First Public Working Draft of WCAG 3.0 was published on 21 January 2021. It is the first of many drafts.

The Working Draft published on 8 June 2021 has minor changes: editorial fixes, extended Acknowledgements section, and information moved from the introduction to a separate informative document: [Explainer for W3C Accessibility Guidelines (WCAG) 3.0](https://w3c.github.io/silver/explainer/). **Many [issues are still open](https://github.com/w3c/silver/issues), including testing and conformance.**

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

### Background: How we got from Silver to the WCAG 3 First Public Working Draft {#background}

<div style="float: right; margin-left: 2rem; width: 10%; max-width: 111px">
<img src="https://www.w3.org/WAI/GL/WCAG3/2020/img/silver-sticker" alt="logo: ag w3c a11y silver" style="height: 10ex;" />
</div>

This expandable section provides more about the goals, user research, development process, and draft example guidelines. It introduces the motivations for the changes from WCAG 2 to WCAG 3. **Before you review and comment on the Draft, please read this section for context.**

{% include_cached excol.html type="middle" %}

#### Research with People Who Use WCAG

In 2016, project “Silver” was launched to explore a new approach to accessibility guidelines, through the AG WG Silver Task Force and the Silver Community Group. The groups conducted 18 months of research to identify stakeholders and understand their needs for accessibility guidance. The results where that generally WCAG users felt the guidance in WCAG 2 is important and useful, yet many thought that WCAG 2:
* is difficult to understand
* is too restrictive to include some requirements that address the needs of some people with disabilities, particularly cognitive disabilities
* conformance model doesn’t meet their organization’s specific needs

Silver held a Design Sprint in 2018 with 27 industry leaders across a variety of accessibility stakeholders. The two-day workshop took the problem statements identified by the research, and challenged participants to come up with innovative solutions. Silver made many prototypes of possible solutions and iterated through options with input from AG WG participants.

The results form the basis of the WCAG 3.0 Working Draft.

#### Goals {#goalsmore}

From the WCAG-user research, Silver defined goals for next generation of accessibility guidelines from W3C WAI. They include:
* Able to address more needs of people with disabilities
* Account for the different impacts of specific accessibility issues on the real-world user experiences of people with disabilities
* Easier to understand and easier to use, especially by people who are not technical
* Flexible conformance model to work well for very different types of web content, apps, tools, &mdash; as well as organizations and people with disabilities
* Enable minor bugs and oversight by content authors that do not significantly impact the accessible user experience to not invalidate conformance to WCAG
* Encourage organizations to continue to improve accessibility (rather than stopping with WCAG 2 Level AA)

More about goals is in [Requirements for WCAG 3.0](https://www.w3.org/TR/wcag-3.0-requirements/). We welcome comments on this document, too.

#### Development Process

In defining the accessibility requirements in WCAG 3.0, Silver started fresh with a list of accessibility needs of people with disabilities. Development goes through this process:
1. From a specific user need, write an outcome to meet that user need.
2. Define tests to determine if the outcome is met.
3. Write the method to meet the outcome.
4. Group the outcomes under guidelines. <!-- [@@correct?] -->
5. Write the How-To support information.

#### _**Draft Examples**_ {#eg-guidelines}

The draft guidelines included in the First Public Working Draft were selected to illustrate specific aspects of the proposed structure of WCAG 3 and relationship with WCAG 2.
* [Text alternatives](https://w3c.github.io/silver/guidelines/#text-alternatives) &mdash; Migrating a WCAG 2 success criterion as is into a WCAG 3 outcome
* [Clear words](https://w3c.github.io/silver/guidelines/#clear-words) &mdash; Adding a new accessibility requirement that was considered insufficiently testable for WCAG 2, and can be tested using the WCAG 3 rating scale
* [Captions](https://w3c.github.io/silver/guidelines/#captions) &mdash; Adapting WCAG 2 success criteria to emerging technologies, such as virtual reality, and demonstrating how scoring varies by context
* [Structured content](https://w3c.github.io/silver/guidelines/#structured-content) &mdash; Combining guidance from multiple WCAG 2 success criteria into a new WCAG 3 guideline with multiple outcomes
* [Visual contrast of text](https://w3c.github.io/silver/guidelines/#visual-contrast-of-text) &mdash; Combining guidance from multiple WCAG 2 success criteria, and a new algorithm with support for different situations

These guidelines and outcomes are rough draft examples that will be refined and edited in future Working Drafts.

{% include_cached excol.html type="end" %}

<div class="excol-all"></div>

### Review Questions and Your Comments {#comments}

For specific questions that we would like feedback on, see:
* Questions in the blog post [WCAG 3 FPWD Published, Feedback section](https://www.w3.org/blog/2021/01/wcag-3-fpwd/#feedback).
* Questions in Editor’s Notes throughout the draft.

**To comment on the WCAG 3 draft:**
* Please open a [new GitHub issue in the WCAG 3 (Silver) repository](https://github.com/w3c/silver/issues/new). Create separate GitHub issues for each topic, rather than commenting on multiple topics in a single issue.
* If it’s not feasible for you to use GitHub, send comments in e-mail to: public-silver@w3.org

_We will update this section when we have new questions on new substantive draft content for review._
