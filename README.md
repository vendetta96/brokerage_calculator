# Brokerage Cost Calculator — Equity Delivery

Interactive calculator comparing annual brokerage costs for Indian stock brokers: **Dhan**, **Zerodha**, and **Groww**.

## Live Demo

[https://vendetta96.github.io/brokerage_calculator/](https://vendetta96.github.io/brokerage_calculator/)

## Features

- Real-time cost comparison with interactive sliders
- Dynamic ranking — cheapest broker highlighted automatically
- Stacked bar chart (Chart.js) showing cost breakdown
- Dark/Light theme toggle with saved preference
- Info tooltips explaining each parameter
- Case studies with step-by-step calculation examples
- Responsive design — works on mobile and desktop
- Verified 2026 brokerage rates from official sources

## Brokerage Rates (March 2026)

| Broker | Brokerage (Delivery) | DP Charges (per sell/ISIN) | Annual AMC |
|--------|---------------------|---------------------------|------------|
| Dhan | ₹0 | ₹12.50 + 18% GST = ₹14.75 | ₹0 |
| Zerodha | ₹0 | ₹13.00 + 18% GST = ₹15.34 | ₹300/yr (portfolio > ₹10L) |
| Groww | ₹20 or 0.05% (lower) per side | ₹20 + 18% GST = ₹23.60 | ₹0 |

## Parameters

| Slider | Range | What it affects |
|--------|-------|-----------------|
| Trade Value | ₹10K – ₹5L | Groww's brokerage (0.05% cap) |
| Sell Orders | 1 – 5 | DP charges multiply per sell order |
| Trades/Year | 1 – 52 | All costs scale linearly |
| Stocks/Trade (ISINs) | 1 – 10 | DP charges multiply per ISIN |

## Excluded Charges

The following charges are identical across all brokers and excluded from comparison:
- STT (Securities Transaction Tax)
- Stamp Duty
- Exchange Transaction Charges
- SEBI Turnover Fees

## Tech

Single HTML file — no build tools, no dependencies (except Chart.js CDN).

- HTML + CSS + vanilla JavaScript
- Chart.js for stacked bar chart
- CSS variables for theming
- LocalStorage for theme preference

## Sources

- [Dhan Pricing](https://dhan.co/pricing/)
- [Zerodha Charges](https://zerodha.com/charges/)
- [Groww Pricing](https://groww.in/pricing)

## License

MIT
