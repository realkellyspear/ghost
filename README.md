# GHoSt website

The static website for [ghost.wildemindpress.com](https://ghost.wildemindpress.com/).
`index.html` is the welcome page; `terminal.html` and `ghostpcp.html` contain
the product pages. GitHub Pages publishes the root of the `main` branch.

The product pages include snapshots of the respective project READMEs. When a
project README or release changes, update the relevant page and download link;
the repository links on the pages always point to the current source.

## Adding a welcome banner

Export a wide image around 2000 × 800 pixels (2.5:1) as an optimized WebP or
JPEG. Keep the mascots and any text near the center, with breathing room at
the edges for smaller screens. Aim for under 500 KB. Add it to this repository
and insert an `<img>` at the banner comment in `index.html`; use a meaningful
`alt` description, or `alt=""` if it is purely decorative. Display it with
`width: 100%; height: auto` to preserve the entire image without cropping.
