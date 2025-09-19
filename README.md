# LOS — Logistical Operating System (Showcase)

A modular field-ops tracker evolving from a spreadsheet prototype into a polished web app.
This repo is a **public showcase**: sanitized docs, visuals, and high-level progress.  
The private codebase remains closed while we shape the MVP.

---

## 🧭 What is LOS?
LOS helps teams track daily field activity (clients, visits, notes) with a **spreadsheet-like grid**, **LOA counters**, and a **territory workflow**. The MVP focuses on a fast grid UX, clear metrics, and simple admin controls—without requiring custom scripts or developer intervention.

> This showcase shares the **look & feel** and **direction** only. Implementation details, business logic, and internal docs stay private by design.

---

## 🎨 Theme & UX Highlights
- **Grid-first Workspace** (default): address/unit, client, phone, timestamps, notes, visit #, and LOA toggles (K, D, C, DM, P, $, NiNp, V).  
- **Tabs:** Grid • Map • LOA • History (Map loads only when opened; LOA shows summary cards & trends).  
- **Color coding:** fast visual status (e.g., Contacted, Presented, Sold) with a high-contrast dark theme.  
- **Mobile:** card-based list with an edit drawer; full-screen map with a bottom sheet.

See `/docs/public/screenshots/` for the latest desktop & mobile mockups.

---

## 🧱 Tech Overview (high level)
- **Frontend:** Next.js (TypeScript), Tailwind, shadcn/ui, Apollo Client  
- **Backend:** FastAPI, Strawberry GraphQL, Beanie (MongoDB)  
- **Auth:** JWT (access/refresh), RBAC  
- **Monorepo:** private main repo (code) + this public showcase (docs & images)

> We intentionally omit environment/config, schemas, and internal scripts here.

---

## 🚧 Progress (light changelog)
- **Week 4:** Auth refresh baseline; dashboard & workspace mockups aligned to final theme  
- **Week 3:** GraphQL mutations for client/visit; seeds & tests groundwork  
- **Week 2:** Core models outlined; initial schema & routes (private)  
- **Week 1:** Repo scaffolding; CI/compose planning; theme exploration

A fuller changelog exists privately; this list mirrors only the public-safe highlights.

---

## 📸 Screenshots
- Desktop workspace (grid-first)
- Desktop dashboard (cards)
- Mobile dashboard
- Mobile workspace

> Find them under `docs/public/screenshots/`.

---

## 🔒 What’s intentionally not here
- Source code, internal prompts/agent logs, monetization/licensing strategy details, data models, migrations, or any proprietary spreadsheets.  
- If you’re evaluating LOS for your team, reach out for a private demo.

---

## 🔔 Follow Along
I post weekly build logs & milestone demos on LinkedIn. Feedback is welcome!

**Contact:** Alex Marrero • (GitHub @Amarrero0215)

---

## 🪪 License (showcase only)
Text and images in this showcase are licensed **CC BY-NC-ND 4.0**.  
No commercial use or derivatives. The LOS name and related marks are reserved.  
See `LICENSE` in this repo.
