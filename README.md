# BF6 Weapon Previewer v2026 - 3D weapon armory 2026

> **Battlefield 6 armory preview in the browser.** BF6 Weapon Previewer is an HTML-based web experience for viewing weapons, attachments, gadgets, and throwables in 3D, with the current release aligned to 2026.

[![Platform](https://img.shields.io/badge/Platform-browser-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2026-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/masonagwrfisher304/bf6-3d-weapon-previewer?style=flat-square)](https://github.com/masonagwrfisher304/bf6-3d-weapon-previewer)

---

<p align="center">
  <a href="https://masonagwrfisher304.github.io/bf6-3d-weapon-previewer/">
    <img src="https://img.shields.io/badge/Download-BF6%20Weapon%20Previewer%20Latest-brightgreen?style=for-the-badge" alt="Download BF6 Weapon Previewer">
  </a>
</p>

> **[Direct Download - BF6 Weapon Previewer v2026](https://masonagwrfisher304.github.io/bf6-3d-weapon-previewer/)**

---

[Download Latest Build](https://masonagwrfisher304.github.io/bf6-3d-weapon-previewer/)

---

## Overview

BF6 Weapon Previewer is a browser-first 3D armory focused on Battlefield 6 content. It gives you a visual way to inspect weapons, combine them with compatible attachments, and move through connected equipment categories without installing a separate desktop application.

This project is aimed at players, loadout builders, and creators who need a fast place to compare setup choices and presentation details side by side. It also covers optics, skins, camos, charms, gadgets, throwables, and Portal SDK code generation, all delivered through a static HTML site with local model staging.

---

## What it includes

- Browser-based 3D weapon preview
- Real weapon and attachment compatibility
- Browsable gadgets and throwables
- Weapon skins, camos, and charms
- Real optic reticles and lens coating colors
- Portal SDK code generation support
- Offline armory list export
- Static site structure with local model staging

---

## Installation

Clone the repository or download the project files, then open the static site in a browser.

```bash
git clone https://github.com/masonagwrfisher304/bf6-3d-weapon-previewer.git
cd REPO
```

After that, open the HTML entry point in your browser, or serve the folder with any simple local web server if you prefer a local preview environment.

---

## How to use it

1. Open the site in a browser.
2. Select a weapon from the armory list.
3. Attach compatible items and see how the build changes.
4. Explore gadgets, throwables, skins, camos, and charms.
5. Use the Portal SDK generation tools when you need exportable code output.
6. Export the offline armory list if you want a local reference set.

For local testing, a simple static server is usually enough:

```bash
python -m http.server 8000
```

Then open the address shown in your terminal and navigate to the preview page.

---

## Configuration

Most behavior is controlled by static HTML, local model assets, and browser-facing data files. If you are customizing content, review the repository layout for model staging paths, armory data, and any export-related files.

A typical setup may include sections like:

```json
{
  "models": "./models",
  "data": "./data",
  "exports": "./exports"
}
```

Update paths to match your local layout and deployment target.

---

## Requirements

- A modern web browser
- HTML support
- Access to the repository files or hosted static build
- Enough local storage for staged models and exported armory data
- A local server is recommended for development or offline testing

---

## FAQ

**How do I get updates?**  
Watch the repository for newer builds and replace your local copy with the latest files when needed.

**Can I change the displayed loadouts or exports?**  
Yes. Since the content comes from static files and local data, edits should be made in the repository assets and configuration used by the browser build.

**What if models or previews do not load?**  
Confirm that the static files are being served correctly and that the model paths match the repository structure.

**Does it require installation like a desktop app?**  
No. This is a browser-based HTML project, so opening it in a compatible browser is the normal workflow.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
