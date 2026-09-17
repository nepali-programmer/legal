# Podly Privacy Policy

**Effective date:** 17 September 2026
**Applies to:** the Podly Android app (`com.podly`), all versions from 1.0.0

## Summary

Podly shows the battery, wear state and settings of wireless earbuds paired
with or near your Android phone. Everything it learns stays on the phone. Podly
has no account, no analytics, no crash reporting service and no network code of
any kind. It does not request the Android `INTERNET` permission, so it cannot
send anything anywhere even if a component tried.

## What Podly stores, and where

Everything below is stored in the app's private storage on your phone. Nothing
is sent to us or to anyone else.

- **Devices it has seen** — the Bluetooth address, the name, the model
  identifier and the colour reported by earbuds Podly has heard or that are
  paired with the phone, with the time each was first and last seen.
- **Battery history** — the battery readings of the earbuds you selected, with
  timestamps, kept for the number of days you choose in Settings (30 by
  default) and deleted after that.
- **Earbud settings** — the noise-control mode, press-and-hold actions, ear
  detection and other settings you configure for each pair, kept so Podly can
  re-apply them when the earbuds reconnect.
- **App preferences** — theme, pop-up card style, alert thresholds, scan mode,
  which device you selected and which nearby devices you chose to hide.

Podly does not store or read your contacts, messages, calls, media, browsing,
or the audio your earbuds play.

## Location

Podly never reads, stores or transmits your location. It declares Bluetooth
scanning with the `neverForLocation` flag, so on Android 12 and later it does
not ask for a location permission at all. On Android 10 and 11 the operating
system requires the fine-location permission before any app may scan for
Bluetooth devices; Podly requests it only for that reason and never calls any
location API.

## What leaves your phone

Nothing, with two exceptions that you control:

1. **Android backup.** If you have Android's app-data backup enabled for your
   Google account, the system may include Podly's stored preferences and
   history in that backup. This is handled entirely by Android and your Google
   account, not by Podly. You can exclude Podly in Android's backup settings.
2. **The troubleshooting summary.** The Troubleshooting screen has a button
   that copies a diagnostic summary to the clipboard so you can paste it into a
   bug report. It contains Bluetooth state, permission state, scan statistics
   and the Android build version. It does not contain serial numbers, your
   location or anything identifying you, and it goes only where you paste it.

## Bluetooth traffic

Podly listens to the short Bluetooth Low Energy broadcasts that some earbuds
send, and opens a control connection to earbuds paired with the phone in order
to read battery levels and change settings. This traffic is between your phone
and your own earbuds. Podly does not connect to earbuds that are not paired
with your phone, and it never transmits anything to a device other than the
earbuds you selected.

## Permissions and why they are needed

| Permission | Why |
| --- | --- |
| Bluetooth scan (`BLUETOOTH_SCAN`, flagged `neverForLocation`) | Hear the battery broadcast of nearby earbuds. |
| Bluetooth connect (`BLUETOOTH_CONNECT`) | Read the list of paired earbuds and open the settings connection to them. |
| Bluetooth / Bluetooth admin / fine location (Android 10–11 only) | The platform equivalents of the two above; Android below 12 requires location access to scan. Podly never reads a location. |
| Notifications (`POST_NOTIFICATIONS`) | The status-bar battery reading, low-battery alerts, and the pop-up card when it cannot draw over other apps. Optional. |
| Foreground service (`FOREGROUND_SERVICE`, `FOREGROUND_SERVICE_CONNECTED_DEVICE`) | Keep readings live and pause playback when you remove an earbud while the screen is off. |
| Run at start-up (`RECEIVE_BOOT_COMPLETED`) | Restart that service after a reboot, only if you finished set-up and granted Bluetooth access. |
| Display over other apps (`SYSTEM_ALERT_WINDOW`) | Show the pop-up card when you open your case. Optional; without it the card is a notification. |

Podly does not request the `INTERNET` permission.

## Third parties

Podly uses no third-party services, SDKs that collect data, advertising or
analytics. The only third-party code it contains is open-source libraries that
run entirely on the device.

## Children

Podly is not directed at children and collects no personal data from anyone.

## Deleting your data

Everything Podly stores is deleted when you uninstall the app, or when you use
Android's "Clear storage" for Podly. Battery history can also be cleared from
within the app. Because nothing is stored elsewhere, there is nothing else to
delete and no request you need to make.

## Changes to this policy

Material changes get a new effective date at the top of this page. The current
version is always at
<https://nepali-programmer.github.io/legal/podly/privacy.html>.

## Contact

Questions about this policy: <joshisijan96@gmail.com>
