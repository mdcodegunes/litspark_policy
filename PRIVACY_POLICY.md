# Privacy Policy (LitSpark)

**Effective date:** 2025-12-28

LitSpark (“the app”) is a lightweight, offline-first app that shows short literary excerpts and lets you share them. This Privacy Policy explains what information is handled when you use the app.

## Summary

- **No account, no signup.** We do not require you to create an account.
- **Core content is offline.** Excerpts are loaded from a bundled JSON file included with the app.
- **Local-only app data.** Streak counters and a once-per-day ad gate are stored locally on your device.
- **Ads (mobile only).** On Android/iOS, the app uses Google AdMob (Google Mobile Ads SDK) to show interstitial ads. Google may collect device and usage information to deliver and measure ads.

## Information we collect

### Information you provide

- **We do not ask you to provide personal information** (such as your name, email address, phone number, or contacts) to use the app.

### Information stored on your device (local storage)

The app stores small pieces of data **only on your device** using `SharedPreferences`, such as:

- Your current reading **streak** (a number)
- The last day the app was opened (a day key)
- The last day an interstitial ad was shown (a day key)

This information is used solely to provide app features (streak display) and to limit ad frequency.

### Advertising data (Google AdMob)

If you use the app on **Android or iOS**, the app may show ads via **Google AdMob**.

- The app itself does not directly collect or store advertising identifiers.
- **Google (as an advertising provider) may collect information** such as device identifiers (e.g., Advertising ID), IP address, approximate location inferred from IP, app interaction data, and diagnostic information for purposes like ad delivery, measurement, frequency capping, fraud prevention, and reporting.

For details on how Google handles data, see Google’s policies:
- Google Privacy Policy: https://policies.google.com/privacy
- Google Advertising: https://policies.google.com/technologies/ads

## Information we share

- **We do not sell your personal information.**
- **We do not share personal information with third parties** except as needed to provide ads on mobile platforms through Google AdMob.

## Sharing features

When you tap Share, the app uses your device’s **system share sheet** (via `share_plus`) to send text or an image to another app **you choose** (e.g., Messages, email, social apps).

- For image sharing, the app creates a **temporary image file** in the device’s temporary directory. This file is used to attach the image to the share sheet.
- After you share, the temporary file may remain in the OS temporary cache until your device cleans it up.

## Children’s privacy

LitSpark is a general-audience app and is **not intended to be directed to children under 13**.

- We do not knowingly collect personal information from children under 13.
- If you are a parent or guardian and believe a child provided personal information to us, contact us and we will take appropriate steps.

**Important (for child-directed audiences):** If you choose to list the app as targeting children under 13, you may need to configure your advertising and app settings to comply with COPPA and Google Play’s Families / User Data policies (for example, restricting ad personalization). This policy describes current app behavior; ensure your runtime configuration matches your store declarations.

## Data retention

- Local streak/ad-gate data remains on your device until you clear the app’s storage or uninstall the app.
- Advertising-related data retention is governed by Google’s policies.

## Security

We use standard platform APIs. However, no method of storage or transmission is 100% secure.

## Changes to this policy

We may update this policy from time to time. We will update the “Effective date” at the top when changes are made.

## Contact

If you have questions about this Privacy Policy, contact:

- **Email:** [ADD_SUPPORT_EMAIL]
- **Developer/Publisher:** [ADD_DEVELOPER_NAME]
