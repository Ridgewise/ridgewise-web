# Leaflet 1.9.4

Vendored from the official Leaflet npm release (BSD-2-Clause; see LICENSE).
Official project: https://leafletjs.com/

Downloaded files:
- https://unpkg.com/leaflet@1.9.4/dist/leaflet.js
- https://unpkg.com/leaflet@1.9.4/dist/leaflet.css
- https://unpkg.com/leaflet@1.9.4/LICENSE

SHA-256:
- leaflet.js: db49d009c841f5ca34a888c96511ae936fd9f5533e90d8b2c4d57596f4e5641a
- leaflet.css: a7837102824184820dfa198d1ebcd109ff6d0ff9a2672a074b9a1b4d147d04c6

The application uses vector circle markers and no image-based layer control,
so Leaflet marker/layer icon images are not required. The optional source map
is not bundled. Map tiles are a separate online service, documented in the
project README; they are not vendored or downloaded for offline use.
