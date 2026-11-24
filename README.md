<h1 align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=26&pause=1000&color=0E75B6&center=true&vCenter=true&width=820&lines=Hi%2C+I'm+Returaj+Proshad+Shornocar+%F0%9F%91%8B;Flutter+Engineer+%C2%B7+Android+%C2%B7+iOS+%C2%B7+Windows;Spring+Boot+Microservices+on+the+backend;Clean+Architecture+%C2%B7+Offline-First+%C2%B7+RBAC" alt="Typing SVG" />
</h1>

<p align="center">
  <b>Flutter engineer first. Comfortable on the Spring Boot side too.</b><br/>
  I build enterprise cross-platform apps and the architecture underneath them: multi-backend data layers, offline sync, role-based access, and native hardware integration.
</p>

<p align="center">
  <a href="mailto:returajsumon0808@gmail.com"><img src="https://img.shields.io/badge/Email-Contact_me-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
  <a href="https://www.linkedin.com/in/returaj-proshad"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <img src="https://komarev.com/ghpvc/?username=returajproshad&label=Profile+Views&color=0e75b6&style=for-the-badge" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Flutter-Primary_Focus-02569B?style=for-the-badge&logo=flutter&logoColor=white" />
  <img src="https://img.shields.io/badge/Spring_Boot-Backend-6DB33F?style=for-the-badge&logo=springboot&logoColor=white" />
  <img src="https://img.shields.io/badge/Platforms-Android_%7C_iOS_%7C_Windows-0E75B6?style=for-the-badge" />
  <a href="https://pub.dev/packages/rj_form_engine"><img src="https://img.shields.io/badge/pub.dev-rj__form__engine-0175C2?style=for-the-badge&logo=dart&logoColor=white" /></a>
  <img src="https://img.shields.io/badge/Play_Store-50K%2B_Downloads-34A853?style=for-the-badge&logo=google-play&logoColor=white" />
</p>

---

## 🧑‍💻 About Me

I'm a **Flutter & Mobile Software Engineer**, hands-on with Flutter since **2023** and working full-time professionally since **April 2025**. At **One Direction Companies Limited (ODCL)** I'm the **sole Flutter developer** across **three concurrent enterprise systems**: an agricultural ERP, a Windows/Android POS kiosk, and an enterprise document management app.

I'm not a one-stack specialist. Flutter is where I go deepest, but I also work on the **Spring Boot microservices** behind our in-house products at ODCL (Eureka, API Gateway, PostgreSQL), and I build Spring Boot backends on my own too (JWT auth, Flyway, modular monoliths). I like problems that cross the boundary between client and server: how data syncs offline, how permissions flow from the API into the UI, and how one codebase can talk to several backends without the UI knowing.

```text
🎯 Focus        Flutter (Android · iOS · Windows) + Spring Boot backends
🏢 Now          Flutter & Mobile Software Engineer @ ODCL (Apr 2025 – present)
📦 Open Source  rj_form_engine: schema-driven Flutter form engine on pub.dev
📱 Shipped      Amar Babu (live on Play Store) · CodeHorse (50K+ downloads, 4.3★)
🏆 Problem      1,100+ problems solved · ICPC 2021 Asia Dhaka Regional contestant
   Solving
🎓 Education    B.Sc. CSE, Islamic University, Bangladesh (CGPA 3.63/4.00)
```

---

## ⚡ What I Bring

<table>
<tr>
<td width="50%" valign="top">

### 📱 Flutter (primary)
- Enterprise apps on **Android, iOS and Windows** from one codebase
- **Riverpod**, Provider, **GoRouter**, deep linking, Material 3 & Cupertino
- **Clean Architecture**, SOLID, feature-first modules, DI, Repository pattern
- **Offline-first**: Hive/SQLite caching (SWR/TTL), LWW + OR-Set CRDT sync
- **Native integration**: Method Channels (Kotlin/Java), Win32 API, Dart FFI, ESC/POS printers
- Performance work with **Flutter DevTools**, Sliver lazy loading, Crashlytics
- Release management: **Google Play**, iOS via **TestFlight**, Windows kiosk updates via **GitHub Actions**

</td>
<td width="50%" valign="top">

### ☕ Spring Boot (strong second)
- **Microservices** with Spring Boot, **Eureka** service discovery and an **API Gateway** (in-house ODCL systems)
- Scaffolded **7 services** for Agrotech; built administrative-area management (country, district/zilla, union and more) for Shimana
- **REST APIs** with Java 17 and Spring Boot
- **Modular monolith** design with clear domain modules
- **JWT authentication** and role-based access control
- **PostgreSQL** with **Flyway** migrations
- Server-side **sync and conflict resolution** for offline-first clients
- Typed API contracts shared cleanly between Flutter and Spring Boot
- Also: Node.js/Express, Firebase Cloud Functions, Oracle PL/SQL

</td>
</tr>
</table>

---

## 💼 Experience

### 🏢 One Direction Companies Limited (ODCL) · Flutter & Mobile Software Engineer
`Apr 2025 – Present` · Dhaka, Bangladesh

Sole Flutter developer, plus Spring Boot microservices work, across **3 concurrent in-house enterprise systems**: **Agrotech** (livestock management ERP), **FoodExpo** (self-service POS kiosk) and **Shimana** (enterprise document management).

- 🏗️ **Multi-backend architecture:** built a Bootstrap Factory so the same Flutter codebase runs against **Firebase Firestore, direct PostgreSQL, or a Spring Boot API**, chosen at build time, with the UI and domain layers unchanged
- 🔐 **App infrastructure:** centralized GoRouter navigation, **JWT auth and dynamic RBAC** standardized across **30+ modules**
- 🔄 **Offline-first data layer:** Hive caching with SWR/TTL strategies; **Last-Write-Wins** for single-owner fields and an **OR-Set CRDT** for concurrently edited collections
- 🧾 **Schema-driven form engine:** renders complex forms from JSON config, cutting form work from hours to minutes; later open-sourced as **rj_form_engine**
- 📄 **Pagination & search framework:** powers **30+ list views** with type-safe filtering and lazy loading over **10,000+ record** datasets
- 🖨️ **Cross-platform POS kiosk** (Windows & Android) with native **Win32 APIs** and **ESC/POS thermal printers** via Method Channels
- ☕ **Spring Boot microservices:** scaffolded **7 services** for Agrotech and built the administrative-area management service (country, district/zilla, union and more) for Shimana, on **Eureka**, an **API Gateway** and **PostgreSQL**
- 🔗 **API contracts:** strongly typed request/response models in Flutter, aligned with the Spring Boot services for reliable serialization
- 🔔 **Smart Alert engine** on FCM notifying farm staff of vaccination schedules, AI due dates, calving windows and missed heat detection
- ⚡ **Performance:** Sliver lazy loading and tighter Riverpod subscriptions to cut unnecessary rebuilds on heavy list and dashboard screens, verified in DevTools
- 🌍 **i18n:** full English, Bangla and French localization (intl + ARB) in Agrotech and Shimana
- 🚀 **Releases:** Android to Google Play, iOS builds via TestFlight, and a **GitHub Actions** pipeline that builds and delivers Windows kiosk updates
- 📚 **Documentation & onboarding:** architecture guides, API references and handover docs; onboarded and mentored a newly joined Flutter developer

### 🧳 Kensink Labs · Flutter Developer (Contract)
`Mar 2025 – Apr 2025` · Remote

- Delivered an **AI-driven itinerary timeline** for the Sootcase travel app, turning Figma designs into production Material 3 Flutter UI and integrating REST APIs under a tight deadline

### 📰 Brainwave Matrix Solutions · Mobile Developer Intern
`Sep 2024 – Oct 2024` · Remote

- Built a responsive Flutter news app consuming REST APIs with Provider state management

---

## 🚀 Featured Work at ODCL

### 🐄 [Agrotech (Smart Gowala / Khabani) · Livestock Management ERP](https://github.com/ReturajProshad/professional-summary/blob/main/SmartGowala%20(KHABANI).md)
> *Clean Architecture · Multi-Backend Factory · Schema-Driven Forms · Dynamic RBAC · Offline-First*

| Capability | Implementation |
|---|---|
| **Multi-Backend Strategy** | Firebase / PostgreSQL / Spring Boot selected at build time through a Factory, UI and domain untouched |
| **Schema-Driven UI** | One engine renders complex forms from JSON definitions instead of hand-built screens |
| **RBAC** | Role and module-level permissions controlling route access and UI visibility |
| **Pagination Engine** | Reusable, type-safe lazy loading and search over 10,000+ records |
| **Offline Sync** | Hive caching with SWR/TTL, LWW and OR-Set CRDT conflict resolution |
| **Smart Alerts** | FCM notifications for vaccinations, AI due dates, calving windows, missed heats |
| **Backend** | Spring Boot microservices (7 services scaffolded by me) behind Eureka and an API Gateway |

**Stack:** Flutter · Riverpod · Dio · GoRouter · Firebase · Hive · Flutter Secure Storage · intl · Spring Boot microservices · Eureka · API Gateway · PostgreSQL

### 🍽️ [FoodExpo · Cross-Platform Restaurant Kiosk](https://github.com/ReturajProshad/professional-summary/blob/main/FoodExpo.md)
> *Windows + Android from one codebase · POS hardware · Platform abstraction*

- **Printing:** one interface, two implementations: Win32 API on Windows, ESC/POS over Bluetooth/USB on Android
- **Kiosk UX:** touch-first ordering, QR invoice scanning, table booking and full cart flow
- **Delivery:** Windows kiosk updates built and shipped automatically with GitHub Actions

**Stack:** Flutter · Riverpod · GoRouter · Dio · Method Channels · Win32 API · ESC/POS · GitHub Actions

### 📘 [Shimana · Enterprise Document Management](https://github.com/ReturajProshad/professional-summary/blob/main/SHIMANA.md)
> *Large modular app · Tri-lingual (Bangla · English · French) · Spring Boot microservices*

- **PDF viewer:** disk-based, memory-efficient loading with QR overlay, table of contents and page jump
- **Document library:** lazy loading, pagination and multi-field filtering
- **Auth:** access/refresh token split with automatic interceptor-based renewal
- **Backend:** built the Spring Boot service for administrative-area management (country, district/zilla, union and more), registered with Eureka behind an API Gateway

**Stack:** Flutter · Riverpod · GoRouter · Dio · intl · Hive · Flutter Secure Storage · Spring Boot · Eureka · API Gateway · PostgreSQL

---

## 📦 Open Source

### [rj_form_engine](https://pub.dev/packages/rj_form_engine) · Schema-Driven Flutter Form Engine
[![pub package](https://img.shields.io/pub/v/rj_form_engine.svg?logo=dart)](https://pub.dev/packages/rj_form_engine)

Extracted from the form system I built at work, so any Flutter app can render validated, multi-step forms from JSON.

- **13+ field types** with automatic parent-child dependency tracking and async data loading
- **25+ composable validation rules**
- **12-column responsive grid** (LayoutBuilder, row packing, breakpoint-aware `RjSpan`: full/half/third/quarter) for phone, tablet and desktop
- State-management-agnostic **`FormController`** that works with Provider, Riverpod, Bloc and GetX
- Covered by **widget and unit tests** for conditional rendering, cascading dependencies and input masking

---

## 📱 Shipped Apps

### 🤰 [Amar Babu · Pregnancy Companion & Baby Game App](https://play.google.com/store/apps/details?id=com.returaj.amarBabu)
`Live on Google Play · Solo project`

A Bangla-first Flutter app I designed, built and shipped on my own.

- Riverpod, GoRouter and feature-first Clean Architecture; **offline-first SQLite** with **12 backward-compatible schema migrations**, Firebase Auth, cloud backup, EN/BN localization
- Interactive talking baby plus **6 Flame mini-games** with Forge2D physics; tuned the game loop with scalar collision math, pre-rasterized emoji rendering, resource reuse and adaptive physics sub-stepping
- AdMob rewarded/banner ads with UMP consent, Firestore-configured ad units, Crashlytics, and a **127-test automated suite**

**Stack:** Flutter · Riverpod · GoRouter · SQLite · Flame · Forge2D · Firebase · AdMob

### 📚 [CodeHorse · Educational App](https://play.google.com/store/apps/details?id=com.rayhans.codehorse) &nbsp; ![Downloads](https://img.shields.io/badge/Play_Store-50K%2B_Downloads-34A853?style=flat&logo=google-play)
`50K+ downloads · 4.3★`

I was the sole Flutter developer. The app is published under a friend's developer account, with my credit inside the app.

- Firebase Firestore, FCM push notifications through a Node.js + Firebase backend, AdMob monetization, Provider state management

---

## 🔬 Full-Stack & Assessment Projects

### 🎓 [EZTrainz · Offline-First Language Learning Platform](https://github.com/ReturajProshad/EZTrainz-Task)
> *Spring Boot + Flutter, built end-to-end in 24 hours as a technical assessment*

- **Backend:** Spring Boot modular monolith with 6 domain modules (Auth, Course, Quiz, Progress, Leaderboard, Sync), JWT auth, PostgreSQL + Flyway
- **Mobile:** Flutter, Clean Architecture, Riverpod, Isar-backed offline sync queue
- **Core problem:** Last-Write-Wins conflict resolution with UTC-normalized timestamps on both client and server, avoiding timezone-drift bugs
- Used AI assistants for scaffolding while owning the architecture, verification and docs (design decisions, API docs, sync strategy) across 19+ incremental commits

**Stack:** Java 17 · Spring Boot · PostgreSQL · Flyway · Flutter · Riverpod · Isar · GoRouter

### 🛒 [ZaviMart · E-Commerce Architecture Case Study](https://github.com/ReturajProshad/zaviMart)
> *Technical assessment with every decision documented, including trade-offs*

- Clean Architecture per feature (`domain → data → presentation`), functional error handling with `dartz` Either
- `AsyncNotifierProvider.family` for independent, cached tab state
- `NestedScrollView` + `SliverOverlapAbsorber/Injector` to solve a collapsible-header scroll conflict
- JWT auth with AES-encrypted secure storage

**Stack:** Flutter · Riverpod · Dio · GoRouter · flutter_secure_storage · dartz · equatable

<details>
<summary><h3>More projects</h3></summary>
<br/>

| Project | Description | Stack |
|---|---|---|
| [🔧 Spring Boot + Next.js ToDo](https://github.com/ReturajProshad/Spring-boot-Next-ts-todo) | Full-stack CRUD with a Spring Boot REST backend and Next.js/TypeScript frontend | Spring Boot · Next.js · TypeScript |
| [📚 Virtual Bookshelf](https://github.com/ReturajProshad/virtual-bookshelf-management--Returaj-Proshad-Shornocar--DB-Batch-11) | Node.js REST API on Oracle with triggers, stored procedures and normalized schema | Node.js · Oracle · PL/SQL |
| [🛒 E-Commerce](https://github.com/ReturajProshad/E-Commerce-Project) | Products, carts and payment | Flutter · GetX · REST API |
| [💬 Chat App](https://github.com/ReturajProshad/Chatt_firebase) | Real-time messaging with media sharing | Flutter · Provider · Firebase |
| [🗂️ Task Manager](https://github.com/ReturajProshad/TaskManagerWithApi) | Full CRUD against a REST API | Flutter · REST API |
| [🌦️ Weather App](https://github.com/ReturajProshad/weather_app_assignment) | Live weather data | Flutter · REST API |
| [📍 Location Tracker](https://github.com/ReturajProshad/map_app_project) | GPS tracking on Google Maps | Flutter · Google Maps SDK |
| 🪙 Coin Catcher 2D | Unity/C# game with my own Illustrator sprites; build process taught as a [YouTube tutorial series](https://www.youtube.com/channel/UClKnDnqQY9zj7G4e7FkJWQA) (source private) | Unity · C# · Illustrator |

</details>

---

## 🛠️ Tech Stack

<p align="left">
  <img src="https://skillicons.dev/icons?i=flutter,dart,kotlin,java,spring,postgres,firebase,sqlite,nodejs,nextjs,ts,cpp,python,githubactions,git,gitlab,androidstudio,vscode,postman,figma&perline=10" alt="Tech stack icons" />
</p>

| Area | Tools |
|---|---|
| **Languages** | Dart · Kotlin · Java · C/C++ · Python |
| **Flutter** | Riverpod · Provider · GoRouter · Deep Linking · Material 3 & Cupertino · Animations · Async/Streams · Flame |
| **Backend & APIs** | Spring Boot · Microservices · Eureka · API Gateway · REST · JWT · WebSockets · Flyway · Node.js/Express · Firebase (Auth, Firestore, Realtime DB, Cloud Functions, FCM, Crashlytics) |
| **Architecture** | Clean Architecture · SOLID · Multi-Backend Abstraction · Feature-First Modules · DI · Repository Pattern · RBAC |
| **Data & Offline** | PostgreSQL · Hive · SQLite · Isar · Oracle · SWR/TTL/LRU caching · LWW & CRDT conflict resolution |
| **Native & Platform** | Android SDK · Platform/Method Channels (Kotlin/Java) · Win32 API · Dart FFI · ESC/POS · QR |
| **Quality & Delivery** | Unit & Widget Testing · Flutter DevTools · GitHub Actions · Play Store · TestFlight |
| **Tools** | Git · GitLab · Postman · Figma · Android Studio · VS Code · Claude Code · GitHub Copilot |
| **Familiar with** | Bloc · GetX · Next.js · Unity |

---

## 🏆 Achievements

```text
🧠  1,100+ problems solved
      Codeforces: max rating 1235, 890+ solved
      LeetCode 60+ · Beecrowd 157+
🏅  ICPC 2021 Regional contestant (Asia Dhaka Regional)
🎓  Top performer, Ostad Flutter Development Program, Batch 3 (2023)
      Assignment 96.7% · Quiz 95% · Live Test 100%
🔬  Thesis: NeuroTransMir, transformer-based miRNA-gene interaction prediction (ROC-AUC, F1)
```

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats-fast.vercel.app/api?username=ReturajProshad&show_icons=true&theme=tokyonight&include_all_commits=true&hide_border=true" alt="GitHub Stats" height="165"/>
  <img src="https://github-readme-stats-fast.vercel.app/api/top-langs/?username=ReturajProshad&layout=compact&theme=tokyonight&hide_border=true" alt="Top Languages" height="165"/>
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=ReturajProshad&theme=tokyonight&hide_border=true" alt="GitHub Streak"/>
</p>

---

## 🤝 Let's Connect

<p align="left">
  <a href="mailto:returajsumon0808@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
  <a href="https://www.linkedin.com/in/returaj-proshad" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="https://pub.dev/packages/rj_form_engine" target="_blank"><img src="https://img.shields.io/badge/pub.dev-0175C2?style=for-the-badge&logo=dart&logoColor=white"/></a>
  <a href="https://codeforces.com/profile/returaj0808" target="_blank"><img src="https://img.shields.io/badge/Codeforces-1F8ACB?style=for-the-badge&logo=codeforces&logoColor=white"/></a>
  <a href="https://leetcode.com/u/returajsumon0808/" target="_blank"><img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=white"/></a>
  <a href="https://www.youtube.com/channel/UClKnDnqQY9zj7G4e7FkJWQA" target="_blank"><img src="https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white"/></a>
  <a href="https://fb.com/returaj.sumon.1" target="_blank"><img src="https://img.shields.io/badge/Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white"/></a>
</p>

📍 Dhaka, Bangladesh · 📧 returajsumon0808@gmail.com

---

<p align="center">
  <i>"I build Flutter apps with the architecture to survive the next hire, the next requirement, and the next scale."</i>
</p>
