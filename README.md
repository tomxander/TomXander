# Thomas Alex — Portfolio

## Files
- `index.html` — the entire website (markup, styles, and all animation code in one file)
- `support.js` — runtime the page needs; keep it in the same folder as index.html

## Running it
Open `index.html` in any modern browser, or upload both files to any static host
(Netlify, Vercel, GitHub Pages, or your own server). No build step needed.

## Editing content
Open `index.html` in a text editor. Every section is marked with a banner comment like:

    <!-- ============ 01 CRAFT ============ -->

each explaining what to change there. Quick map:

- **Hero headline** — search `HERO HEADLINE` (in the script near the bottom)
- **Hidden message in the static** — search `HIDDEN MESSAGE`
- **Scrolling strip words** — search `SCROLLING STRIP`
- **Craft rows** — search `01 CRAFT`
- **Counter numbers** — search `NUMBERS BAND` (edit `data-count` values)
- **Career entries** — search `02 PATH`
- **Big scroll-ink statement** — search `CONVICTION STATEMENT`
- **AI/method copy** — search `04 METHOD`
- **Notes to self** — search `05 NOTES`
- **LinkedIn / location / footer** — search `06 CONTACT`

## Theme
Default is light. The visitor can flip dark/light with the nav button.
To ship dark by default, find `this.props.theme ?? 'light'` and change to `'dark'`.
