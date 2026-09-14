# Solopass v1 — Animated Portfolio Landing

An early, self-contained animated landing page for **Solopass** — preserved as a "v1" artifact from before the current [living-resume site](https://polymatica.pages.dev).

Single `index.html`, no build step. Pure HTML/CSS/JS.

Try it here https://solopass.github.io/solopass-v1/

Nothing crazy but it was exciting back in 2024. I had a monster emoji chasing them around eating the other ones. I should add that back in!

## Features
- Neon cyberpunk theme (Orbitron display type, cyan/magenta/yellow palette)
- Gradient-animated hero title
- Typewriter reel cycling the Solopass service list
- Floating, clickable emoji sprites (spin / bounce / shake on click) that spawn as each service types out
- Interactive `particles.js` background (hover to grab, click to add)
- Service grid, responsive layout, reduced-motion support

## Run it
Just open `index.html` in a browser, or serve the folder:

```bash
python -m http.server 8000   # then visit http://localhost:8000
```

## Deploy
It's fully static — drop the folder on Cloudflare Pages, GitHub Pages, or Netlify. No configuration required.

## Notes
Cleaned up from the original draft: removed a stale `<base>` domain tag, a broken FontAwesome kit and missing audio asset, wired the particle field to an inline config, and made the nav/CTA anchors work.

---

## License

**Source-available, noncommercial.** Copyright © 2026 Solopass. Licensed under the [PolyForm Noncommercial License 1.0.0](LICENSE.md).

- ✅ **Free** for personal use, hobby projects, study and research, and for nonprofits, schools and public institutions.
- 💼 **Commercial use** (in a business, product or paid service, or for-profit internal use) needs a paid license. See [COMMERCIAL.md](COMMERCIAL.md), or contact [realsolopass@gmail.com](mailto:realsolopass@gmail.com) · <https://polymatica.pages.dev>.
