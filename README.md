# Bubbler-mobileapp

Mobile wrapper application for **Bubbler Admin** ([https://bubblerapp.tectangle.com/login](https://bubblerapp.tectangle.com/login)).

## Overview
- **App ID (Bundle ID):** `com.bubbleradmin`
- **App Name:** `Bubbler Admin`
- **Target URL:** `https://bubblerapp.tectangle.com/login`
- **Framework:** Capacitor 6 (iOS & Android)
- **CI/CD:** Codemagic (`codemagic.yaml`)

## Codemagic Workflows
- `bubbler-admin-ios-release`: Automatically builds signed `.ipa` and submits to TestFlight / App Store Connect.
- `bubbler-admin-ios-adhoc`: Builds `.ipa` for direct ad-hoc internal testing.
