# Release notes

## 1.7 — October 2026
- **Navigation fixed across screens:** links inside a screen (Dashboard → AI Advisor or Inputs checklist, checklist → Add income, Investments → Manage strategies, Taxes → Add W-2, Expenses → Rent vs Buy) now open on top of the screen you were on, so **Back** returns there instead of to the sidebar.
- **AI Advisor:** the question list is the main screen; asking opens the conversation on its own screen and **Back** returns to the questions (your category stays selected), with **Continue** to pick the conversation up again. Each answer suggests related questions. An answer keeps generating if you leave the screen, and a half-typed question is kept.
- **Your inputs stay put:** sliders, pickers and what-ifs — Projections, Taxes, Debts, Retirement, Budget, expense and spending-trend filters, every calculator, Rent vs Buy and each investment strategy — are remembered per profile, including after restarting the app. Strategy panels and Rent vs Buy only refill from your data when those numbers change (a new balance, rent or age); use the ↺ button next to the strategy, or *Reset to my numbers* in Rent vs Buy, to start over.
- **Budget & Bills** (new screen under Cash Flow): set a monthly limit per spending category and see this month's progress, what's left, and where you'll land at your current pace. *Suggest from the last 3 months* fills in budgets for the categories you control (groceries, dining, shopping, travel…). Below that, every bill, EMI and paycheck coming up in the next 2 weeks, 30 days or 60 days, with a forecast of your checking balance and a warning if it would go negative.
- **Financial health score** on the Dashboard: 0–100 across savings rate, emergency fund, debt, housing cost, cash flow, retirement odds and protection, with your biggest opportunity called out.
- **Tax-loss harvesting** in Investments: holdings worth less than you paid in taxable accounts, the US $3,000 ordinary-income offset, estimated tax saved and the amount carried forward, with a wash-sale reminder.
- **Life insurance calculator** in Calculators (DIME method), prefilled from your income, debts and savings.
- New insights: over budget or on pace to go over, and losses you could harvest.
- **Investment Strategies** (replaces *Wheel Strategy*): pick your approach — the options wheel, **dollar-cost averaging** (lump sum vs monthly slices over 800 simulated markets), **dividend growth** (after-tax income by year, yield on cost, the year dividends cover your inflation-adjusted spending) or a **three-fund index portfolio** (never vs yearly vs 5-point-drift rebalancing on the same markets, plus what fees cost). Your pick is remembered per profile; simulations run in the background so sliders stay smooth.
- **Diagnostic reports (optional, off by default):** *Settings → Diagnostics → Send diagnostic reports to the developer* sends new log entries and Apple's crash reports through iCloud so problems can be fixed without you exporting anything. See the privacy policy.
- **Mix and match strategies:** *All strategies together* projects every strategy you follow — and unmapped holdings — as one portfolio to retirement. Slide each strategy's share of new money and watch the mix, expected return, median and bad case, late-drop risk, comparison with a single target-date fund and the chart update live. Optionally move today's balances between strategies too, with the buy/sell amounts, an estimated tax on selling, and a comparison with keeping things as they are. The mix is saved with the profile.
- **Four more strategies:** target-date glide path (with the crash risk in the years just before retirement), core & satellite (index core plus your own picks), bond / CD ladder (income or rolling, year by year) and All-Weather / Permanent portfolio (compared with 100% stocks and 60/40). Each can be mapped to your holdings like the others.
- **Multiple strategies, mapped to your holdings:** add as many strategies as you follow (e.g. *Retirement core* as a three-fund portfolio, *Dividend income* in your brokerage account), pick the holdings that follow each, and see each one modeled with those holdings' balance, monthly contributions, fees and mix. A bar shows how the portfolio splits between strategies; unmapped holdings are listed; holdings are tagged with their strategy under Investments; the AI Advisor knows which strategies you follow. Saved with the profile, so they sync and back up.
- **Spending trend, rebuilt:** choose 1M, 3M, 6M, year to date, 1Y, 2Y or any custom dates, and group by day, week, two weeks or month. View by category or as totals with an average line; see total, average, peak period and the change versus the previous period of the same length. Tap *Flexible* to hide fixed bills, or any category to isolate it. Bills now land on their due dates and everyday budgets are spread across the days, so short ranges look like real life. Your choices are remembered.
- Budgets are saved with each profile, so they sync, back up and copy with it.
- **AI Advisor follows your changes:** the conversation is kept while you edit your data elsewhere; when numbers change, the advisor shows what moved since its last answer and offers **Update answer**. Answers after a change note what changed, and on-device AI follow-ups still remember what you asked.
- **Tax figures checked against IRS sources for 2026:** SALT deduction cap corrected to $40,400 ($20,200 married filing separately), phasing down above $505,000 of income; estate exemption stated as $15,000,000; Roth catch-up rule tied to 2025 FICA wages over $150,000; 37% withholding on bonuses above $1 million noted.
- **AI Advisor:** 120 starter questions (112 new) in 11 categories, including new Income & career, Family & kids and Wealth & net worth sections — from daily lifestyle cost, food and housing spend to credit-card payoff, mortgage prepayment, market crashes, withdrawals, Social Security, deductions, capital gains, job offers, side income, child and college costs, estate planning, liquidity and when you could become a millionaire. Each question comes with exact figures computed by the app, so the on-device model explains your real numbers instead of doing arithmetic; without Apple Intelligence you get a rule-based answer to the specific question, not a generic report. Typed questions are matched to the closest topic.

## 1.6 — October 2026
- **Fixed: new entries weren't saved.** Adding an income, expense, debt, savings account, goal, asset, holding or W-2 could silently do nothing (the editor treated the new item as an existing one), so charts never changed. Amount fields now also take effect as you type — you no longer need to press Return before Save.
- **Diagnostic logs:** errors (with full details), crashes, UI hangs, iCloud sync failures and system warnings are recorded on the device for 14 days. Export them from *Settings → Diagnostics* or *Help → Export Diagnostic Logs…* to report a problem. No amounts or notes are logged.
- **Calculations:** payroll 401(k) and HSA contributions are capped at the 2026 limits; Social Security benefits are taxed by the IRS formula (at most 85%) and not by your state; India surcharge on high incomes; California's and Massachusetts' $1M surtaxes are no longer doubled for joint filers; projections grow savings balances at savings-account rates (not stock returns), so plans holding lots of cash show lower — more realistic — results; alert thresholds scale for ₹/¥/AED; retirement "closing the gap" accounts for inflation.
- **Fixes:** a crash on the Dashboard when an expense category named "Other" was among the top categories; an expense end date can no longer fall before its start; paid-off debts can be saved at 0; overdue goals say so; percentage fields are capped at 100%; tapping an empty month no longer highlights the next one.
- **W-2 scanning:** tax years, ZIP codes and box numbers are no longer read as amounts; better matching for Box 1, the Box 15 state and the employer name; rotated PDF pages are read correctly; the tax year is read from the form.
- **Safety:** an automatic backup is saved before restoring, erasing, loading sample data or deleting a profile, and a restore can't leave a profile half-empty. With iCloud on, records that arrive before their profile are no longer moved to "Recovered data". The on-device copy is only refreshed after the iCloud account is confirmed.
- **AI Advisor:** stops generating when you leave the screen, and says when your data changed and it started a fresh conversation.
- **Mac:** the Settings window (⌘,) can't be used while the app is locked; the app relocks when hidden, when the screen sleeps, or when you switch away with no main window open; profile switching is blocked while locked; long charts keep scrolling to new data and no longer crash when recent data is deleted.

## 1.5 — October 2026
- **Your data is always kept on this device.** iCloud data and on-device data now live in separate stores. While sync is on, WealthPilot keeps a full copy on the device, so signing out of iCloud (or switching accounts) never removes your data — the app switches to the on-device copy and tells you.
- Turning sync on copies this device's data to iCloud; turning it off copies your iCloud data back to the device. Every record has a stable identity, so repeated syncs never create duplicates.
- Existing data is migrated automatically on first launch; the previous data file is kept as a fallback.

## 1.4 — October 2026
- **Safety:** automatic local backups (daily and before turning on iCloud, last 10 kept) with one-click restore; choosing to merge or keep separate when enabling iCloud on a device that already has data; onboarding sample data can no longer erase data arriving from iCloud; orphaned records are kept in a “Recovered data” profile; duplicate monthly net-worth points are merged.
- **App lock:** now covers open sheets, the Settings window and the menu-bar panel; turning it off requires authentication; menu shortcuts are blocked while locked.
- **Fixes:** Cancel now discards edits; age steppers no longer crash at the limits; negative amounts are rejected; AI Advisor no longer crashes when starting a new conversation mid-answer; W-2 scans read photos in the right orientation, parse PDF pages separately and report only boxes actually read; expense end dates save correctly; sliders scale for ₹/¥/AED; New Debt shortcut is now ⌥⌘L.
- **Calculations:** India 87A marginal relief and no EPF deduction under the new regime; UK NI thresholds, 45% band and allowance taper; HSA/401(k) contributions no longer double-counted or dropped; debt interest insight uses each debt's own rate; payoff shows “Never” when payments don't cover interest; retirement strategies compared on identical market paths; recommended allocation always totals 100%.

## 1.3.3 — October 2026
- Fixed a possible UI hang on macOS ("Geometry action is cycling"): chart legends now use a stable wrapping layout instead of nested lazy grids, and charts no longer update view state during layout.

## 1.3.2 — October 2026
- Charts on macOS: click-and-drag, trackpad sideways swipe and ⇧-scroll pan long charts (spending trend, net worth, projections); click to inspect; ‹ › Latest buttons. Fixed jitter and drift while scrolling.

## 1.3.1 — October 2026
- Charts: scrollable charts now scroll with swipe/trackpad and snap to months; tap/click inspects a point (tap again to dismiss). Fixed clipped first/last bars, misaligned month labels, inconsistent stacking colors, overflowing legends and a jagged retirement fan chart. Smoother interaction on Projections, Retirement, Wheel and Rent vs Buy (simulations are cached).

## 1.3 — October 2026
- Menu bar commands with keyboard shortcuts (File ▸ New, Profile, Go, View, Help) and a menu-bar extra with live stats, profile switcher and quick-add expense.
- Fixed signing: new iCloud container identifier.

## 1.2 — October 2026
- Profiles: multiple independent plans with their own inputs, results and history. Create blank / copied / sample profiles; rename, restyle, duplicate, export, delete; compare results side by side. Existing data becomes the “Default” profile.
- Backups: export one or all profiles; import as a new profile or replace the current one.

## 1.1 — October 2026
- iCloud sync across iPhone, iPad and Mac (private CloudKit database).
- New Settings screen: Face ID / Touch ID app lock, privacy mode, app-switcher cover (iOS), theme, start screen, monthly & weekly reminders, AI toggle, simulation quality, JSON backup & restore, CSV export.

## 1.0 — October 2026
- First release for macOS.
- Dashboard, Income & Paycheck, Taxes (US 2026 + 8 countries), W-2 scanning, Expenses & Rent, Debts & EMIs, Savings & Goals, Investments, Projections (Monte Carlo), Retirement withdrawal strategies, Wheel options strategy, Rent vs Buy, Calculators, AI Advisor, Inputs Checklist.
