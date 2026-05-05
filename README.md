# The Beauty of Religion

A culminating performance task for HRT 3M1 by **Timothy Ivanov**, Spring 2026.

A multi-page editorial website exploring five world religions through the lens of beauty, ethics, and meaning.

## Pages

| # | File | Content |
|---|------|---------|
| 00 | `index.html` | Title page · table of contents |
| 01 | `hinduism.html` | Infographic — Environmental Ethics |
| 02 | `buddhism.html` | Reflection — Dhammapada on impermanence |
| 03 | `judaism.html` | Profile — Drake (Reform Jew) |
| 04 | `christianity.html` | Analysis — Sagrada Família & Aquinas |
| 05 | `islam.html` | Travel brochure — Saudi Arabia & the holy cities |
| 06 | `works-cited.html` | All sources, categorized by religion |

## Stack

Pure static HTML / CSS / JS. No build step. Loads Google Fonts (Fraunces, Spectral, Cormorant Garamond, JetBrains Mono) from CDN and one stock photo for the Christianity page.

## Deploy to Vercel

The simplest path:

1. Push this folder to a new GitHub repo.
2. Go to [vercel.com/new](https://vercel.com/new), import the repo.
3. Framework preset: **Other**. Root directory: `/`. No build command. Output directory: `/` (the project root).
4. Click Deploy.

Or — drag-and-drop the folder at [vercel.com/new](https://vercel.com/new) for instant hosting.

## Local preview

Open `index.html` in a browser, or run a tiny local server:

```bash
cd religion-cpt
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Notes

- The Christianity hero photo is loaded from Unsplash. If you prefer your own photo from Barcelona, drop it into a new `images/` folder and update the `background-image` URL in `christianity.html`.
- The Drake profile is intentionally written *about* the artist using public, well-known biographical information (no fan speculation or invented quotes).
- All sources are real, verifiable references. Verify URLs before final submission.
- Word counts: Buddhism reflection is well over 250 words across the two paragraphs.
