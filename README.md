# Satellite Habitat Watch

Sentinel-2 monitoring for habitat destruction alerts.

## Problem

Habitat destruction (illegal logging, burning of lakeside reeds) is often noticed by ecologists weeks after the violation occurred, when damage is irreversible.

## Solution

Script that monitors free satellite imagery (Sentinel-2) for defined protected areas and automatically alerts organizations if it detects sudden drops in vegetation or water indices.

## Technical Stack

- Google Earth Engine (GEE) Python API (`ee`)
- NDVI (Normalized Difference Vegetation Index) and NDWI computation
- Anomaly detection algorithm comparing against three-year baseline

## Status

🚧 Planning

## License

MIT — see [LICENSE](LICENSE)
