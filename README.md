# Medication Tracker — Website

Three static pages for the App Store listing. No build step, no dependencies —
plain HTML with inline CSS, light/dark mode aware.

| File           | Purpose                | App Store Connect field    |
|----------------|------------------------|----------------------------|
| `index.html`   | Marketing landing page | Marketing URL (optional)   |
| `support.html` | Support + FAQ          | Support URL (required)     |
| `privacy.html` | Privacy policy         | Privacy Policy URL (required, under App Privacy) |

## Publish free with GitHub Pages

1. Create a new **public** repository on github.com (e.g. `medication-tracker-site`).
2. Upload these three files (drag-and-drop works on the GitHub website:
   "Add file" → "Upload files").
3. In the repo: **Settings → Pages → Branch: `main` / root → Save**.
4. After ~1 minute your site is live at:
   `https://<your-username>.github.io/medication-tracker-site/`

## URLs to paste into App Store Connect

- **Support URL:** `https://<your-username>.github.io/medication-tracker-site/support.html`
- **Marketing URL:** `https://<your-username>.github.io/medication-tracker-site/`
- **Privacy Policy URL:** `https://<your-username>.github.io/medication-tracker-site/privacy.html`

## Before you ship

- When the app is live, replace the "Coming soon to the App Store" button in
  `index.html` with your real App Store link (and ideally Apple's official
  "Download on the App Store" badge from
  https://developer.apple.com/app-store/marketing/guidelines/).
- If you ever add iCloud sync or analytics to the app, update `privacy.html`
  first — it currently (accurately) promises zero data collection.
