# DragonNet rclone

DragonNet rclone is a private backup tool used by its owner to back up his own files to his own Google Drive.
It is not a public service.

This repository holds only the tool's public information pages, which Google requires for an OAuth app:

| Page | URL |
|---|---|
| Home | <https://jrcuster.github.io/dragonnet-rclone/> |
| Privacy policy | <https://jrcuster.github.io/dragonnet-rclone/privacy.html> |

## Repository layout

```
docs/          GitHub Pages site (published from the main branch, /docs folder)
  index.html   home page
  privacy.html privacy policy
  style.css    shared styles
```

## Conventions

- Plain static HTML and CSS: no build step, no scripts, no trackers.
- The pages carry no personal information beyond the app name and the maintainer's GitHub handle.
- Changes to `docs/` go live on GitHub Pages within a few minutes of a push to `main`.
