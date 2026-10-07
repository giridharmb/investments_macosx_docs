# Support & FAQ

**Report a problem or request a feature:** open an issue in this repository.

**Sending diagnostic logs:** reproduce the problem, then choose *Settings → Diagnostics → Export diagnostic logs…* (or *Help → Export Diagnostic Logs…*) and attach the text file to your issue. Turning on *Detailed logging* first records extra sync and data steps. Logs contain no amounts or notes.

### The AI Advisor says it's unavailable
On-device AI requires a Mac with Apple silicon and Apple Intelligence enabled. If the model is still downloading, try again later. A rule-based analysis is shown meanwhile.

### Are the tax numbers exact?
No — they're estimates using simplified rules (standard deduction, major credits). Use them for planning, and file with tax software or a professional.

### The W-2 scan missed some values
Scan quality matters. Use a flat, well-lit image or the original PDF, then correct values on the review screen before saving.

### Why does my spending trend look flat — or spiky?
Recurring everyday budgets (groceries, dining, transport, shopping…) are spread evenly across the days, so they look flat; log one-off purchases to see real variation. Bills such as rent land on their due date, so daily and weekly views show a spike that day. Tap **Flexible** to leave fixed bills out.

### Where are the interest rates and inflation from?
Approximate 2026 defaults per country. Override inflation and expected return in *Profile & Assumptions*.

### iCloud sync isn't working
Make sure every device is signed in to the same Apple Account with iCloud enabled, and sync is on in *Settings* on each device. The Settings screen shows the iCloud account state and the last sync time. Initial sync of a large history can take a few minutes.

### I signed out of iCloud — is my data gone?
No. WealthPilot keeps a full copy on each device. When it detects that you signed out (or switched to a different Apple Account) it switches to that copy and shows a message. Sign back in and turn sync on again in Settings to resume syncing.

### How do I move to a new device without iCloud?
*Settings → Export backup (JSON)* on the old device, then *Restore from backup* on the new one.

### How do I start over?
*Settings → Erase all financial data*, or *Load sample data* to explore.

### How do I create a what-if scenario without touching my real plan?
Profiles → New profile → *Copy of current profile*. Change anything in the copy; the original stays untouched. Compare both on the Profiles screen.

### Can WealthPilot connect to my bank?
No — by design. You enter balances, income and spending yourself (or import a backup), so nothing about your accounts ever goes to a bank aggregator. For holdings, add a ticker and share count and use *Refresh prices* to keep values current.

### A ticker's price won't load
Check the symbol as Yahoo Finance writes it — outside the US add the exchange suffix (e.g. `SHEL.L`, `RELIANCE.NS`, `SAP.DE`). London prices quoted in pence are converted to pounds. If the service can't be reached, type the price in the holding yourself.

### How do I share the plan with my partner?
On your own devices, turn on iCloud sync. For a partner with their own Apple Account, open *Household* → *Send household file…* and send it by AirDrop, Messages or Mail; they open it with *Open a household file…*. Each later file updates the same household on their device without duplicates, and they can send changes back the same way. The file holds your full plan, unencrypted — send it only to them.

### Why didn't my one-time income raise my take-home pay?
One-time money (a stock sale, bonus or gift) isn't part of your monthly pay. If it's still to come, it's added to Projections and Life Events on its date; if it's already arrived, add it to the account it went into so your balances include it.

### My rent from a rental property is counted twice
If you added the property under *Real Estate* with its rent, delete any separate *Rental income* entry under Income — the property's rent is already counted (after empty months, costs and the loan).

### Where can I find the weekly digest?
*Reports & Digest*. Turn on *Send me the digest every week* to get it as a notification; it's refreshed with your latest numbers each time you open the app.

### Why don't I see my data?
Check the profile button at the top of the sidebar — you may be viewing a different profile.
