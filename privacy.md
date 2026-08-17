---
title: Privacy Policy
---
# Privacy Policy — Phosphor Arcade

**Last updated: 17 August 2026.** Applies to Phosphor Arcade
(`io.github.nukareddy.phosphor`), version 0.3.0 and later, distributed on Google
Play.

## The short version

Phosphor Arcade does not collect anything about you. There are no accounts, no
sign-in, no analytics, no crash reporting, and no code in this app that sends
your information anywhere.

The app does show ads. The Google Mobile Ads SDK that serves them does collect
information — your advertising ID, your IP address, and how you interact with
the ads — and shares it with Google. All of the data collection connected to
this app is Google's, done through that SDK, and it is described below.

## What the app stores on your device

Phosphor Arcade keeps one file in its own private storage area, which no other
app can read:

| What is stored | Why |
|---|---|
| Your settings — sound, haptics, scanlines, glow level, chill mode | So the app opens the way you left it |
| Your best score for each of the seven games | To show your personal best |
| Daily streak, runs played today, runs played in total | For the streak display and the ad pacing rules |
| Which one-time hints you have already seen | So the app stops repeating them |
| Whether the ad-free entitlement is set | To suppress ads if it is |

This file never leaves your device. It is not backed up to us, because there is
no "us" to back it up to — no server exists. Android removes it when you
uninstall the app.

None of it identifies you. There is no name, email address, phone number,
location, contact list, photo, file, or device identifier in it.

## What Google collects through the ads

Ads in Phosphor Arcade are served by the Google Mobile Ads SDK
(`play-services-ads`, version 23.6.0). Google publishes the list of what that
SDK collects and shares automatically, and this is that list:

| What Google collects | What it is |
|---|---|
| **Advertising ID** | The resettable identifier Android provides for advertising. The app declares `com.google.android.gms.permission.AD_ID` so the SDK can read it. |
| **App set ID** | An identifier that groups apps from the same developer on one device. |
| **IP address** | Used, among other things, to estimate your general location. |
| **User product interactions** | App launches, taps, and video views, as observed by the ads SDK. |
| **Diagnostic information** | Performance measurements such as launch time, hang rate, and energy usage. |

Google uses all of the above for **advertising, analytics, and fraud
prevention**, and states that it is encrypted in transit using TLS.

The app also declares `ACCESS_ADSERVICES_AD_ID`, `ACCESS_ADSERVICES_ATTRIBUTION`
and `ACCESS_ADSERVICES_TOPICS` — the Android Privacy Sandbox APIs Google uses to
select and measure ads without tracking you across apps.

This data is collected by Google, shared with Google, and handled under Google's
own policies, not ours. We never receive any of it. We can see aggregate
earnings in the AdMob dashboard; we cannot see anything about you.

Google's handling of it is described here:

- Google Privacy Policy — https://policies.google.com/privacy
- How Google uses information from sites or apps that use our services —
  https://policies.google.com/technologies/partner-sites

## Your choices

- **Reset or delete your advertising ID.** Android Settings → Privacy →
  Ads. You can reset the ID or delete it entirely, which stops apps from
  receiving one.
- **Delete everything the app stored.** Uninstalling Phosphor Arcade removes its
  saved file and all of your scores. Android Settings → Apps → Phosphor Arcade →
  Storage → Clear data does the same without uninstalling.

## Permissions, and why each one exists

Every permission the installed app holds, and what it is for:

| Permission | Why |
|---|---|
| `INTERNET`, `ACCESS_NETWORK_STATE` | Requesting ads. Nothing else in the app uses the network. |
| `VIBRATE` | Haptic feedback on taps and game events. You can turn haptics off in Settings. |
| `com.google.android.gms.permission.AD_ID` | The advertising ID, used by the ads SDK. |
| `ACCESS_ADSERVICES_AD_ID`, `ACCESS_ADSERVICES_ATTRIBUTION`, `ACCESS_ADSERVICES_TOPICS` | Android Privacy Sandbox ad-services APIs, used by the ads SDK. |
| `WAKE_LOCK`, `FOREGROUND_SERVICE` | Declared by the Google Mobile Ads SDK. The app's own code does not use them. |

The app requests no runtime permissions. It never asks for camera, microphone,
location, contacts, photos, or files, because it does not use any of them.

## Children

Phosphor Arcade is not directed at children. It is a general-audience arcade
game and shows advertising served with the standard, non-child-directed
configuration. We do not knowingly collect information from children.

## Changes to this policy

If this policy changes, the updated version will be posted at this address and
the date at the top will change. Material changes will also be noted in the
app's release notes on Google Play.

## Contact

Questions about this policy: **nukareddy@gmail.com**
