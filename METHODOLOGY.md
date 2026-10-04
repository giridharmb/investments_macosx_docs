# Methodology & assumptions

All figures are **estimates** for planning. Values marked “2026” reflect published or approximate figures as of 2026 and may change.

## Cash flow
- Annual gross = Σ amount × periods per year (weekly 52, bi-weekly 26, semi-monthly 24, monthly 12, quarterly 4, annual 1).
- Take-home = gross − taxes − payroll retirement − pre-tax benefits − post-tax deductions.
- Monthly spending = active recurring expenses (monthly equivalent) + one-off spending averaged over the last 90 days.
- Savings rate = (payroll retirement + employer match + HSA + savings + investment contributions) ÷ (gross + match).
- Emergency months = emergency fund ÷ (essential expenses + debt payments).

## Taxes
- **US federal 2026** brackets (IRS Rev. Proc. 2025-32), standard deduction $16,100 single / $32,200 joint / $24,150 HoH, child tax credit $2,200 with phase-out.
- **FICA**: Social Security 6.2% to the $184,500 wage base; Medicare 1.45% + 0.9% above $200k/$250k. Self-employment tax 15.3% on 92.35% of net earnings.
- **States**: simplified single-filer brackets (doubled for joint filers) and standard deductions; local/city taxes excluded.
- **Other countries**: national brackets plus approximate regional and social-insurance rates (India new regime with 87A rebate and 4% cess; UK allowance taper; etc.).

## EMI & debt payoff
- EMI = P·r·(1+r)ⁿ / ((1+r)ⁿ − 1), r = APR/12.
- Avalanche/Snowball: all minimums paid; the extra budget plus freed-up minimums go to the target debt.

## Investments & risk
- Asset-class expected returns derive from the country's equity/bond/cash assumptions; volatilities: domestic stocks 16%, international 17.5%, bonds 6%, REITs 20%, crypto 65%, etc. Portfolio volatility uses a simple correlation matrix.
- Recommended equity share ≈ 110 − age, shifted by risk tolerance (−25 to +15 points), clamped to 20–95%.
- Risk score 1–10 from portfolio volatility; “bad year” = expected return − 1.645σ.

## Projections & Monte Carlo
- Annual steps. Before retirement: balance × (1+r) + contribution × (1 + r/2), contributions growing with salary growth. After retirement: inflation-adjusted spending minus benefits is withdrawn.
- Monte Carlo: 1,000 log-normal return paths (post-retirement volatility × 0.75). Success = money lasts to the plan-until age. Results shown in today's money.
- Retirement target = (annual spending − benefits) ÷ safe withdrawal rate.

## Withdrawal strategies
Simulated in real terms: fixed 4% rule; Guyton-Klinger-style guardrails (±10% adjustments when the withdrawal rate drifts 20% from target); percent-of-portfolio; floor (85%) and ceiling (125%).

## Wheel strategy
- Premiums from Black-Scholes using implied volatility; prices simulated with geometric Brownian motion at realized volatility = IV − 2 points (volatility risk premium).
- Puts struck X% below spot; calls struck X% above max(spot, cost basis). Idle collateral earns the risk-free rate.
- Ignores commissions, bid/ask spreads, early assignment, dividends, gaps and taxes.

## Rent vs buy
Monthly simulation including mortgage amortization, property tax, insurance, maintenance, HOA, appreciation, closing (3%) and selling (6%) costs. The cheaper side invests the monthly difference at the investment return.

## Regional data
Rough country defaults (inflation, deposit/savings/mortgage rates, market returns, rent growth, home appreciation) and US state median rents are approximate and editable through overrides. They are not live market data.
