**"비즈니스 로직과 UI를 분리하며, 유지보수하기 좋은 아키텍처를 고민하는 프론트엔드 개발자입니다."**

단순히 기능이 동작하는 것을 넘어 사용자 경험(UX)과 클린 코드에 관심이 많습니다. Feature-Sliced Design(FSD)과 Compound Component 패턴을 활용하여 재사용성 높은 UI를 설계하는 것을 즐기며, 최근에는 브라우저 네이티브 API를 활용한 접근성 개선과 AI 연동을 통해 기존 프로젝트를 고도화하는 과정을 밟고 있습니다.

<br/>

### 🛠 Tech Stack

**Frontend**
<br/>
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)

**State Management & Data Fetching**
<br/>
![Tanstack Query](https://img.shields.io/badge/React_Query-FF4154?style=for-the-badge&logo=reactQuery&logoColor=white)

**Architecture & Patterns**
<br/>
`Feature-Sliced Design (FSD)` `Clean Architecture` `Compound Components`

<br/>

### 🚀 Projects

#### 1. Coworkers-rf (협업 태스크 관리 플랫폼 및 AI 모듈 고도화)
> **기간:** 2026.03 ~ 2026.05 | **[🔗 Repo](https://github.com/jaywai-lee/team2_coworkers-rf-)** | **[🚀 배포 링크](https://coworkers-rf.vercel.app/)**
* **소개:** 팀원들과 일정을 공유할 수 있는 칸반보드 및 커뮤니티 기반 협업 서비스. 배포 후 AI 자연어 입력 모듈을 도입하고 프론트엔드 아키텍처를 리팩토링하여 사용성과 유지보수성을 대폭 개선했습니다.
* **주요 역할 & 트러블슈팅:**
  * **[Architecture]** BFF(Backend for Frontend) 프록시 서버를 구축하여 인증(Auth) 로직 캡슐화, Compound Component 패턴을 적용해 재사용성을 고려한 공통 UI 라이브러리 설계
  * **[UX/Accessibility]** 외부 API 의존 없이 브라우저 내장 `Web Speech API`를 활용한 STT(음성 인식) 커스텀 훅을 직접 구현하여 키보드 없는 모바일 환경에서의 접근성 극대화 및 UX 향상
  * **[AI Prompt Engineering]** AI의 일정 생성 할루시네이션 현상을 제어하기 위해 캘린더 매핑 참조표를 개선하고, 엄격한 백엔드 DTO Validation 에러를 방어하는 동적 Payload 생성 로직 구현
  * **[Refactoring]** 복잡해진 컴포넌트를 비즈니스 로직(Custom Hook)과 순수 UI 뷰 컴포넌트로 완벽하게 분리하여 관심사 분리(SoC) 달성

<br/>

### 📫 Contact
- **Email:** [jylee2670@gmail.com](mailto:jylee2670@gmail.com)
- **Resume:** [노션 이력서](https://www.notion.so/Frontend-Developer-Resume-c16b13631a12820e8f4e0154c55af300?source=copy_link)
