# UNC Bible Study QR redirect

This repository hosts the redirect used by the printed QR code for `unc-bible-study.brotatotes.com`.

## Change the destination

Update the destination URL in all three places in `index.html`:

1. The `meta http-equiv="refresh"` tag
2. `window.location.replace(...)`
3. The fallback link

Commit and push to `main`. GitHub Pages will publish the change automatically.
