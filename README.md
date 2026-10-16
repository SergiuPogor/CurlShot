<div align="center">

<img src="https://curlshot.com/icon.svg" width="96" height="96" alt="CurlShot logo"/>

# CurlShot

### Screenshot any website with one API call

[![Website](https://img.shields.io/badge/website-curlshot.com-2563EB?style=for-the-badge)](https://curlshot.com)
[![Docs](https://img.shields.io/badge/docs-curlshot.com%2Fdocs-111827?style=for-the-badge)](https://curlshot.com/docs)
[![Free plan](https://img.shields.io/badge/free-100%20screenshots%2Fmonth-22C55E?style=for-the-badge)](https://curlshot.com/pricing)

</div>

---

[CurlShot](https://curlshot.com) is a screenshot API: one HTTP request turns a URL, your own HTML or Markdown into a PNG, JPEG, WebP, PDF, or a scrolling video (MP4, WebM, GIF). Pages render in a real browser, so what you get is what a visitor sees.

## Quick start

```bash
curl "https://curlshot.com/api/v1/screenshot?access_key=YOUR_KEY&url=https://example.com" -o example.png
```

That's the whole request. Add options as more words in the address, or POST them as JSON. Get a free key at [curlshot.com/register](https://curlshot.com/register), or try it in the browser without an account on [curlshot.com](https://curlshot.com).

## Features

- **One request, no SDK.** The API is a plain URL, so it works from any language, shell or no-code tool. Examples for cURL, Node.js, Python, PHP, Go and Ruby are in the [docs](https://curlshot.com/docs).
- **The page as visitors see it.** Real browser rendering, lazy images loaded, full-page capture from top to bottom.
- **Clean captures.** Cookie banners, ads, trackers and chat bubbles removed before the shot on most sites.
- **Every screen size.** Phone, tablet and desktop presets, retina density and dark mode.
- **Exactly the part you need.** Capture one element by CSS selector, with an optional transparent background.
- **More than images.** Selectable-text PDFs, scrolling videos, and images rendered from your own HTML or Markdown.
- **Built for agents and automations.** MCP server (`https://curlshot.com/api/mcp`), OpenAPI 3.1, `llms.txt`, an n8n community node, async jobs with signed webhooks, and bulk runs of up to 100 URLs.

## Use cases

- Link previews and website thumbnails
- Open Graph images rendered from HTML templates
- Visual monitoring across phones, tablets and desktops
- Archiving web pages as PDF
- AI agents that need to see a web page
- Reports, invoices and certificates from Markdown or HTML

## Pricing

Free: 100 screenshots a month, no card. Paid plans: Starter $19, Growth $79, Scale $249 a month. One successful render is one screenshot, whatever its size; failed renders and cache hits are free. See [curlshot.com/pricing](https://curlshot.com/pricing).

## Links

- Website: https://curlshot.com
- Documentation: https://curlshot.com/docs
- Pricing: https://curlshot.com/pricing
- MCP server for AI agents: https://github.com/SergiuPogor/curlshot-mcp
