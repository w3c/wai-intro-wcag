---
# Translation instructions are after the "#" character in this first section. They are comments that do not show up in the web page. You do not need to translate the instructions after "#".
# In this first section, do not translate the words before a colon. For example, do not translate "title:". Do translate the text after "title:".

title: "What's New in WCAG 2.2"
title_html: "What's New in WCAG 2.2"
nav_title: "New in 2.2"
lang: en   # Change "en" to the translated-language shortcode
last_updated: 2024-03-25  # Put the date of this translation YYYY-MM-DD (with month in the middle)

# translators: # remove from the beginning of this line and the lines below: "# " (the hash sign and the space)
# - name: "Translator Name Here" # Add one -name: line for every translator
# - name: "Jan Doe"   # Replace Jan Doe with translator name
# - name: "Jan Doe"   # Replace Jan Doe with name, or delete this line if not multiple translators
# contributors:
# - name: "Jan Doe"   # Replace Jan Doe with contributor name, or delete this line if none
# - name: "Jan Doe"   # Replace Jan Doe with name, or delete this line if not multiple contributors

github:
  repository: w3c/wai-intro-wcag
  path: 'content/new-in-22.md'  # Add the language shortcode to the middle of the filename, for example: content/index.fr.md

permalink: /standards-guidelines/wcag/new-in-22/  # Add the language shortcode to the end, with no slash at end, for example: /link/to/page/fr
ref: /standards-guidelines/wcag/new-in-22/  # Do not change this

description: This page lists the new success criteria in Web Content Accessibility Guidelines (WCAG) 2.2. It includes quotes from personas to help you understand some aspects of the success criteria.

teaser_text: WCAG 2.2 has 9 additional requirements ("success criteria") that address the needs of people with cognitive or learning disabilities, mobile devices users, and ebook users. The What’s New in WCAG 2.2 page introduces the new success criteria. It includes quotes from personas to help you understand the issues.

feedbackmail: wai@w3.org
image: /content-images/wai-intro-wcag/general-social.png

# In the footer below:
# Do not change the dates
# Translate the other words below, including "Date:" and "Editor:"
# Translate the Working Group name. Leave the Working Group acronym in English.
footer: >
  <p><strong>Date:</strong> Updated 25 March 2024.</p>

  <p><strong>Editor:</strong> <a href="https://www.w3.org/People/Shawn/">Shawn Lawton Henry</a>. Contributors: Mike Gower, Shadi Abou-Zahra,  <a href="https://www.w3.org/groups/wg/eowg/participants">EOWG Participants</a>, and <a href="https://www.w3.org/groups/wg/ag/participants">AG WG Participants</a>.</p>

  <p>Developed with input from the Education and Outreach Working Group (<a href="https://www.w3.org/WAI/about/groups/eowg/">EOWG</a>) and the Accessibility Guidelines Working Group (<a href="https://www.w3.org/WAI/about/groups/eowg/">AG WG</a>).</p>


inline_css: |
  blockquote.document {
    font-style: normal;
    position: relative;
    border-inline-start: 2px solid var(--line-grey);
    padding-inline-start: 1em;
    -webkit-padding-start: 1em;
    margin-inline-start: 0;
    margin-inline-end: 0;
  
    & p:first-of-type:before {
      content: none;
    }
  
    & p:last-of-type {
        margin-bottom: inherit;
    }
  
    & p:last-of-type:after {
      content: none;
  }
---

{::nomarkdown}
{% include box.html type="start" h="2" title="Summary" class="full" %}
{:/}

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

## Introduction

For an introduction to Web Content Accessibility Guidelines (WCAG) and more about versions 2.2, 2.1, and 2.0, see the [WCAG Overview](/standards-guidelines/wcag/).

[WCAG 2.2](https://www.w3.org/TR/WCAG22/) was published as a "W3C Recommendation" web standard on 5 October 2023.

### Changes from WCAG 2.1 to WCAG 2.2

**WCAG 2.2 provides 9 additional success criteria since WCAG 2.1. They are introduced on this page.**

The 2.0 and 2.1 success criteria are essentially the same in 2.2, with one exception: 4.1.1 Parsing is obsolete and removed from WCAG 2.2. More information is in [WCAG 2 FAQ, 4.1.1 Parsing](/standards-guidelines/wcag/faq/#parsing411). WCAG 2.2 includes Notes about different languages; more information is in [WCAG 2 FAQ, internationalization](https://www.w3.org/WAI/standards-guidelines/wcag/faq/#i18n22).

## Guideline 2.4 Navigable

Provide ways to help users navigate, find content, and determine where they are.

### 2.4.11 Focus Not Obscured (Minimum) (AA) {#focus-not-obscured-minimum}

#### In brief

What to do
: Ensure when an item gets keyboard focus, it is at least partially visible.

Why it’s important
: People who can't use a mouse need to see what has keyboard focus.

#### Persona example &mdash; a [reporter](/people-use-web/user-stories/#reporter) with repetitive stress injury who uses speech recognition software

Problem
: <q>This page has a big banner that's always across the bottom. _(a sticky footer)_ When I move focus to items, some are hidden behind the banner and I can't see them.</q>

Works well
: <q>When I move focus to items, I can see them all.</q>

#### WCAG Success Criteria

{::nomarkdown}
{% include_cached blockquote-document.html type="start" class="document" href="https://www.w3.org/TR/WCAG22/#focus-not-obscured-minimum" %}
{:/}

When a [user interface component](https://www.w3.org/TR/WCAG22/#dfn-user-interface-components) receives keyboard focus, the component is not entirely hidden due to author-created content.

_Note:_ Where content in a configurable interface can be repositioned by the user, then only the initial positions of user-movable content is considered for testing and conformance of this Success Criterion.

_Note:_ Content opened by the _user_ may obscure the component receiving focus. If the user can reveal the focused component without advancing the keyboard focus, the component with focus is not considered hidden due to author-created content.

{::nomarkdown}
{% include_cached blockquote-document.html type="end" %}
{:/}

{% include resource-link.html label="Understanding Focus Not Obscured (Minimum)" href="https://www.w3.org/WAI/WCAG22/Understanding/focus-not-obscured-minimum" %}

### 2.4.12 Focus Not Obscured (Enhanced) (AAA)

#### In brief

What to do
: Ensure when an item gets keyboard focus, it is fully visible.

Why it’s important
: People who can't use a mouse need to see what has keyboard focus.-

_(Persona, problem, and works well same as [2.4.11](#focus-not-obscured-minimum) above.)_

#### WCAG Success Criteria

{::nomarkdown}
{% include_cached blockquote-document.html type="start" class="document" href="@@" %}
{:/}

When a [user interface component](https://www.w3.org/TR/WCAG22/#dfn-user-interface-components) receives keyboard focus, no part of the component is hidden by author-created content.

{::nomarkdown}
{% include_cached blockquote-document.html type="end" %}
{:/}

{% include resource-link.html href="https://www.w3.org/WAI/WCAG22/Understanding/focus-not-obscured-enhanced" label="Understanding Focus Not Obscured (Enhanced)" %}

### 2.4.13 Focus Appearance (AAA)

#### In brief

What to do
: Use a focus indicator of sufficient size and contrast.

Why it’s important
: Many people can't see small changes in visual appearance, including older people.

#### Persona example &mdash; a [reporter](/people-use-web/user-stories/#reporter) with repetitive stress injury who doesn't use a mouse<br /> and [Retiree](/people-use-web/user-stories/#retiree) with low contrast sensitivity

Problem
: <q>I can't tell where the keyboard focus is as I move around a web page or app.</q>

Works well
: <q>I can see where the keyboard focus is as I move around a web page or app.</q>

#### WCAG Success Criteria

{::nomarkdown}
{% include_cached blockquote-document.html type="start" class="document" href="https://www.w3.org/TR/WCAG22/#focus-not-obscured-minimum" %}
{:/}

When the keyboard [focus indicator](https://www.w3.org/TR/WCAG22/#dfn-focus-indicator) is visible, an area of the focus indicator meets all the following:

- is at least as large as the area of a 2 [CSS pixel](https://www.w3.org/TR/WCAG22/#dfn-css-pixels) thick [perimeter](https://www.w3.org/TR/WCAG22/#dfn-perimeter) of the unfocused component or sub-component, and
- has a contrast ratio of at least 3:1 between the same pixels in the focused and unfocused states

Exceptions:
- The focus indicator is determined by the user agent and cannot be adjusted by the author, or
- The focus indicator and the indicator's background color are not modified by the author.

_Note:_ What is perceived as the user interface component or sub-component (to determine enclosure or size) depends on its visual presentation. The visual presentation includes the component's visible content, border, and component-specific background. It does not include shadow and glow effects outside the component's content, background, or border.

_Note:_ Examples of sub-components that may receive a focus indicator are menu items in an opened drop-down menu, or focusable cells in a grid.

_Note:_ Contrast calculations can be based on colors defined within the technology (such as HTML, CSS and SVG). Pixels modified by user agent resolution enhancements and anti-aliasing can be ignored.

{::nomarkdown}
{% include_cached blockquote-document.html type="end" %}
{:/}

{% include resource-link.html href="https://www.w3.org/WAI/WCAG22/Understanding/focus-appearance.html" label="Understanding Focus Appearance" %}

## Guideline 2.5 Input Modalities

Make it easier for users to operate functionality through various inputs beyond keyboard.

### 2.5.7 Dragging Movements (AA)

#### In brief

What to do
: For any action that involves dragging, provide a simple pointer alternative.

Why it’s important
: Some people cannot use a mouse to drag items.

#### Persona example &mdash; a [retiree](/people-use-web/user-stories/#retiree) with hand tremor

Problem
: <q>I cannot hold down the mouse button and drag it accurately enough to move the items in this list.</q>

Works well
: <q>When I click on an item in the list, I get up and down arrows and I can click those to change the order.</q>

#### WCAG Success Criteria

{::nomarkdown}
{% include_cached blockquote-document.html type="start" class="document" href="https://www.w3.org/TR/WCAG22/#focus-not-obscured-minimum" %}
{:/}

All functionality that uses a [dragging movement](https://www.w3.org/TR/WCAG22/#dfn-dragging-movements) for operation can be achieved by a [single pointer](https://www.w3.org/TR/WCAG22/#dfn-single-pointer) without dragging, unless dragging is [essential](https://www.w3.org/TR/WCAG22/#dfn-essential) or the functionality is determined by the user agent and not modified by the author.

_Note:_ This requirement applies to web content that interprets pointer actions (i.e. this does not apply to actions that are required to operate the user agent or assistive technology).

{::nomarkdown}
{% include_cached blockquote-document.html type="end" %}
{:/}

{% include resource-link.html href="https://www.w3.org/WAI/WCAG22/Understanding/dragging-movements" label="Understanding Dragging Movements" %}

### 2.5.8 Target Size (Minimum) (AA)

#### In brief

What to do
: Ensure targets meet a minimum size or have sufficient spacing around them.

Why it’s important
: Some people with physical impairments cannot click small buttons that are close together.

#### Persona example &mdash; a [retiree](/people-use-web/user-stories/#retiree) with hand tremor

Problem
: <q>The buttons are so close, I hit "Cancel" when going for "Submit". Then I have to start all over again.</q>

Works well
: <q>There is more space between the buttons so I don't hit the wrong button even when I'm riding on the bumpy bus.</q>

#### WCAG Success Criteria

{::nomarkdown}
{% include_cached blockquote-document.html type="start" class="document" href="https://www.w3.org/TR/WCAG22/#focus-not-obscured-minimum" %}
{:/}

The size of the [target](https://www.w3.org/TR/WCAG22/#dfn-targets) for [pointer inputs](https://www.w3.org/TR/WCAG22/#dfn-pointer-inputs) is at least 24 by 24 CSS pixels, except where:

- *Spacing:* Undersized targets (those less than 24 by 24 CSS pixels) are positioned so that if a 24 CSS pixel diameter circle is centered on the <a>bounding box</a> of each, the circles do not intersect another target or the circle for another undersized target;
- *Equivalent:* The function can be achieved through a different control on the same page that meets this criterion;
- *Inline:* The target is in a sentence or its size is otherwise constrained by the line-height of non-target text;
- *User agent control:* The size of the target is determined by the user agent and is not modified by the author;
- *Essential:* A particular presentation of the target is [essential](https://www.w3.org/TR/WCAG22/#dfn-essential) or is legally required for the information being conveyed.

_Note:_ Targets that allow for values to be selected spatially based on position within the target are considered one target for the purpose of the success criterion. Examples include sliders with granular values, color pickers displaying a gradient of colors, or editable areas where you position the cursor.

_Note:_ For inline targets the line-height should be interpreted as perpendicular to the flow of text. For example, in a language displayed top to bottom, the line-height would be horizontal.

{::nomarkdown}
{% include_cached blockquote-document.html type="end" %}
{:/}

{% include resource-link.html href="https://www.w3.org/WAI/WCAG22/Understanding/target-size-minimum.html" label="Understanding Target Size (Minimum)" %}

## Guideline 3.2 Predictable

Make Web pages appear and operate in predictable ways.

### 3.2.6 Consistent Help (A)

#### In brief

What to do
: Put help in the same place when it is on multiple pages.

Why it’s important
: People who need help can find it more easily if it's in the same place.

#### Persona example &mdash; a [supermarket assistant](/people-use-web/user-stories/#supermarketassistant) with cognitive disabilities

Problem
: <q>Whenever I use the online app to schedule my medical appointments, I can't remember what to do at each step. I've seen a Chat option in some places, but can't find it now.</q>

Works well
: <q>When I need help, I can easily find the Chat option that's always in the lower right corner of the page.</q>

#### WCAG Success Criteria

{::nomarkdown}
{% include_cached blockquote-document.html type="start" class="document" href="https://www.w3.org/TR/WCAG22/#focus-not-obscured-minimum" %}
{:/}

If a [web page](https://www.w3.org/TR/WCAG22/#dfn-web-page-s) contains any of the following help mechanisms, and those mechanisms are repeated on multiple web pages within a [set of web pages](https://www.w3.org/TR/WCAG22/#dfn-set-of-web-pages), they occur in the same relative order to other page content, unless a change is initiated by the user:

- Human contact details;
- Human contact mechanism;
- Self-help option;
- A fully automated contact mechanism.

_Note:_ Help mechanisms may be provided directly on the page, or may be provided via a direct link to a different page containing the information.

_Note:_ For this Success Criterion, the same relative order can be thought of as how the content is ordered when the page is serialized. The visual position of a help mechanism is likely to be consistent across pages for the same page variation (e.g., CSS break-point). The user can initiate a change, such as changing the page's zoom or orientation, which may trigger a different page variation. This criterion is concerned with relative order across pages displayed in the same page variation (e.g., same zoom level and orientation).

{::nomarkdown}
{% include_cached blockquote-document.html type="end" %}
{:/}

{% include resource-link.html href="https://www.w3.org/WAI/WCAG22/Understanding/consistent-help" label="Understanding Consistent Help" %}

## Guideline 3.3 Input Assistance

Help users avoid and correct mistakes.

### 3.3.7 Redundant Entry (A)

#### In brief

What to do
: Don't ask for the same information twice in the same session.

Why it’s important
: Some people with cognitive disabilities have difficulty remembering what they entered before.

#### Persona example &mdash; a [supermarket assistant](/people-use-web/user-stories/#supermarketassistant) with cognitive disabilities

Problem
: <q>Whenever I use the online app to schedule my medical appointments, I have to re-type some information that I entered in a previous step.</q>

Works well
: <q>The app automatically fills in information that I entered in previous steps.</q>

#### WCAG Success Criteria

{::nomarkdown}
{% include_cached blockquote-document.html type="start" class="document" href="https://www.w3.org/TR/WCAG22/#focus-not-obscured-minimum" %}
{:/}

Information previously entered by or provided to the user that is required to be entered again in the same [process](https://www.w3.org/TR/WCAG22/#dfn-processes) is either:
- auto-populated, or
- available for the user to select.

Except when:

- re-entering the information is [essential](https://www.w3.org/TR/WCAG22/#dfn-essential),
- the information is required to ensure the security of the content, or
- previously entered information is no longer valid.

{::nomarkdown}
{% include_cached blockquote-document.html type="end" %}
{:/}

{% include resource-link.html href="https://www.w3.org/WAI/WCAG22/Understanding/redundant-entry" label="Understanding Redundant Entry" %}

### 3.3.8 Accessible Authentication (Minimum) (AA)

#### In brief

What to do
: Don’t make people solve, recall, or transcribe something to log in.

Why it’s important
: Some people with cognitive disabilities cannot solve puzzles, memorize a username and password, or retype one-time passcodes.

#### Persona example &mdash; a [supermarket assistant](/people-use-web/user-stories/#supermarketassistant) with cognitive disabilities

Problem
: <q>I can never remember my password, it’s really hard to get into this app.</q>

Works well
: <q>To get into this app, I can put my e-mail address. Then I get an e-mail message, and I can click a link in the e-mail to get into the app.</q>

#### WCAG Success Criteria

{::nomarkdown}
{% include_cached blockquote-document.html type="start" class="document" href="https://www.w3.org/TR/WCAG22/#focus-not-obscured-minimum" %}
{:/}

A [cognitive function test](https://www.w3.org/TR/WCAG22/#dfn-cognitive-function-test) (such as remembering a password or solving a puzzle) is not required for any step in an authentication process unless that step provides at least one of the following:

Alternative
: Another authentication method that does not rely on a cognitive function test.

Mechanism
: A mechanism is available to assist the user in completing the cognitive function test.

Object Recognition
: The cognitive function test is to recognize objects.

Personal Content
: The cognitive function test is to identify non-text content the user provided to the website.-

_Note:_ "Object recognition" and "Personal content" may be represented by images, video, or audio.

_Note:_ Examples of mechanisms that satisfy this criterion include:
1. support for password entry by password managers to reduce memory need, and
2. copy and paste to reduce the cognitive burden of re-typing.

{::nomarkdown}
{% include_cached blockquote-document.html type="end" %}
{:/}

{% include resource-link.html href="https://www.w3.org/WAI/WCAG22/Understanding/accessible-authentication-minimum" label="Understanding Accessible Authentication (Minimum)" %}

### 3.3.9 Accessible Authentication (Enhanced) (AAA)

#### In brief

What to do
: Don’t make people recognize objects or user-supplied images and media to login.

Why it’s important
: Some people with cognitive disabilities can't do puzzles, including identifying objects and non-text information they previously supplied.

#### Persona example &mdash; a [supermarket assistant](/people-use-web/user-stories/#supermarketassistant) with cognitive disabilities

Problem
: <q>To get into this app, it's asking me to click on pictures of cats, but I can't tell which are cats.</q>

Works well
: <q>To get into this app, I can copy and paste my password.</q>

#### WCAG Success Criteria

{::nomarkdown}
{% include_cached blockquote-document.html type="start" class="document" href="https://www.w3.org/TR/WCAG22/#focus-not-obscured-minimum" %}
{:/}

A [cognitive function test](https://www.w3.org/TR/WCAG22/#dfn-cognitive-function-test) (such as remembering a password or solving a puzzle) is not required for any step in an authentication process unless that step provides at least one of the following:

Alternative
: Another authentication method that does not rely on a cognitive function test.

Mechanism
: A mechanism is available to assist the user in completing the cognitive function test.-

{::nomarkdown}
{% include_cached blockquote-document.html type="end" %}
{:/}

{% include resource-link.html href="https://www.w3.org/WAI/WCAG22/Understanding/accessible-authentication-enhanced" label="Understanding Accessible Authentication (Enhanced)" %}

## About the Personas

These personas are representations of people with disabilities developed from qualitative data on real people.

The linked persona roles go to the [[Stories of Web Users]](/people-use-web/user-stories/). That page has other personas with different disabilities.
