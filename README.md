<h1 align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=26&pause=1000&color=0E75B6&center=true&vCenter=true&width=800&lines=Returaj+Proshad+Shornocar;Software+Engineer;Backend+%7C+Mobile+%7C+System+Architecture" alt="Typing SVG" />
</h1>

<p align="center">
  <a href="mailto:returajsumon0808@gmail.com"><img src="https://img.shields.io/badge/Email-returajsumon0808%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
  <a href="https://www.linkedin.com/in/returaj-proshad"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <img src="https://komarev.com/ghpvc/?username=returajproshad&label=Profile+Views&color=0e75b6&style=for-the-badge" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Software_Engineer-Full--Stack-0E75B6?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Architecture-Clean_%7C_SOLID-00C853?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Backend-Spring_Boot_%7C_Node.js-6DB33F?style=for-the-badge&logo=spring&logoColor=white" />
  <img src="https://img.shields.io/badge/Mobile-Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white" />
  <img src="https://img.shields.io/badge/Play_Store-50K%2B_Downloads-34A853?style=for-the-badge&logo=google-play&logoColor=white" />
</p>

---

## 🧑‍💻 About Me

Software Engineer with production experience since **September 2024**, having built and shipped **three concurrent enterprise-grade systems** end-to-end — not as a single-stack specialist, but as someone who reasons about a problem first and picks the right layer of the stack second.

My work spans system design (multi-backend factory patterns, dynamic RBAC), client engineering (metadata-driven UI rendering 90+ dynamic forms), native/platform integration (Win32 + ESC/POS via Method Channels), authentication (JWT/RBAC), and distributed-systems concerns like offline-first data synchronization — caching strategies (SWR/TTL/LRU) and conflict resolution (LWW, Operational Transformation, CRDTs). I work directly with backend teams on Spring Boot REST API design and contribute to Node.js services myself when the problem calls for it.

```
🧩 Focus:      Systems thinking, architecture, and correctness — the stack is a means, not the identity
📱 Published:  CodeHorse on Play Store — 50K+ Downloads, 4.3★ Rating
📦 Open Source: rj_form_engine — schema-driven form engine, framework-agnostic core (pub.dev)
🏆 Competitive: ICPC 2021 Regional Contestant | 1,100+ Problems Solved
🎓 Education:  B.Sc. CSE — Islamic University, Bangladesh (CGPA: 3.63/4.00)
```

---

## 💼 Professional Experience

### 🏢 One Direction Companies Limited (ODCL) — Software Engineer
`Apr 2025 – Jun 2026` · Dhaka, Bangladesh

Owned end-to-end engineering across **3 concurrent enterprise production systems** — Smart Gowala, FoodExpo Kiosk, and Shimana — spanning livestock management, self-service F&B POS kiosks, and border compliance workflows, working across client, API, and data layers.

- Architected a **multi-backend abstraction layer** (Factory Pattern) letting the same application swap between Firebase, PostgreSQL, and Spring Boot backends at build/runtime — a system-design decision, not a mobile-specific one
- Engineered a **metadata-driven rendering engine** dynamically generating **90+ complex forms** from JSON configuration, cutting manual UI development effort by ~90% — later extracted into the open-source **rj_form_engine** package
- Designed a **centralized, type-safe routing & pagination framework**, standardizing navigation and data access across **30+ feature modules**
- Implemented **JWT-based authentication with dynamic RBAC**, letting a single codebase serve multiple user roles under granular, module-level permissions
- Built a **cross-platform POS kiosk system** (Windows & Android) integrating native Win32 APIs and ESC/POS thermal printers via platform channel abstractions
- Improved application performance by **30%** (measured via profiling tools) through lazy loading and optimized state subscriptions, reducing unnecessary re-renders
- Set up **GitHub Actions CI/CD** pipelines automating build and deployment, including automatic production app updates
- Partnered directly with backend engineers on **Spring Boot REST API** contracts and contributed to Node.js services covering REST endpoints and Firestore integration
- Mentored junior engineers on Clean Architecture and SOLID principles through structured code reviews

### 🧳 Kensink Labs — Software Engineer (Contract)
`Mar 2025 – Apr 2025` · Remote

- Delivered an **AI-driven itinerary timeline feature** for the Sootcase travel application, translating design specs into production UI and integrating REST APIs under a strict deadline

### 📰 Brainwave Matrix Solutions — Software Engineer Intern
`Sep 2024 – Oct 2024` · Remote

- Built a responsive application consuming REST APIs with clean, testable state management, delivered within the internship timeline

---

## 🚀 Professional Projects

> These are production systems built during my time at ODCL. Source code is confidential; architecture is documented publicly.

---

### 🐄 [Smart Gowala (Khabani) — Enterprise Livestock Management ERP](https://github.com/ReturajProshad/professional-summary/blob/main/SmartGowala%20(KHABANI).md)
> *Clean Architecture · Multi-Backend Factory · Metadata-Driven Forms · Dynamic RBAC*

A production system for livestock management supporting **1,000+ concurrent users**.

| Capability | Implementation |
|---|---|
| **Multi-Backend Strategy** | Build-time configured, runtime-resolved selection: Firebase / PostgreSQL / Spring Boot via Factory Pattern |
| **Metadata-Driven UI** | Dynamic engine renders 90+ forms from schema definitions — one component handles all field types |
| **RBAC System** | Granular, real-time permission control; governs route access and UI visibility |
| **Pagination Engine** | Generic, reusable module handling 10,000+ records with lazy loading and cross-module search |
| **SOLID at Scale** | Every principle documented with trade-offs: S (isolated UseCases), O (Repository pattern), L (swappable backends), I (module-specific contracts), D (injected abstractions) |

**Stack:** Riverpod · Dio · GoRouter · Firebase · PostgreSQL · Spring Boot · Hive · Flutter Secure Storage

---

### 🍽️ [FoodExpo — Cross-Platform Restaurant Kiosk](https://github.com/ReturajProshad/professional-summary/blob/main/FoodExpo.md)
> *Cross-Platform · POS Hardware Integration · Platform Abstraction Layer*

A kiosk ordering system deployed on both **Windows and Android** from a single codebase with platform-specific hardware integrations.

- **POS Printing:** Platform-abstracted interface with Win32 API (Windows) and ESC/POS Bluetooth/USB (Android) implementations
- **Kiosk UX:** Touch-optimized UI with QR invoice scanning, table booking, and full cart management
- **Architecture:** Feature-first modular structure with a clean platform abstraction layer per OS

**Stack:** Riverpod · GoRouter · Dio · Method Channels · Win32 API · ESC/POS

---

### 📘 [Shimana — Multi-Module Enterprise Application](https://github.com/ReturajProshad/professional-summary/blob/main/SHIMANA.md)
> *Large-Scale Modular Architecture · Tri-Lingual · Spring Boot · Border Compliance*

A feature-rich enterprise application supporting border compliance workflows, with full **tri-lingual support** (Bengali 🇧🇩 · English 🇬🇧 · French 🇫🇷).

- **Advanced PDF Viewer:** Disk-based memory-efficient loading, dynamic QR overlay, table of contents drawer, direct page jump
- **Document Library:** Lazy loading + pagination with advanced multi-field filtering
- **JWT Token Flow:** Access + refresh token separation with automatic interceptor-based renewal

**Stack:** Riverpod · GoRouter · Dio · Spring Boot · Flutter Intl · Hive · Flutter Secure Storage

---

## 📦 Open Source

### rj_form_engine — Schema-Driven Form Engine
`pub.dev` | `GitHub`

- Engineered a production-grade form engine that renders complex, validated forms from a JSON schema, cutting UI boilerplate by **90%** across multiple enterprise systems
- Built a comprehensive test suite — widget tests for conditional visibility, unit tests for cascading dependency resolution and input masking
- Architected a metadata-driven pipeline supporting **13+ field types** with automatic parent-child dependency tracking and async data loading for multi-step workflows
- Developed a validation library with **25+ composable rules** and a state-management-agnostic `FormController` compatible with Provider, Riverpod, Bloc, and GetX

---

## 🔬 Assessment & Independent Projects

### 🎓 [EZTrainz — Offline-First Language Learning Platform](https://github.com/ReturajProshad/EZTrainz-Task)
> *Full-stack technical assessment, built end-to-end in 24 hours*

- **Backend:** Spring Boot modular monolith — 6 domain modules (Auth, Course, Quiz, Progress, Leaderboard, Sync), JWT auth, PostgreSQL + Flyway migrations
- **Mobile:** Flutter with Clean Architecture, Riverpod, Isar-backed offline sync queue
- **Core challenge:** Offline-first conflict resolution — Last-Write-Wins with UTC-normalized timestamps across client and server, avoiding timezone-drift bugs in sync comparisons
- Used AI coding assistants to accelerate scaffolding while independently owning architecture decisions, verification, and documentation (design decisions, API docs, sync strategy) across 19+ incremental commits

**Stack:** Java 17 · Spring Boot · PostgreSQL · Flyway · Flutter · Riverpod · Isar · GoRouter

---

### 🛒 [ZaviMart — E-Commerce Architecture Case Study](https://github.com/ReturajProshad/zaviMart)
> *Built as a technical assessment — every decision documented with rationale and trade-offs*

- Clean Architecture per feature: `domain → data → presentation`
- `AsyncNotifierProvider.family` — independent tab state, cached, zero cross-tab side effects
- `NestedScrollView` + `SliverOverlapAbsorber/Injector` — unified scroll contract with collapsible header, resolving a complex scroll-architecture conflict
- JWT auth with AES-encrypted secure storage
- Functional error handling (`dartz` Either) across all layers

**Stack:** `flutter_riverpod` · `dio` · `go_router` · `flutter_secure_storage` · `cached_network_image` · `dartz` · `equatable`

---

### 📱 [CodeHorse — Educational App](https://play.google.com/store/apps/details?id=com.rayhans.codehorse&hl=en&pli=1) &nbsp; ![Downloads](https://img.shields.io/badge/Play_Store-50K%2B_Downloads-34A853?style=flat&logo=google-play)
> **50,000+ downloads · 4.3★ rating** — sole developer, full-stack: Firebase Firestore · AdMob monetization · FCM push notifications · Node.js backend

---

### Other Projects

| Project | Description | Stack |
|---|---|---|
| [🔧 Spring Boot + Next.js ToDo](https://github.com/ReturajProshad/Spring-boot-Next-ts-todo) | Full-stack CRUD app — Spring Boot REST backend + Next.js/TypeScript frontend | Spring Boot · Next.js · TypeScript |
| [📚 Virtual Bookshelf](https://github.com/ReturajProshad/virtual-bookshelf-management--Returaj-Proshad-Shornocar--DB-Batch-11) | Node.js REST API + Oracle DB with triggers, stored procedures, schema normalization | Node.js · Oracle · PL/SQL |
| [🛒 E-Commerce](https://github.com/ReturajProshad/E-Commerce-Project) | Products · Carts · Payment | GetX · REST API |
| [💬 Chat App](https://github.com/ReturajProshad/Chatt_firebase) | Real-time messaging with media sharing | Provider · Firebase Auth · Firestore |
| [🗂️ Task Manager](https://github.com/ReturajProshad/TaskManagerWithApi) | Full CRUD with REST API | Flutter · REST API |
| [🌦️ Weather App](https://github.com/ReturajProshad/weather_app_assignment) | Live weather data integration | REST API |
| [📍 Location Tracker](https://github.com/ReturajProshad/map_app_project) | GPS tracking with Google Maps | Google Maps SDK |

---

## 🎮 Game Development (Independent Exploration)

### 🪙 Coin Catcher 2D — Unity Game
> *Personal project — built to explore game development outside my usual mobile/backend stack*

A 2D collectible-style game built in **Unity** with **C#** scripting, including custom sprites and game assets designed in **Adobe Illustrator**. Documented the full build process as a tutorial series on my YouTube channel.

- Built core gameplay mechanics (movement, collision/trigger-based coin collection, scoring) using Unity's component system and C# scripting
- Designed original 2D sprites and visual assets in Adobe Illustrator, covering both art and implementation
- Recorded and published the development process as an educational tutorial, teaching the same concepts to others

📺 Tutorial series: [YouTube — @developyourself6841](https://www.youtube.com/channel/UClKnDnqQY9zj7G4e7FkJWQA)
*(Source code is currently private; game not yet published to a store)*

**Stack:** Unity · C# · Adobe Illustrator

---

## 🛠️ Tech Stack

<p align="left">
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="java" width="40" height="40"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/spring/spring-original.svg" alt="spring" width="40" height="40"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original.svg" alt="nodejs" width="40" height="40"/>
  <img src="https://www.vectorlogo.zone/logos/flutterio/flutterio-icon.svg" alt="flutter" width="40" height="40"/>
  <img src="https://www.vectorlogo.zone/logos/dartlang/dartlang-icon.svg" alt="dart" width="40" height="40"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nextjs/nextjs-original.svg" alt="nextjs" width="40" height="40"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original.svg" alt="postgresql" width="40" height="40"/>
  <img src="https://www.vectorlogo.zone/logos/firebase/firebase-icon.svg" alt="firebase" width="40" height="40"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/android/android-original-wordmark.svg" alt="android" width="40" height="40"/>
  <img src="https://www.vectorlogo.zone/logos/getpostman/getpostman-icon.svg" alt="postman" width="40" height="40"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/cplusplus/cplusplus-original.svg" alt="cplusplus" width="40" height="40"/>
  <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/figma/figma-original.svg" alt="figma" width="40" height="40"/>
</p>

**Backend & APIs:** Spring Boot · JPA/Hibernate · Node.js · Express · RESTful APIs · JWT Auth · Firebase Cloud Functions
**Mobile & Frontend:** Flutter · Riverpod · Next.js · React
**Architecture:** Clean Architecture · SOLID Principles · Modular & Feature-Based Structure · Dependency Injection · Multi-Backend Abstraction
**Native & Platform:** Platform Channels · Method Channels · Win32 API · ESC/POS Thermal Printing
**Databases:** PostgreSQL · Oracle · Firebase Firestore · Hive · SQLite
**Systems Concepts:** RBAC · Offline-First Architecture · Caching (SWR/TTL/LRU) · Conflict Resolution (LWW, OT, CRDTs) · Performance Optimization
**Testing & Tooling:** Unit/Widget Testing · Git · GitHub Actions (CI/CD) · GitLab · Postman · Figma

---

## 🏆 Achievements

```
🥇  Play Store — CodeHorse: 50K+ Downloads, 4.3★ Rating
🏅  ICPC 2021 Regional Contestant (Asia Dhaka Regional)
🔢  1,100+ Problems Solved:
      Codeforces (Max Rating 1235 | 890+ solved)
      LeetCode (60+) · Beecrowd (157+)
🎓  Top Performer — Ostad Flutter Development Program, Batch 3
      Assignment 96.7% | Quiz 95% | Live Test 100%
🔬  Thesis — NeuroTransMir: Transformer-based miRNA-gene interaction prediction (ROC-AUC + F1)
```

---

## 📊 GitHub Stats & Trophies

<p align="center">
  <img src="https://github-readme-stats-fast.vercel.app/api?username=ReturajProshad&show_icons=true&theme=tokyonight&include_all_commits=true" alt="GitHub Stats"/>
  <img src="https://github-readme-stats-fast.vercel.app/api/top-langs/?username=ReturajProshad&layout=compact&theme=tokyonight" alt="Top Languages"/>
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=ReturajProshad&theme=tokyonight&hide_border=true" alt="GitHub Streak"/>
</p>

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=ReturajProshad&theme=tokyonight&no-frame=true&row=1&column=5" alt="Trophies"/>
</p>

---

## 🤝 Let's Connect

<p align="left">
  <a href="mailto:returajsumon0808@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white"/>
  </a>
  <a href="https://www.linkedin.com/in/returaj-proshad" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
  <a href="https://fb.com/returaj.sumon.1" target="_blank">
    <img src="https://img.shields.io/badge/Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white"/>
  </a>
  <a href="https://codeforces.com/profile/returaj0808" target="_blank">
    <img src="https://img.shields.io/badge/Codeforces-1F8ACB?style=for-the-badge&logo=codeforces&logoColor=white"/>
  </a>
  <a href="https://leetcode.com/u/returajsumon0808/" target="_blank">
    <img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=white"/>
  </a>
  <a href="https://www.youtube.com/channel/UClKnDnqQY9zj7G4e7FkJWQA" target="_blank">
    <img src="https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white"/>
  </a>
</p>

**Contact:** returajsumon0808@gmail.com · +8801608517866

---

<p align="center">
  <i>"I don't just build features — I build systems that survive the next hire, the next requirement, and the next scale."</i>
</p>
