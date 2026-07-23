# AI Blog Explainers

A daily-updated static site of visual explainers for new AI announcements from
Claude, OpenAI, and Microsoft.

- `index.html` — landing page (search + source/category filters). No build step.
- `explainers/` — one self-contained HTML page per post.

## Add a post
1. Drop a new file into `explainers/<slug>.html`.
2. Add one entry to the `POSTS` array near the bottom of `index.html`.

This repo is published automatically via GitHub Pages (Settings → Pages → main / root).
