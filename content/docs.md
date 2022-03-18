---
# Translation instructions are after the "#" character in this first section. They are comments that do not show up in the web page. You do not need to translate the instructions after #.
# In this first section, do not translate the words before a colon. For example, do not translate "title:". Do translate the text after "title:".

title: "The WCAG 2 Documents"
nav_title: "The Documents"

lang: en   # Change "en" to the translated-language shortcode from https://www.iana.org/assignments/language-subtag-registry/language-subtag-registry
last_updated: 2022-03-17  # Put the date of this translation YYYY-MM-DD (with month in the middle)

# translators:    # remove from the beginning of this line and the lines below: "# " (the hash sign and the space)
# - name: "Jan Doe"   # Replace Jan Doe with translator name
# - name: "Jan Doe"   # Replace Jan Doe with name, or delete this line if not multiple translators
# contributors:
# - name: "Jan Doe"   # Replace Jan Doe with contributor name, or delete this line if none
# - name: "Jan Doe"   # Replace Jan Doe with name, or delete this line if not multiple contributors

github:
  repository: w3c/wai-intro-wcag
  path: content/docs.md    # Add the language shortcode to the middle of the filename, for example: content/docs.fr.md
permalink: /standards-guidelines/wcag/docs/   # Add the language shortcode to the end, with no slash at end, for example: /standards-guidelines/wcag/docs/fr

ref: /standards-guidelines/wcag/docs/   # Translators, do not change this

image: /content-images/wai-intro-wcag/general-social.jpg
description:  Describes Web Content Accessibility Guidelines (WCAG) 2 supporting documents and supplemental guidance.

# In the footer below:
# Do not translate or change CHANGELOG or ACKNOWLEDGEMENTS.
# Translate the other words below, including "Date:" and "Editor:"
# Translate the Working Group name. Leave the Working Group acronym in English.
# Do not change the dates in the footer below.
footer: >
   <p><strong>Date:</strong> Updated 17 March 2022. First published July 2005.</p>
   <p><strong>Editor:</strong> <a href="http://www.w3.org/People/Shawn/">Shawn Lawton Henry</a>. Contributors: <a href="http://www.w3.org/People/hidde/">Hidde de Vries</a> and <a href="http://www.w3.org/People/shadi/">Shadi Abou-Zahra</a>.</p>
   <p>Developed with input from the Education and Outreach Working Group (<a href="https://www.w3.org/WAI/about/groups/eowg/">EOWG</a>).</p>


---

{::nomarkdown}
{% include box.html type="start" h="2" title="Summary" class="full" %}
{:/}

This page describes WCAG 2 supporting documents and supplemental guidance. It helps you know where to go for which type of information.

{::nomarkdown}
{% include box.html type="end" %}
{:/}

{::nomarkdown}
{% include_cached toc.html type="start" title="Page Contents" class="simple" %}
{:/}

{::options toc_levels="2,3,4" /}

-   This text will be replaced by the TOC.
{:toc}


{::nomarkdown}
{% include_cached toc.html type="end" %}
{:/}

## WCAG 2 Standard

Web Content Accessibility Guidelines (WCAG) 2 is a stable, referenceable technical standard. Learn more from the [[Web Content Accessibility Guidelines (WCAG) Overview]](/standards-guidelines/wcag/).

When developing web content and web tools, most people will use the documents introduced below, instead of the actual standard document.

## Quick Reference / How to Meet WCAG 2 / WCAG 2 Checklist

**A key resource for designers and developers using WCAG 2 is [How to Meet WCAG 2 (Quick Reference): A customizable quick reference to WCAG 2 requirements (Success Criteria) and techniques](http://www.w3.org/WAI/WCAG21/quickref/).** It includes all the WCAG 2 guidelines and success criteria. It is essentially the [WCAG 2 checklist](http://www.w3.org/WAI/WCAG21/quickref/).

You can customize it so it shows what you are interested in at the time. There are "filters" for different roles, topics, and technologies (such as HTML, CSS, ARIA). And filers for [Level A, AA, or AAA success criteria](https://www.w3.org/WAI/WCAG21/Understanding/conformance#levels).

## Supporting Documents

The supporting documents directly relate to WCAG guidelines and success criteria. They are **not required** to meet WCAG; they are "informative" or "non-normative".

### Understanding

<cite>Understanding WCAG</cite> is a guide to understanding and implementing WCAG. It has details for people who want to understand the guidelines and success criteria more thoroughly. It includes:

*  the intent
*  how it helps people with different disabilities
*  browser and assistive technology support notes
*  examples
*  resources, such as [tools to check contrast between colors](https://www.w3.org/WAI/WCAG21/Understanding/contrast-minimum.html#resources)

More:
* [About Understanding Documents](https://www.w3.org/WAI/WCAG21/Understanding/intro)
* [2.1 Understanding Document List](https://www.w3.org/WAI/WCAG21/Understanding/)
* [2.0 Understanding Document List](https://www.w3.org/TR/UNDERSTANDING-WCAG20/)

### Techniques

<cite>Techniques for WCAG</cite> give specific guidance **for developers** on how to develop accessible web content. It provides general and technology-specific examples, including for HTML, CSS, scripting, multimedia, and [WAI-ARIA](/standards-guidelines/aria/). 

* **Sufficient techniques** are examples of ways to meet success criteria. If you follow the sufficient techniques for the success criteria, then you meet the criteria.
* **Advisory techniques** are suggested ways to improve accessibility. They are very helpful to some users, and may be the only way that some users can access some types of content.
* **Failures** are things that cause accessibility barriers and fail specific success criteria.

More:
* [About Techniques](https://www.w3.org/WAI/WCAG21/Understanding/understanding-techniques)
* [2.1 Techniques List](https://www.w3.org/WAI/WCAG21/Techniques/)
* [2.0 Techniques List](https://www.w3.org/TR/WCAG20-TECHS/)

### Test Rules

Test Rules describe how to test conformance to WCAG success criteria. They are primarily for developing evaluation tools and test methodologies. (They are more robust than the tests in the techniques.)

* [About WCAG 2 Test Rules](/standards-guidelines/act/rules/about/)
* [All WCAG 2 Test Rules List](/standards-guidelines/act/rules/)

## Supplemental Guidance {#supplement}

Supplemental guidance goes beyond the requirements of WCAG. It is **not required** to meet WCAG. Much of the guidance is essential for people with certain impairments, including cognitive and learning disabilities and low vision.

* About Supplemental Guidance - *coming March 2022*
* All Supplemental Guidance list - *coming March 2022*

## Additional Resources

Before you start working with WCAG, you probably want to read these resources:
* [[Introduction to Web Accessibility]](/fundamentals/accessibility-intro/)
* [[Accessibility Principles]](/fundamentals/accessibility-principles/)
* [[Web Content Accessibility Guidelines (WCAG) Overview]](/standards-guidelines/wcag/)

Other resources cover specific topics, for example: 
* [Web Accessibility Tutorials](https://www.w3.org/WAI/tutorials/) cover page structure, menus, images, tables, carousels, forms
* [[Making Audio and Video Media Accessible]](/media/av/) covers multimedia

We encourage you to look around the W3C WAI website to find other information that you might be interested in reading or sharing with others.
