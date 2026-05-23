# HCM OBS Post-Refresh Manager

> **Oracle Fusion HCM — Post-Refresh Cockpit**  
> Built by [HeyCloud4ERP](https://heycloud4erp.com) for the Orange Business Services Oracle Fusion implementation.

---

## 🚀 Live Demo

**▶ [Launch the Demo](https://heycloudai.github.io/HCMCockpit/HCM_OBS_Cockpit_DEMO.html)**

> Demo mode runs entirely in your browser — no backend, no credentials required.  
> Data is fictitious and pre-loaded for illustration purposes.

---

## 📦 What's Inside

| File | Description |
|------|-------------|
| `HCM_OBS_Cockpit.html` | Full production cockpit (connect your own Fusion PODs) |
| `HCM_OBS_Cockpit_DEMO.html` | Demo version with fictitious pre-loaded data |

---

## 🧩 Modules

| # | Module | Description |
|---|--------|-------------|
| ⚙️ | **PODs & Connexions** | Configure Oracle Fusion environments (PROD, DEV, TEST…) |
| 1.1 | **NOMAIL** | Post-refresh email anonymisation — generates HDL `.dat` files |
| 1.2 | **Reset Password** | Bulk password reset across multiple PODs via REST API or HDL |
| 1.3 | **BI URLs** | Scan and fix PROD URLs embedded in BIP/OTBI reports |
| 3 | **Profils & DAS** | Security matrix — Business Profiles, Functional Roles, Oracle App Roles |
| 4 | **Matrice Reports** | BIP/OTBI report access mapping by profile and functional role |

---

## 🔒 Security

- All credentials are stored **in-memory only** (never sent to any third-party server)
- REST API calls go directly from your browser to your Oracle Fusion tenant
- Zero external dependencies for core functionality (CDN only for Excel export)

---

## 🏗️ Tech Stack

- **Pure HTML/JS** — single-file application, no build step
- [ExcelJS](https://github.com/exceljs/exceljs) — Excel export
- [SheetJS/xlsx](https://sheetjs.com/) — Excel import
- [FileSaver.js](https://github.com/eligrey/FileSaver.js/) — file download

---

## 📬 Contact

Interested in deploying this for your Oracle Fusion programme?  
→ [heycloud4erp.com](https://heycloud4erp.com/#contact-form)
