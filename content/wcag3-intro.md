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

This page will be updated to provide and link to additional information. For example, in the future it could link to mapping between WCAG 2 and 3 and to other support for those wanting to transition from 2 to 3.

## Status: Draft for Review

**[W3C Accessibility Guidelines (WCAG) 3.0 Working Draft](https://www.w3.org/TR/WCAG30)** is currently an incomplete, unpolished Working Draft. It includes:
* proposed structure
* proposed [conformance model](#model)
* 5 draft example guidelines

<div style="float: right; margin-left: 2rem; width: 30%; max-width: 220px">
<svg id="dialog" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 150 150">
<path d="M82,82v4c0,3.3-2.7,6-6,6H40.4H39L38,92.8l-13,10V96v-4h-4h-4c-3.3,0-6-2.7-6-6V44c0-3.3,2.7-6,6-6h23v-4H17  c-5.5,0-10,4.5-10,10v42c0,5.5,4.5,10,10,10h4v15l19.4-15H76c5.5,0,10-4.5,10-10v-4H82z" fill="#005A6A"/>
<path d="M111,22c3.3,0,6,2.7,6,6v42c0,3.3-2.7,6-6,6h-4h-4v4v6.9l-13-10L89,76h-1.4H52c-3.3,0-6-2.7-6-6V28  c0-3.3,2.7-6,6-6H111 M111,18H52c-5.5,0-10,4.5-10,10v42c0,5.5,4.5,10,10,10h35.6L107,95V80h4c5.5,0,10-4.5,10-10V28  C121,22.5,116.5,18,111,18L111,18z" fill="#003366"/>
</svg>
</div>

We are seeking input from evaluators, developers, designers, project managers, policy makers, people with disabilities, and others &mdash; particularly on:
* Is this structure clear?
* How well does this conformance model work across different situations?
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

<span style="font-style:italic; margin-left:22px;">(More goals are in the [Background section below](#background).)</span>

WCAG 3 is **similar** to previous versions in some ways. It has similar:
* goal of providing guidance on making websites, apps, etc. accessible to people with disabilities
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

WCAG 3 has:
* **Guidelines**
   * Solutions to accessibility problems
   * More **granular** than the guidelines in WCAG 2
   * Each guideline has outcomes
* **Outcomes**
   * Testable statements
   * Similar to **success criteria** in WCAG 2, more granular
   * Each outcome includes:
      * Critical errors
      * Rating scale

More _granular_ means they are more specific, instead of broad. That generally makes them simpler. And it means there will be more of them.

WCAG 3 supporting material includes:
* **Methods**
   * Technology-specific ways to achieve an outcome
   * Tests for the outcome
   * Similar to **Techniques** for WCAG 2
* **How-To documents**
   * Explain more about each outcome??guideline, such as how it addresses accessibility needs
   * Similar to the **Understanding** documents for WCAG 2
* **Functional categories** of **functional needs**
   * Categorized list of needs of people with disabilities

### Conformance Model {#model}

The _conformance model_ is the way to determine and communicate how well a website meets WCAG. The conformance model in this draft of WCAG 3 is very different from WCAG 2. It is intended to:
* be more flexible for organizations (that is, owners and developers of websites, apps, etc.)
* encourage more accessible user experiences

Some new aspects of the proposed WCAG 3 conformance model:
* Conformance is more focused on **[processes](@@)** (tasks such as ordering an item or registering for a class), rather than web pages.
* Outcomes can be **rated**, beyond just pass or fail. Ratings are 0-5.
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

## Development

### WCAG 3 Name (formerly "Silver" project)

WCAG 3 developed from the “Silver” project. 

WCAG **3** is W3C Accessibility Guidelines.<br>
WCAG **2** is Web Content Accessibility Guidelines.
 
“W3C Accessibility Guidelines (WCAG) 3.0” was chosen:
* because of wide-spread familiarity with the “WCAG” acronym
* to encompass the broader scope beyond “content”

### Timeline
<div style="float: right; margin-left: 2rem; width: 20%; max-width: 111px">
<svg id="calendar" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1280.000000 1272.000000">
<g transform="translate(0.000000,1272.000000) scale(0.100000,-0.100000)"
fill="#003366" stroke="none">
<path d="M1731 12705 c-121 -34 -218 -115 -269 -223 l-27 -57 0 -1115 0 -1115
32 -66 c41 -82 111 -150 201 -192 63 -30 74 -32 208 -35 148 -4 212 6 294 48
66 34 138 108 172 178 l33 67 3 1090 c2 1069 2 1091 -18 1155 -35 115 -121
204 -240 252 -73 28 -305 36 -389 13z"/>
<path d="M4721 12704 c-124 -33 -238 -131 -283 -241 l-23 -58 -3 -1059 c-2
-701 1 -1077 8 -1115 27 -148 127 -259 279 -311 87 -29 295 -29 383 1 152 51
250 158 277 304 15 78 15 2089 1 2166 -30 158 -155 283 -318 318 -73 15 -256
13 -321 -5z"/>
<path d="M7702 12704 c-140 -37 -248 -141 -286 -275 -15 -50 -16 -170 -14
-1145 l3 -1089 27 -55 c55 -113 141 -185 261 -222 58 -17 88 -20 210 -16 135
3 145 5 209 35 85 40 156 106 199 186 l34 62 0 1120 0 1120 -27 57 c-52 111
-150 190 -273 223 -75 19 -270 19 -343 -1z"/>
<path d="M10691 12705 c-121 -34 -218 -115 -269 -223 l-27 -57 0 -1120 0
-1120 31 -60 c41 -77 116 -148 202 -188 67 -32 67 -32 232 -32 149 0 170 2
223 23 115 47 203 140 239 254 17 57 18 117 18 1128 0 1011 -1 1071 -18 1128
-36 113 -127 208 -244 254 -71 28 -304 36 -387 13z"/>
<path d="M319 10986 c-144 -39 -261 -167 -304 -333 -13 -50 -15 -667 -15
-5113 0 -5519 -4 -5114 56 -5232 50 -98 112 -151 272 -231 l145 -72 6001 0
6001 0 68 33 c120 59 206 169 242 309 13 50 15 667 15 5113 0 5519 4 5114 -56
5232 -50 98 -112 151 -272 231 l-145 72 -419 3 -418 3 0 -439 c0 -482 -2 -500
-62 -594 -70 -111 -221 -210 -373 -243 -103 -23 -474 -17 -553 9 -73 24 -161
111 -205 203 l-32 68 -5 460 -5 460 -72 3 -73 3 0 34 0 35 -800 0 -800 0 0
-432 c0 -460 -2 -485 -50 -578 -37 -74 -137 -163 -232 -209 -136 -65 -191 -73
-439 -69 -268 6 -296 13 -384 101 -72 73 -113 150 -125 238 -6 35 -10 246 -9
469 l0 405 -71 3 -70 3 0 34 0 35 -800 -2 -801 -3 1 -396 c0 -220 -4 -428 -10
-468 -25 -178 -158 -319 -367 -387 -87 -29 -91 -29 -318 -29 -285 0 -318 8
-407 93 -40 38 -70 79 -96 131 l-37 75 -3 458 -3 458 -74 0 -75 0 0 35 0 35
-800 0 -799 0 -3 -463 -3 -462 -33 -67 c-64 -130 -225 -245 -397 -283 -102
-23 -474 -17 -552 8 -70 24 -159 111 -204 203 l-34 69 -5 460 -5 460 -72 3
-73 3 0 34 0 35 -397 -1 c-282 0 -411 -4 -444 -13z m11445 -2265 c52 -7 64
-12 93 -46 18 -21 43 -59 55 -84 l23 -46 0 -3805 0 -3805 -29 -53 c-38 -67
-102 -126 -174 -160 l-57 -27 -5349 0 -5348 0 -34 39 c-18 21 -44 60 -56 85
l-23 46 0 3805 0 3805 27 50 c33 63 113 139 175 166 27 11 75 24 108 29 76 10
10509 11 10589 1z"/>
<path d="M10950 8306 c0 -3 -1 -99 -1 -213 l0 -208 23 0 c16 0 23 6 22 18 -1
9 2 17 7 17 5 0 9 -4 9 -8 0 -15 49 -32 91 -32 121 0 162 225 53 296 -32 21
-96 21 -128 0 l-25 -16 -3 73 c-3 66 -5 72 -25 75 -13 2 -23 1 -23 -2z m189
-182 c16 -21 21 -41 21 -91 0 -55 -4 -67 -25 -88 -15 -16 -36 -25 -55 -25 -19
0 -40 9 -55 25 -21 21 -25 33 -25 88 0 83 23 117 80 117 30 0 43 -6 59 -26z"/>
<path d="M8982 8088 l3 -203 25 0 25 0 0 163 c0 89 2 162 5 162 3 0 37 -62 75
-136 103 -200 100 -196 138 -192 l32 3 3 203 2 202 -25 0 -25 0 0 -167 c0 -98
-4 -163 -9 -157 -5 5 -46 80 -92 167 l-84 157 -38 0 -37 0 2 -202z"/>
<path d="M9481 8193 c-68 -13 -104 -68 -105 -158 0 -103 48 -155 142 -155 85
0 132 57 132 162 0 103 -75 169 -169 151z m90 -69 c20 -22 24 -35 24 -91 0
-59 -3 -67 -28 -89 -45 -38 -98 -31 -122 17 -29 54 -11 167 27 182 34 14 75 6
99 -19z"/>
<path d="M10152 8190 c-128 -29 -150 -234 -32 -295 33 -17 126 -20 164 -5 35
13 38 56 4 45 -13 -4 -46 -9 -75 -12 -48 -5 -54 -3 -83 25 -16 17 -30 40 -30
51 0 20 5 21 110 21 l110 0 0 43 c0 45 -27 100 -57 115 -29 15 -75 20 -111 12z
m95 -62 c13 -12 23 -32 23 -45 0 -22 -3 -23 -85 -23 -79 0 -85 1 -85 20 0 60
99 93 147 48z"/>
<path d="M10516 8189 c-15 -4 -37 -16 -47 -25 -18 -16 -19 -16 -19 4 0 17 -6
22 -25 22 l-26 0 3 -152 c3 -148 4 -153 24 -156 21 -3 22 1 26 107 3 99 6 112
27 135 32 34 83 35 105 4 12 -17 16 -49 16 -135 l0 -113 25 0 25 0 0 100 c0
113 14 156 55 166 74 18 95 -20 95 -168 0 -97 0 -99 23 -96 21 3 22 8 25 104
3 128 -10 173 -58 196 -42 21 -95 11 -125 -22 -18 -20 -18 -20 -44 4 -31 28
-66 37 -105 25z"/>
<path d="M11377 8186 c-48 -18 -62 -29 -81 -70 -33 -71 -14 -170 41 -211 56
-40 213 -28 213 17 0 16 -4 19 -22 14 -51 -16 -109 -18 -138 -6 -28 12 -60 54
-60 79 0 6 45 11 113 13 l112 3 -1 42 c-2 93 -88 151 -177 119z m108 -61 c14
-13 25 -33 25 -45 0 -20 -5 -21 -87 -18 -82 3 -88 4 -85 23 9 60 102 86 147
40z"/>
<path d="M11756 8190 c-15 -5 -37 -17 -47 -26 -18 -16 -19 -16 -19 4 0 17 -6
22 -25 22 l-25 0 0 -156 0 -155 23 3 c21 3 22 9 27 108 3 58 10 113 14 123 12
25 38 37 80 37 29 0 36 4 36 19 0 15 -23 35 -33 30 -1 0 -15 -5 -31 -9z"/>
<path d="M9705 8173 c3 -10 27 -71 51 -137 58 -154 59 -156 93 -156 27 0 31 6
57 73 15 39 40 106 56 147 15 41 28 78 28 82 0 5 -11 8 -24 8 -21 0 -28 -12
-65 -112 -23 -62 -45 -118 -49 -125 -5 -7 -26 38 -53 110 -42 113 -48 122 -74
125 -23 3 -27 1 -20 -15z"/>
<path d="M1000 6885 l0 -585 700 0 700 0 0 585 0 585 -700 0 -700 0 0 -585z"/>
<path d="M2550 6885 l0 -585 700 0 700 0 0 585 0 585 -700 0 -700 0 0 -585z"/>
<path d="M4100 6885 l0 -585 700 0 700 0 0 585 0 585 -700 0 -700 0 0 -585z"/>
<path d="M5650 6885 l0 -585 700 0 700 0 0 585 0 585 -700 0 -700 0 0 -585z"/>
<path d="M7200 6885 l0 -585 700 0 700 0 0 585 0 585 -700 0 -700 0 0 -585z"/>
<path d="M8750 6885 l0 -585 700 0 700 0 0 585 0 585 -700 0 -700 0 0 -585z"/>
<path d="M10300 6885 l0 -585 700 0 700 0 0 585 0 585 -700 0 -700 0 0 -585z"/>
<path d="M1000 5555 l0 -585 700 0 700 0 0 585 0 585 -700 0 -700 0 0 -585z"/>
<path d="M2550 5555 l0 -585 700 0 700 0 0 585 0 585 -700 0 -700 0 0 -585z"/>
<path d="M4100 5555 l0 -585 700 0 700 0 0 585 0 585 -700 0 -700 0 0 -585z"/>
<path d="M5650 5555 l0 -585 700 0 700 0 0 585 0 585 -700 0 -700 0 0 -585z"/>
<path d="M7200 5555 l0 -585 700 0 700 0 0 585 0 585 -700 0 -700 0 0 -585z"/>
<path d="M8750 5555 l0 -585 700 0 700 0 0 585 0 585 -700 0 -700 0 0 -585z"/>
<path d="M10300 5555 l0 -585 700 0 700 0 0 585 0 585 -700 0 -700 0 0 -585z"/>
<path d="M1000 4245 l0 -585 700 0 700 0 0 585 0 585 -700 0 -700 0 0 -585z"/>
<path d="M2550 4245 l0 -585 700 0 700 0 0 585 0 585 -700 0 -700 0 0 -585z"/>
<path d="M4100 4245 l0 -585 700 0 700 0 0 585 0 585 -700 0 -700 0 0 -585z"/>
<path d="M5650 4245 l0 -585 700 0 700 0 0 585 0 585 -700 0 -700 0 0 -585z"/>
<path d="M7200 4245 l0 -585 700 0 700 0 0 585 0 585 -700 0 -700 0 0 -585z"/>
<path d="M8750 4245 l0 -585 700 0 700 0 0 585 0 585 -700 0 -700 0 0 -585z"/>
<path d="M10300 4245 l0 -585 700 0 700 0 0 585 0 585 -700 0 -700 0 0 -585z"/>
<path d="M1000 2930 l0 -590 700 0 700 0 0 590 0 590 -700 0 -700 0 0 -590z"/>
<path d="M2550 2930 l0 -590 700 0 700 0 0 590 0 590 -700 0 -700 0 0 -590z"/>
<path d="M4100 2930 l0 -590 700 0 700 0 0 590 0 590 -700 0 -700 0 0 -590z"/>
<path d="M5650 2930 l0 -590 700 0 700 0 0 590 0 590 -700 0 -700 0 0 -590z"/>
<path d="M7200 2930 l0 -590 700 0 700 0 0 590 0 590 -700 0 -700 0 0 -590z"/>
<path d="M8750 2930 l0 -590 700 0 700 0 0 590 0 590 -700 0 -700 0 0 -590z"/>
<path d="M10300 2930 l0 -590 700 0 700 0 0 590 0 590 -700 0 -700 0 0 -590z"/>
<path d="M1000 1605 l0 -585 700 0 700 0 0 585 0 585 -700 0 -700 0 0 -585z"/>
<path d="M2550 1605 l0 -585 700 0 700 0 0 585 0 585 -700 0 -700 0 0 -585z"/>
<path d="M4100 1605 l0 -585 700 0 700 0 0 585 0 585 -700 0 -700 0 0 -585z"/>
<path d="M5650 1605 l0 -585 700 0 700 0 0 585 0 585 -700 0 -700 0 0 -585z"/>
<path d="M7200 1605 l0 -585 700 0 700 0 0 585 0 585 -700 0 -700 0 0 -585z"/>
<path d="M8750 1605 l0 -585 700 0 700 0 0 585 0 585 -700 0 -700 0 0 -585z"/>
<path d="M10300 1605 l0 -585 700 0 700 0 0 585 0 585 -700 0 -700 0 0 -585z"/>
</g>
</svg>
</div>

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

<div style="float: right; margin-left: 2rem; width: 10%; max-width: 111px">
<img src="https://www.w3.org/WAI/GL/WCAG3/2020/img/silver-sticker" alt="logo: ag w3c a11y silver" style="height: 10ex;" />
</div>

This expandable section provides more about goals, user research, development process, and the draft example guidelines.

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

More about goals is in the [spec requirements doc](https://www.@@).

#### Development Process

In defining the accessibility requirements in WCAG 3.0, Silver started fresh with a list of accessibility needs of people with disabilities. Development goes through this process:
1. From a specific user need, write an outcome to meet that user need.
2. Define tests to determine if the outcome is met.
3. Write the method to meet the outcome.
4. Group the outcomes under guidelines. [@@correct?]
5. Write the How-To support information.

#### _Draft Examples_ {#eg-guidelines}

The draft guidelines included in the First Public Working Draft were selected to illustrate specific aspects of the proposed structure of WCAG 3 and relationship with WCAG 2.
* Migrating a WCAG 2 success criterion as is into a WCAG 3 outcome: [Text alternatives]( https://w3c.github.io/silver/guidelines/#text-alternatives)
* Merging multiple AA and AAA success criteria into a single WCAG 3 guideline: [Visual contrast of text]( https://w3c.github.io/silver/guidelines/#visual-contrast-of-text)
* Adding new accessibility requirements that did not fit the parameters for being included in WCAG 2: [Clear words](https://w3c.github.io/silver/guidelines/#clear-words)
* Integrating WCAG 2 content with significant updates: [Structured content](https://w3c.github.io/silver/guidelines/#structured-content)
* Adapting WCAG 2 success criteria to emerging technologies, such as virtual reality: [Captions](https://w3c.github.io/silver/guidelines/#captions)

These guidelines are rough draft examples, and will be refined and edited in future Working Drafts.

{% include_cached excol.html type="end" %}

<div class="excol-all"></div>
