---
title: AS Authenticator Vault privacy policy
---

# AS Authenticator privacy policy

Effective 3 October 2026

AS Authenticator, by Ayala Solutions, generates two-factor authentication codes on your Mac, iPhone and iPad.

## What the app stores

The secrets you add, their names, sites and categories, and your settings. They are kept on your device in a vault encrypted with AES-256-GCM under a key derived from your master password with Argon2id. If you turn on biometric unlock, a copy of the master password is wrapped by a key in the device's Secure Enclave and stored in the device Keychain. Exported vault files are encrypted the same way.

## What the app sends

Nothing, unless you turn on one of two optional features in Settings, each described there:

- **Check the clock** asks timeapi.io for the current time about once an hour so codes stay correct when the device clock drifts. The request carries your IP address and nothing else.
- **Site icons from the web** (on by default; turn it off in Settings to stop and delete the cached icons) asks a site you have an account with for its icon, once, over HTTPS, without cookies or referrer. If that host serves no icon, the same request goes once to the organisation's main domain. That site learns that a device at your IP address asked for its icon.

The app has no account system, no analytics, no advertising, no crash reporting and no tracking.

## What we receive

Nothing. Ayala Solutions runs no server for this app and cannot see your vault, your secrets or your usage.

## Deleting your data

Settings > Delete everything removes the vault, backups, caches and Keychain items from the device. Deleting the app removes everything except the Keychain items, which Delete everything clears first.

## Children

The app is not directed at children under 13 and collects no information from anyone.

## Changes

If this policy changes, the new version is published at https://hov172.github.io/AS-Authenticator-Browser-Extensions/app-privacy with a new effective date.

## Contact

Ayala Solutions, ayala.solutions@gmail.com
