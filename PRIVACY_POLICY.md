# Privacy Policy — Tita

**Last updated:** October 1, 2026

## Introduction

Tita ("the App") is developed by EgeaINC. This Privacy Policy explains how we handle information when you use our App.

## Your Reminders Stay on Your Device

**EgeaINC does not collect, store, or receive your reminders or any other content you create in the App.** It is stored only on your device.

The App stores the following data **locally on your device only**:
- **Reminders:** Titles, dates, categories, recurrence settings, and photos you attach to reminders (stored in a local SQLite database and in the App's private storage)
- **Medications:** Medication schedules, frequencies, and end dates
- **Birthdays and anniversaries:** Dates with yearly recurrence
- **Routines, notes, and shopping lists:** The content you write in them
- **Preferences:** App settings like your name, notification style, alarm sound, quiet hours, and language (stored in the local database and in SharedPreferences)

This data never leaves your device unless you export or share it yourself, and it is deleted when you uninstall the App.

## Advertising

The free version of the App shows ads provided by **Google AdMob**. Users with Tita Pro do not see ads, and the App does not start the ads service for them.

To show and measure ads, Google AdMob may collect and process:
- The device's advertising ID
- Approximate location derived from the IP address
- Device and app information (model, operating system, language, app version)
- Ad interactions (impressions and taps)

This data is collected and processed by Google under its own policies, not by EgeaINC. Your reminders, medications, notes, and lists are never shared with AdMob.

- How Google uses information from apps that use its services: https://policies.google.com/technologies/partner-sites
- Google Privacy Policy: https://policies.google.com/privacy

**Your choices:**
- You can reset or delete your advertising ID, or opt out of personalized ads, in your device settings (Settings → Google → Ads, or Settings → Privacy → Ads, depending on the device).
- In the European Economic Area, the United Kingdom and Switzerland, the App asks for your consent before showing personalized ads, and you can change your choice at any time in Settings → Ad privacy.
- Tita Pro, a one-time purchase, removes all ads.

## Voice Input

The App offers optional voice input for creating reminders and notes. It uses your device's speech recognition service (usually provided by Google), which may process the audio on the device or on its servers under its own privacy policy. **The App does not record or store audio, and EgeaINC never receives it.** Only the resulting text is kept, inside the reminder or note you create.

## Photos and Text Recognition

You can create reminders from a photo (for example, a prescription or an appointment slip) and attach photos to reminders. Text in photos is read **on the device** using Google ML Kit. The first time, ML Kit may download a language model from Google; your photos and their text are not sent to EgeaINC or to Google. Photos you attach are stored only on your device.

## Device Calendar

If you turn on "Device calendar" in Settings, the App reads the events in your device's calendars to show them next to your reminders. The App does not change your calendar, and the events never leave your device.

## Sharing Reminders and Shopping Lists

When you share a reminder or a shopping list, the App creates a link that contains its content and lets you send it with the app you choose (WhatsApp, email, etc.). The content travels in the part of the link after the "#" sign, which browsers do not send to the server, so the page that opens the link (hosted on GitHub Pages) does not receive it. Whoever gets the link can see what you shared.

## App Lock

If you turn on the App lock, the App uses Android's own fingerprint, face, or screen lock check. The App never sees or stores your biometric data.

## Backup & Data Export

The App allows you to export your data as a backup file. You choose where to save it (your phone, Google Drive, etc.) using Android's file picker. **EgeaINC does not have access to your backup files.**

## Internet Usage

The App connects to the internet for:

1. **In-app purchases:** Processed entirely through Google Play Billing. When the App opens, it asks Google Play whether you own Tita Pro, so a reinstall or a new phone keeps it. We do not have access to your payment information. Google's privacy policy applies to these transactions.
2. **Ads (free version only):** Loading ads from Google AdMob, as described above.
3. **Updates:** Checking Google Play for a newer version of the App.
4. **Voice input and text recognition:** As described above, when you use them.

## Permissions

The App requests the following Android permissions:
- **Microphone:** Used for voice input. The App does not record or store audio.
- **Notifications:** Required to deliver reminder alerts at scheduled times.
- **Exact alarms:** Required to fire reminders at the precise time you set, even when the phone is in battery-saving mode.
- **Full-screen alerts and display over other apps:** Used to show the alarm screen when a reminder fires.
- **Foreground service, vibration, and wake lock:** Used to play the alarm sound and vibrate when a reminder fires.
- **Boot completed:** Required to reschedule your alarms after a phone restart.
- **Battery optimization exemption:** Requested to ensure alarms fire reliably on devices with aggressive battery management.
- **Calendar:** Used only if you turn on "Device calendar", to show your calendar events next to your reminders.
- **Biometrics:** Used only if you turn on the App lock.
- **Internet:** Required for in-app purchases, ads in the free version, and update checks.
- **Advertising ID:** Used by Google AdMob to show ads in the free version.

## Children's Privacy

The App is not directed at children under 13. It does not knowingly collect information from children.

## Changes to This Policy

We may update this Privacy Policy from time to time. Changes will be posted on this page with an updated revision date.

## Contact

If you have questions about this Privacy Policy, please open an issue at:
https://github.com/gabriel600r/tita-feedback/issues

---

*Tita — App de Recordatorios by EgeaINC*
