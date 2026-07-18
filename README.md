# 🌐 Climate Adaptation Finance Flows Dashboard

Interactive web dashboard tracking global climate adaptation finance — green bonds, adaptation funds, loss & damage commitments vs. actual disbursements, mapped to need.

**Live**: [hheuristics.com/climate-adaptation-finance-flows](https://hheuristics.com/climate-adaptation-finance-flows) _(via GitHub Pages)_

---

## 📊 Features

- **6 interactive tabs** — Overview, Green Bonds, Adaptation Finance, Loss & Damage, Finance Gap, Data Explorer
- **D3.js Sankey diagram** — Visualize climate finance flows from source to destination
- **Chart.js charts** — Animated line, bar, doughnut, and multi-axis charts
- **KPI counter animations** — Key metrics animate on load
- **Sortable data explorer** — Filter and sort the full dataset
- **Fixed-position web app layout** — Like a desktop application, with Excel-style tab navigation
- **Dark theme** — Professional climate-finance color system with teal/green accents

## 📁 Project Structure

```
├── index.html              # Single-file self-contained dashboard
├── .github/workflows/
│   └── pages.yml           # GitHub Pages deployment workflow
└── README.md
```

## 📈 Data Sources

Data is based on realistic estimates from:
- **Climate Policy Initiative** — Global Landscape of Climate Finance 2024
- **OECD** — Climate Finance Provided and Mobilised
- **UNFCCC** — Standing Committee on Finance reports
- **Climate Bonds Initiative** — Green Bond Market data
- **UNEP** — Adaptation Gap Report 2024
- **Munich Re / Swiss Re** — Climate disaster loss data

## 🚀 Deploy

This is deployed via **GitHub Pages** using the Actions workflow in `.github/workflows/pages.yml`. Push to `main` to trigger deployment.

---

Built by **H Heuristics** © 2025
