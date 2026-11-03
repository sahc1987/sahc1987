<!-- ===== HEADER ===== -->
<a href="https://github.com/sahc1987">
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0077B5,100:00C9A7&height=200&section=header&text=Saul%20Hernandez&fontSize=55&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Full%20Stack%20Developer%20%C2%B7%20React%20%C2%B7%20Node.js%20%C2%B7%20TypeScript%20%C2%B7%20Java&descAlignY=58&descSize=18" alt="header" />
</a>

<p align="center">
<a href="https://www.linkedin.com/in/saul-hernandez-dev/" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="mailto:sahc1987@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
<a href="https://complete-pool-app.vercel.app"><img src="https://img.shields.io/badge/Live%20Demo-CompletePoolApp-000000?style=for-the-badge&logo=vercel&logoColor=white"/></a>
</p>

<p align="center">
<img src="https://img.shields.io/badge/Open%20to%20work-Full%20Stack%20%C2%B7%20Remote%20LATAM%20%C2%B7%20El%20Salvador-43853D?style=flat-square"/>
<img src="https://img.shields.io/badge/Bilingual-ES%20%2F%20EN-4B8BBE?style=flat-square"/>
<img src="https://komarev.com/ghpvc/?username=sahc1987&label=Profile%20Views&color=0077B5&style=flat-square" alt="profile views" />
</p>

<br/>

### 👋 Hi, I'm Saúl

I'm a full stack developer with **7+ years** in software, including team lead and QA lead roles. I build business software that real operations run on: scheduling, billing, inventory, payments, role-based access, and the tests that keep it from breaking.

- 🔧 **Now:** building production apps for small businesses (web + mobile), plus paid freelance client work
- 🏪 **Day job:** General Manager at The UPS Store in Brickell, where I built **CentralDesk**, the operations portal used daily across 4 store locations
- 🧭 **Before:** Telus International, Omnisport and Mitratech, leading teams of up to **12 developers and testers**
- 📍 Moving from **Miami** to **San Salvador**. Open to **full-time remote roles across LATAM** and **on-site/hybrid roles in El Salvador**

<br/>

<!-- ===== FEATURED PROJECTS ===== -->
<h2 align="center">🚀 Featured Projects</h2>

#### 🏊 [CompletePoolApp](https://github.com/sahc1987/CompletePoolApp) · [live demo](https://complete-pool-app.vercel.app) (read-only)

Management system for **Complete Pool Service Inc.**, a real pool service company now running acceptance testing with the owner. Web app for the office plus a mobile app for field workers, on one shared data layer.

- **Operations:** recurring jobs on a schedule, daily route map, job approval flow (submit / approve / flag), inventory with field material requests, payroll hours, owner KPIs, live notifications
- **Money:** estimates signed on screen, automatic invoices with PDF and QR pay links, Stripe online payments, partial payments and reversals
- **Engineering:** three-role RBAC (Owner / Admin / Worker) where you can only manage roles below yours and the last manager can't be removed; PostgreSQL with row level security; 27-model Prisma schema; Zod contracts shared by web and mobile; JWT access + rotating refresh tokens on mobile

<p>
<img src="https://img.shields.io/badge/Next.js_14-000000?style=flat-square&logo=next.js&logoColor=white"/>
<img src="https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white"/>
<img src="https://img.shields.io/badge/Expo_/_React_Native-000020?style=flat-square&logo=expo&logoColor=white"/>
<img src="https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white"/>
<img src="https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white"/>
<img src="https://img.shields.io/badge/Stripe-635BFF?style=flat-square&logo=stripe&logoColor=white"/>
<img src="https://img.shields.io/badge/Jest-C21325?style=flat-square&logo=jest&logoColor=white"/>
</p>

#### 🛒 [Ecommerce](https://github.com/sahc1987/Ecommerce)

General-purpose online store with three clients on one API: customer web shop, staff back office, and a React Native app for iOS/Android. Built with security and data integrity first.

- **Commerce:** product variants with SKU, stock and price per version; guest cart with timed stock holds; Stripe card and cash-on-delivery checkout; shipping with tracking; cancellations, returns and refunds; KPI dashboard; first-run setup wizard
- **Integrity:** row-level locking so two buyers can't take the last unit; idempotency keys so a double click never creates two orders
- **Security:** JWT in httpOnly cookies, bcrypt, Helmet, per-IP rate limiting, magic-byte validation on image uploads
- **Tests:** backend unit and API tests (node:test), web (Vitest), mobile (Jest)

<p>
<img src="https://img.shields.io/badge/React_18-20232A?style=flat-square&logo=react&logoColor=61DAFB"/>
<img src="https://img.shields.io/badge/Redux_Toolkit-764ABC?style=flat-square&logo=redux&logoColor=white"/>
<img src="https://img.shields.io/badge/React_Native-20232A?style=flat-square&logo=react&logoColor=61DAFB"/>
<img src="https://img.shields.io/badge/Node.js-43853D?style=flat-square&logo=node.js&logoColor=white"/>
<img src="https://img.shields.io/badge/Express-404D59?style=flat-square&logo=express&logoColor=white"/>
<img src="https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white"/>
<img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white"/>
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/>
</p>

#### 🏪 CentralDesk · <sub>internal, private repo</sub>

Internal operations portal (React + Node.js/Express) I built for The UPS Store, used daily across **4 store locations**.

<br/>

<!-- ===== HOW I WORK ===== -->
<h2 align="center">🧩 How I Build</h2>

- **Thin routes, one service layer.** Business logic lives in one place; routes and actions only adapt.
- **Validate everything, share the contract.** Zod schemas shared between web and mobile.
- **Protect the data.** Multi-step writes in transactions with row locks; versioned migrations; indexes on searched columns.
- **Test where it matters.** Unit tests that run without a real database, integration tests against a dedicated test DB.
- **Ship clean.** One branch per feature, Conventional Commits, `tsc` and lint clean before merge.
- **AI-assisted, human-reviewed.** I use Claude Code and Codex every day. Nothing ships that I haven't read and understood.

<br/>

<!-- ===== EXPERIENCE ===== -->
<h2 align="center">📈 Experience</h2>

<div align="center">

| Years | Role | Company | Highlights |
|---|---|---|---|
| 2023 – now | Independent Developer | Freelance & clients | Paid client systems and freelance projects (Upwork, Workana and others, under NDA); CompletePoolApp for Complete Pool Service |
| 2020 – now | General Manager | The UPS Store, Brickell | Runs a team of 7-10; built **CentralDesk**, used daily across 4 locations |
| 2019 – 2020 | Full Stack Developer | Telus International | Built an API-management app end to end (React, Node.js, Cassandra): API catalog, consumer onboarding and keys, usage monitoring; maintained PHP and Angular apps and Jenkins/OpenShift pipelines |
| 2017 – 2019 | Team Lead & QA Lead | Omnisport | Led **5 developers + 3 testers** on in-house retail systems (POS, inventory, billing, credit); unblocked **~50 projects** stuck in testing by reworking acceptance and building regression suites |
| 2013 – 2017 | Team Lead & Software Engineer | Mitratech | Legal-tech products for law firms and corporate legal teams; led up to **12 people** and coded the HotDocs move from IE-only to cross-browser (Java, JavaScript, .NET) |

</div>

<br/>

<!-- ===== TECH STACK ===== -->
<h2 align="center">🛠️ Tech Stack</h2>

<p align="center"><b>Languages</b></p>
<p align="center">
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"/>
<img src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white"/>
<img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white"/>
<img src="https://img.shields.io/badge/C%23-512BD4?style=for-the-badge&logo=dotnet&logoColor=white"/>
<img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=databricks&logoColor=white"/>
<img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white"/>
<img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white"/>
</p>

<p align="center"><b>Frontend</b></p>
<p align="center">
<img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB"/>
<img src="https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white"/>
<img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white"/>
<img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white"/>
<img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white"/>
<img src="https://img.shields.io/badge/Redux_Toolkit-764ABC?style=for-the-badge&logo=redux&logoColor=white"/>
<img src="https://img.shields.io/badge/TanStack_Query-FF4154?style=for-the-badge&logo=reactquery&logoColor=white"/>
<img src="https://img.shields.io/badge/Zod-3E67B1?style=for-the-badge&logo=zod&logoColor=white"/>
</p>

<p align="center"><b>Mobile</b></p>
<p align="center">
<img src="https://img.shields.io/badge/React_Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB"/>
</p>

<p align="center"><b>Backend</b></p>
<p align="center">
<img src="https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white"/>
<img src="https://img.shields.io/badge/Express.js-404D59?style=for-the-badge&logo=express&logoColor=white"/>
<img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white"/>
<img src="https://img.shields.io/badge/JSF-007396?style=for-the-badge&logo=java&logoColor=white"/>
<img src="https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white"/>
<img src="https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white"/>
<img src="https://img.shields.io/badge/NextAuth-000000?style=for-the-badge&logo=auth0&logoColor=white"/>
<img src="https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white"/>
<img src="https://img.shields.io/badge/Stripe-635BFF?style=for-the-badge&logo=stripe&logoColor=white"/>
<img src="https://img.shields.io/badge/Cloudinary-3448C5?style=for-the-badge&logo=cloudinary&logoColor=white"/>
</p>

<p align="center"><b>Databases</b></p>
<p align="center">
<img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white"/>
<img src="https://img.shields.io/badge/MySQL-00000F?style=for-the-badge&logo=mysql&logoColor=white"/>
<img src="https://img.shields.io/badge/SQL_Server-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white"/>
<img src="https://img.shields.io/badge/Oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white"/>
<img src="https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white"/>
<img src="https://img.shields.io/badge/Cassandra-1287B1?style=for-the-badge&logo=apache-cassandra&logoColor=white"/>
<img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white"/>
</p>

<p align="center"><b>QA & Testing</b></p>
<p align="center">
<img src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white"/>
<img src="https://img.shields.io/badge/REST_Assured-5A9E3F?style=for-the-badge&logo=java&logoColor=white"/>
<img src="https://img.shields.io/badge/Jira-0052CC?style=for-the-badge&logo=jira&logoColor=white"/>
<img src="https://img.shields.io/badge/TestRail-65C179?style=for-the-badge&logo=checkmarx&logoColor=white"/>
<img src="https://img.shields.io/badge/Zephyr-1E6FD9?style=for-the-badge&logo=atlassian&logoColor=white"/>
<img src="https://img.shields.io/badge/SonarQube-4E9BCD?style=for-the-badge&logo=sonarqube&logoColor=white"/>
<img src="https://img.shields.io/badge/Jest-C21325?style=for-the-badge&logo=jest&logoColor=white"/>
<img src="https://img.shields.io/badge/Testing_Library-E33332?style=for-the-badge&logo=testinglibrary&logoColor=white"/>
</p>

<p align="center"><b>DevOps & Tools</b></p>
<p align="center">
<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>
<img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white"/>
<img src="https://img.shields.io/badge/OpenShift-EE0000?style=for-the-badge&logo=redhatopenshift&logoColor=white"/>
<img src="https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white"/>
<img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white"/>
<img src="https://img.shields.io/badge/CI%2FCD-2088FF?style=for-the-badge&logo=github-actions&logoColor=white"/>
<img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white"/>
<img src="https://img.shields.io/badge/Google_Cloud-4285F4?style=for-the-badge&logo=google-cloud&logoColor=white"/>
<img src="https://img.shields.io/badge/REST_API-009688?style=for-the-badge&logo=fastapi&logoColor=white"/>
</p>

<br/>

<!-- ===== FOOTER ===== -->
<p align="center">
<i>"Ship it working, test it before users do, keep learning."</i>
</p>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:00C9A7,100:0077B5&height=120&section=footer" alt="footer" />
