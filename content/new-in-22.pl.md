---
# Translation instructions are after the "#" character in this first section. They are comments that do not show up in the web page. You do not need to translate the instructions after "#".
# In this first section, do not translate the words before a colon. For example, do not translate "title:". Do translate the text after "title:".

title: "Nowe w WCAG 2.2"
title_html: "Co nowego w WCAG 2.2"
nav_title: "Nowe w WCAG 2.2"
lang: pl   # Change "en" to the translated-language shortcode
last_updated: 2024-02-25  # Put the date of this translation YYYY-MM-DD (with month in the middle)

translators:
  - name: "Stefan Wajda"

github:
  repository: w3c/wai-intro-wcag
  path: 'content/new-in-22.pl.md'  # Add the language shortcode to the middle of the filename, for example: content/index.fr.md

permalink: /standards-guidelines/wcag/new-in-22/pl  # Add the language shortcode to the end, with no slash at end, for example: /link/to/page/fr
ref: /standards-guidelines/wcag/new-in-22/  # Do not change this

description: Ta strona przedstawia listę nowych kryteriów sukcesu w Wytycznych dla dostępności treści internetowych (WCAG) 2.2. Zawiera ona cytaty z person, które pomagają zrozumieć niektóre aspekty kryteriów sukcesu.

teaser_text: WCAG 2.2 zawiera 9 dodatkowych wymagań („kryteriów sukcesu”), które odnoszą się do potrzeb osób z zaburzeniami poznawczymi lub trudnościami w uczeniu się, użytkowników urządzeń mobilnych i użytkowników ebooków. Strona Co nowego w WCAG 2.2 przedstawia nowe kryteria sukcesu. Zawiera ona cytaty z person, które pomagają zrozumieć te kwestie.

feedbackmail: wai@w3.org
image: /content-images/wai-intro-wcag/general-social.png

# In the footer below:
# Do not change the dates
# Translate the other words below, including "Date:" and "Editor:"
# Translate the Working Group name. Leave the Working Group acronym in English.
footer: >
  <p><strong>Data:</strong> Uaktualniono 5 października 2023.</p>
  <p><strong>Redaktor:</strong> <a href="https://www.w3.org/People/Shawn/">Shawn Lawton Henry</a>. Współpraca: Mike Gower, Shadi Abou-Zahra,  <a href="https://www.w3.org/groups/wg/eowg/participants">Uczestnicy EOWG</a>, oraz <a href="https://www.w3.org/groups/wg/ag/participants">Uczestnicy AG WG</a>.</p>
  <p>Opracowane z udziałem Grupy Roboczej ds. Edukacji i Kontaktów Zewnętrznych (<a href="https://www.w3.org/WAI/about/groups/eowg/">EOWG</a>) oraz Grupy Roboczej ds. wytycznych dla dostępności (<a href="https://www.w3.org/WAI/about/groups/eowg/">AG WG</a>).</p>

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
---

{::nomarkdown}
{% include box.html type="start" h="2" title="Podsumowanie" class="full" %}
{:/}

Na tej stronie przedstawiono nowe kryteria sukcesu w WCAG 2.2, w tym:
* Krótkie wprowadzenia, co robić i dlaczego jest to ważne
* Cytaty z [person](#about-the-personas), aby pomóc Ci zrozumieć niektóre aspekty kryteriów sukcesu
* Łącza do dokumentów objaśniających szczegółowo kryteria sukcesu i zawierających więcej przykładów

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

## Wprowadzenie

Wprowadzenie do Wytycznych dla dostępności treści internetowych (WCAG) i więcej informacji na temat wersji 2.0, 2.1 i 2.2 można znaleźć w artykule [Omówienie WCAG](/standards-guidelines/wcag/pl).

[WCAG 2.2](https://www.w3.org/TR/WCAG22/) zostały opublikowane jako standard sieciowy „Rekomendacja W3C” 5 października 2023 r.</p>

### Różnice między WCAG 2.1 a WCAG 2.2

**WCAG 2.2 wprowadziły 9 dodatkowych kryteriów sukcesu w porównaniu z WCAG 2.1. Są one przedstawione na tej stronie.**

Kryteria sukcesu wersji 2.0 i 2.1 są zasadniczo takie same w wersji 2.2, z&nbsp;jednym wyjątkiem: KS 4.1.1 Poprawność kodu jest przestarzałe i&nbsp;zostało usunięte z WCAG 2.2. Więcej informacji znajdziesz w [FAQ dla WCAG 2, 4.1.1 Poprawność kodu](/standards-guidelines/wcag/faq/#parsing411). WCAG 2.2 zawiera Uwagi dotyczące różnych języków; więcej informacji znajdziesz w [FAQ dla WCAG 2, internacjonalizacja](https://www.w3.org/WAI/standards-guidelines/wcag/faq/#i18n22).

## Wytyczna 2.4 Możliwe do nawigacji

Zapewnij użytkownikowi narzędzia pomagające w nawigacji, znalezieniu treści i określeniu, gdzie się aktualnie znajduje.

### 2.4.11 Fokus niezakryty (minimum) (AA)

<div class="quotes">
<p class="brief">W skrócie:</p>
<dl>
  <dt><span class="what">Co robić</span></dt>
  <dd>Zapewnij, że element, który otrzymuje fokus klawiatury, jest przynajmniej częściowo widoczny.</dd>
  <dt><span class="why">Dlaczego to jest ważne</span></dt>
  <dd>Osoby, które nie mogą korzystać z myszy, muszą widzieć element, który ma fokus klawiatury.</dd>

</dl>

<p class="persona">Przykład persony &mdash; a <a href="https://www.w3.org/WAI/people-use-web/user-stories/#reporter">dziennikarz</a> z powtarzającymi się urazami stresowymi, który korzysta z oprogramowania do rozpoznawania mowy:</p>
<dl>
  <dt><span class="issue">Problem</span></dt>
  <dd><span><q>Ta strona ma duży baner, który zawsze jest na dole <em>(przyklejony do stopki)</em>. Kiedy przenoszę fokus na elementy, niektóre są ukryte za banerem i nie mogę ich zobaczyć.</q></span></dd>
  <dt><span class="issue">Poprawne działanie</span></dt>
  <dd><span><q>Kiedy przenoszę fokus na elementy, widzę je całe.</q></span></dd>
</dl>
</div>

<p class="sclabel">Kryterium sukcesu WCAG:</p>
<blockquote class="sc">
  <p>Gdy <a href="https://www.w3.org/TR/WCAG22/#dfn-user-interface-components">komponent interfejsu użytkownika</a> otrzymuje fokus klawiatury, komponent nie jest całkowicie zakryty treścią stworzoną przez autora.</p>
  <p class="note"><em>Uwaga:</em> Gdy treść w konfigurowalnym interfejsie może być przestawiana przez użytkownika, wówczas przy testowaniu i spełnianiu tego kryterium sukcesu brane są pod uwagę tylko początkowe ustawienia ruchomej treści.</p>
  <p class="note"><em>Uwaga:</em> Treść otwierana przez <em>użytkownika</em>  może zakryć komponent otrzymujący fokus. Jeśli użytkownik może odkryć komponent z fokusem bez przesuwania fokusu klawiatury, komponent z fokusem nie jest uważany za zakryty treścią stworzoną przez autora.</p> 
</blockquote>
<p><a href="https://www.w3.org/WAI/WCAG22/Understanding/focus-not-obscured-minimum">Objaśnienie KS Fokus niezakryty (minimum)</a></p>

### 2.4.12 Fokus niezakryty (ulepszony) (AAA)

<div class="quotes">
<p class="brief">W skrócie:</p>
<dl>
  <dt><span class="what">Co robić</span></dt>
  <dd>Zapewnij, że element, który otrzymuje fokus klawiatury, jest w pełni widoczny.</dd>
  <dt><span class="why">Dlaczego to jest ważne</span></dt>
  <dd>Osoby, które nie mogą korzystać z myszy, muszą widzieć element, który ma fokus klawiatury.</dd>
</dl>

<p><em>(Persona, problem i poprawne działanie - tak samo jak powyżej w przypadku KS 2.4.12.)</em></p>
</div>

<p class="sclabel">Kryterium sukcesu WCAG:</p>
<blockquote class="sc">
  <p>Gdy <a href="https://www.w3.org/TR/WCAG22/#dfn-user-interface-components">komponent interfejsu użytkownika</a> otrzymuje fokus klawiatury, żadna część komponentu nie może być zakryta przez treść stworzoną przez autora.</p>
</blockquote>
<p><a href="https://www.w3.org/WAI/WCAG22/Understanding/focus-not-obscured-enhanced">Objaśnienie KS Fokus niezakryty (ulepszony)</a></p>

### 2.4.13 Wygląd fokusu (AAA)

<div class="quotes">
<p class="brief">W skrócie:</p>
<dl>
  <dt><span class="what">Co robić</span></dt>
  <dd>Użyj wskaźnika fokusu o odpowiedniej wielkości i kontraście.</dd>
  <dt><span class="why">Dlaczego to jest ważne</span></dt>
  <dd>Wiele osób, w tym osoby starsze, nie zauważa drobnych zmian w wyglądzie.</dd>
</dl>

<p class="persona">Przykład persony — <a href="https://www.w3.org/WAI/people-use-web/user-stories/#reporter">dziennikarz</a> z powtarzającymi się urazami stresowymi, który nie używa myszy:<br>
i <a href="https://www.w3.org/WAI/people-use-web/user-stories/#retiree">senior</a> z małą wrażliwością na kontrast:</p>
<dl>
  <dd><span><q>Poruszając się po stronie internetowej lub aplikacji, nie mogę stwierdzić, na czym skupia się uwaga klawiatury.</q></span></dd>
  <dt><span class="issue">Poprawne działanie</span></dt>
  <dd><span><q>Poruszając się po stronie internetowej lub aplikacji, widzę, gdzie znajduje się fokus klawiatury.</q></span></dd>
</dl>
</div>

<p class="sclabel">Kryterium sukcesu WCAG:</p>
<blockquote class="sc">
 <p>Gdy <a href="https://www.w3.org/TR/WCAG22/#dfn-focus-indicator">wskaźnik fokusu</a> klawiatury jest widoczny, obszar wskaźnika fokusu spełnia wszystkie poniższe kryteria:</p>
   <ul>
   <li>jest co najmniej tak duży jak obszar <a href="https://www.w3.org/TR/WCAG22/#dfn-perimeter">obwodu</a> o grubości 2 <a href="https://www.w3.org/TR/WCAG22/#dfn-css-pixels">pikseli CSS</a>  komponentu lub podkomponentu bez fokusu oraz</li>
   <li>ma współczynnik kontrastu co najmniej 3:1 między tymi samymi pikselami w stanie „ma fokus” i „nie ma fokusu”.</li>
   </ul>
   <p>Wyjątki:</p>
   <ul>
   <li>Wskaźnik fokusu jest określany przez oprogramowanie użytkownika i autor nie może go regulować lub</li>
   <li>Wskaźnik fokusu i kolor tła wskaźnika nie zostały zmienione przez twórcę.</li>
   </ul>
   <p class="note"><em>Uwaga:</em> To, co jest postrzegane jako komponent lub podkomponent interfejsu użytkownika (w celu określenia obwiedni lub rozmiaru), zależy od jego prezentacji wizualnej. Prezentacja wizualna obejmuje widoczną treść komponentu, obramowanie i tło specyficzne dla komponentu. Nie obejmuje efektów cienia i blasku poza treścią, tłem lub obramowaniem komponentu.</p>
   <p class="note"><em>Uwaga:</em> Przykładami podkomponentów, które mogą otrzymać fokus, są elementy menu w otwartym menu rozwijanym lub komórki siatki, na których można ustawić fokus.</p>
   <p class="note"><em>Uwaga:</em> Obliczenia kontrastu można wykonać w oparciu o kolory zdefiniowane w ramach technologii (np. HTML, CSS i SVG).  Piksele zmodyfikowane przez ulepszenia rozdzielczości oprogramowania użytkownika i wygładzanie można zignorować.</p>
</blockquote>
<p><a href="https://www.w3.org/WAI/WCAG22/Understanding/focus-appearance.html">Objaśnienie KS Wygląd fokusu</a></p>

## Wytyczna 2.5 Metody obsługi

Ułatwiaj użytkownikom obsługę funkcjonalności za pomocą różnych sposobów poza klawiaturą.

### 2.5.7 Ruch przeciągania (AA)

<div class="quotes">
<p class="brief">W skrócie:</p>
<dl>
  <dt><span class="what">Co robić</span></dt>
  <dd>W przypadku każdej akcji wymagającej przeciągania zapewnij alternatywę wykorzystującą pojedynczy wskaźnik</dd>
  <dt><span class="why">Dlaczego to jest ważne</span></dt>
  <dd>Niektóre osoby nie mogą używać myszy do przeciągania elementów.</dd>
</dl>

<p class="persona">Przykład osoby &mdash; a <a href="https://www.w3.org/WAI/people-use-web/user-stories/#retiree">senior</a> z drżeniem rąk:</p>
<dl>
  <dt><span class="issue">Problem</span></dt>
  <dd><span><q>Nie mogę przytrzymać przycisku myszy i przeciągnąć go wystarczająco dokładnie, aby przenieść elementy na tej liście.</q></span></dd>
  <dt><span class="issue">Poprawne działanie</span></dt>
  <dd><span><q>Gdy klikam element na liście, pojawiają się strzałki w górę i w dół, które mogę kliknąć, aby zmienić kolejność.</q></span></dd>
</dl>
</div>

<p class="sclabel">Kryterium sukcesu WCAG:</p>
<blockquote class="sc">
<p>Wszystkie funkcjonalności, które wykorzystują do działania <a href="https://www.w3.org/TR/WCAG22/#dfn-dragging-movements">ruch przeciągania</a> można zrealizować za pomocą <a href="https://www.w3.org/TR/WCAG22/#dfn-single-pointer">pojedynczego wskaźnika</a> bez przeciągania, chyba że przeciąganie jest <a href="https://www.w3.org/TR/WCAG22/#dfn-essential">niezbędne</a> lub funkcjonalność została określona przez program użytkownika, a nie twórcę.</p>
<p class="note"><em>Uwaga:</em> Wymóg ten dotyczy treści internetowych, które odczytują działania wskaźnika (tj. nie dotyczy działań, które są wymagane do obsługi programu użytkownika lub technologii wspomagającej).</p>
</blockquote>
<p><a href="https://www.w3.org/WAI/WCAG22/Understanding/dragging-movements">Objaśnienie KS Ruch przeciągania</a></p>

### 2.5.8 Rozmiar celu (minimalny) (AA)

<div class="quotes">
<p class="brief">W skrócie:</p>
<dl>
  <dt><span class="what">Co robić</span></dt>
  <dd>Zapewnij minimalny rozmiar celów lub wystarczające odstępy wokół nich.</dd>
  <dt><span class="why">Dlaczego to jest ważne</span></dt>
  <dd>Niektóre osoby z niepełnosprawnościami fizycznymi nie mogą klikać małych przycisków znajdujących się blisko siebie.</dd>
</dl>

<p class="persona">Przykład persony &mdash; <a href="https://www.w3.org/WAI/people-use-web/user-stories/#retiree">senior</a> z drżeniem rąk:</p>
<dl>
  <dt><span class="issue">Problem</span></dt>
  <dd><span><q>Przyciski są tak blisko, że wybierając „Prześlij”, klikam „Anuluj”. Wtedy muszę zacząć wszystko od nowa.</q></span></dd>
  <dt><span class="issue">Poprawne działanie</span></dt>
  <dd><span><q>Pomiędzy przyciskami jest więcej miejsca, więc nie nacisnę niewłaściwego przycisku, nawet gdy jadę autobusem po wyboistej drodze.</q></span></dd>
</dl>
</div>

<p class="sclabel">Kryterium sukcesu WCAG:</p>
<blockquote class="sc">
  <p>Rozmiar <a href="https://www.w3.org/TR/WCAG22/#dfn-targets">celu</a> dla <a href="https://www.w3.org/TR/WCAG22/#dfn-pointer-inputs">danych wprowadzanych wskaźnikiem </a> wynosi co najmniej 24 na 24 piksele CSS, z wyjątkiem sytuacji, gdy</p>
  <ul>
    <li><strong>Odstępy:</strong> Niewielkie cele (mniejsze niż 24 na 24 piksele CSS) są umieszczane w taki sposób, że jeśli okrąg o średnicy 24 pikseli CSS jest wyśrodkowany na <a>obwiedni</a> każdego z nich, okręgi nie przecinają innego celu ani okręgu innego niewielkiego celu;</li>
	<li><strong>Odpowiednik:</strong> Efekt może być osiągnięty na tej samej stronie za pomocą innej kontrolki, która spełnia to kryterium;</li>
	<li><strong>Wierszowe:</strong> Cel znajduje się w zdaniu lub jego rozmiar jest w inny sposób ograniczony przez wysokość linii tekstu innego niż wiersz z celem;</li>
	<li><strong>Kontrola programu użytkownika:</strong> Rozmiar celu jest określany przez program użytkownika i nie jest modyfikowany przez twórcę;</li>
	<li><strong>Istotny:</strong> Sposób przedstawienia celu jest <a href="https://www.w3.org/TR/WCAG22/#dfn-essential">niezbędny</a> albo jest prawnie wymagany przy przekazywaniu informacji.</li>
  </ul>
  <p class="note"><em>Uwaga:</em> Cele, które umożliwiają przestrzenny wybór wartości na podstawie pozycji w obrębie celu, są uważane za jeden cel na potrzeby tego kryterium sukcesu.  Przykładami mogą być suwaki, selektory kolorów wyświetlające gradient kolorów lub edytowalne obszary, w których umieszcza się kursor.</p>
  <p class="note"><em>Uwaga:</em> W przypadku celów wbudowanych wysokość linii należy interpretować jako prostopadłą do przepływu tekstu.  Na przykład w języku wyświetlanym pionowo wysokość linii będzie pozioma.</p>
</blockquote>
<p><a href="https://www.w3.org/WAI/WCAG22/Understanding/target-size-minimum.html">Objaśnienie KS Rozmiaru celu (minimalny)</a></p>

## Wytyczna 3.2 Przewidywalne

Twórz strony internetowe tak, aby otwierały się, wyglądały i działały w sposób przewidywalny.

### 3.2.6 Spójna pomoc (A)

<div class="quotes">
<p class="brief">W skrócie:</p>
<dl>
  <dt><span class="what">Co robić</span></dt>
  <dd>Umieść pomoc w tym samym miejscu, jeśli występuje na wielu stronach.</dd>
  <dt><span class="why">Dlaczego to jest ważne</span></dt>
  <dd>Osoby potrzebujące pomocy mogą ją łatwiej znaleźć, jeśli będzie ona w tym samym miejscu.</dd>
</dl>

<p class="persona">Przykład persony &mdash; <a href="https://www.w3.org/WAI/people-use-web/user-stories/#supermarketassistant">sprzedawca w supermarkecie</a> z niepełnosprawnością poznawczą:</p>
<dl>
  <dt><span class="issue">Problem</span></dt>
  <dd><span><q>Ilekroć korzystam z aplikacji internetowej do planowania wizyt lekarskich, nie pamiętam, co robić na każdym etapie. W niektórych miejscach widziałem opcję Czat, ale nie mogę jej teraz znaleźć.</q></span></dd>
  <dt><span class="issue">Poprawne działanie</span></dt>
  <dd><span><q>Kiedy potrzebuję pomocy, z łatwością mogę znaleźć opcję Czat, która zawsze znajduje się w prawym dolnym rogu strony.</q></span></dd>
</dl>
</div>

<p class="sclabel">Kryterium sukcesu WCAG:</p>
<blockquote class="sc">
<p>Jeśli <a href="https://www.w3.org/TR/WCAG22/#dfn-web-page-s">strona internetowa</a> zawiera którykolwiek z poniższych mechanizmów pomocy, a mechanizmy te powtarzają się na wielu stronach internetowych w ramach <a href="https://www.w3.org/TR/WCAG22/#dfn-set-of-web-pages">zestawu stron internetowych</a>, występują one w tej samej kolejności względem innych treści strony, chyba że użytkownik zainicjuje zmianę:</p>
<ul>
  <li>Dane kontaktowe człowieka;</li>
  <li>Mechanizm kontaktu z człowiekiem;</li>
  <li>Opcja samopomocy;</li>
  <li>W pełni zautomatyzowany mechanizm kontaktu.</li>
</ul>
<p class="note"><em>Uwaga:</em> Mechanizmy pomocy mogą być zapewniane bezpośrednio na stronie lub mogą być udostępniane poprzez bezpośrednie łącze do innej strony zawierającej informacje.</p>
<p class="note"><em>Uwaga:</em> W przypadku tego kryterium sukcesu „taka sama kolejność w stosunku do innej treści strony” może oznaczać sposób, w jaki treść jest uporządkowana, gdy strona jest serializowana.  Wizualna pozycja mechanizmu pomocy będzie prawdopodobnie taka sama na wszystkich stronach dla tej samej odmiany strony (np. punkt przerwania CSS).  Użytkownik może zainicjować zmianę, taką jak zmiana powiększenia lub orientacji strony, co może wywołać inną odmianę strony.  To kryterium dotyczy względnej kolejności na stronach wyświetlanych w tej samej odmianie strony (np. przy tym samym poziomie powiększenia i orientacji).</p>
</blockquote>
<p><a href="https://www.w3.org/WAI/WCAG22/Understanding/consistent-help">Objaśnienie KS Spójna pomoc</a></p>

## Wytyczna 3.3 Pomoc przy wprowadzaniu danych

Pomagaj użytkownikom unikać błędów i je korygować.

### 3.3.7 Ponowny wpis (A)

<div class="quotes">
<p class="brief">W skrócie:</p>
<dl>
  <dt><span class="what">Co robić</span></dt>
  <dd>Nie proś o tę samą informację dwa razy w trakcie jednej sesji.</dd>
  <dt><span class="why">Dlaczego to jest ważne</span></dt>
  <dd>Niektóre osoby z problemami poznawczymi mają trudności z zapamiętaniem tego, co wprowadziły wcześniej.</dd>
</dl>

<p class="persona">Przykład persony &mdash; <a href="https://www.w3.org/WAI/people-use-web/user-stories/#supermarketassistant">sprzedawca w supermarkecie</a> z niepełnosprawnością poznawczą:</p>
<dl>
  <dd><span><q>Ilekroć korzystam z aplikacji internetowej do planowania wizyt lekarskich, muszę ponownie wpisać niektóre informacje, które wprowadziłem w poprzednim kroku.</q></span></dd>
  <dt><span class="issue">Poprawne działanie</span></dt>
  dd><span><q>Aplikacja automatycznie uzupełnia informacje, które wprowadziłem w poprzednich krokach.</q></span></dd>
</dl>
</div>

<p class="sclabel">Kryterium sukcesu WCAG:</p>
<blockquote class="sc">
  <p>Informacje uprzednio wprowadzone przez użytkownika lub przekazane użytkownikowi, które muszą zostać wprowadzone ponownie w tej samej <a href="https://www.w3.org/TR/WCAG22/#dfn-processes" class="internalDFN" data-link-type="dfn">procedurze</a> są:</p>
    <ul>
	  <li>wypełniane automatycznie albo</li>
	  <li>możliwe do wybrania przez użytkownika.</li>
    </ul>
  <p>Za wyjątkiem sytuacji, gdy:</p>
    <ul>
	  <li>ponowne wprowadzenie informacji jest <a href="https://www.w3.org/TR/WCAG22/#dfn-essential" class="internalDFN" data-link-type="dfn">niezbędne</a>,</li>
	  <li>informacja jest niezbędna do zapewnienia bezpieczeństwa treści lub</li>
	  <li>poprzednio wprowadzona informacja jest już nieaktualna.</li>
    </ul>
</blockquote>
<p><a href="https://www.w3.org/WAI/WCAG22/Understanding/redundant-entry">Objaśnienie KS Ponowny wpis</a></p>

### 3.3.8 Dostępne uwierzytelnianie (minimum) (AA)

<div class="quotes">
<p class="brief">W skrócie:</p>
<dl>
  <dt><span class="what">Co robić</span></dt>
  <dd>Nie zmuszaj ludzi do rozwiązywania, przypominania sobie lub przepisywania czegoś, aby się zalogować.</dd>
  <dt><span class="why">Dlaczego to jest ważne</span></dt>
  <dd>Niektóre osoby z problemami poznawczymi nie mogą rozwiązywać zagadek, zapamiętywać nazwy użytkownika i hasła lub przepisywać jednorazowych kodów dostępu.</dd>
</dl>

<p class="persona">Przykład persony &mdash; <a href="https://www.w3.org/WAI/people-use-web/user-stories/#supermarketassistant">sprzedawca w supermarkecie</a> z niepełnosprawnością poznawczą:</p>
<dl>
  <dd><span><q>Nigdy nie pamiętam hasła, naprawdę trudno jest dostać się do tej aplikacji.</q></span></dd>
  <dt><span class="issue">Poprawne działanie</span></dt>
  <dd><span><q>Aby dostać się do tej aplikacji, mogę podać swój adres e-mail. Następnie otrzymuję wiadomość e-mail i mogę kliknąć łącze w wiadomości e-mail, aby uzyskać dostęp do aplikacji.</q></span></dd>
</dl>
</div>

<p class="sclabel">Kryterium sukcesu WCAG:</p>
<blockquote class="sc">
  <p><a href="https://www.w3.org/TR/WCAG22/#dfn-cognitive-function-test" class="internalDFN" data-link-type="dfn" id="ref-for-dfn-cognitive-function-test-1" title="Test funkcji poznawczych">test funkcji poznawczych</a> (taki jak zapamiętywanie hasła lub rozwiązywanie łamigłówki) nie jest wymagany na żadnym etapie procedury uwierzytelniania, chyba że etap ten zapewnia co najmniej jedną z poniższych:</p>
    <dl>
	  <dt>Alternatywa</dt>
	  <dd>Istnieje inna metoda uwierzytelniania, która nie opiera się na teście funkcji poznawczych.</dd>
	  <dt>Mechanizm</dt>
	  <dd>Istnieje mechanizm pomagający użytkownikowi w ukończeniu testu funkcji poznawczych.</dd>
	  <dt>Rozpoznawanie obiektów</dt>
	  <dd>Test funkcji poznawczych polega na rozpoznawaniu obiektów.</dd>
	  <dt>Treść osobista</dt>
	  <dd>Test funkcji poznawczych polega na rozpoznaniu treści nietekstowych, które użytkownik dostarczył wcześniej stronie internetowej.</dd>
    </dl>
    <p class="note"><em>Uwaga:</em> „Rozpoznawane obiekty” i „Treść osobista” mogą być reprezentowane przez obrazy, wideo lub audio.</p>
    <p class="note"><em>Uwaga:</em> Przykłady mechanizmów spełniających to kryterium obejmują:</p>
    <ol>
	  <li>obsługa wprowadzania haseł przez aplikacje do zarządzania hasłami w celu ograniczenia konieczności zapamiętywania oraz</li>
	  <li>funkcję kopiuj i wklej, aby zmniejszyć obciążenie poznawcze związane z ponownym wpisywaniem.</li>
    </ol>
</blockquote>
<p><a href="https://www.w3.org/WAI/WCAG22/Understanding/accessible-authentication-minimum">Objaśnienie KS Dostępne uwierzytelnianie (minimum)</a></p>

### 3.3.9 Dostępne uwierzytelnianie (ulepszone) (AAA)

<div class="quotes">
<p class="brief">W skrócie:</p>
<dl>
  <dt><span class="what">Co robić</span></dt>
  <dd>Nie zmuszaj użytkowników do rozpoznawania obiektów lub obrazów i mediów dostarczonych przez użytkownika w celu zalogowania się.</dd>
  <dt><span class="why">Dlaczego to jest ważne</span></dt>
  <dd>Niektóre osoby z problemami poznawczymi nie są w stanie rozwiązywać zagadek, w tym identyfikować obiektów i informacji nietekstowych, które wcześniej dostarczyły.</dd>
</dl>

<p class="persona">Przykład persony &mdash; <a href="https://www.w3.org/WAI/people-use-web/user-stories/#supermarketassistant">sprzedawca w supermarkecie</a> z niepełnosprawnością poznawczą:</p>
<dl>
  <dt><span class="issue">Problem</span></dt>
  <dd><span><q>Aby dostać się do tej aplikacji, dostaję monit o kliknięcie zdjęć kotów, ale nie mogę rozpoznać, które to koty.</q></span></dd>
  <dt><span class="issue">Poprawne działanie</span></dt>
  <dd><span><q>Aby dostać się do tej aplikacji, mogę skopiować i wkleić swoje hasło.</q></span></dd>
</dl>
</div>

<p class="sclabel">Kryterium sukcesu WCAG:</p>
<blockquote class="sc">
  <p><a href="https://www.w3.org/TR/WCAG22/#dfn-cognitive-function-test" class="internalDFN" data-link-type="dfn" id="ref-for-dfn-cognitive-function-test-2" title="Test funkcji poznawczych"></a> (taki jak zapamiętywanie hasła lub rozwiązywanie łamigłówki) nie jest wymagany na żadnym etapie procesu uwierzytelniania, chyba że etap ten zapewnia co najmniej jedną z poniższych:</p>
  <dl>
    <dt>Alternatywa</dt>
    <dd>Istnieje inna metoda uwierzytelniania, która nie opiera się na teście funkcji poznawczych.</dd>
    <dt>Mechanizm</dt>
    <dd>Istnieje mechanizm pomagający użytkownikowi w ukończeniu testu funkcji poznawczych.</dd>
   </dl>
</blockquote>
<p><a href="https://www.w3.org/WAI/WCAG22/Understanding/accessible-authentication-enhanced">Objaśnienie KS Dostępne uwierzytelnianie (rozszerzone)</a></p>

## O personach

Persony te to reprezentacje osób z niepełnosprawnościami opracowane na podstawie danych jakościowych dotyczących prawdziwych ludzi.

Podlinkowane role person prowadzą do <a href="https://www.w3.org/WAI/people-use-web/user-stories/">Historii użytkowników sieci</a> (Stories of Web Users). Na tej stronie znajdują się inne persony z różnymi niepełnosprawnościami.
