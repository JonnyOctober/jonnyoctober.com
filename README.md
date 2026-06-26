# jonnyoctober.com

The personal landing site for Jonny October — a single, hand-built page linking
out to music, videos, and streaming platforms.

No framework and no build step: one `index.html` with all CSS inlined. The
design leans on CSS custom properties, an SVG noise-grain overlay, a radial
glow, and staggered entrance animations, with a responsive grid that collapses
cleanly on mobile.

## Stack

- Static `index.html` (inline CSS, no JS framework)
- Deployed on Cloudflare Workers (`wrangler.jsonc`) serving the directory as
  static assets
- Google Fonts (Anton + JetBrains Mono)

## Develop & deploy

```bash
npx wrangler dev      # local preview
npx wrangler deploy   # publish
```

## License

MIT — see [LICENSE](LICENSE).
