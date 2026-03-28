<div align="center">

# 🤖 AI Freelance Automation

[![Python](https://img.shields.io/badge/Python-3.12-blue?logo=python)](https://python.org)
[![SQLite](https://img.shields.io/badge/SQLite-Database-green?logo=sqlite)](https://sqlite.org)
[![BrowserOS](https://img.shields.io/badge/BrowserOS-CDP-purple)](https://browseros.com)

**Automated freelance prospection — Scan, score, apply, engage. All AI-powered.**

</div>

## How It Works

```mermaid
graph TB
    subgraph Scan
        S1[Codeur.com every 30min]
        S2[LinkedIn every 4h]
    end
    subgraph Score
        F1[Keyword Match]
        F2[Budget Filter]
        F3[AI Scoring 0-100]
    end
    subgraph Act
        A1[Auto-Apply via CDP]
        A2[LinkedIn Comments]
        A3[Telegram Alerts]
    end
    S1 --> F1 --> F3 --> A1
    S2 --> A2
    F3 --> A3
```

## Results (March 2026)

| Metric | Value |
|--------|-------|
| Offers posted | 6 |
| Total value | 9,900 EUR |
| LinkedIn actions | 5 |
| Workflow runs | 9+ |

## Scripts

| Script | Purpose |
|--------|---------|
| `codeur-veille.py` | Scan & score projects |
| `publish.py` | Post to LinkedIn/GitHub |
| `cdp.py` | 33-function CDP wrapper |
| `comet_cluster.py` | Distributed AI engine |
| `db_sync.py` | SQLite persistence |

## Author

**Franck Delmas** — [GitHub](https://github.com/Turbo31150) · [Portfolio](https://turbo31150.github.io/franckdelmas.dev/)
