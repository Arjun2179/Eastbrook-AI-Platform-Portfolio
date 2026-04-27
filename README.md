# Eastbrook Youth AI Well-Being — Portfolio

A premium static portfolio for the **Eastbrook Youth AI Well-Being** research project and platform.

## 🌐 Live Links

| Resource | URL |
|----------|-----|
| Portfolio | Open `index.html` in a browser |
| Live App | [eastbrook-ai-platform.vercel.app](https://eastbrook-ai-platform.vercel.app/) |
| AS-IS Dashboard | [easterbook-youth-ai-dashboard.vercel.app](https://easterbook-youth-ai-dashboard.vercel.app/) |
| Comparison View | [eastbrook-ai-platform.vercel.app/compare](https://eastbrook-ai-platform.vercel.app/compare) |
| GitHub | [github.com/Arjun2179/Easterbook-Youth-AI-Dashboard](https://github.com/Arjun2179/Easterbook-Youth-AI-Dashboard) |

## 📋 Project Overview

Eastbrook Youth AI Well-Being is a research-led case study on how generative AI affects student verification habits, physical strain, and educator intervention timing.

### Verified Key Metrics

| Metric | AS-IS Baseline | TO-BE Modeled |
|--------|----------------|---------------|
| Students | 400 | 400 |
| Total observations | 12,000 | 12,000 |
| Dataset fields | 34 | 34 |
| Daily AI prompts | 14,119 | 11,871 |
| Verification rate | 56.0% | 66.7% |
| Automation bias | 44.0% | 33.3% |
| Screen time | 8.6 hrs/day | 7.8 hrs/day |
| Eye dryness | 7.1/10 | 6.3/10 |
| Neck pain | 5.9/10 | 5.3/10 |
| Nudge success | — | 25.6% |

## 👥 Team

| Member | Role |
|--------|------|
| Tejaswini Vuppalapati | Project Manager |
| Pavani Suthram | Business Analyst |
| Vardhan Sreepurushothama | Data Analyst |
| Vinay | Technical Lead |
| Arjun Penmatsa | Documentation Lead |

## 🛠️ Tech Stack

- **Portfolio:** HTML, CSS, JavaScript
- **Frontend UI:** React 19 + TypeScript, Vite, React Router DOM v7
- **Backend API:** Node.js REST API with Express.js
- **Analytics Engine:** Python processing for the synthetic dataset pipeline
- **Database:** Neon PostgreSQL
- **Visualisation & UI Libraries:** Recharts, Lucide React Icons
- **Deployment:** Vercel Cloud, Edge CDN, Serverless Functions
- **Security:** JWT role-based auth, Helmet.js, CORS, express-rate-limit, bcryptjs, environment variables

## 🏗️ Architecture Highlights

- **Business Architecture:** Student AI behavior tracking, verification monitoring, wellness monitoring, educator risk intervention, policy/compliance analysis, analyst KPI reporting
- **IS Architecture:** React UI, Node.js REST API, Python analytics engine, Neon PostgreSQL, role-based routing, visualisation libraries
- **Tech Architecture:** Vercel hosting, SPA routing, serverless functions, security middleware, and environment-based deployment configuration
- **Operational Contracts:** Core tables include `profiles`, `student_day_metrics`, `student_sessions`, `training_modules`, `training_progress`, `risk_alerts`, `nudges`, and `educator_student_map`

## 📁 Portfolio Structure

```text
Portfolio/
├── index.html
├── styles.css
├── script.js
├── vercel.json
├── README.md
└── images/
    ├── image.png
    ├── chart-setup.png
    ├── chart-verification.png
    ├── chart-strain.png
    ├── solution-architecture.png
    └── erd.png
```

## ✨ Portfolio Features

- Responsive one-page layout
- Sticky navigation and smooth scrolling
- Animated counters and scroll-reveal effects
- Updated architecture, ERD, and dashboard evidence sections
- Static Vercel deployment with no build step

## 🚀 How to View

1. Open `index.html` in any modern browser.
2. Or deploy the folder to Vercel using the included `vercel.json`.

## 📄 License

This portfolio is for educational and demonstration purposes.
