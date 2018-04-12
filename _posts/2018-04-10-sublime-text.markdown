---
layout: post
title:  "Sublime Text 설치 및 세팅"
date:   2018-04-10
categories: Sublime Text
img: sublime.gif
categories: [sublime text, editor]
---



#### Sublime Text2 Download
 [http://www.sublimetext.com/2](http://www.sublimetext.com/2)
 
- - -

#### 각자 OS에 맞는 파일을 다운로드
 ![Version img]({{site.baseurl}}/images/version.GIF)


- - -
#### `Package Control` 설치

- Sublime Text 2를 실행한후 ctrl+\` 또는 `View > Show Console` 을 열고 다음단계의 내용을 복사 => 붙여넣기 => 엔터
- [SUBLIME TEXT 2 Package Control](https://packagecontrol.io/installation#st2)


- - -
#### 플러그인 설치
- Sublime 재부팅 후 `ctrl + shift + p => install package 입력 후 엔터`
- `Emmet` 젠코딩을 가능
- `SublimeCodeIntel` 코드인텔리전스 기능
- `IMESupport` 한글 입력을 할 때 한글자씩 늦게 보이는 현상을 완화시켜준다. Only Window
- `ConvertToUTF8` 서브라임 텍스트는 euc-kr 을 지원하지 않는데, 이 플러그인을 깔고 File - Set File Encoding To 에서 EUC-KR을 선택하면 된다.
- `BracketHighlighter` 태그의 처음과 끝을 하이라이트 시켜서 코드 가독성을 높여준다.
- `AdvancedNewFile` 단축키로 원하는 경로에 파일을 생성해준다. lorem\test.html 식으로 입력하면 한번에 생성되고 폴더가 없으면 생성된다.
- `JQuery `  JQuery 자동완성 기능이 추가된다.
- `CSS Format`  css 를 여러가지 방법으로 정렬시켜준다.
- `CSScomb` css 의 속성 순서를 원하는 순서로 변경시켜준다. CSSFormat 과 같은 기능도 있다.
- `View in Browser`  chrome, firefox, safari, IE 등 여러 브라우저로 오픈 가능하고 상대 경로도 가능
- `Prefixr` Cross browser를 지원하는 플러그인이다. 하나의 CSS를 작성하면 자동으로 Cross browser에 맞게 CSS를 생성해 준다.
- `HTML-CSS-JS Prettify` HTML, CSS, JS에 대해서 코딩을 이쁘게 정렬해주는 기능을 제공해 준다. `Ctrl + Shift + H` 키를 누르면 코드가 이쁘게 정렬된다.
- `FuzzyFilePath` 이미지나 파일의 경로를 자동으로 알려주는 플러그인
- `Markdown Preview` 작성하다가 최종 결과물이 보고 싶다면 `CTRL + B`(빌드. 윈도)하면 브라우저에 작성하고 있는 문서가 보여질 것이다.

- - -

####  환경설정 `Preferences => Setings-User`

```json
{
    "bold_folder_labels": true,
    "color_scheme": "Packages/Theme - Kronuz/Kronuz.tmTheme",
    "dc_bold_folder_labels": true,
    "dc_hide_group_icons": true,
    "dc_highlight_active_sidebar_row": true,
    "dc_mouse_wheel_switches_tabs": true,
    "dc_use_group_icon4": true,
    "dc_use_sidebar_active_row_style2": true,
    "dc_use_soda_search_icons": true,
    "ensure_newline_at_eof_on_save": true,
    "font_face": "NanumGothic",
    "font_size": 12,
    "highlight_line": true,
    "highlight_modified_tabs": true,
    "ignored_packages":
    [
        "Sublime Linter",
        "Vintage"
    ],
    "line_padding_bottom": 1,
    "line_padding_top": 1,
    "shift_tab_unindent": true,
    "soda_folder_icons": true,
    "tab_size": 4,
    "theme": "DC_2.sublime-theme",
    "translate_tabs_to_spaces": true,
    "trim_trailing_white_space_on_save": true,
    "word_wrap": true
}
```


- - -
#### 단축키 활용

- `Ctrl+N` 새문서 만들기
- `Ctrl+Shift+Up`  현재의 행을 윗행과 교체
- `Ctrl+Shift+Down` 현재의 행을 아랫행과 교체합니다
- `Ctrl+/` 주석 만들기 or 주석제거
- `Ctrl+Shift+/` 요소가 포함된 블럭 전체를 주석
- `Ctrl + Alt + ↑,↓` 여러라인을 한꺼번에 선택 가능
- `Ctrl+Shift+Enter` 블럭 앞에 행 삽입
- `Ctrl+Enter` 블럭 뒤에 행 삽입
- `Ctrl+Delete` 커서 뒤 단어 삭제
- `Ctrl+Backspace` 커서 앞 단어 삭제
- `Ctrl+Shift+K` 한줄을 삭제
- `ctrl+[ · ctrl+]` 행 들여쓰기 · 내어쓰기
