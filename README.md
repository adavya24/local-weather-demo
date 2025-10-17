# Weather Dashboard

## Overview
A lightweight, single-page weather dashboard that shows the current weather and a 3-day forecast. It supports toggling temperature units between Celsius and Fahrenheit and displays small weather icons for quick visual context.

- Data source: Open‑Meteo (no API key required)
- Geocoding: Open‑Meteo Geocoding API
- Works in any modern browser

## Setup
1. Download or clone the project.
2. Open index.html in your browser. No build steps or API keys required.

## Usage
- Enter a city name (e.g., "Paris", "Tokyo") and click Search.
- Use the °C / °F toggle in the header to switch temperature units. This updates both current weather and the 3-day forecast.
- On first load, the app attempts to use your device location; otherwise it falls back to New York.

## Improvements in Round 2
- Added a 3-day forecast section below the current weather.
- Implemented a Celsius/Fahrenheit toggle that updates all temperatures consistently.
- Displayed small weather icons (emoji-based) for both current conditions and each forecast day while preserving the existing styling.