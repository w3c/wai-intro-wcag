---
# Translation info https://www.w3.org/wiki/WAI/Website/Translate

title: "What's New in WCAG 2.2 Draft"
title_html: "What's New in WCAG 2.2 Draft"
nav_title: "New in 2.2 Draft"

description: This page lists the new success criteria in Web Content Accessibility Guidelines (WCAG) 2.2. It includes quotes from personas (fictional people) to help you understand some aspects of the success criteria.

teaser_text: WCAG 2.2 has @@ additional requirements (“success criteria”) that address the needs of people with cognitive or learning disabilities, mobile devices users, and ebook users. The What’s New in WCAG 2.2 page introduces the new success criteria. It includes quotes from personas to help you understand the issues.

lang: en
last_updated: 2022-08-@@
permalink: /standards-guidelines/wcag/new-in-22/

github:
  repository: w3c/wai-intro-wcag
  path: 'content/new-in-22.md'

feedbackmail: wai@w3.org
image: /content-images/wai-intro-wcag/general-social.png
footer: >
  <p><strong>Date:</strong> Updated @@ August 2022.</p>
  <p><strong>Editor:</strong> <a href="https://www.w3.org/People/Shawn/">Shawn Lawton Henry</a>. Contributors: <a href="https://www.w3.org/People/shadi/">Shadi Abou-Zahra</a>,  <a href="https://www.w3.org/groups/wg/eowg/participants">EOWG Participants</a>, and <a href="https://www.w3.org/groups/wg/ag/participants">AG WG Participants</a>.</p>
  <p>Developed with input from the Education and Outreach Working Group (<a href="https://www.w3.org/WAI/about/groups/eowg/">EOWG</a>) and the Accessibility Guidelines Working Group (<a href="https://www.w3.org/WAI/about/groups/eowg/">AG WG</a>).</p>
inline_css: |
  blockquote {font-style: normal !important;}
  blockquote p:first-of-type:before, blockquote p:last-of-type:after, blockquote dl:last-of-type:after {content: '' !important;margin-left: 0 !important;}
  blockquote.sc {padding: 0 10px 15px 20px;border: solid #ccc 1px;background: #f0f0f0;color: #000; margin-right: 0; margin-bottom:40px;}
  .quotes {margin-bottom:40px;}
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
  .sc p:last-of-type {margin-bottom: 1em}
  .sc p:last-child, .sc *:last-child {margin-bottom: 0}
  
  
  div.note-title , div.ednote-title, div.warning-title {
      padding-right:  1em;
      min-width: 7.5em;
      color: #b9ab2d;
  }
  div.note-title, div.ednote-title { color: #2b2; }
  div.warning-title { color: #f22; }
  div.note-title span, div.ednote-title span, div.warning-title span {
      text-transform: uppercase;
  }
  div.note, div.ednote, div.warning {
      margin-top: 1em;
      margin-bottom: 1em;
  }
  .note > p:first-child, .ednote > p:first-child,.warning > p:first-child { margin-top: 0 }
  .note, .ednote, .warning {
      padding: .5em;
      border-left-width: .5em;
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
      background: #e9fbe9;
  }
  .note-p {margin-top: 0}

ref: /standards-guidelines/wcag/new-in-22/

---

{::nomarkdown}
{% include box.html type="start" h="2" title="Summary" class="full" %}
{:/}

This page lists the proposed new success criteria in the **Draft** of Web Content Accessibility Guidelines (WCAG) 2.2.

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

_{{ @@ Editor update link reminder: some links go to https://w3c.github.io/wcag/guidelines/22/ and need to be updated to the /TR/ CR when it's ready }}_

## Introduction, Timeline, Comments

For an introduction to Web Content Accessibility Guidelines (WCAG) and more about versions 2.0, 2.1, and 2.2, see the [WCAG Overview](/standards-guidelines/wcag/).

WCAG 2.2 is scheduled to be completed and published by December 2022. Current drafts:
* [WCAG 2.2 Candidate Recommendation Draft](https://www.w3.org/TR/WCAG22/) was approved for publication in @@August 2022
* [Editors' Draft of WCAG 2.2](https://w3c.github.io/wcag/guidelines/22/) may include more recent proposed changes that are not yet all approved

"Candidate Recommendation" and the process for completing WCAG 2.2 is introduced in [How WAI Develops Accessibility Standards through the W3C Process](https://www.w3.org/WAI/standards-guidelines/w3c-process/).

Comments: **@@ Month 2022** is the deadline for comments on the Candidate Recommendation Draft. To comment: Ideally open one [new GitHub issue]( https://github.com/w3c/wcag/issues/new) per discrete comment. If you’re not comfortable with GitHub, you can send comments to public-agwg-comments@w3.org

### Changes from WCAG 2.1 to WCAG 2.2

All success criteria from 2.0 and 2.1 are included in 2.2. The 2.0 and 2.1 success criteria are exactly the same (verbatim, word-for-word) in 2.2. **One changed level: [2.4.7 Focus Visible](https://www.w3.org/TR/WCAG22/#focus-visible)** is changed from Level AA in WCAG 2.1 to Level A in WCAG 2.2.

The WCAG 2.2 Draft provides @@ additional success criteria from WCAG 2.1. They are included on this page.

### Changes to the 2.2 Draft

Changes from the May 2021 Working Draft to the @@ August 2022 Candidate Recommendation Draft include:
* Updated "[Focus Appearance (AA)](https://w3c.github.io/wcag/guidelines/22/#focus-appearance)" and removed “Focus Appearance (Enhanced) (AAA)”.
* Added [Focus Not Obscured (Minimum) (AA)](https://w3c.github.io/wcag/guidelines/22/#focus-not-obscured-minimum) and [Focus not obscured (Enhanced)(AAA)](https://w3c.github.io/wcag/guidelines/22/#focus-not-obscured-enhanced).
* Removed "Visible Controls" (because we did not get agreement on what the visual indicator would need to be). We plan to add this to [Supplemental Guidance](https://www.w3.org/WAI/WCAG2/supplemental/).
* Removed "Page Break Navigation" (because we did not get agreement on the level of granularity required for the page-break markers). We plan to add this to [Supplemental Guidance](https://www.w3.org/WAI/WCAG2/supplemental/).

More details are in the [changelog](https://w3c.github.io/wcag/guidelines/22/#changelog).

## Guideline 2.4 Navigable

Provide ways to help users navigate, find content, and determine where they are.

### 2.4.11 Focus Appearance (AA)
<blockquote class="sc">
  <p>Success Criterion <a href="https://www.w3.org/TR/WCAG22/#focus-appearance" style="font-weight: bold;">2.4.11 Focus Appearance</a> (Level AA): When a <a href="https://www.w3.org/TR/WCAG22/#dfn-user-interface-component">user interface component</a> has keyboard focus, one or both of the following is true:</p>
  <ol>
    <li>The <a href="https://www.w3.org/TR/WCAG22/#dfn-focus-indicator">focus indicator</a>:
      <ul>
        <li> <a href="https://www.w3.org/TR/WCAG22/#dfn-encloses">encloses</a> the visual presentation of the user interface component, and </li>
        <li>has a contrast ratio of at least 3:1 between the same pixels in the focused and unfocused states, and </li>
        <li>has a contrast ratio of at least 3:1 against adjacent colors.</li>
      </ul>
    </li>
    <li>An area of the focus indicator meets all the following:
      <ul>
        <li>is at least as large as the area of a 1 <a href="https://www.w3.org/TR/WCAG22/#dfn-css-pixel">CSS pixel</a> thick <a href="https://www.w3.org/TR/WCAG22/#dfn-perimeter">perimeter</a> of the unfocused component, or is at least as large as a 4 CSS pixel thick line along the shortest side of the <a href="https://www.w3.org/TR/WCAG22/#dfn-minimum-bounding-box">minimum bounding box</a> of the unfocused component, and </li>
        <li>has a contrast ratio of at least 3:1 between the same pixels in the focused and unfocused states, and </li>
        <li>has a contrast ratio of at least 3:1 against adjacent non-focus-indicator colors, or is no thinner than 2 CSS pixels.</li>
      </ul>
    </li>
  </ol>
  <p>Where a user interface component has active sub-components, if a sub-component receives a focus indicator, these requirements may be applied to the sub-component instead. </p>
  <p>Exceptions:</p>
  <ul>
    <li>The focus indicator is determined by the user agent and cannot be adjusted by the author, or</li>
    <li>The focus indicator and the indicator's background color are not modified by the author.</li>
  </ul>
  <p class="note">Note: Examples of sub-components that may receive a focus indicator are menu items in an opened drop-down menu. However, it may also be possible to indicate user interaction for such sub-components by relying strictly on a visual indication of which item is <em>selected</em>. Where selectable sub-components have no differentiated focus indicator, the visual indicator for sub-component selection is measured against <a href="https://www.w3.org/WAI/WCAG22/Understanding/non-text-contrast.html">1.4.11 Non-text Contrast</a> requirements, not against this Criterion.</p>
  <p class="note">Note: Contrast calculations can be based on colors defined within the technology (such as HTML, CSS and SVG). Pixels modified by user agent resolution enhancements and anti-aliasing can be ignored. </p>
</blockquote>
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
<p><a href="https://www.w3.org/WAI/WCAG22/Understanding/focus-appearance.html">Understanding Focus Appearance</a></p>

## Guideline 2.5 Input Modalities

Make it easier for users to operate functionality through various inputs beyond keyboard.

### 2.5.7 Dragging Movements (AA)
<blockquote class="sc">
  <p>All functionality that uses a <a href="https://www.w3.org/TR/WCAG22/#dfn-dragging-movements" class="internalDFN" data-link-type="dfn">dragging movement</a> for operation can be achieved by a single pointer without dragging, unless dragging is <a href="https://www.w3.org/TR/WCAG22/#dfn-essential" class="internalDFN" data-link-type="dfn">essential</a>.</p>
  <div class="note" role="note" id="issue-container-generatedID-29">
    <div role="heading" class="note-title marker" id="h-note-28"><span>Note</span></div>
    <p class="note-p">This requirement applies to web content that interprets pointer actions (i.e. this does not apply to actions that are required to operate the user agent or assistive technology).</p>
  </div>
  <div class="note" id="issue-container-generatedID-30">
    <div role="heading" class="ednote-title marker" id="h-ednote-0"><span>Editor's note</span></div>
    <p class="note-p">Is there an assistive technology that helps for people with mobility impairments? The group would like feedback on the frontier between AT &amp; author responsibility.</p>
  </div>
</blockquote>
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
<p><a href="https://www.w3.org/WAI/WCAG22/Understanding/dragging-movements">Understanding Dragging Movements</a></p>

### 2.5.8 Target Size (Minimum) (AA)
<blockquote class="sc">
  <p><a href="https://www.w3.org/TR/WCAG22/#dfn-target" class="internalDFN" data-link-type="dfn">Targets</a> have an area of at least 24 by 24 CSS pixels, except where:</p>
  <ul>
    <li><strong>Spacing:</strong> The <a href="https://www.w3.org/TR/WCAG22/#dfn-target-offsets" class="internalDFN" data-link-type="dfn">target offset</a> is at least 24 CSS pixels to every adjacent target;</li>
    <li><strong>Inline:</strong> The target is in a sentence or block of text;</li>
    <li><strong>Essential:</strong> A particular presentation of the target is essential to the information being conveyed.</li>
  </ul>
  <div class="note" role="note" id="issue-container-generatedID-31">
    <div role="heading" class="note-title marker" id="h-note-29"><span>Note</span></div>
    <p class="note-p">Targets that allow for values to be selected spatially based on position within the target are considered one target for the purpose of the success criterion. Examples include sliders with granular values, color pickers displaying a gradient of colors, or editable areas where you position the cursor.</p>
  </div>
  <div class="note" id="issue-container-generatedID-32">
    <div role="heading" class="ednote-title marker" id="h-ednote-1"><span>Editor's note</span></div>
    <p class="note-p">Are there issues with internationalization when describing inline links?</p>
  </div>
  <div class="note" id="issue-container-generatedID-33">
    <div role="heading" class="ednote-title marker" id="h-ednote-2"><span>Editor's note</span></div>
    <p class="note-p">Are there issues with pop-over content overlapping targets triggering failures?</p>
  </div>
</blockquote>
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
<p><a href="https://w3c.github.io/wcag/understanding/target-size-minimum.html">Understanding Target Size (Minimum)</a></p>

## Guideline 3.2 Predictable

Make Web pages appear and operate in predictable ways.

### 3.2.6 Consistent Help (A)
<blockquote class="sc">
  <p>For each <a href="https://www.w3.org/TR/WCAG22/#dfn-web-page-s" class="internalDFN" data-link-type="dfn">web page</a> within a <a href="https://www.w3.org/TR/WCAG22/#dfn-set-of-web-pages" class="internalDFN" data-link-type="dfn">set of web pages</a> that provides one or more of the following ways of finding help, access to at least one form of help is included in the same relative order on each page:</p>
  <ul>
    <li>Human contact details;</li>
    <li>Human contact mechanism;</li>
    <li>Self-help option;</li>
    <li>A fully automated contact mechanism.</li>
  </ul>
  <div class="note" role="note" id="issue-container-generatedID-34">
    <div role="heading" class="note-title marker" id="h-note-30"><span>Note</span></div>
    <p class="note-p">Access to help mechanisms may be provided directly on the page, or may be provided via a direct link to a different page containing the information.</p>
  </div>
</blockquote>
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
<p><a href="https://w3c.github.io/wcag/understanding/consistent-help.html">Understanding Consistent Help</a></p>

## Guideline 3.3 Input Assistance

Help users avoid and correct mistakes.

### 3.3.7 Accessible Authentication (A)
<blockquote class="sc">
  <p>For each step in an authentication process that relies on a <a href="https://www.w3.org/TR/WCAG22/#dfn-cognitive-function-test" class="internalDFN" data-link-type="dfn">cognitive function test</a>, at least one other authentication method is available that does not rely on a cognitive function test, or a mechanism is available to assist the user in completing the cognitive function test.</p>
  <div class="note" role="note" id="issue-container-generatedID-333">
    <div role="heading" class="note-title marker" id="h-note-333"><span>Note</span></div>
    <p class="note-p">Examples of mechanisms include: 1) support for password entry by password managers to address the memorization cognitive function test, and 2) copy and paste to help address transcription cognitive function test.</p>
  </div>
</blockquote>
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
<p><a href="https://www.w3.org/WAI/WCAG22/Understanding/accessible-authentication">Understanding Accessible Authentication</a></p>

### 3.3.8 Redundant Entry (A)
<blockquote class="sc">
  <p>Information previously entered by or provided to the user that is required to be entered again in the same <a href="https://www.w3.org/TR/WCAG22/#dfn-processes" class="internalDFN" data-link-type="dfn">process</a> and in the same user-session is either:</p>
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
  <div class="note" id="issue-container-generatedID-111">
    <div role="heading" class="ednote-title marker" id="h-ednote-111"><span>Editor's note</span></div>
    <p class="note-p">Are there issues storing the data so a user can access it in subsequent steps?</p>
  </div>
  <div class="note" id="issue-container-generatedID-222">
    <div role="heading" class="ednote-title marker" id="h-ednote-222"><span>Editor's note</span></div>
    <p class="note-p"> Are there broader exceptions needed than essential? E.g. for mandated or required information re-entry.</p>
  </div>
</blockquote>
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
<p><a href="https://www.w3.org/WAI/WCAG22/Understanding/redundant-entry">Understanding Redundant Entry</a></p>

## About the Personas Quotes

The linked persona roles go to the [[Stories of Web Users]](/people-use-web/user-stories/). That page has other personas with different disabilities. We might add more in the future.

We plan to add persona quotes to the Understanding WCAG documents.
