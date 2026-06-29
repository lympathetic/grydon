# Grydon — Interactive Type Specimen

A single-page, self-contained interactive specimen for the **Grydon** display
typeface (Medium · Bold · Black).

## Features

- Animated marquee masthead
- Three-weight specimen book (Medium 500 · Bold 700 · Black 900)
- Live type tester — type with the keyboard or click any glyph to drop it in
- Full glyph set (723 glyphs) grouped into **Letters, Ligatures, Figures,
  Punctuation, Symbols, Diacritics** — click a glyph to inspect it against the
  font's metric system (Asc / Cap / X / Base / Desc)

## Run locally

Open `index.html` in a browser, keeping the three `Grydon-*.otf` files in the
same folder. (Opening the file directly in Chrome can block local fonts — use
Firefox or a local web server if the font doesn't load. On GitHub Pages it
loads fine over HTTPS.)

## Editing in VS Code

1. Open the folder in VS Code: **File ▸ Open Folder…** → select this folder.
2. Edit `index.html` — everything (HTML, CSS, JS) lives in that one file.
3. To preview with live reload, install the **Live Server** extension
   (Extensions panel → search "Live Server" by Ritwick Dey → Install), then
   right-click `index.html` → **Open with Live Server**. The page opens in your
   browser and refreshes automatically on save.

Page section order (top → bottom): hero (reserved) → about/specimen narrative →
marquee → three-weight specimen → mockup showcase → type tester → glyph set →
footer. Images live in `Grydon_svg/`.

## Hosting

Published with **GitHub Pages** from the repository root.

## Files

- `index.html` — the specimen page
- `Grydon-Medium.otf`, `Grydon-Bold.otf`, `Grydon-Black.otf` — the fonts
