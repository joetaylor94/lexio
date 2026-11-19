# Lexio website

The public website for the Lexio apps, served at lexiolabs.io by Vercel (project `lexiolabs`), which
deploys every push to `main`. GitHub Pages still serves the old address.

Each app has its own folder so its addresses never change:

- `news/` — Lexio News: landing page, `privacy.html`, `terms.html`, `support.html`.

The front page (`index.html`) forwards to `news/` while that is the only app. The privacy,
terms and support addresses are registered with the App Store and linked from inside the app,
so do not move or rename them.
