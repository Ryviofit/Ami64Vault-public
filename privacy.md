---
layout: default
title: Ami64Vault Privacy Policy
permalink: /privacy/
---

# Ami64Vault Privacy Policy

Last updated: October 1, 2026

Ami64Vault is a local-first game library and emulator frontend. This policy
describes the current version of the app for iOS and Android.

## Data collection

Ami64Vault does not create user accounts and does not collect, sell or share
personal data. The current version contains no advertising SDK, analytics SDK
or tracking technology.

## Data stored on the device

Imported game files, firmware files, display names, library preferences and
emulator save data are stored locally in the app's private device storage.
They are not uploaded to the developer.

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
receive a copy of any downloaded file, URL or request.

## File access

When the user selects a local file, the operating system's file picker grants
access only to the selected file. Exporting or restoring a library backup also
uses the operating system picker for the user-selected destination or ZIP.
Ami64Vault does not scan unrelated files.

## Children

Ami64Vault does not knowingly collect personal information from children or
from any other user.

## Changes

This policy will be updated before adding accounts, cloud sync, advertising,
analytics or any other feature that changes the app's data handling.

## Contact

[Open a support or privacy issue](https://github.com/Ryviofit/Ami64Vault-public/issues)

GitHub issues are public. Do not include personal information, commercial
games, proprietary firmware, passwords, signing keys or other confidential
files.
