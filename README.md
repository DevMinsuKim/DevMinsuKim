<div align="center">

![header](https://capsule-render.vercel.app/api?type=waving&height=200&text=Welcome&fontAlign=50&fontAlignY=25&color=gradient&desc=Minsu%27s%20GitHub%20profile&descAlign=60&descAlignY=45)

### 웹 서비스의 구조와 렌더링 성능을 개선해 온 프론트엔드 개발자입니다

React와 Next.js 기반 웹 서비스에서 공통 구조를 설계하고, HLS 스트리밍 플레이어와 WebRTC처럼 고빈도 상태 변화가 발생하는 UI의 렌더링 성능과 브라우저 호환 문제를 해결해 왔습니다.
<br>
Turborepo 기반 모노레포, 공통 컴포넌트, CI/CD와 배포 환경부터 React Native 앱 아키텍처까지 서비스의 초기 구조와 개발 기반을 구축한 경험이 있습니다.
<br>
최근에는 Cursor Rules와 MCP를 활용한 팀 개발 프로세스 개선과 LLM API를 활용한 프로덕트 개발까지 경험을 넓혀가고 있습니다.

</div>

<br>

## Skills

#### Frontend

![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![React Native](https://img.shields.io/badge/React%20Native-61DAFB?style=flat-square&logo=react&logoColor=black)

#### Platform

![Turborepo](https://img.shields.io/badge/Turborepo-EF4444?style=flat-square&logo=turborepo&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Sentry](https://img.shields.io/badge/Sentry-362D59?style=flat-square&logo=sentry&logoColor=white)

#### Media & Realtime

![WebRTC](https://img.shields.io/badge/WebRTC-333333?style=flat-square&logo=webrtc&logoColor=white)
![HLS](https://img.shields.io/badge/HLS-FF0000?style=flat-square&logo=videodotjs&logoColor=white)
![FFmpeg](https://img.shields.io/badge/FFmpeg-007808?style=flat-square&logo=ffmpeg&logoColor=white)

#### State & Data

![TanStack Query](https://img.shields.io/badge/TanStack%20Query-FF4154?style=flat-square&logo=reactquery&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)

<br>

## Side Project

**[clover-pick](https://github.com/DevMinsuKim/clover-pick)** <sub>개인 프로젝트 / 2024년부터 운영 중</sub>

자연어로 원하는 조건을 입력해 로또·연금복권 번호를 생성하는 웹 서비스

<details>
<summary>더보기</summary>
<br>

AI API를 실제 서비스에 적용해보기 위해 시작했으며, 기획부터 프론트엔드, 백엔드, 배포·운영까지 직접 진행하고 있습니다.

최근에는 AI가 번호를 직접 생성하던 방식에서, 사용자의 자연어를 조건으로 해석하고 확인된 조건에 맞춰 번호를 생성하는 방식으로 개편했습니다.

- **AI 해석과 번호 생성 분리**: AI SDK의 구조화 출력과 Zod로 조건을 검증하고, 실제 번호는 서버의 난수 생성 로직으로 선택합니다. 복권별 규칙과 조건 충돌을 검증하며, 랜덤 생성과 빠른 조건은 AI 호출 없이 처리합니다.
- **재시도와 저장 안정성 개선**: 요청 식별자와 트랜잭션으로 중복 저장을 방지하고, 같은 요청을 재시도하면 기존 결과를 반환합니다. AI 호출에는 시간 제한과 요청량 제한을 적용했습니다.
- **사용자 흐름 중심의 UI 개편**: 반응형 화면과 다크 모드의 디자인을 통일하고, 목록 페이지 전환 중 기존 화면을 유지하도록 개선했습니다. Three.js 기반 3D 추첨기는 사용자가 선택할 때만 불러오고, 화면 밖에서는 실행을 멈춥니다.
- **검증 환경 구성**: 회차 계산·당첨 판별·조건별 생성 로직의 단위 테스트와 PostgreSQL 통합 테스트를 구성하고, GitHub Actions에서 린트·타입 검사·테스트·빌드를 실행하도록 설정했습니다.

AI는 당첨 번호를 예측하지 않으며, 사용자가 원하는 조건을 편리하게 적용하는 데 활용합니다.

<br>

`Next.js` `TypeScript` `TanStack Query` `PostgreSQL` `Prisma` `AI SDK` `Zod` `Three.js` `Vitest` `Sentry`

</details>

<br>

## Contact

[![Email](https://img.shields.io/badge/cvnefr7704@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:cvnefr7704@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/kmscv)
