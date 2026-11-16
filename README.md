<div align="center">

# 허정 · HEO JEONG

### Backend Developer

백엔드를 개발하고, 설계의 이유와 문제 해결 과정을 기록합니다.  
인증·권한, 조직별 데이터 격리, 데이터 무결성에 관심이 있습니다.

[![GitHub](https://img.shields.io/badge/GitHub-niftus13-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/niftus13)
[![Project](https://img.shields.io/badge/Explore-Multitenant_Workspace-0D9488?style=flat-square)](https://github.com/niftus13/portfolio)
[![Architecture](https://img.shields.io/badge/Read-Architecture_%26_Decisions-0D9488?style=flat-square)](https://github.com/niftus13/portfolio/blob/main/docs/decisions/001-stack-and-quality-tooling.md)

</div>

---

## About

- **접근 제어** — 사용자의 역할과 조직 범위를 함께 고려하는 백엔드를 만듭니다.
- **데이터 일관성** — 트랜잭션과 동시 수정 충돌 처리를 통해 변경 이력을 보호합니다.
- **검증과 기록** — 명세와 구현을 연결하고, 정상 흐름뿐 아니라 실패 경로도 테스트합니다.

## Tech Stack

현재 멀티테넌트 프로젝트에서 집중적으로 사용하는 기술입니다.

| 영역 | 기술 |
| :--- | :--- |
| **Backend** | ![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white) ![Express](https://img.shields.io/badge/Express-222222?style=flat-square&logo=express&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) |
| **Database** | ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white) · SQL · Transactions |
| **Frontend** | ![Nuxt](https://img.shields.io/badge/Nuxt-00DC82?style=flat-square&logo=nuxt&logoColor=111827) ![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white) |
| **Environment & CI** | ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white) · pnpm |
| **Testing** | ![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=flat-square&logo=vitest&logoColor=white) · Playwright · ESLint · Prettier |

### Additional Experience

이전 프로젝트와 학습 저장소에서 사용한 기술입니다.

| 영역 | 기술 |
| :--- | :--- |
| **Java Backend** | ![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logoColor=white) ![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white) · Spring MVC · Spring Security |
| **Persistence** | Spring Data JPA · QueryDSL · MyBatis · TypeORM |
| **PHP Backend** | ![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white) ![CodeIgniter](https://img.shields.io/badge/CodeIgniter-EF4223?style=flat-square&logo=codeigniter&logoColor=white) |
| **Python Backend** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) · WebSocket |
| **React** | ![React](https://img.shields.io/badge/React-149ECA?style=flat-square&logo=react&logoColor=white) · React Router · Redux Toolkit |
| **UI & State** | ![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white) · Pinia · Astro · JavaScript · HTML · CSS |
| **Cache & Queue** | ![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white) · ioredis · BullMQ |
| **Build & Server** | ![NGINX](https://img.shields.io/badge/NGINX-009639?style=flat-square&logo=nginx&logoColor=white) · Gradle · Vite · npm |

### Applied Skills

| 주제 | 프로젝트에서 다룬 내용 |
| :--- | :--- |
| **인증·인가** | 세션 인증, Spring Security, JWT, OAuth 2.0 연동, 역할별 접근 제어 |
| **데이터 접근** | SQL·MyBatis 매핑, JPA·QueryDSL 조회, TypeORM 기반 엔티티 구성 |
| **비동기 처리** | Redis 연결 관리, BullMQ 큐·워커 구성, WebSocket 메시지 전달 |
| **화면 구성** | React·Vue 컴포넌트, Redux Toolkit·Pinia 상태 관리, Tailwind CSS 스타일링 |
| **실행 환경** | Docker Compose 서비스 구성, Nginx 설정, 정적 사이트 빌드 |

<details>
<summary><strong>공개 코드로 살펴보는 기술 경험</strong></summary>

| 저장소 | 확인할 수 있는 기술 |
| :--- | :--- |
| [TodoSecurity](https://github.com/niftus13/TodoSecurity) | Spring Boot · Spring Security · JPA · JWT · OAuth 2.0 |
| [dd1](https://github.com/niftus13/dd1) | Spring Data JPA · QueryDSL 기반 검색 |
| [r02](https://github.com/niftus13/r02) | React · Redux Toolkit · React Router |
| [classProject](https://github.com/niftus13/classProject) | Java · Spring MVC · MyBatis 학습 |
| [nuxtStudy](https://github.com/niftus13/nuxtStudy) | Nuxt · Vue 학습 |

</details>

## Featured Project

### 📂 조직별 문서 공유 워크스페이스

**여러 조직이 하나의 서비스를 사용하면서, 각자의 문서와 권한을 독립적으로 관리하는 멀티테넌트 MVP입니다.**

`Node.js` `Express` `TypeScript` `MySQL` `Nuxt` `Docker Compose`

| 설계 주제 | 구현 내용 |
| :--- | :--- |
| **조직별 데이터 격리** | 활성 멤버십 확인, 테넌트 범위 조회, 조직 ID를 포함한 복합 외래 키 |
| **인증과 권한** | DB 기반 세션, CSRF 방어, owner·admin·editor·viewer 역할별 접근 제어 |
| **문서 이력과 동시성** | 문서·이력의 트랜잭션 처리, revision 기반 충돌 검사 |
| **실패 경로 검증** | 실제 MySQL을 이용한 격리·충돌·롤백 검증과 브라우저 테스트 |

**진행 상태** · 핵심 문서 기능과 로컬 데모 구현. 공용 배포를 위한 운영 조건 개선 중.

[**저장소 살펴보기 →**](https://github.com/niftus13/portfolio) ·
[**MVP 명세**](https://github.com/niftus13/portfolio/blob/main/specs/multitenant-mvp.md) ·
[**구현 체크리스트**](https://github.com/niftus13/portfolio/blob/main/specs/multitenant-mvp-checklist.md)

## Engineering Notes

코드와 함께 읽을 수 있는 설계 기록입니다.

| 관심 주제 | 문서 |
| :--- | :--- |
| 기술 선택과 품질 검증 도구 | [기술 스택 결정](https://github.com/niftus13/portfolio/blob/main/docs/decisions/001-stack-and-quality-tooling.md) |
| 세션 인증과 보안 정책 | [인증 API 계약](https://github.com/niftus13/portfolio/blob/main/specs/auth-api.md) |
| 문서 버전과 수정 충돌 처리 | [조직·문서 API 계약](https://github.com/niftus13/portfolio/blob/main/specs/documents-api.md) |
| AI 개발 도구와 검증 흐름 | [하네스 재사용 안내](https://github.com/niftus13/portfolio/blob/main/docs/harness-reuse.md) |

---

<div align="center">
<sub>기능을 구현하고, 선택의 이유를 설명하고, 실패 경로까지 확인합니다.</sub>
</div>
