# 웹 페이지의 기본적인 레이아웃과 스타일링으로 반복적인 요소 구성하기 (반응형)

##### 참여자: 김현지 (토이 프로젝트)  
  
#### 프로젝트 기간: 2024.01.27 ~ 2024.01.28 (1일)  
  
#### 프로젝트 도구: Html, Css, Reset Css
  
#### 사용 언어: Html, Css
  
### 프로젝트 개요  
  - Overwatch의 캐릭터 프로필 목록을 나열하는 웹 페이지를 구현.
  - Html과 Css를 사용하여 다수의 캐릭터 프로필을 반복적으로 표시하고, 로고 이미지를 추가하여 Overwatch를 시각적으로 나타내는 웹 페이지 구현.
  - Overwatch 팬들이 캐릭터들을 한눈에 살펴볼 수 있는 간단하고 깔끔한 디자인의 웹 페이지임. 
  
### 프로젝트 배경  
Overwatch는 다양한 캐릭터로 유명한 팀 기반 슈팅 게임으로 각 캐릭터의 개성과 외형은 팬들에게 큰 매력 포인트임.
해당 프로젝트는 Overwatch 캐릭터들을 한 페이지에서 간단히 확인할 수 있는 목적으로 진행함.
Html과 Css를 사용해 이러한 캐릭터 목록을 반복적으로 배치하고, 게임 로고와 같은 요소를 추가해 시각 매력이 부각되도록 구현 목적.
  
### 프로젝트 진행 과정  
1. **HTML 구조 설정**
  - `<div class="container">`와같은 div 요소로 웹 페이지 구조 구분.
  - 각 캐릭터를 `<div class="hero">`로 정의하여 반복적으로 배치.
  - 로고 이미지 추가를 위해 `<div class="logo">`에 `<img>` 태그를 사용.

2. **리셋 CSS 적용**
  - `<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/reset-css@5.0.2/reset.min.css">` 사용으로 브라우저 기본 스타일을 리셋하여 일관된 스타일을 유지.

3. **외부 및 내부 CSS 연결**
  - `<link rel="stylesheet" href="./main.css">`를 통해 프로젝트 메인 CSS 파일 불러옴.
  - CSS 파일로 스타일을 정의하여 HTML 요소에 스타일 적용함.

4. **캐릭터 반복 요소 생성**
  - `<div class="hero"><div class="image"></div></div>`와같이 각 캐릭터 프로필 생성을 위해 동일한 구조의 요소를 반복적으로 사용으로 캐릭터 목록을 그리드 형태로 배치.

5. **반응형 설정**
  - `<meta name="viewport" content="width=device-width, initial-scale=1.0">`으로 다양한 기기에서 페이지가 적절히 보이도록 반응형 뷰포트 설정체크.

<p align="center">
  <img width="460" height="300" src="./images/overwatch-heros-main page.png">
</p>