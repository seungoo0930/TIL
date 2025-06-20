# TIL
#### 2025-06-19
- 웹게임

웹게임: HTML, CSS, JavaScript 같은 웹 기술을 이용해서 만든 게임
PC, 모바일에서도 브라우저만 있으면 플레이 가능

- 웹게임 개발 구성 요소

HTML: 게임의 구조(텍스트, 버튼, 이미지 등)를 만듦
CSS: 디자인(색, 폰트, 애니메이션 등)을 꾸밈
JavaScript (JS): 게임의 로직과 상호작용을 담당함 (예: 버튼 누르면 캐릭터 이동)
Canvas/WebGL: 그래픽 기반 게임을 만들 때 사용 (2D, 3D 가능)

- 웹게임 예시

텍스트 어드벤처: 선택지로 진행되는 이야기형 게임 (예: "당신은 어디로 갈 것인가?")
아케이드 게임:	브라우저에서 하는 미니게임 (예: 테트리스, 공 튕기기 등)
퍼즐 게임:	숫자 맞추기, 단어 퀴즈, 탈출 게임
RPG/시뮬레이션: 웹 기반으로 스토리를 따라가며 성장하는 게임

- 웹게임의 장점

설치 불필요 – 링크만 있으면 누구나 접근 가능
멀티 플랫폼 – PC, 태블릿, 스마트폰 모두 지원
배포 쉬움 – GitHub Pages, Netlify 같은 데에 쉽게 올릴 수 있음
학습 용이 – 코딩을 배우기 좋은 프로젝트 주제

- 대표 기술 스택

초급용: HTML + CSS + JS
중급: Canvas API, Phaser.js(게임 엔진), localStorage (저장기능)
고급: WebGL, WebSockets(실시간 통신), React + Three.js

- HTML 버전(시간 여행자의 메모장)

<!DOCTYPE html>
<html lang="ko">
<head>
  <meta charset="UTF-8">
  <title>시간 여행자의 메모장</title>
  <style>
    body {
      font-family: 'Pretendard', sans-serif;
      background-color: #f4f4f4;
      color: #222;
      padding: 30px;
      max-width: 600px;
      margin: auto;
    }
    h1 {
      text-align: center;
    }
    #story {
      margin-top: 20px;
      font-size: 1.2em;
    }
    .choice {
      margin-top: 20px;
    }
    button {
      display: block;
      margin: 10px 0;
      padding: 10px 20px;
      font-size: 1em;
      background-color: #444;
      color: white;
      border: none;
      border-radius: 8px;
      cursor: pointer;
    }
    button:hover {
      background-color: #666;
    }
  </style>
</head>
<body>
