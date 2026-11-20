# JCOS – Chief of Staff

Joshua Ediale's mobile web app (installable to the home screen). Hosted on GitHub Pages at https://jcos.joshuaediale.com and published automatically from the `main` branch (`.github/workflows/pages.yml`). The old Netlify address (jcos.netlify.app) forwards to the new one and hands the saved login across; Netlify builds are stopped.

- `index.html` – the whole app (screens, styles, scripts)
- `sw.js` – offline cache; bump `CACHE` on every release
- `manifest.webmanifest` + `icon-*.png` – home-screen install and icons

The app talks to the "Chief of staff API" Google Apps Script backend. The backend link and access key are entered on the phone and stored there only, never in this repository.

The repository is public so that Netlify's free plan publishes every push to `main`.
