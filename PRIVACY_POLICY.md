# Privacy Policy — Tita

**Last updated:** March 28, 2026

## Introduction

Tita ("the App") is developed by EgeaINC. This Privacy Policy explains how we handle information when you use our App.

## Data Collection

**We do not collect, store, or transmit any personal data.** The App operates entirely on your device.

### What the App does NOT do:
- Does not collect personal information (name, email, phone, etc.)
- Does not use analytics or tracking services
- Does not display advertisements
- Does not share any data with third parties
- Does not use cookies or similar technologies

### Local Storage Only

The App stores the following data **locally on your device only**:
- **Reminders:** Titles, dates, categories, and recurrence settings of reminders you create (stored in local SQLite database)
- **Medications:** Medication schedules, frequencies, and end dates (stored in local SQLite database)
- **Birthdays:** Birthday reminders with annual recurrence (stored in local SQLite database)
- **Categories:** Custom category assignments for your reminders (stored in local SQLite database)
- **Preferences:** App settings like notification style and sound preferences (stored in SharedPreferences)

This data never leaves your device and is deleted when you uninstall the App.

### Voice Input

The App offers optional voice input for creating reminders. Speech recognition is processed using on-device capabilities (Google ML Kit). **Audio is not recorded, stored, or transmitted to any server.**

### Internet Usage

The App connects to the internet solely for:

1. **In-app purchases:** Processed entirely through Google Play Billing. We do not have access to your payment information. Google's privacy policy applies to these transactions.

### Permissions

The App requests the following Android permissions:
- **Microphone:** Used for voice input to create reminders. Audio is processed on-device only and is never recorded or transmitted.
- **Notifications:** Required to deliver reminder alerts at scheduled times.
- **Exact alarms:** Required to fire reminders at the precise time you set, even when the phone is in battery-saving mode.
- **Internet:** Required for in-app purchases through Google Play.
- **Vibration:** Used for notification alerts.
- **Foreground service:** Required to play alarm sounds when a reminder fires.
- **Boot completed:** Required to reschedule your alarms after a phone restart.
- **Battery optimization exemption:** Requested to ensure alarms fire reliably on devices with aggressive battery management.

## Children's Privacy

The App does not knowingly collect any information from children under 13 years of age. All data is stored locally on the user's device only and is never transmitted.

## Changes to This Policy

We may update this Privacy Policy from time to time. Changes will be posted on this page with an updated revision date.

## Contact

If you have questions about this Privacy Policy, please open an issue at:
https://github.com/gabriel600r/tita-feedback/issues

---

*Tita — App de Recordatorios by EgeaINC*
