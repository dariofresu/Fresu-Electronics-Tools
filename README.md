# Fresu Electronics — Tools

Interactive engineering tools by **Dario Fresu**, Principal EMC Architect at Fresu Electronics.

Live at: **[tool.fresuelectronics.com](https://tool.fresuelectronics.com)**

---

## Repository Structure

```
/                          ← Hub landing page (tool.fresuelectronics.com)
├── index.html             ← Tools hub — all tools listed
│
├── pcb-mistakes/          ← tool.fresuelectronics.com/pcb-mistakes/
│   └── index.html         ← Top 10 PCB Design Mistakes for EMI Control
│
├── hardware-spec/         ← tool.fresuelectronics.com/hardware-spec/
│   └── index.html         ← Hardware Specification Guide
│
├── emc-fundamentals/      ← tool.fresuelectronics.com/emc-fundamentals/
│   └── index.html         ← EMC Fundamentals interactive module
│
├── pcb-em-fields/         ← tool.fresuelectronics.com/pcb-em-fields/
│   └── index.html         ← PCB EM Fields visualiser
│
├── pcb-emc-design-kit/    ← tool.fresuelectronics.com/pcb-emc-design-kit/
│   └── index.html         ← PCB EMC Design Kit
│
├── pcb-signal-propagation/← tool.fresuelectronics.com/pcb-signal-propagation/
│   └── index.html         ← Signal Propagation Visualiser
│
└── images/                ← Shared figures (PCB Mistakes guide)
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

A structured interactive worksheet for defining hardware product specs before opening a schematic tool. Covers Product Vision, Technical Requirements, Architecture & Interfaces, and Compliance & Risk.

Features: 4-Step Worksheet · Confidence Star Ratings · Notes per Item · Auto-Save (localStorage) · Export Product Specification Brief (TXT)

---

### 3. PCB Signal Propagation Visualiser
**URL:** [tool.fresuelectronics.com/pcb-signal-propagation/](https://tool.fresuelectronics.com/pcb-signal-propagation/)

Animated visualisation of how signals travel through a PCB transmission line — wavefront, displacement current, E and H fields, live impedance matching.

---

### 4. PCB EM Fields
**URL:** [tool.fresuelectronics.com/pcb-em-fields/](https://tool.fresuelectronics.com/pcb-em-fields/)

---

### 5. EMC Fundamentals
**URL:** [tool.fresuelectronics.com/emc-fundamentals/](https://tool.fresuelectronics.com/emc-fundamentals/)

---

### 6. PCB EMC Design Kit
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
