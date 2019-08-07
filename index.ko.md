---
# Translation instructions are after the "#" character in this first section. They are comments that do not show up in the web page. You do not need to translate the instructions after #.

title: 접근성 원칙   # Do not translate "title:". Do translate the text after "title:".
nav_title: "접근성 원칙"   # A short title that is used in the navigation

lang: ko   # Change "en" to the translated language shortcode from https://www.iana.org/assignments/language-subtag-registry/language-subtag-registry

last_updated: 2019-07-16   # Put the date of this translation YYYY-MM-DD (with month in the middle)
translators: 
- name: "Yong Ui Lee"   # Replace @@ with translator name
  link: "https://twitter.com/yongui9"
contributors:
# - name: "@@"   # Replace @@ with contributor name, or delete this line if none
# - name: "@@"   # Replace @@ with name, or delete this line if not multiple contributors

ref: /fundamentals/accessibility-principles/   # Do not change this
layout: default
github:
  repository: w3c/wai-accessibility-principles
  path: index.ko.md   # Add the language shortcode to the middle of the filename, for example index.fr.md
permalink: /fundamentals/accessibility-principles/ko   # Add the language shortcode to the end; for example /fundamentals/accessibility-principles/fr

description: 웹 사이트, 웹 어플리케이션, 브라우저와 다른 도구를 위한 기본적 웹 접근성 필요조건에 대한 개요   # translate this sentence
image: /content-images/wai-accessibility-principles/social.png

teaser_text: 접근성 원칙 페이지는 웹 사이트, 웹 어플리케이션, 브라우저와 다른 도구를 위한 웹 접근성 필요조건에 대해 소개하고 있습니다. W3C 웹의 국제 표준에 대해 언급하고 있습니다. 
footer: >   # Translate all the words below, including "Date:", "Editor:", Updated, and the month. Do not change these dates.
  <p><strong>날짜:</strong> 2019년 5월 10일 업데이트됨.</p>
  <p><strong>편집자:</strong> <a href="https://www.w3.org/People/shadi/">Shadi Abou_Zahra</a>. <a href="https://www.w3.org/WAI/intro/people-use-web/acknowledgments">Acknowledgments</a>.</p>
  <p>교육과 활동관련 실무 그룹인 (<a href="http://www.w3.org/WAI/EO/">EOWG</a>)의 지원을 받아 제작되었습니다. 이전에 <a href="https://www.w3.org/WAI/EO/2008/wai-age-tf">WAI-AGE Task Force</a>, with support of the <a href="https://www.w3.org/WAI/WAI-AGE/">WAI-AGE 프로젝트</a>의 지원과 <a href="https://www.w3.org/WAI/EO/2008/wai-age-tf">WAI-AGE 팀</a>에 의해 제작되었습니다.</p>

# Read Important Translations Guidance at https://www.w3.org/WAI/about/translating/#important
# Read Translations Notes for this resource at https://github.com/w3c/wai-accessibility-principles/blob/master/README.md
# end of translation instructions
---


{::nomarkdown}
{% include box.html type="start" h="2" title="Summary" class="full" %}
{:/}

이 페이지는 웹 사이트, 웹 어플리케이션, 브라우저와 다른 도구를 위한 웹 접근성 필요조건에 대해 소개하고 있습니다. W3C 웹 접근성 이니셔티브(WAI)의 국제 표준과 [웹 사용자 이야기](/people-use-web/user-stories/)에 대해 언급하고 있습니다.

**주석:** 본 내용은 모든 접근성 필요조건을 목록화 한 것은 아닙니다.

{::nomarkdown}
{% include box.html type="end" %}
{:/}


{::options toc_levels="2,3" /}

{::nomarkdown}
{% include_cached toc.html type="start" title="Page Contents" class="full" %}
{:/}

-   TOC is created automatically.
{:toc}

{::nomarkdown}
{% include_cached toc.html type="end" %}
{:/}


{% include excol.html type="all" %}

## 웹 접근성 표준 {#standards}

웹 접근성은 함께 동작하는 여러 요소들이 필요합니다. 요소들에는 다음의 내용이 포함됩니다. : 

-   **웹 콘텐츠**{:#webcontent} - 텍스트, 이미지, 폼, 멀티미디어, 마크업 코드, 스크립트, 어플리케이션 등과 같은 것을 포함하는 웹 사이트의 일부를 가리킵니다.
-   **사용자 에이전트**{:#useragents} - 사용자가 웹 콘텐츠에 접근할 수 있도록 하는 소프트웨어(데스크탑 그래픽 브라우저, 음성 브라우저, 모바일 브라우저, 멀티미디어 플레이어, 플러그인와 여러 [보조 기술](/people-use-web/tools-techniques/#at "definition"))를 가리킵니다.
-   **저작 도구**{:#authoringtools} - 코드 에디터, 문서 변환 도구, 저작물 관리 시스템, 블로그, 데이터 베이스 스크립트와 같은 사용자가 웹 콘텐츠를 생산할 수 있도록 하는 소프트웨어나 서비스를 가리킵니다.

{% include excol.html type="start" %}

### 웹 접근성 표준 더 자세히 살펴보기
{:.no_toc}

{% include excol.html type="middle" %}

이 요소들은 서로를 지원하고 밀접한 관련이 있습니다. 예를 들어, **웹 콘텐츠**는 이미지에 대체 텍스트를 포함해야 합니다. 이 정보는 **웹 브라우저**가 처리하고, 스크린 리더와 같은 **보조 기술**에 전달됩니다. 저자들은 대체 텍스트를 작성하기 위해 **저작 도구**를 필요로 합니다. 더 자세한 내용은 [[Essential Components of Web Accessibility]](/fundamentals/components/)를 확인하세요.

표준은 각 요소들의 접근성 필요조건을 정의하는 데에 중요한 역할을 합니다. 몇 접근성 필요조건은 충족하기 쉽지만 장애가 있는 사용자가 웹을 어떻게 사용하는 지에 대한 기본을 이해한다면 더 효과적으로 수행할 수 있을 것입니다. 접근성의 몇몇 부분은 사용자가 웹을 사용하는 방법에 대한 고차원적인 기술과 지식이 필요합니다. 모든 경우에서 [당신의 웹 프로젝트 초기 단계와 전체에 사용자 포함시키기](/test-evaluate/involving-users/)는 당신이 더 일하기 쉽고, 나은 결과를 얻는 데에 도움을 줄 것입니다.

W3C 웹 접근성 이니셔티브(WAI)는 웹 접근성 관련 국제 표준으로 사용되는 지침들을 제공합니다. 다음이 포함됩니다. :

-   **[웹 콘텐츠 접근성 지침 (WCAG)](/standards-guidelines/wcag/)**
-   **[사용자 에이전트 접근성 지침 (UAAG)](/standards-guidelines/uaag/)**
-   **[웹 저작 도구 접근성 지침 (ATAG)](/standards-guidelines/atag/)**

There is also a WAI specification for **[접근 가능한 리치 인터넷 어플리케이션 (WAI-ARIA)](https://www.w3.org/WAI/intro/aria.php)**에 대한 WAI 명세도 있습니다. 이는  Ajax, JavaScript와 관련된 웹 기술로 만들어진 고차원 사용자 인터페이스 컨트롤과 다양한 콘텐츠를 포함합니다.

{% include excol.html type="end" %}

## 인지가능한 정보와 사용자 인터페이스 {#perceivable}

### 텍스트가 아닌 콘텐츠를 위한 대체 텍스트 {#alternatives}

대체 텍스트는 텍스트가 아닌 콘텐츠에 대응하는 것입니다. 다음은 예시입니다. : 

-   아이콘, 버튼, 그래픽을 포함한 이미지에 대한 짧은 문구
-   차트, 다이어그램, 삽화를 나타내는 설명
-   오디오나 영상과 같은 텍스트가 아닌 콘텐츠에 대한 짧은 설명
-   폼 요소, 인풋, 다른 사용자 인터페이스 요소에 대한 라벨

대체 텍스트는 사용자에게 동등한 경험을 제공하기 위해 이미지나 기능의 목적을 전달하는데 사용됩니다. 예를 들어, 검색 버튼의 경우 "*돋보기*" 보다는 "*검색*"이 적절한 대체 텍스트입니다. 

대체 텍스트는 다양한 방법으로 표현할 수 있습니다. 예를 들어, 화면을 보지 못하거나 읽는데 어려움을 겪는 사람들이 음성으로 읽는 용도로 사용될 수 있고, 사용자가 설정한 폰트 사이즈로 키울 수 있고, 점자 단말기에 표시될 수도 있습니다. 대체 텍스트는 음성 인식(음성 제어) 탐색이나 키보드 탐색을 보조하는 제어, 기능을 위한 라벨로 제공될 수 있습니다. 오디오, 영상, 다른 형식의 파일, 웹 사이트의 일부분으로 삽입되어있는 어플리케이션을 구분하기 위한 라벨 역할을 할 수도 있습니다. 

{% include excol.html type="start" %}

#### 대체 텍스트와 관련된 접근성 필요조건 (links to technical specification)
{:.no_toc}

{% include excol.html type="middle" %}

**WCAG**

-   [지침 1.1 - 대체 텍스트](https://www.w3.org/WAI/WCAG21/quickref/#text-alternatives)

**UAAG**

-   [지침 1.1 - 대체 콘텐츠](https://www.w3.org/TR/UAAG20/#gl-access-alternative-content)

**ATAG**

-   [원칙 A.1: 저작 도구 사용자 인터페이스는 해당되는 접근성 지침을 따른다.](https://www.w3.org/TR/ATAG20/#principle_a1)
-   [지침 A.2.1: (저작 도구 사용자 인터페이스를 위한) 저자가 대체 텍스트에 접근할 수 있도록 하라.](https://www.w3.org/TR/ATAG20/#gl_a21)
-   [지침 A.2.2: (저작 도구 사용자 인터페이스를 위한) 편집창 화면을 프로그램적으로 조작할 수 있도록 하라.](https://www.w3.org/TR/ATAG20/#gl_a22)
-   [지침 A.3.7: (저작 도구 사용자 인터페이스를 위한) 미리보기는 적어도 인마켓 사용자 에이전트가 접근할 수 있도록 하라.](https://www.w3.org/TR/ATAG20/#gl_b37)
-   [파트 B. 접근 가능한 콘텐츠 생산을 지원하라.](https://www.w3.org/TR/ATAG20/#part_b)

{% include excol.html type="end" %}

{% include excol.html type="start" %}

#### 대체 텍스트와 관련된 이야기
{:#stories-related-to-text-alternatives.no_toc}

{% include excol.html type="middle" %}

-   [Alex, 반복성 긴장 장애가 있는 리포터](/people-use-web/user-stories/#reporter)
-   [Martine, 청력이 약한 온라인 수강생](/people-use-web/user-stories/#onlinestudent)
-   [Ilya, 시각장애가 있는 고위 간부](/people-use-web/user-stories/#accountant)
-   [Preety, 주의력결핍과다활동장애와 난독증이 있는 중학생](/people-use-web/user-stories/#classroomstudent)
-   [Yun, 저시력, 수전증, 경도 건망증이 있는 퇴직자](/people-use-web/user-stories/#retiree)
-   [Kaseem, 시청각장애가 있는 10대](/people-use-web/user-stories/#teenager)

{% include excol.html type="end" %}

### 멀티미디어를 위한 캡션과 다른 대안 {#captions}

오디오를 듣지 못하고, 영상을 보지못하는 사람에게는 대안이 필요합니다. 다음은 예시입니다. :

-   라디오 인터뷰를 녹음한 것과 같은 오디오 콘텐츠를 위한 텍스트 대본과 캡션
-   영상의 중요한 시각적 정보를 묘사하는 나레이션인 오디오 설명
-   청각 경험과 관련된 오디오 콘텐츠에 대한 수화

정확한 음성, 시각 정보 순서를 담은 잘 정리된 텍스트 대본은 기본적인 접근성을 제공하고, 캡션과 오디오 설명을 제공이 가능하게 합니다.

{% include excol.html type="start" %}

#### 멀티미디어와 관련된 접근성 필요조건 (links to technical specification)
{:.no_toc}

{% include excol.html type="middle" %}

**WCAG**

-   [지침 1.2 - 시간에 기반한 미디어](https://www.w3.org/WAI/WCAG21/quickref/#time-based-media)

**UAAG**

-   [Guide지침line 1.1 - 대체 콘텐츠](https://www.w3.org/TR/UAAG20/#gl-access-alternative-content)

**ATAG**

-   [원칙 A.1: 저작 도구 사용자 인터페이스는 해당되는 접근성 지침을 따른다.](https://www.w3.org/TR/ATAG20/#principle_a1)
-   [지침 A.2.1: (저작 도구 사용자 인터페이스를 위한) 저자가 대체 텍스트에 접근할 수 있도록 하라.](https://www.w3.org/TR/ATAG20/#gl_a21)
-   [지침 A.3.7: (저작 도구 사용자 인터페이스를 위한) 미리보기는 적어도 인마켓 사용자 에이전트가 접근할 수 있도록 하라.](https://www.w3.org/TR/ATAG20/#gl_b37)
-   [파트 B. 접근 가능한 콘텐츠 생산을 지원하라.](https://www.w3.org/TR/ATAG20/#part_b)

{% include excol.html type="end" %}
{% include excol.html type="start" %}

#### 멀티미디어와 관련된 이야기 {#stories-related-to-multimedia}
{:.no_toc}

{% include excol.html type="middle" %}

-   [Martine, 청력이 약한 온라인 수강생](/people-use-web/user-stories/#onlinestudent)
-   [Ilya, 시각장애가 있는 고위 간부](/people-use-web/user-stories/#accountant)
-   [Kaseem, 시청각장애가 있는 10대](/people-use-web/user-stories/#teenager)

{% include excol.html type="end" %}

### 콘텐츠는 여러 방법으로 제공될 수 있습니다. {#adaptable}

사용자를 위해 콘텐츠 제공방식을 바꾸고자 한다면 다음 내용을 따라야 합니다. :

-   헤딩, 목록, 표, 입력 필드와 콘텐츠 구조들은 적절하게 마크업되어야 합니다.
-   정보나 지시사항의 순서는 보여지는 것에 의존하면 안됩니다.
-   브라우저와 보조 기술은 제공 방식을 개인화 할 수 있는 설정을 제공해야 합니다.

위의 조건들을 충족한다면 콘텐츠를 정확하기 읽고, 확대하고, 각 개인의 선호와 필요를 충족시킬 수 있을 것입니다. 예를 들어, 개인이 설정한 색상 조합, 폰트 사이즈 등과 같은 읽는 것을 돕는 여러 스타일 속성을 사용해 제공할 수 있습니다. 사람들이 개요에 접근할 수 있도록 하고, 특정 부분에 더 쉽게 접근할 수 있도록 하기 위한 페이지 아웃라인과 요약을 자동으로 해주는 것과 같은 다른 방법에서 또한 적용할 수 있습니다.

{% include excol.html type="start" %}

#### 적용과 관련된 접근성 조건 (links to technical specification)
{:.no_toc}

{% include excol.html type="middle" %}

**WCAG**

-   [지침 1.3 - 적용가능한](https://www.w3.org/WAI/WCAG21/quickref/#adaptable)

**UAAG**

-   [지침 1.4 - 텍스트 설정](https://www.w3.org/TR/UAAG20/#gl-text-config)
-   [지침 1.5 - 볼륨 설정](https://www.w3.org/TR/UAAG20/#gl-volume-config)
-   [지침 1.6 - 합성된 음성 설정](https://www.w3.org/TR/UAAG20/#gl-speech-config)
-   [지침 1.7 - 사용자 스타일 시트 설정](https://www.w3.org/TR/UAAG20/#gl-style-sheets-config)
-   [지침 1.9 - 다른 보기 방법](https://www.w3.org/TR/UAAG20/#gl-alternative-views)
-   [지침 1.10 - 요소 정보](https://www.w3.org/TR/UAAG20/#gl-info-link)

**ATAG**

-   [원칙 A.1: 저작 도구 사용자 인터페이스는 해당되는 접근성 지침을 따른다.](https://www.w3.org/TR/ATAG20/#principle_a1)
-   [지침 A.2.2: (저작 도구 사용자 인터페이스를 위한) 편집창 화면을 프로그램적으로 조작할 수 있도록 해야 한다.](https://www.w3.org/TR/ATAG20/#gl_a22)
-   [지침 A.3.7: (저작 도구 사용자 인터페이스를 위한) 미리보기는 적어도 인마켓 사용자 에이전트가 접근할 수 있도록 해야 한다.](https://www.w3.org/TR/ATAG20/#gl_b37)
-   [Part B. 접근 가능한 콘텐츠 생산을 지원해야 한다.](https://www.w3.org/TR/ATAG20/#part_b)

{% include excol.html type="end" %}{% include excol.html type="start" %}

#### 적용과 관련된 이야기
{:.no_toc}

{% include excol.html type="middle" %}

-   [Lee, 온라인 쇼핑을 하는 색맹인](/people-use-web/user-stories/#shopper)
-   [Alex, 반복성 긴장 장애가 있는 리포터](/people-use-web/user-stories/#reporter)
-   [Ilya, 시각장애가 있는 고위 간부](/people-use-web/user-stories/#accountant)
-   [Preety, 주의력결핍과다활동장애와 난독증이 있는 중학생](/people-use-web/user-stories/#classroomstudent)
-   [Yun, 저시력, 수전증, 경도 건망증이 있는 퇴직자](/people-use-web/user-stories/#retiree)
-   [Luis, 다운증후군이 있는 슈퍼마켓 직원](/people-use-web/user-stories/#supermarketassistant)
-   [Kaseem, 시청각장애가 있는 10대](/people-use-web/user-stories/#teenager)

{% include excol.html type="end" %}

### 보고 듣기 더 쉬운 콘텐츠 {#distinguishable}

구별 가능한 콘텐츠는 보고 듣기 더 쉽습니다. 다음 콘텐츠들이 포함됩니다. : 

-   색상이 정보 전달이나 콘텐츠 구분에 유일한 방법으로 사용되면 안됩니다. 
-   기본 전경색-배경색의 조합은 충분한 대비를 제공해야 합니다.
-   사용자가 텍스트를 400%로 조절하거나 텍스트 간격을 조정했을 때 정보 유실이 없어야 합니다.
-   작은 화면(뷰포트)이나 텍스트를 크게 했을 때 텍스트는 위치가 재조정되어야 합니다.
-   텍스트 이미지는 조절 가능하거나 실제 텍스트로 교체되거나 가능하면 피해야 합니다. 
-   사용자가 웹 사이트에서 재생되는 소리의 볼륨을 조절하거나 멈출 수 있어야 합니다. 
-   배경음악의 볼륨이 낮거나 끌 수 있어야 하고 방해 요인이 되어서는 안됩니다. 

위의 내용들을 준수하는 것은 중요한 정보를 더 눈에 띄게 하기 위한 전경과 배경 구분에 도움이 됩니다. 보조 기술을 사용하지 않는 사람이나 소리, 배경에 있는 콘텐츠로 탐색하는 데에 방해를 받는 보조 기술을 사용하는 사람 모두를 고려한 것입니다. 예를 들어, 색맹이 있는 사람들은 특별하나 도구를 사용하지 않고, 텍스트와 주변 배경 사이의 충분한 대비를 제공하는 적절한 디자인에 의존합니다. 또 다른 사람들에게는 자동으로 재생되는 소리가 텍스트 음성변환이나 [assistive listening devices (ALDs)](http://www.w3.org/WAI/training/accessible#ald "definition")의 사용을 방해할 수 있습니다. 

{% include excol.html type="start" %}

#### 구별 가능성(Distinguishability)과 관련된 접근성 필요 조건(기술 명세 링크)
{:.no_toc}

{% include excol.html type="middle" %}

**WCAG**

-   [지침 1.4 - 구별 가능성(Distinguishable)](https://www.w3.org/WAI/WCAG21/quickref/#distinguishable)

**UAAG**

-   [지침 1.3 - 강조(Highlighting)](https://www.w3.org/TR/UAAG20/#gl-interaction-highlight)
-   [지침 1.4 - 텍스트 설정](https://www.w3.org/TR/UAAG20/#gl-text-config)
-   [지침 1.5 - 볼륨 설정](https://www.w3.org/TR/UAAG20/#gl-volume-config)
-   [지침 1.6 - 합성된 음성 설정](https://www.w3.org/TR/UAAG20/#gl-speech-config)
-   [지침 1.7 - 사용자 스타일시트 설정](https://www.w3.org/TR/UAAG20/#gl-style-sheets-config)
-   [지침 1.8 - 뷰포트 안에 맞추기](https://www.w3.org/TR/UAAG20/#gl-viewport-orient)
-   [지침 1.9 - 대체 화면 제공(Alternative views)](https://www.w3.org/TR/UAAG20/#gl-alternative-views)
-   [지침 1.10 - 요소 정보](https://www.w3.org/TR/UAAG20/#gl-info-link)

**ATAG**

-   [원칙 A.1: 저작 도구 사용자 인터페이스는 적용할 수 있는 접근성 지침들을 준수해야 한다.](https://www.w3.org/TR/ATAG20/#principle_a1)
-   [지침 A.3.7: (저작 도구 사용자 인터페이스를 위해) 적어도 인마켓 사용자 에이전트 만큼의 미리보기 접근성을 보장해야 한다.](https://www.w3.org/TR/ATAG20/#gl_b37)
-   [Part B. 접근 가능한 콘텐츠 생산을 지원해야 한다.](https://www.w3.org/TR/ATAG20/#part_b)

{% include excol.html type="end" %}{% include excol.html type="start" %}

#### 구별 가능성과 관련된 이야기
{:.no_toc}

{% include excol.html type="middle" %}

-   [Lee, 온라인 쇼핑을 하는 색맹인](/people-use-web/user-stories/#shopper)
-   [Martine, 청력이 약한 온라인 수강생](/people-use-web/user-stories/#onlinestudent)
-   [Ilya, 시각장애가 있는 고위 간부](/people-use-web/user-stories/#accountant)
-   [Yun, 저시력, 수전증, 경도 건망증이 있는 퇴직자](/people-use-web/user-stories/#retiree)
-   [Kaseem, 시청각장애가 있는 10대](/people-use-web/user-stories/#teenager)

{% include excol.html type="end" %}

## Operable user interface and navigation {#operable}

### Functionality is available from a keyboard {#keyboard}

Many people do not use the mouse and rely on the keyboard to interact with the Web. This requires keyboard access to all functionality, including form controls, input, and other user interface components.

Keyboard accessibility includes:

-   All functionality that is available by mouse is also available by keyboard
-   Keyboard focus does not get trapped in any part of the content
-   Web browsers, authoring tools, and other tools provide keyboard support

Meeting this requirement helps keyboard users, including people using alternative keyboards such as keyboards with ergonomic layouts, on-screen keyboards, or switch devices. It also helps people using voice recognition (speech input) to operate websites and to dictate text through the keyboard interface.

{% include excol.html type="start" %}

#### Accessibility requirements related to keyboard accessibility (links to technical specification)
{:.no_toc}

{% include excol.html type="middle" %}

**WCAG**

-   [Guideline 2.1 - Keyboard accessible](https://www.w3.org/WAI/WCAG21/quickref/#keyboard-accessible)

**UAAG**

-   [Guideline 2.1 - Keyboard access](https://www.w3.org/TR/UAAG20/#gl-keyboard-access)
-   [Guideline 2.2 - Sequential navigation](https://www.w3.org/TR/UAAG20/#gl-sequential-navigation)
-   [Guideline 2.3 - Direct navigation and activation](https://www.w3.org/TR/UAAG20/#gl-direct-navigation-and-activation)
-   [Guideline 2.11 - Other Input Devices](https://www.w3.org/TR/UAAG20/#gl-other-devices)

**ATAG**

-   [Principle A.1: Authoring tool user interfaces follow applicable accessibility guidelines](https://www.w3.org/TR/ATAG20/#principle_a1)
-   [Guideline A.3.1: (For the authoring tool user interface) Provide keyboard access to authoring features](https://www.w3.org/TR/ATAG20/#gl_a31)
-   [Part B. Support the production of accessible content](https://www.w3.org/TR/ATAG20/#part_b)

{% include excol.html type="end" %}{% include excol.html type="start" %}

#### Stories related to keyboard accessibility
{:.no_toc}

{% include excol.html type="middle" %}

-   [Alex, 반복성 긴장 장애가 있는 리포터](/people-use-web/user-stories/#reporter)
-   [Ilya, 시각장애가 있는 고위 간부](/people-use-web/user-stories/#accountant)

{% include excol.html type="end" %}

### Users have enough time to read and use the content {#time}

Some people need more time than others to read and use the content. For instance, some people require more time to type text, understand instructions, operate controls, or to otherwise complete tasks on a website.

Examples of providing enough time include providing mechanisms to:

-   Stop, extend, or adjust time limits, except where necessary
-   Pause, stop, or hide moving, blinking, or scrolling content
-   Postpone or suppress interruptions, except where necessary
-   Re-authenticate when a session expires without losing data

{% include excol.html type="start" %}

#### Accessibility requirements related to sufficient time (links to technical specification)
{:.no_toc}

{% include excol.html type="middle" %}

**WCAG**

-   [Guideline 2.2 - Enough time](https://www.w3.org/WAI/WCAG21/quickref/#enough-time)

**UAAG**

-   [Guideline 2.8 - Time-independent interaction](https://www.w3.org/TR/UAAG20/#gl-time-independent)
-   [Guideline 2.10 - Time-based media](https://www.w3.org/TR/UAAG20/#gl-control-inaccessible-content)

**ATAG**

-   [Principle A.1: Authoring tool user interfaces follow applicable accessibility guidelines](https://www.w3.org/TR/ATAG20/#principle_a1)
-   [Guideline A.3.2: (For the authoring tool user interface) Provide authors with enough time](https://www.w3.org/TR/ATAG20/#gl_a32)
-   [Part B. Support the production of accessible content](https://www.w3.org/TR/ATAG20/#part_b)

{% include excol.html type="end" %}{% include excol.html type="start" %}

#### Stories related to sufficient time
{:.no_toc}

{% include excol.html type="middle" %}

-   [Alex, 반복성 긴장 장애가 있는 리포터](/people-use-web/user-stories/#reporter)
-   [Preety, 주의력결핍과다활동장애와 난독증이 있는 중학생](/people-use-web/user-stories/#classroomstudent)
-   [Yun, 저시력, 수전증, 경도 건망증이 있는 퇴직자](/people-use-web/user-stories/#retiree)
-   [Luis, 다운증후군이 있는 슈퍼마켓 직원](/people-use-web/user-stories/#supermarketassistant)
-   [Kaseem, 시청각장애가 있는 10대](/people-use-web/user-stories/#teenager)

{% include excol.html type="end" %}

### Content does not cause seizures and physical reactions {#safe}

Content that flashes at certain rates or patterns can cause photosensitive reactions, including seizures. Flashing content is ideally avoided entirely or only used in a way that does not cause known risks. Also animations and moving content can cause discomfort and physical reactions.

Examples of avoiding causing seizures and physical reactions:

-   Do not include content that flashes at particular rates and patterns
-   Warn users before flashing content is presented, and provide alternatives
-   Provide mechanisms to switch off animations, unless they are essential

{% include excol.html type="start" %}

#### Accessibility requirements related to seizures (links to technical specification)
{:.no_toc}

{% include excol.html type="middle" %}

**WCAG**

-   [Guideline 2.3 - Seizures](https://www.w3.org/WAI/WCAG21/quickref/#seizures-and-physical-reactions)

**UAAG**

-   [Guideline 2.9 - Flashing](https://www.w3.org/TR/UAAG20/#gl-prevent-flash)

**ATAG**

-   [Principle A.1: Authoring tool user interfaces follow applicable accessibility guidelines](https://www.w3.org/TR/ATAG20/#principle_a1)
-   [Guideline A.3.3: (For the authoring tool user interface) Help authors avoid flashing that could cause seizures](https://www.w3.org/TR/ATAG20/#gl_a33)
-   [Part B. Support the production of accessible content](https://www.w3.org/TR/ATAG20/#part_b)

{% include excol.html type="end" %}

### Users can easily navigate, find content, and determine where they are {#navigable}

Well organized content helps users to orient themselves and to navigate effectively. Such content includes:

-   Pages have clear titles and are organized using descriptive section headings
-   There is more than one way to find relevant pages within a set of web pages
-   Users are informed about their current location within a set of related pages
-   There are ways to bypass blocks of content that are repeated on multiple pages
-   The keyboard focus is visible, and the focus order follows a meaningful sequence
-   The purpose of a link is evident, ideally even when the link is viewed on its own

Meeting this requirement helps people to navigate through web pages in different ways, depending on their particular needs and preferences. For instance, while some people rely on hierarchical navigation structures such as menu bars to find specific web pages, others rely on search functions on websites instead. Some people may be seeing the content while others may be hearing it or seeing and hearing it at the same time. Some people may be using the content with only a mouse or a keyboard, while others may be using both.

{% include excol.html type="start" %}

#### Accessibility requirements related to navigation (links to technical specification)
{:.no_toc}

{% include excol.html type="middle" %}

**WCAG**

-   [Guideline 2.4 - Navigable](https://www.w3.org/WAI/WCAG21/quickref/#navigable)

**UAAG**

-   [Guideline 2.2 - Sequential navigation](https://www.w3.org/TR/UAAG20/#gl-sequential-navigation)
-   [Guideline 2.3 - Direct navigation and activation](https://www.w3.org/TR/UAAG20/#gl-direct-navigation-and-activation)
-   [Guideline 2.4 - Text search](https://www.w3.org/TR/UAAG20/#gl-search-text)
-   [Guideline 2.5 - Structural navigation](https://www.w3.org/TR/UAAG20/#gl-nav-structure)
-   [Guideline 2.7 - Graphical controls](https://www.w3.org/TR/UAAG20/#gl-configure-controls)

**ATAG**

-   [Principle A.1: Authoring tool user interfaces follow applicable accessibility guidelines](https://www.w3.org/TR/ATAG20/#principle_a1)
-   [Guideline A.2.2: (For the authoring tool user interface) Ensure that editing-view presentation can be programmatically determined](https://www.w3.org/TR/ATAG20/#gl_a22)
-   [Guideline A.3.4: (For the authoring tool user interface) Enhance navigation and editing via content structure](https://www.w3.org/TR/ATAG20/#gl_a34)
-   [Guideline A.3.5: (For the authoring tool user interface) Provide text search of the content](https://www.w3.org/TR/ATAG20/#gl_a35)
-   [Part B. Support the production of accessible content](https://www.w3.org/TR/ATAG20/#part_b)

{% include excol.html type="end" %}{% include excol.html type="start" %}

#### Stories related to navigation
{:.no_toc}

{% include excol.html type="middle" %}

-   [Alex, 반복성 긴장 장애가 있는 리포터](/people-use-web/user-stories/#reporter)
-   [Ilya, 시각장애가 있는 고위 간부](/people-use-web/user-stories/#accountant)
-   [Preety, 주의력결핍과다활동장애와 난독증이 있는 중학생](/people-use-web/user-stories/#classroomstudent)
-   [Yun, 저시력, 수전증, 경도 건망증이 있는 퇴직자](/people-use-web/user-stories/#retiree)
-   [Luis, 다운증후군이 있는 슈퍼마켓 직원](/people-use-web/user-stories/#supermarketassistant)
-   [Kaseem, 시청각장애가 있는 10대](/people-use-web/user-stories/#teenager)

{% include excol.html type="end" %}

### Users can use different input modalities beyond keyboard {#modalities}

Input modalities beyond keyboard, such as touch activation, voice recognition (speech input), and gestures make content easier to use for many people. Yet not everyone can use each of these input modalities, and to the same degree. Particular design considerations maximize the benefit of these input modalities. This includes:

-   Gestures that require dexterity or fine movement have alternatives that do not require high dexterity
-   Components are designed to avoid accidental activation, for example by providing undo functionality
-   Labels presented to users match corresponding object names in the code, to support activation by voice
-   Functionality that is activated by movement can also be activated through user interface components
-   Buttons, links, and other active components are large enough to make them easier to activate by touch

Meeting this requirement makes the content easier to use for many people with a wide range of abilities using a wide range of devices. This includes content used on mobile phones, tablet computers, and self-service terminals such as ticketing machines.

{% include excol.html type="start" id="" %}

#### Accessibility requirements related to input modalities (links to technical specification)
{:.no_toc}

{% include excol.html type="middle" %}

**WCAG**

-   [Guideline 2.5 - Input Modalities](https://www.w3.org/WAI/WCAG21/quickref/#input-modalities)

{% include excol.html type="end" %}{% include excol.html type="start" id="" %}

#### Stories related to input modalities
{:.no_toc}

{% include excol.html type="middle" %}

-   [Alex, 반복성 긴장 장애가 있는 리포터](/people-use-web/user-stories/#reporter)
-   [Yun, 저시력, 수전증, 경도 건망증이 있는 퇴직자](/people-use-web/user-stories/#retiree)
-   [Luis, 다운증후군이 있는 슈퍼마켓 직원](/people-use-web/user-stories/#supermarketassistant)

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

#### Accessibility requirements related to readability (links to technical specification)
{:.no_toc}

{% include excol.html type="middle" %}

**WCAG**

-   [Guideline 3.1 - Readable](https://www.w3.org/WAI/WCAG21/quickref/#readable)

**ATAG**

-   [Principle A.1: Authoring tool user interfaces follow applicable accessibility guidelines](https://www.w3.org/TR/ATAG20/#principle_a1)
-   [Guideline A.4.2: (For the authoring tool user interface) Document the user interface, including all accessibility features](https://www.w3.org/TR/ATAG20/#gl_b42)
-   [Part B. Support the production of accessible content](https://www.w3.org/TR/ATAG20/#part_b)

{% include excol.html type="end" %}{% include excol.html type="start" %}

#### Stories related to readability
{:.no_toc}

{% include excol.html type="middle" %}

-   [Martine, 청력이 약한 온라인 수강생](/people-use-web/user-stories/#onlinestudent)
-   [Ilya, 시각장애가 있는 고위 간부](/people-use-web/user-stories/#accountant)
-   [Preety, 주의력결핍과다활동장애와 난독증이 있는 중학생](/people-use-web/user-stories/#classroomstudent)
-   [Yun, 저시력, 수전증, 경도 건망증이 있는 퇴직자](/people-use-web/user-stories/#retiree)
-   [Luis, 다운증후군이 있는 슈퍼마켓 직원](/people-use-web/user-stories/#supermarketassistant)

{% include excol.html type="end" %}

### Content appears and operates in predictable ways {#predictable}

Many people rely on predictable user interfaces and are disoriented or distracted by inconsistent appearance or behavior. Examples of making content more predictable include:

-   Navigation mechanisms that are repeated on multiple pages appear in the same place each time
-   User interface components that are repeated on web pages have the same labels each time
-   Significant changes on a web page do not happen without the consent of the user

Meeting this requirement helps people to quickly learn the functionality and navigation mechanisms provided on a website, and to operate them according to their specific needs and preferences. For instance, some people assign personalized shortcut keys to functions they frequently use to enhance keyboard navigation. Others memorize the steps to reach certain pages or to complete processes on a website. Both rely on predictable and consistent functionality.

{% include excol.html type="start" %}

#### Accessibility requirements related to predictability (links to technical specification)
{:.no_toc}

{% include excol.html type="middle" %}

**WCAG**

-   [Guideline 3.2 - Predictable](https://www.w3.org/WAI/WCAG21/quickref/#predictable)

**UAAG**

-   [Guideline 3.3 - Predictable](https://www.w3.org/TR/UAAG20/#gl-predictable-operation)

**ATAG**

-   [Principle A.1: Authoring tool user interfaces follow applicable accessibility guidelines](https://www.w3.org/TR/ATAG20/#principle_a1)
-   [Guideline A.2.2: (For the authoring tool user interface) Ensure that editing-view presentation can be programmatically determined](https://www.w3.org/TR/ATAG20/#gl_a22)
-   [Guideline A.4.2: (For the authoring tool user interface) Document the user interface, including all accessibility features](https://www.w3.org/TR/ATAG20/#gl_b42)
-   [Part B. Support the production of accessible content](https://www.w3.org/TR/ATAG20/#part_b)

{% include excol.html type="end" %}{% include excol.html type="start" %}

#### Stories related to predictability
{:.no_toc}

{% include excol.html type="middle" %}

-   [Alex, 반복성 긴장 장애가 있는 리포터](/people-use-web/user-stories/#reporter)
-   [Ilya, 시각장애가 있는 고위 간부](/people-use-web/user-stories/#accountant)
-   [Preety, 주의력결핍과다활동장애와 난독증이 있는 중학생](/people-use-web/user-stories/#classroomstudent)
-   [Yun, 저시력, 수전증, 경도 건망증이 있는 퇴직자](/people-use-web/user-stories/#retiree)
-   [Luis, 다운증후군이 있는 슈퍼마켓 직원](/people-use-web/user-stories/#supermarketassistant)
-   [Kaseem, 시청각장애가 있는 10대](/people-use-web/user-stories/#teenager)

{% include excol.html type="end" %}

### Users are helped to avoid and correct mistakes {#tolerant}

Forms and other interaction can be confusing or difficult to use for many people, and, as a result, they may be more likely to make mistakes. Examples of helping users to avoid and correct mistakes include:

-   Descriptive instructions, error messages, and suggestions for correction
-   Context-sensitive help for more complex functionality and interaction
-   Opportunity to review, correct, or reverse submissions if necessary

Meeting this requirement helps people who do not see or hear the content, and may not recognize implicit relationships, sequences, and other cues. It also helps people who do not understand the functionality, are disoriented or confused, forget, or make mistakes using forms and interaction for any other reason.

{% include excol.html type="start" %}

#### Accessibility requirements related to input assistance (links to technical specification)
{:.no_toc}

{% include excol.html type="middle" %}

**WCAG**

-   [Guideline 3.3 - Input assistance](https://www.w3.org/WAI/WCAG21/quickref/#input-assistance)

**UAAG**

-   [Guideline 3.1 - Mistakes](https://www.w3.org/TR/UAAG20/#gl-avoid-mistakes)

**ATAG**

-   [Principle A.1: Authoring tool user interfaces follow applicable accessibility guidelines](https://www.w3.org/TR/ATAG20/#principle_a1)
-   [Guideline A.2.2: (For the authoring tool user interface) Ensure that editing-view presentation can be programmatically determined](https://www.w3.org/TR/ATAG20/#gl_a22)
-   [Guideline A.4.1: (For the authoring tool user interface) Help authors avoid and correct mistakes](https://www.w3.org/TR/ATAG20/#gl_b41)
-   [Part B. Support the production of accessible content](https://www.w3.org/TR/ATAG20/#part_b)

{% include excol.html type="end" %}{% include excol.html type="start" %}

#### Stories related to input assistance
{:.no_toc}

{% include excol.html type="middle" %}

-   [Lee, 온라인 쇼핑을 하는 색맹인](/people-use-web/user-stories/#shopper)
-   [Alex, 반복성 긴장 장애가 있는 리포터](/people-use-web/user-stories/#reporter)
-   [Preety, 주의력결핍과다활동장애와 난독증이 있는 중학생](/people-use-web/user-stories/#classroomstudent)
-   [Yun, 저시력, 수전증, 경도 건망증이 있는 퇴직자](/people-use-web/user-stories/#retiree)
-   [Luis, 다운증후군이 있는 슈퍼마켓 직원](/people-use-web/user-stories/#supermarketassistant)

{% include excol.html type="end" %}

## Robust content and reliable interpretation {#robust}

### Content is compatible with current and future user tools {#compatible}

Robust content is compatible with different browsers, assistive technologies, and other user agents. Examples of how this can be achieved include:

-   Ensuring markup can be reliably interpreted, for instance by ensuring it is valid
-   Providing a name, role, and value for non-standard user interface components

Meeting this requirement helps maximize compatibility with current and future user agents, including assistive technologies. In particular, it enables assistive technologies to process the content reliably, and to present or to operate it in different ways. This includes non-standard (scripted) buttons, input fields, and other controls.

{% include excol.html type="start" %}

#### Accessibility requirements related to compatibility (links to technical specification)
{:.no_toc}

{% include excol.html type="middle" %}

**WCAG**

-   [Guideline 4.1 - Compatible](https://www.w3.org/WAI/WCAG21/quickref/#compatible)

**UAAG**

-   [Guideline 2.6 - Preference settings](https://www.w3.org/TR/UAAG20/#gl-store-prefs)
-   [Guideline 4.1 - Assistive technology](https://www.w3.org/TR/UAAG20/#gl-AT-access)
-   [Guideline 5.1 - Follow specifications](https://www.w3.org/TR/UAAG20/#gl-obs-env-conventions)

**ATAG**

-   [Principle A.1: Authoring tool user interfaces follow applicable accessibility guidelines](https://www.w3.org/TR/ATAG20/#principle_a1)
-   [Part B. Support the production of accessible content](https://www.w3.org/TR/ATAG20/#part_b)

{% include excol.html type="end" %}{% include excol.html type="start" %}

#### Stories related to compatibility
{:.no_toc}

{% include excol.html type="middle" %}

-   [Lee, 온라인 쇼핑을 하는 색맹인](/people-use-web/user-stories/#shopper)
-   [Alex, 반복성 긴장 장애가 있는 리포터](/people-use-web/user-stories/#reporter)
-   [Ilya, 시각장애가 있는 고위 간부](/people-use-web/user-stories/#accountant)
-   [Preety, 주의력결핍과다활동장애와 난독증이 있는 중학생](/people-use-web/user-stories/#classroomstudent)
-   [Luis, 다운증후군이 있는 슈퍼마켓 직원](/people-use-web/user-stories/#supermarketassistant)
-   [Kaseem, 시청각장애가 있는 10대](/people-use-web/user-stories/#teenager)

{% include excol.html type="end" %}

{% include excol.html type="all" %}