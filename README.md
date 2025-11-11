<!--
  Premium Profile README for: bajrangsolge
  Notes:
  - All images are from public badge/card services; no local assets needed.
  - Mermaid diagrams render natively on GitHub.
  - Replace any links (LinkedIn/Portfolio) if you want later.
-->

<h1 align="center">Hi, I'm Bajrang Solge</h1>
<p align="center">
  <b>Android Automotive OS (AAOS) • HMI & Framework • React / React Native • Flutter • MERN / Laravel • GenAI & RAG</b>
  <br/>
  <a href="https://github.com/bajrangsolge?tab=followers"><img src="https://img.shields.io/github/followers/bajrangsolge?style=for-the-badge&label=Followers"></a>
  <img src="https://komarev.com/ghpvc/?username=bajrangsolge&style=for-the-badge&label=Profile%20views" />
  <a href="mailto:bs.bajrangsolge@gmail.com"><img src="https://img.shields.io/badge/Email-bs.bajrangsolge%40gmail.com-blue?style=for-the-badge&logo=gmail&logoColor=white"></a>
  <a href="https://github.com/bajrangsolge"><img src="https://img.shields.io/badge/GitHub-bajrangsolge-black?style=for-the-badge&logo=github"></a>
</p>

---

## 🔥 What I Do

- **Android Automotive OS (AAOS):** CarService, Vehicle HAL, CarPropertyManager, power/UX restrictions, JNI/HAL glue, cluster/IVI apps (Kotlin/Java).
- **Android & Cross-Platform:** React Native and Flutter apps; modern UI with Compose/Views and material motion.
- **Full-Stack:** MERN & Laravel + MySQL/MongoDB; JWT/OAuth, admin dashboards, reporting, CI/CD.
- **GenAI & RAG:** Document ingestion, chunking/embeddings, FGAC/ACL-aware retrieval, Prompt-flow style orchestration.

> Currently: building an **IVI/cluster** demo (AAOS), a **recruitment/ATS** suite with dashboards, and a **skincare e-commerce** (MERN + React Native).

---

## 🧰 Tech I use (selection)

<p>
  <img src="https://img.shields.io/badge/Android-3DDC84?logo=android&logoColor=white&style=for-the-badge" />
  <img src="https://img.shields.io/badge/Android%20Automotive-2025-blue?style=for-the-badge&logo=androidauto&logoColor=white" />
  <img src="https://img.shields.io/badge/Kotlin-7F52FF?logo=kotlin&logoColor=white&style=for-the-badge" />
  <img src="https://img.shields.io/badge/Java-007396?logo=java&logoColor=white&style=for-the-badge" />
  <img src="https://img.shields.io/badge/React-20232a?logo=react&logoColor=61DAFB&style=for-the-badge" />
  <img src="https://img.shields.io/badge/React%20Native-20232a?logo=react&logoColor=61DAFB&style=for-the-badge" />
  <img src="https://img.shields.io/badge/Flutter-02569B?logo=flutter&logoColor=white&style=for-the-badge" />
  <img src="https://img.shields.io/badge/Laravel-FF2D20?logo=laravel&logoColor=white&style=for-the-badge" />
  <img src="https://img.shields.io/badge/Node.js-43853D?logo=node.js&logoColor=white&style=for-the-badge" />
  <img src="https://img.shields.io/badge/Express-000?logo=express&logoColor=white&style=for-the-badge" />
  <img src="https://img.shields.io/badge/MongoDB-4ea94b?logo=mongodb&logoColor=white&style=for-the-badge" />
  <img src="https://img.shields.io/badge/PostgreSQL-316192?logo=postgresql&logoColor=white&style=for-the-badge" />
  <img src="https://img.shields.io/badge/AWS-232F3E?logo=amazonaws&logoColor=white&style=for-the-badge" />
</p>

---

## 🏗️ Architecture Snapshots

### AAOS (Vehicle → HAL → CarService → App)
```mermaid
flowchart LR
  CAN[(CAN Bus)] --> MCU[ECU / MCU]
  MCU -->|USB Serial| ESP[ESP32]
  ESP -->|Telemetry| ANDROID[Android Device]

  subgraph ANDROID_SIDE[Android (AAOS)]
    HAL[Vehicle HAL (AIDL)]
    CS[CarService / Vehicle System Service]
    CPM[CarPropertyManager]
    APP[IVI / Cluster App (Kotlin)]
    UI[Compose / Views]
  end

  HAL --> CS --> CPM --> APP --> UI
