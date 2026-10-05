# ROC Data Hub map prototype

Proof of concept for retiring ArcGIS from ROC Data Hub (rocdatahub issue #83): the owner's sample
flood grid (`Flood_extent`, 39,270 flooded cells of 184,567) and the 39 study locations, served as
plain GeoJSON files and drawn with Leaflet on OpenStreetMap tiles. Nothing loads from arcgis.com.

Live: https://ucc-web-dev-team.github.io/rocdatahub-map-prototype/

Generated, not hand-edited: `data/` and `index.html` come from
`.scratch/arcgis-retirement/poc/` in the rocdatahub repo (`build_poc_data.py`, `index.src.html`,
published by `publish_pages.py`).
Map data (c) OpenStreetMap contributors; borders fallback from Natural Earth (public domain).
