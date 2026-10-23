# ArtisanTerra — Multi-Vendor D2C Marketplace App (Axlero UI/UX Project 1)

![Project Status](https://img.shields.io/badge/Status-Final_Submission-2E7D5B?style=for-the-badge)
![WCAG Compliance](https://img.shields.io/badge/Accessibility-WCAG_2.1_AA_Verified-C86D51?style=for-the-badge)
![Design System](https://img.shields.io/badge/Figma-100%25_Auto--Layout_%26_Variables-1E242B?style=for-the-badge)

## 1. Executive Summary & Problem Statement
The rapid growth of Direct-to-Consumer (D2C) artisan brands requires unified digital marketplace infrastructure. Traditional e-commerce templates struggle to maintain visual harmony when shoppers browse across dozens of independent sellers, while vendors face overly complex inventory tools.

**ArtisanTerra** is a mobile-first Multi-Vendor Marketplace application engineered under the **Axlero UI/UX Design Internship PRD**. It delivers:
1. **Consumer Storefront**: A warm, unified alabaster-and-terracotta visual language (`#F9F6F0` / `#C86D51`) that frames diverse seller photography cohesively and reduces checkout friction to **3 screens maximum** (*Product Detail -> Cart Drawer -> Order Summary & Payment*).
2. **Vendor Dashboard**: A high-contrast mobile seller portal featuring real-time revenue/order analytics, low-stock alerts, and a 1-tap **Add Product** publishing workflow.

---

## 2. Standardized 7-Page Figma File Architecture
Per the Axlero Universal Architectural Directives, the Figma source file and the accompanying interactive viewer (`index.html`) strictly follow the mandated 7-page structure:

| Page Name | Deliverable Scope & Implementation Details | Status |
| :--- | :--- | :--- |
| `01_Cover` | Project thumbnail, title, intern/team metadata, and status badge (`Final`). | ✅ Complete |
| `02_Research & Flows` | 2 distinct User Personas (*The Shopper* & *The Vendor*), user journey mapping, and full Information Architecture (IA). | ✅ Complete |
| `03_Wireframes` | Low-fidelity grayscale structural layouts (zero imagery) for Consumer Flow and Vendor Dashboard. | ✅ Complete |
| `04_Design System` | Local color variables, typography scale, 8pt spacing tokens, and Auto-Layout interactive variants (Buttons, Inputs, Cards). | ✅ Complete |
| `05_High-Fidelity UI` | Pixel-perfect mobile screens (393x852 iPhone 16 Pro) with 100% Auto-Layout and verified WCAG 2.1 AA contrast ratios. | ✅ Complete |
| `06_Prototype` | Interactive user flows with Smart Animate micro-interactions (heart favorite toggle, 3-step checkout drawer). | ✅ Complete |
| `07_Developer Handoff` | 8pt grid redlines, spacing annotations, CSS variables, and exportable SVG asset containers. | ✅ Complete |

---

## 3. Figma Version History Audit Log (Named Checkpoints)
In compliance with Axlero's weekly tracking protocol (`Cmd+Option+S` / `Ctrl+Alt+S`), the Figma file contains the four mandatory Named Versions (kept under 25 characters with <140 char descriptions):

| Week | Date Window | Named Version Title | Version Description (<140 chars) |
| :--- | :--- | :--- | :--- |
| **Week 1** | 8th – 15th | `[Week 1] UX & Wireframes` | Created Shopper & Vendor personas, IA hierarchy, and low-fi grayscale wireframes for core flows. |
| **Week 2** | 16th – 22nd | `[Week 2] Design System` | Built 04_Design System with local color/type variables, 8pt tokens, and Auto-Layout variants. |
| **Week 3** | 23rd – 29th | `[Week 3] Hi-Fi Screens` | Converted wireframes into WCAG AA compliant Hi-Fi Consumer & Vendor screens using Auto-Layout. |
| **Week 4** | 30th – 6th | `[Week 4] Prototype & Dev` | Linked 3-step checkout prototype with Smart Animate and added 8pt grid redlines for handoff. |

---

## 4. Repository Directory Structure
```text
├── README.md                          # Master PRD overview & version history log
├── WORK_DISTRIBUTION.md               # Mandatory Team Work Distribution & Branch Allocation
├── index.html                         # Live Interactive Prototype + All 7 Figma Deliverable Pages
├── docs/
│   ├── 01_Cover_and_Brief.md          # Project cover metadata & KPI targets
│   ├── 02_Research_and_Flows.md       # User Personas, Empathy Map & IA diagram
│   ├── 03_Wireframes_Specs.md         # Grayscale wireframe structural specifications
│   ├── 07_Developer_Handoff.md        # 8pt grid redlines, WCAG audit & HM presentation script
│   └── GITHUB_COMMIT_SCHEDULE.md      # 10-day Mid Review & 20-day Final Review commit tracker
├── tokens/
│   ├── design_tokens.json             # W3C Design Tokens (Colors, Typography, 8pt Spacing)
│   └── variables.css                  # CSS Custom Properties for engineering handoff
└── assets/icons/                      # Exported vector SVG icons from 04_Design System
```

## 5. How to Run the Live Interactive Prototype (`index.html`)
Open `index.html` in any modern web browser to inspect:
- **Live Interactive Storefront & Seller Portal (`06_Prototype`)**: Filter products by category, trigger the animated favorite heart micro-interaction, view the Product Detail Page (PDP), complete the **3-Step Checkout Flow**, or switch to the **Seller Dashboard** to add new inventory items live.
- **All 7 Axlero Figma Pages**: Use the top navigation tabs to switch between `01_Cover`, `02_Research & Flows`, `03_Wireframes`, `04_Design System`, `05_High-Fidelity UI`, `06_Prototype`, and `07_Developer Handoff`.
- **8pt Redline Grid & Mobile Frame Toggle**: Toggle between responsive web view and a **393px Mobile Frame** or overlay the **8pt Developer Redline Grid** at any time.
