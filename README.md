# Giridih Assembly Explorer

An interactive one-page explorer of Jharkhand's assembly constituencies, focused on the six segments of Giridih district. Village boundaries and names come from `vb_soi_jh.GeoJSON`; the full state assembly layer comes from `Jharkhand.geojson`.

The published site is served with GitHub Pages from `index.html`.

## Features

- All 95 Jharkhand assembly segments; the six Giridih segments are highlighted and the rest are muted.
- Village boundaries and names for 2,761 Giridih villages, assigned to their assembly segment.
- Search by village, block, or gram panchayat; click a village to zoom to it.
- English / हिन्दी interface toggle.
- Light theme.

## Data

- `vb_soi_jh.GeoJSON` — village-layer source (EPSG:7755), tracked with Git LFS because of its size.
- `Jharkhand.geojson` — assembly constituency source (EPSG:4326).

The page embeds a reprojected, simplified copy of the data so it works standalone without loading the large source files.

## Attribution

Assembly boundaries: `datta07/INDIAN-SHAPEFILES` (JHARKHAND_ASSEMBLY / Jharkhand.geojson). Village data: `vb_soi_jh.GeoJSON`. Areas shown are approximate.
