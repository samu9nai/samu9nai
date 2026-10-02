<div align="center">

# Mingyu Joung

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://readme-typing-svg.demolab.com/?font=JetBrains+Mono&size=20&duration=3000&pause=1000&color=75CAE8&center=true&vCenter=true&width=520&lines=Backend+Developer+%C2%B7+Java+%26+Spring" />
  <img src="https://readme-typing-svg.demolab.com/?font=JetBrains+Mono&size=20&duration=3000&pause=1000&color=1F6F94&center=true&vCenter=true&width=520&lines=Backend+Developer+%C2%B7+Java+%26+Spring" alt="Backend Developer · Java & Spring" />
</picture>

I like knowing what the framework does for me, and I check that a test fails before I call a bug fixed.

</div>

## About Me

- Build backend services with **Java, Spring, and relational databases**, and ship the Vue/React frontends that sit on them
- Wired **Spring MVC without Spring Boot** to learn what auto-configuration hides
- Care about **trust boundaries**: auth flows, concurrency, and what a system does and does not guarantee
- Work with **AI coding agents daily**, giving them repository rules first and reporting verified and unverified results separately

## Background

| | |
|---|---|
| **Program** | KB IT's Your Life 7th · 2026 |
| **Education** | Hongik University · Computer Engineering |

## Selected Projects

### [NA-WA](https://github.com/T-ravelers/NA-WA) · Travel Collaboration Service for Visitors to Korea

**Full-stack · KB IT's Your Life Final Project**

A mobile-first service for foreign visitors to Korea: meetups, wallet and QR payments, expense splitting, and trip reports. Served in English, Japanese, Traditional Chinese, and Vietnamese.

- Wired Spring MVC 5.3 by hand on a WAR without Spring Boot: DispatcherServlet, Security filter chain, transactions, HikariCP, MyBatis, Flyway
- Implemented Google and LINE OAuth 2.0 / OIDC without delegating to a library: ID token verification, PKCE, rotating refresh tokens with reuse detection, and no account merging by matching email
- Built the report comparison API with a four-table join and `ROW_NUMBER()`, returning cohort averages without exposing individuals
- Enforced design tokens with a custom ESLint rule and self-hosted CJK fonts as 229 `unicode-range` slices
- Opened 124 PRs and left 131 review comments, the most on the team

### [sottaejap](https://github.com/jittaejap/sottaejap-server) · Spending Reflection Service

**Backend · Team Project · Hackathon** · [Overview](https://github.com/jittaejap)

Asks "was it worth it?" when the time of a past payment comes around again, then turns the answers into a satisfaction map and saving suggestions.

- Owned the deterministic rule engine and Flyway migrations, keeping AI calls at the edges
- Found a lost update caused by Hibernate's full-column `UPDATE`, reproduced the race on real PostgreSQL, fixed it with `@DynamicUpdate`, and confirmed the test fails (`expected 20000, was 0`) when the fix is removed
- Closed an unauthenticated internal endpoint in production by moving the trust boundary from Nginx into code with a constant-time secret check

### [HongBookStore](https://github.com/HongikBookStore/HongBookStore) · Used Textbook Marketplace for Hongik University

**Full-stack · Graduation Project · Mar–Nov 2025** · [rev](https://github.com/samu9nai/hongbookstore-rev)

A marketplace for Hongik University students to trade used textbooks, with real-time chat, trade reservations, and map-based meetup spots.

- Top contributor with 174 commits and 36 PRs
- Integrated Naver Maps and place search, and added a profanity filter for posts
- Upgraded the frontend and backend to new major versions (React 19, Spring Boot 3.5)
- **rev**: refactoring the codebase after graduation (in progress)

## Tech Stack

**Languages**

<p>
  <img src="https://img.shields.io/badge/Java-18181B?style=flat-square&logo=openjdk&logoColor=white" alt="Java" />
  <img src="https://img.shields.io/badge/TypeScript-18181B?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/JavaScript-18181B?style=flat-square&logo=javascript&logoColor=white" alt="JavaScript" />
  <img src="https://img.shields.io/badge/Python-18181B?style=flat-square&logo=python&logoColor=white" alt="Python" />
</p>

**Backend**

<p>
  <img src="https://img.shields.io/badge/Spring-18181B?style=flat-square&logo=spring&logoColor=white" alt="Spring" />
  <img src="https://img.shields.io/badge/Spring_Boot-18181B?style=flat-square&logo=springboot&logoColor=white" alt="Spring Boot" />
  <img src="https://img.shields.io/badge/Spring_Security-18181B?style=flat-square&logo=springsecurity&logoColor=white" alt="Spring Security" />
  <img src="https://img.shields.io/badge/Hibernate-18181B?style=flat-square&logo=hibernate&logoColor=white" alt="Hibernate" />
  <img src="https://img.shields.io/badge/MyBatis-18181B?style=flat-square" alt="MyBatis" />
</p>

**Frontend**

<p>
  <img src="https://img.shields.io/badge/Vue.js-18181B?style=flat-square&logo=vuedotjs&logoColor=white" alt="Vue.js" />
  <img src="https://img.shields.io/badge/React-18181B?style=flat-square&logo=react&logoColor=white" alt="React" />
</p>

**Database**

<p>
  <img src="https://img.shields.io/badge/MySQL-18181B?style=flat-square&logo=mysql&logoColor=white" alt="MySQL" />
  <img src="https://img.shields.io/badge/PostgreSQL-18181B?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/Redis-18181B?style=flat-square&logo=redis&logoColor=white" alt="Redis" />
</p>

**Infrastructure & Tools**

<p>
  <img src="https://img.shields.io/badge/Docker-18181B?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/Nginx-18181B?style=flat-square&logo=nginx&logoColor=white" alt="Nginx" />
  <img src="https://img.shields.io/badge/AWS_EC2-18181B?style=flat-square" alt="AWS EC2" />
  <img src="https://img.shields.io/badge/Google_Cloud-18181B?style=flat-square&logo=googlecloud&logoColor=white" alt="Google Cloud" />
  <img src="https://img.shields.io/badge/GitHub_Actions-18181B?style=flat-square&logo=githubactions&logoColor=white" alt="GitHub Actions" />
</p>

**Collaboration**

<p>
  <img src="https://img.shields.io/badge/Git-18181B?style=flat-square&logo=git&logoColor=white" alt="Git" />
  <img src="https://img.shields.io/badge/Figma-18181B?style=flat-square&logo=figma&logoColor=white" alt="Figma" />
  <img src="https://img.shields.io/badge/Notion-18181B?style=flat-square&logo=notion&logoColor=white" alt="Notion" />
</p>

**AI Coding Agents**

<p>
  <img src="https://img.shields.io/badge/Claude_Code-18181B?style=flat-square&logo=claude&logoColor=white" alt="Claude Code" />
  <img src="https://img.shields.io/badge/Codex-18181B?style=flat-square" alt="Codex" />
</p>

Also worked with **Flyway, Vite, Tailwind CSS, Playwright, Vitest, and Flask**.

## Problem Solving

[![Solved.ac 프로필](http://mazassumnida.wtf/api/v2/generate_badge?boj=chino)](https://solved.ac/chino)
