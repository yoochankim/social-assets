# social-assets

Images attached to social posts (Threads). This repository exists because the Threads
API fetches `image_url` from its own servers — there is no local upload path, so every
attachment needs a public URL.

```
https://raw.githubusercontent.com/froggsleep/social-assets/main/<product>/<date>-<slug>.png
```

## Rules

- **Only publish-approved assets go here.** This repository is public; unapproved drafts stay local.
- Path layout: `<product>/<YYYY-MM-DD>-<slug>.png`
- Threads limits: width 320–1440px · 8MB max · **JPEG and PNG only**
  (webp and gif fail at container creation, after the attempt has already been counted)

## Products

- `forgecat/` — ForgeCat Agent Profiles
- `rising/` — "rising on GitHub" posts from the personal account
- `letti/` — Letti
