# AlertLinkGuard GitHub Pages Landing

This folder contains a ready landing page for publishing on **GitHub Pages**.

## Files
- `index.html` — main page with:
  - store buttons (App Store, Google Play, AppGallery)
  - official app icon in hero, favicon, and social preview tags
  - language auto-detect (`en`, `ru`, `es`) + manual switch
  - placeholders for your studio page and donate link
- `icon.png` — official AlertLinkGuard app icon used by `index.html`

## 1) Replace placeholder links
Open `index.html` and find `STORE_LINKS` block. Replace:

- `YOUR_GOOGLE_PLAY_URL`
- `YOUR_APPGALLERY_URL`
- `YOUR_STUDIO_PAGE_URL`
- `YOUR_DONATE_URL`

## 2) Publish in your public landing repo
You can publish this landing from any public GitHub Pages repository.

Example:
`https://github.com/your-org/your-landing-repo`

Then your Pages URL will usually be:
`https://your-org.github.io/your-landing-repo/`

### Minimal publish flow
1. Copy landing files into the root of your public landing repo
2. Commit + push to `main`
3. In GitHub repo: `Settings -> Pages`
4. Source: `Deploy from a branch`
5. Branch: `main` and folder: `/ (root)`
6. Save and wait 1-3 minutes

## 3) If URL is different
If the public landing URL changes, update app builds to use the new URL.

Current app share link is configured through:
- env var `EXPO_PUBLIC_LANDING_PAGE_URL`
- fallback helper `src/utils/publicSiteUrl.js`

## 4) Optional improvements
- Add favicon and Open Graph image
- Add analytics (Plausible/GA)
- Add separate page for all your apps
- Add privacy policy and support links
