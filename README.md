# Privacy Policy for Alarm Loud

**Last updated: June 18, 2026**

## Overview

Alarm Loud is a native iOS alarm clock application that helps you wake up with mission-based challenges. **We do not collect, transmit, or share any of your personal data.** Your privacy is built into the app by design.

## Data Collection

Alarm Loud **does not collect any data**. The app:
- Has **no analytics** or crash reporting SDKs
- Has **no advertising** or ad networks
- Has **no third-party SDKs** of any kind
- Does **not create an account** or require registration
- Does **not make any network requests**
- Does **not track you** across other apps or websites

## Permissions

Alarm Loud requests certain permissions only to deliver its core alarm and mission functionality:

| Permission | Purpose |
|---|---|
| **Notifications** | Delivering alarm alerts, snooze reminders, bedtime reminders, and wake-up check notifications |
| **Camera** | Used only when you create or complete a Photo, QR code, or Barcode wake-up mission |
| **Motion & Fitness** | Used only on-device while you complete Shake, Step, or Squat wake-up missions |
| **Background Audio** | Allows alarm sounds and sleep sounds to play when the app is in the background or device is locked |

All permissions are requested only when the relevant feature is first used. You can grant or revoke any permission at any time in your device's Settings.

## Local Data Storage

All data created by Alarm Loud is stored **exclusively on your device** using Apple's SwiftData framework (on-device SQLite). This includes:

- Alarm configurations (times, repeat days, labels, sounds, assigned missions)
- Mission configurations (math difficulty, photo reference images, QR/barcode values, step/shake targets)
- Sleep tracking records (bedtime, wake time, duration, quality rating)
- Alarm dismissal history (wake scores, dismiss durations, snooze counts)
- App preferences (theme, default snooze duration, dark mode)
- Bedtime reminder settings

**All of this data stays on your device.** It is never sent to us or anyone else.

## Photo Mission Privacy

When you use the Photo mission feature:
- The reference photo you register and photos taken during alarm dismissal are processed **entirely on-device** using Apple's Vision framework (`VNFeaturePrint`).
- Photos are **never uploaded** or transmitted anywhere.
- Reference photos are stored locally in your app's SwiftData database as external binary data.

## Motion Data Privacy

Motion data (accelerometer readings, step counts) is:
- Accessed **only while you are actively completing** a Shake, Step, or Squat mission
- Processed **entirely on-device**
- **Never recorded, stored, or transmitted**

## Data Deletion

You can delete all locally stored data at any time by going to:

**Settings → Privacy & Data → Delete All Local Data**

This removes all alarms, alarm history, sleep records, active sleep sessions, and reminders from your device.

## Children's Privacy

Alarm Loud does not collect any personal information from anyone, including children under 13. All data remains on the user's device.

## Changes to This Policy

If this privacy policy changes, the "Last updated" date at the top will be revised. Since the app does not collect data, changes will only reflect operational or regulatory clarifications.

## Contact
E-mail: ktnapps@gmail.com

## Third-Party Services

Alarm Loud uses **no third-party services**.

## Your Rights

Because we collect no data, there is nothing to access, correct, delete, or port from our servers. All your data is on your device and fully under your control.
