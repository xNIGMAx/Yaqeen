---
permalink: /privacy/
---

# Privacy Policy For Yaqeen App (iOS)

This Privacy Policy describes how the Yaqeen mobile application ("Yaqeen," "we," "our") handles information when you use the app. Yaqeen is designed as a **privacy-first** app: your data stays on your device. **Anonymous analytics** — Yaqeen uses Firebase Analytics (by Google) to collect anonymous, aggregated usage events (for example, that an onboarding step or reflection session was completed). These events are **not linked to your identity**, contain no personal data, and are **not used for advertising or cross-app tracking**. No accounts, names, contacts, or message content are ever collected. See Google's privacy information at https://firebase.google.com/support/privacy.

If you have questions about this policy, contact us at the support email listed on the App Store listing for Yaqeen.

---

## Summary

- **No accounts** — you do not sign in to use Yaqeen.
- **No Yaqeen servers** — we do not receive or store your personal data on our own backend.
- **Anonymous analytics** — Yaqeen uses Firebase Analytics (by Google) to collect anonymous, aggregated usage events (for example, that an onboarding step or reflection session was completed). These events are **not linked to your identity**, contain no personal data, and are **not used for advertising or cross-app tracking**. See Google's privacy information at https://firebase.google.com/support/privacy.
- **On-device storage only** — settings, prayer activity, reflections, and related data are stored locally on your iPhone (and shared only with Apple system components and Yaqeen’s own app extensions on the same device, as described below).
- **You can delete everything** — Settings → Privacy → **Reset Yaqeen** removes local app data and returns you to onboarding.

---

## Information stored on your device

Yaqeen stores the following types of data **only on your device** (using Apple’s SwiftData and a secure App Group shared between the main app and its extensions). **None of this data is sent to Yaqeen or to any server we operate.**

| Data                                                 | Purpose                                                                                                                                         | Leaves your device? |
| ---------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------- | ------------------- |
| **User settings**                                    | Language, notification preferences, prayer setup, reflection options, onboarding progress, optional display name                                | No                  |
| **Prayer events**                                    | Records when prayer-window reminders were shown, when you confirmed prayer (“I prayed”), or dismissed prompts — used for in-app experience only | No                  |
| **Reflection events**                                | Your reflection sessions and progress through bundled content                                                                                   | No                  |
| **Content progress**                                 | Which reflection or trivia items you have seen or completed                                                                                     | No                  |
| **Prayer location**                                  | Coordinates and a label you provide (or derive from location) to calculate prayer times locally                                                 | No                  |
| **App selection for prayer shield**                  | Opaque tokens from Apple’s Family Activity picker representing apps/categories you chose to pause during prayer windows                         | No                  |
| **App selection for reflection shield** (if enabled) | Separate opaque tokens for apps you chose for reflection-mode pauses                                                                            | No                  |
| **Dhikr counter**                                    | Daily and lifetime tap counts and cycle state for the Dhikr widget and in-app counter                                                           | No                  |
| **Schedule data**                                    | Your enabled prayer windows and related scheduling configuration                                                                                | No                  |

Yaqeen does **not** export this data in v1.0. There is no “download my data” server endpoint because there is no server.

### Family Activity (Screen Time) tokens

When you pick apps to shield, Apple provides **opaque tokens** — not app names readable by Yaqeen outside Apple’s picker UI. Yaqeen stores those tokens locally to apply shields during your configured prayer (and optional reflection) windows. We cannot see your full app list or browsing history.

### Bundled content

Quranic reflections, Adhkar, trivia, and similar content are **bundled inside the app**. Reading or completing them does not send usage reports to us.

---

## Permissions and how they are used

Yaqeen may ask for the following **optional or feature-specific** permissions. You can deny any optional permission and still use other parts of the app.

### Screen Time / Family Controls (required for prayer shields)

- **What it is:** Apple’s Family Controls APIs, used **only** to pause apps **you select** during **prayer windows you configure**.
- **What it is not:** Not parental controls, not monitoring of other people, and not blocking apps outside your prayer windows.
- **If denied:** Prayer shields will not work; you may see guidance to grant access or continue without prayer mode.

### Location (optional — prayer times)

- **When asked:** When you set up prayer times or update location in settings.
- **Use:** Compute adhan/prayer times **on your device** using your coordinates or chosen location.
- **Not used for:** Tracking your movements, advertising, or sending location to our servers (we have none).

### Notifications (optional)

- **When asked:** When you turn on a notification type (e.g., prayer reminders, reflection nudges, Azkar, daily trivia).
- **Use:** **Local notifications** scheduled on your device. Yaqeen does not use a push notification server.

Yaqeen does **not** request access to the camera, microphone, contacts, calendar, photos, HealthKit, or Bluetooth in v1.0.

---

## What we do not collect

We do **not** collect, and Yaqeen is not built to transmit to us:

- Email addresses or passwords (no accounts)
- Name or identity beyond an optional **preferred name** you type in Settings (stored only on device)
- Advertising identifiers
- Personally-identifying analytics or usage events sent to third-party services
- Crash reports sent to third-party crash reporters
- Payment or purchase history (no in-app purchases in v1.0 as described in this policy’s effective version)
- Screen-time or app-usage reports uploaded to our servers
- Messages, contacts, or media from other apps

---

## App extensions and widgets

Yaqeen includes Apple-approved **app extensions** (for example, Screen Time shield UI, activity monitoring, and home/lock screen widgets). These extensions run on your device and read/write only to the same **App Group** storage as the main app so features like prayer shields and the Dhikr counter work consistently. This sharing does not send data off your device to Yaqeen.

---

## Children

Yaqeen is not directed at children under 13, and we do not knowingly collect personal information from children. Because we do not operate accounts or collect data on our servers, we do not receive child data from the app. If you believe a child has provided information in the app on a device, you can remove it with **Reset Yaqeen** on that device.

---

## Your choices and control

- **Change permissions:** iOS Settings → Yaqeen (or Screen Time / Notifications / Location as applicable).
- **Change app selections:** Re-open the in-app app picker for prayer or reflection shields.
- **Delete all app data:** Settings → Privacy → **Reset Yaqeen**. This deletes schedules, reflections, prayer events, Dhikr history, settings, and related local data, and cannot be undone. It does not uninstall the app.
- **Uninstall:** Deleting the app from your device removes the app and its local data from that device.

---

## Data retention

Data remains on your device until you reset the app, uninstall Yaqeen, or erase the device. We do not retain copies on our servers because we do not receive your data.

---

## Legal bases and international users

Because Yaqeen does not process personal data on our servers, traditional “data controller” obligations for a remote database largely do not apply to us. You remain in control of the data on your device through iOS and the in-app reset option. If you use Yaqeen in the European Economic Area, United Kingdom, or other regions with privacy laws, your primary rights are exercised on-device (access via the app, deletion via reset) and through Apple’s platform settings.

---

## Security

Data is protected by **your device’s security** (passcode, Face ID, Touch ID, encryption at rest provided by iOS). Yaqeen does not transmit your stored information to our own backend. Keep your device secure and do not share your unlock credentials with others if you wish to keep your Yaqeen data private.

---

## Third parties

- **Apple Inc.** — Yaqeen is distributed through the App Store and uses Apple frameworks (Screen Time, notifications, location, widgets). Apple’s privacy practices are governed by [Apple’s Privacy Policy](https://www.apple.com/legal/privacy/).
- **TestFlight** — If you participate in beta testing, Apple processes distribution and feedback according to Apple’s terms.
- **Firebase Analytics (Google)** — Yaqeen uses Firebase Analytics to collect anonymous, aggregated usage events (for example, that an onboarding step or reflection session was completed). These events are not linked to your identity, contain no personal data, and are not used for advertising or cross-app tracking. See https://firebase.google.com/support/privacy.

- **No other third-party data processors** — We do not integrate Mixpanel, Amplitude, advertising networks, or similar services in v1.0.

---

## Changes to this policy

We may update this Privacy Policy when the app changes (for example, new features or legal requirements). We will post the updated policy at the same URL and change the **Effective date** at the top. Continued use of Yaqeen after an update means you accept the revised policy.

---

## Contact

For privacy questions or requests related to Yaqeen, use the **support contact** listed on the App Store product page for Yaqeen. We will respond as reasonably possible.
