# Vessalia Health — Website

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

## App Store link

The app is live. The "Download on the App Store" button in `index.html` links to:

```
https://apps.apple.com/us/app/vessalia-health-tracking/id6786770500
```

Optionally swap the text button for Apple's official "Download on the App Store"
badge from https://developer.apple.com/app-store/marketing/guidelines/.

## If the app changes

- If you ever add your own servers, analytics, or accounts, update
  `privacy.html` first — it currently (accurately) promises zero data
  collection by us. Data can leave the device only via user-controlled,
  Apple-handled paths: the optional iCloud backup (to the user's own
  private iCloud), optional Apple Health sync, or manual file export.
- Vessy, the assistant, runs on Apple Intelligence entirely on-device —
  keep the privacy copy about it accurate if that ever changes.
