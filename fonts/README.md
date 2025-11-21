Bundle Comic Neue locally

This folder is intended to hold the Comic Neue font files so the site can render the congration page consistently offline.

Steps to add the fonts:

1. Visit the Google Fonts page for Comic Neue:
   https://fonts.google.com/specimen/Comic+Neue

2. Download the family using the Download family button (this gets a ZIP).

3. Extract the ZIP and copy the following files into this `fonts/` folder (rename if necessary):
   - `ComicNeue-Regular.woff2` (or `ComicNeue-Regular.woff`)
   - `ComicNeue-Bold.woff2` (or `ComicNeue-Bold.woff`)

4. The files must be named exactly as above (or update the paths in `congration.html`).

Notes:
- The site will prefer local files; if they are missing the page still falls back to Comic Neue via Google Fonts (network required).
- Google Fonts is open-licensed; bundling for your repo is allowed per the font license. If you want, I can fetch and add the woff2 files for you.
