# Satellite map assets

Northern Norway imagery: Esri World Imagery. Sources: Esri, Vantor, Earthstar Geographics, and the GIS User Community.

Export service: https://services.arcgisonline.com/ArcGIS/rest/services/World_Imagery/MapServer/export
The returned Web Mercator extent is preserved in src/data/satellite-bounds.ts. Attribution is visible below the map.

Location coordinates: Kartverket / Norwegian Mapping Authority place-name API, https://ws.geonorge.no/stedsnavn/v1/.
The selected representative positions and original queries are preserved in src/data/route-coordinates.ts. The 24 descriptions and nearby relationships come from V1.

SVG route connections are illustrative story links, not navigational tracks. The original schematic is adapted to geographic coordinates instead of stretching its coastline over the imagery.
