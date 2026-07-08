# ct-al2mru — news content

This repository holds ONLY the news content, edited through **Pages CMS**.
Editors work here; they never touch the website code repository.

- `content/news/*.json` — one file per news item (managed by Pages CMS).
- `images/` — news images (uploaded by editors via Pages CMS).
- `.pages.yml` — Pages CMS configuration (defines the editor form).

The website repository automatically pulls from this repo and rebuilds every
few minutes, so published news appears on the live site shortly after saving.

Do not add GitHub Actions/workflows or secrets to this repository.
