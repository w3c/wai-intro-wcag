---
# Translation info https://www.w3.org/wiki/WAI/Website/Translate

title: "What’s New in WCAG 2.1"
nav_title: "New in 2.1"

description: This page lists the new success criteria in Web Content Accessibility Guidelines (WCAG) 2.1. It includes quotes from personas (fictional people) to help you understand some aspects of the success criteria.

teaser_text: WCAG 2.1 has 17 additional requirements (“success criteria”) that address mobile accessibility, people with low vision, and people with cognitive and learning disabilities. The What’s New in WCAG 2.1 page introduces the new success criteria. It includes quotes from personas to help you understand the issues.

lang: en
last_updated: 2019-04-08
permalink: /standards-guidelines/wcag/new-in-21/

github:
  repository: w3c/wai-intro-wcag
  path: 'new-in-21.md'

image: /content-images/wai-intro-wcag/general-social.jpg
footer: >
  <p><strong>Date:</strong> Updated 8 April 2019.</p>
  <p><strong>Editor:</strong> <a href="https://www.w3.org/People/Shawn/">Shawn Lawton Henry</a>. Contributors: Shadi Abou-Zahra, Jonathan Avila, Brent Bakken, Laura Carlson, Stéphane Deschamps, Eric Eggert, James Green, Becky Gibson, Marc Johlic, Robert Jolly, Howard Kramer, Chris O'Brien, Sharron Rush, Nic Steenhout, Glenda Sims, Bill Tyler.</p>
  <p>Developed with input from the Education and Outreach Working Group (<a href="https://www.w3.org/WAI/about/groups/eowg/">EOWG</a>) and the Accessibility Guidelines Working Group (<a href="https://www.w3.org/WAI/about/groups/eowg/">AG WG</a>).</p>
inline_css: |
  blockquote {font-style: normal !important;}
  blockquote p:first-of-type:before, blockquote p:last-of-type:after, blockquote dl:last-of-type:after {content: '' !important;margin-left: 0 !important;}
  blockquote.sc {padding: 0 10px 15px 20px;border: solid #ccc 1px;background: #f0f0f0;color: #000; margin-right: 0; margin-bottom:40px;}
  .quotes {margin-bottom:40px;}
  .quotes ul {list-style-type: none;}
  .quotes li>p {display:table-row; padding-bottom:}
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
ref: /standards-guidelines/wcag/new-in-21/
---

{::nomarkdown}
{% include box.html type="start" h="2" title="Summary" class="full" %}
{:/}

This page lists the new success criteria in Web Content Accessibility Guidelines (WCAG) 2.1.

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

## Introducción

Puede ver una introducción a las Pautas de Accesibilidad del Contenido Web y saber más sobre las versiones 2.0 y 2.1 consultando la [[Introducción a WCAG]](/standards-guidelines/wcag/).

Todos los requisitos (criterios de conformidad) de la versión 2.0 están incluidos en 2.1. Los criterios de conformidad 2.0 son exactamente iguales (literalmente) en 2.1.

WCAG proporciona 17 criterios de conformidad adicionales que hay que tener en cuenta:

- [[Accesibilidad móvil]](/standards-guidelines/mobile/)
- Personas con baja visión
- [[Personas con discapacidades cognitivas y del aprendizaje]](/standards-guidelines/cognitive/)

## Pauta 1.3 Adaptable

Cree contenido que pueda presentarse en diferentes formas (por ejemplo, con una disposición más simple) sin perder información ni estructura.

### 1.3.4 Orientación  (AA)

<blockquote class="sc">
  <p>El contenido no restringe su vista y operación a una única orientación, como por ejemplo retrato o paisaje, salvo que una orientación específica sea <a href="https://www.w3.org/TR/WCAG21/#dfn-essential" data-link-type="dfn">esencial</a>.</p>
</blockquote>
<p class="persona">Un cómico con parálisis cerebral que usa una silla de ruedas:</p>
<div class="quotes">
  <ul>
    <li><p><span class="issue">Problema:</span><span><q>No puedo rotar mi tableta, está fijada a mi silla de ruedas.</q></span></p></li>
    <li><p><span class="issue">Funciona bien:</span><span><q>La aplicación funciona tanto si mi tableta está fijada de forma horizontal como vertical.</q></span></p></li>
  </ul>
</div>
<p><a href="https://www.w3.org/WAI/WCAG21/Understanding/orientation.html">Comprender la Orientación</a></p>

### 1.3.5 Identificación del Propósito de Entrada (AA)

<blockquote class="sc">
  <p>El propósito de cada campo de entrada que recoge información sobre el usuario puede ser <a href="https://www.w3.org/TR/WCAG21/#dfn-programmatically-determinable" data-link-type="dfn">determinado por software</a> cuando:</p>
  <ul>
    <li>El campo de entrada sirve a un propósito identificado en la sección de los <a href="https://www.w3.org/TR/WCAG21/#input-purposes">Propósitos de Entrada de los Componentes de la Interfaz de Usuario</a>; y</li>
    <li>El contenido se implementa usando tecnologías con soporte para identificar el significado esperado de los datos de entrada en formularios.</li>
  </ul>
</blockquote>
<p class="persona">Un <a href="https://www.w3.org/WAI/people-use-web/user-stories/#supermarketassistant">auxiliar de supermercado</a> con dislexia y discalculia:</p>
<div class="quotes">
  <ul>
    <li><p><span class="issue">Problema:</span><span><q>Mi dirección es tan complicada. Tiene muchos números y palabras largas. Me resulta difícil teclearlo todo sin cometer errores.</q></span></p></li>
    <li><p><span class="issue">Funciona bien:</span><span><q>Me encantan los sitios web que automáticamente rellenan todo eso por mí. De esta forma, no tengo que esforzarme tanto para asegurar que los números y las palabras están bien.</q><br/>
      <em>Nota: </em>Esto funciona porque los campos utilizan autocompletado.</span></p></li>
  </ul>
</div>
<p><a href="https://www.w3.org/WAI/WCAG21/Understanding/identify-input-purpose.html">Comprender la Identificación del Propósito de Entrada</a></p>

### 1.3.6 Identificación del Propósito (AAA)

<blockquote class="sc">
  <p>En el contenido implementado con lenguajes de marcado, el propósito de los <a href="https://www.w3.org/TR/WCAG21/#dfn-user-interface-components" data-link-type="dfn">Componentes de la Interfaz de Usuario</a>, iconos y <a href="https://www.w3.org/TR/WCAG21/#dfn-regions" data-link-type="dfn">regiones</a> puede <a href="https://www.w3.org/TR/WCAG21/#dfn-programmatically-determinable" data-link-type="dfn">determinarse por software</a>.</p>
</blockquote>
<p class="persona">Un jugador con discapacidad para procesar el lenguaje:</p>
<div class="quotes">
  <ul>
    <li><p><span class="issue">Problema:</span><span><q>Tengo un programa que cambia las palabras de la navegación por símbolos. No funciona con todos los sitios web.</q></span></p></li>
    <li><p><span class="issue">Funciona bien:</span><span><q>Funciona bastante bien con algunos sitios web.</q></span></p></li>
  </ul>
</div>
<p><a href="https://www.w3.org/WAI/WCAG21/Understanding/identify-purpose.html">Comprender la Identificación del Propósito</a></p>

## Pauta 1.4 Distinguible

Facilite que los usuarios puedan ver y oír el contenido incluyendo la separación entre el primer plano y el fondo.

### 1.4.10 Redimensionamiento  (AA)

<blockquote class="sc">
  <p>El contenido se puede presentar sin perder información ni funcionalidad, y sin necesidad de desplazamiento en dos dimensiones, para:</p>
  <ul>
    <li>Contenido en desplazamiento vertical con una anchura equivalente a 320 <a href="https://www.w3.org/TR/WCAG21/#dfn-css-pixels" data-link-type="dfn">píxeles en CSS</a>;</li>
    <li>Contenido en desplazamiento horizontal con una altura equivalente a 256 <a href="https://www.w3.org/TR/WCAG21/#dfn-css-pixels" data-link-type="dfn">píxeles en CSS</a>;</li>
  </ul>
  <p>Excepto para aquellas partes del contenido que debido a su uso o significado requieran desplazamiento bidimensional.</p>
</blockquote>
<p class="persona">Un padre con baja visión – 20/400:</p>
<div class="quotes">
  <ul>
    <li><p><span class="issue">Problema:</span><span><q>Es casi imposible leer el texto si tengo que desplazarme de derecha a izquierda con cada línea. Me siento desorientado y pierdo la posición. Hace que sea difícil entender lo que estoy leyendo.</q></span></p></li>
    <li><p><span class="issue">Funciona bien:</span><span><q>Aumento el tamaño del texto al 400% y se redimensiona dentro de la anchura de la ventana. Puedo leerlo fácilmente sin necesidad de desplazarme adelante y atrás.</q></span></p></li>
  </ul>
</div>
<p><a href="https://www.w3.org/WAI/WCAG21/Understanding/reflow.html">Comprender el Redimensionamiento</a></p>

### 1.4.11 Contraste no Textual (AA)

<blockquote class="sc">
  <p>La <a href="https://www.w3.org/TR/WCAG21/#dfn-presentation" data-link-type="dfn">presentación </a> visual de los siguientes elementos tiene un <a href="https://www.w3.org/TR/WCAG21/#dfn-contrast-ratio" data-link-type="dfn">ratio de contraste</a> de al menos 3:1 con respecto a los colores adyacentes:</p>
  <dl>
    <dt>Componentes de la interfaz de usuario</dt>
    <dd>Información visual necesaria para identificar los <a href="https://www.w3.org/TR/WCAG21/#dfn-user-interface-components" data-link-type="dfn">componentes de la interfaz de usuario</a> y los <a href="https://www.w3.org/TR/WCAG21/#dfn-states" data-link-type="dfn">estados</a>, excepto aquellos componentes inactivos o cuya apariencia sea determinada por el agente de usuario y no modificada por el autor;</dd>
    <dt>Objetos gráficos</dt>
    <dd>Partes de gráficos necesarias para comprender el contenido, excepto cuando una presentación particular de los gráficos sea <a href="https://www.w3.org/TR/WCAG21/#dfn-essential" data-link-type="dfn">esencial </a> para la información transmitida.</dd>
  </dl>
</blockquote>
<p class="persona"><a href="https://www.w3.org/WAI/people-use-web/user-stories/#retiree">Un jubilado</a> con poca sensibilidad al contraste:</p>
<div class="quotes">
  <ul>
    <li><p><span class="issue">Problema:</span><span><q>No pude usar el formulario de pedidos, no había cajas de texto. Después de una larga llamada con el servicio de atención al cliente, supe que las cajas de texto tenían un borde muy claro que yo no podía ver.</q></span></p></li>
    <li><p><span class="issue">Funciona bien:</span><span><q>Puedo ver los iconos, botones y todo lo demás fácilmente, incluso bajo la luz del sol.</q></span></p></li>
  </ul>
</div>
<p><a href="https://www.w3.org/WAI/WCAG21/Understanding/non-text-contrast.html">Comprender el Contraste no Textual</a></p>

### 1.4.12 Espaciado de Texto (AA)

<blockquote class="sc">
  <p>En contenido implementado con lenguajes de marcado que soporten las <a href="https://www.w3.org/TR/WCAG21/#dfn-style-properties" data-link-type="dfn">propiedades de estilo</a> del <a href="https://www.w3.org/TR/WCAG21/#dfn-text" data-link-type="dfn">texto</a> siguientes no se produce ninguna pérdida de contenido o funcionalidad al ajustar todas estas propiedades y sin cambiar ninguna otra propiedad de estilo:</p>
  <ul>
    <li>Altura de la línea hasta al menos 1,5 veces el tamaño de la fuente;</li>
    <li>Espacio tras párrafo hasta al menos 2 veces el tamaño de la fuente;</li>
    <li>Espacio entre letras (<span lang="en">tracking</span>) hasta al menos 0,12 veces el tamaño de la fuente;</li>
    <li>Espacio entre palabras hasta al menos 0,16 veces el tamaño de la fuente.</li>
  </ul>
  <p>Excepción: Los lenguajes humanos y el código que no usen una o más de estas propiedades en forma escrita pueden cumplir usando solamente las propiedades que existan para esa combinación de lenguaje y código.</p>
</blockquote>
<p class="persona"><a href="https://www.w3.org/WAI/people-use-web/user-stories/#classroomstudent">Un estudiante</a> con dislexia:<br/>
  y <a href="https://www.w3.org/WAI/people-use-web/user-stories/#retiree">un jubilado</a> con baja visión:</p>
<div class="quotes">
  <ul>
    <li><p><span class="issue">Problema:</span><span><q>La mayor parte del texto es difícil de leer. Está tan amontonado que no puedo concentrarme. Solamente aumentando el espacio entre líneas ya noto una diferencia. Cuando estoy muy cansado, también aumento el espacio entre palabras.</q></span></p></li>
    <li><p><span class="issue">Funciona bien:</span><span><q>De acuerdo, sé que soy un poco raro, pero he creado una hoja de estilos que establece el espaciado de texto adecuado para mí. Es un alivio cuando los sitios web funcionan con mi CSS.</q></span></p></li>
  </ul>
</div>
<a href="https://www.w3.org/WAI/WCAG21/Understanding/text-spacing.html">Comprender el Espaciado de Texto</a>

### 1.4.13 Contenido sobre Cursor o en Foco (AA)

<blockquote class="sc">
  <p>Si moviendo y alejado el cursor o el foco del teclado sobre un elemento resulta en contenido adicional que se muestra y después se oculta, entonces lo siguiente debe ser cierto:</p>
  <dl>
    <dt>Descartable</dt>
    <dd>Debe existir un <a href="https://www.w3.org/TR/WCAG21/#dfn-mechanism" data-link-type="dfn">mecanismo</a> para descartar el contenido adicional sin mover el cursor o el foco del teclado, salvo que el contenido adicional informe acerca de un <a href="https://www.w3.org/TR/WCAG21/#dfn-input-error" data-link-type="dfn">error de entrada</a> o no oculte ni sustituya otro contenido;</dd>
    <dt>Sobrevolable</dt>
    <dd>Si posando el cursor sobre un elemento resulta en contenido adicional que se muestra, entonces el cursor debe poder moverse sobre el contenido adicional sin que éste desaparezca;</dd>
    <dt>Persistente</dt>
    <dd>El contenido adicional debe permanecer visible hasta que el cursor o el foco lo abandonen, el usuario lo descarte o la información ya no sea válida.</dd>
  </dl>
  <p>Excepción: la presentación visual del contenido adicional es controlada por el agente de usuario y no es modificada por el autor.</p>
</blockquote>
<p class="persona">Un profesor con baja visión que usa un programa de magnificación de pantalla:</p>
<div class="quotes">
  <ul>
    <li><p><span class="issue">Problema:</span><span><q>Estaba moviendo el ratón para seguir lo que veía en el sitio web. Me ayuda a concentrarme. De repente, bum, apareció un cuadro pequeño. Cubría lo que estaba intentando leer y no pude hacerlo desaparecer.</q></span></p></li>
    <li><p><span class="issue">Funciona bien:</span><span><q>Posé el ratón sobre una palabra y se abrió un cuadro con su definición, pero se encontraba prácticamente fuera de la pantalla debido a mi magnificación. Moví el puntero del ratón hasta el cuadro de definición magnificado y me desplacé por éste, que permaneció visible y de esta forma pude leerlo.</q></span></p></li>
  </ul>
</div>
<p><a href="https://www.w3.org/WAI/WCAG21/Understanding/content-on-hover-or-focus.html">Comprender Contenido sobre Cursor o en Foco</a></p>

## Pauta 2.1 Accesible por Teclado

Proporcione acceso a toda la funcionalidad mediante el teclado.

### 2.1.4 Atajos de Teclado (A)

<blockquote class="sc">
  <p>Si el contenido implementa un <a href="https://www.w3.org/TR/WCAG21/#dfn-keyboard-shortcuts" data-link-type="dfn">atajo de teclado</a> que solamente hace uso de letras (tanto mayúsculas como minúsculas), signos de puntuación, números o símbolos, entonces al menos una de las siguientes condiciones debe ser cierta:</p>
  <dl>
    <dt>Desactivación</dt>
    <dd>Existe un <a href="https://www.w3.org/TR/WCAG21/#dfn-mechanism" data-link-type="dfn">mecanismo </a> para desactivar el atajo de teclado;</dd>
    <dt>Modificación</dt>
    <dd>Existe un mecanismo que modifica el atajo para usar una o más teclas de caracteres no imprimibles (por ejemplo Ctrl, Alt, etc)</dd>
    <dt>Activo solamente en foco</dt>
    <dd>El atajo de teclado perteneciente a un <a href="https://www.w3.org/TR/WCAG21/#dfn-user-interface-components" data-link-type="dfn">componente de la interfaz de usuario</a> solamente está activo cuando dicho componente tiene el foco.</dd>
  </dl>
</blockquote>
<p class="persona"><a href="https://www.w3.org/WAI/people-use-web/user-stories/#reporter">Un periodista</a> con trastorno musculoesquelético que usa un programa de reconocimiento de voz:</p>
<div class="quotes">
  <ul>
    <li><p><span class="issue">Problema:</span><span><q>Usando mi aplicación de correo electrónico, borraba los mensajes en lugar de abrirlos.</q><br/>
      <em>Nota: </em>Había un atajo de teclado para borrar los mensajes que se activaba por algo que él estaba diciendo y no había manera de desactivarlo.</span></p></li>
    <li><p><span class="issue">Funciona bien:</span><span><q>En mi aplicación de hojas de cálculo puedo desactivar o modificar los atajos de teclado.</q></span></p></li>
  </ul>
</div>
<p><a href="https://www.w3.org/WAI/WCAG21/Understanding/character-key-shortcuts.html">Comprender los Atajos de Teclado</a></p>

## Guideline 2.2 Tiempo Suficiente

Proporcione a los usuarios tiempo suficiente para leer y usar el contenido.

### 2.2.6 Límites Temporales (AAA)

<blockquote class="sc">
  <p>Los usuarios son informados de la duración del periodo de <a href="https://www.w3.org/TR/WCAG21/#dfn-user-inactivity" data-link-type="dfn">inactividad</a> que podría provocar la pérdida de datos, salvo que los datos se mantengan durante más de 20 horas desde que el usuario no realiza acciones.</p>
</blockquote>
<p class="persona">Un auxiliar de supervisión en un colegio con discapacidad cognitiva:</p>
<div class="quotes">
  <ul>
    <li><p><span class="issue">Problema:</span><span><q>Estaba seleccionando los beneficios de los empleados y comparando diferentes planes. Cuando volví para seleccionar el plan de salud, la sesión caducó y perdí toda la información que había introducido.</q></span></p></li>
    <li><p><span class="issue">Funciona bien:</span><span><q>Al iniciar la aplicación de beneficios de los empleados, fui informado de cuántos minutos disponía para rellenar los formularios.</q></span></p></li>
  </ul>
</div>
<p><a href="https://www.w3.org/WAI/WCAG21/Understanding/timeouts.html">Comprender los Límites Temporales</a></p>

## Guideline 2.3 Seizures and Physical Reactions

Do not design content in a way that is known to cause seizures or physical reactions.

### 2.3.3 Animation from Interactions (AAA)

<blockquote class="sc">
  <p><a href="https://www.w3.org/TR/WCAG21/#dfn-motion-animation" data-link-type="dfn">Motion animation</a> triggered by interaction can be disabled, unless the animation is <a href="https://www.w3.org/TR/WCAG21/#dfn-essential" data-link-type="dfn">essential</a> to the functionality or the information being conveyed.</p>
</blockquote>
<p class="persona">Artist with vestibular disorder:</p>
<div class="quotes">
  <ul>
    <li><p><span class="issue">Problem:</span><span><q>In the online tax app, as I move my  mouse around or tab to different fields, this little bubble with the current  balance follows me around the screen. Makes me dizzy and nauseous.</q></span></p></li>
    <li><p><span class="issue">Works well:</span><span><q>I was so glad there was an option  to turn off animations.</q></span></p></li>
  </ul>
</div>
<p><a href="https://www.w3.org/WAI/WCAG21/Understanding/animation-from-interactions.html">Understanding Animation from Interactions</a></p>

## Guideline 2.5 Input Modalities

Make it easier for users to operate functionality through various inputs beyond keyboard.

### 2.5.1 Pointer Gestures (A)

<blockquote class="sc">
  <p>All <a href="https://www.w3.org/TR/WCAG21/#dfn-functionality" data-link-type="dfn">functionality</a> that uses multipoint or path-based gestures for operation can be operated with a <a href="https://www.w3.org/TR/WCAG21/#dfn-single-pointer" data-link-type="dfn">single pointer</a> without a path-based gesture, unless a multipoint or path-based gesture is <a href="https://www.w3.org/TR/WCAG21/#dfn-essential" data-link-type="dfn">essential</a>.</p>
</blockquote>
<p class="persona">Comic with cerebral palsy who has limited movement in fingers:</p>
<div class="quotes">
  <ul>
    <li><p><span class="issue">Problem:</span><span><q>I can't move my fingers like that. I need another way to zoom in the map.</q></span></p></li>
    <li><p><span class="issue">Works well:</span><span><q>Good thing there are buttons to  zoom in and out.</q></span></p></li>
  </ul>
</div>
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
<p class="persona"> Politician with motor disabilities and low vision:</p>
<div class="quotes">
  <ul>
    <li><p><span class="issue">Problem:</span><span><q>I went to hit the &quot;Mute&quot; button and  accidentally touched the &quot;End Call&quot; button instead. It hung up immediately.</q></span></p></li>
    <li><p><span class="issue">Works well:</span><span><q>In another web conferencing  application, if I accidentally touch the &quot;End Call&quot; button, I can just slide my  finger off the &quot;End Call&quot; button and it won't end the call.</q></span></p></li>
  </ul>
</div>
<p><a href="https://www.w3.org/WAI/WCAG21/Understanding/pointer-cancellation.html">Understanding Pointer Cancellation</a></p>

### 2.5.3 Label in Name (A)

<blockquote class="sc">
  <p>For <a href="https://www.w3.org/TR/WCAG21/#dfn-user-interface-components" data-link-type="dfn">user interface components</a> with <a href="https://www.w3.org/TR/WCAG21/#dfn-labels" data-link-type="dfn">labels</a> that include <a href="https://www.w3.org/TR/WCAG21/#dfn-text" data-link-type="dfn">text</a> or <a href="https://www.w3.org/TR/WCAG21/#dfn-images-of-text" data-link-type="dfn">images of text</a>, the <a href="https://www.w3.org/TR/WCAG21/#dfn-name" data-link-type="dfn">name</a> contains the text that is presented visually.</p>
</blockquote>
<p class="persona"><a href="https://www.w3.org/WAI/people-use-web/user-stories/#reporter">Reporter</a> with repetitive stress injury who uses voice recognition software:</p>
<div class="quotes">
  <ul>
    <li><p><span class="issue">Problem:</span><span><q>It understood most of my voice  commands until I got to the Send button. I kept saying 'Send' and it didn't work.</q><br/>
      <em>Note:  </em>It was visually labeled 'send' but the 'name' in the  code was 'submit'. It would have worked if the 'name' started with 'send'.</span></p></li>
  </ul>
</div>
<p><a href="https://www.w3.org/WAI/WCAG21/Understanding/label-in-name.html">Understanding Label in Name</a></p>

### 2.5.4 Motion Actuation (A)

<blockquote class="sc">
  <p><a href="https://www.w3.org/TR/WCAG21/#dfn-functionality" data-link-type="dfn">Functionality</a> that can be operated by device motion or user motion can also be operated by <a href="https://www.w3.org/TR/WCAG21/#dfn-user-interface-components" data-link-type="dfn">user interface components</a> and responding to the motion can be disabled to prevent accidental actuation, except when:</p>
  <dl>
    <dt>Supported Interface</dt>
    <dd>The motion is used to operate functionality through an <a href="https://www.w3.org/TR/WCAG21/#dfn-accessibility-supported" data-link-type="dfn">accessibility supported</a> interface;</dd>
    <dt>Essential</dt>
    <dd>The motion is <a href="https://www.w3.org/TR/WCAG21/#dfn-essential" data-link-type="dfn">essential</a> for the function and doing so would invalidate the activity.</dd>
  </dl>
</blockquote>
<p class="persona">Comic with cerebral palsy who uses a wheelchair:</p>
<div class="quotes">
  <ul>
    <li><p><span class="issue">Problem:</span><span><q>I can't shake my phone; it's  connected to my wheelchair. So there needs to be another way to activate that feature, like a button.</q></span></p></li>
    <li><p><span class="issue">Problem:</span><span><q>I have tremors, so I need to turn  off motion activation &mdash; and then be able to do stuff without motion  actuation.</q></span></p></li>
    <li><p><span class="issue">Works well:</span><span><q>My friend has this cool application that looks like a physical spin lock. She rotates the phone to turn to the combination. I can use the same application by typing the numbers directly.</q></span></p></li>
  </ul>
</div>
<p><a href="https://www.w3.org/WAI/WCAG21/Understanding/motion-actuation.html">Understanding Motion Actuation</a></p>

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
<p class="persona"><a href="https://www.w3.org/WAI/people-use-web/user-stories/#retiree">Retiree</a> with hand tremor (and big fingers):</p>
<div class="quotes">
  <ul>
    <li><p><span class="issue">Problem:</span><span><q>The buttons are so small, I hit  &quot;Cancel&quot; when going for &quot;Submit&quot;. Then I have to start all over again.</q></span></p></li>
    <li><p><span class="issue">Works well:</span><span><q>This website buttons are big enough  that I don't hit the wrong button even when I'm riding on the bumpy bus.</q></span></p></li>
  </ul>
</div>
<p><a href="https://www.w3.org/WAI/WCAG21/Understanding/target-size.html">Understanding Target Size</a></p>

### 2.5.6 Concurrent Input Mechanisms (AAA)

<blockquote class="sc">
  <p>Web content does not restrict use of input modalities available on a platform except where the restriction is <a href="https://www.w3.org/TR/WCAG21/#dfn-essential" data-link-type="dfn">essential</a>, required to ensure the security of the content, or required to respect user settings.</p>
</blockquote>
<p class="persona"><a href="https://www.w3.org/WAI/people-use-web/user-stories/#reporter">Reporter</a> with repetitive stress injury who uses voice recognition software:</p>
<div class="quotes">
  <ul>
    <li><p><span class="issue">Problem:</span><span><q>When my RSI acts up, I switch back and forth a lot between keyboard, mouse,  stylus, voice. This application doesn't let me use the stylus when I have a keyboard plugged in.</q></span></p></li>
  </ul>
</div>
<p><a href="https://www.w3.org/WAI/WCAG21/Understanding/concurrent-input-mechanisms.html">Understanding Concurrent Input Mechanisms</a></p>

## Guideline 4.1 Compatible

Maximize compatibility with current and future user agents, including assistive technologies.

### 4.1.3 Status Messages (AA)

<blockquote class="sc">
  <p>In content implemented using markup languages, <a href="https://www.w3.org/TR/WCAG21/#dfn-status-messages" data-link-type="dfn">status messages</a> can be <a href="https://www.w3.org/TR/WCAG21/#dfn-programmatically-determinable" data-link-type="dfn">programmatically determined</a> through <a href="https://www.w3.org/TR/WCAG21/#dfn-role" data-link-type="dfn">role</a> or properties such that they can be presented to the user by <a href="https://www.w3.org/TR/WCAG21/#dfn-assistive-technologies" data-link-type="dfn">assistive technologies</a> without receiving focus.</p>
</blockquote>
<p class="persona"><a href="https://www.w3.org/WAI/people-use-web/user-stories/#ilya-senior-staff-member-who-is-blind">Accountant</a> who is blind and uses a screen reader:</p>
<div class="quotes">
  <ul>
    <li><p><span class="issue">Problem:</span><span><q>I selected a class for the conference, but I can't tell if it got added to my  schedule.</q></span></p></li>
    <li><p><span class="issue">Works well:</span><span><q>When I add a meeting to my calendar,  I hear a confirmation.</q></span></p></li>
  </ul>
</div>
<p><a href="https://www.w3.org/WAI/WCAG21/Understanding/status-messages.html">Understanding Status Messages</a></p>

## About the Personas Quotes

The linked persona roles go to the [[Stories of Web Users]](/people-use-web/user-stories/). That page has other personas with different disabilities. We might add more in the future.

After we’ve reviewed these persona quotes sufficiently, we plan to add
them to the Understanding documents.

