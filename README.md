# Gulf Card — Privacy Policy

Public Privacy Policy for the **Gulf Card** iOS app
([App Store listing](https://apps.apple.com/) — added at App Store launch).

This repository is the canonical source for the policy text and is
served at:

- <https://qtrcipher.github.io/gulf-card-privacy/>

## Why a separate repo?

The privacy policy is a public legal document with its own update cadence
and audit trail. Keeping it in a dedicated repo (rather than buried inside
the main `gulf-card` codebase) means:

1. The URL stays stable across app versions.
2. Changes to the policy land via standard PR review without forcing an
   app rebuild.
3. The commit history of the policy is the authoritative record of what
   was in force on any given date — important for Saudi PDPL, GDPR, and
   App Store Connect compliance audits.

## Updating the policy

1. Edit `index.md`.
2. Update the "Last updated" date at the top.
3. Open a PR.
4. After merge, GitHub Pages auto-redeploys at the URL above.
5. If the change is **material** (new data category, new third-party
   service, scope change), trigger an in-app notification per the
   policy's "Changes to This Policy" section.

## License

The policy text is © Hamam Alabdulla. All rights reserved.
