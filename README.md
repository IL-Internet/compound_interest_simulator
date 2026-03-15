# Compound Interest Simulator

An interactive single-file HTML tool for visualizing how compound interest grows over time.

## more specifically

- Adjustable principal, annual rate, time horizon, and compounding frequency
- Live chart showing total balance, principal, and interest earned over time
- Summary stats: final balance, amount deposited, and total interest gained

## How it works, exactly?

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
