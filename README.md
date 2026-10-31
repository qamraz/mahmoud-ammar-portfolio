# Mahmoud Ammar — portfolio site

A static site: `index.html` + `media/`. Upload the folder to any static host (Netlify, Vercel, Cloudflare Pages, GitHub Pages).

## Before launch — edit the SITE config at the top of the script in index.html
1. **Contact form**: create a free form at formspree.io (or Basin/Getform), paste its endpoint into `SITE.contact.formEndpoint`. The form shows success only when the service confirms receipt.
2. **Email & socials**: fill `SITE.contact.email` and the `SITE.social` URLs. Empty ones stay hidden.
3. **Services**: set the third value of each service to `true` once Mahmoud confirms he offers it.
4. **Projects**: in `PROJECTS`, add `role`, `year`, `intro`, `approach`, `credits:[["Client","…"]]` as they are confirmed.
5. **Portrait**: add a photo to `media/` and set `SITE.about.portrait`.
6. **Hero video (optional)**: add a short, compressed, muted .mp4 loop to `media/` and set `SITE.hero.video`.
7. When everything is confirmed, set `SITE.editorNotes = false` to hide the gold notes.

Films play from Google Drive (the folder must stay shared as "anyone with the link"). For faster playback, re-host the key films on Vimeo or as self-hosted MP4s.
