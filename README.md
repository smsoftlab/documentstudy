# (주) 에스엠소프트랩   자료 및 문서 공유

![](https://user-images.githubusercontent.com/42054927/99507249-7e0d5b00-29c6-11eb-8f6b-5a954318ea9a.png)

![GitHub last commit](https://img.shields.io/github/last-commit/smsoftlab/documentstudy?style=plastic)

#

# 할용목적

- 각 팀별 자료 조사 및  신기능등 사원간 공유 목적으로 한다.
- 연구소팀에서 신규기능 및 Web 개발에 필요한 정보를 수집하고자 합니다.

# 시장동향 및 관련자료 보고 내용 정리

내용  | 관련자료 링크
------------- | -------------
웹브라우저 시장동향보고  | [WebView2 와 Cef 비교](marketreport/Browsertrend.md)
KSMBuilder 방향성보고   | 주소연결
내용설명  | 주소연결
다국어 처리 변환모듈  | [Github링크](https://github.com/robnyman/TranslationTester)
내용설명  | 주소연결

# Doc 폴더 문서내용 자료모음  

문서내용  | 참고사이트 링크
------------- | -------------
[01.Electron-readme](https://github.com/smsoftlab/documentstudy/blob/main/01.Electron/README.md "01.Electron")  | Electron 개론설명
[01.Electron-url](https://github.com/smsoftlab/documentstudy/blob/main/01.Electron/URL.md")  | Electron 관련 각 사이트 정리 내용 기술
continue... | continue...

#

### 마크다운(MarkDown)이란

- **마크다운(Markdown)**은 웹상에서 글을 쓰는 모든 사람들을 위한 글쓰기 도구(서식, 포맷, 양식) 입니다.
- 마크다운(Markdown)은 HTML을 몰라도 약간의 노력으로 글자를 HTML형식으로 변환시켜 줍니다.(단 변환도구는 따로 있어야 합니다)
- 마크다운(Markdown)은 쉽게 글을 쓸 수 있도록 해 주고, 읽는 사람에게도 쉽게 읽힐 수 있도록 해 주는 간소한 서식(포맷)입니다.
- 마크다운(Markdown)은 꾸밈없는 간소한 문법으로 글쓰기에 집중 할 수 있도록 도와줍니다.
- 소스코드를 읽기 기능이 편리 합니다

#

@소스보고일부예제

```js
const electron = require('electron')
const proc = require('child_process')

// will print something similar to /Users/maf/.../Electron
console.log(electron)

// spawn Electron
const child = proc.spawn(electron)
```

**단 간단하기에 모든 HTML을 지원하지는 않습니다.**

#

# 마크다운(MarkDown) Online Edit 기능 따라해보기

![](https://pandao.github.io/editor.md/images/logos/editormd-logo-180x180.png)

### 특징

- 툴바 기능을 이용해서 편집가능
- 편집한 내용을 복사해서 사용가능
- 중국어/영어만 메뉴가 보임(영어추천)

[작성밥법 따라해보기 (English)](https://pandao.github.io/editor.md/en.html)
