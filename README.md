# Gulf Card — Privacy Policy

Public Privacy Policy for the **Gulf Card** iOS app in English and Arabic
([App Store listing](https://apps.apple.com/) — added at App Store launch).

This repository is the canonical source for the policy text and is
served at:

- English: <https://qtrcipher.github.io/gulf-card-privacy/>
- العربية: <https://qtrcipher.github.io/gulf-card-privacy/ar/>

## Why a separate repo?

The privacy policy is a public legal document with its own update cadence
and audit trail. Keeping it in a dedicated repo (rather than buried inside
the main `gulf-card` codebase) means:

1. The URL stays stable across app versions.
2. Changes to the policy land through Git history without forcing an
   app rebuild.
3. The commit history records what was in force on any given date for
   privacy and App Store Connect compliance review.

## Updating the policy

1. Edit both `index.md` and `ar/index.md` so the two versions stay aligned.
2. Update the "Last updated" date at the top.
3. Commit and push the reviewed change.
4. GitHub Pages automatically redeploys both URLs.
5. If the change is **material** (new data category, new third-party
   service, scope change), trigger an in-app notification per the
   policy's "Changes to This Policy" section.

## License

The policy text is © Hamam Alabdulla. All rights reserved.
