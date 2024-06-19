# OSM Maps from GPX

Create OSM maps from GPX files to use with OSRM.

Allows creating new routes based on the history of your runs.

## How to use

Launch two OSRM instances with public map and custom OSM:

```
docker compose up
```

Use these notebooks:

- `notebooks/Convert GPX to OSM map.ipynb` to create OSM map from GPX files in `data` folder
- `notebooks/Query OSRM to get GPX route.ipynbb` to query OSRM with custom map

Remember to restart OSRM instance after changes to the map.