# Ripplino public support website

Prepared on 2026-09-16. This package is ready for static GitHub Pages hosting.
**The repository and public URLs have NOT been created or verified in this chat.**

## Files and intended URL roles

- `index.html`: English support page — App Store Connect **Support URL**.
- `privacy.html`: English privacy policy — App Store Connect **Privacy Policy URL**.
- `ja/index.html`: Japanese support.
- `ja/privacy.html`: Japanese privacy policy.
- `assets/site.css`: shared flat, mint-and-aqua responsive styling.
- `assets/ripplino-icon.png`: resized derivative of the user-approved smile icon, not a new design.
- `.nojekyll`: plain static delivery.

All pages work without JavaScript, cookies, analytics, external web fonts, forms, or embedded third-party media. The contact link opens the visitor's email app. GitHub's own hosting logs are separately explained in the privacy policy.

## Content basis

Content uses the app specification and Build 2 review reports supplied by the owner, not an independent source-code audit in this chat:
- 60 stages; 1–15 free and 16–60 accessible after a non-consumable purchase; normal progress remains required.
- Normal / Bloom / Echo / Prism; Bloom and Echo bonus emission once per core per player turn.
- Local progress and settings; no developer account system, app-operated cloud sync, ad SDK, or third-party behavioral analytics.
- Apple StoreKit handles purchases and restoration; Apple may independently provide reports/diagnostics according to its policies and settings.
- BGM/SFX are bundled files, not runtime AI requests.
- Independent Music / Sound Effects / Haptics switches; Silent Mode respected.

Operator and email are based on the user's company context and public company contact information: STROBOFACTORY Inc. (株式会社ストロボファクトリー), `strobofactory@gmail.com`. No phone number, street address, unconfirmed response-time guarantee, price, App Store download link, or unconfirmed copyright ownership statement has been added.

The policy distinguishes local app data, Apple purchase processing, voluntarily emailed support data, and GitHub hosting logs. It does not authorize filing App Privacy, Content Rights, age, export, or other declarations.

## Local checks performed

- Four HTML files parsed; internal links and anchors resolve to package files/IDs.
- One H1 per page; language attributes, main landmark, skip link, and navigation present.
- No script, iframe, or form elements.
- Eight offline Chromium render checks: 390×844 and 1440×1000, all four pages.
- No horizontal page overflow or browser JavaScript errors in those eight checks.
- FAQ open/close interaction works in browser.
- Public HTTP availability, deployed paths, and GitHub Pages build remain unverified until deployment.
- Screen-reader usability and all external links require final live checks; local rendering is not a guarantee of full accessibility or legal compliance.

## Deployment

See `PUBLISH_WITH_CODEX.md`. Publish only this website package. Never copy or push the native app repository, audio files, certificates, private documentation, or audit ZIPs into a public repository.

Expected repository name: `strobofactory/ripplino-support`.
This is a proposed new repository, not a confirmed existing repository.
Do not use expected URLs in App Store Connect until the actual deployed pages have been opened publicly and checked.

## Official references used when preparing content

- Apple review requirements: https://developer.apple.com/app-store/review/guidelines/
- Apple app review preparation: https://developer.apple.com/distribute/app-review/
- Apple restore purchases: https://support.apple.com/en-us/108096
- Apple App Store privacy: https://www.apple.com/legal/privacy/data/en/app-store/
- Apple privacy policy: https://www.apple.com/legal/privacy/
- Apple refund requests: https://reportaproblem.apple.com/
- GitHub Pages hosting data: https://docs.github.com/en/pages/getting-started-with-github-pages/what-is-github-pages#data-collection
- GitHub privacy: https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement
- Google privacy: https://policies.google.com/privacy
- Existing company contact: https://strobofactory.net/policies/refund-policy

## Native app follow-up

After the public URLs work, verify the shipped app has an easily accessible privacy-policy link (for example, in Settings/About). Merely adding the URL in App Store Connect does not establish that in-app access exists. If code changes are required, treat them as a separate reviewed build task; do not silently alter Build 2 or the existing Archive.
