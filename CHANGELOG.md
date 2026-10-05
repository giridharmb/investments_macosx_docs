# Release notes

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
