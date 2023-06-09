---
# Translation info https://www.w3.org/wiki/WAI/Website/Translate

title: "[discussion draft] What's New in WCAG 2.2 Draft"
title_html: "[discussion draft] What's New in WCAG 2.2 Draft"
nav_title: "New in 2.2 Draft"

description: This page lists the new success criteria in Web Content Accessibility Guidelines (WCAG) 2.2. It includes quotes from personas to help you understand some aspects of the success criteria.

teaser_text: WCAG 2.2 has 9 additional requirements (“success criteria”) that address the needs of people with cognitive or learning disabilities, mobile devices users, and ebook users. The What’s New in WCAG 2.2 page introduces the new success criteria. It includes quotes from personas to help you understand the issues.

lang: en
last_updated: 2023-05-26
permalink: /standards-guidelines/wcag/new-in-22/

github:
  repository: w3c/wai-intro-wcag
  path: 'content/new-in-22.md'

feedbackmail: wai@w3.org
image: /content-images/wai-intro-wcag/general-social.png
footer: >
  <p><strong>Date:</strong> Updated 26 May 2023.</p>
  <p><strong>Editor:</strong> <a href="https://www.w3.org/People/Shawn/">Shawn Lawton Henry</a>. Contributors: Shadi Abou-Zahra,  <a href="https://www.w3.org/groups/wg/eowg/participants">EOWG Participants</a>, and <a href="https://www.w3.org/groups/wg/ag/participants">AG WG Participants</a>.</p>
  <p>Developed with input from the Education and Outreach Working Group (<a href="https://www.w3.org/WAI/about/groups/eowg/">EOWG</a>) and the Accessibility Guidelines Working Group (<a href="https://www.w3.org/WAI/about/groups/eowg/">AG WG</a>).</p>
inline_css: |
  blockquote {font-style: normal !important;}
  blockquote p:first-of-type:before, blockquote p:last-of-type:after, blockquote dl:last-of-type:after {content: '' !important;margin-left: 0 !important;}
  blockquote.sc {padding: 0 10px 15px 20px;border: solid #ccc 1px;background: #f0f0f0;color: #000; margin: 0;}
  .quotes {margin-bottom: 0;}
  .quotes ul {list-style-type: none;}
  .quotes li>p {display:table-row;}
  .quotes li>p span {display:table-cell;}
  .whatwhy {font-weight: bold; display:table-cell; width: 6em;}
  .issue {font-weight: bold; display:table-cell; width: 6em;}
  q:before {content: open-quote;color: #005a6a;font-weight: bold;}
  q:after {content: close-quote;color: #005a6a;font-weight: bold;}
  .sc dt {
    display: list-item;
    list-style-type: disc;
    float: left;
    font-weight: bold;
    margin-left: 2em;
    margin-right: 1ex;
    margin-top: 0;
  }
  .sc dt:after {
    content: ":";
  }
  /* new start */	
  .sc dl dd {margin: 0 0 0.5em 2em;}
  .sc dd {margin-left: 0;}
  .sc dd {display: block;  margin-inline-start: 40px;}
  /* new end */	
  .sc p:last-of-type {margin-bottom: 1em}
  .sc p:last-child, .sc *:last-child {margin-bottom: 0}
  .sclabel {
    padding: 0;
    margin: 0;
    color: #686868;
  }
  div.note, div.ednote, div.warning {
      margin-top: 1em;
      margin-bottom: 1em;
  }
  .note > p:first-child, .ednote > p:first-child,.warning > p:first-child { margin-top: 0 }
    .note > p:first-child, .ednote > p:first-child,.warning > p:first-child { margin-top: 0 }
  .note, .ednote, .warning {
      padding: .5em;
      border-left-width: 1px;
      border-left-style: solid;
  }
  div.note , div.ednote,  div.warning {
      padding: 1em 1.2em 0.5em;
      margin: 1em 0;
      position: relative;
      clear: both;
  }
  span.note, span.ednote, span.warning { padding: .1em .5em .15em; }
  .note, .ednote {
      border-color: #52e052;
  }
  .note-p {margin-top: 0}
  #markdown-toc ul li {
    margin-bottom: 0;
  }

ref: /standards-guidelines/wcag/new-in-22/

---

{::nomarkdown}
{% include box.html type="start" h="2" title="Summary" class="full" %}
{:/}

This page includes:
* The updated publication schedule for Web Content Accessibility Guidelines (WCAG) 2.2.
* The proposed new success criteria (SC) in WCAG 2.2.
* A brief introduction to each success criteria. **Note:** The "What" does not cover all aspects of the success criteria. The "Why" does not include all users or situations. They are just brief examples.
* Quotes from [personas](#about-the-personas-quotes) to help you understand some aspects of the success criteria.
* Links to Understanding documents that explain the success criteria in detail and provide more examples.

{::nomarkdown}
{% include box.html type="end" %}
{:/}

{::options toc_levels="2,3" /}

{::nomarkdown}
{% include toc.html type="start" title="Page Contents" %}
{:/}

- This will be replaced by an automatically generated TOC when using Markdown formatting.
{:toc}
{::nomarkdown}
{% include toc.html type="end" %}
{:/}

## Introduction, Timeline, Changes

For an introduction to Web Content Accessibility Guidelines (WCAG) and more about versions 2.0 and 2.1, see the [WCAG Overview](/standards-guidelines/wcag/).

WCAG 2.2 is scheduled to be completed and published in 2023 Q3 (July, August, September). Drafts:
* [WCAG 2.2 W3C Candidate Recommendation Draft](https://www.w3.org/TR/WCAG22/) is the published version
* [WCAG 2.2 Editors' Draft](https://w3c.github.io/wcag/guidelines/22/) may include additional proposed changes

The main purpose of "Candidate Recommendation" (CR) is to ensure that the standard can be implemented. It is stable at this stage; however, it could change based on implementation experience. More about Candidate Recommendation and the process for completing WCAG 2.2 is in [How WAI Develops Accessibility Standards through the W3C Process](https://www.w3.org/WAI/standards-guidelines/w3c-process/).

### Comments

We are processing implementations and comments from the Candidate Recommendation publication. We hope that the normative content in WCAG 2.2 itself does not need changes. We will continue to update the Understanding documents based on feedback. To comment, please open a [new issue in the WCAG GitHub repository](https://github.com/w3c/wcag/issues/new). Create separate GitHub issues for each topic, rather than commenting on multiple topics in a single issue. If it’s not feasible for you to use GitHub, send comments in e-mail to: public-agwg-comments@w3.org

### Changes from WCAG 2.1 to WCAG 2.2

The 2.0 and 2.1 success criteria are exactly the same (verbatim, word-for-word) in 2.2, with **one exception**: 4.1.1 Parsing is obsolete and removed from WCAG 2.2. More information is in the [WCAG 2 FAQ, 4.1.1 Parsing](https://www.w3.org/WAI/standards-guidelines/wcag/faq/#parsing411).

The WCAG 2.2 Draft provides 9 additional success criteria from WCAG 2.1. They are included on this page.

### Changes to the 2.2 Draft

Changes from the January 2023 CR to the May 2023 CR include:

* 2.4.7 Focus Visible &mdash; Changed from Level A back to Level AA, as it is in WCAG 2.1.
* 2.4.11, 2.4.12, 2.4.13  &mdash; Changed numbering.
* 2.4.13 Focus Appearance &mdash; Changed to Level AAA. Edited to simplify and be more rigorous.
* 2.5.8 Target Size (Minimum) &mdash; Changed the "Spacing" exception and the "Inline" exception.
* 2.4.12 Focus Not Obscured (Minimum) &mdash; Changed the Notes.
* 3.3.8 Understanding Accessible Authentication (Minimum) &mdash; Added "(Minimum)".

Previous changes are listed in the [changelog](https://www.w3.org/TR/WCAG22/#change-log).

## Guideline 2.4 Navigable

Provide ways to help users navigate, find content, and determine where they are.

### [current] 2.4.11 Focus Not Obscured (Minimum) (AA)
<section class="brief">
      <p>In brief:</p>
      <dl>
         <dt>Objective</dt><dd>Do not hide the item with focus</dd>
         <dt>Author task</dt><dd>The item with focus should be at least partially visible in the viewport</dd>
         <dt>Key beneficiaries</dt><dd>Some users with cognitive disabilities and sighted users reliant on keyboard interaction</dd>
      </dl>
  </section>

### [EOWG draft] 2.4.11 Focus Not Obscured (Minimum) (AA)
In brief:
<div class="quotes">
	<ul>
  <li>
    <p><span class="whatwhy">What to do: </span>Ensure that when items have focus, they are at least partially visible.</p>
  </li>
  <li>
    <p><span class="whatwhy">Why: </span>Some people cannot use a mouse and rely on seeing what has keyboard focus. {@@ can we add a short, clear, specific example for COGA? <a href="https://www.w3.org/WAI/WCAG22/Understanding/focus-not-obscured-minimum#benefits">benefits</a>}</p>
  </li>
</ul>

<p class="persona">For example, a <a href="https://www.w3.org/WAI/people-use-web/user-stories/#reporter">reporter</a> with repetitive stress injury who uses speech recognition software:</p>

  <ul>
    <li>
      <p><span class="issue">Problem:</span><span><q>This page has a big banner that's always across the bottom. <em>(a sticky footer)</em> When I move focus to items, some are hidden behind the banner and I can't see them.</q></span></p>
    </li>
    <li>
      <p><span class="issue">Works well:</span><span><q>When I move focus to items, I can see them all.</q></span></p>
    </li>
  </ul>
</div>
<p class="sclabel">WCAG:</p>
<blockquote class="sc">
  <p>When a <a href="https://www.w3.org/TR/WCAG22/#dfn-user-interface-components">user interface component</a> receives keyboard focus, the component is not entirely hidden due to author-created content.</p>
  <p class="note">Note: Where content in a configurable interface can be repositioned by the user, then only the initial positions of user-movable content is considered for testing and conformance of this Success Criterion.</p>
  <p class="note">Note: Content opened by the <em>user</em> may obscure the component receiving focus. If the user can reveal the focused component without advancing the keyboard focus, the component with focus is not considered hidden due to author-created content.</p>
</blockquote>
<p><a href="https://www.w3.org/WAI/WCAG22/Understanding/focus-not-obscured-minimum">Understanding Focus Not Obscured (Minimum)</a></p>

### [EOWG draft] 2.4.12 Focus Not Obscured (Enhanced) (AAA)

<div class="quotes">
    <p>In brief:</p>
    <ul>
      <li>
        <p><span class="whatwhy">What to do: </span>Ensure that when items have focus, they are fully visible.</p>
      </li>
      <li>
        <p><span class="whatwhy">Why do it: </span>
          Some people cannot use a mouse and rely on seeing what has keyboard focus.</p>
      </li>
</ul>
</div>
<p><em>(Persona, problem, and works well same as 2.4.12 above.)</em></p>
<p class="sclabel">WCAG:</p>
<blockquote class="sc">
  <p>When a <a href="https://www.w3.org/TR/WCAG22/#dfn-user-interface-components">user interface component</a> receives keyboard focus, no part of the component is hidden by author-created content.</p>
</blockquote>
<p><a href="https://www.w3.org/WAI/WCAG22/Understanding/focus-not-obscured-enhanced">Understanding Focus Not Obscured (Enhanced)</a></p>

### [current] 2.4.13 Focus Appearance (AAA)
<section class="brief">
  <p>In brief:</p>
  <dl>
    <dt>Objective</dt>
    <dd>Make it easier to see what has keyboard focus</dd>
    <dt>Author task</dt>
    <dd>The focus indicator color contrasts 3:1 with both the component’s unfocused state and its surroundings</dd>
    <dt>Key beneficiaries</dt>
    <dd>Sighted users reliant on keyboard interaction</dd>
  </dl>
</section>

### [EOWG draft] 2.4.13 Focus Appearance (AAA)
<div class="quotes">
    <p>In brief:</p>
    <ul>
      <li>
        <p><span class="whatwhy">What to do: </span>Ensure that the focus indicator contrasts 3:1 with the component’s unfocused state and with its surroundings.</p>
      </li>
      <li>
        <p><span class="whatwhy">Why it's important: </span>
          People with low contrast sensitivity cannot see small contrast differences.</p>
      </li>
</ul>
    <p class="persona">For example, a <a href="https://www.w3.org/WAI/people-use-web/user-stories/#reporter">reporter</a> with repetitive stress injury who doesn't use a mouse:<br />
      and <a href="https://www.w3.org/WAI/people-use-web/user-stories/#retiree">Retiree</a> with low contrast sensitivity:</p>
  <ul>
    <li>
      <p><span class="issue">Problem:</span><span><q>I can't tell where the keyboard focus is as I move around a web page or app.</q></span></p>
    </li>
    <li>
      <p><span class="issue">Works well:</span><span><q>I can see where the keyboard focus is as I move around a web page or app.</q></span></p>
    </li>
  </ul>
</div>
<p class="sclabel">WCAG:</p>
<blockquote class="sc">
<p>When the keyboard <a href="https://www.w3.org/TR/WCAG22/#dfn-focus-indicator">focus indicator</a> is visible, an area of the focus indicator meets all the following:</p>
<ul>
  <li>is at least as large as the area of a 2 <a href="https://www.w3.org/TR/WCAG22/#dfn-css-pixels">CSS pixel</a> thick <a href="https://www.w3.org/TR/WCAG22/#dfn-perimeter">perimeter</a> of the unfocused component or sub-component, and</li>
  <li>has a contrast ratio of at least 3:1 between the same pixels in the focused and unfocused states</li>
</ul>
<p>Exceptions:</p>
<ul>
  <li>The focus indicator is determined by the user agent and cannot be adjusted by the author, or</li>
  <li>The focus indicator and the indicator's background color are not modified by the author.</li>
</ul>
<p class="note">Note: What is perceived as the user interface component or sub-component (to determine enclosure or size) depends on its visual presentation. The visual presentation includes the component's visible content, border, and component-specific background. It does not include shadow and glow effects outside the component's content, background, or border.</p>
<p class="note">Note: Examples of sub-components that may receive a focus indicator are menu items in an opened drop-down menu, or focusable cells in a grid.</p>
<p class="note">Note: Contrast calculations can be based on colors defined within the technology (such as HTML, CSS and SVG). Pixels modified by user agent resolution enhancements and anti-aliasing can be ignored.</p>
</blockquote>
<p><a href="https://www.w3.org/WAI/WCAG22/Understanding/focus-appearance.html">Understanding Focus Appearance</a></p>

## Guideline 2.5 Input Modalities

Make it easier for users to operate functionality through various inputs beyond keyboard.

### [current] 2.5.7 Dragging Movements (AA)

<section class="brief">
      <p>In brief:</p>
      <dl>
         <dt>Objective</dt><dd>Don't rely on dragging for user actions</dd>
         <dt>Author task</dt><dd>Provide a simple pointer alternative to any action that involves dragging</dd>
         <dt>Key beneficiaries</dt><dd>Users with some physical disabilities</dd>
      </dl>
 </section>

### [EOWG draft] 2.5.7 Dragging Movements (AA)
<div class="quotes">
    <p>In brief:</p>
    <ul>
      <li>
        <p><span class="whatwhy">What to do: </span>
          For any action that involves dragging, provide a simple pointer alternative.</p>
      </li>
      <li>
        <p><span class="whatwhy">Why: </span>
          Some people cannot use a mouse to drag items.</p>
      </li>
</ul>
    <p class="persona">For example, a <a href="https://www.w3.org/WAI/people-use-web/user-stories/#retiree">retiree</a> with hand tremor:</p>
  <ul>
    <li>
      <p><span class="issue">Problem:</span><span><q>I cannot hold down the mouse button and drag it accurately enough to move the items in this list.</q></span></p>
    </li>
    <li>
      <p><span class="issue">Works well:</span><span><q>When I click on an item in the list, I get up and down arrows and I can click those to change the order.</q></span></p>
    </li>
  </ul>
</div>

<p class="sclabel">WCAG:</p>
<blockquote class="sc">
<p>All functionality that uses a <a href="https://www.w3.org/TR/WCAG22/#dfn-dragging-movements">dragging movement</a> for operation can be achieved by a <a href="https://www.w3.org/TR/WCAG22/#dfn-single-pointer">single pointer</a> without dragging, unless dragging is <a href="https://www.w3.org/TR/WCAG22/#dfn-essential">essential</a> or the functionality is determined by the user agent and not modified by the author.</p>
<p class="note">Note: This requirement applies to web content that interprets pointer actions (i.e. this does not apply to actions that are required to operate the user agent or assistive technology).</p>
</blockquote>
<p><a href="https://www.w3.org/WAI/WCAG22/Understanding/dragging-movements">Understanding Dragging Movements</a></p>

### [current] 2.5.8 Target Size (Minimum) (AA)

<section class="brief">
      <p>In brief:</p>
      <dl>
          <dt>Objective</dt><dd>Make controls easier to activate</dd>
          <dt>Author task</dt><dd>Ensure targets meet a minimum size or have sufficient spacing around them</dd>
          <dt>Key beneficiaries</dt><dd>Users with some physical disabilities</dd>
      </dl>
</section>

### [EOWG draft] 2.5.8 Target Size (Minimum) (AA)

<div class="quotes">
    <p>In brief:</p>
    <ul>
      <li>
        <p><span class="whatwhy">What to do: </span>
          Ensure targets meet a minimum size or have sufficient spacing around them.</p>
      </li>
      <li>
        <p><span class="whatwhy">Why: </span>
          Some people with physical impairments cannot click small buttons that are close together.</p>
      </li>
</ul>
    <p class="persona">For example, a <a href="https://www.w3.org/WAI/people-use-web/user-stories/#retiree">retiree</a> with hand tremor:</p>
  <ul>
    <li>
      <p><span class="issue">Problem:</span><span><q>The buttons are so close together, I hit "Cancel" when going for "Submit". Then I have to start all over again.</q></span></p>
    </li>
    <li>
      <p><span class="issue">Works well:</span><span><q>There is more space between the buttons so I don't hit the wrong button even when I'm riding on the bumpy bus.</q></span></p>
    </li>
  </ul>
</div>
<p class="sclabel">WCAG:</p>
<blockquote class="sc">
  <p>The size of the <a href="https://www.w3.org/TR/WCAG22/#dfn-targets">target</a> for <a href="https://www.w3.org/TR/WCAG22/#dfn-pointer-inputs">pointer inputs</a> is at least 24 by 24 CSS pixels, except where:</p>
  <ul>
    <li><strong>Spacing:</strong> Undersized targets (those less than 24 by 24 CSS pixels) are positioned so that if a 24 CSS pixel diameter circle is centered on the <a>bounding box</a> of each, the circles do not intersect another target or the circle for another undersized target;</li>
    <li><strong>Equivalent:</strong> The function can be achieved through a different control on the same page that meets this criterion;</li>
    <li><strong>Inline:</strong> The target is in a sentence or its size is otherwise constrained by the line-height of non-target text;</li>
    <li><strong>User agent control:</strong> The size of the target is determined by the user agent and is not modified by the author;</li>
    <li><strong>Essential:</strong> A particular presentation of the target is <a href="https://www.w3.org/TR/WCAG22/#dfn-essential">essential</a> or is legally required for the information being conveyed.</li>
  </ul>
  <p class="note">Note: Targets that allow for values to be selected spatially based on position within the target are considered one target for the purpose of the success criterion. Examples include sliders with granular values, color pickers displaying a gradient of colors, or editable areas where you position the cursor.</p>
  <p class="note">Note: For inline targets the line-height should be interpreted as perpendicular to the flow of text. For example, in a language displayed top to bottom, the line-height would be horizontal.</p>
</blockquote>
<p><a href="https://www.w3.org/WAI/WCAG22/Understanding/target-size-minimum.html">Understanding Target Size (Minimum)</a></p>

## Guideline 3.2 Predictable

Make Web pages appear and operate in predictable ways.

### [current] 3.2.6 Consistent Help (A)

<section class="brief">
      <p>In brief:</p>
      <dl>
          <dt>Objective</dt><dd>Consistently locate user help</dd>
          <dt>Author task</dt><dd>If you provide a help mechanism, provide it in a consistent location</dd>
          <dt>Key beneficiaries</dt><dd>Users with some cognitive disabilities</dd>
      </dl>
</section>

### [EOWG draft] 3.2.6 Consistent Help (A)

<div class="quotes">
    <p>In brief:</p>
    <ul>
      <li>
        <p><span class="whatwhy">What to do: </span>
          If you provide help, put  it in the same place on all web pages and app windows.</p>
      </li>
      <li>
        <p><span class="whatwhy">Why: </span>
          People who have difficulty finding help are more likely to find it when it is in the same place.</p>
      </li>
</ul>
    <p class="persona">For example, a <a href="https://www.w3.org/WAI/people-use-web/user-stories/#supermarketassistant">supermarket assistant</a> with cognitive disabilities:</p>
  <ul>
    <li>
      <p><span class="issue">Problem:</span><span><q>Whenever I use the online app to schedule my medical appointments, I can't remember what to do at each step. I've seen a Chat option in some places, but can't find it now.</q></span></p>
    </li>
    <li>
      <p><span class="issue">Works well:</span><span><q>When I need help, I can easily find the Chat option that's always in the lower right corner of the page.</q></span></p>
    </li>
  </ul>
</div>
<p class="sclabel">WCAG:</p>
<blockquote class="sc">
<p>If a <a href="https://www.w3.org/TR/WCAG22/#dfn-web-page-s">web page</a> contains any of the following help mechanisms, and those mechanisms are repeated on multiple web pages within a <a href="https://www.w3.org/TR/WCAG22/#dfn-set-of-web-pages">set of web pages</a>, they occur in the same relative order to other page content, unless a change is initiated by the user:</p>
<ul>
  <li>Human contact details;</li>
  <li>Human contact mechanism;</li>
  <li>Self-help option;</li>
  <li>A fully automated contact mechanism.</li>
</ul>
<p class="note">Note: Help mechanisms may be provided directly on the page, or may be provided via a direct link to a different page containing the information.</p>
<p class="note">Note: For this Success Criterion, the same relative order can be thought of as how the content is ordered when the page is serialized. The visual position of a help mechanism is likely to be consistent across pages for the same page variation (e.g., CSS break-point). The user can initiate a change, such as changing the page's zoom or orientation, which may trigger a different page variation. This criterion is concerned with relative order across pages displayed in the same page variation (e.g., same zoom level and orientation).</p>
</blockquote>
<p><a href="https://www.w3.org/WAI/WCAG22/Understanding/consistent-help">Understanding Consistent Help</a></p>

## Guideline 3.3 Input Assistance

Help users avoid and correct mistakes.

### [EOWG draft] 3.3.7 Redundant Entry (A)

_[@@ SLH didn't find In Brief for this one.]_

<div class="quotes">
    <p>In brief:</p>
    <ul>
      <li>
        <p><span class="whatwhy">What to do: </span>
          If you have data that needs to be entered again, auto-populate it or make it avaliable for the user to select.</p>
      </li>
      <li>
        <p><span class="whatwhy">Why: </span>
          Some people with cognitive disabilities have difficulty remembering what they entered before..</p>
      </li>
</ul>
    <p class="persona">For example, a <a href="https://www.w3.org/WAI/people-use-web/user-stories/#supermarketassistant">supermarket assistant</a> with cognitive disabilities:</p>
  <ul>
    <li>
      <p><span class="issue">Problem:</span><span><q>Whenever I use the online app to schedule my medical appointments, I have to re-type some information that I entered in a previous step.</q></span></p>
    </li>
    <li>
      <p><span class="issue">Works well:</span><span><q>The app automatically fills in information that I entered in previous steps.</q></span></p>
    </li>
  </ul>
</div>
<p class="sclabel">WCAG:</p>
<blockquote class="sc">
  <p>Information previously entered by or provided to the user that is required to be entered again in the same <a href="https://www.w3.org/TR/WCAG22/#dfn-processes" class="internalDFN" data-link-type="dfn">process</a> is either:</p>
  <ul>
    <li>auto-populated, or</li>
    <li>available for the user to select.</li>
  </ul>
  <p>Except when:</p>
  <ul>
    <li>re-entering the information is <a href="https://www.w3.org/TR/WCAG22/#dfn-essential" class="internalDFN" data-link-type="dfn">essential</a>,</li>
    <li>the information is required to ensure the security of the content, or</li>
    <li>previously entered information is no longer valid.</li>
  </ul>
</blockquote>
<p><a href="https://www.w3.org/WAI/WCAG22/Understanding/redundant-entry">Understanding Redundant Entry</a></p>

### [current] 3.3.8 Accessible Authentication (Minimum) (AA)

<section class="brief">
  <p>In brief:</p>
  <dl>
    <dt>Objective</dt>
    <dd>Make logins possible with less mental effort</dd>
    <dt>Author task</dt>
    <dd>Don’t make people memorize or transcribe something in order to log in</dd>
    <dt>Key beneficiaries</dt>
    <dd>Users with some cognitive disabilities</dd>
  </dl>
</section>

### [EOWG draft] 3.3.8 Accessible Authentication (Minimum) (AA)
<div class="quotes">
    <p>In brief:</p>
    <ul>
      <li>
        <p><span class="whatwhy">What to do: </span>
          Provide an accessible, easy-to-use, and secure method to log in. Don’t make people memorize or transcribe something in order to log in.</p>
      </li>
      <li>
        <p><span class="whatwhy">Why: </span>
          Some people with cognitive disabilities cannot memorize a username and password, or type them.</p>
      </li>
  </ul>
    <p class="persona">For example, a <a href="https://www.w3.org/WAI/people-use-web/user-stories/#supermarketassistant">supermarket assistant</a> with cognitive disabilities:</p>
  <ul>
    <li>
      <p><span class="issue">Problem:</span><span><q>I can never remember my password, it’s really hard to get into this app.</q></span></p>
    </li>
    <li>
      <p><span class="issue">Works well:</span><span><q>To get into this app, I can put my e-mail address. Then I get an e-mail message, and I can click a link in the e-mail to get into the app.</q></span></p>
    </li>
  </ul>
</div>
<p class="sclabel">WCAG:</p>
<blockquote class="sc">
<p>A <a href="https://www.w3.org/TR/WCAG22/#dfn-cognitive-function-test" class="internalDFN" data-link-type="dfn" id="ref-for-dfn-cognitive-function-test-1" title="A task that requires the user to remember, manipulate, or transcribe information. Examples include, but are not limited to:">cognitive function test</a> (such as remembering a password or solving a puzzle) is not required for any step in an authentication process unless that step provides at least one of the following:</p>
<dl>
  <dt>Alternative</dt>
  <dd>Another authentication method that does not rely on a cognitive function test.</dd>
  <dt>Mechanism</dt>
  <dd>A mechanism is available to assist the user in completing the cognitive function test.</dd>
  <dt>Object Recognition</dt>
  <dd>The cognitive function test is to recognize objects.</dd>
  <dt>Personal Content</dt>
  <dd>The cognitive function test is to identify non-text content the user provided to the website.</dd>
</dl>
  <p class="note">Note: "Object recognition" and "Personal content" may be represented by images, video, or audio.</p>
  <p class="note">Note: Examples of mechanisms that satisfy this criterion include:</p>
    <ol>
      <li>support for password entry by password managers to reduce memory need, and</li>
      <li>copy and paste to reduce the cognitive burden of re-typing.</li>
    </ol>
</blockquote>
<p><a href="https://www.w3.org/WAI/WCAG22/Understanding/accessible-authentication">Understanding Accessible Authentication (Minimum)</a></p>

### [current] 3.3.9 Accessible Authentication (Enhanced) (AAA)

<section class="brief">
        <p>In brief</p>
        <dl>
            <dt>Objective</dt><dd>Make logins possible with less mental effort</dd>
            <dt>Author task</dt><dd>Don’t make people recognize objects or user-supplied information in order to login</dd>
            <dt>Key beneficiaries</dt><dd>Users with some cognitive disabilities</dd>
        </dl>
 </section>

### [EOWG draft] 3.3.9 Accessible Authentication (Enhanced) (AAA)
<div class="quotes">
    <p>In brief:</p>
    <ul>
      <li>
        <p><span class="whatwhy">What to do: </span>
          Don’t make people recognize objects or information they previous provided in order to login.</p>
      </li>
      <li>
        <p><span class="whatwhy">Why: </span>
          Some people with cognitive disabilities cannot identify objects.@@</p>
      </li>
  </ul>
    <p class="persona">For example, a <a href="https://www.w3.org/WAI/people-use-web/user-stories/#supermarketassistant">supermarket assistant</a> with cognitive disabilities:</p>
  <ul>
    <li>
      <p><span class="issue">Problem:</span><span><q>To get into this app, it's asking me to click on pictues of cats, but I can't tell which are cats. @@needs review, along with previous one@@</q></span></p>
    </li>
    <li>
      <p><span class="issue">Works well:</span><span><q>To get into this app, I can copy and paste my password. @@needs review, along with previous one@@</q></span></p>
    </li>
  </ul>
</div>
<p class="sclabel">WCAG:</p>
<blockquote class="sc">
<p>A <a href="https://www.w3.org/TR/WCAG22/#dfn-cognitive-function-test" class="internalDFN" data-link-type="dfn" id="ref-for-dfn-cognitive-function-test-2" title="A task that requires the user to remember, manipulate, or transcribe information. Examples include, but are not limited to:">cognitive function test</a> (such as remembering a password or solving a puzzle) is not required for any step in an authentication process unless that step provides at least one of the following:</p>
<dl>
  <dt>Alternative</dt>
  <dd>Another authentication method that does not rely on a cognitive function test.</dd>
  <dt>Mechanism</dt>
  <dd>A mechanism is available to assist the user in completing the cognitive function test.</dd>
</dl>
</blockquote>
<p><a href="https://www.w3.org/WAI/WCAG22/Understanding/accessible-authentication-enhanced">Understanding Accessible Authentication (Enhanced)</a></p>

## About the Personas Quotes

Personas represent users@@. They are based on @@

The linked persona roles go to the [[Stories of Web Users]](/people-use-web/user-stories/). That page has other personas with different disabilities.
