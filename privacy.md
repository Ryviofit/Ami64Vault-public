---
layout: default
title: Ami64Vault Privacy Policy
permalink: /privacy/
---

# Ami64Vault Privacy Policy

Last updated: October 2, 2026

Ami64Vault is a local-first game library and emulator frontend. This policy
describes the current version of the app for iOS and Android.

## Data collection

Ami64Vault does not create user accounts, operate an analytics service or send
the user's game library to the developer. The free version includes Google
Mobile Ads. Depending on the user's region, consent choices and device
settings, Google and its advertising partners may process information such as
IP address, device or advertising identifiers, ad interactions and diagnostic
information to provide, secure and measure advertising. Ami64Vault uses
Google's consent flow where required and provides an advertising privacy entry
point when the consent platform requires one. Ami64Vault requests only
non-personalized ads, removes Android advertising-ID and AdServices
permissions, disables Google's Android publisher first-party ID and disables
the iOS same-app key. The app does not request Apple's tracking permission.

The app shows no banner ads. After four completed game sessions, it may show a
full-screen ad before the next game starts, with a limit of two ads per local
calendar day and at least 30 minutes between ads. No ad is shown inside the
emulator, during import or during firmware setup. A non-consumable in-app
purchase permanently removes advertising on the store platform where it was
purchased.

Apple App Store or Google Play processes purchases and may process account,
payment, transaction and device information under its own privacy policy.
Ami64Vault receives the purchase result needed to unlock the ad-free feature;
the developer does not receive the user's payment-card details.

## Data stored on the device

Imported game files, firmware files, display names, library preferences and
emulator save data are stored locally in the app's private device storage.
They are not uploaded to the developer.

The app also stores the ad-free entitlement, completed-session counter, daily
ad counter and last-ad time locally. These values enforce the advertising
limit and are not uploaded to the developer.

When the user explicitly exports a library backup, Ami64Vault writes a ZIP to
the location selected by the user. That ZIP contains game files, multi-disk
sets and edited display names. It does not contain firmware, ROM files or
emulator save data. Restoring a backup reads only the ZIP selected by the user
and merges it into local app storage.

Users can remove individual games from the library. Uninstalling Ami64Vault
removes the app's private data according to the operating system's normal
uninstall behavior. A backup exported outside the app remains wherever the
user chose to save it until the user or storage provider removes it.

## Network access

Network access is used when the user chooses to import a game or firmware file
from a direct URL. The device then contacts the server identified by that URL.
That server may receive normal connection information such as the user's IP
address under the server operator's own privacy policy.

When the user explicitly selects **Install OpenROMs**, the device contacts
`raw.githubusercontent.com` and downloads three files from one pinned revision
of the MEGA65 OpenROMs project. GitHub may receive normal connection and
request information, including the user's IP address, under GitHub's privacy
policy. Ami64Vault verifies the exact file sizes and SHA-256 checksums before
installing the files locally.

Ami64Vault does not operate a backend service and the app developer does not
receive a copy of any downloaded file, URL or request. Network access is also
used to request consent information and advertising from Google and to connect
to Apple App Store or Google Play for purchases and purchase restoration.

## File access

When the user selects a local file, the operating system's file picker grants
access only to the selected file. Exporting or restoring a library backup also
uses the operating system picker for the user-selected destination or ZIP.
Ami64Vault does not scan unrelated files.

## Children

Ami64Vault is not directed to children. The developer does not knowingly
collect personal information from children. Advertising and store providers
may require additional age or audience configuration before publication.

## Changes

This policy will be updated before adding accounts, cloud sync, analytics or
any other feature that changes the app's data handling.

## Contact

[Open a support or privacy issue](https://github.com/Ryviofit/Ami64Vault-public/issues)

GitHub issues are public. Do not include personal information, commercial
games, proprietary firmware, passwords, signing keys or other confidential
files.
