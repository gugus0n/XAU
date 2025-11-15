# XAU Risk Calculator 🏆

A comprehensive risk management calculator for XAU (Gold) trading with multiple position sizes, Fibonacci growth milestones, and risk percentage analysis.

## 🌐 Live Webapp

Visit the live calculator: **https://gugus0n.github.io/XAU/**

## Features

- **XAU-Specific Calculations**: Based on 1 point = $500 per 1 lot
- **Multiple Position Sizes**: Trade from 0.01 to 0.50 lots
- **Adjustable Contracts**: Configure number of contracts (1-100)
- **Risk Percentage Lines**: Visualize risk at 60%, 30%, 11%, 8%, 5%, 2%, 1.5%, 1%, and 0.5%
- **Fibonacci Account Growth**: Track 7 Fibonacci milestone targets
- **Interactive Charts**: 
  - Risk percentage visualization
  - Fibonacci growth path
  - Position size comparison
- **Detailed Analysis Table**: Compare risk across all position sizes
- **Real-time Calculations**: Instant updates as you adjust parameters

## How to Use

1. **Set Account Size**: Enter your risk capital (the amount you're willing to risk)
2. **Number of Contracts**: Choose how many contracts to trade
3. **Contract Size**: Select position size from 0.01 to 0.50 lots
4. **Stop Loss Points**: Set your stop loss in points

The calculator will show:
- Total position size
- Risk per point
- Total risk amount
- Risk as percentage of account
- Visual charts and detailed analysis table

## Understanding XAU

- **XAU** = Gold trading symbol
- **1 Point** = $500 per 1 lot
- **Example**: 0.05 lot position with 10-point stop = $250 risk (0.05 × $500 × 10)

## Margin Calculation Example

With $150 account and 3 contracts of 0.05 each:
- **Total Position**: 0.15 lots (3 × 0.05)
- **Risk per Point**: $75 (0.15 × $500)
- **10-Point Stop Loss Risk**: $750

## Technologies

- HTML5
- JavaScript (Vanilla)
- Chart.js for visualization
- GitHub Pages for hosting

## Local Development

Simply open `index.html` in any modern web browser.

## License

MIT License - Feel free to use and modify for your trading needs.

---

**Disclaimer**: This tool is for educational and planning purposes only. Always manage your risk carefully. Past performance is not indicative of future results.