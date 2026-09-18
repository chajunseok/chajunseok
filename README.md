<h1 align="center">차준석</h1>
<p align="center"><b>Full-stack Developer · AI-assisted Development</b></p>

<p align="center">
  금융권 연계 솔루션의 관리 콘솔을 개발하고 있습니다.<br/>
  React부터 Spring Boot, DB까지 직접 다루며,<br/>
  새로운 AI 도구와 개발 방식을 실제 업무에 적용하고 검증하는 데 관심이 많습니다.
</p>

<p align="center">
  <a href="mailto:wnstjr401@gmail.com"><img src="https://img.shields.io/badge/Gmail-wnstjr401%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="email"/></a>
  <a href="https://chajunseok.github.io/"><img src="https://img.shields.io/badge/Portfolio-chajunseok.github.io-1E2E44?style=flat-square&logo=githubpages&logoColor=white" alt="portfolio"/></a>
</p>

---

## About Me

금융권 연계 솔루션 회사에서 **React / TypeScript 기반 Frontend와 Spring Boot 기반 Backend를 함께 개발**하고 있습니다.

기존 시스템을 단순히 유지보수하기보다 구조를 개선하고, 반복되는 개발 작업을 자동화하고, 새로운 도구를 실제 개발 프로세스에 적용하는 것에 관심이 많습니다.

특히 빠르게 변화하는 AI 개발 트렌드를 따라가기 위해 **Claude Code, MCP, Plugins, Coding Agent와 같은 도구를 직접 도입하고 테스트**하고 있습니다.

단순히 사용해 보는 것에 그치지 않고,

* 실제 프로젝트에 적용해 생산성과 한계를 확인하고
* 여러 플러그인과 MCP를 비교하고
* 팀 프로젝트에 맞는 규칙과 워크플로우를 만들고
* 검증한 내용과 사용 방법을 팀원들에게 공유합니다.

AI가 개발자를 대체하는 것보다, **개발자가 AI를 어떻게 개발 프로세스 안에 잘 배치할 것인가**에 관심이 있습니다.

---

## What I'm Working On

### 관리 콘솔 차세대 전환

JSP 기반의 기존 관리 콘솔을 **React + TypeScript 기반으로 전환**하고 있습니다.

약 190개의 화면과 여러 화면을 동시에 사용하는 MDI 구조를 다루기 때문에 일반적인 Router 중심 SPA와는 다른 구조가 필요했습니다.

프로젝트의 폴더 구조와 의존성 규칙을 정의하고 lint 규칙으로 강제하여, 개발 인원이 늘어나더라도 코드 구조가 쉽게 무너지지 않도록 설계하고 있습니다.

### Backend API

**Spring Boot, JPA, QueryDSL, PostgreSQL**을 사용해 REST API를 개발합니다.

거래 로그와 같은 대용량 데이터 조회, 연계 엔진과의 HTTP 통신, 메뉴 단위 권한 검사 등 관리 시스템의 Backend 기능도 함께 담당하고 있습니다.

### On-Premise LLM

인터넷 연결이 제한된 금융권 고객사 환경에서도 사용할 수 있는 **경량 LLM 기반 운영 지원 기능**을 설계하고 있습니다.

현재 목표로 하는 기능은 다음과 같습니다.

* 거래 실패 시 로그를 기반으로 원인 후보 정리
* 자연어로 입력한 조회 조건을 검색 Form으로 변환
* 현재 화면과 기능에 대한 사용 방법 안내

모델의 크기보다 **제한된 인프라 안에서 실제 업무에 사용할 수 있는 기능을 만드는 것**에 초점을 두고 있습니다.

---

## AI & Developer Experience

새로운 AI 도구가 나오면 단순히 기능을 확인하는 데서 끝내지 않고 실제 개발 환경에 적용해 보고 있습니다.

현재는 **Claude Code를 중심으로 MCP, Plugins, Skills, Subagents와 같은 기능을 실제 개발 프로세스에 연결**해서 사용하고 있습니다.

요구사항 분석 → 구현 계획 → 코드 작성 → 리뷰 → 검증까지의 흐름을 정리하고, 반복되는 작업은 재사용 가능한 Skill이나 도구로 만들어 사용합니다.

또한 새로운 MCP나 Plugin을 발견하면

**도입 → 테스트 → 실제 프로젝트 적용 → 장단점 리뷰 → 팀 공유**

과정을 거쳐 팀에서 사용할 가치가 있는지를 판단합니다.

AI 도구 자체보다 **AI를 활용해 팀의 개발 방식과 생산성을 어떻게 개선할 수 있는지**에 관심이 있습니다.

---

## Projects

### [claude-config-map](https://github.com/chajunseok/claude-config-map)

Claude Code 설정은 Global, Project, Plugin 등 여러 위치에 분산되어 있습니다.

프로젝트를 사용하다 보면

> "현재 이 프로젝트에 실제로 적용되는 설정은 무엇이지?"

를 확인하는 일이 생각보다 번거롭습니다.

`claude-config-map`은 이러한 설정을 한 화면에서 확인하고 수정할 수 있도록 만든 로컬 관리 도구입니다.

* Global / Project / Plugin 설정 탐색
* 설정 내용 확인 및 수정
* 설정 활성화 / 비활성화
* Browser 기반 UI
* Python Standard Library 기반 실행

Claude Code를 실제 프로젝트에서 사용하면서 느낀 불편함을 해결하기 위해 만들었습니다.

> 회사 업무 코드는 사내 GitLab에서 관리하고 있어 GitHub에는 공개하지 않습니다.

---

## Tech Stack

### Frontend

<p>
  <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB"/>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white"/>
  <img src="https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white"/>
  <img src="https://img.shields.io/badge/TanStack_Query-FF4154?style=flat-square&logo=reactquery&logoColor=white"/>
  <img src="https://img.shields.io/badge/Zustand-443E38?style=flat-square&logo=react&logoColor=white"/>
  <img src="https://img.shields.io/badge/React_Hook_Form-EC5990?style=flat-square&logo=reacthookform&logoColor=white"/>
  <img src="https://img.shields.io/badge/Zod-3E67B1?style=flat-square&logo=zod&logoColor=white"/>
  <img src="https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white"/>
  <img src="https://img.shields.io/badge/Radix_UI-161618?style=flat-square&logo=radixui&logoColor=white"/>
  <img src="https://img.shields.io/badge/Vitest-6E9F18?style=flat-square&logo=vitest&logoColor=white"/>
  <img src="https://img.shields.io/badge/Storybook-FF4785?style=flat-square&logo=storybook&logoColor=white"/>
  <img src="https://img.shields.io/badge/Vue.js-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white"/>
</p>

### Backend / Database

<p>
  <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white"/>
  <img src="https://img.shields.io/badge/JPA_/_QueryDSL-59666C?style=flat-square&logo=hibernate&logoColor=white"/>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white"/>
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white"/>
  <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white"/>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
</p>

### AI / Developer Tools

<p>
  <img src="https://img.shields.io/badge/Claude_Code-D97757?style=flat-square&logo=anthropic&logoColor=white"/>
  <img src="https://img.shields.io/badge/MCP-000000?style=flat-square&logo=modelcontextprotocol&logoColor=white"/>
  <img src="https://img.shields.io/badge/llama.cpp-000000?style=flat-square&logo=meta&logoColor=white"/>
  <img src="https://img.shields.io/badge/Obsidian-7C3AED?style=flat-square&logo=obsidian&logoColor=white"/>
  <img src="https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=figma&logoColor=white"/>
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white"/>
</p>

---

## Contact

**Email**
[wnstjr401@gmail.com](mailto:wnstjr401@gmail.com)

**Portfolio**
https://chajunseok.github.io/
