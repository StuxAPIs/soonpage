<p align="center">
  <picture><source media="(prefers-color-scheme: dark)" srcset="https://global.media.stuxapis.net/logo-light.png"><source media="(prefers-color-scheme: light)" srcset="https://global.media.stuxapis.net/logo-dark.png"><img src="https://global.media.stuxapis.net/logo-dark.png" height="100" alt="StuxAPIs Logo"></picture>
</p>

# Coming Soon Page

A clean and simple coming soon page template for StuxAPIs services.

## Overview

This repository contains a lightweight HTML page designed to let users know something exciting is on the way. It's perfect for building anticipation ahead of a new StuxAPIs service or launch.

## Features

- 📄 Simple, clean HTML structure
- ⚡ Lightweight and fast-loading
- 🎨 Ready to customize
- 📱 Responsive design
- 🚀 Deployed at [soonpage.stuxapis.net](https://soonpage.stuxapis.net)

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/StuxAPIs/soonpage.git
   ```

2. Open `index.html` in your browser or deploy to your hosting provider

## Customization

Edit the HTML files to:
- Update the coming soon message
- Add your branding and logo
- Customize colors and styling
- Include email signup or social links

## Deployment

This project uses GitHub Pages and can be automatically deployed to your desired domain.

The live version is deployed at [soonpage.stuxapis.net](https://soonpage.stuxapis.net).

## Local development

Run `./dev-server.sh [port]` (or `dev-server.bat [port]` on Windows), then open `http://127.0.0.1:8000`. Add `--lan` to open it from a phone or tablet on the same network: the server then listens on all interfaces instead of `127.0.0.1` only, and prints the addresses to open (usually the `192.168.x.x` one).

## Versioning

This project uses [Date Versioning](https://datevers.ing): each release is numbered by its UTC release date as `YY.MM.DD` (for example `26.10.23`), with `-1`, `-2`… for later releases the same day. See [CHANGELOG.md](CHANGELOG.md) for what changed in each release.

Releases are committed and tagged on the `test` branch, then go live through two pull requests: `test` into `staging`, then `staging` into `main`. Each needs CI to pass and is reviewed and merged by Leo; see [Branches and going live](CONTRIBUTING.md#branches-and-going-live).

## Tests

Run `bash tests/version.sh` and `bash tests/site.sh` (Python 3.8+, no dependencies). The second checks the Discord link previews and the icon set. See [CONTRIBUTING.md](CONTRIBUTING.md).

## License

This project is open source and available for use and modification.

---

*Built & Maintained by <picture><source media="(prefers-color-scheme: dark)" srcset="https://global.media.stuxapis.net/icon-light.png"><source media="(prefers-color-scheme: light)" srcset="https://global.media.stuxapis.net/icon-dark.png"><img src="https://global.media.stuxapis.net/icon-dark.png" height="14" alt="StuxAPIs" valign="middle"></picture> [StuxAPIs](https://github.com/StuxAPIs), Hosted by <img src="https://github.com/Stuxedo.png" height="14" alt="Stuxedo" valign="middle"> [Stuxedo](https://stuxedo.com).    
StuxAPIs is a part of the <picture><source media="(prefers-color-scheme: dark)" srcset="https://global.media.stux.group/icon-light.png"><source media="(prefers-color-scheme: light)" srcset="https://global.media.stux.group/icon-dark.png"><img src="https://global.media.stux.group/icon-dark.png" height="14" alt="Stux.Group" valign="middle"></picture> Stux.Group brand of businesses.*
