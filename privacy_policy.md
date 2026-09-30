# PingMe Privacy Policy

**App:** PingMe by AS-Tech Studios  
**Publisher:** AS-Tech Studios  
**Package:** `com.astechstudios.pingme`  
**Effective:** 30 September 2026  
**Version:** 1.0.2 (legal document v14)  
**Contact:** [flutterdev7861@gmail.com](mailto:flutterdev7861@gmail.com)  
**Website:** [https://astechstudios.com](https://astechstudios.com)  
**Hosted policy URL:** [https://astechstudios.com/pingme/privacy](https://astechstudios.com/pingme/privacy)

## Overview

PingMe is an Android anti-theft and device-protection toolkit for a phone you own or are authorized to manage. It processes data on your device so trusted phone numbers can text SMS commands to locate, lock, alert, or save local evidence after loss or theft.

This policy explains what PingMe handles, what stays on the device, and what may leave as plain-text SMS. PingMe does not create a PingMe cloud account, does not sell your data, and does not use advertising or analytics SDKs to profile you.

PingMe is for lawful personal or organizational anti-theft protection and recovery aid. It is not for secretly monitoring someone else’s phone without lawful authority and consent.

## Who can control this device

Only phone numbers you add under **Trusted** can trigger commands. Messages from any other number are ignored and do not receive helpful replies.

You choose which commands stay enabled. High-risk commands can require a **Command PIN** that you set under Settings → Security.

## Data processed on-device

Depending on the permissions and features you enable, PingMe may process:

- SMS command text from trusted numbers
- Device, network, and GPS details for Where, THEFT, SOS, and low-battery location / status replies
- Photos, screenshots, audio, screen video, and camera video you trigger (ASP, BASP, SS, REC / CREC, SREC / CSREC, VREC / VFREC / VBREC / CVREC, and SOS / THEFT evidence), stored locally in **Captures**
- App usage summaries for the CAL command (when Usage access is granted)
- Lock, SNP, RING / ALARM, and THEFT state while those features are active
- Trusted numbers, Command PIN (stored as a one-way hash), App Lock unlock PIN (secure on-device storage), biometrics-enabled preference, retention settings, and other preferences you configure
- Optional Device Owner enrollment status for USB charge-only and related THEFT hardware hardening

PingMe does not upload Captures, trusted-number lists, or PINs to a PingMe server.

## Captures stay on this device

Capture files remain in PingMe’s private Captures storage on this phone. PingMe:

- Does not upload Captures to a PingMe cloud
- Does not send Captures as MMS or email attachments
- Does not offer a share or export action from Captures

You can preview or delete Captures on this device. You may also enable automatic deletion of older Captures under Security settings.

## What leaves the device

The only routine outbound communication PingMe sends for these features is **plain-text SMS** to the trusted number that issued a command (or that you configured for alerts such as SIM change). Those SMS replies may include:

- Location / maps links and device or network snapshot text
- Command status (for example, that a capture was saved, or that lockdown is active)

Capture success replies confirm that a file was saved in Captures. They do **not** include media bytes or full filesystem paths.

SMS delivery uses your mobile carrier. Standard SMS is not end-to-end encrypted by PingMe.

If you open the hosted privacy page or website links in a browser, normal web traffic applies to that visit only.

## Sharing

We do not sell your personal data. Capture media stays on the device. SMS replies are delivered by your carrier only to the contact you trust. We do not share Captures or trusted-number lists with third-party analytics or advertising partners.

## Permissions

PingMe requests permissions only to power anti-theft and activity commands you enable. Sensitive permissions are explained in-app before you grant them (a first-time summary, then a Home trust line you can open again). You can revoke permissions in Android settings at any time.

| Permission | Why PingMe may need it |
|---|---|
| SMS | Receive commands from trusted numbers and send plain-text status / location replies |
| Phone | CALL-back replies and SIM / network identity for anti-theft alerts |
| Location (including background / Allow all the time) | Where, THEFT, SOS, and low-battery alerts when the app may be closed |
| Camera | ASP / BASP photos, SOS / THEFT evidence, and VREC camera video saved in Captures |
| Microphone | REC / CREC audio and VREC video audio saved in Captures |
| Notifications | Ongoing status for SNP, RING, THEFT, and capture services (Android 13+) |
| Device Admin | Lock and THEFT screen lock; SNP unlock policies |
| Accessibility | SNP panel lock, SS screenshots, THEFT volume-key block, lock-screen CALL controls |
| Notification access | Hide interrupting alerts while SNP is on |
| Do Not Disturb | Silence interruptions during SNP |
| Usage access | CAL app-usage summary replies |
| Battery unrestricted | Keep the SMS listener alive in the background |
| Screen capture | SREC screen recording after you approve Android’s cast prompt |
| Full-screen intent | Show the SREC Allow dialog when the app is in the background or the phone is locked (Android 14+) |

Related system capabilities (boot completed, wake lock, vibrate, modify audio settings, foreground services) support RING / THEFT / capture work and keeping the SMS listener alive.

Remote camera, microphone, and screen capture can run after a trusted SMS command and may show an ongoing notification while active. Media stays on-device.

## Biometrics

Optional fingerprint / face unlock is used only for **App Lock** (opening PingMe or protected screens such as Trusted, Captures, and Activity). PingMe uses Android’s BiometricPrompt. Biometric templates stay in the operating system and are **not** read, stored, or uploaded by PingMe. You can turn biometrics off anytime under Settings → App Lock.

## Security controls

You can:

- Set a Command PIN for high-risk SMS commands
- Enable App Lock with an unlock PIN and optional fingerprint / face unlock
- Protect Trusted, Captures, and Activity behind App Lock
- Use Minimal Where replies
- Auto-delete older Captures
- Clear THEFT lockdown with SAFE / UTHEFT from a trusted number

Home shows a reminder if a Command PIN is not set. SIM changes can alert your trusted numbers when that feature is available.

## Retention and deletion

Data stays on the device until you delete it or uninstall PingMe. You can:

- Remove trusted numbers
- Delete Captures in the Captures tab
- Disable individual commands
- Change or remove Command PIN and App Lock settings
- Revoke permissions in Android settings
- Clear app storage or uninstall PingMe

Doing so stops further processing for those features.

## Children

PingMe is not directed to children and is not intended for use by children.

## Changes

We may update this policy when features change. Material updates also appear in the in-app privacy notice and may require acceptance again before you continue using the app. The hosted URL above should match the latest published policy.

## Copyright

© 2026 AS-Tech Studios. PingMe is a product and trademark of AS-Tech Studios. All rights reserved. Not affiliated with any unrelated “PingMe” apps or brands.

## Contact

- Privacy: [flutterdev7861@gmail.com](mailto:flutterdev7861@gmail.com)
- Support: [flutterdev7861@gmail.com](mailto:flutterdev7861@gmail.com)
- Web: [https://astechstudios.com](https://astechstudios.com)
