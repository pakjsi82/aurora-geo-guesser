# Aurora Sports Geo-Guesser: GIS Day 2026

A GeoGuesser-style game featuring sports landmarks across Aurora, Ontario. Read the description and hint, click where you think it is, and see how close you got.

**Play:** https://pakjsi82.github.io/aurora-geo-guesser/

## How to play

1. Read the description and hint for the location.
2. Click or tap the map to place your guess (switch to **Satellite** in the layer menu if fields are easier to spot from above).
3. Click **Submit Guess**.
4. Land within 150 m for a perfect 1,000 points; the score drops off with distance.
5. After 5 rounds, see your final score.

## Editing

Everything is in `index.html`; there's no build step.

- **Questions:** the `QUESTIONS` list at the top of the `<script>` (name, description, hint, image URL, lat/lng).
- **Basemaps:** the `BASEMAPS` list (Esri World Street Map and World Imagery by default).
- **Colours:** `--primary` (Aurora Green) and `--primary-fg` / `--secondary` (Aurora Gold) at the top of the `<style>`.

## Tech

Plain HTML, CSS and JavaScript with [Leaflet](https://leafletjs.com/) 1.9.4. Works on phones (portrait and landscape), tablets and desktop. Basemaps: Esri World Street Map and World Imagery (Powered by Esri). Hosted on GitHub Pages.
