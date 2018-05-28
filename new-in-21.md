---
title: What's New in WCAG 2.1
nav: New in 2.1
permalink: /standards-guidelines/wcag/new-in-21/
layout: default
github:
  path: 'new-in-21.md'
footer: >
  <p><strong>Date: DRAFT</strong> Updated @@ June 2018.</p>
  <p><strong>Editors:</strong> @@...</p>
  <p>Developed with input from the Education and Outreach Working Group (<a href="https://www.w3.org/WAI/about/groups/eowg/">EOWG</a>) and the Accessibility Guidelines Working Group (<a href="https://www.w3.org/WAI/about/groups/eowg/">AG WG</a>).</p>

---

<style>
blockquote {font-style:normal !important;}
blockquote p:first-of-type:before, blockquote p:last-of-type:after, blockquote dl:last-of-type:after {content:'' !important; margin-left: 0 !important;}
blockquote.sc {padding: 0 10px 15px 20px; border: solid #ccc 1px; background: #f0f0f0; color: #000;}
blockquote.quotes p {text-indent: -5em; padding-left: 5em;}
.persona {font-style: italic;}
.qnote {margin-top: -15px}
</style>

{::nomarkdown}
{% include box.html type="start" h="2" title="Summary" class="full" %}
{:/}

This page lists the new success criteria in Web Content Accessibility Guidelines (WCAG) 2.1.

It includes quotes from personas (fictional people) to help you understand some aspects of the success criteria. It also includes links to Understanding documents that explain the success criteria in detail and provide more examples.

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

WCAG 2.1 provides additional accessibility requirements for [mobile accessibility](https://www.w3.org/WAI/standards-guidelines/mobile/#intro), people with low vision, and people with cognitive and learning disabilities.

For information about WCAG 2.0 and WCAG 2.1, see the [WCAG Overview](https://w3c.github.io/wai-intro-wcag/standards-guidelines/wcag/).

## Guideline 1.3 Adaptable

Create content that can be presented in different ways (for example simpler layout) without losing information or structure.

### 1.3.4 Orientation (Level AA)
<blockquote class="sc">
  <p>Content does not restrict its view and  operation to a single display orientation, such as portrait or landscape,  unless a specific display orientation is <a href="https://www.w3.org/TR/WCAG21/#dfn-essential" data-link-type="dfn">essential</a>.</p>
</blockquote>
<p class="persona">Person who uses a wheelchair:</p>
<blockquote class="quotes">
  <p>Problem: &quot;I can't rotate my tablet &mdash;  it's attached to my wheelchair.&quot;</p>
  <p>Works well: &quot;The application works whether I  attach my tablet horizontally or vertically.&quot;</p>
</blockquote>
<p><a href="https://www.w3.org/WAI/WCAG21/Understanding/orientation.html">Understanding Orientation</a></p>

### 1.3.5 Identify Input Purpose (AA)
<blockquote class="sc">
  <p>The purpose of each input field collecting information about the user can be <a href="https://www.w3.org/TR/WCAG21/#dfn-programmatically-determinable" data-link-type="dfn">programmatically determined</a> when:</p>
  <ul>
    <li>The input field serves a purpose identified in the <a href="https://www.w3.org/TR/WCAG21/#input-purposes">Input Purposes for User Interface Components section</a>; and</li>
    <li>The content is implemented using technologies with support for identifying the expected meaning for form input data.</li>
  </ul>
</blockquote>
<p class="persona">Person who has dyslexia and  dyscalculia:</p>
<blockquote class="quotes">
  <p>Problem: &quot;My address is so complicated. There's lots of numbers and long words. It's hard to type it all without making mistakes.&quot;</p>
  <p>Works well: &quot;I love websites that can automatically fill it all in for me. Then I don't have to work so hard to get the  numbers and spelling right.&quot;</p>
  <p class="qnote">Note: This works because the fields use autocomplete.</p>
</blockquote>
<p><a href="https://www.w3.org/WAI/WCAG21/Understanding/orientation.html">Understanding Orientation</a> </p>

### 1.3.6 Identify Purpose (AAA)
<blockquote class="sc">
  <p>In content implemented using markup languages, the purpose of <a href="https://www.w3.org/TR/WCAG21/#dfn-user-interface-components" data-link-type="dfn">User Interface Components</a>, icons, and <a href="https://www.w3.org/TR/WCAG21/#dfn-regions" data-link-type="dfn">regions</a> can be <a href="https://www.w3.org/TR/WCAG21/#dfn-programmatically-determinable" data-link-type="dfn">programmatically determined</a>.</p>
</blockquote>
<p class="persona">Person with cognitive disability:</p>
<blockquote class="quotes">
  <p>Problem and Works well: &quot;I have software that  changes the words in the navigation into symbols. It works pretty good with  some websites, and not at all with other websites.&quot;</p>
</blockquote>
<p><a href="https://www.w3.org/WAI/WCAG21/Understanding/identify-purpose.html">Understanding Identify Purpose</a></p>

## Guideline 1.4 Distinguishable

Make it easier for users to see and hear content including separating foreground from background.

### 1.4.10 Reflow (AA)
<blockquote class="sc">
  <p>Content can be presented without loss of information or functionality, and without requiring scrolling in two dimensions for:</p>
  <ul>
    <li>Vertical scrolling content at a width equivalent to 320 <a href="https://www.w3.org/TR/WCAG21/#dfn-css-pixels" data-link-type="dfn">CSS pixels</a>;</li>
    <li>Horizontal scrolling content at a height equivalent to 256 <a href="https://www.w3.org/TR/WCAG21/#dfn-css-pixels" data-link-type="dfn">CSS pixels</a>;</li>
  </ul>
  <p>Except for parts of the content which require two-dimensional layout for usage or meaning.</p>
</blockquote>
<p class="persona">Person with low vision:</p>
<blockquote class="quotes">
  <p>Problem: &quot;It's nearly impossible to read  text if I have to scroll right and left to read each line. It's disorienting  and I lose my place. It makes it hard to understand what I'm reading.&quot;</p>
  <p>Works well: &quot;I increase the text size 400% and  it reflowed within the width of the window. I can read it easily without  scrolling back and forth.&quot;</p>
</blockquote>
<p><a href="https://www.w3.org/WAI/WCAG21/Understanding/reflow.html">Understanding Reflow</a></p>

### 1.4.11 Non-Text  Contrast (AA)
<blockquote class="sc">
  <p>The visual <a href="https://www.w3.org/TR/WCAG21/#dfn-presentation" data-link-type="dfn">presentation</a> of the following have a <a href="https://www.w3.org/TR/WCAG21/#dfn-contrast-ratio" data-link-type="dfn">contrast ratio</a> of at least 3:1 against adjacent color(s):</p>
  <dl>
    <dt>User Interface Components</dt>
    <dd>Visual information used to indicate <a href="https://www.w3.org/TR/WCAG21/#dfn-states" data-link-type="dfn">states</a> and boundaries of <a href="https://www.w3.org/TR/WCAG21/#dfn-user-interface-components" data-link-type="dfn">user interface components</a>, except for inactive components or where the appearance of the component is determined by the user agent and not modified by the author;</dd>
    <dt>Graphical Objects</dt>
    <dd>Parts of graphics required to understand the content, except when a particular presentation of graphics is <a href="https://www.w3.org/TR/WCAG21/#dfn-essential" data-link-type="dfn">essential</a> to the information being conveyed.</dd>
  </dl>
</blockquote>
<p class="persona"><a hr><a href="https://www.w3.org/WAI/people-use-web/user-stories/#retiree">Yun</a></a>, retiree with low contrast sensitivity:</p>
<blockquote class="quotes">
  <p>Problem: &quot;I couldn't use the &quot;Order Form&quot;  &mdash; there were no text boxes. After a long call with customer service, I learned  there were text box borders that were too light for me to see.</p>
  <p>Works well: &quot;It's easy for me to see all the  icons and buttons and everything &mdash; even in the sunlight.&quot;</p>
</blockquote>
<p><a href="https://www.w3.org/WAI/WCAG21/Understanding/non-text-contrast.html">Understanding Non-text Contrast</a></p>

### 1.4.12 Text Spacing (AA)
<blockquote class="sc">
  <p>In content implemented using markup languages that support the following <a href="https://www.w3.org/TR/WCAG21/#dfn-text" data-link-type="dfn">text</a> <a href="https://www.w3.org/TR/WCAG21/#dfn-style-properties" data-link-type="dfn">style properties</a>, no loss of content or functionality occurs by setting all of the following and by changing no other style property:</p>
  <ul>
    <li>Line height (line spacing) to at least 1.5 times the font size;</li>
    <li>Spacing following paragraphs to at least 2 times the font size;</li>
    <li>Letter spacing (tracking) to at least 0.12 times the font size;</li>
    <li>Word spacing to at least 0.16 times the font size.</li>
  </ul>
  <p>Exception: Human languages and scripts that do not make use of one or more of these text style properties in written text can conform using only the properties that exist for that combination of language and script.</p>
</blockquote>
<p class="persona"><a href="https://www.w3.org/WAI/people-use-web/user-stories/#classroomstudent">Preety</a>, student with attention deficit hyperactivity disorder and dyslexia:<br/>
  <span class="persona">and <a href="https://www.w3.org/WAI/people-use-web/user-stories/#retiree">Yun</a>, retiree with low </span>vision:</p>
<blockquote class="quotes">
  <p>Problem:  &quot;Most text is hard to read. It's so cluttered  I can't keep my focus. Just increasing the space between lines makes all the  difference. When I'm really tired, I also increase the space between  words.&quot;</p>
  <p>Works well: &quot;OK, I know I'm a bit of a geek, but  I've perfected a user style sheet to make text spacing just right for me. It's  a relief when websites work with my CSS.&quot;</p>
</blockquote>
<a href="https://www.w3.org/WAI/WCAG21/Understanding/text-spacing.html">Understanding Text Spacing</a>

### 1.4.13 Content on Hover or Focus (AA)
<blockquote class="sc">
  <p>Where receiving and then removing pointer hover or keyboard focus triggers additional content to become visible and then hidden, the following are true:</p>
  <dl>
    <dt>Dismissable</dt>
    <dd>A <a href="https://www.w3.org/TR/WCAG21/#dfn-mechanism" data-link-type="dfn">mechanism</a> is available to dismiss the additional content without moving pointer hover or keyboard focus, unless the additional content communicates an <a href="https://www.w3.org/TR/WCAG21/#dfn-input-error" data-link-type="dfn">input error</a> or does not obscure or replace other content;</dd>
    <dt>Hoverable</dt>
    <dd>If pointer hover can trigger the additional content, then the pointer can be moved over the additional content without the additional content disappearing;</dd>
    <dt>Persistent</dt>
    <dd>The additional content remains visible until the hover or focus trigger is removed, the user dismisses it, or its information is no longer valid.</dd>
  </dl>
  <p>Exception: The visual presentation of the additional content is controlled by the user agent and is not modified by the author.</p>
</blockquote>
<p class="persona">Person with low vision who uses screen magnification software:</p>
<blockquote class="quotes">
  <p>Problem: &quot;I was moving my mouse around to  track what I was looking at on a web page. It helps me keep focused. Then  -boom- this little box popped up. It covered what I was trying to read and I  couldn't get it to go away.&quot;</p>
  <p>Works well: &quot;I hovered over a word and a box popped up with the definition, but it was mostly off the screen with my magnification. I moved my mouse pointer  to the definition box and scrolled the magnified area over to  the definition box and it stayed popped up so I could read it.&quot;</p>
</blockquote>
<p><a href="https://www.w3.org/WAI/WCAG21/Understanding/content-on-hover-or-focus.html">Understanding Content on Hover or Focus</a> </p>

## Guideline 2.1 Keyboard Accessible

Make all functionality available from a keyboard.

### 2.1.4 Character Key Shortcuts (A)
<blockquote class="sc">
  <p>If a <a href="https://www.w3.org/TR/WCAG21/#dfn-keyboard-shortcuts" data-link-type="dfn">keyboard shortcut</a> is implemented in content using only letter (including upper- and lower-case letters), punctuation, number, or symbol characters, then at least one of the following is true:</p>
  <dl>
    <dt>Turn off</dt>
    <dd>A <a href="https://www.w3.org/TR/WCAG21/#dfn-mechanism" data-link-type="dfn">mechanism</a> is available to turn the shortcut off;</dd>
    <dt>Remap</dt>
    <dd>A mechanism is available to remap the shortcut to use one or more non-printable keyboard characters (e.g. Ctrl, Alt, etc).</dd>
    <dt>Active only on focus</dt>
    <dd>The keyboard shortcut for a <a href="https://www.w3.org/TR/WCAG21/#dfn-user-interface-components" data-link-type="dfn">user interface component</a> is only active when that component has focus.</dd>
  </dl>
</blockquote>
<p class="persona"><a href="https://www.w3.org/WAI/people-use-web/user-stories/#reporter">Alex</a>, reporter with repetitive stress injury who uses voice recognition software:</p>
<blockquote class="quotes">
  <p>Problem: &quot;When I was using my mail app with  voice commands, it kept deleting the messages instead of opening them.&quot;</p>
<p class="qnote">Note: There was a shortcut key for delete that was  triggered by something he was saying, and no way to turn off the shortcut  keys.</p>
  <p>Works well: &quot;In my spreadsheet application,  there's a setting to turn off or modify character key shortcuts.&quot;</p>
</blockquote>
<p><a href="https://www.w3.org/WAI/WCAG21/Understanding/character-key-shortcuts.html">Understanding Character Key Shortcuts</a></p>

## Guideline 2.2 Enough Time

Provide users enough time to read and use content.

### 2.2.6 Timeouts (AAA)
<blockquote class="sc">
  <p>Users are warned of the duration of any <a href="https://www.w3.org/TR/WCAG21/#dfn-user-inactivity" data-link-type="dfn">user inactivity</a> that could cause data loss, unless the data is preserved for more than 20 hours when the user does not take any actions.</p>
</blockquote>
<p class="persona">Person with cognitive disabilities who takes frequent breaks when completing complex forms:</p>
<blockquote class="quotes">
  <p>Problem: &quot;I was selecting my Employee Benefits  and was comparing the different plans. When I went back to select the Health  Plan, it had timed out and lost all the information I had already entered.&quot;</p>
  <p>Works well: &quot;When I started the Employee  Benefits app, it told me how many minutes I had to complete the forms.&quot;</p>
</blockquote>
<a href="https://www.w3.org/WAI/WCAG21/Understanding/timeouts.html">Understanding Timeouts</a>

## Guideline 2.3 Seizures and Physical Reactions

Do not design content in a way that is known to cause seizures or physical reactions.

### 2.3.3 Animation from Interactions (AAA)
<blockquote class="sc">
  <p><a href="https://www.w3.org/TR/WCAG21/#dfn-motion-animation" data-link-type="dfn">Motion animation</a> triggered by interaction can be disabled, unless the animation is <a href="https://www.w3.org/TR/WCAG21/#dfn-essential" data-link-type="dfn">essential</a> to the functionality or the information being conveyed.</p>
</blockquote>
<p class="persona">Person with vestibular disorder:</p>
<blockquote class="quotes">
  <p>Problem: &quot;In the online tax app, as I move my  mouse around or tab to different fields, this little bubble with the current  balance follows me around the screen. Makes me dizzy and nauseous.&quot;</p>
  <p>Works well: &quot;I was so glad there was an option  to turn off animations.&quot;</p>
</blockquote>
<p><a href="https://www.w3.org/WAI/WCAG21/Understanding/animation-from-interactions.html">Understanding Animation from Interactions</a></p>


## Guideline 2.4 Navigable

Provide ways to help users navigate, find content, and determine where they are.

### 2.4.1 Motion Actuation (A)
<blockquote class="sc">
  <p><a href="https://www.w3.org/TR/WCAG21/#dfn-functionality" data-link-type="dfn">Functionality</a> that can be operated by device motion or user motion can also be operated by <a href="https://www.w3.org/TR/WCAG21/#dfn-user-interface-components" data-link-type="dfn">user interface components</a> and responding to the motion can be disabled to prevent accidental actuation, except when:</p>
  <dl>
    <dt>Supported Interface</dt>
    <dd>The motion is used to operate functionality through an <a href="https://www.w3.org/TR/WCAG21/#dfn-accessibility-supported" data-link-type="dfn">accessibility supported</a>interface;</dd>
    <dt>Essential</dt>
    <dd>The motion is <a href="https://www.w3.org/TR/WCAG21/#dfn-essential" data-link-type="dfn">essential</a> for the function and doing so would invalidate the activity.</dd>
  </dl>
</blockquote>
<p class="persona">Person with cerbal palsy who uses a wheelchair: </p>
<blockquote class="quotes">
  <p>Problem: &quot;I can't shake my phone; it's  connected to my wheelchair. So there needs to be another way to activate that  feature, like a button.&quot;</p>
  <p>Problem: &quot;I have tremors, so I need to turn  off motion activation &mdash; and then be able to do stuff without motion  actuation.&quot;</p>
  <p>Works well: &quot;My friend has this cool application that looks like a physical spin lock. She rotates the phone to turn to the combination. I can use the same application by typing the numbers directly.&quot;</p>
</blockquote>

## Guideline 2.5 Input Modalities

Make it easier for users to operate functionality through various inputs beyond keyboard.

### 2.5.1 Pointer Gestures (A)
<blockquote class="sc">
  <p>All <a href="https://www.w3.org/TR/WCAG21/#dfn-functionality" data-link-type="dfn">functionality</a> that uses multipoint or path-based gestures for operation can be operated with a <a href="https://www.w3.org/TR/WCAG21/#dfn-single-pointer" data-link-type="dfn">single pointer</a> without a path-based gesture, unless a multipoint or path-based gesture is <a href="https://www.w3.org/TR/WCAG21/#dfn-essential" data-link-type="dfn">essential</a>.</p>
</blockquote>
<p class="persona">Person with limited movement in fingers:</p>
<blockquote class="quotes">
  <p>Problem: &quot;I can't move my fingers like that. I  need another way to zoom in the map.&quot;</p>
  <p>Works well: &quot;Good thing there are buttons to  zoom in and out.&quot;</p>
</blockquote>
<p><a href="https://www.w3.org/WAI/WCAG21/Understanding/pointer-gestures.html">Understanding Pointer Gestures</a></p>

### 2.5.2 Pointer Cancellation (A)
<blockquote class="sc">
  <p>For <a href="https://www.w3.org/TR/WCAG21/#dfn-functionality" data-link-type="dfn">functionality</a> that can be operated using a <a href="https://www.w3.org/TR/WCAG21/#dfn-single-pointer" data-link-type="dfn">single pointer</a>, at least one of the following is true:</p>
  <dl>
    <dt>No Down-Event</dt>
    <dd>The <a href="https://www.w3.org/TR/WCAG21/#dfn-down-event" data-link-type="dfn">down-event</a> of the pointer is not used to execute any part of the function;</dd>
    <dt>Abort or Undo</dt>
    <dd>Completion of the function is on the <a href="https://www.w3.org/TR/WCAG21/#dfn-up-event" data-link-type="dfn">up-event</a>, and a <a href="https://www.w3.org/TR/WCAG21/#dfn-mechanism" data-link-type="dfn">mechanism</a> is available to abort the function before completion or to undo the function after completion;</dd>
    <dt>Up Reversal</dt>
    <dd>The up-event reverses any outcome of the preceding down-event;</dd>
    <dt>Essential</dt>
    <dd>Completing the function on the down-event is <a href="https://www.w3.org/TR/WCAG21/#dfn-essential" data-link-type="dfn">essential</a>.</dd>
  </dl>
</blockquote>
<p class="persona">Person with motor disabilties and low vision:</p>
<blockquote class="quotes">
  <p>Problem: &quot;I went to hit the &quot;Mute&quot; button and  accidentally touched the &quot;End Call&quot; button instead. It hung up immediately.&quot;</p>
  <p>Works well: &quot;In another web conferencing  application, if I accidentally touch the &quot;End Call&quot; button, I can just slide my  finger off the &quot;End Call&quot; button and it won't end the call.&quot;</p>
</blockquote>
<p><a href="https://www.w3.org/WAI/WCAG21/Understanding/pointer-cancellation.html">Understanding Pointer Cancellation</a></p>

### 2.5.3 Label in Name (A)
<blockquote class="sc">
  <p>For <a href="https://www.w3.org/TR/WCAG21/#dfn-user-interface-components" data-link-type="dfn">user interface components</a> with <a href="https://www.w3.org/TR/WCAG21/#dfn-labels" data-link-type="dfn">labels</a> that include <a href="https://www.w3.org/TR/WCAG21/#dfn-text" data-link-type="dfn">text</a> or <a href="https://www.w3.org/TR/WCAG21/#dfn-images-of-text" data-link-type="dfn">images of text</a>, the <a href="https://www.w3.org/TR/WCAG21/#dfn-name" data-link-type="dfn">name</a> contains the text that is presented visually.</p>
</blockquote>
<p><span class="persona"><a href="https://www.w3.org/WAI/people-use-web/user-stories/#reporter">Alex</a>, reporter with repetitive stress injury who uses voice recognition software:</span></p>
<blockquote class="quotes">
  <p>Problem: &quot;It understood most of my voice  commands until I got to the Send button. I kept saying 'Send' and it didn't  work.&quot;</p>
  <p class="qnote">Note: It was visually labelled 'send' but the 'name' in the  code was 'submit'. It would have worked if the 'name' started with 'send'.</p>
</blockquote>
<p><a href="https://www.w3.org/WAI/WCAG21/Understanding/label-in-name.html">Understanding Label in Name</a></p>

### 2.5.5 Target Size (AAA)
<blockquote class="sc">
  <p>The size of the <a href="https://www.w3.org/TR/WCAG21/#dfn-target" data-link-type="dfn">target</a> for <a href="https://www.w3.org/TR/WCAG21/#dfn-pointer-inputs" data-link-type="dfn">pointer inputs</a> is at least 44 by 44 <a href="https://www.w3.org/TR/WCAG21/#dfn-css-pixels" data-link-type="dfn">CSS pixels</a> except when:</p>
  <dl>
    <dt>Equivalent</dt>
    <dd>The target is available through an equivalent link or control on the same page that is at least 44 by 44 CSS pixels;</dd>
    <dt>Inline</dt>
    <dd>The target is in a sentence or block of text;</dd>
    <dt>User Agent Control</dt>
    <dd>The size of the target is determined by the user agent and is not modified by the author;</dd>
    <dt>Essential</dt>
    <dd>A particular presentation of the target is <a href="https://www.w3.org/TR/WCAG21/#dfn-essential" data-link-type="dfn">essential</a> to the information being conveyed.</dd>
  </dl>
</blockquote>
<p class="persona"><a href="https://www.w3.org/WAI/people-use-web/user-stories/#retiree">Yun</a>, retiree with hand tremor (and big fingers):</p>
<blockquote class="quotes">
  <p>Problem: &quot;The buttons are so small, I hit  &quot;Cancel&quot; when going for &quot;Submit&quot;. Then I have to start all over again.&quot;</p>
  <p>Works well: &quot;This website buttons are big enough  that I don't hit the wrong button even when I'm riding on the bumpy bus.&quot;</p>
</blockquote>
<p><a href="https://www.w3.org/WAI/WCAG21/Understanding/target-size.html">Understanding Target Size</a></p>

### 2.5.6 Concurrent Input  Mechanisms (AAA)
<blockquote class="sc">
  <p>Web content does not restrict use of input modalities available on a platform except where the restriction is <a href="https://www.w3.org/TR/WCAG21/#dfn-essential" data-link-type="dfn">essential</a>, required to ensure the security of the content, or required to respect user settings.</p>
</blockquote>
<p class="persona"><a href="https://www.w3.org/WAI/people-use-web/user-stories/#reporter">Alex</a>, reporter with repetitive stress injury (RSI):</p>
<blockquote class="quotes">
  <p>Problem: &quot;When my RSI acts up, I switch back and forth a lot between keyboard, mouse,  stylus, voice. This application doesn't let me use the stylus when I have a  keyboard plugged in.&quot;</p>
</blockquote>
<p><a href="https://www.w3.org/WAI/WCAG21/Understanding/concurrent-input-mechanisms.html">Understanding Concurrent Input Mechanisms</a></p>

## Guideline 4.1 Compatible

Maximize compatibility with current and future user agents, including assistive technologies.

### 4.1.3 Status Messages (AA)
<blockquote class="sc">
  <p>In content implemented using markup languages, <a href="https://www.w3.org/TR/WCAG21/#dfn-status-messages" data-link-type="dfn">status messages</a> can be <a href="https://www.w3.org/TR/WCAG21/#dfn-programmatically-determinable" data-link-type="dfn">programmatically determined</a> through <a href="https://www.w3.org/TR/WCAG21/#dfn-role" data-link-type="dfn">role</a> or properties such that they can be presented to the user by <a href="https://www.w3.org/TR/WCAG21/#dfn-assistive-technologies" data-link-type="dfn">assistive technologies</a> without receiving focus.</p>
</blockquote>
<p class="persona"><a href="https://www.w3.org/WAI/people-use-web/user-stories/#ilya-senior-staff-member-who-is-blind">Ilya</a>, who is blind and uses a screen reader:</p>
<blockquote class="quotes">
  <p>Problem: &quot;I selected a class for the conference, but I can't tell if it got added to my  schedule.&quot;</p>
  <p>Works well: &quot;When I add a meeting to my calendar,  I hear a confirmation.&quot;</p>
</blockquote>
<p><a href="https://www.w3.org/WAI/WCAG21/Understanding/status-messages.html">Understanding Status Messages</a></p>

## About the Personas Quotes
<p>The linked personas names go to the <a href="https://www.w3.org/WAI/people-use-web/user-stories/">Stories of Web Users</a>. For the quotes above, if we don't have a relevant user story, they don't include a name. We might update that in the future.</p>
<p>After we've reviewed these persona quotes sufficiently, we plan to add them to the Understanding documents.</p>

