# Plainroot Studio

The public pages for Plainroot Studio's apps, served by Cloudflare at https://plainrootstudio.com. Every push to `main` deploys.

- `lexmio/index.html`: the Lexmio page in English and Turkish, at https://plainrootstudio.com/lexmio (the App Store marketing URL)
- `lexmio/support.html`: Lexmio support, at https://plainrootstudio.com/lexmio/support
- `lexmio/privacy.html`: Lexmio privacy policy, at https://plainrootstudio.com/lexmio/privacy
- `gradino/support.html`: Gradino support, at https://plainrootstudio.com/gradino/support
- `gradino/privacy.html`: Gradino privacy policy, at https://plainrootstudio.com/gradino/privacy
- `paperhop/support.html`: Paperhop support, at https://plainrootstudio.com/paperhop/support
- `paperhop/privacy.html`: Paperhop privacy policy, at https://plainrootstudio.com/paperhop/privacy

The Paperhop pages are written and kept here, not in the Paperhop project. The app links to them, with `#tr` for Turkish. When the app starts to send something new or uses a new AI service, update the privacy page in the same release, so it and the app's consent screen say the same thing.

The Lexmio pages are generated from `Site/` in the Lexmio project, with the support address filled in and links without the `.html` ending. Edit them there and copy them here, so the app and these pages stay in step. The Gradino pages come from `Site/` in the Gradino project (the glp1-tracker repository) the same way. Gradino has no app page here yet.

The Lexmio page is kept here, not in the Lexmio project, because the app doesn't link to it. Its screenshots in `lexmio/img/` and the press kit in `lexmio/press/` come from the Lexmio project's `Docs/Evidence/Store-1.0/raw/` captures and its app icon. Its headings use Fraunces from the app, subset to Latin and Turkish in `lexmio/fonts/` with its SIL Open Font License beside it. Lexmio was released on 11 November 2026. The page, the studio home page and the press kit link to https://apps.apple.com/app/id6822015059, with a text button in both languages until Apple's official App Store badge (from Apple's Marketing Tools) is added to `lexmio/img/`; switch the page's link to the web campaign link (`ct=web`) once it exists.
