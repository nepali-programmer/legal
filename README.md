# legal

Public legal documents for Nepali Programmer products. Everything here is
published with GitHub Pages so each document has a stable public URL, which is
what app stores and payment processors require.

| Product | Document | URL |
| --- | --- | --- |
| PinData (Chrome extension) | Privacy policy | https://nepali-programmer.github.io/legal/pindata/privacy.html |
| CV Maker & PDF Editor (Android, iOS) | Privacy policy | https://nepali-programmer.github.io/legal/pdf-tool/privacy.html |
| CV Maker & PDF Editor (Android, iOS) | Terms of use | https://nepali-programmer.github.io/legal/pdf-tool/terms.html |
| CV Maker & PDF Editor (Android, iOS) | Support | https://nepali-programmer.github.io/legal/pdf-tool/support.html |
| CV Maker & PDF Editor (Android, iOS) | Product page (marketing URL) | https://nepali-programmer.github.io/legal/pdf-tool/ |
| Podly (Android app) | Privacy policy | https://nepali-programmer.github.io/legal/podly/privacy.html |
| Podly (Android app) | Terms of use | https://nepali-programmer.github.io/legal/podly/terms.html |

## Rules for this repo

- **URLs never move.** A store listing points at these paths; renaming a file
  breaks a published listing. Add a new file instead of moving an old one.
- Every document carries an effective date, and material changes get a new one.
- Source of truth for PinData's policy is `PRIVACY.md` in the (private) pindata
  repository; `pindata/privacy.md` here is the published copy and must be
  updated in the same change.
- Podly's documents are authored directly here (`podly/*.md` is the source, `podly/*.html` the
  published copy); update both in the same change.
- CV Maker & PDF Editor's pages are written as Markdown (`pdf-tool/*.md`) and
  rendered to the matching `.html`; edit the Markdown and regenerate both in
  the same change. The app (`pdf_tool` repository, `AppConfig`) and both store
  listings point at the `.html` URLs.
