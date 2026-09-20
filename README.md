# TouchifyMouse — website and downloads

Public home for the TouchifyMouse website, its privacy policy and terms, and the
desktop app downloads. **No application source code lives here** — that stays in a
private repository.

- Website: https://hamzahussainshah.github.io/touchifymouse/
- Privacy policy: https://hamzahussainshah.github.io/touchifymouse/privacy.html
- Terms of use: https://hamzahussainshah.github.io/touchifymouse/terms.html
- Desktop downloads: [Releases](https://github.com/hamzahussainshah/touchifymouse/releases/latest)

## Publishing

- **Website:** push to `main`; the "Deploy site" workflow publishes it. Enable it once
  under Settings → Pages → Source: GitHub Actions.
- **Desktop installers:** attach them to a release, using exactly these names, because
  the phone app and the website link to them:
  - `TouchifyMouse-mac.dmg`
  - `TouchifyMouse-win.zip`
  - `TouchifyMouse-win-Setup.exe`

The pages are generated from the app's own privacy and terms text in the private repo
(`scripts/publish_site.sh`), so the store listing, the in-app screens and this site always match.
