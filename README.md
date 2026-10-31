# quant-notes

Interactive study notes on systematic trading, published with GitHub Pages from the `docs/` folder.

Each note is one self-contained HTML file: no build step, no framework. Charts are drawn from simulated
series inside the page so the "true" answer is known; no market data and no performance claims.
Every note ends with the books and papers it draws on.

Live site: https://teejay772.github.io/quant-notes/

## Notes

| # | Page | Topic |
|---|---|---|
| 01 | docs/momentum.html | Time-series momentum (trend following) |
| 02 | docs/ewma.html | EWMA and volatility estimation |
| 03 | docs/backtest.html | The honest backtest |
| 04 | docs/backtester.html | The backtester, line by line (backtest.py) |
| 05 | docs/roadmap.html | Research plan: phases, weekly scope, sources, deliverables |

## Adding a note

1. Write `docs/<slug>.html` as a standalone page (doctype, head, fonts, inline style and script).
2. Add a card to `docs/index.html` and a row to the table above.
3. Add a Sources section at the end of the page: books and papers only.
4. Commit and push; Pages redeploys in about a minute.

## Setup (once)

GitHub → repository Settings → Pages → Source: "Deploy from a branch", branch `main`, folder `/docs`.
