---
# Translation instructions are after the "#" character in this first section. They are comments that do not show up in the web page. You do not need to translate the instructions after #.

title: Zásady přístupnosti   # Do not translate "title:". Do translate the text after "title:".
nav_title: "Zásady přístupnosti"   # A short title that is used in the navigation

lang: cs   # Change "en" to the translated language shortcode from https://www.iana.org/assignments/language-subtag-registry/language-subtag-registry

last_updated: 2020-11-20   # Put the date of this translation YYYY-MM-DD (with month in the middle)
translators: 
- name: "Kristýna Švecová"   # Replace @@ with translator name
# - name: "@@"   # Replace @@ with name, or delete this line if not multiple translators
# contributors:
# - name: "@@"   # Replace @@ with contributor name, or delete this line if none
# - name: "@@"   # Replace @@ with name, or delete this line if not multiple contributors

ref: /fundamentals/accessibility-principles/   # Do not change this
layout: default
github:
  repository: w3c/wai-accessibility-principles
  path: content/index.cs.md   # Add the language shortcode to the middle of the filename, for example index.fr.md
permalink: /fundamentals/accessibility-principles/cs   # Add the language shortcode to the end; for example /fundamentals/accessibility-principles/fr

description: Přehled základních požadavků na webovou přístupnost pro webové stránky, webové aplikace, prohlížeče a další nástroje.   # translate this sentence
image: /content-images/wai-accessibility-principles/social.png

teaser_text: Stránka Zásady přístupnosti představuje některé požadavky na přístupnost webu pro webové stránky, webové aplikace, prohlížeče a další nástroje. Poskytuje odkazy na mezinárodní standardy z Iniciativy pro webovou přístupnost W3C (WAI) a na příběhy uživatelů webu.

footer: >   # Translate all the words below, including "Date:", "Editor:", Updated, and the month. Do not change these dates.
  <p><strong>Datum:</strong> Aktualizováno 10. května 2019. CHANGELOG</p>
  <p><strong>Editoři:</strong> <a href="https://www.w3.org/People/shadi/">Shadi Abou Zahra</a>. <a href="https://www.w3.org/WAI/intro/people-use-web/acknowledgments">Poděkování</a>.</p>
  <p>Vyvinuto Pracovní skupinou pro vzdělání a osvětu (<a href="http://www.w3.org/WAI/EO/">EOWG</a>). Dříve vyvinuto s Pracovní skupinou <a href="https://www.w3.org/WAI/EO/2008/wai-age-tf">WAI-AGE</a> za podpory Projektu <a href="https://www.w3.org/WAI/WAI-AGE/">WAI-AGE</a>.</p>

changelog: /fundamentals/accessibility-principles/changelog/

# Read Important Translations Guidance at https://www.w3.org/WAI/about/translating/#important
# Read Translations Notes for this resource at https://github.com/w3c/wai-accessibility-principles/blob/master/README.md
# end of translation instructions
---


{::nomarkdown}
{% include box.html type="start" h="2" title="Shrnutí" class="full" %}
{:/}

Tato stránka představuje některé požadavky na přístupnost webu pro webové stránky, webové aplikace, prohlížeče a další nástroje. Poskytuje odkazy na mezinárodní standardy z Iniciativy pro webovou přístupnost W3C (WAI) a na [příběhy uživatelů webu](/people-use-web/user-stories/).

**Poznámka:** Toto není kompletní seznam všech požadavků na přístupnost.

{::nomarkdown}
{% include box.html type="end" %}
{:/}


{::options toc_levels="2,3" /}

{::nomarkdown}
{% include_cached toc.html type="start" title="Obsah stránky" class="full" %}
{:/}

-   TOC is created automatically.
{:toc}

{::nomarkdown}
{% include_cached toc.html type="end" %}
{:/}


{% include excol.html type="all" %}

## Standardy webové přístupnosti {#standards}

Webová přístupnost spoléhá na několik komponent, které spolupracují. Některé z nich zahrnují:

-   **Obsah webu**{:#webcontent} - jakákoliv část webové stránky, která obsahuje text, obrázky, formuláře a multimédia, stejně tak markup kód, skripty, aplikace a další.
-   **Uživatelské agenty**{:#useragents} - software, který lidé používají pro přístup k webovému obsahu. Jedná se o grafické prohlížeče pro PC, hlasové prohlížeče, mobilní prohlížeče, přehrávače multimédií, pluginy a některé [kompenzační pomůcky](/people-use-web/tools-techniques/#at "definition").
-   **Vývojové nástroje**{:#authoringtools} - software nebo služby, které se používají k tvorbě webového obsahu, včetně editorů kódu, nástrojů pro převod dokumentů, systémů pro správu obsahu, blogů, databázových skriptů a dalších.

{% include excol.html type="start" %}

### Další informace o standardech webové přístupnosti
{:.no_toc}

{% include excol.html type="middle" %}

Výše zmíněné komponenty jsou vzájemně propojeny a vzájemně se podporují. Například **webový obsah** musí zahrnovat textové alternativy pro obrázky. Tato informace musí být zpracována **webovými prohlížeči** a předána **asistenčním technologiím**, například čtečkám obrazovky. Autoři potřebují **vývojové nástroje**, které jim umožní tvorbu těchto textových alternativ. Více informací je v [[Základních komponentech webové přístupnosti]](/fundamentals/components/).

Standardy hrají zásadní roli v definování požadavků na přístupnost pro každý z těchto komponentů. Splnění některých požadavků na přístupnost je jednoduché, přesto porozumnění základů, jak osoby se zdravotním postižením používají Web, pomáhá tyto požadavky splnit efektivněji. Některé aspekty přístupnosti vyžadují více technických dovedností nebo pokročilé znalosti toho, jak lidé používají Web. V každém případě [zapojení uživatelů ze začátku a během projektů](/test-evaluate/involving-users/) zlepší a usnadní vaši práci.

Iniciativa pro webovou přístupnost W3C (WAI) poskytuje soubor pokynů, které jsou mezinárodně uznávány jako standard pro webovou přístupnost. Tyto zahrnují:

-   **[Pokyny pro zpřístupnění obsahu webu (WCAG)](/standards-guidelines/wcag/)**
-   **[Pokyny k uživatelským agentům (UAAG)](/standards-guidelines/uaag/)**
-   **[Pokyny pro zpřístupnění vývojových nástrojů (ATAG)](/standards-guidelines/atag/)**

K dispozici jsou také WAI specifikace pro **[Přístupné internetové aplikace (WAI-ARIA)](https://www.w3.org/WAI/intro/aria.php)**, které zahrnují dynamický obsah a pokročilé ovládací prvky uživatelského rozhraní vyvinuté s použitím Ajaxu, JavaScriptu a souvisejících webových technologií.

{% include excol.html type="end" %}

## Vnímatelné informace a uživatelské rozhraní {#perceivable}

### Textové alternativy pro netextový obsah {#alternatives}

Textové alternativy jsou ekvivalenty pro netextový obsah. Mezi příklady patří:

-   Krátké alternativy pro obrázky, včetně ikon, tlačítek a grafického obsahu
-   Popis dat znázorněných v grafech, diagramech a ilustracích
-   Krátký popis netextového obsahu jako audio a video souborů
-   Popisky pro ovládací prvky formulářů, vstupů a dalších komponent uživatelského rozhraní

Textové alternativy vyjadřují význam obrázku nebo pomáhají poskytnout srovnatelný uživatelský prožitek. Například vhodná textová alternativa pro tlačítko vyhladávání je "*vyhledat*", ne "*lupa*".

Textové alternativy lze prezentovat různými způsoby. Například mohou být nahlas přečteny pro uživatele, kteří nevidí obrazovku a pro lidi s obtížemi při čtení. Mohou být zvětšeny na vlastní velikost textu nebo zobrazeny na braillských zařízeních. Textové alternativy slouží jako popisky pro ovládácí prvky a funkce pro usnadnění navigace pomocí klávesnice a navigace pomocí rozpoznávání hlasu (hlasový vstup). Také slouží jako popisky pro audio, video a další formáty. Mohou také popisovat aplikace, které jsou vloženy jako součást webové stránky.

{% include excol.html type="start" %}

#### Požadavky na přístupnost související s textovými alternativami (odkazy na technické specifikace)
{:.no_toc}

{% include excol.html type="middle" %}

**WCAG**

-   [Pokyn 1.1 - Textové alternativy](https://www.w3.org/WAI/WCAG21/quickref/#text-alternatives)

**UAAG**

-   [Pokyn 1.1 - Alternativní obsah](https://www.w3.org/TR/UAAG20/#gl-access-alternative-content)

**ATAG**

-   [Princip A.1: Uživatelská rozhraní nástrojů pro tvorbu se řídí příslušnými pokyny pro přístupnost](https://www.w3.org/TR/ATAG20/#principle_a1)
-   [Pokyn A.2.1: (Pro uživatelské rozhraní nástrojů pro tvorbu) Zpřístupněte autorům alternativní obsah](https://www.w3.org/TR/ATAG20/#gl_a21)
-   [Pokyn A.2.2: (Pro uživatelské rozhraní nástrojů pro tvorbu) Zajistěte, aby bylo možné programově určit zobrazení pro úpravy](https://www.w3.org/TR/ATAG20/#gl_a22)
-   [Pokyn A.3.7: (Pro uživatelské rozhraní nástrojů pro tvorbu) Zajistěte, aby náhledy byly přinejmenším stejně přístupné jako v běžných uživatelských agentech](https://www.w3.org/TR/ATAG20/#gl_a37)
-   [Část B. Podporujte tvorbu přístupného obsahu](https://www.w3.org/TR/ATAG20/#part_b)

{% include excol.html type="end" %}

{% include excol.html type="start" %}

#### Příběhy související s textovými alternativami
{:#stories-related-to-text-alternatives.no_toc}

{% include excol.html type="middle" %}

-   [Alex, reportér s poškozením z opakovaného namáhání](/people-use-web/user-stories/#reporter)
-   [Martine, online studentka, která špatně slyší](/people-use-web/user-stories/#onlinestudent)
-   [Ilya, vedoucí pracovnice, která je slepá](/people-use-web/user-stories/#accountant)
-   [Preety, studentka střední školy s poruchou pozornosti, hyperaktivitou a dislexií](/people-use-web/user-stories/#classroomstudent)
-   [Yun, důchodce se slabým zrakem, třesem rukou a mírnou ztrátou krátkodobé paměti](/people-use-web/user-stories/#retiree)
-   [Kaseem, teenagerka, která je hluchá a slepá](/people-use-web/user-stories/#teenager)

{% include excol.html type="end" %}

### Titulky a další alternativy pro multimédia {#captions}

Osoby, které neslyší audio nebo nevidí video potřebují alternativy. Například:

-   Textové přepisy a titulky pro audio, jako třeba nahrávky rozhlasových rozhovorů
-   Audio popis líčí důležité vizuální detaily ve videu
-   Znaková řeč pro audio včetně důležitých sluchových prožitků

Dobře napsané textové přepisy, které obsahují správnou posloupnost všech zvukových a vizuálních informací, poskytují základní úroveň přístupnosti a usnadňují tvorbu titulků a audio popisů.

{% include excol.html type="start" %}

#### Požadavky na přístupnost související s multimédii (odkazy na technické specifikace)
{:.no_toc}

{% include excol.html type="middle" %}

**WCAG**

-   [Pokyn 1.2 - Média závisející na času](https://www.w3.org/WAI/WCAG21/quickref/#time-based-media)

**UAAG**

-   [Pokyn 1.1 - Alternativní obsah](https://www.w3.org/TR/UAAG20/#gl-access-alternative-content)

**ATAG**

-   [Princip A.1: Uživatelská rozhraní nástrojů pro tvorbu se řídí příslušnými pokyny pro přístupnost](https://www.w3.org/TR/ATAG20/#principle_a1)
-   [Pokyn A.2.1: (Pro uživatelské rozhraní nástrojů pro tvorbu) Zpřístupněte autorům alternativní obsah](https://www.w3.org/TR/ATAG20/#gl_a21)
-   [Pokyn A.3.7: (Pro uživatelské rozhraní nástrojů pro tvorbu) Zajistěte, aby náhledy byly přinejmenším stejně přístupné jako v běžných uživatelských agentech](https://www.w3.org/TR/ATAG20/#gl_a37)
-   [Část B. Podporujte tvorbu přístupného obsahu](https://www.w3.org/TR/ATAG20/#part_b)

{% include excol.html type="end" %}
{% include excol.html type="start" %}

#### Příběhy související s multimédii {#stories-related-to-multimedia}
{:.no_toc}

{% include excol.html type="middle" %}

-   [Martine, online studentka, která špatně slyší](/people-use-web/user-stories/#onlinestudent)
-   [Ilya, vedoucí pracovnice, která je slepá](/people-use-web/user-stories/#accountant)
-   [Kaseem, teenagerka, která je hluchá a slepá](/people-use-web/user-stories/#teenager)

{% include excol.html type="end" %}

### Obsah lze prezentovat různými způsoby {#adaptable}

Aby uživatelé mohli změnit prezentaci obsahu, je nutné aby:

-   nadpisy, seznamy, tabulky, vstupní políčka a struktury obsahu byly správně označeny
-   pořadí informací a instrukcí nezáleželo na prezentaci
-   prohlížeče a asistenční technologie poskytovaly nastavení pro přizpůsobení prezentace

Splnění tohoto požadavku umožňuje správné čtení obsahu nahlas, zvětšení nebo přizpůsobení tak, aby vyhovovalo potřebám a preferencím různých lidí. Obsah může být například prezentován pomocí vlastních barevných kombinací, velikosti textu nebo jiných úplrav vzhledu, které usnadní čtení. Tento požadavek také usnadňuje další formy přizpůsobení, včetně automatického generování obrysů a souhrnů stránek, které lidem pomohou získat přehled a snadněji se zaměřit na konkrétní části.

{% include excol.html type="start" %}

#### Požadavky na přístupnost související s přizpůsobivostí (odkazy na technické specifikace)
{:.no_toc}

{% include excol.html type="middle" %}

**WCAG**

-   [Pokyn 1.3 - Přizpůsobivost](https://www.w3.org/WAI/WCAG21/quickref/#adaptable)

**UAAG**

-   [Pokyn 1.4 - Konfigurace textu](https://www.w3.org/TR/UAAG20/#gl-text-config)
-   [Pokyn 1.5 - Konfigurace hlasitosti](https://www.w3.org/TR/UAAG20/#gl-volume-config)
-   [Pokyn 1.6 - Konfigurace syntetizované řeči](https://www.w3.org/TR/UAAG20/#gl-speech-config)
-   [Pokyn 1.7 - Konfigurace šablony stylů uživatele](https://www.w3.org/TR/UAAG20/#gl-style-sheets-config)
-   [Pokyn 1.9 - Alternativní zobrazení](https://www.w3.org/TR/UAAG20/#gl-alternative-views)
-   [Pokyn 1.10 - Informace o elementech](https://www.w3.org/TR/UAAG20/#gl-info-link)

**ATAG**

-   [Princip A.1: Uživatelská rozhraní nástrojů pro tvorbu se řídí příslušnými pokyny pro přístupnost](https://www.w3.org/TR/ATAG20/#principle_a1)
-   [Pokyn A.2.2: (Pro uživatelské rozhraní nástrojů pro tvorbu) Zajistěte, aby bylo možné programově určit zobrazení pro úpravy](https://www.w3.org/TR/ATAG20/#gl_a22)
-   [Pokyn A.3.7: (Pro uživatelské rozhraní nástrojů pro tvorbu) Zajistěte, aby náhledy byly přinejmenším stejně přístupné jako v běžných uživatelských agentech](https://www.w3.org/TR/ATAG20/#gl_a37)
-   [Část B. Podporujte tvorbu přístupného obsahu](https://www.w3.org/TR/ATAG20/#part_b)

{% include excol.html type="end" %}{% include excol.html type="start" %}

#### Příběhy související s přizpůsobivostí
{:.no_toc}

{% include excol.html type="middle" %}

-   [Lee, online nakupující, který je barvoslepý](/people-use-web/user-stories/#shopper)
-   [Alex, reportér s poškozením z opakovaného namáhání](/people-use-web/user-stories/#reporter)
-   [Ilya, vedoucí pracovnice, která je slepá](/people-use-web/user-stories/#accountant)
-   [Preety, studentka střední školy s poruchou pozornosti, hyperaktivitou a dislexií](/people-use-web/user-stories/#classroomstudent)
-   [Yun, důchodce se slabým zrakem, třesem rukou a mírnou ztrátou krátkodobé paměti](/people-use-web/user-stories/#retiree)
-   [Luis, asistent v supermarketu s Downovým syndromem](/people-use-web/user-stories/#supermarketassistant)
-   [Kaseem, teenagerka, která je hluchá a slepá](/people-use-web/user-stories/#teenager)

{% include excol.html type="end" %}

### Obsah je lépe vidět a slyšet {#distinguishable}

Rozlišitelný obsah je lépe vidět a slyšet. Příklady takového obsahu jsou:

-   Barva není jediný nositel informace nebo identifikátor obsahu
-   Výchozí kombinace barvy popředí a pozadí má dostatečný barevný kontrast
-   Pokud uživatel zvětší text na 400% nebo změní velikost řádkování, žádné informace nejsou ztraceny
-   Přeformátování textu v malých oknech („výřezech“) a při zvětšení textu uživatelem
-   U obrázků textu lze změnit velikost, nahradit je textem nebo se jim pokud možno vyhnout
-   Uživatel může pozastavit, zastavit nebo změnit hlasitost zvuku, který hraje na webové stránce
-   Audio na pozadí je potichu a je možné ho vypnout, aby nerušilo nebo nerozptylovalo uživatele

Splnění tohoto požadavku pomáhá oddělit popředí od pozadí, takže jsou důležité informace lépe rozlišitelné. Toto má vliv jak na osoby, co nepoužívají asistenční technologie, tak na ty, kteří je používají. Ti mohou vnímat rušení, pokud je v pozadí výrazný audio nebo vizuální obsah. Například mnoho lidí s barvoslepostí nepoužívá určité nástroje a spoléhají se na vlastní design, který má dostatečný barevný kontrast mezi textem a jeho pozadím. Pro ostatní může zvuk na pozadí rušit převod textu na řeč nebo [asistenční zařízení pro slyšení (ALDs)](http://www.w3.org/WAI/training/accessible#ald "definition").

{% include excol.html type="start" %}

#### Požadavky na přístupnost související s rozlišitelností (odkazy na technické specifikace)
{:.no_toc}

{% include excol.html type="middle" %}

**WCAG**

-   [Pokyn 1.4 - Rozlišitelnost](https://www.w3.org/WAI/WCAG21/quickref/#distinguishable)

**UAAG**

-   [Pokyn 1.3 - Zvýraznění](https://www.w3.org/TR/UAAG20/#gl-interaction-highlight)
-   [Pokyn 1.4 - Konfigurace textu](https://www.w3.org/TR/UAAG20/#gl-text-config)
-   [Pokyn 1.5 - Konfigurace hlasitosti](https://www.w3.org/TR/UAAG20/#gl-volume-config)
-   [Pokyn 1.6 - Konfigurace syntetizované řeči](https://www.w3.org/TR/UAAG20/#gl-speech-config)
-   [Pokyn 1.7 - Konfigurace šablony stylů uživatele](https://www.w3.org/TR/UAAG20/#gl-style-sheets-config)
-   [Pokyn 1.8 - Orientation in viewports](https://www.w3.org/TR/UAAG20/#gl-viewport-orient)
-   [Pokyn 1.9 - Alternativní zobrazení](https://www.w3.org/TR/UAAG20/#gl-alternative-views)
-   [Pokyn 1.10 - Informace o elementech](https://www.w3.org/TR/UAAG20/#gl-info-link)

**ATAG**

-   [Princip A.1: Uživatelská rozhraní nástrojů pro tvorbu se řídí příslušnými pokyny pro přístupnost](https://www.w3.org/TR/ATAG20/#principle_a1)
-   [Pokyn A.3.7: (Pro uživatelské rozhraní nástrojů pro tvorbu) Zajistěte, aby náhledy byly přinejmenším stejně přístupné jako v běžných uživatelských agentech](https://www.w3.org/TR/ATAG20/#gl_a37)
-   [Část B. Podporujte tvorbu přístupného obsahu](https://www.w3.org/TR/ATAG20/#part_b)

{% include excol.html type="end" %}{% include excol.html type="start" %}

#### Příběhy související s rozlišitelností
{:.no_toc}

{% include excol.html type="middle" %}

-   [Lee, online nakupující, který je barvoslepý](/people-use-web/user-stories/#shopper)
-   [Martine, online student who is hard of hearing](/people-use-web/user-stories/#onlinestudent)
-   [Ilya, vedoucí pracovnice, která je slepá](/people-use-web/user-stories/#accountant)
-   [Yun, důchodce se slabým zrakem, třesem rukou a mírnou ztrátou krátkodobé paměti](/people-use-web/user-stories/#retiree)
-   [Kaseem, teenagerka, která je hluchá a slepá](/people-use-web/user-stories/#teenager)

{% include excol.html type="end" %}

## Ovladatelné uživatelské rozhraní a navigace  {#operable}

### Funkce jsou dostupné klávesnicí {#keyboard}

Mnoho lidí pro interakci s webem nepoužívá myš, ale spoléhá na klávesnici. To vyžaduje přístup ke všem funkcím z klávesnice, včetně ovládacích prvků formulářů, vstupů a dalších komponent uživatelského rozhraní.

Přístupnost klávesnice zahrnuje:

-   Všechny funkce, které jsou dostupné myší jsou také dostupné klávesnicí
-   Focus klávesnice neuvízne v žádné části obsahu
-   Webové prohlížeče, nástroje pro tvorbu a další nástroje podporují ovládání klávesnicí

Splnění tohoto požadavku pomáhá uživatelům klávesnice včetně osob, které používají alternativní klávesnice jako třeba klávesnice s ergonomických rozložením, klávesnice na obrazovce nebo tlačítková zářízení. Také pomáhá osobám, které používají rozpoznávání hlasu (hlasový vstup) k ovládání webových stránek a k diktování textu použitím klávesnice.

{% include excol.html type="start" %}

#### Požadavky na přístupnost související s přístupností z klávesnice (odkazy na technické specifikace)
{:.no_toc}

{% include excol.html type="middle" %}

**WCAG**

-   [Pokyn 2.1 - Přístupnost z klávesnice](https://www.w3.org/WAI/WCAG21/quickref/#keyboard-accessible)

**UAAG**

-   [Pokyn 2.1 - Přístup z klávesnice](https://www.w3.org/TR/UAAG20/#gl-keyboard-access)
-   [Pokyn 2.2 - Sekvenční navigace](https://www.w3.org/TR/UAAG20/#gl-sequential-navigation)
-   [Pokyn 2.3 - Přímá navigace a aktivace](https://www.w3.org/TR/UAAG20/#gl-direct-navigation-and-activation)
-   [Pokyn 2.11 - Další vstupní zařízení](https://www.w3.org/TR/UAAG20/#gl-other-devices)

**ATAG**

-   [Princip A.1: Uživatelská rozhraní nástrojů pro tvorbu se řídí příslušnými pokyny pro přístupnost](https://www.w3.org/TR/ATAG20/#principle_a1)
-   [Pokyn A.3.1: (Pro uživatelské rozhraní nástrojů pro tvorbu) Podporujte přístup z klávesnice k autorským funkcím](https://www.w3.org/TR/ATAG20/#gl_a31)
-   [Část B. Podporujte tvorbu přístupného obsahu](https://www.w3.org/TR/ATAG20/#part_b)

{% include excol.html type="end" %}{% include excol.html type="start" %}

#### Příběhy související s přístupností z klávesnice
{:.no_toc}

{% include excol.html type="middle" %}

-   [Alex, reportér s poškozením z opakovaného namáhání](/people-use-web/user-stories/#reporter)
-   [Ilya, vedoucí pracovnice, která je slepá](/people-use-web/user-stories/#accountant)

{% include excol.html type="end" %}

### Uživatelé mají dostatek času na přečtení a použití obsahu {#time}

Někteří lidé potřebují více času než jiní pro čtení a použití obsahu. Například někteří lidé vyžadují více času pro napsání textu, porozumnění instrukcím, ovládání ovládacích prvků nebo jiný způsob provedení úkonů na webové stránce.

Mezi příklady poskytnutí dostatku času patří poskytnutí možnosti:

-   Zastavení, zvýšení nebo přizpůsobení časových limitů pokud to je v dané situaci možné
-   Pozastavit, zastavit nebo skrýt pohyb, blikání nebo posouvání obsahu
-   Odložit nebo potlačit vyrušení pokud to je v dané situaci možné
-   Opětovného přihlášení po vypršení relace bez ztráty dat

{% include excol.html type="start" %}

#### Požadavky na přístupnost související s dostatkem času (odkazy na technické specifikace)
{:.no_toc}

{% include excol.html type="middle" %}

**WCAG**

-   [Pokyn 2.2 - Dostatek času](https://www.w3.org/WAI/WCAG21/quickref/#enough-time)

**UAAG**

-   [Pokyn 2.8 - Časově nezávislé interakce](https://www.w3.org/TR/UAAG20/#gl-time-independent)
-   [Pokyn 2.10 - Časově závislá média](https://www.w3.org/TR/UAAG20/#gl-control-inaccessible-content)

**ATAG**

-   [Princip A.1: Uživatelská rozhraní nástrojů pro tvorbu se řídí příslušnými pokyny pro přístupnost](https://www.w3.org/TR/ATAG20/#principle_a1)
-   [Pokyn A.3.2: (Pro uživatelské rozhraní nástrojů pro tvorbu) Poskytněte autorům dostatek času](https://www.w3.org/TR/ATAG20/#gl_a32)
-   [Část B. Podporujte tvorbu přístupného obsahu](https://www.w3.org/TR/ATAG20/#part_b)

{% include excol.html type="end" %}{% include excol.html type="start" %}

#### Příběhy související s dostatkem času
{:.no_toc}

{% include excol.html type="middle" %}

-   [Alex, reportér s poškozením z opakovaného namáhání](/people-use-web/user-stories/#reporter)
-   [Preety, studentka střední školy s poruchou pozornosti, hyperaktivitou a dislexií](/people-use-web/user-stories/#classroomstudent)
-   [Yun, důchodce se slabým zrakem, třesem rukou a mírnou ztrátou krátkodobé paměti](/people-use-web/user-stories/#retiree)
-   [Luis, asistent v supermarketu s Downovým syndromem](/people-use-web/user-stories/#supermarketassistant)
-   [Kaseem, teenagerka, která je hluchá a slepá](/people-use-web/user-stories/#teenager)

{% include excol.html type="end" %}

### Obsah nezpůsobuje záchvaty a fyzické reakce {#safe}

Obsah, který bliká určitou rychlostí nebo vzorem může způsobit fotocitlivé reakce včetně záchvatů. Blikající obsah by ideálně neměl být zobrazen vůbec nebo tak, aby nezpůsoboval známá rizika. Animace a pohybující se obsah může také způsobovat zdravotní potíže a fyzické reakce.

Příklady, jak se nezpůsobovat záchvaty a fyzické reakce:

-   Nepoužívejte obsah, který bliká určitou rychlostí nebo vzorem
-   Varujte uživatele před zobrazením blikajícího obsahu a poskytněte alternativy
-   Poskytněte možnost vypnout animace, pokud nejsou nezbytné

{% include excol.html type="start" %}

#### Požadavky na přístupnost související se záchvaty (odkazy na technické specifikace)
{:.no_toc}

{% include excol.html type="middle" %}

**WCAG**

-   [Pokyn 2.3 - Záchvaty](https://www.w3.org/WAI/WCAG21/quickref/#seizures-and-physical-reactions)

**UAAG**

-   [Pokyn 2.9 - Blikání](https://www.w3.org/TR/UAAG20/#gl-prevent-flash)

**ATAG**

-   [Princip A.1: Uživatelská rozhraní nástrojů pro tvorbu se řídí příslušnými pokyny pro přístupnost](https://www.w3.org/TR/ATAG20/#principle_a1)
-   [Pokyn A.3.3: (Pro uživatelské rozhraní nástrojů pro tvorbu) Pomozte autorům vyhnout se blikání, které by mohlo způsobit záchvat](https://www.w3.org/TR/ATAG20/#gl_a33)
-   [Část B. Podporujte tvorbu přístupného obsahu](https://www.w3.org/TR/ATAG20/#part_b)

{% include excol.html type="end" %}

### Uživatelé mohou snadno procházet a vyhledávat obsah, snadno určí, kde se nacházejí {#navigable}

Dobře zorganizovaný obsah pomáhá uživatelům orientovat se a efektivně procházet obsah. Mezi příklady patří:

-   Stránky mají jasný titul a popisné nadpisy jednotlivých sekcí
-   Najít relevantní stránky v rámci řady webových stránek lze více než jedním způsobem
-   Uživatelé jsou informování o současné lokaci v rámci několika souvisejících stránek
-   Je možné přeskočit části obsahu, které se opakují na více stránkách
-   Focus klávesnice je vidět a pořadí focusu dává smysl
-   Účel odkazu je jasný, nejlépe i v případě, kdy je odkaz zobrazen samostatně

Splnění tohoto požadavku pomáhá lidem navigovat webovou stránkou různými způsoby podle jejich konkrétních potřeb a preferencí. Například někteří lidé při hledání určité webové stránky spoléhají na hierarchické navigační struktury, jako jsou panely nabídek. Jiní ale ve stejné situaci spoléhají spíše na funkci vyhledávání na webových stránkách. Někteří obsah vidí, jiný slyší nebo slyší a vidí zároveň. Někteří uživatelé používají pouze myš nebo klávesnici, zatímco jiní mohou používat obojí.

{% include excol.html type="start" %}

#### Požadavky na přístupnost související s navigací (odkazy na technické specifikace)
{:.no_toc}

{% include excol.html type="middle" %}

**WCAG**

-   [Pokyn 2.4 - Navigace](https://www.w3.org/WAI/WCAG21/quickref/#navigable)

**UAAG**

-   [Pokyn 2.2 - Sekvenční navigace](https://www.w3.org/TR/UAAG20/#gl-sequential-navigation)
-   [Pokyn 2.3 - Přímá navigace a aktivace](https://www.w3.org/TR/UAAG20/#gl-direct-navigation-and-activation)
-   [Pokyn 2.4 - Textové vyhledávání](https://www.w3.org/TR/UAAG20/#gl-search-text)
-   [Pokyn 2.5 - Strukturální navigace](https://www.w3.org/TR/UAAG20/#gl-nav-structure)
-   [Pokyn 2.7 - Grafické ovládací prvky](https://www.w3.org/TR/UAAG20/#gl-configure-controls)

**ATAG**

-   [Princip A.1: Uživatelská rozhraní nástrojů pro tvorbu se řídí příslušnými pokyny pro přístupnost](https://www.w3.org/TR/ATAG20/#principle_a1)
-   [Pokyn A.2.2: (Pro uživatelské rozhraní nástrojů pro tvorbu) Zajistěte, aby bylo možné programově určit zobrazení pro úpravy](https://www.w3.org/TR/ATAG20/#gl_a22)
-   [Pokyn A.3.4: (Pro uživatelské rozhraní nástrojů pro tvorbu) Vylepšete navigaci a úpravy prostřednictvím struktury obsahu](https://www.w3.org/TR/ATAG20/#gl_a34)
-   [Pokyn A.3.5: (Pro uživatelské rozhraní nástrojů pro tvorbu) Poskytněte textové vyhledávání obsahu](https://www.w3.org/TR/ATAG20/#gl_a35)
-   [Část B. Podporujte tvorbu přístupného obsahu](https://www.w3.org/TR/ATAG20/#part_b)

{% include excol.html type="end" %}{% include excol.html type="start" %}

#### Příběhy související s navigací
{:.no_toc}

{% include excol.html type="middle" %}

-   [Alex, reportér s poškozením z opakovaného namáhání](/people-use-web/user-stories/#reporter)
-   [Ilya, vedoucí pracovnice, která je slepá](/people-use-web/user-stories/#accountant)
-   [Preety, studentka střední školy s poruchou pozornosti, hyperaktivitou a dislexií](/people-use-web/user-stories/#classroomstudent)
-   [Yun, důchodce se slabým zrakem, třesem rukou a mírnou ztrátou krátkodobé paměti](/people-use-web/user-stories/#retiree)
-   [Luis, asistent v supermarketu s Downovým syndromem](/people-use-web/user-stories/#supermarketassistant)
-   [Kaseem, teenagerka, která je hluchá a slepá](/people-use-web/user-stories/#teenager)

{% include excol.html type="end" %}

### Uživatelé mohou použít různé způsoby vstupu mimo klávesnici {#modalities}

Způsoby vstupu kromě klávesnice, jako třeba aktivace dotykem, hlasové rozpoznávání (hlasový vstup) a gesta, umožňují pro mnoho lidí snadnější použití obsahu. Přesto ne všichni mohou použít kterýkoliv z těchto způsobů nebo ve stejné míře. Specifický design maximalizuje výhody těchto způsobů. To zahrnuje:

-   Gesta vyžadující obratnost nebo jemný pohyb mají alternativy, které nevyžadují velkou obratnost
-   Komponenty jsou navrženy tak, aby se zabránilo nechtěné aktivaci, například poskytnutím funkce Zpět
-   Popisky prezentované uživatelům se shodují s odpovídajícími názvy objektů v kódu, což podporuje aktivaci hlasem
-   Funkčnost aktivovanou pohybem lze aktivovat také prostřednictvím komponent uživatelského rozhraní
-   Tlačítka, odkazy a další aktivní komponenty jsou dostatečně velké, aby se snadněji aktivovaly dotykem

Splnění tohoto požadavku usnadňuje používání obsahu pro mnoho lidí se širokou škálou schopností využívajících širokou škálu zařízení. To zahrnuje obsah používaný v mobilních telefonech, tabletech a samoobslužných terminálech, jako jsou automaty na jízdenky.

{% include excol.html type="start" id="" %}

#### Požadavky na přístupnost související se způsoby vstupu (odkazy na technické specifikace)
{:.no_toc}

{% include excol.html type="middle" %}

**WCAG**

-   [Pokyn 2.5 - Způsoby vstupu](https://www.w3.org/WAI/WCAG21/quickref/#input-modalities)

{% include excol.html type="end" %}{% include excol.html type="start" id="" %}

#### Příběhy související se způsoby vstupu
{:.no_toc}

{% include excol.html type="middle" %}

-   [Alex, reportér s poškozením z opakovaného namáhání](/people-use-web/user-stories/#reporter)
-   [Yun, důchodce se slabým zrakem, třesem rukou a mírnou ztrátou krátkodobé paměti](/people-use-web/user-stories/#retiree)
-   [Luis, asistent v supermarketu s Downovým syndromem](/people-use-web/user-stories/#supermarketassistant)

{% include excol.html type="end" %}

## Understandable information and user interface {#understandable}

### Text is readable and understandable {#readable}

Content authors need to ensure that text content is readable and understandable to the broadest audience possible, including when it is read aloud by text-to-speech. Such content includes:

-   Identifying the primary language of a web page, such as Arabic, Dutch, or Korean
-   Identifying the language of text passages, phrases, or other parts of a web page
-   Providing definitions for any unusual words, phrases, idioms, and abbreviations
-   Using the clearest and simplest language possible, or providing simplified versions

Meeting this requirement helps software, including assistive technology, to process text content correctly. For instance, this requirement helps software to read the content aloud, to generate page summaries, and to provide definitions for unusual words such as technical jargon. It also helps people who have difficulty understanding more complex sentences, phrases, and vocabulary. In particular, it helps people with different types of cognitive disabilities.

{% include excol.html type="start" %}

#### Accessibility requirements related to readability (odkazy na technické specifikace)
{:.no_toc}

{% include excol.html type="middle" %}

**WCAG**

-   [Pokyn 3.1 - Readable](https://www.w3.org/WAI/WCAG21/quickref/#readable)

**ATAG**

-   [Princip A.1: Uživatelská rozhraní nástrojů pro tvorbu se řídí příslušnými pokyny pro přístupnost](https://www.w3.org/TR/ATAG20/#principle_a1)
-   [Pokyn A.4.2: (Pro uživatelské rozhraní nástrojů pro tvorbu) Document the user interface, including all accessibility features](https://www.w3.org/TR/ATAG20/#gl_b42)
-   [Část B. Podporujte tvorbu přístupného obsahu](https://www.w3.org/TR/ATAG20/#part_b)

{% include excol.html type="end" %}{% include excol.html type="start" %}

#### Stories related to readability
{:.no_toc}

{% include excol.html type="middle" %}

-   [Martine, online studentka, která špatně slyší](/people-use-web/user-stories/#onlinestudent)
-   [Ilya, vedoucí pracovnice, která je slepá](/people-use-web/user-stories/#accountant)
-   [Preety, studentka střední školy s poruchou pozornosti, hyperaktivitou a dislexií](/people-use-web/user-stories/#classroomstudent)
-   [Yun, důchodce se slabým zrakem, třesem rukou a mírnou ztrátou krátkodobé paměti](/people-use-web/user-stories/#retiree)
-   [Luis, asistent v supermarketu s Downovým syndromem](/people-use-web/user-stories/#supermarketassistant)

{% include excol.html type="end" %}

### Content appears and operates in predictable ways {#predictable}

Many people rely on predictable user interfaces and are disoriented or distracted by inconsistent appearance or behavior. Examples of making content more predictable include:

-   Navigation mechanisms that are repeated on multiple pages appear in the same place each time
-   User interface components that are repeated on web pages have the same labels each time
-   Significant changes on a web page do not happen without the consent of the user

Meeting this requirement helps people to quickly learn the functionality and navigation mechanisms provided on a website, and to operate them according to their specific needs and preferences. For instance, some people assign personalized shortcut keys to functions they frequently use to enhance keyboard navigation. Others memorize the steps to reach certain pages or to complete processes on a website. Both rely on predictable and consistent functionality.

{% include excol.html type="start" %}

#### Accessibility requirements related to predictability (odkazy na technické specifikace)
{:.no_toc}

{% include excol.html type="middle" %}

**WCAG**

-   [Pokyn 3.2 - Predictable](https://www.w3.org/WAI/WCAG21/quickref/#predictable)

**UAAG**

-   [Pokyn 3.3 - Predictable](https://www.w3.org/TR/UAAG20/#gl-predictable-operation)

**ATAG**

-   [Princip A.1: Uživatelská rozhraní nástrojů pro tvorbu se řídí příslušnými pokyny pro přístupnost](https://www.w3.org/TR/ATAG20/#principle_a1)
-   [Pokyn A.2.2: (Pro uživatelské rozhraní nástrojů pro tvorbu) Zajistěte, aby bylo možné programově určit zobrazení pro úpravy](https://www.w3.org/TR/ATAG20/#gl_a22)
-   [Pokyn A.4.2: (Pro uživatelské rozhraní nástrojů pro tvorbu) Document the user interface, including all accessibility features](https://www.w3.org/TR/ATAG20/#gl_b42)
-   [Část B. Podporujte tvorbu přístupného obsahu](https://www.w3.org/TR/ATAG20/#part_b)

{% include excol.html type="end" %}{% include excol.html type="start" %}

#### Stories related to predictability
{:.no_toc}

{% include excol.html type="middle" %}

-   [Alex, reportér s poškozením z opakovaného namáhání](/people-use-web/user-stories/#reporter)
-   [Ilya, vedoucí pracovnice, která je slepá](/people-use-web/user-stories/#accountant)
-   [Preety, studentka střední školy s poruchou pozornosti, hyperaktivitou a dislexií](/people-use-web/user-stories/#classroomstudent)
-   [Yun, důchodce se slabým zrakem, třesem rukou a mírnou ztrátou krátkodobé paměti](/people-use-web/user-stories/#retiree)
-   [Luis, asistent v supermarketu s Downovým syndromem](/people-use-web/user-stories/#supermarketassistant)
-   [Kaseem, teenagerka, která je hluchá a slepá](/people-use-web/user-stories/#teenager)

{% include excol.html type="end" %}

### Users are helped to avoid and correct mistakes {#tolerant}

Forms and other interaction can be confusing or difficult to use for many people, and, as a result, they may be more likely to make mistakes. Examples of helping users to avoid and correct mistakes include:

-   Descriptive instructions, error messages, and suggestions for correction
-   Context-sensitive help for more complex functionality and interaction
-   Opportunity to review, correct, or reverse submissions if necessary

Meeting this requirement helps people who do not see or hear the content, and may not recognize implicit relationships, sequences, and other cues. It also helps people who do not understand the functionality, are disoriented or confused, forget, or make mistakes using forms and interaction for any other reason.

{% include excol.html type="start" %}

#### Accessibility requirements related to input assistance (odkazy na technické specifikace)
{:.no_toc}

{% include excol.html type="middle" %}

**WCAG**

-   [Pokyn 3.3 - Input assistance](https://www.w3.org/WAI/WCAG21/quickref/#input-assistance)

**UAAG**

-   [Pokyn 3.1 - Mistakes](https://www.w3.org/TR/UAAG20/#gl-avoid-mistakes)

**ATAG**

-   [Princip A.1: Uživatelská rozhraní nástrojů pro tvorbu se řídí příslušnými pokyny pro přístupnost](https://www.w3.org/TR/ATAG20/#principle_a1)
-   [Pokyn A.2.2: (Pro uživatelské rozhraní nástrojů pro tvorbu) Zajistěte, aby bylo možné programově určit zobrazení pro úpravy](https://www.w3.org/TR/ATAG20/#gl_a22)
-   [Pokyn A.4.1: (Pro uživatelské rozhraní nástrojů pro tvorbu) Help authors avoid and correct mistakes](https://www.w3.org/TR/ATAG20/#gl_b41)
-   [Část B. Podporujte tvorbu přístupného obsahu](https://www.w3.org/TR/ATAG20/#part_b)

{% include excol.html type="end" %}{% include excol.html type="start" %}

#### Stories related to input assistance
{:.no_toc}

{% include excol.html type="middle" %}

-   [Lee, online nakupující, který je barvoslepý](/people-use-web/user-stories/#shopper)
-   [Alex, reportér s poškozením z opakovaného namáhání](/people-use-web/user-stories/#reporter)
-   [Preety, studentka střední školy s poruchou pozornosti, hyperaktivitou a dislexií](/people-use-web/user-stories/#classroomstudent)
-   [Yun, důchodce se slabým zrakem, třesem rukou a mírnou ztrátou krátkodobé paměti](/people-use-web/user-stories/#retiree)
-   [Luis, asistent v supermarketu s Downovým syndromem](/people-use-web/user-stories/#supermarketassistant)

{% include excol.html type="end" %}

## Robust content and reliable interpretation {#robust}

### Content is compatible with current and future user tools {#compatible}

Robust content is compatible with different browsers, assistive technologies, and other user agents. Examples of how this can be achieved include:

-   Ensuring markup can be reliably interpreted, for instance by ensuring it is valid
-   Providing a name, role, and value for non-standard user interface components

Meeting this requirement helps maximize compatibility with current and future user agents, including assistive technologies. In particular, it enables assistive technologies to process the content reliably, and to present or to operate it in different ways. This includes non-standard (scripted) buttons, input fields, and other controls.

{% include excol.html type="start" %}

#### Accessibility requirements related to compatibility (odkazy na technické specifikace)
{:.no_toc}

{% include excol.html type="middle" %}

**WCAG**

-   [Pokyn 4.1 - Compatible](https://www.w3.org/WAI/WCAG21/quickref/#compatible)

**UAAG**

-   [Pokyn 2.6 - Preference settings](https://www.w3.org/TR/UAAG20/#gl-store-prefs)
-   [Pokyn 4.1 - Assistive technology](https://www.w3.org/TR/UAAG20/#gl-AT-access)
-   [Pokyn 5.1 - Follow specifications](https://www.w3.org/TR/UAAG20/#gl-obs-env-conventions)

**ATAG**

-   [Princip A.1: Uživatelská rozhraní nástrojů pro tvorbu se řídí příslušnými pokyny pro přístupnost](https://www.w3.org/TR/ATAG20/#principle_a1)
-   [Část B. Podporujte tvorbu přístupného obsahu](https://www.w3.org/TR/ATAG20/#part_b)

{% include excol.html type="end" %}{% include excol.html type="start" %}

#### Stories related to compatibility
{:.no_toc}

{% include excol.html type="middle" %}

-   [Lee, online nakupující, který je barvoslepý](/people-use-web/user-stories/#shopper)
-   [Alex, reportér s poškozením z opakovaného namáhání](/people-use-web/user-stories/#reporter)
-   [Ilya, vedoucí pracovnice, která je slepá](/people-use-web/user-stories/#accountant)
-   [Preety, studentka střední školy s poruchou pozornosti, hyperaktivitou a dislexií](/people-use-web/user-stories/#classroomstudent)
-   [Luis, asistent v supermarketu s Downovým syndromem](/people-use-web/user-stories/#supermarketassistant)
-   [Kaseem, teenagerka, která je hluchá a slepá](/people-use-web/user-stories/#teenager)

{% include excol.html type="end" %}

{% include excol.html type="all" %}

