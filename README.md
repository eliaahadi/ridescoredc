# RideScore DC

A community-built pipeline and map that scores the bike-safety/comfort of DC streets, combining open data (crashes, lanes, speed, lanes count, etc.) with transparent rule sets (e.g., LTS, BNA-style connectivity).

## What this repo contains
- **Rulesets** (YAML): Encoded versions of existing bike safety/comfort frameworks (e.g., LTS) plus a composite RideScore for ranking.
- **Schemas** (JSON): Canonical fields for street segments and scores so layers stay consistent.
- **Pipeline code** (Python): Ingest → clean → features → scoring → layers → (optional) tiles.
- **Layers** (JSON): Toggleable map layers (ranking, crash history, number of car lanes, etc.).
- **Web**: A simple Leaflet/MapLibre web app for exploration.
- **Project Plan/Meeting Notes**: View link [here](https://docs.google.com/document/d/1AsSjS07xshxVOjvKomdz90E6jUUXW7Dy5Z89CkY_dj4/edit?usp=sharing)

## Quickstart (local)
TBD