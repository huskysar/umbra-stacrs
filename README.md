# Umbra Public Data Experiments

This repository holds a STAC catalog based on Umbra public data (https://registry.opendata.aws/umbra-open-data/). 

While Umbra has a [published a STAC catalog](https://radiantearth.github.io/stac-browser/#/external/s3.us-west-2.amazonaws.com/umbra-open-data-catalog/stac/catalog.json?.language=en), it is only browseable by year and only shows thumbnails. Here we gathered collections by their "site id" name (like "Hetch Hetchy Reservoir") to more easily browse available data by location. We also modify the original metadata, for example we only provide links to GEC assets.

## Rendering

### STAC Browser link:
- https://radiantearth.github.io/stac-browser/#/external/raw.githubusercontent.com/huskysar/umbra-stacrs/refs/heads/main/catalog/catalog.json

### GeoJSON.io:
- https://geojson.io/#id=github:huskysar/umbra-stacrs/blob/main/umbra-stac-v2.geojson
- https://geojson.io/#id=github:huskysar/umbra-stacrs/blob/main/umbra-stac-v2-centroids.geojson

### GitHub:
- https://github.com/huskysar/umbra-stacrs/blob/main/umbra-stac-v2-centroids.geojson
