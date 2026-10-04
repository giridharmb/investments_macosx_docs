# WealthPilot user guide (macOS)

## Getting started

On first launch choose **Set up my profile** or **Explore with sample data** (a fictional profile you can erase from *Profile & Assumptions*).

Only four things are **required** for meaningful results:

1. Country, age and retirement age
2. Your paycheck / income
3. Rent or housing cost
4. A few monthly expenses

Everything else is **recommended** (debts, savings, investments, state) or **optional** (W-2, filing status, Social Security estimate, goals, other assets). The **Inputs Checklist** screen shows what's missing and what each input unlocks.

## Menus & keyboard shortcuts

Everything is reachable from the menu bar.

| Menu | Commands |
|---|---|
| **File** | **New ▸** Income (⌥⌘I), Recurring Expense (⌥⌘E), One-off Expense (⌘N), Debt/EMI (⌥⌘D), Savings Account, Savings Goal, Asset, Investment (⌥⌘V), W-2 · **New Profile…** (⇧⌘N) · **Import Backup…** (⇧⌘I) · **Export Current Profile…** (⇧⌘E) · Export All Profiles… · Export Expenses as CSV… |
| **View** | **Hide Amounts** (⇧⌘H) · **Appearance** ▸ System / Light / Dark · **Lock WealthPilot** (⌃⌘L, when app lock is on) |
| **Profile** | Every profile with a checkmark on the active one — switch with **⌃⌘1…9** · New / Rename / Duplicate current profile · **Manage Profiles…** (⇧⌘P) · Edit Profile & Assumptions |
| **Go** | All screens — Dashboard ⌘1, AI Advisor ⌘2, Income ⌘3, Taxes ⌘4, Expenses ⌘5, Debts ⌘6, Savings ⌘7, Investments ⌘8, Projections ⌘9, Retirement ⌘0 |
| **Help** | User guide, methodology, privacy policy, report an issue |

### Menu bar extra
A chart icon in the macOS menu bar opens a compact panel for the active profile:
net worth, take-home, spending, savings rate, free cash flow and emergency-fund months; the top warning; a **profile switcher**; a **hide/show amounts** toggle; **quick add expense** (amount, category, note — press Return); and buttons to open the app, Settings (⌘,) or quit.
Turn it off in *Settings → Appearance → Show in menu bar*.

## Profiles

A **profile** is a complete, independent plan: its own country and assumptions, income, expenses, debts, savings, investments, goals, W-2s, net-worth history — and therefore its own results. Use them for:

- separate people or households (you, parents, a client),
- what-if scenarios (“Move to Texas”, “Retire at 50”, “Buy a house in 2028”),
- a sandbox with sample data.

**Default** is created automatically. It can be renamed and restyled but not deleted.

- **Switch** from the profile button at the top of the sidebar, or from the Profiles screen. Every screen immediately shows the selected profile.
- **Create** (Profiles → New profile): start *blank*, as a *copy of the current profile* (ideal for what-ifs), or with *sample data*. Pick a name, icon and color.
- **Manage** from each profile card's ⋯ menu: rename & style, duplicate, export, delete (removes the profile and all its data).
- **Compare**: with two or more profiles, the Profiles screen charts net worth, projected retirement balance and target, and lists key results side by side.
- **Backups**: export one profile or all profiles. When importing, add the backup as a new profile or replace the current one.
- **iCloud**: all profiles sync. Each device remembers which profile it has open.

## Screens

### Dashboard
KPI tiles, *Where your paycheck goes* (donut from gross pay: taxes, housing, living costs, EMIs, retirement, benefits, saving, unassigned), top spending categories, a 12-month stacked spending trend (scroll horizontally; tap a bar for the per-category tooltip), net worth history (recorded monthly), a retirement fan chart and the top savings opportunities with $/month impact.

### Income & Paycheck
Add salary (any pay frequency), self-employment, rental, dividends, pension or other income. For salary enter your 401(k)/pension % (pre-tax or Roth), employer match (e.g. 100% up to 6%), and per-paycheck deductions (health premium, HSA, FSA/commuter, post-tax). The paycheck breakdown chart shows exactly where each paycheck goes.

### Taxes
Annual estimate with federal/national, state/regional, Social Security/social insurance, Medicare and self-employment tax; effective and marginal rates; a bracket chart; and a *what-if* slider showing how much tax extra pre-tax contributions save. With a W-2 on file (US) it compares withholding vs. estimated liability.

### W-2 Forms
Import from PDF or image file, or Photos. Text is recognized with Apple Vision and structured with layout heuristics plus Apple Intelligence (if available). **Always review the values** before saving. You can also create a salary income from the W-2.

### Expenses & Rent
Recurring bills (with frequency, start/end dates) and one-off purchases. Mark items essential vs. discretionary. The Rent card shows housing as % of gross pay, the 30% affordability limit, your state's rough median rent and 5-year rent cost. The 50/30/20 card compares needs/wants/savings with targets.

### Debts & EMIs
Each loan's EMI is computed from balance, APR and remaining months (or enter your actual payment). Tap a debt to see its amortization (principal vs. interest by year with the remaining balance). *Payoff strategy* compares minimum payments, Avalanche (highest rate first) and Snowball (smallest balance first) with an adjustable extra payment.

### Savings & Goals
Accounts with APY and monthly contributions; flag your emergency fund. A 5-year chart compares your current rates with the best typical high-yield rate. Goals show progress and the monthly saving needed to hit the target date.

### Investments
Holdings by account type (401(k), IRA, Roth, brokerage, HSA, 529, pension, crypto, real estate) and asset class. Shows current vs. recommended allocation (age- and risk-based glide path), rebalancing suggestions, a risk/return scatter vs. model portfolios, and the prioritized contribution ladder (emergency fund → match → high-interest debt → HSA → IRA → 401(k) max → taxable).

### Projections
Year-by-year projection plus a 1,000-scenario Monte Carlo fan chart in today's money. What-if sliders: extra monthly investing, retirement age, return, retirement spending, inflation. Milestone table every 5 years.

### Retirement
Readiness (projected vs. needed), budget split between benefits and portfolio, income-by-source chart, and a comparison of withdrawal strategies with success rates and spending ranges. The bucket strategy splits the nest egg into cash (years 1–2), bonds (3–10) and growth (11+).

### Wheel Strategy
Model the options “wheel”: sell a cash-secured put; if assigned, sell covered calls above your cost basis; if called away, start again. Adjust price, implied volatility, strike distances, days to expiry, drift, rate and horizon. See per-trade quotes (premium, delta, assignment probability, annualized return), a Monte Carlo comparison against buy-and-hold, drawdowns, and an estimate of monthly income from an options sleeve of your portfolio. Read the risk notes — the wheel keeps most of the stock's downside while capping its upside.

### Rent vs Buy
Compares the net worth of buying (equity after selling costs + invested savings) against renting and investing the difference, with a breakeven year.

### Calculators
Loan/EMI with prepayment, SIP/compound growth with annual step-up, inflation, and FIRE (years to financial independence).

### AI Advisor
Ask natural-language questions such as *“Where am I overspending?”* or *“Should I pay off debt or invest?”*. A compact summary of your numbers (viewable under *What the advisor sees*) is given to Apple's on-device language model. Nothing is sent to a server. If Apple Intelligence is unavailable, a rule-based report is shown instead.

### Profile & Assumptions
Country, state, filing status, dependents, ages, risk tolerance (with a 5-question quiz), retirement spending, Social Security/pension estimate, salary growth, and optional overrides for inflation and expected return. Data tools (backup, restore, sample data, erase) live in **Settings**.

### Settings
Open from the sidebar or with **⌘,**.

| Setting | What it does |
|---|---|
| **Sync with iCloud** | Stores your plan in your private iCloud (CloudKit) database and syncs it across devices signed in to the same Apple Account. Shows account state, sync activity and last sync time. Turning it off keeps a local copy. |
| **Require Face ID / Touch ID** | Locks the app on launch and when it returns from the background (falls back to device passcode). |

| **Hide amounts** | Privacy mode — masks every money value on screen. |
| **Theme / Open app to** | Light, dark or system appearance; the screen shown at launch. |
| **Reminders** | Monthly money check-in (choose the day) and weekly spending log (choose the weekday), at a time you pick. |
| **On-device AI analysis** | Turn Apple Intelligence features off to use rule-based analysis only. |
| **Monte Carlo scenarios** | 500 – 5,000 simulated markets for projections. |
| **Data** | Export a JSON backup, restore from a backup, export expenses as CSV, load sample data, or erase everything. |

Device-specific preferences (theme, lock, reminders) stay on each device; your financial data is what syncs.
