
# Expense Tracker — Icons & Logos

This package contains pre-sized app icons and logos for web/PWA and mobile platforms.

## Folders
- `icons/` — Square PNG icons with padding, ideal for iOS/Android/PWA favicons.
- `logos/` — Wide logo PNGs for headers, splash screens, and marketing.

## Suggested mappings
- PWA manifest:
  ```json
  {
    "name": "Expense Tracker",
    "short_name": "Expenses",
    "icons": [
      { "src": "icons/app-icon-192.png", "sizes": "192x192", "type": "image/png" },
      { "src": "icons/app-icon-512.png", "sizes": "512x512", "type": "image/png" }
    ],
    "theme_color": "#000000",
    "background_color": "#ffffff",
    "display": "standalone",
    "start_url": "/"
  }
  ```

- HTML `<head>` (favicons example):
  ```html
  <link rel="icon" type="image/png" sizes="32x32" href="/icons/app-icon-32.png">
  <link rel="icon" type="image/png" sizes="48x48" href="/icons/app-icon-48.png">
  <link rel="icon" type="image/png" sizes="96x96" href="/icons/app-icon-96.png">
  <link rel="apple-touch-icon" sizes="180x180" href="/icons/app-icon-180.png">
  ```

## Originals
- `icons/app-icon-original.png` — original uploaded icon
- `icons/app-icon-original-square.png` — original normalized to a perfect square with transparent padding
- `logos/app-logo-original.png` — logo converted to PNG

## Notes
- All images are PNG (lossless). The square icons keep transparent padding to avoid warping.
- If you need additional sizes or a transparent-background logo remake, let me know.
