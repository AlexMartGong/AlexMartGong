<div align="center">

# Alex Martínez González

### ☕ Java & Spring Boot Developer · Full-Stack Engineer

📍 Tequila, Jalisco, Mexico

*I build software that runs real businesses — a multi-tenant point-of-sale SaaS in commercial pilot and an ERP/retail ecosystem processing **2,100+ live transactions every month**.*

<br/>

<a href="https://www.linkedin.com/in/axmgdev"><img src="https://img.shields.io/badge/LinkedIn-axmgdev-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="mailto:ing.alex.martinez.g@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
<a href="https://github.com/AlexMartGong"><img src="https://img.shields.io/badge/GitHub-AlexMartGong-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/></a>

</div>

---

## 🚀 About Me

I'm a software engineer specialized in **backend development with Java & Spring Boot**, with production experience designing, shipping, and operating SaaS and ERP platforms end to end — from domain modeling and security to CI/CD and VPS infrastructure.

- 🧩 I design **domain-oriented, modular clean architectures** that stay maintainable as products grow.
- ⚙️ I automate painful processes — like turning a ~10-minute manual invoicing flow into a **<10-second automated one** (Mexican CFDI 4.0).
- 🌉 Full-stack when it matters: **React + TypeScript** frontends (installable PWAs) talking to well-documented REST APIs.
- 🔌 I connect software to the physical world: serial-port scales, ESC/POS thermal printers, barcode scanners.
- 🎓 **B.Eng. in Informatics** — TecNM Campus Tequila (Mar 2026) · **Distinguished Student Award** · Dual Education (work-study) program.

---

## ⭐ Featured Projects

### 🛒 VentaCore — Multi-Tenant Point-of-Sale SaaS

**Founder & Developer** · Apr 2026 – Present · 🌐 [ventacore.app](https://ventacore.app)

![Java 21](https://img.shields.io/badge/Java_21-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot 4](https://img.shields.io/badge/Spring_Boot_4-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![PostgreSQL 16](https://img.shields.io/badge/PostgreSQL_16-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![React 19](https://img.shields.io/badge/React_19-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![PWA](https://img.shields.io/badge/PWA-5A0FC8?style=flat-square&logo=pwa&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

> A multi-tenant POS SaaS built from scratch, currently in **commercial pilot with its first active client** (500+ products, real daily sales) and another client on the waitlist.

- 🏗️ **Domain-oriented modular architecture**: sales, inventory, customer store credit (*"fiado"*), cash-register shifts, subscriptions, notifications, and auditing — each an isolated domain module.
- 🔐 **Dual-flow JWT security** for store users and SaaS admins, with per-request state revalidation, role-based access control, and login rate limiting powered by **Bucket4j**.
- 📱 Installable **PWA frontend** (React 19, TypeScript, Zustand, Tailwind CSS 4) with **camera-based barcode scanning**.
- ✅ Service-layer tests with Mockito and controller tests with `@WebMvcTest` importing the real security configuration; **Qodana static analysis wired into CI**.
- 🚀 Zero-touch **CI/CD**: GitHub Actions building and deploying via Docker Compose to a Linux VPS.

### 🏪 La Pasadita — ERP & Retail Ecosystem

**Full-Stack Developer** · Mar 2025 – Present · 🌐 [lapasadita.app](https://lapasadita.app)

![Java 21](https://img.shields.io/badge/Java_21-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot 3](https://img.shields.io/badge/Spring_Boot_3-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![React 18](https://img.shields.io/badge/React_18-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Facturapi](https://img.shields.io/badge/Facturapi_CFDI_4.0-4F46E5?style=flat-square)
![Cloudflare R2](https://img.shields.io/badge/Cloudflare_R2-F38020?style=flat-square&logo=cloudflare&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

> High-volume transactional engine running **in production at 2 retail stores**, processing **2,100+ monthly transactions** across a 300+ product catalog.

- 🧾 **CFDI 4.0 electronic invoicing automation** via the Facturapi REST API — real-time stamping with automated XML/PDF email delivery — cutting invoicing time by **more than 98%** (~10 min → <10 s per invoice).
- ⚖️ Custom **Java WebSocket agent** bridging the browser with physical hardware — digital scales (RS-232) and ESC/POS thermal printers — **shaving 6–7 seconds off every checkout**.
- 🧪 JUnit 5 + Mockito coverage of critical **tax-compliance rules** (RESICO income-tax withholding, SAT catalog validation, cancellation flows); API documented with Spring REST Docs.
- ☁️ Operated on a **Linux VPS** with Docker Compose, GitHub Actions CI/CD, Spring Security (JWT), and **Cloudflare CDN + R2** image storage (AWS SDK v2).
- 💰 Digitizing the point of sale **cut paper-related operating costs by 70%**.

### 🎓 SICIA — School Management System (TecNM)

**Frontend Development Lead** · Jan 2025 – Dec 2025 · Institutional system, TecNM Campus Tequila

![PHP](https://img.shields.io/badge/PHP_(PDO)-777BB4?style=flat-square&logo=php&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Bootstrap 5](https://img.shields.io/badge/Bootstrap_5-7952B3?style=flat-square&logo=bootstrap&logoColor=white)
![jQuery](https://img.shields.io/badge/jQuery-0769AD?style=flat-square&logo=jquery&logoColor=white)

> Institutional SPA serving **500+ active users and ~50 faculty members**, built as my capstone internship (*Residencia Profesional*).

- 🗂️ **12 functional modules** — grades, schedules, course offerings, withdrawals, and more.
- 🛡️ **Role-Based Access Control (RBAC)** with three privilege tiers: Admin, Faculty, and Program Head.
- 📊 **Client-side Excel report-matrix processing**, moving heavy report generation off the server entirely.

---

## 🛠️ Tech Stack

#### ⚙️ Backend

![Java 17/21](https://img.shields.io/badge/Java_17%2F21-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot 3/4](https://img.shields.io/badge/Spring_Boot_3%2F4-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![Maven](https://img.shields.io/badge/Maven-C71A36?style=for-the-badge&logo=apachemaven&logoColor=white)
![Lombok](https://img.shields.io/badge/Lombok-B32629?style=for-the-badge)
![Spring Security](https://img.shields.io/badge/Spring_Security_(JWT)-6DB33F?style=for-the-badge&logo=springsecurity&logoColor=white)
![JPA/Hibernate](https://img.shields.io/badge/JPA%2FHibernate-59666C?style=for-the-badge&logo=hibernate&logoColor=white)
![REST APIs](https://img.shields.io/badge/REST_APIs-009688?style=for-the-badge)
![WebSockets](https://img.shields.io/badge/WebSockets-010101?style=for-the-badge)

#### 🎨 Frontend

![React 18/19](https://img.shields.io/badge/React_18%2F19-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![Zustand](https://img.shields.io/badge/Zustand-443E38?style=for-the-badge)
![Tailwind CSS 4](https://img.shields.io/badge/Tailwind_CSS_4-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![PWA](https://img.shields.io/badge/PWA-5A0FC8?style=for-the-badge&logo=pwa&logoColor=white)

#### 🗄️ Databases & DevOps

![PostgreSQL 16](https://img.shields.io/badge/PostgreSQL_16-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Docker Compose](https://img.shields.io/badge/Docker_Compose-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare_CDN%2FR2-F38020?style=for-the-badge&logo=cloudflare&logoColor=white)
![Linux](https://img.shields.io/badge/Linux_(VPS)-FCC624?style=for-the-badge&logo=linux&logoColor=black)

#### 🧪 Testing & Quality

![JUnit 5](https://img.shields.io/badge/JUnit_5-25A162?style=for-the-badge&logo=junit5&logoColor=white)
![Mockito](https://img.shields.io/badge/Mockito-78A641?style=for-the-badge)
![@WebMvcTest](https://img.shields.io/badge/%40WebMvcTest-6DB33F?style=for-the-badge)
![Qodana](https://img.shields.io/badge/Qodana-07C3F2?style=for-the-badge&logo=qodana&logoColor=white)
![Spring REST Docs](https://img.shields.io/badge/Spring_REST_Docs-6DB33F?style=for-the-badge)

#### 🔌 Integrations & Hardware

![RS-232](https://img.shields.io/badge/RS--232_Serial-4B5563?style=for-the-badge)
![ESC/POS](https://img.shields.io/badge/ESC%2FPOS_Thermal_Printing-1F2937?style=for-the-badge)
![Facturapi](https://img.shields.io/badge/Facturapi_(CFDI_4.0_e--invoicing)-4F46E5?style=for-the-badge)

---

## 📊 GitHub Analytics

<div align="center">

<img height="180" alt="Alex's GitHub stats" src="https://github-readme-stats.vercel.app/api?username=AlexMartGong&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true"/>
<img height="180" alt="Alex's top languages" src="https://github-readme-stats.vercel.app/api/top-langs/?username=AlexMartGong&layout=compact&theme=tokyonight&hide_border=true&langs_count=8"/>

</div>

---

## 🤝 Let's Connect

<div align="center">

Whether it's a backend/full-stack opportunity, a freelance project, or just talking shop about Spring Boot and clean architecture — my inbox is open.

<br/>

<a href="https://www.linkedin.com/in/axmgdev"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="mailto:ing.alex.martinez.g@gmail.com"><img src="https://img.shields.io/badge/Email-ing.alex.martinez.g%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
<a href="https://github.com/AlexMartGong"><img src="https://img.shields.io/badge/GitHub-AlexMartGong-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/></a>

<br/><br/>

<sub>⚡ Built with care in Tequila, Jalisco — yes, like the drink 🥃</sub>

</div>
