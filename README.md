# GIS UI Gallery

Plug-and-play UI templates for map apps. Copy one HTML file, swap the data block at the top, ship it.

**Live gallery:** https://cyruschu430.github.io/gis-ui-gallery/

## Philosophy

- **Frontend-first, backend-neutral.** Every template is a single self-contained HTML file. No build step, no npm, no framework.
- **MapLibre GL JS by default** (open source, no API key). Some templates ship as an **ArcGIS Maps SDK for JavaScript variant** — same UI shell, native widgets (popups, renderer, Calcite components). Point the layer at your hosted Feature Service and go.
- **One template, multiple skins.** Themes are CSS custom properties; a theme switcher is built in. See the feel before you describe it.
- **The data lives at the top of the file** in a clearly marked block: `/* ==== SWAP YOUR DATA HERE ==== */`.

## Templates

| Template | Category | Skins |
|---|---|---|
| [Vessel Tracking](templates/vessel-tracking/) | Real-time monitoring | MapLibre | Dark console · Clean light · 水墨 |
| [Field Work Orders](templates/work-orders/) | Field & work order | **ArcGIS JS SDK + Calcite** | Dark dashboard |

More coming: smart site supervision, asset management, drone data hub, tree management, work order, building showcase, utility network.

## Using a template

1. Open the template's `index.html` — copy the whole file.
2. Replace the data block at the top with your own GeoJSON / API endpoint.
3. (Optional) Delete the theme switcher if you only need one skin.
4. (Optional) Swap MapLibre for ArcGIS JS SDK — see the comment in each template.

## License

MIT. Take it, change it, ship it.
