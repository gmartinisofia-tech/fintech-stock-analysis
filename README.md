# fintech-stock-analysis

> A working portfolio of equity research, financial modeling, and market analysis built publicly while I develop my skills as an analyst.

[![Python](https://img.shields.io/badge/python-3.11+-blue.svg)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/jupyter-notebook-orange.svg)](https://jupyter.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Last Commit](https://img.shields.io/github/last-commit/YOUR_USERNAME/fintech-stock-analysis)](https://github.com/YOUR_USERNAME/fintech-stock-analysis)

---

## About This Repository

I'm a sophomore at Emmanuel College double-majoring in Economics and Finance, with a minor in Computer Science. I serve as the **Technology Sector Head** for the Colleges of the Fenway Investment Group (COFIG), where I lead research on public tech equities.

This repository is essentially where that research lives. Every company write-up, every script, every valuation model here represents how I actually think about markets. It's not polished marketing, but it's the analytical work I'm doing as I grow.

**What you'll find here:**
- Company-level equity research reports with investment theses
- Python-based tools for pulling, cleaning, and analyzing market data
- Valuation models (DCF, comparables, ratio analysis)
- Sector-level market commentary, with a focus on technology
- Reproducible Jupyter notebooks documenting every analytical decision

---

## Current Focus

**Version 1 (in progress):** Technology sector — building the analytical foundation
- First company deep-dive: *[Company name — to be selected from watchlist]*
- Python toolkit for historical price data, returns, and basic ratios
- Comparable company analysis template

See the [roadmap](./docs/ROADMAP.md) for what's coming next.

---

## Repository Structure

```
fintech-stock-analysis/
│
├── README.md                    ← You are here
├── requirements.txt             ← Python dependencies
├── LICENSE
│
├── companies/                   ← One folder per company analyzed
│   ├── template/                ← Standard analysis template
│   └── [TICKER]/                ← e.g., MSFT/, NVDA/, CRWD/
│       ├── thesis.md            ← Investment thesis (the point of view)
│       ├── analysis.ipynb       ← Notebook with financials and charts
│       └── model.xlsx           ← Valuation model (optional)
│
├── notebooks/                   ← Exploratory and cross-company analysis
│   ├── 01_sector_overview.ipynb
│   ├── 02_returns_analysis.ipynb
│   └── 03_ratio_comparison.ipynb
│
├── src/                         ← Reusable Python modules
│   ├── data_loader.py           ← Pulls from yfinance, FRED, etc.
│   ├── ratios.py                ← Financial ratio calculations
│   ├── valuation.py             ← DCF, comparables helpers
│   └── visualization.py         ← Plotting utilities
│
├── data/                        ← Cached datasets (gitignored if large)
│   └── README.md                ← Describes data sources
│
├── reports/                     ← Polished PDF/markdown reports
│
└── docs/                        ← Methodology, roadmap, glossary
    ├── METHODOLOGY.md
    ├── ROADMAP.md
    └── GLOSSARY.md
```

---

## Getting Started

```bash
# Clone the repo
git clone https://github.com/YOUR_USERNAME/fintech-stock-analysis.git
cd fintech-stock-analysis

# Set up a virtual environment
python -m venv venv
source venv/bin/activate       # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Launch Jupyter
jupyter notebook
```

---

## Methods

Every company analysis in this repo follows a consistent framework:

1. **Business model** — how the company makes money
2. **Industry context** - competitive position
3. **Financial health** — revenue growth, margins, balance sheet, cash flow
4. **Valuation** — multiples vs. peers, DCF where needed
5. **Risks** — what would break the thesis
6. **Thesis** — a clear view with a price target or directional call

Full methodology: [docs/METHODOLOGY.md](./docs/METHODOLOGY.md)

---

## Disclaimer

This repository is an educational and professional portfolio. Nothing in it is meant to be taken as investment advice. All views are my own and don't represent the positions of Emmanuel College, COFIG, or any other organization I'm associated with. I am a student learning in public.

---

## Connect

- **LinkedIn:** [your-linkedin-url]
- **Email:** [your-email]
- **COFIG:** Colleges of the Fenway Investment Group — Technology Sector Head

If you're a recruiter, analyst, or fellow student interested in discussing any of this work, I'd love to hear from you.
