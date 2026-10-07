# Privacy policy

_Last updated: October 7, 2026_

WealthPilot is designed so your financial data never leaves your device.

- **No account, no server.** All data (income, expenses, debts, balances, W-2s, goals) is stored locally using Apple's SwiftData in the app's private container.
- **Optional iCloud sync.** If you turn on *Settings → Sync with iCloud*, your data — including screen settings and saved scenarios — is stored in **your own private iCloud (CloudKit) database**, which only you can access. The developer cannot see it. Data is encrypted in transit and at rest by Apple; with Advanced Data Protection it is end-to-end encrypted. A full copy of your data is always kept on the device as well, so signing out of iCloud doesn't remove it from the device. Turn sync off at any time; delete iCloud data via your device's iCloud settings (Manage Storage).
- **No tracking or analytics.** The app contains no third-party SDKs, advertising, or analytics.
- **On-device AI.** The AI Advisor and W-2 extraction use Apple's on-device Foundation Models. Prompts and responses are processed on your device.
- **Documents and camera.** W-2 files, photos are read only to recognize text on-device and are not stored or transmitted. 
- **Network.** WealthPilot makes network requests only for things you turn on or ask for: Apple's iCloud sync and diagnostic reports (each only when you turn it on), and two optional lookups you trigger with a button —
  - **Share prices:** *Get price* in a holding and *Refresh prices* send only the ticker symbols you entered (e.g. "VTI") to Yahoo Finance's public quote service to read the latest price. No amounts, share counts or other data are sent.
  - **Exchange rates:** *Get latest rates* asks the free Frankfurter service for the European Central Bank's reference rates. Nothing about you or your money is sent.

  Like any web request, these services see your device's IP address. You can always enter prices and rates yourself instead. Financial data is never included in diagnostic reports. WealthPilot never connects to your bank.
- **Automatic backups.** WealthPilot keeps up to 10 automatic backups (daily, and before iCloud is turned on) inside the app's private storage on your device. They are not uploaded anywhere and are removed if you delete the app.
- **Diagnostic logs.** To help fix bugs, WealthPilot records errors, crashes, UI hangs, sync problems and the screens you visited in a log inside the app's private storage (last 14 days). Logs contain no amounts, names or notes. They stay on your device unless you turn on *Settings → Diagnostics → Send diagnostic reports to the developer* (off by default). When it is on, new log entries and Apple's crash and hang reports for WealthPilot are sent to the developer through Apple's iCloud (the app's CloudKit public database). This requires being signed in with an Apple Account but not iCloud Drive. Each report includes the device model, OS and app version, and a random ID that is not linked to your Apple Account. Reports are used only by the developer, to fix bugs. Turn the setting off to stop sending. You can also export logs yourself to share with support, or clear them.
- **Backups.** JSON backups you export are written where you choose and are not encrypted — store them safely.
- **Household files.** *Household → Send household file…* saves your whole profile (amounts, names and notes included) as an unencrypted file so you can send it to your partner yourself — by AirDrop, Messages, Mail or Files. WealthPilot doesn't send it anywhere; whoever you give it to can read it, so share it only with people you trust.
- **Reports and notifications.** PDF reports are made on the device and saved or shared only where you choose; they contain your financial details. The weekly digest notification is scheduled on the device and its text (amounts included) is shown in Notification Center and on the Lock Screen according to your notification settings — turn off previews if others can see your screen.
- **Deleting data.** Use *Settings → Erase all financial data* (with sync on, this also removes it from iCloud), or delete the app.

If your device backs up app data (e.g. iCloud or Time Machine backups), that backup is governed by Apple's and your own settings.

Questions: open an issue at https://github.com/giridharmb/investments_macosx_docs/issues
