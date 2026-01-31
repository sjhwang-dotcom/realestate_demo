# Agentic Real Estate Intelligence

An AI-powered dashboard for institutional multifamily real estate asset management, built by [DeepAuto.ai](https://deepauto.ai).

![Dashboard Preview](https://img.shields.io/badge/Status-Demo-blue) ![License](https://img.shields.io/badge/License-Proprietary-red)

## 🏢 Overview

This platform provides institutional-grade analytics for multifamily property portfolios, featuring:

- **Asset Management Dashboard** - Financial statements, rent rolls, and aged receivables
- **Lumina AI** - Context-aware AI assistant with multi-turn conversation
- **Data Lakehouse** - Unified data layer for property analytics
- **Tool Studio** - Extensible tooling for code, software integrations, and visualizations

## ✨ Key Features

### 📊 Asset Management
- T-12 Financial Statements with NOI analysis
- Rent Roll with unit-level details
- Aged Receivables tracking (0-30, 31-60, 61-90, 90+ days)
- Property-level KPIs: Occupancy, Bad Debt, Loss-to-Lease

### 🤖 Lumina AI Assistant
- Context-aware responses based on current view
- Multi-turn conversation with portfolio data
- Inline visualizations (charts, tables, trend analysis)
- Natural language querying of property metrics

### 🛠️ Tool Studio
- **Code Tools**: NOI Margin, DSCR, Cap Rate, Cash-on-Cash, IRR, Equity Multiple
- **Software Tools**: CoStar API, Yardi Voyager, RealPage Analytics, SQL Query Engine, Python Executor
- **Visualization Tools**: Line, Bar, Pie, Heatmap, Waterfall, Radar, Treemap charts

### 📈 Portfolio Analytics
- Fund-level performance comparison (Fund I vs Fund II)
- YoY occupancy and rent growth trends
- Distribution waterfall analysis
- IRR and equity multiple tracking

## 🚀 Quick Start

```bash
# Clone the repository
git clone https://github.com/YOUR_USERNAME/agentic-real-estate.git
cd agentic-real-estate

# Serve locally (no build required)
python3 -m http.server 8000

# Open in browser
open http://localhost:8000
```

## 📁 Project Structure

```
├── index.html          # Main dashboard
├── lumina.html         # Lumina AI workspace
├── lakehouse.html      # Data Lakehouse view
├── tools.html          # Tool Studio
├── logo.png            # DeepAuto logo
└── data/
    ├── properties.json     # Property portfolio data
    ├── loans.json          # Loan/debt data
    ├── portfolio.json      # Portfolio summary
    ├── monthly.json        # Monthly performance
    ├── receivables.json    # Aged receivables
    ├── rental-summary.json # Rent roll summary
    └── tools.json          # Tool definitions
```

## 🌐 Deployment

### Vercel (Recommended)
1. Push to GitHub
2. Import project in [Vercel](https://vercel.com)
3. Framework Preset: `Other`
4. Build Command: (leave empty)
5. Output Directory: `.`
6. Deploy!

### Netlify
1. Push to GitHub
2. Connect in [Netlify](https://netlify.com)
3. Build Command: (leave empty)
4. Publish Directory: `.`
5. Deploy!

## 🎨 Tech Stack

- **Frontend**: Vanilla HTML/CSS/JavaScript
- **Styling**: Tailwind CSS (via CDN)
- **Charts**: Chart.js
- **Icons**: Heroicons (inline SVG)
- **Fonts**: Inter (Google Fonts)

## 📄 License

Proprietary - © 2024 DeepAuto.ai. All rights reserved.

---

Built with ❤️ by [DeepAuto.ai](https://deepauto.ai) - Agentic AI for Enterprise
