# 브라우저 시장 트랜드

![GitHub last commit](https://img.shields.io/github/last-commit/smsoftlab/documentstudy?style=plastic)
>
> - 일반 브라우저 기능이 아닌 Hybrid브라우저 기능으로 C/S 시장에 대응 방향에 대한 내용을  설명 하고자 합니다.
> - CEF3(크롬기반)과 엣지기반의 내장 브라우저 2가지 종류 존재

#

## 1. Chromium Embedded Framework(CEF) - 크롬시장

![CEF)](https://bytebucket.org/ravatar/%7Bfe200f46-6de8-41ce-9e54-1826c5610083%7D?ts=608609)

# [소개](https://ko.wikipedia.org/wiki/%ED%81%AC%EB%A1%9C%EB%AF%B8%EC%97%84_%EC%9E%84%EB%B2%A0%EB%94%94%EB%93%9C_%ED%94%84%EB%A0%88%EC%9E%84%EC%9B%8C%ED%81%AC "소개사이트 이동")

## 장점

1. 네이티브와 Web간에 인터페이스 확장이 용이
2. 시장트렌드에 빠르게 대응
3. 멀티CPU 지원
4. 많은 개발 응용 프로그램 존재

## 단점

1. 확장성용이는 많은 연동 인터페이스 기능으로 구현돠 유지보수 불편
2. 시장 트렌드에 빠르게 대응으로 기능 변경 및 추가건 확인
3. 개발 배포의 용량이 엄청 큰 리스크

## 2. webview2  - 엣지브라우저 시장

# [소개](https://docs.microsoft.com/en-us/microsoft-edge/webview2/ "소개사이트이동")

Microsoft Edge WebView2 컨트롤을 사용하면 네이티브 응용 프로그램에 웹 기술 (HTML, CSS 및 JavaScript)을 포함 할 수 있습니다. WebView2 컨트롤은 Microsoft Edge (Chromium) 를 렌더링 엔진으로 사용하여 네이티브 응용 프로그램에 웹 콘텐츠를 표시합니다. WebView2를 사용하면 네이티브 애플리케이션의 여러 부분에 웹 코드를 포함하거나 단일 WebView 내에서 전체 네이티브 애플리케이션을 빌드 할 수 있습니다.
![( Microsoft Edge (Chromium))](<https://docs.microsoft.com/en-us/microsoft-edge/webview2/media/webview2/whatwebview.png>)

## 장점

1. 네이티브와 Web간에 인터페이스 확장 가능(부분적)
2. 개발자 배포는 CEF보다는 적음
3. 멀티CPU 지원

## 단점

1. 네이티와 Web인터페이스 CEF 확작성 부족

# 대응전략

제품  | 사용용도
------------- | -------------
CEF  | 기능을 많이 포함하는 Hybrid유형의 제품

WebView2  | HTS뉴스 및 웹서비스 기능 최적
