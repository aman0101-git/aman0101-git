<!--
  PROFILE README  —  goes in the special repo named "aman0101-git"
  (Create a public repo named exactly aman0101-git, add this as README.md.)
  Replace: <LINKEDIN_URL>, <PORTFOLIO_URL>, and the QAMS link after you rename the repo.
-->

<h1 align="center">Hi, I'm Aman Undre 👋</h1>

<p align="center">
  <b>Full-Stack Developer</b> · TypeScript · React / Next.js · Node.js · NestJS · MySQL
  <br/>
  I design, build, and operate production internal platforms — used daily by 50+ people.
</p>

<p align="center">
  <a href="mailto:aman.undre01@gmail.com"><img src="https://img.shields.io/badge/Email-aman.undre01@gmail.com-D14836?style=flat&logo=gmail&logoColor=white"></a>
  <a href="[<LINKEDIN_URL>](https://www.linkedin.com/in/aman-undre-0a1b0c1d/)"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat&logo=linkedin&logoColor=white"></a>
  <a href="[<PORTFOLIO_URL>](https://personal-portfolio-bay-omega.vercel.app/)"><img src="https://img.shields.io/badge/Portfolio-Visit-111111?style=flat&logo=vercel&logoColor=white"></a>
  <img src="https://img.shields.io/badge/Pune,%20India-📍-success?style=flat">
</p>

---

## 👨‍💻 About me

I'm a full-stack developer based in Pune with 1+ year of experience across internship and full-time roles. My focus is **internal enterprise platforms** — the systems a business actually runs on every day.

Right now I'm a **Software Developer at Firstclose Solutions**, where I've single-handedly architected and shipped **four production platforms** (AMS, CMS, QAMS, HRMS) that 50+ agents, supervisors, and admins use daily to run BPO operations — replacing manual spreadsheet workflows end to end.

What I care about as an engineer isn't just making features work — it's making systems that **stay correct and stay up** in production: role-based access enforced in the backend, multi-tenant data isolation at the SQL layer, query performance, audit trails, and clean operational behaviour (rate limiting, health checks, graceful shutdown). I own features end to end: requirements → schema → API → UI → deployment.

- 🔭 Currently building & maintaining four internal platforms at Firstclose Solutions
- 🌱 Deepening backend architecture, SQL performance, and system design
- 💬 Ask me about RBAC, multi-tenant data isolation, audit logging, or React + TypeScript at scale
- 🎯 Open to full-stack / backend software engineering roles

---

## 🛠️ Tech stack

**Languages**
<br/>
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![Java](https://img.shields.io/badge/Java-007396?logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?logo=postgresql&logoColor=white)

**Frontend**
<br/>
![React](https://img.shields.io/badge/React-61DAFB?logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?logo=nextdotjs&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?logo=vite&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-06B6D4?logo=tailwindcss&logoColor=white)
![Material UI](https://img.shields.io/badge/MUI-007FFF?logo=mui&logoColor=white)

**Backend**
<br/>
![Node.js](https://img.shields.io/badge/Node.js-339933?logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?logo=express&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?logo=nestjs&logoColor=white)
![REST](https://img.shields.io/badge/REST_APIs-005571?logo=fastapi&logoColor=white)
![JWT](https://img.shields.io/badge/JWT_Auth-000000?logo=jsonwebtokens&logoColor=white)

**Data & tooling**
<br/>
![MySQL](https://img.shields.io/badge/MySQL-4479A1?logo=mysql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?logo=mongodb&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?logo=prisma&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?logo=postman&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?logo=vercel&logoColor=white)
![Render](https://img.shields.io/badge/Render-46E3B7?logo=render&logoColor=white)

**Foundations:** Data Structures & Algorithms · OOP · DBMS · Operating Systems · Computer Networks

---

## 🚀 Featured projects

> Four internal enterprise platforms I built and operate at Firstclose Solutions, plus selected earlier work.

### 🏢 [Customer Management System (CMS)](https://github.com/aman0101-git/Customer-Management-System)
Role-based lead & sales-pipeline platform for a real-estate sales org.
`React 19` · `TypeScript` · `Express 5` · `MySQL` · `TanStack Query`
- 11-stage lead pipeline with per-lead **audit logging** and scheduled follow-ups
- **Supervisor-scoped multi-tenant isolation enforced in SQL** (a supervisor can only ever see their own team)
- Analytics dashboards: pipeline funnels, an agent-by-status performance matrix, Excel export
- Production-hardened: gzip, connection pooling, login rate limiting, request-correlation IDs, `/healthz`, graceful shutdown
- _~120+ commits over ~4.5 months_

### 🎧 [Quality Audit Management System (QAMS)](https://github.com/aman0101-git/Quality-Audit-Management-System)
Call-center QA auditing & scoring platform.
`NestJS` · `Prisma` · `React 19` · `TypeScript` · `MySQL`
- Weighted, **versioned scorecards** with a pure, deterministic **scoring engine**
- Server-enforced audit lifecycle: `DRAFT → IN_PROGRESS → SUBMITTED → PUBLISHED → REVIEWED`
- **Immutable published records** with snapshot-based revision history (tamper-evident audit trail)
- Agent acknowledgment / dispute workflow

### 📞 [Agent Management System (AMS)](https://github.com/aman0101-git/Agent-Management-System)
Dialer-integrated platform for loan-collection operations.
`React` · `Node.js`
- Used **daily by 50+ agents** to track interactions and log call dispositions in real time
- Replaced manual spreadsheet tracking with a live, supervisor-visible system

### 🧑‍💼 [HR Management System (HRMS)](https://github.com/aman0101-git/HR_Management_System)
Internal HR platform for a BPO operation.
`React` · `TypeScript` · `Node.js` · `MySQL`
- Manages agent **attendance, leave, and employee-lifecycle** data in one place

<details>
<summary><b>More work — internship & personal projects</b></summary>

- **Hangar-HQ** — DGCA exam-prep platform (MERN): mock-test engine, performance analytics, JWT auth, secure sessions. _(Fingspace internship)_
- **[Arrivo](https://github.com/aman0101-git/Arrivo)** — MVC travel-booking app: Passport.js auth, Leaflet maps, Cloudinary uploads, EJS SSR.
- **[Personal Portfolio](https://github.com/aman0101-git/Personal-Portfolio)** — Next.js + Tailwind CSS.
- **Data analytics** — interactive dashboards & reports in Python, SQL, Excel, and Power BI _(Codaaz Data Analyst internship)_.

</details>

---

## 💼 Experience

**Software Developer** — *Firstclose Solutions, Pune* · Dec 2025 – Present
Architected and shipped four internal enterprise platforms (AMS, CMS, QAMS, HRMS) used daily by 50+ agents, supervisors, and admins. Engineered REST APIs and normalized MySQL schemas with TypeScript, Node.js, and Express for concurrent multi-role access. Owned the full SDLC per platform.

**Software Development Engineer Intern** — *Fingspace* · Jun 2025 – Nov 2025
Built Hangar-HQ (MERN DGCA exam-prep) and Arrivo (MVC travel-booking). Optimized Mongoose schemas to reduce query times; collaborated via Git/GitHub on reviews, debugging, and deployments.

**Data Analyst Intern** — *Codaaz Software Pvt. Ltd.* · Jan 2025 – May 2025
Built interactive BI dashboards and reports (Python, SQL, Excel, Power BI) to support decisions across internal teams.

---

## 🎓 Education

**B.Tech** — Yeshwantrao Chavan College of Engineering (YCCE), Nagpur · CGPA 7.5 · 2025

---

## 📫 Get in touch

- 📧 **aman.undre01@gmail.com**
- 💼 **LinkedIn:** `https://www.linkedin.com/in/aman-undre-0a1b0c1d`
- 🌐 **Portfolio:** `https://personal-portfolio-bay-omega.vercel.app`
- 📍 Pune, Maharashtra, India

<p align="center"><i>Open to full-stack and backend software engineering opportunities.</i></p>
