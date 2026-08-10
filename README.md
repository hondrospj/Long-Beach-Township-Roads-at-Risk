# Long Beach Township Roads at Risk

Static GitHub Pages app for drawing road and cross-section profiles through the Long Beach Township municipal DEM.

The interface follows the North Wildwood Roads at Risk reference: threshold presets, NAVD88/MLLW conversion, terrain and hillshade views, saved multi-line cross sections, flood-history and future-frequency charts, and CSV/Shapefile exports.

Municipal constants:

- Observations: USGS 01409335, Tuckerton
- PETSS / NOAA station: 8534319
- NAVD88 thresholds: 2.57 ft minor, 3.57 ft moderate, 4.57 ft major
- MLLW thresholds: 4.4 ft minor, 5.4 ft moderate, 6.4 ft major
- MLLW = NAVD88 + 1.83 ft

Terrain source: USGS 3DEP Bare Earth DEM Dynamic ImageServer, clipped to the Long Beach Township boundary at 24.6-foot adaptive resolution.
