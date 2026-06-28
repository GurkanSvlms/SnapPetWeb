# SnapPet GitHub Pages Site

Static marketing, privacy, and terms website for **SnapPet: Cat & Dog Collector**.

## Files

- `index.html` - marketing landing page.
- `privacy.html` - App Store Privacy Policy URL.
- `terms.html` - App Store Terms of Use URL with Apple Standard EULA reference.
- `styles.css` - cozy neobrutalism styling.
- `assets/` - SnapPet icon assets.

## Publish on GitHub Pages

1. Create a GitHub repository, for example `snappet-site`.
2. Commit these files to the repository root.
3. In GitHub, open **Settings > Pages**.
4. Set **Build and deployment** to **Deploy from a branch**.
5. Select branch `main` and folder `/root`.
6. Use these live App Store Connect URLs:
   - Privacy Policy: `https://gurkansvlms.github.io/SnapPetWeb/privacy.html`
   - Terms of Use: `https://gurkansvlms.github.io/SnapPetWeb/terms.html`

## App Store Connect Privacy Setup

- Privacy Policy URL: `https://gurkansvlms.github.io/SnapPetWeb/privacy.html`
- App Privacy label:
  - Identifiers > User ID: App Functionality, not tracking.
  - Other Data: App Functionality, not tracking.
  - Diagnostics > Crash Data: App Functionality, not tracking.
  - Location: not collected.
  - Tracking: no.

Support email in the HTML files is `sketchhero.team@gmail.com`.
