---
title: Principes d’accessibilité
permalink: /fundamentals/accessibility-principles/fr/
github:
  repository: w3c/wai-accessibility-principles
layout: default
description: Un aperçu des exigences d’accessibilité web fondamentales pour les sites et les applications web, les navigateurs et autres outils.
image: /content-images/wai-accessibility-principles/social.png
footer: >
  <p>Traduction&#8239;: Stéphane Deschamps pour <a href="http://www.w3.org/WAI/EO/" hreflang="en">EOWG</a>. La seule version officielle est <a href="https://www.w3.org/WAI/fundamentals/accessibility-principles/" hreflang="en">https://www.w3.org/WAI/fundamentals/accessibility-principles/</a> (en anglais).</p>
  <p><strong>Date:</strong> dernière mise à jour de cette traduction le @@DATE.</p>
  <p lang="en"><strong>Editors:</strong> <a href="https://www.w3.org/People/shadi/" hreflang="en">Shadi Abou_Zahra</a>. <a href="https://www.w3.org/WAI/intro/people-use-web/acknowledgments" hreflang="en">Acknowledgments</a>.</p>
  <p lang="en">Developed by the Education and Outreach Working Group (<a href="http://www.w3.org/WAI/EO/" hreflang="en">EOWG</a>). Previously developed with the <a href="https://www.w3.org/WAI/EO/2008/wai-age-tf" hreflang="en">WAI-AGE Task Force</a>, with support of the <a href="https://www.w3.org/WAI/WAI-AGE/" hreflang="en">WAI-AGE Project</a>.</p>

---

{::nomarkdown}
{% include box.html type="start" h="2" title="Résumé" class="full" %}
{:/}

Cette page introduit certaines exigences d’accessibilité web fondamentales pour les sites et les applications web, les navigateurs et autres outils. Elle fournit des liens vers les standards internationaux de l’Initiative Accessibilité du Web (WAI) du W3C et vers une page parlant des particularités de [quelques utilisateurs du Web]({{ "/people-use-web/user-stories.fr/" | relative_url }}).

**Note :** ce n’est pas une liste exhaustive de toutes les exigences d’accessibilité.

{::nomarkdown}
{% include box.html type="end" %}
{:/}


{::options toc_levels="2,3" /}

{::nomarkdown}
{% include_cached toc.html type="start" title="Contenu de la page" class="full" %}
{:/}

-   TOC is created automatically.
{:toc}

{::nomarkdown}
{% include_cached toc.html type="end" %}
{:/}


{% include excol.html type="all" %}

Standards d’accessibilité Web {#standards}
-----------------------------------------

L’accessibilité web s’appuie sur plusieurs composants qui travaillent ensemble. Certains d’entre eux sont :

- **Les contenus web**{:#webcontent} : ce terme s’applique à toute partie d’un site web, y compris le texte, les images, les formulaires et le multimédia, aussi bien que tout code, script, application, et ainsi de suite.
- **Les agents utilisateurs**{:#useragents} : des logiciels que l’on utilise pour accéder aux contenus web, incluant les navigateurs graphiques de bureau, les navigateurs vocaux, les navigateurs mobiles, les lecteurs multimédia, les <i lang="en">plug-ins</i>, et certaines [technologies d’assistance]({{ "/people-use-web/tools-techniques.fr/" | relative_url }}#at "définition").
- **Outils de production de contenu**{:#authoringtools} : des logiciels ou des services que l’on utilise pour produit des contenus web, incluant les éditeurs de code, les outils de conversion de documents, les systèmes de gestion de contenus, les blogs, les scripts de bases de données, et d’autres outils.

{% include excol.html type="start" %}

### Plus sur les standards d’accessibilité web
{:.no_toc}

{% include excol.html type="middle" %}

Ces composants sont liés les uns aux autres et se complètent mutuellement. Par exemple, le **contenu web** doit inclure des textes alternatifs pour les images. Cette information doit être interprétée par les **navigateurs web** puis transmise aux **technologies d’assistance**, comme les lecteurs d’écran. Pour créer ces alternatives textuelles, les auteurs ont besoin **d’outils de production de contenus** qui leur permettent de le faire. Plus d’information est disponible dans [Composants essentiels pour l’accessibilité web]({{ "/fundamentals/components.fr/" | relative_url }}).

Les standards jouent un rôle vital dans la définition des exigences d’accessibilité pour chacun de ces composants. Certaines exigences d’accessibilité sont facilement atteignables, cependant comprendre les bases du l’usage du Web par des personnes ayant un handicap aide à les mettre en place plus efficacement. Certains aspects de l’accessibilité réclament plus de compétences techniques ou de connaissances expertes de la façon dont les gens utilisent le Web. Dans tous les cas, [impliquer les utilisateurs dès le début et tout le long de vos projets web]({{ "/test-evaluate/involving-users/" | relative_url }}){: hreflang="en"} (en anglais) rendra votre travail plus facile et de meilleure qualité.

L’Initiative d’Accessibilité Web (WAI) fournit une liste de recommandations qui sont reconnues internationalement comme le standard pour l’accessibilité web. Elles incluent :

-   **[Recommandations d’accessibilité des contenus web (WCAG)]({{ "/standards-guidelines/wcag/" | relative_url }}){: hreflang="en"}** (en anglais)
-   **[Recommandations d’accessibilité des agents utilisateurs (UAAG)]({{ "/standards-guidelines/uaag/" | relative_url }}){: hreflang="en"}** (en anglais)
-   **[Recommandations d’accessibilité des outils de production de contenu (ATAG)]({{ "/standards-guidelines/atag/" | relative_url }}){: hreflang="en"}** (en anglais)

Il existe aussi une spécification WAI pour les [Applications internet riches accessibles  (WAI-ARIA)](https://www.w3.org/WAI/intro/aria.php){: hreflang="en"}** (en anglais), qui inclut les contenus dynamiques et les contrôles d’interface utilisateur avancés développés avec Ajax, Javascript et d’autres technologies web liées.

{% include excol.html type="end" %}

Information perceptible et interface utilisateur {#perceivable}
----------------------------------------------------------

### Alternatives textuelles pour les contenus non textuels {#alternatives}

Les alternatives textuelles sont un équivalent des contenus non textuels. Par exemple :

- Des équivalents courts pour les images, y compris les icônes, les boutons et les graphiques ;
- Une description des données représentées sur des graphes, des diagrammes et des illustrations ;
- Des descriptions courtes de contenus non textuels comme les fichiers audio et vidéo ;
- Des étiquettes pour les éléments de formulaires, de saisie, et d’autres composants d’interface utilisateur.

Les alternatives textuelles véhiculent le but d’une image ou sa fonction pour fournir une expérience utilisateur équivalente. Par exemple, le texte alternatif approprié d’un bouton de recherche pourrait être « *recherche* » plutôt que « *loupe* ».

Les alternatives textuelles peuvent être présentées sous des formes variées. Par exemple, elles peuvent être lues à voix haute aux personnes qui ne peuvent pas voir l’écran ou à des personnes ayant des difficultés à lire, elles peuvent être agrandies pour ceux qui ont personnalisé la taille d’affichage des textes, ou affichées sur des plages Braille. Les alternatives textuelles servent d’étiquettes pour les contrôles et les fonctionnalités et facilitent la navigation au clavier ou via la reconnaissance vocale (contrôle à la voix). Elles permettent aussi d’identifier les fichiers audio, vidéo et dans d’autres formats, ainsi que les applications intégrées dans un site web.

{% include excol.html type="start" %}

#### Exigences d’accessibilité liées aux alternatives textuelles (liens vers les spécifications techniques, en anglais)
{:.no_toc}

{% include excol.html type="middle" %}

<div lang="en">

**WCAG 2.0**

-   [Guideline 1.1 - Text
    Alternatives](http://www.w3.org/WAI/WCAG20/quickref/#text-equiv){: hreflang="en"}

**UAAG 2.0**

-   [Guideline 1.1 - Alternative
    content](https://www.w3.org/TR/UAAG20/#gl-access-alternative-content){: hreflang="en"}

**ATAG 2.0**

-   [Principle A.1: Authoring tool user interfaces follow applicable
    accessibility
    guidelines](https://www.w3.org/TR/ATAG20/#principle_a1){: hreflang="en"}
-   [Guideline A.2.1: (For the authoring tool user interface) Make
    alternative content available to
    authors](https://www.w3.org/TR/ATAG20/#gl_a21){: hreflang="en"}
-   [Guideline A.2.2: (For the authoring tool user interface) Ensure
    that editing-view presentation can be programmatically
    determined](https://www.w3.org/TR/ATAG20/#gl_a22){: hreflang="en"}
-   [Guideline A.3.7: (For the authoring tool user interface) Ensure
    that previews are at least as accessible as in-market user
    agents](https://www.w3.org/TR/ATAG20/#gl_b37){: hreflang="en"}
-   [Part B. Support the production of accessible
    content](https://www.w3.org/TR/ATAG20/#part_b){: hreflang="en"}

</div>

{% include excol.html type="end" %}

{% include excol.html type="start" %}

#### Histoires d’utilisateurs liées aux alternatives textuelles
{:#stories-related-to-text-alternatives.no_toc}

{% include excol.html type="middle" %}

-   [Alex, journaliste avec un trouble musculosquelettique]({{ "/people-use-web/user-stories.fr/" | relative_url }}#reporter)
-   [Martine, étudiante en ligne, malentendante]({{ "/people-use-web/user-stories.fr/" | relative_url }}#onlinestudent)
-   [Ilya, cadre supérieure, aveugle]({{ "/people-use-web/user-stories.fr/" | relative_url }}#accountant)
-   [Preety, élève de collège avec un trouble du déficit de l'attention avec hyperactivité et dyslexique]({{ "/people-use-web/user-stories.fr/" | relative_url }}#classroomstudent)
-   [Yun, retraité avec une mauvaise vue, un tremblement des mains, et une perte de mémoire à court terme]({{ "/people-use-web/user-stories.fr/" | relative_url }}#retiree)
-   [Kaseem, adolescente qui est sourde et aveugle]({{ "/people-use-web/user-stories.fr/" | relative_url }}#teenager)

{% include excol.html type="end" %}

### Sous-titres et autres alternatives pour le multimédia {#captions}

Une personne qui ne peut pas entendre le son ou voir la vidéo a besoin d’alternatives, par exemple :

- Des retranscriptions sous forme textuelle, des sous-titres pour les contenus audio, tels que les enregistrements ou une interview radio ;
- Des audio-descriptions, qui sont une narration qui décrit les détails visuels importants d’une vidéo ;
- Des traductions en langue des signes du contenu audio, y compris l’expérience audio pertinente.

Des retranscriptions texte bien écrites contenant la séquence correct de toutes les informations auditives et visuelles fournissent un niveau d’accessibilité de base et facilitent la production de sous-titres et d’audio-descriptions.

{% include excol.html type="start" %}

#### Exigences d’accessibilité liées au multimédia (liens vers les spécifications techniques, en anglais)
{:.no_toc}

{% include excol.html type="middle" %}

<div lang="en">

**WCAG 2.0**

-   [Guideline 1.2 - Time-based
    Media](http://www.w3.org/WAI/WCAG20/quickref/#media-equiv)

**UAAG 2.0**

-   [Guideline 1.1 - Alternative
    content](https://www.w3.org/TR/UAAG20/#gl-access-alternative-content)

**ATAG 2.0**

-   [Principle A.1: Authoring tool user interfaces follow applicable
    accessibility
    guidelines](https://www.w3.org/TR/ATAG20/#principle_a1)
-   [Guideline A.2.1: (For the authoring tool user interface) Make
    alternative content available to
    authors](https://www.w3.org/TR/ATAG20/#gl_a21)
-   [Guideline A.3.7: (For the authoring tool user interface) Ensure
    that previews are at least as accessible as in-market user
    agents](https://www.w3.org/TR/ATAG20/#gl_b37)
-   [Part B. Support the production of accessible
    content](https://www.w3.org/TR/ATAG20/#part_b)


</div>
{% include excol.html type="end" %}
{% include excol.html type="start" %}

#### Histoires d’utilisateurs liées au multimédia {#stories-related-to-multimedia}
{:.no_toc}

{% include excol.html type="middle" %}

-   [Martine, étudiante en ligne, malentendante]({{ "/people-use-web/user-stories.fr/" | relative_url }}#onlinestudent)
-   [Ilya, cadre supérieure, aveugle]({{ "/people-use-web/user-stories.fr/" | relative_url }}#accountant)
-   [Kaseem, adolescente qui est sourde et aveugle]({{ "/people-use-web/user-stories.fr/" | relative_url }}#teenager)

{% include excol.html type="end" %}

### Du contenu qui peut être présenté de différentes façons {#adaptable}

Pour que les utilisateurs puissent changer la présentatino des contenus, il est nécessaire que :

- Les titres, les listes, les tableaux, et autres structures de contenu soient convenablement balisés ;
- Les séquences d’informations ou d’instructions soient indépendantes de toute présentation ;
- Les navigateurs et les technologies d’assistance fournissent des réglages permettant de personnaliser la présentation.

Être conforme à cette exigence permet que le contenu soit correctement lu par une synthèse vocale, agrandi, ou adapté pour satisfaire aux besoins et aux préférences de différentes personnes. Par exemple, il peut être présenté dans une combinaison de couleurs personnalisée, dans une taille de police différente, ou selon des règles de style permettant d’en faciliter la lecture. Cette exigence facilite aussi d’autres formes d’adaptation, comme la génération automatique de plans de page ou de résumés pour permettre d’avoir une vue d’ensemble de la page et de se concentrer sur un endroit en particulier plus facilement.

{% include excol.html type="start" %}

#### Exigences d’accessibilité liées à l’adaptabilité (liens vers les spécifications techniques, en anglais)
{:.no_toc}

{% include excol.html type="middle" %}

<div lang="en">

**WCAG 2.0**

-   [Guideline 1.3 -
    Adaptable](http://www.w3.org/WAI/WCAG20/quickref/#content-structure-separation)

**UAAG 2.0**

-   [Guideline 1.4 - Text
    configuration](https://www.w3.org/TR/UAAG20/#gl-text-config)
-   [Guideline 1.5 - Volume
    configuration](https://www.w3.org/TR/UAAG20/#gl-volume-config)
-   [Guideline 1.6 - Synthesized speech
    configuration](https://www.w3.org/TR/UAAG20/#gl-speech-config)
-   [Guideline 1.7 - User style sheet
    configuration](https://www.w3.org/TR/UAAG20/#gl-style-sheets-config)
-   [Guideline 1.9 - Alternative
    views](https://www.w3.org/TR/UAAG20/#gl-alternative-views)
-   [Guideline 1.10 - Element
    Information](https://www.w3.org/TR/UAAG20/#gl-info-link)

**ATAG 2.0**

-   [Principle A.1: Authoring tool user interfaces follow applicable
    accessibility
    guidelines](https://www.w3.org/TR/ATAG20/#principle_a1)
-   [Guideline A.2.2: (For the authoring tool user interface) Ensure
    that editing-view presentation can be programmatically
    determined](https://www.w3.org/TR/ATAG20/#gl_a22)
-   [Guideline A.3.7: (For the authoring tool user interface) Ensure
    that previews are at least as accessible as in-market user
    agents](https://www.w3.org/TR/ATAG20/#gl_b37)
-   [Part B. Support the production of accessible
    content](https://www.w3.org/TR/ATAG20/#part_b)

</div>

{% include excol.html type="end" %}{% include excol.html type="start" %}

#### Histoires d’utilisateurs liées à l’adaptabilité
{:.no_toc}

{% include excol.html type="middle" %}

-   [Lee, client de site Web marchand, daltonien]({{ "/people-use-web/user-stories.fr/" | relative_url }}#shopper)
-   [Alex, journaliste avec un trouble musculosquelettique]({{ "/people-use-web/user-stories.fr/" | relative_url }}#reporter)
-   [Ilya, cadre supérieure, aveugle]({{ "/people-use-web/user-stories.fr/" | relative_url }}#accountant)
-   [Preety, élève de collège avec un trouble du déficit de l'attention avec hyperactivité et dyslexique]({{ "/people-use-web/user-stories.fr/" | relative_url }}#classroomstudent)
-   [Yun, retraité avec une mauvaise vue, un tremblement des mains, et une perte de mémoire à court terme]({{ "/people-use-web/user-stories.fr/" | relative_url }}#retiree)
-   [Luis, assistant en supermarché, atteint du syndrome de Down]({{ "/people-use-web/user-stories.fr/" | relative_url }}#supermarketassistant)
-   [Kaseem, adolescente qui est sourde et aveugle]({{ "/people-use-web/user-stories.fr/" | relative_url }}#teenager)

{% include excol.html type="end" %}

### Content is easier to see and hear {#distinguishable}

Distinguishable content is easier to see and hear. Such content
includes:

-   Color is not used as the only way of conveying information or
    identifying content;
-   Default foreground and background color combinations provide
    sufficient contrast;
-   Text is resizable up to 200% without losing information, using a
    standard browser;
-   Images of text are resizable, replaced with actual text, or avoided
    where possible;
-   Users can pause, stop, or adjust the volume of audio that is played
    on a website;
-   Background audio is low or can be turned off, to avoid interference
    or distraction.

Meeting this requirement helps separate foreground from background, to
make important information more distinguishable. This includes
considerations for people who do not use assistive technologies and for
people using assistive technologies who may observe interference from
prominent audio or visual content in the background. For instance, many
people with color blindness do not use any particular tools and rely on
a proper design that provides sufficient color contrast between text and
its surrounding background. For others, audio that is automatically
played could interfere with text-to-speech or with [assistive listening
devices
(ALDs)](http://www.w3.org/WAI/training/accessible#ald "definition").

{% include excol.html type="start" %}

#### Accessibility requirements related to distinguishability (links to technical specification)
{:.no_toc}

{% include excol.html type="middle" %}

**WCAG 2.0**

-   [Guideline 1.4 -
    Distinguishable](http://www.w3.org/WAI/WCAG20/quickref/#visual-audio-contrast)

**UAAG 2.0**

-   [Guideline 1.3 -
    Highlighting](https://www.w3.org/TR/UAAG20/#gl-interaction-highlight)
-   [Guideline 1.4 - Text
    configuration](https://www.w3.org/TR/UAAG20/#gl-text-config)
-   [Guideline 1.5 - Volume
    configuration](https://www.w3.org/TR/UAAG20/#gl-volume-config)
-   [Guideline 1.6 - Synthesized speech
    configuration](https://www.w3.org/TR/UAAG20/#gl-speech-config)
-   [Guideline 1.7 - User style sheet
    configuration](https://www.w3.org/TR/UAAG20/#gl-style-sheets-config)
-   [Guideline 1.8 - Orientation in
    viewports](https://www.w3.org/TR/UAAG20/#gl-viewport-orient)
-   [Guideline 1.9 - Alternative
    views](https://www.w3.org/TR/UAAG20/#gl-alternative-views)
-   [Guideline 1.10 - Element
    Information](https://www.w3.org/TR/UAAG20/#gl-info-link)

**ATAG 2.0**

-   [Principle A.1: Authoring tool user interfaces follow applicable
    accessibility
    guidelines](https://www.w3.org/TR/ATAG20/#principle_a1)
-   [Guideline A.3.7: (For the authoring tool user interface) Ensure
    that previews are at least as accessible as in-market user
    agents](https://www.w3.org/TR/ATAG20/#gl_b37)
-   [Part B. Support the production of accessible
    content](https://www.w3.org/TR/ATAG20/#part_b)

{% include excol.html type="end" %}{% include excol.html type="start" %}

#### Stories related to distinguishability
{:.no_toc}

{% include excol.html type="middle" %}

-   [Lee, online shopper with color blindness]({{ "/people-use-web/user-stories/" | relative_url }}#shopper)
-   [Martine, online student who is hard of hearing]({{ "/people-use-web/user-stories/" | relative_url }}#onlinestudent)
-   [Ilya, senior staff member who is blind]({{ "/people-use-web/user-stories/" | relative_url }}#accountant)
-   [Yun, retiree with low vision, hand tremor, and mild short-term memory loss]({{ "/people-use-web/user-stories/" | relative_url }}#retiree)
-   [Kaseem, teenager who is deaf and blind]({{ "/people-use-web/user-stories/" | relative_url }}#teenager)

{% include excol.html type="end" %}

Operable user interface and navigation {#operable}
---------------------------------------------------

### Functionality is available from a keyboard {#keyboard}

Many people do not use the mouse and rely on the keyboard to interact
with the Web. This requires keyboard access to all functionality,
including form controls, input, and other user interface components.

Keyboard accessibility includes:

-   All functionality that is available by mouse is also available by
    keyboard;
-   Keyboard focus does not get trapped in any part of the content;
-   Web browsers, authoring tools, and other tools provide keyboard
    support.

Meeting this requirement helps keyboard users, including people using
alternative keyboards such as keyboards with ergonomic layouts,
on-screen keyboards, or switch devices. It also helps people using voice
recognition (speech input) to operate websites and to dictate text
through the keyboard interface.

{% include excol.html type="start" %}

#### Accessibility requirements related to keyboard accessibility (links to technical specification)
{:.no_toc}

{% include excol.html type="middle" %}

**WCAG 2.0**

-   [Guideline 2.1 - Keyboard
    accessible](http://www.w3.org/WAI/WCAG20/quickref/#keyboard-operation)

**UAAG 2.0**

-   [Guideline 2.1 - Keyboard
    access](https://www.w3.org/TR/UAAG20/#gl-keyboard-access)
-   [Guideline 2.2 - Sequential
    navigation](https://www.w3.org/TR/UAAG20/#gl-sequential-navigation)
-   [Guideline 2.3 - Direct navigation and
    activation](https://www.w3.org/TR/UAAG20/#gl-direct-navigation-and-activation)
-   [Guideline 2.11 - Other Input
    Devices](https://www.w3.org/TR/UAAG20/#gl-other-devices)

**ATAG 2.0**

-   [Principle A.1: Authoring tool user interfaces follow applicable
    accessibility
    guidelines](https://www.w3.org/TR/ATAG20/#principle_a1)
-   [Guideline A.3.1: (For the authoring tool user interface) Provide
    keyboard access to authoring
    features](https://www.w3.org/TR/ATAG20/#gl_a31)
-   [Part B. Support the production of accessible
    content](https://www.w3.org/TR/ATAG20/#part_b)

{% include excol.html type="end" %}{% include excol.html type="start" %}

#### Stories related to keyboard accessibility
{:.no_toc}

{% include excol.html type="middle" %}

-   [Alex, reporter with repetitive stress injury]({{ "/people-use-web/user-stories/" | relative_url }}#reporter)
-   [Ilya, senior staff member who is blind]({{ "/people-use-web/user-stories/" | relative_url }}#accountant)

{% include excol.html type="end" %}

### Users have enough time to read and use the content {#time}

Some people need more time than others to read and use the content. For
instance, some people require more time to type text, understand
instructions, operate controls, or to otherwise complete tasks on a
website.

Examples of providing enough time include providing mechanisms to:

-   Stop, extend, or adjust time limits, except where necessary;
-   Pause, stop, or hide moving, blinking, or scrolling content;
-   Postpone or suppress interruptions, except where necessary;
-   Re-authenticate when a session expires without losing data.

{% include excol.html type="start" %}

#### Accessibility requirements related to sufficient time (links to technical specification)
{:.no_toc}

{% include excol.html type="middle" %}

**WCAG 2.0**

-   [Guideline 2.2 - Enough
    time](http://www.w3.org/WAI/WCAG20/quickref/#time-limits)

**UAAG 2.0**

-   [Guideline 2.8 - Time-independent
    interaction](https://www.w3.org/TR/UAAG20/#gl-time-independent)
-   [Guideline 2.10 - Time-based
    media](https://www.w3.org/TR/UAAG20/#gl-control-inaccessible-content)

**ATAG 2.0**

-   [Principle A.1: Authoring tool user interfaces follow applicable
    accessibility
    guidelines](https://www.w3.org/TR/ATAG20/#principle_a1)
-   [Guideline A.3.2: (For the authoring tool user interface) Provide
    authors with enough time](https://www.w3.org/TR/ATAG20/#gl_a32)
-   [Part B. Support the production of accessible
    content](https://www.w3.org/TR/ATAG20/#part_b)

{% include excol.html type="end" %}{% include excol.html type="start" %}

#### Stories related to sufficient time
{:.no_toc}

{% include excol.html type="middle" %}

-   [Alex, reporter with repetitive stress injury]({{ "/people-use-web/user-stories/" | relative_url }}#reporter)
-   [Preety, middle school student with Attention Deficit Hyperactivity Disorder and Dyslexia]({{ "/people-use-web/user-stories/" | relative_url }}#classroomstudent)
-   [Yun, retiree with low vision, hand tremor, and mild short-term memory loss]({{ "/people-use-web/user-stories/" | relative_url }}#retiree)
-   [Luis, supermarket assistant with Down syndrome]({{ "/people-use-web/user-stories/" | relative_url }}#supermarketassistant)
-   [Kaseem, teenager who is deaf and blind]({{ "/people-use-web/user-stories/" | relative_url }}#teenager)

{% include excol.html type="end" %}

### Content does not cause seizures {#safe}

Content that flashes at certain rates or patterns can cause
photosensitive reactions, including seizures. Flashing content is
ideally avoided entirely or only used in a way that does not cause known
risks.

{% include excol.html type="start" %}

#### Accessibility requirements related to seizures (links to technical specification)
{:.no_toc}

{% include excol.html type="middle" %}

**WCAG 2.0**

-   [Guideline 2.3 -
    Seizures](http://www.w3.org/WAI/WCAG20/quickref/#seizure)

**UAAG 2.0**

-   [Guideline 2.9 -
    Flashing](https://www.w3.org/TR/UAAG20/#gl-prevent-flash)

**ATAG 2.0**

-   [Principle A.1: Authoring tool user interfaces follow applicable
    accessibility
    guidelines](https://www.w3.org/TR/ATAG20/#principle_a1)
-   [Guideline A.3.3: (For the authoring tool user interface) Help
    authors avoid flashing that could cause
    seizures](https://www.w3.org/TR/ATAG20/#gl_a33)
-   [Part B. Support the production of accessible
    content](https://www.w3.org/TR/ATAG20/#part_b)

{% include excol.html type="end" %}

### Users can easily navigate, find content, and determine where they are {#navigable}

Well organized content helps users to orient themselves and to navigate
effectively. Such content includes:

-   Pages have clear titles and are organized using descriptive section
    headings;
-   There is more than one way to find relevant pages within a set of
    web pages;
-   Users are informed about their current location within a set of
    related pages;
-   There are ways to bypass blocks of content that are repeated on
    multiple pages;
-   The keyboard focus is visible, and the focus order follows a
    meaningful sequence;
-   The purpose of a link is evident, ideally even when the link is
    viewed on its own.

Meeting this requirement helps people to navigate through web pages in
different ways, depending on their particular needs and preferences. For
instance, while some people rely on hierarchical navigation structures
such as menu bars to find specific web pages, others rely on search
functions on websites instead. Some people may be seeing the content
while others may be hearing it or seeing and hearing it at the same
time. Some people may be using the content with only a mouse or a
keyboard, while others may be using both.

{% include excol.html type="start" %}

#### Accessibility requirements related to navigation (links to technical specification)
{:.no_toc}

{% include excol.html type="middle" %}

**WCAG 2.0**

-   [Guideline 2.4 -
    Navigable](http://www.w3.org/WAI/WCAG20/quickref/#navigation-mechanisms)

**UAAG 2.0**

-   [Guideline 2.2 - Sequential
    navigation](https://www.w3.org/TR/UAAG20/#gl-sequential-navigation)
-   [Guideline 2.3 - Direct navigation and
    activation](https://www.w3.org/TR/UAAG20/#gl-direct-navigation-and-activation)
-   [Guideline 2.4 - Text
    search](https://www.w3.org/TR/UAAG20/#gl-search-text)
-   [Guideline 2.5 - Structural
    navigation](https://www.w3.org/TR/UAAG20/#gl-nav-structure)
-   [Guideline 2.7 - Graphical
    controls](https://www.w3.org/TR/UAAG20/#gl-configure-controls)

**ATAG 2.0**

-   [Principle A.1: Authoring tool user interfaces follow applicable
    accessibility
    guidelines](https://www.w3.org/TR/ATAG20/#principle_a1)
-   [Guideline A.2.2: (For the authoring tool user interface) Ensure
    that editing-view presentation can be programmatically
    determined](https://www.w3.org/TR/ATAG20/#gl_a22)
-   [Guideline A.3.4: (For the authoring tool user interface) Enhance
    navigation and editing via content
    structure](https://www.w3.org/TR/ATAG20/#gl_a34)
-   [Guideline A.3.5: (For the authoring tool user interface) Provide
    text search of the content](https://www.w3.org/TR/ATAG20/#gl_a35)
-   [Part B. Support the production of accessible
    content](https://www.w3.org/TR/ATAG20/#part_b)

{% include excol.html type="end" %}{% include excol.html type="start" %}

#### Stories related to navigation
{:.no_toc}

{% include excol.html type="middle" %}

-   [Alex, reporter with repetitive stress injury]({{ "/people-use-web/user-stories/" | relative_url }}#reporter)
-   [Ilya, senior staff member who is blind]({{ "/people-use-web/user-stories/" | relative_url }}#accountant)
-   [Preety, middle school student with Attention Deficit Hyperactivity Disorder and Dyslexia]({{ "/people-use-web/user-stories/" | relative_url }}#classroomstudent)
-   [Yun, retiree with low vision, hand tremor, and mild short-term memory loss]({{ "/people-use-web/user-stories/" | relative_url }}#retiree)
-   [Luis, supermarket assistant with Down syndrome]({{ "/people-use-web/user-stories/" | relative_url }}#supermarketassistant)
-   [Kaseem, teenager who is deaf and blind]({{ "/people-use-web/user-stories/" | relative_url }}#teenager)

{% include excol.html type="end" %}

Understandable information and user interface {#understandable}
----------------------------------------------------------------

### Text is readable and understandable {#readable}

Content authors need to ensure that text content is readable and
understandable to the broadest audience possible, including when it is
read aloud by text-to-speech. Such content includes:

-   Identifying the primary language of a web page, such as Arabic,
    Dutch, or Korean;
-   Identifying the language of text passages, phrases, or other parts
    of a web page;
-   Providing definitions for any unusual words, phrases, idioms, and
    abbreviations;
-   Using the clearest and simplest language possible, or providing
    simplified versions.

Meeting this requirement helps software, including assistive technology,
to process text content correctly. For instance, this requirement helps
software to read the content aloud, to generate page summaries, and to
provide definitions for unusual words such as technical jargon. It also
helps people who have difficulty understanding more complex sentences,
phrases, and vocabulary. In particular, it helps people with different
types of cognitive disabilities.

{% include excol.html type="start" %}

#### Accessibility requirements related to readability (links to technical specification)
{:.no_toc}

{% include excol.html type="middle" %}

**WCAG 2.0**

-   [Guideline 3.1 -
    Readable](http://www.w3.org/WAI/WCAG20/quickref/#meaning)

**ATAG 2.0**

-   [Principle A.1: Authoring tool user interfaces follow applicable
    accessibility
    guidelines](https://www.w3.org/TR/ATAG20/#principle_a1)
-   [Guideline A.4.2: (For the authoring tool user interface) Document
    the user interface, including all accessibility
    features](https://www.w3.org/TR/ATAG20/#gl_b42)
-   [Part B. Support the production of accessible
    content](https://www.w3.org/TR/ATAG20/#part_b)

{% include excol.html type="end" %}{% include excol.html type="start" %}

#### Stories related to readability
{:.no_toc}

{% include excol.html type="middle" %}

-   [Martine, online student who is hard of hearing]({{ "/people-use-web/user-stories/" | relative_url }}#onlinestudent)
-   [Ilya, senior staff member who is blind]({{ "/people-use-web/user-stories/" | relative_url }}#accountant)
-   [Preety, middle school student with Attention Deficit Hyperactivity Disorder and Dyslexia]({{ "/people-use-web/user-stories/" | relative_url }}#classroomstudent)
-   [Yun, retiree with low vision, hand tremor, and mild short-term memory loss]({{ "/people-use-web/user-stories/" | relative_url }}#retiree)
-   [Luis, supermarket assistant with Down syndrome]({{ "/people-use-web/user-stories/" | relative_url }}#supermarketassistant)

{% include excol.html type="end" %}

### Content appears and operates in predictable ways {#predictable}

Many people rely on predictable user interfaces and are disoriented or
distracted by inconsistent appearance or behavior. Examples of making
content more predictable include:

-   Navigation mechanisms that are repeated on multiple pages appear in
    the same place each time;
-   User interface components that are repeated on web pages have the
    same labels each time;
-   Significant changes on a web page do not happen without the consent
    of the user.

Meeting this requirement helps people to quickly learn the functionality
and navigation mechanisms provided on a website, and to operate them
according to their specific needs and preferences. For instance, some
people assign personalized shortcut keys to functions they frequently
use to enhance keyboard navigation. Others memorize the steps to reach
certain pages or to complete processes on a website. Both rely on
predictable and consistent functionality.

{% include excol.html type="start" %}

#### Accessibility requirements related to predictability (links to technical specification)
{:.no_toc}

{% include excol.html type="middle" %}

**WCAG 2.0**

-   [Guideline 3.2 -
    Predictable](http://www.w3.org/WAI/WCAG20/quickref/#consistent-behavior)

**UAAG 2.0**

-   [Guideline 3.3 -
    Predictable](https://www.w3.org/TR/UAAG20/#gl-predictable-operation)

**ATAG 2.0**

-   [Principle A.1: Authoring tool user interfaces follow applicable
    accessibility
    guidelines](https://www.w3.org/TR/ATAG20/#principle_a1)
-   [Guideline A.2.2: (For the authoring tool user interface) Ensure
    that editing-view presentation can be programmatically
    determined](https://www.w3.org/TR/ATAG20/#gl_a22)
-   [Guideline A.4.2: (For the authoring tool user interface) Document
    the user interface, including all accessibility
    features](https://www.w3.org/TR/ATAG20/#gl_b42)
-   [Part B. Support the production of accessible
    content](https://www.w3.org/TR/ATAG20/#part_b)

{% include excol.html type="end" %}{% include excol.html type="start" %}

#### Stories related to predictability
{:.no_toc}

{% include excol.html type="middle" %}

-   [Alex, reporter with repetitive stress injury]({{ "/people-use-web/user-stories/" | relative_url }}#reporter)
-   [Ilya, senior staff member who is blind]({{ "/people-use-web/user-stories/" | relative_url }}#accountant)
-   [Preety, middle school student with Attention Deficit Hyperactivity Disorder and Dyslexia]({{ "/people-use-web/user-stories/" | relative_url }}#classroomstudent)
-   [Yun, retiree with low vision, hand tremor, and mild short-term memory loss]({{ "/people-use-web/user-stories/" | relative_url }}#retiree)
-   [Luis, supermarket assistant with Down syndrome]({{ "/people-use-web/user-stories/" | relative_url }}#supermarketassistant)
-   [Kaseem, teenager who is deaf and blind]({{ "/people-use-web/user-stories/" | relative_url }}#teenager)

{% include excol.html type="end" %}

### Users are helped to avoid and correct mistakes {#tolerant}

Forms and other interaction can be confusing or difficult to use for
many people, and, as a result, they may be more likely to make mistakes.
Examples of helping users to avoid and correct mistakes include:

-   Descriptive instructions, error messages, and suggestions for
    correction;
-   Context-sensitive help for more complex functionality and
    interaction;
-   Opportunity to review, correct, or reverse submissions if necessary.

Meeting this requirement helps people who do not see or hear the
content, and may not recognize implicit relationships, sequences, and
other cues. It also helps people who do not understand the
functionality, are disoriented or confused, forget, or make mistakes
using forms and interaction for any other reason.

{% include excol.html type="start" %}

#### Accessibility requirements related to input assistance (links to technical specification)
{:.no_toc}

{% include excol.html type="middle" %}

**WCAG 2.0**

-   [Guideline 3.3 - Input
    assistance](http://www.w3.org/WAI/WCAG20/quickref/#minimize-error)

**UAAG 2.0**

-   [Guideline 3.1 -
    Mistakes](https://www.w3.org/TR/UAAG20/#gl-avoid-mistakes)

**ATAG 2.0**

-   [Principle A.1: Authoring tool user interfaces follow applicable
    accessibility
    guidelines](https://www.w3.org/TR/ATAG20/#principle_a1)
-   [Guideline A.2.2: (For the authoring tool user interface) Ensure
    that editing-view presentation can be programmatically
    determined](https://www.w3.org/TR/ATAG20/#gl_a22)
-   [Guideline A.4.1: (For the authoring tool user interface) Help
    authors avoid and correct
    mistakes](https://www.w3.org/TR/ATAG20/#gl_b41)
-   [Part B. Support the production of accessible
    content](https://www.w3.org/TR/ATAG20/#part_b)

{% include excol.html type="end" %}{% include excol.html type="start" %}

#### Stories related to input assistance
{:.no_toc}

{% include excol.html type="middle" %}

-   [Lee, online shopper with color blindness]({{ "/people-use-web/user-stories/" | relative_url }}#shopper)
-   [Alex, reporter with repetitive stress injury]({{ "/people-use-web/user-stories/" | relative_url }}#reporter)
-   [Preety, middle school student with Attention Deficit Hyperactivity Disorder and Dyslexia]({{ "/people-use-web/user-stories/" | relative_url }}#classroomstudent)
-   [Yun, retiree with low vision, hand tremor, and mild short-term memory loss]({{ "/people-use-web/user-stories/" | relative_url }}#retiree)
-   [Luis, supermarket assistant with Down syndrome]({{ "/people-use-web/user-stories/" | relative_url }}#supermarketassistant)

{% include excol.html type="end" %}

Robust content and reliable interpretation {#robust}
-----------------------------------------------------

### Content is compatible with current and future user tools {#compatible}

Robust content is compatible with different browsers, assistive
technologies, and other user agents. Examples of how this can be
achieved include:

-   Ensuring markup can be reliably interpreted, for instance by
    ensuring it is valid;
-   Providing a name, role, and value for non-standard user interface
    components.

Meeting this requirement helps maximize compatibility with current and
future user agents, including assistive technologies. In particular, it
enables assistive technologies to process the content reliably, and to
present or to operate it in different ways. This includes non-standard
(scripted) buttons, input fields, and other controls.

{% include excol.html type="start" %}

#### Accessibility requirements related to compatibility (links to technical specification)
{:.no_toc}

{% include excol.html type="middle" %}

**WCAG 2.0**

-   [Guideline 4.1 -
    Compatible](http://www.w3.org/WAI/WCAG20/quickref/#ensure-compat)

**UAAG 2.0**

-   [Guideline 2.6 - Preference
    settings](https://www.w3.org/TR/UAAG20/#gl-store-prefs)
-   [Guideline 4.1 - Assistive
    technology](https://www.w3.org/TR/UAAG20/#gl-AT-access)
-   [Guideline 5.1 - Follow
    specifications](https://www.w3.org/TR/UAAG20/#gl-obs-env-conventions)

**ATAG 2.0**

-   [Principle A.1: Authoring tool user interfaces follow applicable
    accessibility
    guidelines](https://www.w3.org/TR/ATAG20/#principle_a1)
-   [Part B. Support the production of accessible
    content](https://www.w3.org/TR/ATAG20/#part_b)

{% include excol.html type="end" %}{% include excol.html type="start" %}

#### Stories related to compatibility
{:.no_toc}

{% include excol.html type="middle" %}

-   [Lee, online shopper with color blindness]({{ "/people-use-web/user-stories/" | relative_url }}#shopper)
-   [Alex, reporter with repetitive stress injury]({{ "/people-use-web/user-stories/" | relative_url }}#reporter)
-   [Ilya, senior staff member who is blind]({{ "/people-use-web/user-stories/" | relative_url }}#accountant)
-   [Preety, middle school student with Attention Deficit Hyperactivity Disorder and Dyslexia]({{ "/people-use-web/user-stories/" | relative_url }}#classroomstudent)
-   [Luis, supermarket assistant with Down syndrome]({{ "/people-use-web/user-stories/" | relative_url }}#supermarketassistant)
-   [Kaseem, teenager who is deaf and blind]({{ "/people-use-web/user-stories/" | relative_url }}#teenager)

{% include excol.html type="end" %}

{% include excol.html type="all" %}
