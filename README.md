<h1 align="center">Hi, I'm Santiago Gonzalez 👋</h1>

<p align="center">
  <b>Full-Stack Developer · QA Automation</b><br/>
  TypeScript · React · Node.js — web apps built with clean architecture, automated tests and CI/CD.<br/>
  📍 Medellín, Colombia &nbsp;·&nbsp; 🎓 Universidad de Medellín
</p>

---

### 🧑‍💻 About me

- 🔭 I build full-stack web applications with **React + TypeScript** on the frontend and **Node.js / Express** REST APIs designed with **Clean Architecture** on the backend.
- 🧪 Quality is part of how I build, not an afterthought: unit and integration tests, **E2E automation** with Cypress, Playwright and Serenity/JS (Screenplay pattern), accessibility checks with axe, and load testing.
- ⚙️ I ship through pipelines: **Docker**, **Jenkins**, **GitHub Actions** and **SonarQube** quality gates, deploying to Vercel.
- 📱 Currently exploring mobile development with **Flutter** (offline-first apps with Drift + Firestore).
- 💼 Open to **junior Full-Stack / QA Automation** roles and internships.

---

### 🚀 Featured projects

#### 📱 CelularPro — e-commerce for certified phones &nbsp;<sub>team project</sub>

Online store for new, refurbished and verified used phones, built by a small team as a production-style project.

| Repo | Highlights |
|---|---|
| [**celularpro-web**](https://github.com/Santiago-mg/celularpro-web) | React 18 + TypeScript + Vite, React Hook Form + Zod. **415 Vitest + Testing Library tests**, E2E suites in **Serenity/JS (Screenplay) + Playwright + Cucumber** and **Cypress**, axe accessibility checks. |
| [**celularpro-api**](https://github.com/Santiago-mg/celularpro-api) | Express + TypeScript REST API with **Clean Architecture**, Prisma + PostgreSQL, JWT, Zod validation, Helmet, login-attempt limiting and load tests. |
| **CI/CD** | Jenkins orchestrator: typecheck → tests + coverage → **SonarQube Quality Gate** → Docker images → E2E against the running stack → deploy to **Vercel**. |

#### 🏡 [EstadiaPro](https://github.com/Santiago-mg/estadiapro) — Airbnb-style stays platform

Monorepo with three independently containerized layers: SSR frontend (Express + Pug + Tailwind), REST API (Express + Sequelize + JWT) and MySQL 8. Runs with **Docker Compose** and includes **Kubernetes** manifests and Jest tests. Admin panel with Chart.js analytics, property and review moderation, a **dynamic pricing engine**, audit log and CSV export.

#### 🎟️ [Mi Boleta](https://github.com/Santiago-mg/Mi-boleta) — lottery & raffle ticket tracker

React + TypeScript SPA consuming a REST API: JWT auth with protected and admin-only routes, ticket CRUD with React Hook Form + Zod, statistics dashboard, pagination, light/dark theme and a seeding script for 1,000+ records.

#### 🏢 [Real Estate API](https://github.com/Santiago-mg/real-estate-api) — property management REST API

Express API organized in **domain / application / infrastructure** layers with use cases and repository interfaces. Sequelize + PostgreSQL (Supabase), JWT authentication, Joi validation and bcrypt.

#### 🎬 [Movies](https://github.com/Santiago-mg/movies-drift-firebase) — offline-first Flutter app

Flutter app that stores personal movie notes locally with **Drift (SQLite, also on web via WASM)** and syncs pending changes to **Cloud Firestore** when online, using a repository with local and remote data sources.

#### 🌍 [Dream Vacation](https://github.com/Santiago-mg/dream-vacation-app) — Dockerized full-stack app

React + Express + MySQL app that consumes the REST Countries API. Each service has its own Dockerfile and a **GitHub Actions** matrix pipeline builds and pushes the images to Docker Hub.

---

### 🛠️ Tech stack

| | |
|---|---|
| **Languages** | ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white) |
| **Frontend** | ![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB) ![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white) ![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white) ![React Hook Form](https://img.shields.io/badge/React_Hook_Form-EC5990?style=flat-square&logo=reacthookform&logoColor=white) ![Zod](https://img.shields.io/badge/Zod-3E67B1?style=flat-square&logo=zod&logoColor=white) |
| **Backend** | ![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white) ![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white) ![Sequelize](https://img.shields.io/badge/Sequelize-52B0E7?style=flat-square&logo=sequelize&logoColor=white) ![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white) |
| **Databases** | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white) ![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white) ![Firebase](https://img.shields.io/badge/Firebase-DD2C00?style=flat-square&logo=firebase&logoColor=white) ![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white) |
| **Testing & QA** | ![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=flat-square&logo=vitest&logoColor=white) ![Jest](https://img.shields.io/badge/Jest-C21325?style=flat-square&logo=jest&logoColor=white) ![Testing Library](https://img.shields.io/badge/Testing_Library-E33332?style=flat-square&logo=testinglibrary&logoColor=white) ![Cypress](https://img.shields.io/badge/Cypress-69D3A7?style=flat-square&logo=cypress&logoColor=black) ![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white) ![Serenity/JS](https://img.shields.io/badge/Serenity%2FJS-1F6FEB?style=flat-square) ![Cucumber](https://img.shields.io/badge/Cucumber-23D96C?style=flat-square&logo=cucumber&logoColor=white) ![Katalon](https://img.shields.io/badge/Katalon-1A1A1A?style=flat-square&logo=katalon&logoColor=white) |
| **DevOps & Cloud** | ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white) ![SonarQube](https://img.shields.io/badge/SonarQube-4E9BCD?style=flat-square&logo=sonarqube&logoColor=white) ![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white) ![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white) |
| **Mobile** | ![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white) |

---

### 🇨🇴 En español

Soy **desarrollador Full-Stack con enfoque en QA Automation**, de Medellín, estudiante de la Universidad de Medellín. Construyo aplicaciones web con **React + TypeScript** y APIs en **Node.js / Express** con **Clean Architecture**, y me tomo en serio la calidad: pruebas unitarias, de integración y **E2E automatizadas** (Cypress, Playwright, Serenity/JS), accesibilidad y pipelines de **CI/CD** con Docker, Jenkins, GitHub Actions y SonarQube.

Estoy abierto a oportunidades como **desarrollador Full-Stack junior o QA Automation**, y a prácticas profesionales.

---

<p align="center"><i>Thanks for stopping by! · ¡Gracias por pasar!</i></p>
