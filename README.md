# Fresu Electronics — Tools

Interactive engineering tools by **Dario Fresu**, Principal EMC Architect at Fresu Electronics.

Live at: **[tool.fresuelectronics.com](https://tool.fresuelectronics.com)**

---

## Repository Structure

```
/                              ← Hub landing page (tool.fresuelectronics.com)
├── index.html                 ← Tools hub — all tools listed
│
├── pcb-mistakes/              ← tool.fresuelectronics.com/pcb-mistakes/
│   └── index.html
│
├── hardware-spec/             ← tool.fresuelectronics.com/hardware-spec/
│   └── index.html
│
├── pre-layout-checklist/      ← tool.fresuelectronics.com/pre-layout-checklist/
│   └── index.html
│
├── emc-fundamentals/          ← tool.fresuelectronics.com/emc-fundamentals/
│   └── index.html
│
├── pcb-em-fields/             ← tool.fresuelectronics.com/pcb-em-fields/
│   └── index.html
│
├── pcb-emc-design-kit/        ← tool.fresuelectronics.com/pcb-emc-design-kit/
│   └── index.html
│
├── pcb-signal-propagation/    ← tool.fresuelectronics.com/pcb-signal-propagation/
│   └── index.html
│
└── images/                    ← Shared figures (PCB Mistakes guide)
    └── fig-01.jpg … fig-22.jpg, portrait.jpg
```

---

## Tools

### 1. Top 10 PCB Design Mistakes for EMI Control
**URL:** [tool.fresuelectronics.com/pcb-mistakes/](https://tool.fresuelectronics.com/pcb-mistakes/)

The complete interactive guide. 10 chapters covering the most common PCB layout mistakes that cause EMC test failures — with chapter quizzes, self-audit tool, roadmap, printable checklist, and a certification exam.

Features: Reader · Chapter Quizzes · Self-Audit · Roadmap · Key Insights Gallery · Printable Checklist · Certification Exam · Dark/Light Mode

---

### 2. Hardware Specification Guide
**URL:** [tool.fresuelectronics.com/hardware-spec/](https://tool.fresuelectronics.com/hardware-spec/)

5-step interactive spec capture tool for defining hardware product requirements before opening a schematic tool. Covers Product Vision, Technical Requirements, EMC by Design, Architecture & Interfaces, and Compliance & Risk.

Features: 5-Step Worksheet · Gate Reviews · Confidence Star Ratings · Live Brief Preview · Risk Register · PDF Export · Save Offline

---

### 3. Pre-Layout Review Checklist
**URL:** [tool.fresuelectronics.com/pre-layout-checklist/](https://tool.fresuelectronics.com/pre-layout-checklist/)

9-category, 50+ item checklist covering schematic organisation, signal integrity, protection, compliance, and layout readiness. Complete before the first trace is placed.

Features: 9 Categories · 50+ Items · Notes per Item · Export Progress Report · Print to PDF · Auto-Save

---

### 4. PCB Signal Propagation Visualiser
**URL:** [tool.fresuelectronics.com/pcb-signal-propagation/](https://tool.fresuelectronics.com/pcb-signal-propagation/)

Animated visualisation of how signals travel through a PCB transmission line — wavefront, displacement current, E and H fields, live impedance matching.

---

### 5. PCB EM Fields
**URL:** [tool.fresuelectronics.com/pcb-em-fields/](https://tool.fresuelectronics.com/pcb-em-fields/)

---

### 6. EMC Fundamentals
**URL:** [tool.fresuelectronics.com/emc-fundamentals/](https://tool.fresuelectronics.com/emc-fundamentals/)

---

### 7. PCB EMC Design Kit
**URL:** [tool.fresuelectronics.com/pcb-emc-design-kit/](https://tool.fresuelectronics.com/pcb-emc-design-kit/)

---

## Deployment

- **Hosting:** GitHub Pages (public repo)
- **Domain:** `tool.fresuelectronics.com` → CNAME → `dariofresu.github.io`
- **Push to deploy:** Changes pushed to `main` go live within 1–2 minutes automatically.
- **No build step.** All tools are self-contained HTML files.

## Development

Each tool is a single self-contained `index.html` — no framework, no bundler, no dependencies beyond Google Fonts.
To work on a tool locally: open the `index.html` in any browser. No server required.

---

## Legal

© 2026 Fresu Electronics SRL — All rights reserved  
[fresuelectronics.com](https://fresuelectronics.com)
