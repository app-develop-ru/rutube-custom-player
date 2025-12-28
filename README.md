# Rutube Custom Player Pro

High-performance, lightweight HTML5 player wrapper for Rutube integration.
Developed by **[App-Develop.Ru](https://app-develop.ru)** for professional use cases.

## 🚀 Key Advantages

### ⚡ Zero Performance Impact
Optimized for heavy pages. Unlike the standard iframe embed, our player uses Lazy Loading and DOM virtualization. You can place **10+ videos on a single page** without slowing down the browser or lowering your Google PageSpeed score.

### 🔒 User Retention (No Leaks)
External links and aggressive advertising clicks are blocked. Users watch your content and stay on **your** website, increasing retention and conversion rates.

### 🎨 Fully Customizable
*   **Responsive Design:** Automatically adapts to any container width and aspect ratio.
*   **Clean UI:** Minimalist interface that matches your brand guidelines.
*   **Control API:** Full programmatic control over playback, volume, and events.

## 📦 Quick Start

1. Download `rutube-player.min.js` and `rutube-player.min.css`.
2. Include them in your document `<head>`:

```html
<link rel="stylesheet" href="rutube-player.min.css">
<script src="rutube-player.min.js" defer></script>
```

3. Insert the player — you only need one line of HTML.

### Minimal example

Specify the container size (via style or CSS class) and the video source:

```html
<div class="rutube-player" data-video="c5256e2646279f0452335123456789" style="width: 800px;"></div>
```

### Flexible input formats

The `data-video` attribute accepts:

*   ✅ **Video ID:** `c5256e2646279f0452335123456789`
*   ✅ **Direct URL:** `https://rutube.ru/video/c5256e2646279f0452335123456789/`
*   ✅ **Embed URL:** `https://rutube.ru/play/embed/c5256e2646279f0452335123456789`

The player automatically extracts the video ID and renders the video correctly.

## 💰 Support & Customization
**This version is free to use "as is".**

Need changes? We offer professional services:
*   ✅ **Custom branding:** Logo, colors, layout.
*   ✅ **Advanced features:** Analytics, playlist management.
*   ✅ **Source code:** Available for enterprise purchase.

[![Contact us](https://img.shields.io/badge/👉_Contact_us_for_a_quote-0052CC?style=for-the-badge&logo=telegram&logoColor=white)](https://app-develop.ru)
