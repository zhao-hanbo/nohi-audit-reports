# Nohi Agent Audit — sample reports

Public-facing landing for sample Agent Audit reports shared with merchants. Each report scores a Shopify product detail page from the perspective of AI shopping agents (ChatGPT, Gemini, Claude) and pairs every gap with a one-click fix.

The source code for the audit pipeline lives in a separate private repo. This repo only contains the rendered HTML output.

## Pages

- `/` — index of all sample reports
- `/conceptglobal.html`, `/annarave.html`, `/nirogam.html`, `/huggwaii.html` — multi-agent reports
- `/venvia.html`, `/olipop.html`, `/conceptglobal-single.html` — single-agent reports

## Hosting

GitHub Pages on the `main` branch. URL pattern:

```
https://zhao-hanbo.github.io/nohi-audit-reports/<slug>.html
```

## Privacy

Reports are not indexed (each carries `<meta name="robots" content="noindex, nofollow">`). URLs are intended for direct sharing with the audited merchant, not for public discovery.
