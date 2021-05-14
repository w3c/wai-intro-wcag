---
# Translation info https://www.w3.org/wiki/WAI/Website/Translate

title: "What's New in WCAG 2.2 Working Draft"
title_html: "What's New in WCAG 2.2 Working Draft"
nav_title: "New in 2.2 Draft"

description: This page lists the new success criteria in Web Content Accessibility Guidelines (WCAG) 2.2. It includes quotes from personas (fictional people) to help you understand some aspects of the success criteria.

teaser_text: WCAG 2.2 has 9 additional requirements (“success criteria”) that address the needs of people with cognitive or learning disabilities, mobile devices users, and ebook users. The What’s New in WCAG 2.2 page introduces the new success criteria. It includes quotes from personas to help you understand the issues.

lang: en
last_updated: 2021-05-13
permalink: /standards-guidelines/wcag/new-in-22/

github:
  repository: w3c/wai-intro-wcag
  path: 'content/new-in-22.md'

feedbackmail: wai@w3.org
image: /content-images/wai-intro-wcag/general-social.png
footer: >
  <p><strong>Date:</strong> Updated 13 May 2021.</p>
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

This page lists the proposed new success criteria in the **Working Draft** of Web Content Accessibility Guidelines (WCAG) 2.2.

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

## Introduction

For an introduction to Web Content Accessibility Guidelines (WCAG) and more about versions 2.0, 2.1, and 2.2, see the [WCAG Overview](/standards-guidelines/wcag/).

WCAG 2.2 is scheduled to be completed and published in 2021. Current drafts:
* [WCAG 2.2 Working Draft](https://www.w3.org/TR/WCAG22/) is approved to be posted as a draft
* [Editors' Draft of WCAG 2.2](https://w3c.github.io/wcag/guidelines/22/) may have more recent updates that are not yet approved

<em>If you have comments on the WCAG 2.2 Draft:</em> Please submit any comments on the proposed new success criteria **by 11 June 2021**. Ideally open one [new GitHub issue]( https://github.com/w3c/wcag/issues/new) per discrete comment. If you’re not comfortable with GitHub, you can send comments to public-agwg-comments@w3.org

### Changes from WCAG 2.1 to WCAG 2.2

All success criteria from 2.0 and 2.1 are included in 2.2. The 2.0 and 2.1 success criteria are exactly the same (verbatim, word-for-word) in 2.2. **One changed level: [2.4.7 Focus Visible](https://www.w3.org/TR/WCAG22/#focus-visible)** is changed from Level AA in WCAG 2.1 to Level A in WCAG 2.2.

WCAG 2.2 Working Draft provides 9 additional success criteria, that are included on this page.

### Changes to 2.2 Working Draft

Changes from the 11 August 2020 to 11 May 2021 Working Draft include:
* Accessible authentication: Incorporates concepts of ‘steps’ to account for multi-factor authentication, and explicitly allows for ‘mechanisms’ like password managers.
* Dragging movement: A very minor wording update.
* Consistent help: Renamed from “Findable help”, and follows the ‘consistent navigation’ criterion more closely.
* Page Break Navigation: Renamed, the criterion text is reduced to focus on content which already implements programmatic page break locators.
* Focus appearance (minimum): Restructured the criterion text, whilst keeping the requirement essentially the same.
* Focus appearance (enhanced): Aligned with the minimum version.
* Visible control: Renamed (from Hidden controls), added several exceptions.
* Target size (minimum): Renamed (from Pointer target Spacing), reduced the core size requirement to 24px, and simplified the criterion text.
* Redundant entry: Removed the ‘steps in a process’ aspect, added a within-session scope, and added several exceptions.

## Guideline 2.4 Navigable

Provide ways to help users navigate, find content, and determine where they are.

### 2.4.11 Focus Appearance (Minimum) (AA)
<blockquote class="sc">
  <p>When <a href="https://www.w3.org/TR/WCAG22/#dfn-user-interface-components" class="internalDFN" data-link-type="dfn">user interface components</a> receive keyboard focus, all of the following are true:</p>
  <ul>
    <li><strong>Contrasting area:</strong> There is an area of the <a href="https://www.w3.org/TR/WCAG22/#dfn-focus-indicator" class="internalDFN" data-link-type="dfn">focus indicator</a> that has a contrast ratio of at least 3:1 between the colors in the focused and unfocused states.</li>
    <li><strong>Minimum area:</strong> The contrasting area is at least as large as:
      <ul>
        <li><strong>Outline:</strong> the area of a 1 <a href="https://www.w3.org/TR/WCAG22/#dfn-css-pixels" class="internalDFN" data-link-type="dfn">CSS pixel</a> thick <a href="https://www.w3.org/TR/WCAG22/#dfn-perimeter" class="internalDFN" data-link-type="dfn">perimeter</a> of the unfocused component, or</li>
        <li><strong>Shape:</strong> the area of a 4 CSS pixel thick line along the shortest side of a <a href="https://www.w3.org/TR/WCAG22/#dfn-minimum-bounding-box" class="internalDFN" data-link-type="dfn">minimum bounding box</a> of the unfocused component, and no thinner than 2 CSS pixels.</li>
      </ul>
    </li>
    <li><strong>Adjacent contrast:</strong> The contrasting area also has a contrast ratio of least 3:1 against adjacent colors in the focused component, or the contrasting area has a thickness of at least 2 CSS pixels.</li>
    <li><strong>Not fully obscured:</strong> The item with focus is not entirely hidden by author-created content.</li>
  </ul>
  <div class="note" role="note" id="issue-container-generatedID-22">
    <div role="heading" class="note-title marker" id="h-note-22"><span>Note</span></div>
    <p class="note-p">A keyboard focus indicator which has a pattern or gradient may have parts that do not meet the 3:1 contrast ratio for the change of contrast, as long as an area equal to the minimum does meet the contrast ratio.</p>
  </div>
  <div class="note" role="note" id="issue-container-generatedID-23">
    <div role="heading" class="note-title marker" id="h-note-23"><span>Note</span></div>
    <p class="note-p">If the component has a visible boundary smaller than the hit area, or the size of the component is not available, the minimum area can be taken from the visible boundary.</p>
  </div>
  <div class="note" id="issue-container-generatedID-24">
    <div role="heading" class="ednote-title marker" id="h-ednote"><span>Editor's note</span></div>
    <p class="note-p">The working group is interested in feedback about the minimum area metric, and if there are unusual scenarios where visible indicators are caught by the wording.</p>
  </div>
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
<p><a href="https://www.w3.org/WAI/WCAG22/Understanding/focus-appearance-minimum.html">Understanding Focus Appearance (Minimum)</a></p>

### 2.4.12 Focus Appearance (Enhanced) (AAA)
<blockquote class="sc">
  <p>When <a href="https://www.w3.org/TR/WCAG22/#dfn-user-interface-components" class="internalDFN" data-link-type="dfn">user interface components</a> have keyboard focus, all of the following are true:</p>
  <ul>
    <li><strong>Contrasting area:</strong> There is an area of the <a href="https://www.w3.org/TR/WCAG22/#dfn-focus-indicator" class="internalDFN" data-link-type="dfn">focus indicator</a> that has a contrast ratio of at least 4.5:1 between the colors in the focused and unfocused states.</li>
    <li><strong>Minimum area:</strong> The contrasting area is at least double the area of a 1 <a href="https://www.w3.org/TR/WCAG22/#dfn-css-pixels" class="internalDFN" data-link-type="dfn">CSS pixel</a> <a href="https://www.w3.org/TR/WCAG22/#dfn-perimeter" class="internalDFN" data-link-type="dfn">perimeter</a> of the unfocused component;</li>
    <li><strong>Not obscured:</strong> No part of the focus indicator is hidden by author-created content.</li>
  </ul>
</blockquote>
<p class="persona"><a href="https://www.w3.org/WAI/people-use-web/user-stories/#reporter">Reporter</a> with repetitive stress injury who doesn't use a mouse:<br>
  and <a href="https://www.w3.org/WAI/people-use-web/user-stories/#retiree">Retiree</a> with low contrast sensitivity:</p>
<div class="quotes">
  <ul>
    <li>
      <p><span class="issue">Problem:</span><span><q>I can't tell where the keyboard focus is as I move around a web page or app.</q></span></p>
    </li>
    <li>
      <p><span class="issue">Works well:</span><span><q>I can easily see where the keyboard focus is as I move around a web page or app.</q></span></p>
    </li>
  </ul>
</div>
<p><a href="https://www.w3.org/WAI/WCAG22/Understanding/focus-appearance-enhanced">Understanding Focus Appearance (Enhanced)</a></p>

### 2.4.13 Page Break Navigation (A)
<blockquote class="sc">
  <p>For web content with <a href="https://www.w3.org/TR/WCAG22/#dfn-pagebreak-locators" class="internalDFN" data-link-type="dfn">page break locators</a>, a mechanism is available to navigate to each locator.</p>
</blockquote>
<p class="persona"><a href="https://www.w3.org/WAI/people-use-web/user-stories/#classroomstudent">Student</a> with dyslexia:<br>
  and <a href="https://www.w3.org/WAI/people-use-web/user-stories/#retiree">Retiree</a> with low vision:</p>
<div class="quotes">
  <ul>
    <li>
      <p><span class="issue">Problem:</span><span><q>I increase the text size and spacing in the online textbook. The instructor said: "The activity is on page 37." But it's not on page 37 in my view, and I cannot find it.</q></span></p>
    </li>
    <li>
      <p><span class="issue">Works well:</span><span><q>I used the page contents list to get to "page 37". (It's actually page 53 in my view — that's OK, I found it.)</q></span></p>
    </li>
  </ul>
</div>
<p><a href="https://w3c.github.io/wcag/understanding/page-break-navigation.html">Page Break Navigation</a></p>

## Guideline 2.5 Input Modalities

Make it easier for users to operate functionality through various inputs beyond keyboard.

### 2.5.7 Dragging (AA)
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
<p><a href="https://www.w3.org/WAI/WCAG22/Understanding/dragging">Understanding Dragging</a></p>

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

### 3.2.7 Visible Controls (AA)
<blockquote class="sc">
  <p>Where receiving pointer hover or keyboard focus triggers <a href="https://www.w3.org/TR/WCAG22/#dfn-user-interface-components" class="internalDFN" data-link-type="dfn">user interface components</a> to be visible, information needed to identify that user interface components are available is visible, except when:</p>
  <ul>
    <li>The information needed to identify the user interface components is available through an equivalent component that is visible on the same page or on a different step in a multi-step process without requiring pointer hover or keyboard focus;</li>
    <li>The component is provided specifically to enhance the experience for keyboard navigation;</li>
    <li>A mechanism is available to make the information persistently visible;</li>
    <li>Hiding the information needed to identify the component is essential.</li>
  </ul>
  <div class="note" role="note" id="issue-container-generatedID-35">
    <div role="heading" class="note-title marker" id="h-note-31"><span>Note</span></div>
    <p class="note-p">User interface components can be available through other visible components such as sub-menus, edit buttons, tabs, or thumbnails of media.</p>
  </div>
  <div class="note" id="issue-container-generatedID-36">
    <div role="heading" class="ednote-title marker" id="h-ednote-3"><span>Editor's note</span></div>
    <p class="note-p">The working group is interested in feedback about whether there are Components determined by the user agent that should not be in scope.</p>
  </div>
</blockquote>
<p class="persona"><a href="https://www.w3.org/WAI/people-use-web/user-stories/#supermarketassistant">Supermarket assistant</a> with cognitive disabilities:</p>
<div class="quotes">
  <ul>
    <li>
      <p><span class="issue">Problem:</span><span><q>I can't tell what options are available. Some buttons appeared when I was mousing around, but now I can't find them.</q></span></p>
    </li>
    <li>
      <p><span class="issue">Works well:</span><span><q>The available buttons are all visible, without me having to mouse around.</q></span></p>
    </li>
  </ul>
</div>
<p><a href="https://w3c.github.io/wcag/understanding/visible-controls.html">Understanding Visible Controls</a></p>

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
      <p><span class="issue">Problem:</span><span><q>I don't understand what they want me to type in or click on to get into this app.</q></span></p>
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
