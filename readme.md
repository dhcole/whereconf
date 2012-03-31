# Outline

- (5 min) Intro to web mapping: what can you make?

    - example base map
    - adding features
    - custom data overlays
    
- (5 min) What are the steps

    - sourcing data
    - processing data
    - designing map
    - integrating with web (for adding features, distributing maps)

## Examples

### (15 min) Making a base layer: tiled

    - sourcing data (osm, census, open data, natural earth)
        - OSM for streets, open data from cities, census data, natural earth
    - processing data (gdal, qgis)
        - working with OSM
        - projections for design and performance
        - postgis, sqlite
    - designing the map (tilemill)

### (15 min) Adding client-side features

    - the basics: MM vs Leaflet vs Openlayers
    - a simple map embed with MM
    - an embed with leaflet
    - adding points
    - adding polygons
    - geojson
    
### (15 min) Tile-based overlays

    - designing a choropleth
    - adding points
    - something fancy (dot density?)
    - serving tiles

- (5 min) Conclusion

    - future things to watch out for
        - vectors
        - webgl
        - tile-based data
    - performance
        - web performance
        - interactivity performance
        - render performance
