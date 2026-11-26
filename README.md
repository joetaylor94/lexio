# Lexio website

The public website for the Lexio apps, served at lexiolabs.io by Vercel (project `lexiolabs`), which
deploys every push to `main`. GitHub Pages still serves the old address.

Each app has its own folder so its addresses never change:

- `news/` — Lexio News: landing page, `privacy.html`, `terms.html`, `support.html`, and `get/`,
  the download link. `get/` goes straight to the App Store, except inside TikTok's own browser,
  which will not open the App Store: there it shows how to open the page in Safari.

`lexiolabs.io/get` is the short address to share on TikTok; it forwards to `news/get/`.

The front page (`index.html`) forwards to `news/` while that is the only app. The privacy,
terms and support addresses are registered with the App Store and linked from inside the app,
so do not move or rename them.
