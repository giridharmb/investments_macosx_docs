# Privacy policy

_Last updated: October 4, 2026_

WealthPilot is designed so your financial data never leaves your device.

- **No account, no server.** All data (income, expenses, debts, balances, W-2s, goals) is stored locally using Apple's SwiftData in the app's private container.
- **Optional iCloud sync.** If you turn on *Settings → Sync with iCloud*, your data is stored in **your own private iCloud (CloudKit) database**, which only you can access. The developer cannot see it. Data is encrypted in transit and at rest by Apple; with Advanced Data Protection it is end-to-end encrypted. A full copy of your data is always kept on the device as well, so signing out of iCloud doesn't remove it from the device. Turn sync off at any time; delete iCloud data via your device's iCloud settings (Manage Storage).
- **No tracking or analytics.** The app contains no third-party SDKs, advertising, or analytics.
- **On-device AI.** The AI Advisor and W-2 extraction use Apple's on-device Foundation Models. Prompts and responses are processed on your device.
- **Documents and camera.** W-2 files, photos are read only to recognize text on-device and are not stored or transmitted. 
- **Network.** Apart from Apple's iCloud sync (when you enable it), WealthPilot makes no network requests with your data.
- **Automatic backups.** WealthPilot keeps up to 10 automatic backups (daily, and before iCloud is turned on) inside the app's private storage on your device. They are not uploaded anywhere and are removed if you delete the app.
- **Diagnostic logs.** To help fix bugs, WealthPilot records errors, crashes, UI hangs, sync problems and the screens you visited in a log inside the app's private storage (last 14 days). Logs contain no amounts, names or notes and are never sent anywhere; you can export them yourself (*Settings → Diagnostics*) to share with support, or clear them.
- **Backups.** JSON backups you export are written where you choose and are not encrypted — store them safely.
- **Deleting data.** Use *Settings → Erase all financial data* (with sync on, this also removes it from iCloud), or delete the app.

If your device backs up app data (e.g. iCloud or Time Machine backups), that backup is governed by Apple's and your own settings.

Questions: open an issue at https://github.com/giridharmb/investments_macosx_docs/issues
