# Thinkroid Space Website

Marketing website for [Thinkroid Space](https://www.thinkroid.space/) — the gamified multi-agent orchestration platform.

## Structure

```
Thinkroid_Space-Website/
├── index.html          # Landing page
├── docs/index.html     # Documentation redirect
├── css/shared.css      # Design system (variables, layout, nav, footer)
├── assets/             # Logo, favicons, OG image
├── CNAME               # Custom domain: www.thinkroid.space
├── robots.txt
├── site.webmanifest
└── favicon.ico
```

## Development

Static HTML site — no build step required. Open `index.html` in a browser or use any local server:

```bash
npx serve .
```

## Deployment

Deployed via GitHub Pages with custom domain `www.thinkroid.space`.

## License

[CC BY-SA 4.0](LICENSE)
