<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=26&duration=3500&pause=1000&color=58A6FF&center=true&vCenter=true&width=600&lines=Software+Engineer" alt="Typing SVG" />

# Ramez Ragaay

**Software Engineer — building scalable backend systems, real-time applications, and clean architectures.**

B.Sc. Computer Science @ Cairo University · Class of 2026 · Cairo, Egypt

<br>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ramez-ragaay04)
[![Email](https://img.shields.io/badge/Email-Contact-58A6FF?style=flat-square&logo=maildotru&logoColor=white)](mailto:ramezragaay@outlook.com)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-8957E5?style=flat-square&logo=github&logoColor=white)](https://github.com/RamezRagaay)

<br>

`Open to:` **Internships** · **Freelance** · **Full-Time Backend / Software Engineering Roles**

</div>

<br>

---

## About

I'm a software engineer who cares about how systems are **designed**, not just how they run. My core strength is backend engineering — APIs, real-time systems, data modeling, authentication, and background processing — but I work comfortably across the stack, from PostgreSQL schemas to React Native clients.

- 🎓 **B.Sc. Computer Science**, Faculty of Computers & AI, Cairo University *(2022 – 2026)*
- 💼 Interned at **Dell Technologies** (enterprise tech & cloud) and **Egronx** (backend engineering, Spring Boot)
- 🏗️ Currently building **AllaTre** — a real-time C2C auction marketplace (graduation project)
- 🏆 **ECPC** competitive programming qualifier — 2023, 2024, 2025
- 📚 Deepening my knowledge in **distributed systems, system design, and software architecture**

<br>

## Tech Stack

<table>
<tr>
<td valign="top" width="50%">

**Languages**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)

**Backend**

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Socket.IO](https://img.shields.io/badge/Socket.IO-010101?style=flat-square&logo=socketdotio&logoColor=white)
![BullMQ](https://img.shields.io/badge/BullMQ-D93B3B?style=flat-square&logo=redis&logoColor=white)
![JWT](https://img.shields.io/badge/JWT_/_OAuth_2.0-000000?style=flat-square&logo=jsonwebtokens&logoColor=white)

**Databases & Caching**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)

</td>
<td valign="top" width="50%">

**Frontend & Mobile**

![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![React Native](https://img.shields.io/badge/React_Native_(Expo)-000020?style=flat-square&logo=expo&logoColor=white)
![TanStack Query](https://img.shields.io/badge/TanStack_Query-FF4154?style=flat-square&logo=reactquery&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

**DevOps & Tooling**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

**Testing**

![JUnit](https://img.shields.io/badge/JUnit-25A162?style=flat-square&logo=junit5&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white)
![Integration Testing](https://img.shields.io/badge/Unit_&_Integration_Testing-58A6FF?style=flat-square)

</td>
</tr>
</table>

<br>

## Featured Projects

### 🔨 AllaTre — Real-Time C2C Auction Marketplace
> **Graduation Project** · `Node.js` `TypeScript` `Express` `PostgreSQL` `Prisma` `Redis` `BullMQ` `Socket.IO` `React Native`

A consumer-to-consumer auction platform built as a **modular monolith** with a shared infrastructure layer (event bus, background jobs).

- ⚡ Real-time bidding & notifications over Socket.IO — authenticated handshakes, per-socket rate limiting, room-based broadcasting
- 🔐 Multi-factor signup (email verification + SMS OTP) with a **three-tier JWT model** (ephemeral, access, rotating refresh tokens)
- 🧱 PostgreSQL schema designed through Prisma migrations; background processing with BullMQ + Redis
- 🔌 Integrations: Cloudinary, Google OAuth, Expo Push (with webhooks), Nodemailer

### 🍽️ Bistro-Bliss — Restaurant Booking Platform
> `MongoDB` `Express` `React` `Node.js`

Full-stack booking and menu-management system with JWT auth, **role-based access control** (user/admin), admin approval workflows, and automated email notifications on booking status changes.

### 🎓 Learning Management System
> `Java` `Spring Boot` `JUnit`

RESTful APIs for user management, courses, assessments, grading, and performance tracking — with **JUnit test coverage** across core service layers.

### 🎬 MovieFlex — Movie Discovery App
> `React Native (Expo)` `TypeScript` `Appwrite` `Clerk`

Mobile movie-discovery app with OAuth authentication, TMDB API integration, a trending algorithm, and lazy-loaded, performance-optimized UI.

<br>

## How I Build Software

- **Design before code** — clear data models, well-defined boundaries, and explicit contracts between modules
- **Real-time done right** — authenticated connections, rate limiting, and predictable broadcasting patterns
- **Reliability by default** — background jobs for slow work, caching where it matters, tests where it counts
- **Ship clean** — readable code, meaningful commits, CI/CD from day one

<br>

## GitHub Stats

<div align="center">

<img height="165" src="https://github-stats-extended.vercel.app/api?username=RamezRagaay&theme=github_dark&hide_border=true&include_all_commits=true&rank_icon=github&show_icons=true" alt="GitHub Stats" />
<img height="165" src="https://github-stats-extended.vercel.app/api/top-langs/?username=RamezRagaay&theme=github_dark&hide_border=true&layout=compact&langs_count=8" alt="Top Languages" />

<img src="https://streak-stats.demolab.com/?user=RamezRagaay&theme=github-dark-blue&hide_border=true" alt="Streak Stats" />

<img src="https://github-readme-activity-graph.vercel.app/graph?username=RamezRagaay&theme=github-compact&hide_border=true&area=true&color=58A6FF&line=58A6FF&point=FFFFFF" alt="Activity Graph" width="95%" />

</div>

<br>

## Certifications & Achievements

| | |
|---|---|
| 🏆 | **ECPC Qualifications** — Egyptian Collegiate Programming Contest (2023 · 2024 · 2025) |
| 📜 | **Full-Stack MERN Diploma** — AMIT Learning (2024) |
| 🏢 | **Summer Technology Internship Certificate** — Dell Technologies (2025) |

<br>

---

<div align="center">

**Let's build something together.**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-ramez--ragaay04-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ramez-ragaay04)
[![Email](https://img.shields.io/badge/Email-ramezragaay@outlook.com-58A6FF?style=for-the-badge&logo=maildotru&logoColor=white)](mailto:ramezragaay@outlook.com)

<br>

<img src="https://komarev.com/ghpvc/?username=RamezRagaay&color=58A6FF&style=flat-square&label=Profile+Views" alt="Profile Views" />

</div>
