# GIS Pipeline

## Import
- Normalize CRS on ingest; reproject once, not per tool.
- Keep raw LiDAR tiles immutable; derive surfaces as copies.

## Export
- Match vertical datum to client spec before contour generation.
