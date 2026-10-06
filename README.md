# Paloma Cordeiro — Portfolio

Software engineering portfolio focused on data-heavy products, SaaS platforms, complex backend systems and applied ML.

## Case studies

- **OpenWEC** — endurance racing data platform; 2M+ laps across five series.
- **Alphecca** — multi-tenant B2B quotation SaaS.
- **Argos** — CRM and business-domain modeling.
- **Asterism** — personal knowledge graph, ingestion and search.
- **Talos** — observability, incidents and reliability.
- **Quant-AI** — temporal ML, backtesting and risk research.

Additional work includes PLOT / Heavenverso, ml-lab and Churn Prediction.

## Stack

Astro · TypeScript · CSS

## Local development

```bash
npm install
npm run dev
```

Production check/build:

```bash
npm run build
```

## Structure

```text
src/
├── data/projects.ts       # case-study content
├── layouts/Base.astro     # shared shell/navigation/footer
├── pages/
│   ├── index.astro        # homepage
│   ├── about.astro
│   └── work/              # index + generated case pages
└── styles/global.css      # design system and responsive layout
```
