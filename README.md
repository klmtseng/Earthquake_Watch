# Earthquake_Watch

**Live demo:** https://klmtseng.github.io/Earthquake_Watch/

Cyberpunk-styled geo-hazard map in a single HTML page (Leaflet.js).

Shows on a dark world map:

- Earthquakes from the last 5 days (USGS FDSN event API), marker size/color by magnitude
- Tectonic plate boundaries (fraxen/tectonicplates GeoJSON)
- Active tropical storms (NRL active-storms feed)
- Country outlines and a sortable quake list panel

## Run

No build step. Open `index.html` in a browser (internet connection required —
all data is fetched live from public APIs).
