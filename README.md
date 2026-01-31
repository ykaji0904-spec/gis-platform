# GIS Platform - HardSkill OS

Public Web:
https://gis-platform.pages.dev/

## Purpose
A high-fidelity Web GIS built on CesiumJS.
This is NOT an auto-decision system.
It visualizes reality so humans can make better decisions.

## Non-negotiable constraints
- WGS84 / geodetic accuracy (no "looks right" shortcuts)
- Terrain: Cesium World Terrain
- Bathymetry: official DEM (negative elevation)
- Mapbox 3D is not used

## Layers
- Truth Layer: terrain + bathymetry
- Reference Layer: GSI / municipal GIS (WMS/WFS), OSM trails
- Operation Layer: fire points, water sources, pump candidates, hose routes

## Development workflow
- 1 Issue = 1 feature
- Builder (Claude) implements
- User tests on iPhone and gives 3-line feedback
- Critic (GPT) converts feedback into max 3 improvement tickets
