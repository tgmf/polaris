# Polaris

A layered star-field animation centered on Polaris — the fixed point around which the night sky appears to rotate.

## Live Demo

🔗 **[View on GitHub Pages](https://polaris.tgmf.st)**

## What it is

Seven concentric layers — a star background, five intermediate nebula/star layers, and a constellation overlay — all rotating at different speeds around a single anchor point near the top-left corner of the screen, mimicking the apparent rotation of the northern sky around Polaris.

| Layer | Period |
|---|---|
| Stars (background) | 7680 s |
| Layer 5 | 4640 s |
| Layer 4 | 3040 s |
| Layer 3 | 1600 s |
| Layer 2 | 1440 s |
| Layer 1 | 960 s |
| Constellations | 480 s |

## Files

```
index.html          — main page
stars.jpg           — deep background star field
layer1–5.svg        — intermediate parallax layers
constellations.svg  — constellation line art overlay
```

## Running locally

Just open `index.html` in a browser — no build step, no dependencies.

```bash
# or serve it with any static server, e.g.:
npx serve .
```

## License

MIT