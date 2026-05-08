# Category Crusher — SharkNinja Hackathon

A product decision engine that turns consumer signals into ranked, actionable priorities. Built for the SharkNinja Vacuum category, April 2026.

> "Not an analysis tool. A decision engine."

## What it does

Aggregates Amazon reviews, social media trends, and patent data across competing products, then surfaces prioritised recommendations — not just data.

- **Market overview** — share, new entrants, US vs global
- **Competitive intel** — feature matrix, price/rating, complaint rates by competitor
- **Consumer voice** — pros/cons ranked by sales impact, not volume
- **Market signals** — TikTok/Reddit/YouTube trends + patent activity
- **Opportunity** — all signals synthesised into a ranked action plan with urgency windows

## Files

| File | Description |
|------|-------------|
| `index.html` | Overview dashboard with sidebar navigation |
| `sharkninja_all_tabs_white.html` | Full detail view — all 5 tabs per product |

## Stack

Plain HTML/CSS/JS — no build step. Charts via [Chart.js 4.4](https://www.chartjs.org/).

## Running locally

```bash
open [index.html](https://kiteta.github.io/sharkninja-categories-crush/)
```

No server required. Open either file directly in a browser.

## Data Scraped

- 10,432 Amazon, Bestbuy, Walmart reviews(Shark IQ Robot + 4 competitors)
- Social trends: TikTok, Reddit, YouTube
- Patent filings: 2026 Q1

Every number traces back to a source review.
