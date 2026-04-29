---
title: Privacy Policy
lang: en
---

# Privacy Policy — Gulf Card

**Last updated:** 2026-04-29
**Effective date:** 2026-04-29

[العربية](ar/) · English

---

This Privacy Policy explains how **Gulf Card** ("we", "us", "the app")
collects, uses, and protects your information when you use the iOS app.
Gulf Card is operated by Hamam Alabdulla, based in Saudi Arabia. By using
the app you agree to the practices described in this policy.

## 1. Information we collect

### From you, when you sign in or play

- **Account identifier (UID).** When you launch the app for the first
  time, Firebase Authentication issues an anonymous UID. If you sign in
  with **Sign in with Apple**, the UID is linked to your Apple ID. The
  UID is the only identifier we use to associate your gameplay with you.
- **Email address.** Optional. If you choose Sign in with Apple, you can
  share your real email or use Apple's "Hide My Email" relay. We never
  see your real email if you choose to hide it.
- **Display name.** A name of your choosing, shown to opponents at the
  table and on leaderboards. You can change it any time in Profile.
- **Country.** A coarse country code (e.g. SA, AE) you select in Profile.
  We use it for matchmaking pools and regional content; we do not collect
  precise location.
- **Date of birth (hash only).** When you sign up we ask your date of
  birth to confirm you're at least 17. The raw date is never stored —
  only a SHA-256 hash with a per-user salt, used to verify the same DOB
  is presented in case of disputes. The raw value never leaves your
  device.

### From your gameplay

- **Match data.** Every move you make is sent to our server-authoritative
  game engine (deals, bids, plays, scores, declarations). This is
  necessary for the game to function — without it the server cannot
  determine whether your moves are legal.
- **Chat messages.** Optional in-room and club chat. Messages pass
  through a profanity filter and rate limiter before being saved.
- **Reports you submit.** When you report another player's chat message,
  display name, or club name, we store the report (target, reason,
  timestamp, your UID) for moderation review.
- **Audit log.** For anti-cheat and anti-collusion analysis, we record
  per-move metadata (seat, move type, latency, timestamp). This log is
  never shown to other players.
- **Purchase history.** When you buy a chip pack or a VIP subscription
  through the App Store, we record the transaction ID, amount, and the
  resulting chip / VIP grant.

### From your device

- **Push notification token (FCM).** If you opt in to notifications, we
  store an FCM token so we can send you turn-your-move alerts and match
  invites. You can revoke at any time in iOS Settings → Notifications.
- **Crash reports.** Firebase Crashlytics collects stack traces and
  device model when the app crashes. No personally identifying
  information is included unless you explicitly add it via in-app
  feedback.
- **Analytics events.** Firebase Analytics records aggregate usage
  events (screen views, button taps) without personal identifiers.

### From third-party SDKs (with your consent)

- **AdMob attribution.** If you grant App Tracking Transparency consent
  when prompted, AdMob may receive a device identifier (IDFA) for ad
  attribution. If you decline, AdMob serves only non-personalized ads
  and we do not transmit any device identifier.
- **Apple Game Center.** If you sign in to Game Center, Apple shares
  your stable Game Center player ID with us so we can post your scores
  to leaderboards. Game Center is optional and you can opt out in
  Profile → Game Center.

## 2. How we use your information

- **To run the game.** Match data, audit logs, and the UID are all used
  to enforce the game's rules server-side, deal cards via our
  provably-fair shuffle, and prevent cheating.
- **To communicate with you.** Push notifications you opted into,
  account-related emails (account deletion confirmations, etc.).
- **To improve the app.** Crashlytics + Analytics tell us where the app
  crashes or where users drop off in flows; we use this to fix bugs.
- **To deliver ads.** AdMob serves ads. Personalized ads only with
  your ATT consent; otherwise, generic ads only.
- **To process payments.** Apple processes the actual payment; we
  receive only the transaction ID and the SKU you bought.
- **To moderate user content.** Profanity filter, length cap, rate
  limiter, and the user-report flow described above.
- **To comply with law.** We respond to lawful requests from authorities
  and preserve information when required.

We do not sell your personal information.

## 3. Sharing your information

We share data only with:

- **Service providers.** Firebase (Google) for authentication,
  database, push notifications, crash reporting, analytics, and remote
  config. AdMob (Google) for advertising. Apple for App Store payments
  and Game Center. These providers process data on our behalf under
  their own contracts and certifications.
- **Other players you choose to play with.** Your display name,
  country, and bot-or-human flag are visible to opponents at the table.
- **Authorities, when required by law.** Subpoenas, court orders, or
  similar instruments compel disclosure.

## 4. Your rights

If you are in **Saudi Arabia**, the **Personal Data Protection Law
(PDPL)** grants you these rights:

- **Right to be informed** about the processing of your data (this policy).
- **Right to access** the data we hold about you.
- **Right to rectification** of inaccurate or incomplete data.
- **Right to erasure** (account deletion).
- **Right to data portability** (export your data in machine-readable
  format).
- **Right to object** to processing for non-essential purposes.

If you are in the **European Economic Area** or the **United Kingdom**,
the **GDPR / UK-GDPR** grants you the same set of rights, plus the
right to lodge a complaint with your supervisory authority.

If you are in **California**, the **CCPA / CPRA** grants you the right
to know, delete, correct, and opt out of "sale" — though we do not sell
personal information.

To exercise any of these rights, use the in-app flows in
**Profile → Privacy**:

- **Export your data** — generates a downloadable archive within 30
  days.
- **Delete your account** — cascades deletion across Firebase Auth,
  Firestore, and Cloud Storage. The deletion is final.

For inquiries the in-app flows don't cover, contact us at the address
in section 12.

## 5. Data retention

| Data category | Retention period |
|---|---|
| Active account profile | Until you request deletion |
| Match state (live) | Cleared at match end, except for shuffle proofs (see below) |
| Shuffle proofs (`/shuffleProofs/`) | 90 days post match-end (provably-fair audit) |
| Audit log (anti-cheat) | 90 days post match-end |
| Crash logs (Crashlytics) | 90 days (Firebase default) |
| Analytics events | 14 months (Firebase default) |
| Purchase records | 7 years (tax / legal retention) |
| Deleted account residue | Up to 90 days for anti-fraud, then irreversibly deleted |

## 6. International data transfers

Firebase and AdMob are operated by Google in data centers worldwide.
Your data is currently primarily processed in Google Cloud's
**`us-central1`** region. We will migrate to **`me-central1`** (Saudi
Arabia / UAE) when that region becomes generally available for
Firestore.

For transfers out of the European Economic Area we rely on the
**EU-US Data Privacy Framework** (where applicable) or **Standard
Contractual Clauses (SCCs)** approved by the European Commission.

## 7. Age restriction (17+)

Gulf Card is rated **17+**. We collect a date of birth at sign-up to
verify you meet this minimum. If you indicate you are under 17, your
sign-up is blocked and no account is created.

The app uses **virtual chips** for in-game wagering. Chips have **no
real-money value** — they cannot be cashed out, traded for currency,
or used outside the app. There is no real-money gambling.

## 8. Children's privacy

Gulf Card is not directed at children under 17. We do not knowingly
collect personal data from anyone under that age. If we discover that
data has been collected from a person under 17, we will delete it and
the associated account.

If you are a parent or guardian who believes your child has provided
us data, please contact us at the address in section 12.

## 9. Security

- All network traffic uses **HTTPS / TLS**.
- Authentication relies on **Firebase Authentication** with **Apple's
  Sign in with Apple** as the only third-party provider.
- **Firebase App Check** verifies that requests originate from the
  legitimate Gulf Card app, blocking impersonation and abuse.
- Game logic is **server-authoritative** — a malicious client cannot
  cheat by tampering with local state.
- The provably-fair shuffle uses **SHA-256 commitment-reveal** — you
  can independently verify every hand was dealt fairly via the
  "Verify this hand" UI.
- Data at rest in Firebase Cloud Firestore and Cloud Storage is
  **encrypted by default** by Google.

No system is perfectly secure. If you believe your account has been
compromised, please contact us immediately.

## 10. Cookies and similar technologies

Gulf Card does not use browser cookies. The app stores small amounts
of preference data (theme, language, hand-sort preference, feature
flags) in **iOS UserDefaults** — this storage never leaves your device.

## 11. Changes to this policy

We will post any change here, update the "Last updated" date at the
top, and — for changes that materially expand what data we collect or
how we use it — show an in-app notification at next launch with a
summary of the change. By continuing to use the app after a change you
accept the updated policy.

## 12. Contact / Data Protection Officer

For privacy questions, requests, or complaints:

- **Email**: <dpo@gulfcard.app>
- **Subject line**: include "PDPL", "GDPR", or "CCPA" if applicable so
  we can route faster.

We aim to respond to data-rights requests within **30 days**.

---

This policy is published in **Arabic** (primary) and **English**
(secondary). If the two versions differ in meaning, the
[Arabic version](ar/) controls.
