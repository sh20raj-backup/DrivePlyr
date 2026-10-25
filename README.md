# DrivePlyr

**Google Drive proxy video-player demo suite with multiple HTML5 player integrations.** This backup copy uses the `sh20raj-backup` project namespace for site links and Sopplayer CDN examples.

[![GitHub Pages](https://img.shields.io/badge/demo-GitHub%20Pages-222?logo=github)](https://sh20raj-backup.github.io/DrivePlyr/)
[![Pages deployment](https://github.com/sh20raj-backup/DrivePlyr/actions/workflows/pages.yml/badge.svg?branch=main)](https://github.com/sh20raj-backup/DrivePlyr/actions/workflows/pages.yml)

## Demo links

- **DrivePlyr:** https://sh20raj-backup.github.io/DrivePlyr/
- **VideoPlyr:** https://sh20raj-backup.github.io/VideoPlyr/
- **DrivePlyr20 source/templates:** https://github.com/sh20raj-backup/DrivePlyr20

## Player library CDN

The demo uses Sopplayer assets from a version-pinned CDN URL:

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/sh20raj-backup/Sopplayer@v2.0.0/sopplayer.min.css">
<script src="https://cdn.jsdelivr.net/gh/sh20raj-backup/Sopplayer@v2.0.0/sopplayer.min.js"></script>
```

## Deployment

GitHub Actions deploys static files to Pages through [`.github/workflows/pages.yml`](.github/workflows/pages.yml). Review [Actions](https://github.com/sh20raj-backup/DrivePlyr/actions) for current build status.

**Important:** GitHub Pages is a static host and cannot execute PHP templates. Use a PHP-capable server to run PHP endpoints and player templates; Pages is for static examples only.

## Related projects

- [Sopplayer CDN library](https://github.com/sh20raj-backup/Sopplayer)
- [VideoPlyr demos](https://github.com/sh20raj-backup/VideoPlyr)
- [DrivePlyr20 PHP templates](https://github.com/sh20raj-backup/DrivePlyr20)

## License

Refer to the repository's existing license file, if present.
