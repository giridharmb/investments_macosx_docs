<p align="center"><img src="icon.png" width="160" alt="WealthPilot icon"></p>

<h1 align="center">WealthPilot for macOS</h1>

<p align="center"><b>Personal finance, savings, investing, tax and retirement planning — private, on-device, with Apple Intelligence.</b></p>

WealthPilot turns your paycheck, rent, expenses, debts, savings and investments into one clear plan: where your money goes, where you can save, what you'll pay in taxes, and whether you're on track to retire. Everything is computed **on your device** — no accounts, no servers, no tracking. Optional **iCloud sync** keeps your iPhone, iPad and Mac in step through your private iCloud database.

> Also available for iOS: [investments_ios_docs](https://github.com/giridharmb/investments_ios_docs)

![Dashboard](screenshots/dashboard.png)

## Highlights

| | |
|---|---|
| 📊 **Dashboard** | Net worth, take-home pay, spending, savings rate, emergency-fund months, retirement odds, effective tax rate a 0–100 financial health score, and a spending trend by day, week, two weeks or month over any date range. |
| 💼 **Paycheck** | Gross → 401(k)/pension → health/HSA → taxes → net, per paycheck. Employer-match gap detection. |
| 🏛 **Taxes** | 2026 US federal brackets, FICA, all 50 states + DC (approx.), child tax credit; simplified national systems for India, UK, Canada, Germany, Australia, Singapore, UAE and Japan. |
| 🧾 **W-2 import** | Scan a W-2 (PDF or image file, or Photos). Vision OCR + on-device AI extract the boxes; you review before saving. Predicts refund or amount owed. |
| 🏠 **Expenses & Rent** | 22 categories, recurring and one-off spending, rent affordability (30% rule), state median-rent comparison, 50/30/20 check. |
| 📅 **Budget & Bills** | Monthly category budgets with pace tracking and suggestions; upcoming bills, EMIs and paychecks with a checking-balance forecast. |
| 💳 **Debts & EMIs** | EMI calculation, amortization charts, Avalanche vs Snowball payoff with extra-payment slider. |
| 🐷 **Savings & Goals** | Emergency fund, high-yield optimization, goals with the monthly amount needed. |
| 📈 **Investments** | Allocation vs an age/risk glide path, expected return, volatility, risk score, fee drag, “where should my next dollar go” ladder, tax-loss harvesting. |
| 🔮 **Projections** | Deterministic + 1,000-path Monte Carlo fan charts, FI age, sustainable spending, what-if sliders. |
| 🏖 **Retirement** | Readiness gauge, income by source, withdrawal strategies (4% rule, Guardrails, percent-of-portfolio, floor & ceiling), bucket strategy. |
| 🧭 **Investment strategies** | Pick one: the options **wheel** (Black-Scholes premiums, Monte Carlo vs buy-and-hold), **dollar-cost averaging** vs lump sum, **dividend growth** income, or a **three-fund index portfolio** with rebalancing rules — each prefilled from your plan. |
| 🏡 **Rent vs Buy** | Net worth comparison with breakeven year. |
| 🧮 **Calculators** | Loan/EMI with prepayment, SIP/compound with step-up, inflation, FIRE, life insurance needs. |
| ✨ **AI Advisor** | Ask questions about *your* numbers using Apple's on-device Foundation Models — or pick from 39 starter questions across spending, saving, debt, investing, retirement, taxes and big decisions. Answers quote figures the app computes itself; a rule-based answer is shown when Apple Intelligence is unavailable. |
| 👥 **Profiles** | Multiple independent plans — “Default” plus any number you create (blank, copied, or sample). Rename, restyle, duplicate, export, delete, and compare results side by side. |
| ☁️ **iCloud sync & settings** | Optional sync across devices, Face ID / Touch ID app lock, privacy mode that masks amounts, reminders, JSON backup/restore and CSV export. |
| ⌨️ **Menus & menu bar extra** | Full menu bar with keyboard shortcuts (New…, Profile switching ⌃⌘1–9, Go ⌘1–0, Hide Amounts, Import/Export) plus a menu-bar panel with live stats and quick-add expense. |
| ✅ **Inputs checklist** | Shows which inputs are required, recommended or optional — and what each one unlocks. |

## Screenshots

Screenshots below are from the iPad build, followed by the macOS app.

| Projections | Wheel strategy | Retirement |
|---|---|---|
| ![](screenshots/projections.png) | ![](screenshots/wheel.png) | ![](screenshots/retirement.png) |
| **Expenses & Rent** | **Taxes** | **Debts & EMIs** |
| ![](screenshots/expenses.png) | ![](screenshots/taxes.png) | ![](screenshots/debts.png) |
| **Investments** | **AI Advisor** | **Rent vs Buy** |
| ![](screenshots/investments.png) | ![](screenshots/advisor.png) | ![](screenshots/rentVsBuy.png) |
| **Settings & iCloud** | **Profiles** | |
| ![](screenshots/settings.png) | ![](screenshots/profiles.png) | |

### macOS

| Dashboard | Dashboard charts | Projections |
|---|---|---|
| ![](screenshots/mac/01-dashboard.png) | ![](screenshots/mac/02-dashboard-charts.png) | ![](screenshots/mac/03-projections.png) |
| **Expenses & Rent** | **Investments** | **Taxes** |
| ![](screenshots/mac/04-expenses-and-rent.png) | ![](screenshots/mac/05-investments.png) | ![](screenshots/mac/06-taxes.png) |
| **Retirement** | **Wheel strategy** | **Debts & EMIs** |
| ![](screenshots/mac/07-retirement.png) | ![](screenshots/mac/08-wheel-strategy.png) | ![](screenshots/mac/09-debts-and-emis.png) |
| **Profiles** | | |
| ![](screenshots/mac/10-profiles.png) | | |

## Requirements

- macOS 26 (Tahoe) or later on Apple silicon / Intel
- On-device AI features need a Mac with Apple silicon and Apple Intelligence enabled. Everything else works on any supported device.

## Documentation

- [User guide](GUIDE.md) — every screen explained
- [Methodology & assumptions](METHODOLOGY.md) — formulas, tax tables, data sources
- [Privacy policy](PRIVACY.md)
- [Support & FAQ](SUPPORT.md)
- [Release notes](CHANGELOG.md)

## Disclaimer

WealthPilot provides educational estimates and planning tools. It is **not** financial, investment, tax or legal advice, and the developer is not a licensed advisor. Tax rules are simplified; market simulations are hypothetical. Consult qualified professionals before making financial decisions.
