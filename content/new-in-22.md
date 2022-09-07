---
# Translation info https://www.w3.org/wiki/WAI/Website/Translate

title: "What's New in WCAG 2.2 Draft"
title_html: "What's New in WCAG 2.2 Draft"
nav_title: "New in 2.2 Draft"

description: This page lists the new success criteria in Web Content Accessibility Guidelines (WCAG) 2.2. It includes quotes from personas (fictional people) to help you understand some aspects of the success criteria.

teaser_text: WCAG 2.2 has 9 additional requirements (“success criteria”) that address the needs of people with cognitive or learning disabilities, mobile devices users, and ebook users. The What’s New in WCAG 2.2 page introduces the new success criteria. It includes quotes from personas to help you understand the issues.

lang: en
last_updated: 2022-09-06
permalink: /standards-guidelines/wcag/new-in-22/

github:
  repository: w3c/wai-intro-wcag
  path: 'content/new-in-22.md'

feedbackmail: wai@w3.org
image: /content-images/wai-intro-wcag/general-social.png
footer: >
  <p><strong>Date:</strong> Updated 6 September 2022 (about 18:00 UTC).</p>
  <p><strong>Editor:</strong> <a href="https://www.w3.org/People/Shawn/">Shawn Lawton Henry</a>. Contributors: <a href="https://www.w3.org/People/shadi/">Shadi Abou-Zahra</a>,  <a href="https://www.w3.org/groups/wg/eowg/participants">EOWG Participants</a>, and <a href="https://www.w3.org/groups/wg/ag/participants">AG WG Participants</a>.</p>
  <p>Developed with input from the Education and Outreach Working Group (<a href="https://www.w3.org/WAI/about/groups/eowg/">EOWG</a>) and the Accessibility Guidelines Working Group (<a href="https://www.w3.org/WAI/about/groups/eowg/">AG WG</a>).</p>
inline_css: |
  blockquote {font-style: normal !important;}
  blockquote p:first-of-type:before, blockquote p:last-of-type:after, blockquote dl:last-of-type:after {content: '' !important;margin-left: 0 !important;}
  blockquote.sc {padding: 0 10px 15px 20px;border: solid #ccc 1px;background: #f0f0f0;color: #000; margin: 0;}
  .quotes {margin-bottom: 0;}
  .quotes ul {list-style-type: none;}
  .quotes li>p {display:table-row;}
  .quotes li>p span {display:table-cell;}
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

This page lists the **proposed** new success criteria for Web Content Accessibility Guidelines (WCAG) 2.2.

**It includes quotes from personas (fictional people)** to help you understand some aspects of the success criteria. It also includes links to Understanding documents that explain the success criteria in detail and provide more examples.

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

For an introduction to Web Content Accessibility Guidelines (WCAG) and more about versions 2.0, 2.1, and 2.2, see the [WCAG Overview](/standards-guidelines/wcag/).

WCAG 2.2 is scheduled to be completed and published by December 2022. Current versions:
* [WCAG 2.2 W3C Candidate Recommendation Snapshot](https://www.w3.org/TR/WCAG22/) was approved for publication in September 2022
* [Editors' Draft of WCAG 2.2](https://w3c.github.io/wcag/guidelines/22/) may include more recent proposed changes that are not yet all approved

The main purpose of "Candidate Recommendation" is to ensure that the standard can be implemented. It is stable at this stage; however, it could change based on implementation experience. Specifically, 2.4.11 Focus Appearance is "<a href="https://www.w3.org/TR/WCAG22/#items-at-risk">at risk</a>" and might not be included in the final publication.

More about Candidate Recommendation and the process for completing WCAG 2.2 is introduced in [How WAI Develops Accessibility Standards through the W3C Process](https://www.w3.org/WAI/standards-guidelines/w3c-process/).

### Implementations and Comments

**4 October 2022** is the deadline for implementations and comments.

We welcome examples of the new WCAG 2.2 success criteria implemented in websites and web apps. You can share your implementations by logging into [your W3C account](https://www.w3.org/Help/Account/) and using the [WCAG Implementation Information Form](https://www.w3.org/WAI/GL/WCAG22/CR/select_site). Please also send e-mail to the Accessibility Guidelines Working Group Co-Chairs and W3C staff at: group-ag-chairs@w3.org

We hope that the normative content in WCAG 2.2 itself does not need changes. We will continue to update the Understanding documents based on feedback. To comment, please open a [new issue in the WCAG GitHub repository](https://github.com/w3c/wcag/issues/new). Create separate GitHub issues for each topic, rather than commenting on multiple topics in a single issue. If it’s not feasible for you to use GitHub, send comments in e-mail to: public-agwg-comments@w3.org

### Changes from WCAG 2.1 to WCAG 2.2

All success criteria from 2.0 and 2.1 are included in 2.2. The 2.0 and 2.1 success criteria are exactly the same (verbatim, word-for-word) in 2.2. **One changed level: [2.4.7 Focus Visible](https://www.w3.org/TR/WCAG22/#focus-visible)** is changed from Level AA in WCAG 2.1 to Level A in WCAG 2.2.

The WCAG 2.2 Draft provides 9 additional success criteria from WCAG 2.1. They are included on this page.

### Changes to the 2.2 Draft

Changes from the May 2021 Working Draft to the September 2022 Candidate Recommendation Draft include:
* Added "Focus Not Obscured (Minimum) (AA)" and "Focus Not Obscured (Enhanced) (AAA)".
* Updated "Focus Appearance (AA)" and removed “Focus Appearance (Enhanced) (AAA)”.
* After "Accessible Authentication (AA)", added "Accessible Authentication (No Exception) (AAA)"
* Removed "Visible Controls" (because we did not get agreement on what the visual indicator would need to be). We plan to add this to [Supplemental Guidance](https://www.w3.org/WAI/WCAG2/supplemental/).
* Removed "Page Break Navigation" (because we did not get agreement on the level of granularity required for the page-break markers). We plan to add this to [Supplemental Guidance](https://www.w3.org/WAI/WCAG2/supplemental/).

Previous changes are listed in the [changelog](https://www.w3.org/TR/WCAG22/#changelog).

## Guideline 2.4 Navigable

Provide ways to help users navigate, find content, and determine where they are.

### 2.4.11 Focus Appearance (AA)
<p class="persona"><a href="https://www.w3.org/WAI/people-use-web/user-stories/#reporter">Reporter</a> with repetitive stress injury who doesn't use a mouse:<br>
  and <a href="https://www.w3.org/WAI/people-use-web/user-stories/#retiree">Retiree</a> with low contrast sensitivity:</p>
<div class="quotes">
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
<p>When the keyboard <a href="https://www.w3.org/TR/WCAG22/#dfn-focus-indicator" class="internalDFN" data-link-type="dfn" id="ref-for-dfn-focus-indicator-1" title="pixels that are changed to visually indicate when a user interface component is in a focused state">focus indicator</a> is visible, one or both of the following are true:</p>
<ol>
  <li>The entire <a href="https://www.w3.org/TR/WCAG22/#dfn-focus-indicator" class="internalDFN" data-link-type="dfn" id="ref-for-dfn-focus-indicator-2" title="pixels that are changed to visually indicate when a user interface component is in a focused state">focus indicator</a> meets all the following:
    <ul>
      <li><a href="https://www.w3.org/TR/WCAG22/#dfn-enclose" class="internalDFN" data-link-type="dfn" id="ref-for-dfn-enclose-1" title="solidly bounds or surrounds">encloses</a> the <a href="https://www.w3.org/TR/WCAG22/#dfn-user-interface-components" class="internalDFN" data-link-type="dfn" id="ref-for-dfn-user-interface-components-7" title="a part of the content that is perceived by users as a single control for a distinct function">user interface component</a> or sub-component that is focused, and</li>
      <li>has a contrast ratio of at least 3:1 between the same pixels in the focused and unfocused states, and</li>
      <li>has a contrast ratio of at least 3:1 against adjacent non-focus-indicator colors.</li>
    </ul>
  </li>
  <li>An area of the focus indicator meets all the following:
    <ul>
      <li>is at least as large as the area of a 1 <a href="https://www.w3.org/TR/WCAG22/#dfn-css-pixels" class="internalDFN" data-link-type="dfn" id="ref-for-dfn-css-pixels-3" title="visual angle of about 0.0213 degrees">CSS pixel</a> thick <a href="https://www.w3.org/TR/WCAG22/#dfn-perimeter" class="internalDFN" data-link-type="dfn" id="ref-for-dfn-perimeter-1" title="continuous line forming the boundary of a shape not including shared pixels, or the minimum bounding box, whichever is shortest.">perimeter</a> of the unfocused component or sub-component, or is at least as large as a 4 CSS pixel thick line along the shortest side of the <a href="https://www.w3.org/TR/WCAG22/#dfn-minimum-bounding-box" class="internalDFN" data-link-type="dfn" id="ref-for-dfn-minimum-bounding-box-1" title="the smallest enclosing rectangle aligned to the horizontal axis within which all the points of a shape lie. For components which wrap onto multiple lines as part of a sentence or block of text (such as hypertext links), the bounding box is based on how the component would appear on a single line.">minimum bounding box</a> of the unfocused component or sub-component, and</li>
      <li>has a contrast ratio of at least 3:1 between the same pixels in the focused and unfocused states, and</li>
      <li>has a contrast ratio of at least 3:1 against adjacent non-focus-indicator colors, or is no thinner than 2 CSS pixels.</li>
    </ul>
  </li>
</ol>
<p>Exceptions:</p>
<ul>
  <li>The focus indicator is determined by the user agent and cannot be adjusted by the author, or</li>
  <li>The focus indicator and the indicator's background color are not modified by the author.</li>
</ul>
<p class="note">Note: What is perceived as the user interface component or sub-component (to determine enclosure or size) depends on its visual presentation. The visual presentation includes the component's visible content, border, and component-specific background. It does not include shadow and glow effects outside the component's content, background, or border.</p>
  <p class="note">Note: Examples of sub-components that may receive a focus indicator are menu items in an opened drop-down menu, or focusable cells in a grid.</p>
  <p class="note">Note: Contrast calculations can be based on colors defined within the technology (such as HTML, CSS and SVG). Pixels modified by user agent resolution enhancements and anti-aliasing can be ignored.</p>
<p class="note">Editor's note: This Success Criterion is <a href="https://www.w3.org/TR/WCAG22/#items-at-risk">at risk</a>.</p>
</blockquote>
<p><a href="https://www.w3.org/WAI/WCAG22/Understanding/focus-appearance.html">Understanding Focus Appearance</a></p>

### 2.4.12 Focus Not Obscured (Minimum) (AA)
<p class="persona"><a href="https://www.w3.org/WAI/people-use-web/user-stories/#reporter">Reporter</a> with repetitive stress injury who uses speech recognition software:</p>
<div class="quotes">
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
</blockquote>
<p><a href="https://www.w3.org/WAI/WCAG22/Understanding/focus-not-obscured-minimum">Understanding Focus Not Obscured (Minimum)</a></p>

### 2.4.13 Focus Not Obscured (Enhanced) (AAA)
<p class="persona"><a href="https://www.w3.org/WAI/people-use-web/user-stories/#reporter">Reporter</a> with repetitive stress injury who uses speech recognition software:</p>
<div class="quotes">
  <ul>
    <li>
      <p><span class="issue">Problem:</span><span><q>This page has a big banner that's always across the bottom. When I move focus to items, some are hidden behind the banner and I can't see them.</q></span></p>
    </li>
    <li>
      <p><span class="issue">Works well:</span><span><q>When I move focus to items, I can see them all.</q></span></p>
    </li>
  </ul>
</div>
<p class="sclabel">WCAG:</p>
<blockquote class="sc">
  <p>When a <a href="https://www.w3.org/TR/WCAG22/#dfn-user-interface-components">user interface component</a> receives keyboard focus, no part of the <a href="https://www.w3.org/TR/WCAG22/#dfn-focus-indicator">focus indicator</a> is hidden by author-created content.</p>
</blockquote>
<p><a href="https://www.w3.org/WAI/WCAG22/Understanding/focus-not-obscured-enhanced">Understanding Focus Not Obscured (Enhanced)</a></p>

## Guideline 2.5 Input Modalities

Make it easier for users to operate functionality through various inputs beyond keyboard.

### 2.5.7 Dragging Movements (AA)
<p class="persona"><a href="https://www.w3.org/WAI/people-use-web/user-stories/#retiree">Retiree</a> with hand tremor:</p>
<div class="quotes">
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

### 2.5.8 Target Size (Minimum) (AA)
<p class="persona"><a href="https://www.w3.org/WAI/people-use-web/user-stories/#retiree">Retiree</a> with hand tremor:</p>
<div class="quotes">
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
    <li><strong>Spacing:</strong> The <a href="https://www.w3.org/TR/WCAG22/#dfn-target-offsets">target offset</a> is at least 24 CSS pixels to every adjacent target;</li>
    <li><strong>Equivalent:</strong> The function can be achieved through a different control on the same page that has an area of at least 24 by 24 CSS pixels;</li>
    <li><strong>Inline:</strong> The target is in a sentence or block of text;</li>
    <li><strong>User agent control:</strong> The size of the target is determined by the user agent and is not modified by the author;</li>
    <li><strong>Essential:</strong> A particular presentation of the target is <a href="https://www.w3.org/TR/WCAG22/#dfn-essential">essential</a> or is legally required for the information being conveyed.</li>
  </ul>
  <p class="note">Note: Targets that allow for values to be selected spatially based on position within the target are considered one target for the purpose of the success criterion. Examples include sliders with granular values, color pickers displaying a gradient of colors, or editable areas where you position the cursor.</p>
</blockquote>
<p><a href="https://www.w3.org/WAI/WCAG22/Understanding/target-size-minimum.html">Understanding Target Size (Minimum)</a></p>

## Guideline 3.2 Predictable

Make Web pages appear and operate in predictable ways.

### 3.2.6 Consistent Help (A)
<p class="persona"><a href="https://www.w3.org/WAI/people-use-web/user-stories/#supermarketassistant">Supermarket assistant</a> with cognitive disabilities:</p>
<div class="quotes">
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
<p class="note">Note: Access to help mechanisms may be provided directly on the page, or may be provided via a direct link to a different page containing the information.</p>
<p class="note">Note: For this Success Criterion, the same relative order can be thought of as how the content is ordered when the page is serialized. The visual position of a help mechanism is likely to be consistent across pages for the same page variation (e.g., CSS break-point). The user can initiate a change, such as changing the page's zoom or orientation, which may trigger a different page variation. This criterion is concerned with relative order across pages displayed in the same page variation (e.g., same zoom level and orientation).</p>
</blockquote>
<p><a href="https://www.w3.org/WAI/WCAG22/Understanding/consistent-help">Understanding Consistent Help</a></p>

## Guideline 3.3 Input Assistance

Help users avoid and correct mistakes.

### 3.3.7 Accessible Authentication (AA)
<p class="persona"><a href="https://www.w3.org/WAI/people-use-web/user-stories/#supermarketassistant">Supermarket assistant</a> with cognitive disabilities:</p>
<div class="quotes">
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
  <p class="note">Note: Objects to recognize and user provided content may be represented by images, video, or audio.</p>
  <p class="note">Note: Examples of mechanisms that satisfy this criterion include:</p>
    <ol>
      <li>support for password entry by password managers to reduce memory need, and</li>
      <li>copy and paste to reduce the cognitive burden of re-typing.</li>
    </ol>
</blockquote>
<p><a href="https://www.w3.org/WAI/WCAG22/Understanding/accessible-authentication">Understanding Accessible Authentication</a></p>

### 3.3.8 Accessible Authentication (No Exception) (AAA)
<p class="persona"><a href="https://www.w3.org/WAI/people-use-web/user-stories/#supermarketassistant">Supermarket assistant</a> with cognitive disabilities:</p>
<div class="quotes">
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
<p>A <a href="https://www.w3.org/TR/WCAG22/#dfn-cognitive-function-test" class="internalDFN" data-link-type="dfn" id="ref-for-dfn-cognitive-function-test-2" title="A task that requires the user to remember, manipulate, or transcribe information. Examples include, but are not limited to:">cognitive function test</a> (such as remembering a password or solving a puzzle) is not required for any step in an authentication process unless that step provides at least one of the following:</p>
<dl>
  <dt>Alternative</dt>
  <dd>Another authentication method that does not rely on a cognitive function test.</dd>
  <dt>Mechanism</dt>
  <dd>A mechanism is available to assist the user in completing the cognitive function test.</dd>
</dl>
</blockquote>
<p><a href="https://www.w3.org/WAI/WCAG22/Understanding/accessible-authentication-no-exception">Understanding Accessible Authentication (No Exception)</a></p>

### 3.3.9 Redundant Entry (A)
<p class="persona"><a href="https://www.w3.org/WAI/people-use-web/user-stories/#supermarketassistant">Supermarket assistant</a> with cognitive disabilities:</p>
<div class="quotes">
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

## About the Personas Quotes

The linked persona roles go to the [[Stories of Web Users]](/people-use-web/user-stories/). That page has other personas with different disabilities. We might add more in the future.

We plan to add persona quotes to the Understanding WCAG documents.
