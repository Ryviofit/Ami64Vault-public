---
layout: default
title: Ami64Vault Support
permalink: /support/
---

# Ami64Vault Support

Ami64Vault is a local-first Commodore 64 and Amiga library and emulator
frontend for iPhone and Android. This page covers the current version 1.0
release candidate.

## Contact

[Open a support issue](https://github.com/Ryviofit/Ami64Vault-public/issues)

GitHub issues are public. Do not include personal information, commercial
games, proprietary firmware, passwords, signing keys or other confidential
files. See the [privacy policy](../privacy/).

## Information to include

Include the following without attaching copyrighted game or firmware files:

- phone model and operating-system version;
- Ami64Vault version and build number from **Settings > About**;
- whether the game is C64 or Amiga and its file extension;
- the exact error message and the steps that produced it;
- whether the problem also occurs after closing and reopening the app.

## Common checks

- **A game does not start:** Open **Settings > Firmware & ROMs** and review the
  installed firmware. C64 can use the optional pinned MEGA65 OpenROMs set or a
  legally obtained custom set. Amiga can use built-in AROS test mode or a
  supported, legally obtained Kickstart.
- **A ZIP does not import:** The archive must contain a supported C64 or Amiga
  game file. Password-protected, damaged, oversized or ambiguous archives are
  rejected for safety.
- **Controls do not respond:** Try both C64 joystick ports. For Amiga, confirm
  whether the game expects joystick or mouse mode.
- **An Amiga game requests another disk:** Use the disk selector in the
  emulator controls. Multi-disk imports are grouped and sorted automatically.
- **Android audio is quiet:** Raise the phone's media volume and try the
  optional in-app audio boost. Disable the boost if a particular game sounds
  distorted.

## Backups and older development builds

Library backups include games, multi-disk sets and edited titles. They exclude
firmware and emulator saves. Before removing an older development build,
export its library backup and verify that it restores into the permanent
`no.articom.ami64vault` app. Keep the older app until the restored library has
been checked.

Uninstalling an app removes its private local data. Ami64Vault does not operate
a cloud backup service and cannot recover files that were not exported by the
user.
