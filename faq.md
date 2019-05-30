---
# Translation info https://www.w3.org/wiki/WAI/Website/Translate

title: "WCAG 2 FAQ"
nav_title: "FAQ"

description: Answers to some frequently asked questions (FAQ) about Web Content Accessibility Guidelines (WCAG).

lang: en
last_updated: 2018-06-22
permalink: /standards-guidelines/wcag/faq/

github:
  repository: w3c/wai-intro-wcag
  path: 'faq.md'

image: /content-images/wai-intro-wcag/general-social.jpg
footer: >
    <p><strong>Date:</strong> Updated 22 June 2018. First published October 2006.</p>
    <p><strong>Editor:</strong> <a href="http://www.w3.org/People/Shawn/">Shawn Lawton Henry</a>.</p>
    <p>Developed with input from the Education and Outreach Working Group (<a href="https://www.w3.org/WAI/about/groups/eowg/">EOWG</a>) and the Accessibility Guidelines Working Group (<a href="https://www.w3.org/WAI/about/groups/agwg/">AG WG</a>).</p>
permalink: /standards-guidelines/wcag/faq/
---

{::nomarkdown}
{% include box.html type="start" h="2" title="Summary" class="full" %}
{:/}

This page answers to some frequently asked questions (FAQ) about Web Content Accessibility Guidelines (WCAG). Let us know what <a href="#more">other questions</a> you have.<br>
~<em><a href="http://w3.org/People/Shawn/">Shawn Henry</a></em>, <abbr title="World Wide Web Consortium">W3C</abbr> <abbr title="Web Accessibility Initiative">WAI</abbr>, <em>updated 22 June 2018</em>

{::nomarkdown}
{% include box.html type="end" %}
{:/}

{::nomarkdown}
{% include_cached toc.html type="start" title="Page Contents" class="simple" %}
{:/}

{::options toc_levels="2" /}

  <ul class="questions">
    <li><a href="#done">Is WCAG 2 stable?</a></li>
    <li><a href="#v21">What about WCAG 2.1?</a></li>
    <li><a href="#next">What's next after WCAG 2.1?</a></li>
    <li><a href="#vpat21">Does VPAT 2.1 include WCAG 2.1?</a></li> 
    <li><a href="#mobile">Does WCAG address mobile accessibility?</a></li>
    <li><a href="#start">Where should I start?</a></li>
    <li><a href="#docs">What are the different WCAG 2 documents?</a></li>
    <li><a href="#techs">Do content authors (developers, designers, etc.) have to follow W3C's techniques to meet WCAG?</a></li>
    <li><a href="#techsnot">What would be the negative consequences of allowing <em>only</em> W3C's published techniques to be used for conformance to WCAG 2?</a></li>
    <li><a href="#iso">Is ISO/IEC 40500 the same as WCAG 2.0?</a></li>
    <li><a href="#languages">Is WCAG 2 available in other languages?</a></li>
    <li><a href="#othertechs">Can I meet WCAG 2 with Javascript/Ajax, Silverlight, and other technologies?</a></li>
    <li><a href="#more">Where can I find answers to more of my questions?</a></li>
  </ul>

-   This text will be replaced by the TOC.
{:toc}

{::nomarkdown}
{% include_cached toc.html type="end" %}
{:/}

## Is WCAG 2 stable? {#done}

Yes. WCAG standards (called "W3C Recommendations") are a stable, referenceable standards that do not change. There may be later versions published.

[WCAG 2.0](http://www.w3.org/TR/WCAG20/) was published as a final W3C Recommendation Web Standard on 11 December 2008. [WCAG 2.1](http://www.w3.org/TR/WCAG21/) was published as a final W3C Recommendation Web Standard on 5 June 2018. **They will not change.**

The supporting resources — Techniques for WCAG 2 and Understanding WCAG 2 — are updated periodically to reflect updates in technologies and best practices.

*See also important information in the next answer about WCAG 2.1:*

## What about WCAG 2.1? {#v21}

All requirements ("success criteria") from 2.0 are included in 2.1. The 2.0 success criteria are exactly the same (verbatim, word-for-word) in 2.1.

The primary focus for WCAG 2.1 is additional accessibility requirements for:
* [mobile accessibility](/standards-guidelines/mobile/)
* people with low vision,
* [people with cognitive and learning disabilities](/cognitive/)

There are 17 additional success criteria in 2.1 that are not in 2.0. They are introduced in [[What's New in WCAG 2.1]](/standards-guidelines/wcag/new-in-21/).

**Content that conforms to WCAG 2.1 also conforms to WCAG 2.0**. (This is often called “backwards compatible”.) A website that meets WCAG 2.1 should meet the requirements of policies that reference WCAG 2.0.

To put it another way: If you want to meet both WCAG 2.0 and WCAG 2.1, you can use the 2.1 resources and you don't need to bother looking at 2.0.

WCAG 2.0 and WCAG 2.1 are both existing standards. WCAG 2.1 does not deprecate or supersede WCAG 2.0. W3C encourages you to use the most recent version of WCAG when developing or updating content or accessibility policies.

## What's next after WCAG 2.1? {#next}

The Accessibility Guidelines Working Group is also exploring future accessibility guidelines through the [Silver Task Force](https://www.w3.org/WAI/GL/task-forces/silver/). Additional information is available in a [Silver presentation {% include_cached external.html %}](https://docs.google.com/presentation/d/1YjaxD3qNAUV0dcx485AyEpq5RY_WpXgFk27TozDbPM8/edit#slide=id.p). This project will take several years.

In the interim, the Working Group might decide to develop WCAG 2.2 to provide additional updates to address current accessibility requirements.


## Does WCAG 2 address mobile accessibility? {#mobile}

**Yes.** See the [[Mobile Accessibility at W3C]](/standards-guidelines/mobile/) page.

## Does VPAT 2.1 include WCAG 2.1? {#vpat21}

No. Voluntary Product Accessibility Template (VPAT) 2.1 includes information from WCAG 2.0. VPAT 2.1 does not include information from WCAG 2.1. (VPAT is not developed by W3C.)

  
## Where should I start? {#start}

If you want a really short introduction to 3 web accessibility issues (alternative text for images, keyboard input, and transcripts), see [Examples of Web Accessibility](/fundamentals/accessibility-intro/#examples).

To learn about web accessibility principles and guidelines, see [[Accessibility Principles]](/fundamentals/accessibility-principles/).

**To learn about WCAG 2 specifically, start with the [WCAG Overview](/standards-guidelines/wcag/).** It provides an important foundation for understanding the different WCAG 2 documents, and points to several resources for using WCAG 2.

[How to Meet WCAG 2: A customizable quick reference](http://www.w3.org/WAI/WCAG21/quickref/) is the primary resource for developers using WCAG 2.

## What are the different WCAG 2 documents? {#docs}

To learn how the different WCAG 2 technical documents are related and linked, see [[The WCAG 2 Documents]](/standards-guidelines/wcag/docs/).

Here’s a little more perspective on the different technical documents. When web content and web software developers were using WCAG ***1.0***, they had many questions on how to implement it, how to evaluate for it, and the reasons behind its requirements. WAI wanted to provide this information with WCAG 2, and since those details don’t fit well in a technical standard, they are in the supporting documents.

Thus with WCAG 2, there are extensive supporting materials, which are advisory documents. The WCAG 2 guidelines document itself is the only document that is a web standard, and it is fairly short.

## Do content authors (developers, designers, etc.) have to follow W3C’s techniques to meet WCAG? {#techs}

**No**, you do not have to use the techniques in W3C’s Techniques for WCAG 2 document.

The techniques are informative; that means they are not required. The basis for determining conformance to WCAG 2 is the success criteria from the WCAG 2 standard — not the techniques.

While many authors find W3C-documented techniques useful, there may be other ways to meet WCAG success criteria. You can use other techniques. Web content could even fail a particular technique test, yet still meet WCAG in a different way. Also, content that uses some of the Techniques does not necessarily meet all WCAG success criteria.

**For important additional information, see the [Understanding Techniques for WCAG Success Criteria section](https://www.w3.org/WAI/WCAG21/Understanding/understanding-techniques) of Understanding WCAG 2.1**.


## What would be the negative consequences of allowing *only* W3C’s published techniques to be used for conformance to WCAG 2? {#techsnot}

Background: Some organizations have considered requiring all web content to use W3C’s published techniques.

**W3C recommends that the only thing that is required is meeting the WCAG 2 success criteria.** The basis for determining conformance to WCAG 2 is the success criteria from the WCAG 2 standard --- not the techniques. W3C’s _Techniques for WCAG 2_ document is informative (that is, not required, non-normative).

**W3C cautions against requiring web content to use only W3C’s published sufficient techniques and not allowing other techniques** for several reasons, including:

-   **It would prevent the use of new technologies (for example, HTML5 and WAI-ARIA) while the technologies and relevant sufficient techniques are being developed, which is usually more than a year.** 

    It often takes several years for technologies to be developed and finalized. Once a technology is stable, it usually takes several months for the WCAG Working Group to develop techniques, test them with user agents and assistive technologies, make them available for public review, revise them as needed, and formally publish them.

-   W3C’s *Techniques for WCAG 2* is not comprehensive and may not cover newer technologies and situations. There may be techniques that are sufficient to meet a given success criteria, but that are not yet included in W3C’s published document.

-   W3C’s published sufficient techniques may not always be the best techniques in a specific circumstance.

-   It is not always possible to use the W3C’s published sufficient techniques — for example, because of the way the content is designed — and there are other ways to meet the success criteria.

-   It would prevent the use of new techniques and best practices until W3C published them.

**Therefore, W3C’s published techniques should not be required as the only way to meet WCAG 2 success criteria unless the limitations and consequences above are understood and acceptable.**

For additional information, see: [Understanding Techniques for WCAG Success Criteria](https://www.w3.org/WAI/WCAG21/Understanding/understanding-techniques) section of Understanding WCAG 2.1.


## Is ISO/IEC 40500 the same as WCAG 2.0? {#iso}

**Yes.** WCAG 2.0 is approved as an ISO standard: ISO/IEC 40500:2012. ISO/IEC 40500 is exactly the same as the original Web Content Accessibility Guidelines (WCAG) 2.0 from the [W3C](http://www.w3.org/) Web Accessibility Initiative ([WAI](http://www.w3.org/WAI/)).

The content of ISO/IEC 40500 is freely available from [www.w3.org/TR/WCAG20](http://www.w3.org/TR/WCAG20/); it is available for purchase from the [ISO catalogue {% include_cached external.html %}](http://www.iso.org/iso/iso_catalogue/catalogue_tc/catalogue_detail.htm?csnumber=58625).

**For supporting resources that provide practical advice for meeting ISO/IEC 40500 (which is WCAG 2.0), see the [WCAG Overview](/standards-guidelines/wcag/).**

The approval was announced 15 October 2012 in a [press release](http://www.w3.org/2012/07/wcag2pas-pr.html) and [blog post](http://www.w3.org/QA/2012/10/wcag_20_is_now_also_isoiec_405.html). If you want more information on W3C and the ISO process, see [W3C PAS FAQ](http://www.w3.org/2010/04/pasfaq).


### Benefits of WCAG as ISO

Approval of WCAG 2.0 as an ISO standard benefits countries and organizations that can more easily adopt ISO standards. Countries that previously adapted WCAG 2.0 may now be able to *adopt WCAG 2.0 as is* by referencing ISO/IEC 40500. 

### Translations {#isotranslations}

W3C has offered our [WCAG 2.0 Authorized Translations](/standards-guidelines/wcag/translations/) to be used for the ISO/IEC translations. We will update this page when more information about translations is available. 

## Is WCAG 2 available in other languages? {#languages}

**Yes.** Authorized Translations and unofficial translations of the technical documents WCAG 2, Techniques for WCAG 2, and Understanding WCAG 2 are listed in [[WCAG 2 Translations]](/standards-guidelines/wcag/translations/).

Unofficial translations of other WAI documents are listed at [Translations of W3C Documents - WAI documents - listed by languages](http://www.w3.org/2005/11/Translations/Query?lang=any&translator=any&date=any&docSelection=choose&rec=none&note=none&xg=none&tut=none&wai=any&i18n=none&qa=none&misc=none&sorting=byLanguage&output=FullHTML&submit=Submit) and [Translations of W3C Documents - WAI documents - listed by document](http://www.w3.org/2005/11/Translations/Query?lang=any&translator=any&date=any&docSelection=choose&rec=none&note=none&xg=none&tut=none&wai=any&i18n=none&qa=none&misc=none&sorting=byTechnology&output=FullHTML&submit=Submit).

For more information on how you can contribute to WAI translations, see [[Translating WAI Documents]](/about/translating/).


## Can I meet WCAG 2 with Javascript/Ajax, Silverlight, and other technologies? {#othertechs}

WCAG 2 is designed to apply to a broad range of web technologies.

[Techniques for WCAG 2](https://www.w3.org/WAI/WCAG21/Techniques/) has techniques for several different web technologies. *Note that publication of techniques for a specific technology does not imply that the technology can be used in all cases to create accessible content that meets WCAG 2.* Developers need to be aware of the limitations of specific technologies and ensure that they create content in a way that is accessible to all their potential users.

WAI is also developing guidance on [Applying WCAG 2 to Non-Web Information and Communications Technologies (WCAG2ICT)](http://www.w3.org/TR/wcag2ict/).


## Where can I find answers to more of my questions? {#more}

First, look through the documents on the W3C WAI website.

WAI hosts an Interest Group (WAI IG) mailing list where the community discusses web accessibility issues. WAI IG provides ideas from different perspectives. If you have a question that might be relevant to the WAI IG list, you can:

-   Search the [WAI IG list archives](http://lists.w3.org/Archives/Public/w3c-wai-ig/) to see if your question has already been addressed sufficiently.
-   Join the self-subscription list and post an appropriate question. Please read the [Using the WAI IG mailing list](/about/groups/waiig/#mailinglist) section of the WAI IG page.

WAI staff are actively developing guidelines, technical reports, and supporting material, and generally are not available to answer individual questions. However, you can send questions to <wai@w3.org> and we will integrate answers into this page and other documents as we are able. 