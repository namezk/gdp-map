# World GDP Heat Map

Interactive choropleth map showing nominal GDP (2023 estimates) for ~190 countries, built with Leaflet.js and TopoJSON.

## Features

- Color-coded countries by GDP using an 11-step green scale
- Hover to see country name, total GDP, GDP per capita, and population
- Click any country to zoom in
- Search bar to find countries by name
- Country labels rendered on top of the choropleth for readability

## Usage

Serve the directory with any static file server:

```
npx serve
```

Then open `http://localhost:3000` in your browser.

## Data

- **GDP figures**: World Bank 2023 estimates (nominal, current USD)
- **Country boundaries**: [world-atlas](https://github.com/topojson/world-atlas) 50m TopoJSON
