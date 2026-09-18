<h1 align="center">차준석</h1>
<p align="center"><b>Full-stack Developer</b></p>

<p align="center">
  금융권 연계 솔루션 회사에서 관리 콘솔을 만들고 있습니다.<br/>
  React로 화면을 짜고, Spring Boot API와 DB까지 개발하고 있습니다.
</p>

<p align="center">
  <a href="mailto:wnstjr401@gmail.com"><img src="https://img.shields.io/badge/Gmail-wnstjr401%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="email"/></a>
  <a href="https://chajunseok.github.io/"><img src="https://img.shields.io/badge/Portfolio-chajunseok.github.io-1E2E44?style=flat-square&logo=githubpages&logoColor=white" alt="portfolio"/></a>
</p>

---

## 지금 하고 있는 일

**관리 콘솔 차세대 전환**
JSP로 만들어진 기존 관리 콘솔을 React와 TypeScript로 새로 만들고 있습니다. 화면이 190개쯤 되고, 탭 여러 개를 띄워놓고 쓰는 MDI 방식이라 일반적인 라우터 기반 구조와는 다르게 설계했습니다. 폴더 구조와 의존 규칙을 정하고 lint로 강제해서, 사람이 늘어나도 구조가 무너지지 않게 하는 데 신경을 쓰고 있습니다.

**백엔드 API**
Spring Boot와 JPA, QueryDSL, PostgreSQL로 REST API를 만듭니다. 거래 로그처럼 데이터가 많은 조회, 연계 엔진과의 HTTP 통신, 메뉴 단위 권한 검사 같은 부분을 담당했습니다.

**운영 보조 LLM**
인터넷이 안 되는 고객사 환경에서도 돌아가도록, 작은 모델을 서버에 같이 띄워 운영자를 도와주는 기능을 설계 중입니다. 거래가 실패했을 때 원인 후보를 정리해 주거나, 조회 조건을 말로 입력하면 검색 폼을 채워 주거나, 화면 사용법을 알려주는 정도를 목표로 하고 있습니다.

**개발 환경 정비**
Claude Code를 팀 작업에 쓰기 위한 규칙과 도구를 만들고 있습니다. 요구사항 정리부터 계획, 구현, 검증까지 흐름을 정해두고, 반복되는 작업은 스킬로 묶어서 씁니다.

## 만든 것

[**claude-config-map**](https://github.com/chajunseok/claude-config-map)
Claude Code 설정 파일이 전역, 프로젝트, 플러그인 여기저기에 흩어져 있어서 "지금 이 프로젝트에 적용되는 규칙이 뭐지"를 확인하기 번거로웠습니다. 그걸 브라우저 한 화면에 모아서 보고, 바로 고치고, 켜고 끌 수 있게 만든 로컬 도구입니다. Python 표준 라이브러리만 사용합니다.

회사 업무 코드는 사내 GitLab에서 관리하고 있어 GitHub에는 올리지 않습니다.

## 기술

**Frontend**
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

**Backend / DB**
<p>
  <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white"/>
  <img src="https://img.shields.io/badge/JPA_/_QueryDSL-59666C?style=flat-square&logo=hibernate&logoColor=white"/>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white"/>
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white"/>
  <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white"/>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
</p>

**AI / Tools**
<p>
  <img src="https://img.shields.io/badge/Claude_Code-D97757?style=flat-square&logo=anthropic&logoColor=white"/>
  <img src="https://img.shields.io/badge/MCP-000000?style=flat-square&logo=modelcontextprotocol&logoColor=white"/>
  <img src="https://img.shields.io/badge/llama.cpp-000000?style=flat-square&logo=meta&logoColor=white"/>
  <img src="https://img.shields.io/badge/Obsidian-7C3AED?style=flat-square&logo=obsidian&logoColor=white"/>
  <img src="https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=figma&logoColor=white"/>
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white"/>
</p>

## 연락처

wnstjr401@gmail.com
https://chajunseok.github.io/
