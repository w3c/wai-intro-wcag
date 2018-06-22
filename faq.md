---
title: WCAG 2 FAQ
permalink: /standards-guidelines/wcag/faq/
layout: default
github:
  path: 'faq.md'
footer: >
    <p><strong>Date:</strong> Updated 22 June 2018. First published October 2006.</p>
    <p><strong>Editor:</strong> <a href="http://www.w3.org/People/Shawn/">Shawn Lawton Henry</a>.</p>
    <p>Developed with input from the Education and Outreach Working Group (<a href="https://www.w3.org/WAI/about/groups/eowg/">EOWG</a>) and the Accessibility Guidelines Working Group (<a href="https://www.w3.org/WAI/about/groups/agwg/">AG WG</a>).</p>

---

{::nomarkdown}
{% include box.html type="start" h="2" title="Summary" class="full" %}
{:/}

  <p>This page answers to some frequently asked questions (FAQ) about Web Content Accessibility Guidelines (WCAG). Let us know what <a href="#more">other questions</a> you have. <br/>
    ~<em><a href="http://w3.org/People/Shawn/">Shawn Henry</a></em>, <abbr title="World Wide Web Consortium">W3C</abbr> <abbr title="Web Accessibility Initiative">WAI</abbr>, <em>updated 22 June 2018</em></p>

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

{:toc}

{::nomarkdown}
{% include_cached toc.html type="end" %}
{:/}

  <h2 id="done">Is WCAG 2 stable?</h2>
  <p>Yes. WCAG standards (called &quot;W3C Recommendations&quot;) are a stable, referenceable standards that do not change. There may be later versions published.</p>
  <p><a href="http://www.w3.org/TR/WCAG20/">WCAG 2.0</a> was published as a final W3C Recommendation Web Standard on 11 December 2008. <a href="http://www.w3.org/TR/WCAG21/">WCAG 2.1</a> was published as a final W3C Recommendation Web Standard on 5 June 2018. <strong>They will not change.</strong></p>
  <p>The supporting resources &mdash; Techniques for WCAG 2 and Understanding WCAG 2 &mdash; are updated periodically to reflect updates in technologies and best practices.</p>
  <p><em>See also important information in the next answer about WCAG 2.1:</em></p>
  <h2 id="v21">What about WCAG 2.1?</h2>

All requirements ("success criteria") from 2.0 are included in 2.1. The 2.0 success criteria are exactly the same (verbatim, word-for-word) in 2.1.

The primary focus for WCAG 2.1 is additional accessibility requirements for:
* [mobile accessibility](https://www.w3.org/WAI/standards-guidelines/mobile/#intro)
* people with low vision,
* people with cognitive and learning disabilities

There are 17 additional success criteria in 2.1 that are not in 2.0. They are introduced in [What's New in WCAG 2.1](https://www.w3.org/WAI/standards-guidelines/wcag/new-in-21/).

**Content that conforms to WCAG 2.1 also conforms to WCAG 2.0**. (This is often called “backwards compatible”.) A website that meets WCAG 2.1 should meet the requirements of policies that reference WCAG 2.0.

To put it another way: If you want to meet both WCAG 2.0 and WCAG 2.1, you can use the 2.1 resources and you don't need to bother looking at 2.0.

WCAG 2.0 and WCAG 2.1 are both existing standards. WCAG 2.1 does not deprecate or supersede WCAG 2.0. W3C encourages you to use the most recent version of WCAG when developing or updating content or accessibility policies.

<h2 id="next">What's next after WCAG 2.1?</h2>
  <p>The Accessibility Guidelines Working Group is also exploring future accessibility guidelines through the <a href="https://www.w3.org/WAI/GL/task-forces/silver/">Silver Task Force</a>. Additional information is available in a <a href="https://docs.google.com/presentation/d/1YjaxD3qNAUV0dcx485AyEpq5RY_WpXgFk27TozDbPM8/edit#slide=id.p">Silver presentation</a>. This project will take several years.</p>
  <p>In the interim, the Working Group might decide to develop WCAG 2.2 to provide additional updates to address current accessibility requirements.</p>
  <h2><a id="mobile"></a>Does WCAG 2 address mobile accessibility?</h2>
  <p><strong>Yes.</strong> See the <a href="https://www.w3.org/WAI/standards-guidelines/mobile/">Mobile Accessibility at W3C</a> page.</p>
  
    <h2 id="vpat21">Does VPAT 2.1 include WCAG 2.1?</h2>
<p>No. Voluntary Product Accessibility Template (VPAT) 2.1 includes information from WCAG 2.0. VPAT 2.1 does not include information from WCAG 2.1. (VPAT is not developed by W3C.)</p>
  
  <h2 id="start">Where should I start?</h2>
  <p class="listintro">If you want a really short introduction to 3 web accessibility issues (alternative text for images, keyboard input, and transcripts), see <a href="https://www.w3.org/WAI/fundamentals/accessibility-intro/#examples">Examples of Web Accessibility</a>.</p>
  <p class="listintro">To learn about web accessibility principles and guidelines, see <a href="https://www.w3.org/WAI/fundamentals/accessibility-principles/">Accessibility Principles</a>.</p>
  <p><strong>To learn about WCAG 2 specifically, start with the <a href="https://www.w3.org/WAI/standards-guidelines/wcag/">WCAG Overview</a>.</strong> It provides an important foundation for understanding the different WCAG 2 documents, and points to several resources for using WCAG 2.</p>
  <p><a href="http://www.w3.org/WAI/WCAG20/quickref/">How to Meet WCAG 2: A customizable quick reference</a> is the primary resource for developers using WCAG 2.</p>
  <h2 id="docs">What are the different WCAG 2 documents?</h2>
  <p>To learn how the different WCAG 2 technical documents are related and linked, see <a href="http://www.w3.org/WAI/intro/wcag20">The WCAG 2 Documents</a>.</p>
  <p>Here's a little more perspective on the different technical documents. When web content and web software developers were using WCAG <em><strong>1.0</strong></em>, they had many questions on how to implement it, how to evaluate for it, and the reasons behind its requirements. WAI wanted to provide this information with WCAG 2, and since those details don't fit well in a technical standard, they are in the supporting documents.</p>
  <p>Thus with WCAG 2, there are extensive supporting materials, which are advisory documents. The WCAG 2 guidelines document  itself is the only document that is a web standard, and it is fairly short.</p>
  <h2 id="techs">Do content authors (developers, designers, etc.) have to follow W3C's techniques to meet WCAG?</h2>
  <p><strong>No</strong>, you do not have to use the techniques in W3C's <cite>Techniques for WCAG 2</cite> document.</p>
  <p>The techniques are informative; that means they are not required. The basis for determining conformance to WCAG 2 is the success criteria from the WCAG 2 standard — not the techniques.</p>
  <p>While many authors find W3C-documented techniques useful, there may be other ways to meet WCAG success criteria. You can use other techniques. Web content could even fail a particular technique test, yet still meet WCAG in a different way. Also, content that uses some of the  Techniques does not necessarily meet all WCAG success criteria.</p>
  <p><strong>For important additional information, see the <a href="http://www.w3.org/TR/UNDERSTANDING-WCAG20/understanding-techniques.html">Understanding Techniques for WCAG Success Criteria section</a> of Understanding WCAG 2.1</strong>.</p>
  <h2 id="techsnot">What would be the negative consequences of allowing <em>only</em> W3C's published techniques to be used for conformance to WCAG 2?</h2>
  <p>Background:  Some organizations have considered requiring all web content to use  W3C's published techniques.</p>
  <p><strong>W3C recommends that the only thing that is required is meeting the WCAG 2 success criteria. </strong>The basis for determining conformance to WCAG 2 is the success criteria from the WCAG 2 standard — not the techniques. <span class="prefix">W3C's <cite>Techniques for WCAG 2</cite> document is informative (that is, not required, non-normative).</span></p>
  <p><strong>W3C cautions against requiring  web content to use only W3C's published sufficient techniques and not allowing other techniques</strong> for several reasons, including:</p>
  <ul class="listspaced">
    <li><strong>It would prevent the use of  new technologies (for example, HTML5 and WAI-ARIA) while the technologies and relevant sufficient techniques are being developed, which is usually more than a year.<br>
      </strong> It often takes several years for technologies to be developed and finalized. Once a technology is stable, it usually takes several months for the WCAG Working Group to  develop techniques, test them with user agents and assistive technologies, make them available for public review, revise them as needed, and formally publish them.</li>
    <li>W3C's <em><cite>Techniques for WCAG 2</cite></em> is not comprehensive and may not cover newer technologies and situations.  There may be techniques that are sufficient to meet a given success criteria, but that are not yet included in W3C's published document.</li>
    <li>W3C's published sufficient techniques may not always be the best techniques in a specific circumstance.</li>
    <li>It is not always possible to use the W3C's published sufficient techniques — for example, because of the way the content is designed — and there are other ways to meet the success criteria.</li>
    <li>It would prevent the use of new techniques and best practices until W3C published them.</li>
  </ul>
  <p><strong>Therefore, W3C's published techniques should not be required as the only way to meet WCAG 2 success criteria  unless the  limitations and consequences above are understood and acceptable.</strong></p>
  <p>For additional information, see: <a href="http://www.w3.org/TR/UNDERSTANDING-WCAG20/understanding-techniques.html">Understanding Techniques for WCAG Success Criteria</a> section of Understanding WCAG 2.1.</p>
  <h2 id="iso">Is ISO/IEC 40500 the same as WCAG 2.0?</h2>
  <p><strong>Yes.</strong> WCAG 2.0 is  approved as an ISO standard: ISO/IEC 40500:2012. ISO/IEC 40500 is exactly the same as the original Web Content Accessibility Guidelines (WCAG) 2.0 from the <a href="http://www.w3.org/">W3C</a> Web Accessibility Initiative (<a href="http://www.w3.org/WAI/">WAI</a>).</p>
  <p>The content of ISO/IEC 40500 is freely available from <a href="http://www.w3.org/TR/WCAG20/">www.w3.org/TR/WCAG20</a>;  it is available for purchase from the <a href="http://www.iso.org/iso/iso_catalogue/catalogue_tc/catalogue_detail.htm?csnumber=58625">ISO catalogue</a>.</p>
  <p><strong>For supporting resources that provide practical advice for meeting ISO/IEC 40500 (which is WCAG 2.0), see the <a href="http://www.w3.org/WAI/intro/wcag">WCAG Overview</a>.</strong></p>
  <p>The approval was announced 15 October 2012 in a <a href="http://www.w3.org/2012/07/wcag2pas-pr.html">press release</a> and <a href="http://www.w3.org/QA/2012/10/wcag_20_is_now_also_isoiec_405.html">blog post</a>.
    If you want more information on W3C and the ISO process, see <a href="http://www.w3.org/2010/04/pasfaq">W3C PAS FAQ</a>.</p>
  <h3>Benefits of WCAG as ISO</h3>
  <p>Approval of WCAG 2.0 as an ISO standard benefits countries and organizations that can more easily  adopt ISO standards. Countries that previously adapted WCAG 2.0 may now be able to <em>adopt WCAG 2.0 as is</em> by referencing  ISO/IEC 40500.</p>
  <h3 id="isotranslations">Translations</h3>
  <p>W3C has offered our <a href="http://www.w3.org/WAI/WCAG20/translations.html">WCAG 2.0 Authorized Translations</a> to be used for the ISO/IEC translations. We will update this page when more information about translations is available.</p>
  <h2 id="languages">Is WCAG 2 available in other languages?</h2>
  <p><strong>Yes.</strong> Authorized Translations and unofficial translations of the technical documents WCAG 2, Techniques for WCAG 2, and Understanding WCAG 2 are listed in <a href="http://www.w3.org/WAI/WCAG20/translations.html">WCAG 2 Translations</a>.</p>
  <p>Unofficial translations of other WAI documents are listed at <a href="http://www.w3.org/2005/11/Translations/Query?lang=any&amp;translator=any&amp;date=any&amp;docSelection=choose&amp;rec=none&amp;note=none&amp;xg=none&amp;tut=none&amp;wai=any&amp;i18n=none&amp;qa=none&amp;misc=none&amp;sorting=byLanguage&amp;output=FullHTML&amp;submit=Submit">Translations of W3C Documents - WAI documents - listed by languages</a> and <a href="http://www.w3.org/2005/11/Translations/Query?lang=any&amp;translator=any&amp;date=any&amp;docSelection=choose&amp;rec=none&amp;note=none&amp;xg=none&amp;tut=none&amp;wai=any&amp;i18n=none&amp;qa=none&amp;misc=none&amp;sorting=byTechnology&amp;output=FullHTML&amp;submit=Submit">Translations of W3C Documents - WAI documents - listed by document</a>.</p>
  <p>For  more information on how you can contribute to WAI translations, see <a href="http://www.w3.org/WAI/translation">Translating WAI Documents.</a></p>
  <h2 id="othertechs">Can I meet WCAG 2 with Javascript/Ajax, Silverlight, and other technologies?</h2>
  <p>WCAG 2 is designed to apply to a broad range of web technologies.</p>
  <p><a href="http://www.w3.org/TR/WCAG20-TECHS/">Techniques for WCAG 2</a> has  techniques for several different web technologies. <em>Note that publication of techniques for a specific technology does not imply that the technology can be used in all cases to create accessible content that meets WCAG 2.</em> Developers need to be aware of the limitations of specific technologies and ensure that they create content in a way that is accessible to all their potential users. 
  </p>
  <p>WAI is also developing guidance on <a href="http://www.w3.org/TR/wcag2ict/">Applying WCAG 2 to Non-Web Information and Communications Technologies (WCAG2ICT)</a>.</p>
  <h2 id="more">Where can I find answers to more of my questions?</h2>
  <p>First, look through the documents on the W3C WAI website.</p>
  <p class="listintro">WAI hosts an Interest Group (WAI IG) mailing list where the community discusses web accessibility issues.   WAI IG  provides ideas from different perspectives. If you have a question that might be relevant to the WAI IG list, you can:</p>
  <ul class="listafterpul">
    <li>Search the <a href="http://lists.w3.org/Archives/Public/w3c-wai-ig/">WAI IG list archives</a> to see if your question has already been
      addressed sufficiently.</li>
    <li>Join the
      self-subscription list and post an appropriate question. Please read the <a href="https://www.w3.org/WAI/IG/Overview.html#Uselist">Using the WAI IG mailing list</a> section of the WAI IG page.</li>
  </ul>
  <p>WAI staff are actively developing guidelines, technical reports, and supporting material, and generally are not available to answer individual questions. However, you can send questions to <a href="mailto:wai@w3.org">wai@w3.org</a> and we will integrate answers into this page and other documents as we are able.</p>
