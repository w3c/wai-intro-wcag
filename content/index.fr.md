---
# Translation info https://www.w3.org/wiki/WAI/Website/Translate

title: "Vue d'ensemble des Règles pour l'accessibilité des contenus Web,  (WCAG)"
nav_title: "Web Content – WCAG"

description: Présente le standard international des Règles pour l'accessibilité des contenus web, (WCAG), y compris 2.0 et WCAG 2.1. Les documents des WCAG expliquent comment rendre les contenus web plus accessibles aux personnes handicapées.

lang: fr
last_updated: 2020-10-06
permalink: /standards-guidelines/wcag/fr/
translators: 
- name: "Sylvie Duchateau"

github:
  repository: w3c/wai-intro-wcag
  path: 'content/index.fr.md'

footer: >
  <p><strong>Date :</strong> Mis à jour le 22 juin 2018. Première publication en juillet 2005.</p>
  <p><strong>Auteure :</strong> <a href="http://www.w3.org/People/Shawn/">Shawn Lawton Henry</a>.</p>
  <p>Développé avec la contribution du Groupe de travail Éducation et Promotion (<a href="https://www.w3.org/WAI/about/groups/eowg/">EOWG</a>) et le Groupe de travail en charge des règles d'accessibilité (<a href="https://www.w3.org/WAI/about/groups/agwg/">AG WG</a>).</p>
image: /content-images/wai-intro-wcag/wcag-intro-social.jpg
feedbackmail: wai@w3.org  
ref: /standards-guidelines/wcag/

---

{::nomarkdown}
{% include box.html type="start" h="2" title="Résumé" class="full" %}
{:/}

Présentation des règles pour l'accessibilité des contenus web (WCAG), y compris WCAG 2.0 et WCAG 2.1.

Liens vers les ressources :
* [How to Meet WCAG 2 (Quick Reference)](http://www.w3.org/WAI/WCAG21/quickref/)
* [WCAG 2.1 Standard](http://www.w3.org/TR/WCAG21/)
* [WCAG 2.0 Standard](http://www.w3.org/TR/WCAG20/)

{::nomarkdown}
{% include box.html type="end" %}
{:/}

{::nomarkdown}
{% include_cached toc.html type="start" title="Contenu de la page" class="simple" %}
{:/}

{::options toc_levels="2" /}

-   This text will be replaced by the TOC.
{:toc}

{::nomarkdown}
{% include_cached toc.html type="end" %}
{:/}

## Introduction {#intro}

Les règles pour l'accessibilité des contenus web (WCAG) sont développées dans le cadre du [Processus du W3C](/standards-guidelines/w3c-process/) en collaboration avec des personnes et des organismes du monde entier, dans le but de fournir un standard unique commun pour l'accessibilité des contenus web répondant, au niveau international, aux besoins des personnes, des organismes et des gouvernements.

Les documents des WCAG expliquent comment rendre les contenus web plus accessibles aux personnes handicapées. Le terme « contenu » Web fait en général référence à l'information d'une page web ou d'une application web, comprenant :

-   les informations générales telles que le texte, les images et les sons
-   le code ou le balisage qui définit la structure, la présentation, etc.

## WCAG 2.0 et 2.1 {#versions}

Les WCAG 2.0 ont été publiées le 11 décembre  2008. Les WCAG 2.1 ont été publiées le 5 juin 2018.

Toutes les exigences (« critères de succès"
 ») de la version 2.0 sont incluses dans la 2.1. Les critères de succès 2.0 sont exactement les mêmes (verbatim, mot pour mot) dans la 2.1.

La version 2.1 comprend des critères de succès supplémentaires qui n'étaient pas dans la version 2.0. Ils sont présentés dans [[Quoi de neuf dans les WCAG 2.1]](/standards-guidelines/wcag/new-in-21/).

**Les contenus conformes aux WCAG 2.1 sont également conformes aux WCAG 2.0**. (On appelle souvent cela “la rétro compatibilité”.) Un site web conforme aux WCAG 2.1 devrait répondre aux exigences des politiques qui font référence aux WCAG 2.0.

Dit autrement : si vous voulez vous conformer à la fois aux WCAG 2.0 et WCAG 2.1, vous pouvez utiliser les ressources des 2.1 et vous n'avez pas besoin de vous préoccuper des 2.0.

Les WCAG 2.0 et WCAG 2.1 sont toutes deux des normes en vigueur. Les WCAG 2.1 ne déprécient ni ne remplacent les WCAG 2.0. Le W3C vous encourage à utiliser la version la plus récente des WCAG quand vous développez ou mettez à jour des contenus ou une politique d'accessibilité.

## À qui s'adressent les WCAG {#for}

En premier lieu, les WCAG sont destinées :

-   aux personnes qui développent des contenus web (conception de pages, designers de sites, etc.)
-   aux personnes qui développent des outils pour l'édition sur le web,
-   aux personnes qui développent des outils pour évaluer l'accessibilité du web, 
-   à d'autres personnes qui souhaitent ou qui ont besoin d'un standard sur l'accessibilité du web, y compris pour l'accessibilité du mobile.

Les ressources liées sont destinées à répondre aux besoins de beaucoup de personnes différentes, incluant les responsables de politiques, les chefs de projets et les chercheurs, et d'autres.

Les WCAG sont une norme technique, et non une introduction à l'accessibilité. Pour des documents d'introduction, voir [“Where should I start?” dans la FAQ](/standards-guidelines/wcag/faq/#start).

## Que contiennent les documents des WCAG 2 {#whatis2}

**[WCAG 2.0](https://www.w3.org/TR/WCAG20/)** et **[WCAG 2.1](https://www.w3.org/TR/WCAG21/)** sont des standards techniques stables, referenceables. Ils contiennent 12-13 règles organisées selon [4 principes : perceptible, utilisable, compréhensible et robuste](https://www.w3.org/WAI/WCAG21/Understanding/intro#understanding-the-four-principles-of-accessibility). Pour chaque règle, il y a des *critères de succès* à tester, qui sont sur [trois niveaux : A, AA, et AAA](https://www.w3.org/WAI/WCAG21/Understanding/conformance#levels).

Pour un court résumé des règles des  WCAG 2, voir **[[WCAG 2 en bref]](/standards-guidelines/wcag/glance/)**.

Pour en savoir plus sur les principes et les règles de l'accessibilité du web, voir **[[Les Principes d'accessibilité]](/fundamentals/accessibility-principles/)**.

Les documents techniques d'accompagnement des WCAG 2 comprennent :

-   [**How to Meet WCAG 2**: A customizable quick reference to Web Content Accessibility Guidelines 2 requirements (success criteria) and techniques](http://www.w3.org/WAI/WCAG21/quickref/) is essentially the [WCAG 2 checklist](http://www.w3.org/WAI/WCAG21/quickref/). La plupart des gens utilisent cette référence rapide comme ressource principale pour travailler avec les  WCAG.
-   **Techniques for WCAG 2** ([2.1 Techniques](https://www.w3.org/WAI/WCAG21/Techniques/), [2.0 Techniques](https://www.w3.org/TR/WCAG20-TECHS/)) vous donnent des détails spécifiques sur la façon de développer des contenus web accessibles, tels que des exemples de code HTML. Les techniques sont « informatives », c'est-à-dire que vous n'êtes pas obligés de les utiliser. La base sur laquelle déterminer la conformité aux WCAG 2 est les *critères de succès* de la norme des WCAG 2, et non les techniques. Lire plus d'informations dans [Techniques in the FAQ](/standards-guidelines/wcag/faq/#techs).
-  **Comprendre les WCAG 2** ([Comprendre 2.1](https://www.w3.org/WAI/WCAG21/Understanding/), [Comprendre 2.0](https://www.w3.org/TR/UNDERSTANDING-WCAG20/)) donne une aide supplémentaire pour apprendre à implémenter les WCAG 2 pour les personnes souhaitant comprendre les règles et les critères de succès plus en détail.

Pour plus de détails sur ces documents et comment ils sont liés, voir **[[Les documents des WCAG]](/standards-guidelines/wcag/docs/)**.

### Traductions

Les traductions autorisées et non officielles des WCAG 2 sont référencées dans [[WCAG 2 Translations]](/standards-guidelines/wcag/translations/).

### Format des documents techniques

Les documents tecniques et pour comprendre les WCAG sont au format du W3C destiné aux rapports techniques, qui contient plusieurs paragraphes, au début, avec des liens vers différentes versions, auteurs, résumé et statut.

### Aide supplémentaire {#supplement}

Une aide supplémentaire vous propose d'autres informations au-delà de ce qui est requis dans les WCAG 2.0 et 2.1. Elle concerne l'amélioration de l'accessibilité pour les personnes ayant des handicaps cognitifs et les personnes ayant une basse vision. Des liens vers une aide supplémentaire seront prochainement ajoutés à ce paragraphe.

## Les WCAG 2.0 sont une norme ISO/IEC 40500 {#iso}

Les WCAG 2.0 ont été approuvées comme norme ISO : ISO/IEC 40500:2012. ISO/IEC 40500 est exactement la même norme que les WCAG d'origine, les WCAG 2.0, introduites ci-dessus avec les ressources d'accompagnement.

Le contenu d'ISO/IEC 40500 est disponible gratuitement à [www.w3.org/TR/WCAG20](http://www.w3.org/TR/WCAG20/); il peut être acheté dans le [catalogue ISO{% include_cached external.html %}](http://www.iso.org/iso/iso_catalogue/catalogue_tc/catalogue_detail.htm?csnumber=58625).

Les avantages des WCAG 2.0 en tant que norme ISO sont résumés dans [ISO dans la FAQ](/standards-guidelines/wcag/faq/#iso). Plus d'informations sur le W3C et le processus ISO sont dans [W3C PAS FAQ](http://www.w3.org/2010/04/pasfaq).

## Autres recommandations {#components}

Les WCAG font partie d'une série de recommandations d'accessibilité qui comprennent les <span lang="en>Authoring Tool Accessibility Guidelines</span> (ATAG) et les <span lang="en">User Agent Accessibility Guidelines</span> (UAAG). [[Les composantes essentielles de l'accessibilité du Web]](/fundamentals/components/) expliquent la relation entre les différentes recommandations.

## Qui développe les WCAG {#wg}

Les documents techniques des WCAG sont développés par le groupe de travail <span lang="en">Accessibility Guidelines Working Group</span> ([AG WG](https://www.w3.org/WAI/GL/)) *(anciennement le <span lang="en">Web Content Accessibility Guidelines Working Group</span>)*, qui fait partie du <span lang="en">World Wide Web Consortium</span> ([W3C](http://www.w3.org)) La <span lang="en">Web Accessibility Initiative</span> ([WAI](https://www.w3.org/WAI/)).

WAI met à jour les techniques pour les WCAG 2 et Comprendre les WCAG 2 régulièrement. Tous [commentaires](/standards-guidelines/wcag/commenting/) et [envoi de nouvelles techniques](http://www.w3.org/WAI/GL/WCAG20/TECHS-SUBMIT/) sont les bienvenus.

Les possibilités de contribuer aux WCAG et aux autres travaux de la WAI sont présentées dans [[Participer à la WAI]](/about/participating/).

## Plus d'informations {#more}

Voir la [[FAQ des WCAG 2]](/standards-guidelines/wcag/faq/) pour plus d'informations sur :

-   **Le support par les WCAG 2 de [l'accessibilité mobile](/standards-guidelines/wcag/faq/#mobile)**
-   **L'applicabilité des WCAG 2 à des technologies ne relevant pas du w3C [<span lang="en">non-W3C technologies</span>](/standards-guidelines/wcag/faq/#othertechs)**
-   et plus encore...
