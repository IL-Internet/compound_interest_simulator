# Compound Interest Explainer

An interactive single-file HTML tool for visualizing how compound interest grows over time.

## Demo

Open `compound_interest_explainer.html` in any browser — no install, no dependencies, no build step.

## Features

- Adjustable principal, annual rate, time horizon, and compounding frequency
- Live chart showing total balance, principal, and interest earned over time
- Summary stats: final balance, amount deposited, and total interest gained

## Usage

Just clone and open:

```bash
git clone https://github.com/your-username/compound-interest-explainer.git
cd compound-interest-explainer
open compound_interest_explainer.html
```

Or download `compound_interest_explainer.html` directly and open it in your browser.

## How it works

Uses the standard compound interest formula:

```
A = P(1 + r/n)^(nt)
```

| Variable | Meaning |
|---|---|
| A | Final balance |
| P | Principal (initial deposit) |
| r | Annual interest rate (decimal) |
| n | Compounding frequency per year |
| t | Time in years |

Chart rendered with [Chart.js](https://www.chartjs.org/) loaded from CDN — the only external dependency.

## License

MIT
