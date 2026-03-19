# GlyphGuard Landing Gallery Assets

Put your real 4K screenshots here.

Required filenames (used in `../index.html`):

- `dark-theme-4k.webp`
- `light-theme-4k.webp`
- `royal-gold-4k.webp`
- `robot-buddy-4k.webp`
- `obsidian-titan-4k.webp`
- `emerald-vault-4k.webp`

Hard requirements (for this landing):

- Folder: `landing/github-pages/gallery/`
- Aspect ratio: `9:16` (portrait)
- Minimum resolution: `1080x1920`
- Recommended resolution: `2160x3840` (4K portrait)
- Preferred format: `WEBP`
- Allowed fallback: `PNG`

Recommended export settings:

- Color profile: `sRGB`
- WEBP quality: `82-90`
- Target file size: `<= 1.2 MB` per image (better page speed)
- Keep all screenshots in the same framing and zoom level
- Keep text/UI inside safe area (at least 6% left/right and 8% top/bottom)

How the landing renders images:

- Gallery cards use `aspect-ratio: 9 / 16`
- Images use `object-fit: cover`
- If your source is not 9:16, edges may be cropped

Quick QA checklist:

1. All 6 files are present with exact names above
2. Every image is portrait 9:16 and sharp on mobile
3. No critical text near edges
4. Files are optimized (fast loading)
