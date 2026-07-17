# AlphaSmith v2026 - Procedural Alpha Brush Generator 2026

> **AlphaSmith is a browser-based, client-side procedural alpha brush generator for producing grayscale and height masks with seeded, reproducible output, live preview, and PNG export.**

[![Platform](https://img.shields.io/badge/Platform-web%20browser-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2026-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/mooredaniel25/alphasmith-png-export-brush?style=flat-square)](https://github.com/mooredaniel25/alphasmith-png-export-brush)

---

<p align="center">
  <a href="https://mooredaniel25.github.io/alphasmith-png-export-brush/">
    <img src="https://img.shields.io/badge/Download-AlphaSmith%20Latest-brightgreen?style=for-the-badge" alt="Download AlphaSmith">
  </a>
</p>

> **[Direct Download - AlphaSmith v2026](https://mooredaniel25.github.io/alphasmith-png-export-brush/)**

---

[Download Latest Build](https://mooredaniel25.github.io/alphasmith-png-export-brush/)

---

## Overview

AlphaSmith is aimed at artists who want quick, repeatable alpha brushes and mask assets without installing desktop software or depending on an external service. Everything runs locally in the browser, so generation stays on-device while the output remains focused on clean grayscale and height-mask results that can be exported for later use.

Its workflow suits texture creation and sculpting pipelines in tools such as Blender, Unreal Engine, and Photoshop. Procedural presets, a live sculpt-relief preview, and seed-driven output make it easy to iterate through variations while still being able to recreate the same look when needed.

---

## Key Features

- 13 procedural presets for quick starting points
- Tileable, seamless generation for repeatable texture use
- Seed-based output for reproducible results
- Live sculpt-relief preview while adjusting settings
- Export to 8-bit and true 16-bit PNG formats
- Fully client-side operation with offline use
- Preset gallery with live thumbnails for browsing variants
- Custom in-browser PNG encoder for local exports

---

## Getting Started

AlphaSmith is delivered as a browser tool, so there is no standard installer to run.

To use it locally from the repository:

1. Clone or download the project files
2. Open the main HTML file in a modern web browser
3. Start generating and exporting masks directly in the page

Example:

```bash
git clone https://github.com/mooredaniel25/alphasmith-png-export-brush.git
cd alphasmith
```

Then open the app entry file in your browser, or host the folder with any simple static server if you prefer.

---

## How to Use

1. Launch AlphaSmith in a browser.
2. Pick a preset from the gallery.
3. Tweak the parameters to shape the alpha, mask, or relief style.
4. Update the seed when you want a different variation, or leave it unchanged to reproduce the same output.
5. Check the live preview before exporting.
6. Download the final PNG in the bit depth that matches your workflow.

Typical workflow:

- Generate a grayscale mask for painting or texturing
- Export a height mask for sculpt-related workflows
- Reuse the same seed to recreate a previous asset
- Test multiple presets until the shape fits your target asset

---

## Configuration

Most controls live in the browser UI, and changes take effect as you work. If you save presets or browser state, those values stay local to your device and depend on browser session behavior.

Example of the kind of settings you may work with:

```json
{
  "preset": "custom",
  "seed": 12345,
  "output": "16-bit PNG",
  "tileable": true
}
```

---

## Requirements

- A modern web browser
- JavaScript enabled
- Local storage space for downloaded PNG exports
- No server-side runtime required
- Compatible with browser-based workflows for Blender, Unreal Engine, and Photoshop asset prep

---

## FAQ

### Does AlphaSmith need an internet connection?
No. Since it runs on the client side, all generation happens in the browser without relying on a remote service.

### Can I reproduce the same output later?
Yes. If you keep the same inputs, the seeded workflow is intended to return the same result.

### What file formats can I export?
AlphaSmith supports PNG export in 8-bit and true 16-bit output.

### How do I switch presets?
Use the preset gallery in the interface to move between the available procedural options.

### Where are my settings stored?
Settings are kept locally in the browser environment. Clearing browser data may remove saved preferences.

### I am getting unexpected results. What should I check?
Try resetting the seed, changing presets, or reloading the page. If the problem continues, make sure you are using a current browser and that local browser features are enabled.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
