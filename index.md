---
title: Privacy Policy
description: Privacy Policy for the Gulf Card iOS app.
lang: en
text_direction: ltr
---

# Privacy Policy — Gulf Card

[العربية]({{ '/ar/' | relative_url }})

[Support]({{ '/support/' | relative_url }})

**Last updated:** July 19, 2026<br>
**Effective date:** July 19, 2026

This Privacy Policy explains how Gulf Card ("we," "us," or "the app"),
operated by Hamam Alabdulla, collects, uses, shares, retains, and protects
information when you use the Gulf Card iOS app. If you do not agree with this
policy, please do not use the app.

## 1. Information we collect

### Account and profile information

- **Account identifiers.** Firebase Authentication creates a unique user ID,
  including for guest accounts. If you use Sign in with Apple, Apple provides
  an account identifier and, depending on your choices, your name and either
  your email address or an Apple private relay address.
- **Profile information.** We may store the display name, country, language,
  and notification preferences you provide. Your display name and limited
  gameplay profile may be visible to other players.
- **Age verification.** You submit a date of birth to a secured Cloud Function
  to confirm that you meet the minimum age. We do not persist the raw date of
  birth. We store a SHA-256 hash created with a random per-user salt, along
  with the verification time. An under-minimum attempt may create a
  PII-free security event without the submitted date or its hash.

### Gameplay and integrity information

We process room membership, matches, cards and game actions, bids, scores,
leaderboard results, timestamps, move latency, and fairness-verification data.
We also process anti-cheat and abuse-prevention signals, including Firebase
App Check and limited device or network signals made available by our service
providers. The current app does **not** provide in-app chat, so we do not
collect chat messages.

### Purchases and advertising

- **App Store purchases.** Apple processes payment details. We receive and
  retain signed transaction identifiers, original transaction identifiers,
  product IDs, purchase and expiry dates, entitlement status, and refund or
  revocation events to deliver chips or subscriptions, prevent duplicate
  credits, and maintain accounting records. We do not receive your full card
  or bank-account details.
- **Advertising.** The app includes Google Mobile Ads, including rewarded-ad
  support. Google may process device, usage, and ad-interaction information
  under its terms and your consent choices. iOS App Tracking Transparency
  controls whether the advertising identifier (IDFA) is available for
  cross-app tracking. Denying permission prevents the app from granting that
  identifier to the advertising SDK.

### Device, diagnostics, and usage information

- **Notifications.** If enabled, we store an FCM registration token, an
  app-scoped device identifier, APNs environment, and notification preferences
  to deliver turn, invitation, and reward reminders.
- **Diagnostics and analytics.** Firebase Crashlytics and Firebase Analytics
  may process crash traces, diagnostics, device and app information, and usage
  events. Firebase Remote Config and App Check process technical information
  needed to configure and protect the app.
- **Network information.** Firebase and Google Cloud may temporarily process
  IP addresses, user-agent information, and request metadata to operate and
  secure their services.

### Apple Game Center

If you enable Game Center, Apple processes your Game Center identity and the
app submits scores and achievements. Game Center is governed by Apple's terms
and privacy policy.

We do not intentionally collect precise location, contacts, microphone audio,
or payment-card details.

## 2. How we use information

We use information to:

- authenticate users and maintain accounts;
- operate multiplayer and AI games and synchronize game state;
- provide wallets, purchases, subscriptions, rewards, and leaderboards;
- send notifications selected by the user;
- detect cheating, fraud, abuse, and security incidents;
- diagnose crashes, measure app performance, and improve features;
- provide advertising and measure ad delivery, subject to applicable choices;
- answer support and privacy requests; and
- comply with legal, accounting, and App Store obligations.

## 3. How we disclose information

We disclose information only as needed to:

- **Google and Firebase:** authentication, Firestore, Cloud Functions, Cloud
  Storage, Cloud Messaging, App Check, Remote Config, Analytics, Crashlytics,
  and Google Mobile Ads;
- **Apple:** Sign in with Apple, APNs, StoreKit/App Store purchases, and Game
  Center;
- **Other players:** display name, country or regional indicator, game actions,
  match results, and leaderboard information needed for social gameplay; and
- **Authorities or successors:** when required by law, to protect rights and
  safety, or as part of a business transfer subject to appropriate safeguards.

We require service providers that process user data for us to protect it in a
manner consistent with this policy and applicable requirements. We do not sell
personal information for money. Advertising-related transfers may be treated
as "sharing" under some laws; you can limit tracking through iOS privacy
settings and can contact us to exercise applicable rights.

Provider information:

- [Privacy and Security in Firebase](https://firebase.google.com/support/privacy/)
- [Google Privacy Policy](https://policies.google.com/privacy)
- [Apple Privacy Policy](https://www.apple.com/legal/privacy/)

## 4. Retention and deletion

We retain account and profile information while an account is active and only
as long as reasonably needed for the purposes described above. Gameplay,
security, and fairness records may be retained to operate the service, resolve
disputes, prevent abuse, and enforce game integrity. Notification tokens are
kept until replaced, disabled, or the account is deleted. Analytics,
diagnostics, and advertising data follow the applicable provider settings and
retention controls.

Purchase ledger records may be retained after account deletion when reasonably
necessary for fraud prevention, refunds, accounting, tax, or other legal
obligations. They are marked as belonging to a deleted user and are not used to
recreate the account. Temporary data-export files and download links expire.
Backups and provider systems may take additional time to complete deletion.

To delete your account in the app, open **Profile → Danger Zone → Delete
Account** and confirm. This removes the Firebase account and profile tree,
notification tokens, private wallet data, App Store ownership mappings,
avatars and pending export files, removes waiting-room membership, and
anonymizes applicable active-match references. Apple purchase records subject
to legal retention are handled as described above. You may also contact us at
the email below.

## 5. Your choices and rights

Depending on where you live, you may have rights to access, correct, export,
delete, restrict, or object to processing of your personal information, and to
withdraw consent where processing relies on consent.

You can:

- edit supported profile and notification settings in the app;
- disable notifications in the app or iOS Settings;
- change tracking permission in iOS Settings;
- request an export through the available in-app privacy flow; and
- delete your account using the in-app process described above.

For any request you cannot complete in the app, email
[hamam@gccapp.com](mailto:hamam@gccapp.com). We may need to verify your
identity before completing a request.

## 6. International processing

Our providers operate globally. Information may be processed in countries
other than your own, including the United States, where Firebase Authentication
and our `us-central1` Cloud Functions operate. Where required, transfers are
handled using contractual or other legally recognized safeguards.

## 7. Children and age restriction

Gulf Card is intended for users aged 17 and older. If a submitted date of birth
indicates that the user is under 17, access is blocked. If you believe that we
have collected personal information from someone under 17, contact us so we
can investigate and delete it as appropriate.

Virtual chips have no cash value and cannot be redeemed, transferred for
currency, or used outside the app.

## 8. Security

We use measures designed to protect information, including HTTPS/TLS,
Firebase Authentication, App Check, server-authoritative game logic,
restricted Firestore and Storage rules, access controls, and encryption
provided by Google Cloud. No method of storage or transmission is completely
secure, so we cannot guarantee absolute security.

## 9. Changes to this policy

We may update this policy when the app, providers, or legal requirements
change. We will publish the revised version here and update the date above.
Where required, we will provide additional notice or request consent.

## 10. Contact

For privacy questions, requests, or complaints:

**Email:** [hamam@gccapp.com](mailto:hamam@gccapp.com)

This English policy and the [Arabic version]({{ '/ar/' | relative_url }})
describe the same practices. If a translation differs, the English version
controls to the extent permitted by applicable law.
