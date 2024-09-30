
# 프론트엔드 개발자 김동규입니다

## 자기소개
Typescript, Next.js기반의 프론트엔드 개발자입니다.

## 기술스택
<p>
  <img alt="React" src="https://img.shields.io/badge/-React-45b8d8?style=flat-square&logo=react&logoColor=white" />
  <img alt="Nextjs" src="https://img.shields.io/badge/-Next.js-000000?style=flat-square&logo=Next.js&logoColor=white" />
  
  <img alt="TypeScript" src="https://img.shields.io/badge/-TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white" />
  <img alt="JavaScript" src="https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javaScript&logoColor=white" />
  
  <img alt="redux" src="https://img.shields.io/badge/-Redux-764ABC?style=flat-square&logo=redux&logoColor=white" />
  <img alt="react-query" src="https://img.shields.io/badge/-React Query-FF4154?style=flat-square&logo=React Query&logoColor=white" />
  <img alt="zustand" src="https://img.shields.io/badge/-Zustand-7F00FF?style=flat-square" />

  <img alt="tailwindcss" src="https://img.shields.io/badge/-tailwindcss-06B6D4?style=flat-square&logo=Tailwind Css&logoColor=white" />
  <img alt="Sass" src="https://img.shields.io/badge/-Sass-CC6699?style=flat-square&logo=sass&logoColor=white" />
  <img alt="Styled Components" src="https://img.shields.io/badge/-Styled_Components-db7092?style=flat-square&logo=styled-components&logoColor=white" />

  <img alt="lambda" src="https://img.shields.io/badge/-lambda-FF9900?style=flat-square&logo=awslambda&logoColor=white" />
  <img alt="ecs" src="https://img.shields.io/badge/-ecs-FF9900?style=flat-square&logo=amazonecs&logoColor=white" />
  <img alt="fargate" src="https://img.shields.io/badge/-fargate-FF9900?style=flat-square&logo=awsfargate&logoColor=white" />
  <img alt="s3" src="https://img.shields.io/badge/-s3-569A31?style=flat-square&logo=amazons3&logoColor=white" />
  
  <img alt="MongoDB" src="https://img.shields.io/badge/-MongoDB-13aa52?style=flat-square&logo=mongodb&logoColor=white" />
  <img alt="Nodejs" src="https://img.shields.io/badge/-Nodejs-43853d?style=flat-square&logo=Node.js&logoColor=white" />
  <img alt="expressjs" src="https://img.shields.io/badge/-Express.js-000000?style=flat-square&logo=Express&logoColor=white" />

  
  <img alt="Docker" src="https://img.shields.io/badge/-Docker-46a2f1?style=flat-square&logo=docker&logoColor=white" />
  <img alt="Webpack" src="https://img.shields.io/badge/-Webpack-8DD6F9?style=flat-square&logo=webpack&logoColor=white" /> 
  <img alt="git" src="https://img.shields.io/badge/-Git-F05032?style=flat-square&logo=git&logoColor=white" />
  <img alt="html5" src="https://img.shields.io/badge/-HTML5-E34F26?style=flat-square&logo=html5&logoColor=white" />
  <img alt="css" src="https://img.shields.io/badge/-CSS3-1572B6?style=flat-square&logo=CSS3&logoColor=white" />
</p>


## frontendMentor & icodethis : 30day challenge

브라우저 서포트 93%이하의 기능 테스트 및 매일 아침 손풀이 용으로 사용하는 레포입니다. [link](https://github.com/caffesale/fe-practice.git)

- day1: qr-code-component-main
- day2: blog-preview-card-main
- day3: contact-form 
  - css subgrid 활용
  - js없이 css selector만을 활용한 invalid feedback
- day4 ~ day5: product-list-width
  - 최적화 테스트 및 derived State의 검증
- day6: social-links-profile-main
- day7 ~ day8: newsletter-sign-up-with-success-message-main
  - dialog element:
    - width:100%로 덮을 수 없는 padding을 가졌기 때문에 네거티브 마진으로도 패딩이 남음.
    - display: grid, flex값일 때 dialog.close() method 동작 안함.
    - dialog.style.display= none으로는 해결 가능하나 스크린 리더 이슈 발생 가능성 있음
- day9: faq-accordion-main
  - details mark: safari는 ::-webkit-details-marker selector로 따로 처리하기
- day10: Multi-toggle
- day11 ~ 12: bento-grid
  - cascading을 최대한 활용해 복잡도를 줄일 수 있는 방법이 없는지 검증 필요
  - grid-template-area로는 해결 가능하나 html구조 변경이 강요됨
  - grid-template-rows의 경우 매직넘버를 사용하는 해결책이라서 유연성이 낮아 비선호.
- day13: pricing-card
- day14: horizontal-scroll-infinite
  - scroller__inner animation: width: max-content로 inner가 container보다 넓게 수정
  - scroller__inner animation: translate(calc(-50% - **--gap // 2**))
  - prefers-reduced-motion: true접근성을 고려한 flex-wrap: nowrap처리 -> animation이 없을 시 표시영역 외부 요소도 볼 수 있도록 접근성 개선
  - mask는 브라우저 서포트상 -webkit-mask필수
- day15: typo-effects
  - typo이펙트의 경우 monospace계열의 고정폭 글꼴, 영어의 조건이 훨씬 쉬움
  - glitch, hacker effect
- day16 ~ day17: prefetching, requestmemoization
- day18: footer-ui
- day19: 프로그래머스 실전과제형 게시물 레이아웃 재구성하기
- day20: circle-team
  - svg, textPath 학습하기
  - sin, cos, calcPosition
- day21~23: Intro section with dropdown navigation
- day24: Interactive rating component
- day25~26: svg tutorial

## 세컨드브레인 - 메모 상자

### 2024.09

- [S3 파일업로드 유스케이스별 비교](https://publish.obsidian.md/my-para-til/Post/S3+%ED%8C%8C%EC%9D%BC+%EC%97%85%EB%A1%9C%EB%93%9C+%EC%9C%A0%EC%8A%A4%EC%BC%80%EC%9D%B4%EC%8A%A4%EB%B3%84+%EB%B9%84%EA%B5%90)
- [aws lambda 고려사항](https://publish.obsidian.md/my-para-til/Resources/aws-usage/lambda-%EA%B8%B0%EB%B3%B8)
- 도커 시리즈
  - [Dockerfile](https://publish.obsidian.md/my-para-til/Project/Docker/Dockerfile)
  - [docker-compose](https://publish.obsidian.md/my-para-til/Project/Docker/docker-compose)
  - [qna](https://publish.obsidian.md/my-para-til/Project/Docker/docker-qna)
  - [volume](https://publish.obsidian.md/my-para-til/Project/Docker/docker-volume)
  - [network](https://publish.obsidian.md/my-para-til/Project/Docker/docker-network)
  - [자원 할당](https://publish.obsidian.md/my-para-til/Project/Docker/docker-%EC%9E%90%EC%9B%90%ED%95%A0%EB%8B%B9)
- [AI 스크립트 예시](https://publish.obsidian.md/my-para-til/Resources/AI-script/Prompt+Example)
- [람다함수 기본](https://publish.obsidian.md/my-para-til/Resources/aws-usage/lambda-%EA%B8%B0%EB%B3%B8)
- [추론의 일방통행성](https://publish.obsidian.md/my-para-til/000_ZettelKasten/%EC%B6%94%EB%A1%A0%EC%9D%98+%EC%9D%BC%EB%B0%A9%ED%86%B5%ED%96%89%EC%84%B1)
- [정형화에 반하는 사회규범](https://publish.obsidian.md/my-para-til/000_ZettelKasten/%EC%A0%84%ED%98%95%ED%99%94%EC%97%90+%EB%B0%98%ED%95%98%EB%8A%94+%EC%82%AC%ED%9A%8C+%EA%B7%9C%EB%B2%94)
- SEO 시리즈
  - [구글 서치 센터](https://publish.obsidian.md/my-para-til/Resources/SEO/Google+Search+Central/index)
  - [스타터 가이드](https://publish.obsidian.md/my-para-til/Resources/SEO/Google+Search+Central/index)
  - [robots.txt](https://publish.obsidian.md/my-para-til/Resources/SEO/Google+Search+Central/robots.txt)
  - [sitemap](https://publish.obsidian.md/my-para-til/Resources/SEO/Google+Search+Central/sitemap)
  - [기술적 요구사항과 스팸 정책](https://publish.obsidian.md/my-para-til/Resources/SEO/Google+Search+Central/%EA%B8%B0%EC%88%A0%EC%A0%81+%EC%9A%94%EA%B5%AC%EC%82%AC%ED%95%AD%EA%B3%BC+%EC%8A%A4%ED%8C%B8+%EC%A0%95%EC%B1%85)
  - [simplilearn](https://publish.obsidian.md/my-para-til/Resources/SEO/Simplilearn)
  - [fireship SEO](https://publish.obsidian.md/my-para-til/Resources/SEO/Fireship+SEO)
- [승리한 바닷가재](https://publish.obsidian.md/my-para-til/000_ZettelKasten/%EC%8A%B9%EB%A6%AC%ED%95%9C+%EB%B0%94%EB%8B%B7%EA%B0%80%EC%9E%AC)
- [뇌 계산기와 자동화](https://publish.obsidian.md/my-para-til/000_ZettelKasten/%EB%87%8C+%EA%B3%84%EC%82%B0%EA%B8%B0%EC%99%80+%EC%9E%90%EB%8F%99%ED%99%94)
- [승자가 독식한다](https://publish.obsidian.md/my-para-til/000_ZettelKasten/%EC%8A%B9%EC%9E%90%EA%B0%80+%EB%8F%85%EC%8B%9D%ED%95%9C%EB%8B%A4)
- [아키텍처는 이어진 직물이다](https://publish.obsidian.md/my-para-til/000_ZettelKasten/%EC%95%84%ED%82%A4%ED%85%8D%EC%B2%98%EB%8A%94+%EC%9D%B4%EC%96%B4%EC%A7%84+%EC%A7%81%EB%AC%BC%EC%9D%B4%EB%8B%A4)
- [불완전한 지식에 기초해 행동하기](https://publish.obsidian.md/my-para-til/000_ZettelKasten/%EB%B6%88%EC%99%84%EC%A0%84%ED%95%9C+%EC%A7%80%EC%8B%9D%EC%97%90+%EA%B8%B0%EC%B4%88%ED%95%B4+%ED%96%89%EB%8F%99%ED%95%98%EA%B8%B0)

### 2024.08

- [좋은 유저 스토리를 작성하기 위한 원칙](https://publish.obsidian.md/my-para-til/000_ZettelKasten/%EC%A2%8B%EC%9D%80+%EC%9C%A0%EC%A0%80+%EC%8A%A4%ED%86%A0%EB%A6%AC%EB%A5%BC+%EC%9E%91%EC%84%B1%ED%95%98%EA%B8%B0+%EC%9C%84%ED%95%9C+%EC%9B%90%EC%B9%99)
- [frontend action](https://publish.obsidian.md/my-para-til/000_ZettelKasten/frontend-action)
- [소프트웨어에서 가장 가치있는 부분](https://publish.obsidian.md/my-para-til/000_ZettelKasten/%EC%86%8C%ED%94%84%ED%8A%B8%EC%9B%A8%EC%96%B4%EC%97%90%EC%84%9C+%EA%B0%80%EC%9E%A5+%EA%B0%80%EC%B9%98%EC%9E%88%EB%8A%94+%EB%B6%80%EB%B6%84)
- [vscode & yarnberry오류](https://publish.obsidian.md/my-para-til/Resources/%ED%8A%B8%EB%9F%AC%EB%B8%94%EC%8A%88%ED%8C%85/yarn_berry%26vscode%3D%3EmoduleNotFound)
- [AWS ECS: 서킷브레이커](https://publish.obsidian.md/my-para-til/Resources/%ED%8A%B8%EB%9F%AC%EB%B8%94%EC%8A%88%ED%8C%85/AWS-ECS%EC%84%9C%EB%B9%84%EC%8A%A4%3D%3E%EC%84%9C%ED%82%B7%EB%B8%8C%EB%A0%88%EC%9D%B4%EC%BB%A4+%EB%AC%B8%EC%A0%9C)
- [최소권한의 원칙](https://publish.obsidian.md/my-para-til/000_ZettelKasten/%EC%B5%9C%EC%86%8C%EA%B6%8C%ED%95%9C%EC%9D%98+%EC%9B%90%EC%B9%99%EC%97%90+%EC%9E%85%EA%B0%81%ED%95%9C+%EA%B6%8C%ED%95%9C+%EA%B4%80%EB%A6%AC)
- [sort](https://publish.obsidian.md/my-para-til/AreaOfResponse/LeetCode/Sort)
- [uf 코드 추가](https://publish.obsidian.md/my-para-til/AreaOfResponse/LeetCode/union_find)

### 2024.07

- [다양한 입출력 방법](https://publish.obsidian.md/my-para-til/Project/%EC%9A%B4%EC%98%81%EC%B2%B4%EC%A0%9C_%EB%B3%B5%EC%8A%B5/%EB%8B%A4%EC%96%91%ED%95%9C+%EC%9E%85%EC%B6%9C%EB%A0%A5+%EB%B0%A9%EB%B2%95)
- [데이터](https://publish.obsidian.md/my-para-til/Project/%EC%9A%B4%EC%98%81%EC%B2%B4%EC%A0%9C_%EB%B3%B5%EC%8A%B5/%EB%8D%B0%EC%9D%B4%ED%84%B0)
- [장치 컨트롤러와 장치 드라이버](https://publish.obsidian.md/my-para-til/Project/%EC%9A%B4%EC%98%81%EC%B2%B4%EC%A0%9C_%EB%B3%B5%EC%8A%B5/%EC%9E%A5%EC%B9%98+%EC%BB%A8%ED%8A%B8%EB%A1%A4%EB%9F%AC%EC%99%80+%EC%9E%A5%EC%B9%98+%EB%93%9C%EB%9D%BC%EC%9D%B4%EB%B2%84)
- [보조기억장치](https://publish.obsidian.md/my-para-til/Project/%EC%9A%B4%EC%98%81%EC%B2%B4%EC%A0%9C_%EB%B3%B5%EC%8A%B5/%EB%B3%B4%EC%A1%B0%EA%B8%B0%EC%96%B5%EC%9E%A5%EC%B9%98)
- [메모리와 캐시메모리](https://publish.obsidian.md/my-para-til/Project/%EC%9A%B4%EC%98%81%EC%B2%B4%EC%A0%9C_%EB%B3%B5%EC%8A%B5/%EB%A9%94%EB%AA%A8%EB%A6%AC%EC%99%80+%EC%BA%90%EC%8B%9C%EB%A9%94%EB%AA%A8%EB%A6%AC)
- [CISC와 RISC](https://publish.obsidian.md/my-para-til/Project/%EC%9A%B4%EC%98%81%EC%B2%B4%EC%A0%9C_%EB%B3%B5%EC%8A%B5/CISC%EC%99%80+RISC)
- [빠른 CPU를 위한 설계기법](https://publish.obsidian.md/my-para-til/Project/%EC%9A%B4%EC%98%81%EC%B2%B4%EC%A0%9C_%EB%B3%B5%EC%8A%B5/%EB%B9%A0%EB%A5%B8+CPU%EB%A5%BC+%EC%9C%84%ED%95%9C+%EC%84%A4%EA%B3%84+%EA%B8%B0%EB%B2%95)
- [명령어 사이클과 인터럽트](https://publish.obsidian.md/my-para-til/Project/%EC%9A%B4%EC%98%81%EC%B2%B4%EC%A0%9C_%EB%B3%B5%EC%8A%B5/%EB%AA%85%EB%A0%B9%EC%96%B4+%EC%82%AC%EC%9D%B4%ED%81%B4%EA%B3%BC+%EC%9D%B8%ED%84%B0%EB%9F%BD%ED%8A%B8)
- [ALU와 제어장치](https://publish.obsidian.md/my-para-til/Project/%EC%9A%B4%EC%98%81%EC%B2%B4%EC%A0%9C_%EB%B3%B5%EC%8A%B5/ALU%EC%99%80+%EC%A0%9C%EC%96%B4%EC%9E%A5%EC%B9%98)
- [명령어](https://publish.obsidian.md/my-para-til/Project/%EC%9A%B4%EC%98%81%EC%B2%B4%EC%A0%9C_%EB%B3%B5%EC%8A%B5/%EB%AA%85%EB%A0%B9%EC%96%B4)
- [컴퓨터 구조](https://publish.obsidian.md/my-para-til/Project/%EC%9A%B4%EC%98%81%EC%B2%B4%EC%A0%9C_%EB%B3%B5%EC%8A%B5/%EC%BB%B4%ED%93%A8%ED%84%B0+%EA%B5%AC%EC%A1%B0)
- [상태 다이어그램](https://publish.obsidian.md/my-para-til/Project/UML_%EC%8B%A4%EC%A0%84%EC%97%90%EC%84%9C%EB%8A%94_%EC%9D%B4%EA%B2%83%EB%A7%8C_%EC%93%B4%EB%8B%A4/%EC%83%81%ED%83%9C+%EB%8B%A4%EC%9D%B4%EC%96%B4%EA%B7%B8%EB%9E%A8)
- [패키지 다이어그램](https://publish.obsidian.md/my-para-til/000_ZettelKasten/%EB%B0%98%EA%B0%91%EC%8A%B5%EB%8B%88%EB%8B%A4!)
- [CPU 스케쥴링](https://publish.obsidian.md/my-para-til/Project/%EC%9A%B4%EC%98%81%EC%B2%B4%EC%A0%9C_%EB%B3%B5%EC%8A%B5/CPU+%EC%8A%A4%EC%BC%80%EC%A5%B4%EB%A7%81)
- [유스케이스 다이어그램](https://publish.obsidian.md/my-para-til/Project/UML_%EC%8B%A4%EC%A0%84%EC%97%90%EC%84%9C%EB%8A%94_%EC%9D%B4%EA%B2%83%EB%A7%8C_%EC%93%B4%EB%8B%A4/%EC%9C%A0%EC%8A%A4%EC%BC%80%EC%9D%B4%EC%8A%A4+%EB%8B%A4%EC%9D%B4%EC%96%B4%EA%B7%B8%EB%9E%A8)
- [UML과 CodeSmell](https://publish.obsidian.md/my-para-til/000_ZettelKasten/UML%EB%A1%9C+CodeSmell+%EC%B0%BE%EA%B8%B0)
- [시퀀스 다이어그램](https://publish.obsidian.md/my-para-til/Project/UML_%EC%8B%A4%EC%A0%84%EC%97%90%EC%84%9C%EB%8A%94_%EC%9D%B4%EA%B2%83%EB%A7%8C_%EC%93%B4%EB%8B%A4/%EC%8B%9C%ED%80%80%EC%8A%A4+%EB%8B%A4%EC%9D%B4%EC%96%B4%EA%B7%B8%EB%9E%A8)
- [위상 정렬](https://publish.obsidian.md/my-para-til/AreaOfResponse/LeetCode/%EA%B7%B8%EB%9E%98%ED%94%84+%EC%A1%B0%EA%B1%B4%EC%A0%95%EB%A6%AC)
- [클래스 다이어그램](https://publish.obsidian.md/my-para-til/Project/UML_%EC%8B%A4%EC%A0%84%EC%97%90%EC%84%9C%EB%8A%94_%EC%9D%B4%EA%B2%83%EB%A7%8C_%EC%93%B4%EB%8B%A4/%ED%81%B4%EB%9E%98%EC%8A%A4+%EB%8B%A4%EC%9D%B4%EC%96%B4%EA%B7%B8%EB%9E%A8)
- [그래프 조건정리](https://publish.obsidian.md/my-para-til/AreaOfResponse/LeetCode/%EA%B7%B8%EB%9E%98%ED%94%84+%EC%A1%B0%EA%B1%B4%EC%A0%95%EB%A6%AC)
- [REST API - 6 constraints](https://publish.obsidian.md/my-para-til/000_ZettelKasten/REST+API+-+6+constraints)
- [애자일 프로세스](https://publish.obsidian.md/my-para-til/000_ZettelKasten/%EC%95%A0%EC%9E%90%EC%9D%BC+%ED%94%84%EB%A1%9C%EC%84%B8%EC%8A%A4)
- [운영체제와 프로세스&스레드](https://publish.obsidian.md/my-para-til/Project/%EC%9A%B4%EC%98%81%EC%B2%B4%EC%A0%9C_%EB%B3%B5%EC%8A%B5/%EC%9A%B4%EC%98%81%EC%B2%B4%EC%A0%9C%EC%99%80+%ED%94%84%EB%A1%9C%EC%84%B8%EC%8A%A4%26%EC%8A%A4%EB%A0%88%EB%93%9C)
- [Authentication & Authorization](https://publish.obsidian.md/my-para-til/Project/%EC%9D%B8%EC%A6%9D%26%EC%9D%B8%EA%B0%80/Authentication+%26+Authorization)
- [Basic Authentication](https://publish.obsidian.md/my-para-til/Project/%EC%9D%B8%EC%A6%9D%26%EC%9D%B8%EA%B0%80/Basic+Authentication)
- [JWT](https://publish.obsidian.md/my-para-til/Project/%EC%9D%B8%EC%A6%9D%26%EC%9D%B8%EA%B0%80/JWT+Authentication)
- [OAuth2.0](https://publish.obsidian.md/my-para-til/Project/%EC%9D%B8%EC%A6%9D%26%EC%9D%B8%EA%B0%80/OAuth2.0+-+Open+Authorization)
- [기저율과 대표성의 대결](https://publish.obsidian.md/my-para-til/000_ZettelKasten/%EA%B8%B0%EC%A0%80%EC%9C%A8%EA%B3%BC+%EB%8C%80%ED%91%9C%EC%84%B1%EC%9D%98+%EB%8C%80%EA%B2%B0)
- [왜, 언제 UML을 사용하나?](https://publish.obsidian.md/my-para-til/Project/UML_%EC%8B%A4%EC%A0%84%EC%97%90%EC%84%9C%EB%8A%94_%EC%9D%B4%EA%B2%83%EB%A7%8C_%EC%93%B4%EB%8B%A4/%EC%99%9C%2C+%EC%96%B8%EC%A0%9C+UML%EC%9D%84+%EC%82%AC%EC%9A%A9%ED%95%B4%EC%95%BC+%ED%95%98%EB%8A%94%EA%B0%80%3F)
- [REST API TIP](https://publish.obsidian.md/my-para-til/Project/REST+API+QUICK+TIP)
- [중복 다루기](https://publish.obsidian.md/my-para-til/000_ZettelKasten/%EC%A4%91%EB%B3%B5+%EB%8B%A4%EB%A3%A8%EA%B8%B0)
- [예광탄 - 위험우선관리와 가치우선관리](https://publish.obsidian.md/my-para-til/000_ZettelKasten/%EC%98%88%EA%B4%91%ED%83%84+-+%EC%9C%84%ED%97%98%EC%9A%B0%EC%84%A0%EA%B4%80%EB%A6%AC%EC%99%80+%EA%B0%80%EC%B9%98%EC%9A%B0%EC%84%A0%EA%B4%80%EB%A6%AC)

### 2024.06

- [품질은 요구사항의 일부다](https://publish.obsidian.md/my-para-til/000_ZettelKasten/%ED%92%88%EC%A7%88%EC%9D%80+%EC%9A%94%EA%B5%AC%EC%82%AC%ED%95%AD%EC%9D%98+%EC%9D%BC%EB%B6%80%EB%8B%A4)
- [가역성, 상자를 열 용기가 있는가?](https://publish.obsidian.md/my-para-til/000_ZettelKasten/%EA%B0%80%EC%97%AD%EC%84%B1%2C+%EC%83%81%EC%9E%90%EB%A5%BC+%EC%97%B4+%EC%9A%A9%EA%B8%B0%EA%B0%80+%EC%9E%88%EB%8A%94%EA%B0%80%3F)
- [직교성, 소프트웨어 품질](https://publish.obsidian.md/my-para-til/000_ZettelKasten/%EC%A7%81%EA%B5%90%EC%84%B1%2C+%EC%86%8C%ED%94%84%ED%8A%B8%EC%9B%A8%EC%96%B4+%ED%92%88%EC%A7%88)
- [스크럼 팀의 성과를 생각할 때 고려해야 할 점](https://publish.obsidian.md/my-para-til/000_ZettelKasten/%EC%8A%A4%ED%81%AC%EB%9F%BC+%ED%8C%80%EC%9D%98+%EC%84%B1%EA%B3%BC%EB%A5%BC+%EC%83%9D%EA%B0%81%ED%95%A0+%EB%95%8C+%EA%B3%A0%EB%A0%A4%ED%95%B4%EC%95%BC+%ED%95%A0+%EC%A0%90)
- [스프링이 트랜잭션을 다루는 방식](https://publish.obsidian.md/my-para-til/Project/%EC%9E%90%EB%B0%94_%EB%8D%B0%EC%9D%B4%ED%84%B0%EB%B2%A0%EC%9D%B4%EC%8A%A4_%EA%B0%95%EC%9D%98/%EC%8A%A4%ED%94%84%EB%A7%81%EC%9D%B4+%ED%8A%B8%EB%9E%9C%EC%9E%AD%EC%85%98%EC%9D%84+%EB%8B%A4%EB%A3%A8%EB%8A%94+%EB%B0%A9%EC%8B%9D)
- [스프링이 트랜잭션을 다루는 방식_2](https://publish.obsidian.md/my-para-til/Project/%EC%9E%90%EB%B0%94_%EB%8D%B0%EC%9D%B4%ED%84%B0%EB%B2%A0%EC%9D%B4%EC%8A%A4_%EA%B0%95%EC%9D%98/%EC%8A%A4%ED%94%84%EB%A7%81%EC%9D%B4+%ED%8A%B8%EB%9E%9C%EC%9E%AD%EC%85%98%EC%9D%84+%EB%8B%A4%EB%A3%A8%EB%8A%94+%EB%B0%A9%EC%8B%9D_2)
- [JDBC 이해](https://publish.obsidian.md/my-para-til/Project/%EC%9E%90%EB%B0%94_%EB%8D%B0%EC%9D%B4%ED%84%B0%EB%B2%A0%EC%9D%B4%EC%8A%A4_%EA%B0%95%EC%9D%98/JDBC+%EC%9D%B4%ED%95%B4)
- [JDBC 직접 사용하기](https://publish.obsidian.md/my-para-til/Project/%EC%9E%90%EB%B0%94_%EB%8D%B0%EC%9D%B4%ED%84%B0%EB%B2%A0%EC%9D%B4%EC%8A%A4_%EA%B0%95%EC%9D%98/JDBC+%EC%A7%81%EC%A0%91+%EC%82%AC%EC%9A%A9%ED%95%98%EA%B8%B0)
- [자바 예외 이해](https://publish.obsidian.md/my-para-til/Project/%EC%9E%90%EB%B0%94_%EB%8D%B0%EC%9D%B4%ED%84%B0%EB%B2%A0%EC%9D%B4%EC%8A%A4_%EA%B0%95%EC%9D%98/%EC%9E%90%EB%B0%94+%EC%98%88%EC%99%B8+%EC%9D%B4%ED%95%B4)
- [가장 큰 낭비는 과잉 생산의 낭비다](https://publish.obsidian.md/my-para-til/000_ZettelKasten/%EA%B0%80%EC%9E%A5+%ED%81%B0+%EB%82%AD%EB%B9%84%EB%8A%94+%EA%B3%BC%EC%9E%89+%EC%83%9D%EC%82%B0%EC%9D%98+%EB%82%AD%EB%B9%84%EB%8B%A4)
- [TDD를 적용하기 힘든 상황이 맞는가?](https://publish.obsidian.md/my-para-til/000_ZettelKasten/TDD%EB%A5%BC+%EC%A0%81%EC%9A%A9%ED%95%98%EA%B8%B0+%ED%9E%98%EB%93%A0+%EC%83%81%ED%99%A9%EC%9D%B4+%EB%A7%9E%EB%8A%94%EA%B0%80%3F)
- [소프트웨어 개발의 메타포 - 건축과 가드닝](https://publish.obsidian.md/my-para-til/000_ZettelKasten/%EC%86%8C%ED%94%84%ED%8A%B8%EC%9B%A8%EC%96%B4+%EA%B0%9C%EB%B0%9C%EC%9D%98+%EB%A9%94%ED%83%80%ED%8F%AC+-+%EA%B1%B4%EC%B6%95%EA%B3%BC+%EA%B0%80%EB%93%9C%EB%8B%9D)
- [TDD의 세 가지 효용](https://publish.obsidian.md/my-para-til/000_ZettelKasten/TDD%EC%9D%98+%EC%84%B8+%EA%B0%80%EC%A7%80+%ED%9A%A8%EC%9A%A9)
- [TDD 요약](https://publish.obsidian.md/my-para-til/000_ZettelKasten/TDD+%EC%9A%94%EC%95%BD)
- [감정이라는 꼬리가 이성이라는 몸통을 흔든다](https://publish.obsidian.md/my-para-til/000_ZettelKasten/%EA%B0%90%EC%A0%95%EC%9D%B4%EB%9D%BC%EB%8A%94+%EA%BC%AC%EB%A6%AC%EA%B0%80+%EC%9D%B4%EC%84%B1%EC%9D%B4%EB%9D%BC%EB%8A%94+%EB%AA%B8%ED%86%B5%EC%9D%84+%ED%9D%94%EB%93%A0%EB%8B%A4)
- [회상 용이성이 주는 편향](https://publish.obsidian.md/my-para-til/000_ZettelKasten/%ED%9A%8C%EC%83%81%EC%9A%A9%EC%9D%B4%EC%84%B1%EC%9D%B4+%EC%A3%BC%EB%8A%94+%ED%8E%B8%ED%96%A5)
- [기준점 효과](https://publish.obsidian.md/my-para-til/000_ZettelKasten/%ED%98%91%EC%83%81%EC%9D%98+%EA%B8%B0%EC%A4%80%EC%A0%90)
- [인과관계는 없다](https://publish.obsidian.md/my-para-til/000_ZettelKasten/%EC%9D%B8%EA%B3%BC%EA%B4%80%EA%B3%84%EB%8A%94+%EC%97%86%EB%8B%A4)
- [네트워크 응용계층 문제](https://publish.obsidian.md/my-para-til/Project/%ED%98%BC%EC%9E%90+%EA%B3%B5%EB%B6%80%ED%95%98%EB%8A%94+%EB%84%A4%ED%8A%B8%EC%9B%8C%ED%81%AC/%EC%9D%91%EC%9A%A9+%EA%B3%84%EC%B8%B5/Active+Recall)
- [네트워크 추가 문제](https://publish.obsidian.md/my-para-til/Project/%ED%98%BC%EC%9E%90+%EA%B3%B5%EB%B6%80%ED%95%98%EB%8A%94+%EB%84%A4%ED%8A%B8%EC%9B%8C%ED%81%AC/%EC%B6%94%EA%B0%80+%ED%8C%8C%ED%8A%B8/Active+Recall)
- [스프링MVC 기본 기능 - Controller](https://publish.obsidian.md/my-para-til/Project/%EC%8A%A4%ED%94%84%EB%A7%81MVC-%EC%A0%84%ED%8E%B8/%EC%8A%A4%ED%94%84%EB%A7%81MVC+%EA%B8%B0%EB%B3%B8+%EA%B8%B0%EB%8A%A5+-+Controller)
- [후광 효과에 대항하기](https://publish.obsidian.md/my-para-til/000_ZettelKasten/%ED%9B%84%EA%B4%91+%ED%9A%A8%EA%B3%BC%EC%97%90+%EB%8C%80%ED%95%AD%ED%95%98%EA%B8%B0)
- [안정성과 고가용성](https://publish.obsidian.md/my-para-til/Project/%ED%98%BC%EC%9E%90+%EA%B3%B5%EB%B6%80%ED%95%98%EB%8A%94+%EB%84%A4%ED%8A%B8%EC%9B%8C%ED%81%AC/%EC%B6%94%EA%B0%80+%ED%8C%8C%ED%8A%B8/%EC%95%88%EC%A0%95%EC%84%B1%EA%B3%BC+%EA%B3%A0%EA%B0%80%EC%9A%A9%EC%84%B1)
- [MVC 프레임워크 만들기](https://publish.obsidian.md/my-para-til/Project/%EC%8A%A4%ED%94%84%EB%A7%81MVC-%EC%A0%84%ED%8E%B8/MVC+%ED%94%84%EB%A0%88%EC%9E%84%EC%9B%8C%ED%81%AC+%EB%A7%8C%EB%93%A4%EA%B8%B0)
- [HTTP 헤더와 기반 기술](https://publish.obsidian.md/my-para-til/Project/%ED%98%BC%EC%9E%90+%EA%B3%B5%EB%B6%80%ED%95%98%EB%8A%94+%EB%84%A4%ED%8A%B8%EC%9B%8C%ED%81%AC/%EC%9D%91%EC%9A%A9+%EA%B3%84%EC%B8%B5/HTTP+%ED%97%A4%EB%8D%94%EC%99%80+%EA%B8%B0%EB%B0%98+%EA%B8%B0%EC%88%A0)
- [캐시, 쿠키, 컨텐츠 협상관련 헤더](https://publish.obsidian.md/my-para-til/Project/%ED%98%BC%EC%9E%90+%EA%B3%B5%EB%B6%80%ED%95%98%EB%8A%94+%EB%84%A4%ED%8A%B8%EC%9B%8C%ED%81%AC/%EC%9D%91%EC%9A%A9+%EA%B3%84%EC%B8%B5/%EC%BA%90%EC%8B%9C%2C+%EC%BF%A0%ED%82%A4%2C+%EC%BB%A8%ED%85%90%EC%B8%A0+%ED%98%91%EC%83%81%EA%B4%80%EB%A0%A8+%ED%97%A4%EB%8D%94)
- [왜 백엔드는 MVC이고 프론트는 MVVM, Flux인가?](https://publish.obsidian.md/my-para-til/000_ZettelKasten/%EC%99%9C+%EB%B0%B1%EC%97%94%EB%93%9C%EB%8A%94+MVC%EC%9D%B4%EA%B3%A0+%ED%94%84%EB%A1%A0%ED%8A%B8%EB%8A%94+MVVM%2C+Flux%EC%9D%B8%EA%B0%80%3F)
- [서블릿](https://publish.obsidian.md/my-para-til/Project/%EC%8A%A4%ED%94%84%EB%A7%81MVC-%EC%A0%84%ED%8E%B8/%EC%84%9C%EB%B8%94%EB%A6%BF)
- [웹 애플리케이션의 이해](https://publish.obsidian.md/my-para-til/Project/%EC%8A%A4%ED%94%84%EB%A7%81MVC-%EC%A0%84%ED%8E%B8/%EC%9B%B9+%EC%95%A0%ED%94%8C%EB%A6%AC%EC%BC%80%EC%9D%B4%EC%85%98%EC%9D%98+%EC%9D%B4%ED%95%B4)
- [HTTP](https://publish.obsidian.md/my-para-til/Project/%ED%98%BC%EC%9E%90+%EA%B3%B5%EB%B6%80%ED%95%98%EB%8A%94+%EB%84%A4%ED%8A%B8%EC%9B%8C%ED%81%AC/%EC%9D%91%EC%9A%A9+%EA%B3%84%EC%B8%B5/HTTP)
- [자원](https://publish.obsidian.md/my-para-til/Project/%ED%98%BC%EC%9E%90+%EA%B3%B5%EB%B6%80%ED%95%98%EB%8A%94+%EB%84%A4%ED%8A%B8%EC%9B%8C%ED%81%AC/%EC%9D%91%EC%9A%A9+%EA%B3%84%EC%B8%B5/%EC%9E%90%EC%9B%90)
- [DNS](https://publish.obsidian.md/my-para-til/Project/%ED%98%BC%EC%9E%90+%EA%B3%B5%EB%B6%80%ED%95%98%EB%8A%94+%EB%84%A4%ED%8A%B8%EC%9B%8C%ED%81%AC/%EC%9D%91%EC%9A%A9+%EA%B3%84%EC%B8%B5/DNS)
- [DNS 레코드 타입](https://publish.obsidian.md/my-para-til/Project/%ED%98%BC%EC%9E%90+%EA%B3%B5%EB%B6%80%ED%95%98%EB%8A%94+%EB%84%A4%ED%8A%B8%EC%9B%8C%ED%81%AC/%EC%9D%91%EC%9A%A9+%EA%B3%84%EC%B8%B5/DNS+%EB%A0%88%EC%BD%94%EB%93%9C+%ED%83%80%EC%9E%85)
- [스프링 개념 파트](https://publish.obsidian.md/my-para-til/Project/%EC%8A%A4%ED%94%84%EB%A7%81_%ED%95%B5%EC%8B%AC_%EC%9B%90%EB%A6%AC-%EA%B8%B0%EB%B3%B8%ED%8E%B8/%EC%8A%A4%ED%94%84%EB%A7%81+%EA%B0%9C%EB%85%90+%ED%8C%8C%ED%8A%B8)
- [스프링 실 사용 파트](https://publish.obsidian.md/my-para-til/Project/%EC%8A%A4%ED%94%84%EB%A7%81_%ED%95%B5%EC%8B%AC_%EC%9B%90%EB%A6%AC-%EA%B8%B0%EB%B3%B8%ED%8E%B8/%EC%8A%A4%ED%94%84%EB%A7%81+%EC%8B%A4+%EC%82%AC%EC%9A%A9+%ED%8C%8C%ED%8A%B8)
- [사용자 역할 모델링](https://publish.obsidian.md/my-para-til/000_ZettelKasten/%EC%82%AC%EC%9A%A9%EC%9E%90+%EC%97%AD%ED%95%A0+%EB%AA%A8%EB%8D%B8%EB%A7%81)
- [시스템 1과 2](https://publish.obsidian.md/my-para-til/000_ZettelKasten/%EC%8B%9C%EC%8A%A4%ED%85%9C+1%EA%B3%BC+2)
- [요구사항 그물질하기](https://publish.obsidian.md/my-para-til/000_ZettelKasten/%EC%9A%94%EA%B5%AC%EC%82%AC%ED%95%AD+%EA%B7%B8%EB%AC%BC%EC%A7%88%ED%95%98%EA%B8%B0)
- [포트](https://publish.obsidian.md/my-para-til/Project/%ED%98%BC%EC%9E%90+%EA%B3%B5%EB%B6%80%ED%95%98%EB%8A%94+%EB%84%A4%ED%8A%B8%EC%9B%8C%ED%81%AC/%EC%A0%84%EC%86%A1+%EA%B3%84%EC%B8%B5/%ED%8F%AC%ED%8A%B8)
- [TCP와 UDP](https://publish.obsidian.md/my-para-til/Project/%ED%98%BC%EC%9E%90+%EA%B3%B5%EB%B6%80%ED%95%98%EB%8A%94+%EB%84%A4%ED%8A%B8%EC%9B%8C%ED%81%AC/%EC%A0%84%EC%86%A1+%EA%B3%84%EC%B8%B5/TCP%EC%99%80+UDP)
- [TCP의 오류, 흐름, 혼잡제어](https://publish.obsidian.md/my-para-til/Project/%ED%98%BC%EC%9E%90+%EA%B3%B5%EB%B6%80%ED%95%98%EB%8A%94+%EB%84%A4%ED%8A%B8%EC%9B%8C%ED%81%AC/%EC%A0%84%EC%86%A1+%EA%B3%84%EC%B8%B5/TCP%EC%9D%98+%EC%98%A4%EB%A5%98%2C+%ED%9D%90%EB%A6%84%2C+%ED%98%BC%EC%9E%A1%EC%A0%9C%EC%96%B4)
- [깨진 유리창보다 자세하게](https://publish.obsidian.md/my-para-til/000_ZettelKasten/%EA%B9%A8%EC%A7%84+%EC%9C%A0%EB%A6%AC%EC%B0%BD%EB%B3%B4%EB%8B%A4+%EC%9E%90%EC%84%B8%ED%95%98%EA%B2%8C)
- [7과 12와 150](https://publish.obsidian.md/my-para-til/000_ZettelKasten/7%EA%B3%BC+12%EC%99%80+150)
- [집단 1과 2](https://publish.obsidian.md/my-para-til/000_ZettelKasten/%EC%A7%91%EB%8B%A8+1%EA%B3%BC+2)

### 2024.05

- [영향력은 당근과 채찍으로 퍼지지 않는다](https://publish.obsidian.md/my-para-til/000_ZettelKasten/%EC%98%81%ED%96%A5%EB%A0%A5%EC%9D%80+%EB%8B%B9%EA%B7%BC%EA%B3%BC+%EC%B1%84%EC%B0%8D%EC%9C%BC%EB%A1%9C+%ED%8D%BC%EC%A7%80%EC%A7%80+%EC%95%8A%EB%8A%94%EB%8B%A4)
- [케이크 자르기](https://publish.obsidian.md/my-para-til/000_ZettelKasten/%EC%BC%80%EC%9D%B4%ED%81%AC+%EC%9E%90%EB%A5%B4%EA%B8%B0)
- [IP주소 더 알아보기](https://publish.obsidian.md/my-para-til/Project/%ED%98%BC%EC%9E%90+%EA%B3%B5%EB%B6%80%ED%95%98%EB%8A%94+%EB%84%A4%ED%8A%B8%EC%9B%8C%ED%81%AC/%EB%84%A4%ED%8A%B8%EC%9B%8C%ED%81%AC+%EA%B3%84%EC%B8%B5/IP+%EC%A3%BC%EC%86%8C+%EB%8D%94+%EC%95%8C%EC%95%84%EB%B3%B4%EA%B8%B0)
- [LAN을 넘어선 네트워크 통신](https://publish.obsidian.md/my-para-til/Project/%ED%98%BC%EC%9E%90+%EA%B3%B5%EB%B6%80%ED%95%98%EB%8A%94+%EB%84%A4%ED%8A%B8%EC%9B%8C%ED%81%AC/%EB%84%A4%ED%8A%B8%EC%9B%8C%ED%81%AC+%EA%B3%84%EC%B8%B5/LAN%EC%9D%84+%EB%84%98%EC%96%B4%EC%84%A0+%EB%84%A4%ED%8A%B8%EC%9B%8C%ED%81%AC+%ED%86%B5%EC%8B%A0)
- [라우팅](https://publish.obsidian.md/my-para-til/Project/%ED%98%BC%EC%9E%90+%EA%B3%B5%EB%B6%80%ED%95%98%EB%8A%94+%EB%84%A4%ED%8A%B8%EC%9B%8C%ED%81%AC/%EB%84%A4%ED%8A%B8%EC%9B%8C%ED%81%AC+%EA%B3%84%EC%B8%B5/%EB%9D%BC%EC%9A%B0%ED%8C%85)
- [이더넷 규격](https://publish.obsidian.md/my-para-til/Project/%ED%98%BC%EC%9E%90+%EA%B3%B5%EB%B6%80%ED%95%98%EB%8A%94+%EB%84%A4%ED%8A%B8%EC%9B%8C%ED%81%AC/%EB%AC%BC%EB%A6%AC+%EA%B3%84%EC%B8%B5%EA%B3%BC+%EB%8D%B0%EC%9D%B4%ED%84%B0+%EB%A7%81%ED%81%AC+%EA%B3%84%EC%B8%B5/%EC%9D%B4%EB%8D%94%EB%84%B7+%EA%B7%9C%EA%B2%A9)
- [허브와 스위치](https://publish.obsidian.md/my-para-til/Project/%ED%98%BC%EC%9E%90+%EA%B3%B5%EB%B6%80%ED%95%98%EB%8A%94+%EB%84%A4%ED%8A%B8%EC%9B%8C%ED%81%AC/%EB%AC%BC%EB%A6%AC+%EA%B3%84%EC%B8%B5%EA%B3%BC+%EB%8D%B0%EC%9D%B4%ED%84%B0+%EB%A7%81%ED%81%AC+%EA%B3%84%EC%B8%B5/%ED%97%88%EB%B8%8C%EC%99%80+%EC%8A%A4%EC%9C%84%EC%B9%98)
- [NIC와 케이블](https://publish.obsidian.md/my-para-til/Project/%ED%98%BC%EC%9E%90+%EA%B3%B5%EB%B6%80%ED%95%98%EB%8A%94+%EB%84%A4%ED%8A%B8%EC%9B%8C%ED%81%AC/%EB%AC%BC%EB%A6%AC+%EA%B3%84%EC%B8%B5%EA%B3%BC+%EB%8D%B0%EC%9D%B4%ED%84%B0+%EB%A7%81%ED%81%AC+%EA%B3%84%EC%B8%B5/NIC%EC%99%80+%EC%BC%80%EC%9D%B4%EB%B8%94)
- [메타인지와 파레토 법칙](https://publish.obsidian.md/my-para-til/000_ZettelKasten/%EB%A9%94%ED%83%80%EC%9D%B8%EC%A7%80%EC%99%80+%ED%8C%8C%EB%A0%88%ED%86%A0+%EB%B2%95%EC%B9%99)
- [물 흐르듯이 이어지는 SDLC](https://publish.obsidian.md/my-para-til/000_ZettelKasten/%EB%AC%BC+%ED%9D%90%EB%A5%B4%EB%93%AF%EC%9D%B4+%EC%9D%B4%EC%96%B4%EC%A7%80%EB%8A%94+SDLC)
- [컴퓨터 네트워크 시작하기](https://publish.obsidian.md/my-para-til/Project/%ED%98%BC%EC%9E%90+%EA%B3%B5%EB%B6%80%ED%95%98%EB%8A%94+%EB%84%A4%ED%8A%B8%EC%9B%8C%ED%81%AC/%EC%BB%B4%ED%93%A8%ED%84%B0+%EB%84%A4%ED%8A%B8%EC%9B%8C%ED%81%AC+%EC%8B%9C%EC%9E%91%ED%95%98%EA%B8%B0)
- [검색 과정을 탐색 과정으로 바꾸기](https://publish.obsidian.md/my-para-til/000_ZettelKasten/%EA%B2%80%EC%83%89%EA%B3%BC%EC%A0%95%EC%9D%84+%ED%83%90%EC%83%89%EA%B3%BC%EC%A0%95%EC%9C%BC%EB%A1%9C+%EB%B0%94%EA%BE%B8%EA%B8%B0)
