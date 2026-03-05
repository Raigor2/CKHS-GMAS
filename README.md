# CKHS GMAS Performance Dashboard

**Cross Keys High School · Georgia Milestones EOC · Winter Administration 2025**

A standalone, interactive data dashboard for disaggregating student performance on the Georgia Milestones Assessment System (GMAS) End-of-Course (EOC) exams. Built as a single-file SPA deployable via GitHub Pages — no build step, no backend, no dependencies to install.

---

## 🔗 Live Dashboard

**[View Dashboard →](https://YOUR-USERNAME.github.io/CKHS_GMAS)**

---

## 📊 Content Areas

| Course | Teachers | Total Students | Status |
|---|---|---|---|
| Biology | Jenkins, Koehnke, Nieves, Robbins, Tonn | 202 | ✅ Live |
| US History | Bogan, Elswick, Holcomb, Owen-Robinson | 142 | ✅ Live |
| Algebra I | — | — | 🔄 Pending |

---

## 🧭 Dashboard Features

### Three interactive tabs per content area:

**📊 Dashboard**
- KPI cards — Total Students, Proficiency Rate, CCRPI Performance, Gap to 70% Target
- Performance Band Distribution (Beginning / Developing / Proficient / Distinguished)
- Proficiency Breakdown donut gauge
- CCRPI by Teacher bar chart with 70% target line
- Teacher Detail table — clickable rows to drill into individual teacher data

**⚡ Band Comparison**
- Four individual charts, one per performance band
- Teachers sorted ascending (lowest → highest) within each band
- Instantly identifies which teachers have the highest concentration of students at each level

**🎯 Achievement Targets**
- CCRPI Achievement Score 2025 by subgroup
- 3% Growth Target and Projected 2026 score
- Subgroups: All Students, Black, Economically Disadvantaged, English Learners, Hispanic, Students With Disability, and others

---

## 🚀 Deployment

This dashboard is a **single `index.html` file**. No npm, no Node.js, no build process.

### To deploy on GitHub Pages:

1. Fork or clone this repository
2. Go to **Settings → Pages**
3. Set Source to **Deploy from branch → main → / (root)**
4. Your dashboard will be live at `https://YOUR-USERNAME.github.io/CKHS_GMAS`

### To add the school logo:

Place a file named `ckhs-logo.png` in the root of the repository alongside `index.html`. The dashboard will automatically display it in the top-left corner.

---

## 📁 File Structure

```
CKHS_GMAS/
├── index.html        ← Full dashboard (single file)
├── ckhs-logo.png     ← School logo (add your own)
├── README.md         ← This file
└── LICENSE           ← MIT License
```

---

## 🔢 Performance Level Definitions

| Band | Score Range | CCRPI Weight |
|---|---|---|
| Beginning | 0 – 67 | 0 pts |
| Developing | 68 – 79 | 0.5 pts |
| Proficient | 80 – 91 | 1.0 pt |
| Distinguished | 92 – 100 | 1.5 pts |

**Proficiency benchmark:** Students scoring Proficient or Distinguished count toward the proficiency rate. District target: **70%**.

---

## 🛠 Built With

- Vanilla HTML / CSS / JavaScript — zero frameworks
- [Chart.js 4.4.1](https://www.chartjs.org/) — data visualization
- [Google Fonts — Outfit + JetBrains Mono](https://fonts.google.com/)

---

## 📄 License

MIT License · © 2026 **Derikson Rivera-Rios**

Permission is hereby granted, free of charge, to any person obtaining a copy of this software to use, copy, modify, and distribute it, subject to the conditions of the MIT License included in this repository.

---

*Cross Keys High School · DeKalb County School District · Georgia*
