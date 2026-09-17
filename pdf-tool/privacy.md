# CV Maker & PDF Editor — Privacy Policy

Effective 17 September 2026 · applies to all versions from 1.0.0

Published at https://nepali-programmer.github.io/legal/pdf-tool/privacy.html

## Summary

CV Maker & PDF Editor ("the app") makes CVs and edits PDFs entirely on your
phone or tablet. The documents you open, the PDFs it produces and the CVs you
write never leave your device. There is no account and no server of ours.

The app shows ads and collects anonymous usage and crash data through three
Google SDKs. Usage and crash reporting can be switched off in Settings, and ad
consent can be changed at any time. That is the whole of it; the rest of this
page is the detail.

## Who we are

The app is published by Nepali Programmer (Sijan Joshi), Nepal. Contact:
support@nepaliprogrammer.com.np.

## Your documents and CVs stay on the device

- **PDFs, images and Office files** you open are read and written on the
  device. No file, page, image or extracted text is uploaded anywhere. Text
  recognition (OCR) runs on the device through Google ML Kit's on-device
  model.
- **Outputs** are saved to a folder named "CV Maker & PDF" in your device's
  documents area. You can share, open or delete them from the Files tab or
  with any file manager.
- **CVs**, their photos and the app's settings are stored in the app's private
  storage. A CV backup is a file the app writes and hands to the share sheet;
  it goes only where you send it.
- **Recent files** is a list of paths on your device, kept locally so you can
  reopen work. It never contains file contents.

We never see any of this. The app has no way to send it to us.

## What is collected, and by whom

The app itself collects nothing. Three Google SDKs do, for the purposes in
this table.

| Service | What it receives | Why | Your control |
| --- | --- | --- | --- |
| Google AdMob (with the User Messaging Platform) | Advertising identifier, IP address, coarse device and app information, ad interactions | Serving and measuring ads, which fund the app | Consent prompt on the first ad of a session; "Privacy options" in Settings to change it; system-level ad-tracking controls |
| Firebase Analytics | Anonymous usage events: which tool ran, how long it took, file sizes and page counts, whether it succeeded, app version, device model, OS version, country | Understanding which features are used and where they fail | Settings → Privacy → "Share usage data" (on by default, off in one tap) |
| Firebase Crashlytics | Crash reports: stack trace, device model, OS version, app version, free memory, the name of the tool that was running | Finding and fixing crashes | Settings → Privacy → "Send crash reports" (on by default, off in one tap) |
| Firebase Remote Config | A Firebase installation identifier, app version, device locale | Fetching configuration such as ad pacing and the CV design pack; nothing about you is stored | None needed; it carries no personal data |

Analytics events never include file names, file paths, document content,
CV content or anything you typed. They carry tool identifiers, sizes, counts
and durations only.

Each of these is a Google service governed by Google's own privacy policy at
https://policies.google.com/privacy. Google acts as a processor for analytics
and crash reporting and as an independent controller for advertising.

## Advertising

The app is free and funded by ads: banner, native and interstitial units
served by Google AdMob.

- Before the first ad of a session, and after you have seen the app's own
  privacy notice, Google's consent form may be shown where the law requires
  it (EEA, UK, Switzerland, and US states with applicable laws).
- If you decline personalised ads, or your region gives no consent, ads are
  still shown but are non-personalised: they are chosen from context rather
  than from your advertising identifier.
- You can change your choice at any time from Settings → Privacy → "Privacy
  options".

### On iOS: App Tracking Transparency

On iOS the app asks for tracking permission through Apple's App Tracking
Transparency prompt before the first personalised ad. Declining changes one
thing: ads become non-personalised. Every feature of the app works the same
either way.

## Permissions

| Permission | Used for | Required? |
| --- | --- | --- |
| Photos / media | Picking images to convert to PDF, and choosing a CV photo | Only when you pick a photo |
| Camera | "Scan to PDF" | Only when you tap Scan |
| Files (system picker) | Choosing PDFs and documents to work on | Only when you pick a file |
| Network | Ads, analytics, crash reports, Remote Config | Everything else works offline |

The app does not request location, contacts, microphone or notification
permissions.

## Children

The app is not directed at children under 13 and does not knowingly collect
data from them. The store listings are rated for a general audience of 13+.

## Retention and deletion

- Data on your device — CVs, outputs, settings, recent files — is deleted when
  you uninstall the app, or earlier by you from within the app or a file
  manager.
- Analytics data is held by Google for the retention period set in the
  Firebase project (at most 14 months) and crash reports for 90 days, then
  deleted. Turning either toggle off stops new collection immediately.
- Advertising data is retained under Google's advertising policies. You can
  reset your advertising identifier in your device's system settings.

To exercise a data right (access, deletion, objection) under GDPR, the UK
GDPR, the CCPA or a similar law, write to support@nepaliprogrammer.com.np.
Because the data the SDKs collect is not linked to you by name, we will
usually ask for your advertising identifier or Firebase installation id to
locate it.

## Security

Everything the SDKs send travels over TLS. Your documents never travel at all.
Nothing in the app is encrypted at rest beyond what your device does, so the
usual advice applies: lock your device, and treat a CV backup file as you
would the CV itself.

## Changes

Material changes to this policy get a new effective date at the top of this
page and a note in the app's release notes. The URL never changes.

## Contact

support@nepaliprogrammer.com.np
