# PSKReporter logo kit — B1 "Centered signal"

Gradient pin (#8E0015 → #D81E05 → #F27A00 → #FFB400) with a centered dot and two pairs of white arcs.
Wordmark: **Outfit** — "PSK" Bold 700, "Reporter" Regular 400 (Google Fonts, SIL Open Font License).

## web/ — logo on a web page
- `pskreporter-mark.svg` — static vector mark (preferred for the site)
- `pskreporter-mark-pulse.svg` — arcs pulse (inner first, then outer; 2.4 s loop). Animation stops for users with "reduce motion" set.
  Works as `<img src>` or inline. Inline SVG (see `sample/index.html`) lets page CSS control the animation.
- `pskreporter-mark-{128,256,512}.png` — transparent PNGs, height in px

## icons/ — small sizes
- `favicon.ico` (16/32/48), `favicon.svg`
- `icon-{16,32,48,64,128,256,512}.png` — transparent, square
- `app-icon-{180,192,512}.png` — white background with padding (Apple touch icon / PWA manifest)

## wordmark/ — "PSKReporter" in Outfit
- `pskreporter-wordmark-{dark,white,twotone}.png` — text only (two-tone = "PSK" in #C4122A)
- `pskreporter-lockup-{dark,white}.png` — mark + wordmark, transparent
- `pskreporter-lockup-on-dark-preview.png` — preview only

## print/ — DRAFTS for printing on material
- `pskreporter-{2,4}in-stacked.pdf` / `-mark.pdf` — vector, exact 2×2 in and 4×4 in pages
- matching `-300dpi.png` files (600 px and 1200 px)
- These are drafts. Before production: convert text to outlines, confirm the printer's color mode
  (the gradient is RGB and will shift in CMYK), and add any bleed or margins the vendor requires.
  Embroidery or screen printing may need a flat (non-gradient) version.

## sample/
- `index.html` — header lockup with a pulsing inline mark, favicon tags, and each asset in context.
  Open it from inside this folder so the relative paths resolve.
