## 학습과 개발을 즐기는 프론트엔드 개발자

안녕하세요. 새로운 기술을 배우고 서비스를 개발하는 것을 즐기는 신입 프론트엔드 개발자 최현성입니다.

개발을 넘어, 사용자들이 사용할 서비스를 상상하고 설계하는 과정에서 행복을 느낍니다.

---

## **Tech Stacks**

### Front-End

- `HTML`, `CSS`, `JS`, `TS`

  - HTML, CSS 마크업에 익숙합니다.

  - 바닐라JS로 DOM 조작을 통한 동적 웹페이지 개발이 가능합니다.

    - 프로토타입, 스코프체인, 렉시컬스코프, 클로저 등에 대해 이해하고 있습니다.

  - TS를 활용해 type, interface 선언과 type narrowing을 수행할 수 있으며, TS를 매우 선호합니다.

- `React`, `React Native`

  - React를 활용한 SPA 웹앱 개발에 익숙합니다.

  - React Lifecycle, V-DOM 등의 기본적인 개념을 이해하고 있습니다.

  - useState, useEffect, useRef, useMemo, useCallback, memo 등의 hook의 동작을 이해하고 적재적소에 활용할 수 있습니다.

  - 중복되는 로직이 존재하거나, 컴포넌트의 로직이 거대해지면, 이를 분리하기 위해 custom hook을 작성합니다.

    - React에서 렌더링과 로직을 분리할 수 있다는 점이 custom hook의 장점이라고 생각합니다.

  - React Native를 활용한 크로스플랫폼 애플리케이션 개발 및 배포 경험이 있습니다. 서브 기술 스택으로 생각하고 소식과 아티클을 챙겨보고 있습니다.

- `CRA`, `Vite`, `Metro`

  - React, React Native에서 사용되는 빌드 도구 및 번들러를 사용해본 경험이 있습니다.

  - Webpack, Babel, Rollup, ESBuild, SWC 등의 번들러/트랜스파일러의 설정파일을 만져본 적은 아직 없지만, 필요성이 생기면 공부해서 적용할 자신이 있습니다.

- `npm`, `yarn`

  - 거의 모든 프로젝트에서 npm과 yarn 중 하나를 선택해 패키지를 관리했습니다.

  - 최근 압축 파일 캐싱이나 심볼릭 링크를 활용해 node_modules의 구조적 문제(의존성 중첩/중복 설치, 유령 의존성 등)를 해결하는 yarn berry, pnpm에 대해 알게 되어, 이를 공부해 프로젝트에 시범 도입 해볼 예정입니다.

- `Jotai`, `Zustand`, ~~`Recoil`~~

  - 전역 상태 관리 라이브러리는 "도입 이유와 목적"이 가장 중요하다고 생각합니다.

  - 전역 상태를 남발하면 상태의 흐름이 props로 전달되지 않아 유지보수 시 어려움이 발생할 수 있기 때문입니다.

  - 대표적인 atomic 패턴인 Jotai와 flux 패턴인 Zustand를 주로 사용하고 있습니다.

  - 두 라이브러리를 사용하며 각 패턴의 장단점과 선택의 중요성을 느꼈습니다.

- `Styled-components`, `Tailwind CSS`

  - Tailwind CSS는 디자인 없이 빠른 프로토타입 제작 시, Styled-components는 디자인과 레이아웃을 미리 정한 뒤 개발하는 경우 주로 사용했습니다.

  - 두 라이브러리 모두 능숙히 사용할 수 있지만, 최근에는 Tailwind CSS의 가독성 저하 문제를 체감하고 있어 Styled-components를 사용하려 하고 있습니다.

- `WebSocket`, `WebRTC`, `Three.js`, `Pixi.js`, **and more...**

  - WebSocket과 Pixi.js(Canvas API)을 활용한 실시간 멀티플레이어 플래시 게임 개발.

  - WebSocket과 webRTC를 활용한 3인 화상채팅 구현.

  - Three.js, R3F, Drei, GSAP를 활용한 우주 망원경 시뮬레이터 개발 등...

  - 새로운 기술에 겁먹지 않고 다양한 것들을 개발해왔습니다. 그리고 이는 현재 진행형입니다.

---

### Back-End & DevOps

- `FastAPI`, `Express`

  - 간단한 프로젝트의 API 서버 제작을 하게 되면 주로 사용했습니다.

- `Docker`, `Docker-compose`

  - 간단한 Dockerfile, .dockerignore, docker-compose.yml 작성법에 대해 알고 있습니다.

  - 서버 측에서 컨테이너를 띄우기 위한 명령어들을 알고 있으며, 컨테이너와 로컬 간 포트포워딩, 볼륨 마운트, 환경변수 주입 등의 흐름을 이해하고 있습니다.

  - Docker, Docker-compose를 활용해 프로젝트를 개인 서버에 배포/운영하고 있습니다.

- `NginX`

  - 개인 서버에서 웹페이지 서빙, 리버스 프록시, https 적용, 도메인 연결 등에 NginX를 활용하고 있습니다.

  - sites-available, sites-enabled 내 파일들을 읽고, 수정할 수 있습니다.

  - Nginx Proxy Manager를 사용해 리버스 프록시를 구성해본 경험이 있습니다.

- `PM2`
  - 개인 서버에서 Express, Next.js, serve 등의 Node.js 기반 애플리케이션의 배포, 클러스터링, 자동 재시작 등을 위해 활용하고 있습니다.

---

### ETC

- `Git`, `Github`

  - Git을 사용한 협업에 문제가 없는 정도의 이해도를 갖추고 있습니다.
    - 브랜치 전략(Github Flow, Fork 등), 커밋 컨벤션 준수, PR, Review를 해본 경험이 있습니다.

---

## Projects

> 링크는 추후 배포/레포 퍼블릭화 후 수정할 예정

> 각 프로젝트의 문제해결 과정, 결과물 등은 각 Repository의 README.md를 참고해주세요.

| Title                                                                                                                                                                     | Timeline            | Project Type  | Description                                                                     | Tech Stack                                                                                                                           | Code                                                                                       |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------- | ------------- | ------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------ |
| **[바다 이야기](https://example.com)**                                                                                                                                    | 24.10.07 ~          | 팀프로젝트    | 실시간 멀티플레이 해양 쓰레기 수집 플래시 게임                                  | React, Vite, TS, Zustand, React-Router, TailwindCSS, Axios, Socket.io, Pixi.js, Express, MongoDB, Redis, Docker-compose, PM2, NginX  | [GitHub](https://github.com/NARARIA03/24-team-ho1ysea.git)                                                               |
| **[화상채팅 웹앱](https://example.com)**                                                                                                                           | 24.11.11 ~ 24.11.24 | 개인 프로젝트 | WebSocket과 WebRTC를 사용한 최대 3인 화상채팅 웹앱                                                          | React, Vite, TS, React-Router, TailwindCSS, Axios, Socket.io, Express, MySQL, NginX, PM2                                             | [GitHub](https://github.com/NARARIA03/WebRTC_Socket_Room)                                  |
| **[ImageTale](https://imagetale.mooo.com)**                                                                                                                               | 24.05.29 ~ 24.11.14 | 팀 프로젝트   | 선택지가 존재하는 AI 인터랙티브 동화책 웹앱 (캡스톤)                            | React, Vite, TS, React-Router, Styled-components, Axios, FastAPI, Docker, NginX                                                      | [GitHub](https://github.com/NARARIA03/ImageTale)                                           |
| **[QRFret 2024](https://concert-14fret-2024.web.app)**                                                                                                                    | 24.09.25 ~ 24.11.01 | 개인 프로젝트 | 공연 추첨 이벤트를 위한 추첨번호 발급, 셋리스트 페이지와 관리자 페이지 구현     | React, Vite, TS, React-Router, TailwindCSS, react-cookie, Firebase(Firestore, Hosting)                                               | [GitHub](https://github.com/NARARIA03/QRFret_2024)                                         |
| **[Exofinder](https://exofinder.github.io/FrontEnd)**                                                                                                                     | 24.09.03 ~ 24.10.06 | 팀 프로젝트   | HWO 망원경 시뮬레이터 / 외계 행성계 시각화 웹앱 (NASA Space Apps Challenge)     | React, Vite, TS, Jotai, TailwindCSS, Three.js, R3F, Drei, GSAP, Axios,                                                               | [GitHub](https://github.com/NARARIA03/Exofinder_FE)                                        |
| **I See You**                                                                                                                                                             | 24.07.07 ~ 24.08.06 | 팀 프로젝트   | GPT-4o를 활용한 시각장애인 시각 보조 음성 대화 애플리케이션 (SeSAC 해커톤 본선) | React Native, TS, React-Navigation, Async-storage, Nativewind, Axios,                                                                | [GitHub](https://github.com/NARARIA03/I-See-You-RN)                                        |
| **[HS DEV](https://chsdev.mooo.com)**                                                                                                                                     | 24.05.09 ~ 24.06.09 | 개인 프로젝트 | OSS 수업 개인 프로젝트(자기소개 페이지, 방명록)                                 | HTML, CSS, JS, FastAPI, NginX, Docker                                                                                                | [GitHub](https://github.com/NARARIA03/2024_OSS_Mypage)                                     |
| **[Genshin.gg](https://genshin.gg.mooo.com)**                                                                                                                             | 24.03.15 ~ 24.07.30 | 개인 프로젝트 | 게임 원신 계정, 캐릭터 스펙 검색 웹앱                                           | React, CRA, JS, React-Router, Recoil, TailwindCSS, FastAPI, NginX, Docker                                                            | [GitHub](https://github.com/NARARIA03/Genshin.gg)                                          |
| **CollaboraMate ([Appstore](https://apps.apple.com/pl/app/collaboramate/id6477861349), [Playstore](https://play.google.com/store/apps/details?id=com.guzicguzic&hl=ko))** | 24.01.14 ~ 24.02.25 | 팀 프로젝트   | 광운대학교 팀 프로젝트 인원 모집 애플리케이션                                   | React Native, JS, React-Navigation, Async-storage, Recoil, Firebase(Auth, Firestore, Database, CloudFunction, CloudMessage), Notifee | [Notion](https://collaboramate.notion.site/CollaboraMate-90933f328cfd4c569c0fbe19f4bdf89c) |
