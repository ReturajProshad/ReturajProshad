<h1 align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=26&pause=1000&color=0E75B6&center=true&vCenter=true&width=800&lines=Returaj+Proshad+Shornocar;Flutter+%26+Mobile+App+Developer;Immediately+Available+%7C+Clean+Architecture+%7C+Riverpod" alt="Typing SVG" />
</h1>

<p align="center">
  <a href="mailto:returajsumon0808@gmail.com"><img src="https://img.shields.io/badge/Email-returajsumon0808%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
  <a href="https://www.linkedin.com/in/returaj-proshad"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <img src="https://komarev.com/ghpvc/?username=returajproshad&label=Profile+Views&color=0e75b6&style=for-the-badge" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Status-Immediately_Available-success?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Flutter-Expert-02569B?style=for-the-badge&logo=flutter&logoColor=white" />
  <img src="https://img.shields.io/badge/Dart-Proficient-0175C2?style=for-the-badge&logo=dart&logoColor=white" />
  <img src="https://img.shields.io/badge/Clean_Architecture-Practitioner-00C853?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Play_Store-50K%2B_Downloads-34A853?style=for-the-badge&logo=google-play&logoColor=white" />
</p>

---

## 🧑‍💻 About Me

Flutter & Mobile Engineer with production experience since **September 2024**, having built and shipped **three concurrent enterprise-grade systems** using Clean Architecture, SOLID principles, and Riverpod-based state management.

My work spans a metadata-driven form engine (90+ dynamic forms), cross-platform native integration (Win32 + ESC/POS via Method Channels), JWT/RBAC authentication, and offline-first data synchronization using caching strategies (SWR/TTL/LRU) and conflict-resolution logic (LWW, Operational Transformation, CRDTs). I'm comfortable collaborating directly with backend teams on Spring Boot REST APIs and have contributed to Node.js services.

```
📌 Status:     Immediately Available — open to Full-time / Contract / Remote roles
📱 Published:  CodeHorse on Play Store — 50K+ Downloads, 4.3★ Rating
📦 Open Source: rj_form_engine — schema-driven Flutter form engine (pub.dev)
🏆 Competitive: ICPC 2021 Regional Contestant | 1,100+ Problems Solved
🎓 Education:  B.Sc. CSE — Islamic University, Bangladesh (CGPA: 3.63/4.00)
```

---

## 💼 Professional Experience

### 🏢 One Direction Companies Limited (ODCL) — Flutter & Mobile Developer
`Apr 2025 – Jun 2026` · Dhaka, Bangladesh

Owned Flutter development end-to-end across **3 concurrent enterprise production systems** — Smart Gowala, FoodExpo Kiosk, and Shimana — covering livestock management, self-service F&B POS kiosks, and border compliance workflows.

- Engineered a **metadata-driven form engine** dynamically rendering **90+ complex forms** from JSON configuration, cutting manual UI development effort by ~90% — later extracted into the open-source **rj_form_engine** package
- Designed a **centralized, type-safe routing & pagination framework** using GoRouter, standardizing navigation across **30+ feature modules**
- Implemented **JWT-based authentication with dynamic RBAC**, letting a single app build serve multiple user roles with granular, module-level permissions
- Built a **cross-platform POS kiosk system** (Windows & Android) integrating native Win32 APIs and ESC/POS thermal printers via Flutter Method Channels
- Improved UI performance by **30%** (measured via Flutter DevTools) through Sliver-based lazy loading and optimized Riverpod state subscriptions
- Implemented **GitHub Actions CI/CD** to automate build/deploy pipelines, including automatic Windows (KIOSK) app updates
- Partnered with backend engineers on **Spring Boot REST API** contracts and contributed to a Node.js backend covering REST endpoints and Firestore integration
- Mentored junior developers on Clean Architecture and SOLID principles through structured code reviews

### 🧳 Kensink Labs — Flutter Developer (Contract)
`Mar 2025 – Apr 2025` · Remote

- Delivered an **AI-driven itinerary timeline feature** for the Sootcase travel application, translating Figma designs into production Flutter UI and integrating REST APIs under a strict deadline

### 📰 Brainwave Matrix Solutions — Mobile Developer Intern
`Sep 2024 – Oct 2024` · Remote

- Built a responsive Flutter news application consuming REST APIs with Provider-based state management, delivered within the internship timeline

---

## 🚀 Professional Projects

> These are production systems built during my time at ODCL. Source code is confidential; architecture is documented publicly.

---

### 🐄 [Smart Gowala (Khabani) — Enterprise Livestock Management ERP](https://github.com/ReturajProshad/professional-summary/blob/main/SmartGowala%20(KHABANI).md)
> *Clean Architecture · Multi-Backend Factory · Metadata-Driven Forms · Dynamic RBAC · Riverpod*

A production Flutter ERP for livestock management supporting **1,000+ concurrent users**.

| Capability | Implementation |
|---|---|
| **Multi-Backend Strategy** | Build-time configured, runtime-resolved selection: Firebase / PostgreSQL / Spring Boot via Factory Pattern |
| **Metadata-Driven UI** | Dynamic engine renders 90+ forms from `FieldMetadata` schemas — one widget handles all field types |
| **RBAC System** | Granular, real-time permission control via `StateNotifierProvider`; controls route access and widget visibility |
| **Pagination Engine** | Generic, reusable module handling 10,000+ records with lazy loading and search across all modules |
| **SOLID at Scale** | Every principle documented with trade-offs: S (isolated UseCases), O (Repository pattern), L (swappable backends), I (module-specific contracts), D (Riverpod-injected abstractions) |

**Stack:** Riverpod · Dio · GoRouter · Firebase · PostgreSQL · Spring Boot · Hive · Flutter Secure Storage

---

### 🍽️ [FoodExpo — Cross-Platform Restaurant Kiosk](https://github.com/ReturajProshad/professional-summary/blob/main/FoodExpo.md)
> *Cross-Platform · POS Hardware Integration · Flutter Method Channels · Riverpod*

A kiosk ordering system deployed on both **Windows and Android** from a single Flutter codebase with platform-specific hardware integrations.

- **POS Printing:** Platform-abstracted `POSInterface` with Win32 API (Windows) and ESC/POS Bluetooth/USB (Android) implementations via Method Channels
- **Kiosk UX:** Touch-optimized UI with QR invoice scanning, table booking, and full cart management
- **Architecture:** Feature-first modular structure with a clean platform abstraction layer per OS

**Stack:** Riverpod · GoRouter · Dio · Flutter Method Channels · Win32 API · ESC/POS

---

### 📘 [Shimana — Multi-Module Enterprise Application](https://github.com/ReturajProshad/professional-summary/blob/main/SHIMANA.md)
> *Large-Scale Modular Architecture · Tri-Lingual · Spring Boot · Advanced PDF Handling · Border Compliance*

A feature-rich enterprise application supporting border compliance workflows, with full **tri-lingual support** (Bengali 🇧🇩 · English 🇬🇧 · French 🇫🇷).

- **Advanced PDF Viewer:** Disk-based memory-efficient loading, dynamic QR overlay on page 1, table of contents drawer, direct page jump
- **Document Library:** Lazy loading + pagination with advanced multi-field filtering
- **JWT Token Flow:** Access + refresh token separation with automatic Dio interceptor-based renewal

**Stack:** Riverpod · GoRouter · Dio · Spring Boot · Flutter Intl · Hive · Flutter Secure Storage

---

## 📦 Open Source

### rj_form_engine — Schema-Driven Flutter Form Engine
`pub.dev` | `GitHub`

- Engineered a production-grade form engine that renders complex, validated forms from JSON, cutting UI boilerplate by **90%** across multiple enterprise systems
- Built a comprehensive test suite — Widget Tests for conditional visibility, Unit Tests for cascading dependency resolution and input masking
- Architected a metadata-driven pipeline supporting **13+ field types** with automatic parent-child dependency tracking and async data loading for multi-step workflows
- Developed a validation library with **25+ composable rules** and a state-management-agnostic `FormController` compatible with Provider, Riverpod, Bloc, and GetX

---

## 🔬 Assessment & Independent Projects

### 🛒 [ZaviMart — E-Commerce Architecture Case Study](https://github.com/ReturajProshad/zaviMart)
> *Built as a technical assessment — every decision documented with rationale and trade-offs*

- Clean Architecture per feature: `domain → data → presentation`
- `AsyncNotifierProvider.family` — independent tab state, Riverpod-cached, zero cross-tab side effects
- `NestedScrollView` + `SliverOverlapAbsorber/Injector` — unified scroll contract with collapsible header, resolving a complex scroll-architecture conflict
- `PageStorageKey` per tab — scroll position preserved independently across tab switches
- JWT auth with AES-encrypted `flutter_secure_storage`
- `dartz` Either for functional error handling across all layers

**Stack:** `flutter_riverpod` · `dio` · `go_router` · `flutter_secure_storage` · `cached_network_image` · `dartz` · `equatable`

---

### 📱 [CodeHorse — Educational App](https://play.google.com/store/apps/details?id=com.rayhans.codehorse&hl=en&pli=1) &nbsp; ![Downloads](https://img.shields.io/badge/Play_Store-50K%2B_Downloads-34A853?style=flat&logo=google-play)
> **50,000+ downloads · 4.3★ rating** — sole developer. Firebase Firestore · AdMob monetization · FCM push notifications · Node.js backend · Provider state management

---

### Other Projects (older, foundational work)

| Project | Description | Stack |
|---|---|---|
| [🛒 E-Commerce](https://github.com/ReturajProshad/E-Commerce-Project) | Products · Carts · Payment | GetX · REST API |
| [💬 Chat App](https://github.com/ReturajProshad/Chatt_firebase) | Real-time messaging with media sharing | Provider · Firebase Auth · Firestore |
| [🗂️ Task Manager](https://github.com/ReturajProshad/TaskManagerWithApi) | Full CRUD with REST API | Flutter · REST API |
| [🌦️ Weather App](https://github.com/ReturajProshad/weather_app_assignment) | Live weather data integration | REST API |
| [📍 Location Tracker](https://github.com/ReturajProshad/map_app_project) | GPS tracking with Google Maps | Google Maps SDK |

---

## 🛠️ Tech Stack

<p align="left">
  <img src="https://www.vectorlogo.zone/logos/flutterio/flutterio-icon.svg" alt="flutter" width="40" height="40"/>
  <img src="https://www.vectorlogo.zone/logos/dartlang/dartlang-icon.svg" alt="dart" width="40" height="40"/>
  <img src="https://www.vectorlogo.zone/logos/firebase/firebase-icon.svg" alt="firebase" width="40" height="40"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/android/android-original-wordmark.svg" alt="android" width="40" height="40"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original.svg" alt="postgresql" width="40" height="40"/>
  <img src="https://www.vectorlogo.zone/logos/getpostman/getpostman-icon.svg" alt="postman" width="40" height="40"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="java" width="40" height="40"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/cplusplus/cplusplus-original.svg" alt="cplusplus" width="40" height="40"/>
  <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/figma/figma-original.svg" alt="figma" width="40" height="40"/>
</p>

**Mobile:** Flutter · Dart · Riverpod · Provider · GetX · GoRouter · Deep Linking · Async/Streams
**Architecture:** Clean Architecture · SOLID Principles · Modular & Feature-Based Structure · Dependency Injection
**Native & Platform:** Platform Channels · Method Channels · Win32 API · ESC/POS Thermal Printing
**Testing:** Unit Testing · Widget Testing
**Backend:** Spring Boot · Node.js · Express · REST APIs · Firebase Functions
**Databases:** PostgreSQL · Firebase Firestore · Hive · SQLite
**Tools:** Git · GitHub Actions (CI/CD) · GitLab · Postman · VS Code · Android Studio · Figma
**Concepts:** Performance Optimization · RBAC · Offline-First Architecture · Caching (SWR/TTL/LRU) · Conflict Resolution (LWW, OT, CRDTs)

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
  <img src="https://github-readme-stats.vercel.app/api?username=ReturajProshad&show_icons=true&theme=tokyonight&include_all_commits=true" alt="GitHub Stats"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=ReturajProshad&layout=compact&theme=tokyonight" alt="Top Languages"/>
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.demolab.com?user=ReturajProshad&theme=tokyonight&hide_border=true" alt="GitHub Streak"/>
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

**📌 Immediately Available for:** Full-time · Contract · Remote — Mid to Senior Flutter roles
**Contact:** returajsumon0808@gmail.com · +8801608517866

---

<p align="center">
  <i>"I don't just build features — I build systems that survive the next hire, the next requirement, and the next scale."</i>
</p>
