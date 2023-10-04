---
title: "What's New in WCAG 2.2"
title_html: "What's New in WCAG 2.2"
nav_title: "New in 2.2"

description: This page lists the new success criteria in Web Content Accessibility Guidelines (WCAG) 2.2. It includes quotes from personas to help you understand some aspects of the success criteria.

teaser_text: WCAG 2.2 has 9 additional requirements ("success criteria") that address the needs of people with cognitive or learning disabilities, mobile devices users, and ebook users. The What’s New in WCAG 2.2 page introduces the new success criteria. It includes quotes from personas to help you understand the issues.

lang: en
last_updated: 0000-00-00 # update if do translations
permalink: /standards-guidelines/wcag/new-in-22/

github:
  repository: w3c/wai-intro-wcag
  path: 'content/new-in-22.md'

feedbackmail: wai@w3.org
image: /content-images/wai-intro-wcag/general-social.png
footer: >
  <p><strong>Date:</strong> Updated 27 September 2023.</p>
  <p><strong>Editor:</strong> <a href="https://www.w3.org/People/Shawn/">Shawn Lawton Henry</a>. Contributors: Mike Gower, Shadi Abou-Zahra,  <a href="https://www.w3.org/groups/wg/eowg/participants">EOWG Participants</a>, and <a href="https://www.w3.org/groups/wg/ag/participants">AG WG Participants</a>.</p>
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
  .what {font-weight: bold; display:table-cell; width: 6em;}
  .why {font-weight: bold; display:table-cell; width: 10em;}
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
  .sc dl dd {margin: 0 0 0.5em 2em;}
  .sc dd {margin-left: 0;}
  .sc dd {display: block;  margin-inline-start: 40px;}
  .sc p:last-of-type {margin-bottom: 1em}
  .sc p:last-child, .sc *:last-child {margin-bottom: 0}
  .sclabel, .brief, .persona {
    padding: 0;
    margin: 0;
  }
  .sclabel {color: #005a6a; font-weight: bold; }
  #markdown-toc ul li {
    margin-bottom: 0;
  }

ref: /standards-guidelines/wcag/new-in-22/

---

{::nomarkdown}
{% include box.html type="start" h="2" title="Summary" class="full" %}
{:/}

We plan to publish WCAG 2.2 as a completed web standard in 2023.<br>The latest update is [WCAG 2.2 W3C Proposed Recommendation](https://www.w3.org/TR/WCAG22/).

This page lists the new success criteria in WCAG 2.2, with:
* A brief introduction of what to do and why it's important
* Quotes from [personas](#about-the-personas) to help you understand some aspects of the success criteria
* Links to Understanding documents that explain the success criteria in detail and provide more examples

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

## Status, Timeline, Changes

Background: For an introduction to Web Content Accessibility Guidelines (WCAG) and more about versions 2.0 and 2.1, see the [WCAG Overview](/standards-guidelines/wcag/).

**[WCAG 2.2 W3C Proposed Recommendation](https://www.w3.org/TR/WCAG22/)** is the latest update published on 20 July 2023. More about the process for completing WCAG 2.2 is in [How WAI Develops Accessibility Standards through the W3C Process](https://www.w3.org/WAI/standards-guidelines/w3c-process/).

**We expect to publish WCAG 2.2 as a "W3C Recommendation" web standard in 2023.** We are addressing new comments that we received in August 2023. We hope to publish in early October 2023. However, publication may be delayed by the time we need to resolve these comments. We will update information here as soon as we reach consensus and have a more specific expected final publication date.

We are not planning to change the new WCAG 2.2 success criteria. The changes **might** be informative notes:
* Added to WCAG 2.0 and 2.1 that success criteria 4.1.1 is obsolete with today's technology
* To clarify that success criteria 1.4.12 (AA) does not require content to use those text settings, only to work when users set those settings; and does not apply to certain language scripts
* To clarify applicability of success criteria 1.4.8 (AAA)

### Changes from WCAG 2.1 to WCAG 2.2

The 2.0 and 2.1 success criteria are exactly the same (verbatim, word-for-word) in 2.2, with **one exception**: 4.1.1 Parsing is obsolete and removed from WCAG 2.2. More information is in the [WCAG 2 FAQ, 4.1.1 Parsing](https://www.w3.org/WAI/standards-guidelines/wcag/faq/#parsing411).

WCAG 2.2 provides 9 additional success criteria from WCAG 2.1. They are included on this page.

### Changes to 2.2 from May to July

There are no substantive changes from the May 2023 to the July 2023 publication. There are only minor editorial changes to add links and correct punctuation.

Previous changes are listed in the [changelog](https://www.w3.org/TR/WCAG22/#change-log).

## Guideline 2.4 Navigable

Provide ways to help users navigate, find content, and determine where they are.

### 2.4.11 Focus Not Obscured (Minimum) (AA)

<div class="quotes">
<p class="brief">In brief:</p>
<dl>
  <dt><span class="what">What to do</span></dt>
  <dd>Ensure when an item gets keyboard focus, it is at least partially visible.</dd>
  <dt><span class="why">Why it’s important</span></dt>
  <dd>People who can't use a mouse need to see what has keyboard focus.</dd>

</dl>

<p class="persona">Persona example &mdash; a <a href="https://www.w3.org/WAI/people-use-web/user-stories/#reporter">reporter</a> with repetitive stress injury who uses speech recognition software:</p>
<dl>
  <dt><span class="issue">Problem</span></dt>
  <dd><span><q>This page has a big banner that's always across the bottom. <em>(a sticky footer)</em> When I move focus to items, some are hidden behind the banner and I can't see them.</q></span></dd>
  <dt><span class="issue">Works well</span></dt>
  <dd><span><q>When I move focus to items, I can see them all.</q></span></dd>
</dl>
</div>

<p class="sclabel">WCAG success criteria:</p>
<blockquote class="sc">
  <p>When a <a href="https://www.w3.org/TR/WCAG22/#dfn-user-interface-components">user interface component</a> receives keyboard focus, the component is not entirely hidden due to author-created content.</p>
  <p class="note"><em>Note:</em> Where content in a configurable interface can be repositioned by the user, then only the initial positions of user-movable content is considered for testing and conformance of this Success Criterion.</p>
  <p class="note"><em>Note:</em> Content opened by the <em>user</em> may obscure the component receiving focus. If the user can reveal the focused component without advancing the keyboard focus, the component with focus is not considered hidden due to author-created content.</p>
</blockquote>
<p><a href="https://www.w3.org/WAI/WCAG22/Understanding/focus-not-obscured-minimum">Understanding Focus Not Obscured (Minimum)</a></p>

### 2.4.12 Focus Not Obscured (Enhanced) (AAA)

<div class="quotes">
<p class="brief">In brief:</p>
<dl>
  <dt><span class="what">What to do</span></dt>
  <dd>Ensure when an item gets keyboard focus, it is fully visible.</dd>
  <dt><span class="why">Why it’s important</span></dt>
  <dd>People who can't use a mouse need to see what has keyboard focus.</dd>
</dl>

<p><em>(Persona, problem, and works well same as 2.4.12 above.)</em></p>
</div>

<p class="sclabel">WCAG success criteria:</p>
<blockquote class="sc">
  <p>When a <a href="https://www.w3.org/TR/WCAG22/#dfn-user-interface-components">user interface component</a> receives keyboard focus, no part of the component is hidden by author-created content.</p>
</blockquote>
<p><a href="https://www.w3.org/WAI/WCAG22/Understanding/focus-not-obscured-enhanced">Understanding Focus Not Obscured (Enhanced)</a></p>

### 2.4.13 Focus Appearance (AAA)

<div class="quotes">
<p class="brief">In brief:</p>
<dl>
  <dt><span class="what">What to do</span></dt>
  <dd>Use a focus indicator of sufficient size and contrast.</dd>
  <dt><span class="why">Why it’s important</span></dt>
  <dd>Many people can't see small changes in visual appearance, including older people.</dd>
</dl>

<p class="persona">Persona example &mdash; a <a href="https://www.w3.org/WAI/people-use-web/user-stories/#reporter">reporter</a> with repetitive stress injury who doesn't use a mouse:<br />
      and <a href="https://www.w3.org/WAI/people-use-web/user-stories/#retiree">Retiree</a> with low contrast sensitivity:</p>
<dl>
  <dt><span class="issue">Problem</span></dt>
  <dd><span><q>I can't tell where the keyboard focus is as I move around a web page or app.</q></span></dd>
  <dt><span class="issue">Works well</span></dt>
  <dd><span><q>I can see where the keyboard focus is as I move around a web page or app.</q></span></dd>
</dl>
</div>

<p class="sclabel">WCAG success criteria:</p>
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
<p class="note"><em>Note:</em> What is perceived as the user interface component or sub-component (to determine enclosure or size) depends on its visual presentation. The visual presentation includes the component's visible content, border, and component-specific background. It does not include shadow and glow effects outside the component's content, background, or border.</p>
<p class="note"><em>Note:</em> Examples of sub-components that may receive a focus indicator are menu items in an opened drop-down menu, or focusable cells in a grid.</p>
<p class="note"><em>Note:</em> Contrast calculations can be based on colors defined within the technology (such as HTML, CSS and SVG). Pixels modified by user agent resolution enhancements and anti-aliasing can be ignored.</p>
</blockquote>
<p><a href="https://www.w3.org/WAI/WCAG22/Understanding/focus-appearance.html">Understanding Focus Appearance</a></p>

## Guideline 2.5 Input Modalities

Make it easier for users to operate functionality through various inputs beyond keyboard.

### 2.5.7 Dragging Movements (AA)

<div class="quotes">
<p class="brief">In brief:</p>
<dl>
  <dt><span class="what">What to do</span></dt>
  <dd>For any action that involves dragging, provide a simple pointer alternative.</dd>
  <dt><span class="why">Why it’s important</span></dt>
  <dd>Some people cannot use a mouse to drag items.</dd>
</dl>

<p class="persona">Persona example &mdash; a <a href="https://www.w3.org/WAI/people-use-web/user-stories/#retiree">retiree</a> with hand tremor:</p>
<dl>
  <dt><span class="issue">Problem</span></dt>
  <dd><span><q>I cannot hold down the mouse button and drag it accurately enough to move the items in this list.</q></span></dd>
  <dt><span class="issue">Works well</span></dt>
  <dd><span><q>When I click on an item in the list, I get up and down arrows and I can click those to change the order.</q></span></dd>
</dl>
</div>

<p class="sclabel">WCAG success criteria:</p>
<blockquote class="sc">
<p>All functionality that uses a <a href="https://www.w3.org/TR/WCAG22/#dfn-dragging-movements">dragging movement</a> for operation can be achieved by a <a href="https://www.w3.org/TR/WCAG22/#dfn-single-pointer">single pointer</a> without dragging, unless dragging is <a href="https://www.w3.org/TR/WCAG22/#dfn-essential">essential</a> or the functionality is determined by the user agent and not modified by the author.</p>
<p class="note"><em>Note:</em> This requirement applies to web content that interprets pointer actions (i.e. this does not apply to actions that are required to operate the user agent or assistive technology).</p>
</blockquote>
<p><a href="https://www.w3.org/WAI/WCAG22/Understanding/dragging-movements">Understanding Dragging Movements</a></p>

### 2.5.8 Target Size (Minimum) (AA)

<div class="quotes">
<p class="brief">In brief:</p>
<dl>
  <dt><span class="what">What to do</span></dt>
  <dd>Ensure targets meet a minimum size or have sufficient spacing around them.</dd>
  <dt><span class="why">Why it’s important</span></dt>
  <dd>Some people with physical impairments cannot click small buttons that are close together.</dd>
</dl>

<p class="persona">Persona example &mdash; a <a href="https://www.w3.org/WAI/people-use-web/user-stories/#retiree">retiree</a> with hand tremor:</p>
<dl>
  <dt><span class="issue">Problem</span></dt>
  <dd><span><q>The buttons are so close, I hit "Cancel" when going for "Submit". Then I have to start all over again.</q></span></dd>
  <dt><span class="issue">Works well</span></dt>
  <dd><span><q>There is more space between the buttons so I don't hit the wrong button even when I'm riding on the bumpy bus.</q></span></dd>
</dl>
</div>

<p class="sclabel">WCAG success criteria:</p>
<blockquote class="sc">
  <p>The size of the <a href="https://www.w3.org/TR/WCAG22/#dfn-targets">target</a> for <a href="https://www.w3.org/TR/WCAG22/#dfn-pointer-inputs">pointer inputs</a> is at least 24 by 24 CSS pixels, except where:</p>
  <ul>
    <li><strong>Spacing:</strong> Undersized targets (those less than 24 by 24 CSS pixels) are positioned so that if a 24 CSS pixel diameter circle is centered on the <a>bounding box</a> of each, the circles do not intersect another target or the circle for another undersized target;</li>
    <li><strong>Equivalent:</strong> The function can be achieved through a different control on the same page that meets this criterion;</li>
    <li><strong>Inline:</strong> The target is in a sentence or its size is otherwise constrained by the line-height of non-target text;</li>
    <li><strong>User agent control:</strong> The size of the target is determined by the user agent and is not modified by the author;</li>
    <li><strong>Essential:</strong> A particular presentation of the target is <a href="https://www.w3.org/TR/WCAG22/#dfn-essential">essential</a> or is legally required for the information being conveyed.</li>
  </ul>
  <p class="note"><em>Note:</em> Targets that allow for values to be selected spatially based on position within the target are considered one target for the purpose of the success criterion. Examples include sliders with granular values, color pickers displaying a gradient of colors, or editable areas where you position the cursor.</p>
  <p class="note"><em>Note:</em> For inline targets the line-height should be interpreted as perpendicular to the flow of text. For example, in a language displayed top to bottom, the line-height would be horizontal.</p>
</blockquote>
<p><a href="https://www.w3.org/WAI/WCAG22/Understanding/target-size-minimum.html">Understanding Target Size (Minimum)</a></p>

## Guideline 3.2 Predictable

Make Web pages appear and operate in predictable ways.

### 3.2.6 Consistent Help (A)

<div class="quotes">
<p class="brief">In brief:</p>
<dl>
  <dt><span class="what">What to do</span></dt>
  <dd>Put help in the same place when it is on multiple pages.</dd>
  <dt><span class="why">Why it’s important</span></dt>
  <dd>People who need help can find it more easily if it's in the same place.</dd>
</dl>

<p class="persona">Persona example &mdash; a <a href="https://www.w3.org/WAI/people-use-web/user-stories/#supermarketassistant">supermarket assistant</a> with cognitive disabilities:</p>
<dl>
  <dt><span class="issue">Problem</span></dt>
  <dd><span><q>Whenever I use the online app to schedule my medical appointments, I can't remember what to do at each step. I've seen a Chat option in some places, but can't find it now.</q></span></dd>
  <dt><span class="issue">Works well</span></dt>
  <dd><span><q>When I need help, I can easily find the Chat option that's always in the lower right corner of the page.</q></span></dd>
</dl>
</div>

<p class="sclabel">WCAG success criteria:</p>
<blockquote class="sc">
<p>If a <a href="https://www.w3.org/TR/WCAG22/#dfn-web-page-s">web page</a> contains any of the following help mechanisms, and those mechanisms are repeated on multiple web pages within a <a href="https://www.w3.org/TR/WCAG22/#dfn-set-of-web-pages">set of web pages</a>, they occur in the same relative order to other page content, unless a change is initiated by the user:</p>
<ul>
  <li>Human contact details;</li>
  <li>Human contact mechanism;</li>
  <li>Self-help option;</li>
  <li>A fully automated contact mechanism.</li>
</ul>
<p class="note"><em>Note:</em> Help mechanisms may be provided directly on the page, or may be provided via a direct link to a different page containing the information.</p>
<p class="note"><em>Note:</em> For this Success Criterion, the same relative order can be thought of as how the content is ordered when the page is serialized. The visual position of a help mechanism is likely to be consistent across pages for the same page variation (e.g., CSS break-point). The user can initiate a change, such as changing the page's zoom or orientation, which may trigger a different page variation. This criterion is concerned with relative order across pages displayed in the same page variation (e.g., same zoom level and orientation).</p>
</blockquote>
<p><a href="https://www.w3.org/WAI/WCAG22/Understanding/consistent-help">Understanding Consistent Help</a></p>

## Guideline 3.3 Input Assistance

Help users avoid and correct mistakes.

### 3.3.7 Redundant Entry (A)

<div class="quotes">
<p class="brief">In brief:</p>
<dl>
  <dt><span class="what">What to do</span></dt>
  <dd>Don't ask for the same information twice in the same session.</dd>
  <dt><span class="why">Why it’s important</span></dt>
  <dd>Some people with cognitive disabilities have difficulty remembering what they entered before.</dd>
</dl>

<p class="persona">Persona example &mdash; a <a href="https://www.w3.org/WAI/people-use-web/user-stories/#supermarketassistant">supermarket assistant</a> with cognitive disabilities:</p>
<dl>
  <dt><span class="issue">Problem</span></dt>
  <dd><span><q>Whenever I use the online app to schedule my medical appointments, I have to re-type some information that I entered in a previous step.</q></span></dd>
  <dt><span class="issue">Works well</span></dt>
  <dd><span><q>The app automatically fills in information that I entered in previous steps.</q></span></dd>
</dl>
</div>

<p class="sclabel">WCAG success criteria:</p>
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

### 3.3.8 Accessible Authentication (Minimum) (AA)

<div class="quotes">
<p class="brief">In brief:</p>
<dl>
  <dt><span class="what">What to do</span></dt>
  <dd>Don’t make people solve, recall, or transcribe something to log in.</dd>
  <dt><span class="why">Why it’s important</span></dt>
  <dd>Some people with cognitive disabilities cannot solve puzzles, memorize a username and password, or retype one-time passcodes.</dd>
</dl>

<p class="persona">Persona example &mdash; a <a href="https://www.w3.org/WAI/people-use-web/user-stories/#supermarketassistant">supermarket assistant</a> with cognitive disabilities:</p>
<dl>
  <dt><span class="issue">Problem</span></dt>
  <dd><span><q>I can never remember my password, it’s really hard to get into this app.</q></span></dd>
  <dt><span class="issue">Works well</span></dt>
  <dd><span><q>To get into this app, I can put my e-mail address. Then I get an e-mail message, and I can click a link in the e-mail to get into the app.</q></span></dd>
</dl>
</div>

<p class="sclabel">WCAG success criteria:</p>
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
  <p class="note"><em>Note:</em> "Object recognition" and "Personal content" may be represented by images, video, or audio.</p>
  <p class="note"><em>Note:</em> Examples of mechanisms that satisfy this criterion include:</p>
   <ol>
      <li>support for password entry by password managers to reduce memory need, and</li>
      <li>copy and paste to reduce the cognitive burden of re-typing.</li>
    </ol>
</blockquote>
<p><a href="https://www.w3.org/WAI/WCAG22/Understanding/accessible-authentication">Understanding Accessible Authentication (Minimum)</a></p>

### 3.3.9 Accessible Authentication (Enhanced) (AAA)

<div class="quotes">
<p class="brief">In brief:</p>
<dl>
  <dt><span class="what">What to do</span></dt>
  <dd>Don’t make people recognize objects or user-supplied images and media to login.</dd>
  <dt><span class="why">Why it’s important</span></dt>
  <dd>Some people with cognitive disabilities can't do puzzles, including identifying objects and non-text information they previously supplied.</dd>
</dl>

<p class="persona">Persona example &mdash; a <a href="https://www.w3.org/WAI/people-use-web/user-stories/#supermarketassistant">supermarket assistant</a> with cognitive disabilities:</p>
<dl>
  <dt><span class="issue">Problem</span></dt>
  <dd><span><q>To get into this app, it's asking me to click on pictues of cats, but I can't tell which are cats.</q></span></dd>
  <dt><span class="issue">Works well</span></dt>
  <dd><span><q>To get into this app, I can copy and paste my password.</q></span></dd>
</dl>
</div>

<p class="sclabel">WCAG success criteria:</p>
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

## About the Personas

These personas are representations of people with disabilities developed from qualitative data on real people.

The linked persona roles go to the [[Stories of Web Users]](/people-use-web/user-stories/). That page has other personas with different disabilities.
