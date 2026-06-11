# ⚽ FIFA World Cup 2026 Prediction Championship

A cinematic, real-time tracking dashboard for department and organization tournament prediction competitions. Built as a self-contained single-page web app with a dynamic glassmorphic interface, custom graph analytics, and live database streaming.

![Championship Arena](https://img.shields.io/badge/FIFA_World_Cup-2026-blue?style=for-the-badge&logo=soccer&logoColor=white)
![Firebase Live](https://img.shields.io/badge/Cloud_Database-Firestore_Live-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)
![SheetJS Core](https://img.shields.io/badge/Excel_Engine-SheetJS-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)

---

## ✨ Features

* **🎭 Cinematic Visual Wall:** Immersive user environment utilizing high-fidelity sports portrait panels running smooth variable panning animations.
* **⚡ Real-Time Cloud Synchronization:** Powered by Firebase Firestore. When the administrator inputs actual results or drops new profiles, updates propagate across all screens instantly without a page refresh.
* **📊 Standings Analytics:** Features an interactive Top-3 Podium generator alongside dynamic performance graphs mapping competitor distributions.
* **📁 Smart Dropzone Ingestion:** Integrates **SheetJS** client-side parsing engines to scan multiple standard structural `.xlsx` predictions simultaneously.
* **🛡️ Hardened Security Core:** No plain-text passwords or secret keys are stored within the codebase. Operator credential profiles are isolated and handled natively inside cloud rules.

---

## 📐 Scoring System Logic

The score validation engine computes participant data arrays across three structural criteria:

| Evaluation Phase | Prediction Condition | Points Awarded |
| :--- | :--- | :--- |
| **Group Stage** | Match Outcome Correct (Win / Loss / Draw) | `+1 Pt` |
| **Group Stage** | Match Score Correct (Exact Goal Matrix Match) | `+2 Pts` |
| **Group Standings** | Predicting Top 2 Qualified Teams (per Group) | `+1 Pt` |
| **Knockout Bracket** | Core Score Metric Correct (90-min Full Time) | `+2 Pts` |
| **Knockout Bracket** | Team Advancement Verified (R16, QF, SF, Final) | `Variable` |
| **World Champion** | Final Tournament Champion Match | `+10 Pts` |

---
