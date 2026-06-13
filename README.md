# Toby Website

Static website for Toby: private AI agents with free self-hosting and hosted paths built around owner control.

## Files

- `index.html` - human-facing website
- `agent.json` - structured agent-readable service profile
- `llms.txt` - short LLM brief
- `robots.txt` - crawler policy
- `assets/toby-secure-cloud-hero.jpg` - optimized hero image used by the page
- `assets/toby-secure-cloud-hero.png` - generated source image

## Preview

Open `index.html` directly in a browser.

For local HTTP testing:

```sh
python3 -m http.server 4173
```

Then visit `http://localhost:4173`.

## Before Publishing

Replace the placeholder `mailto:hello@example.com` in `index.html` with the real Toby intake address or form endpoint.

## Image Asset

The hero image was generated with the built-in image generation tool and then copied into `assets/`. The JPEG is used by the site for page weight; the PNG is kept as the source asset.
