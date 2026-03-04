✈️ ADS-B Live Flight Tracker

A FlightRadar24-style live flight tracker running entirely in the browser.  
No backend, no API key — powered by the free [adsb.fi](https://adsb.fi) open data API.

## 🚀 Live Demo
Enable GitHub Pages on this repo → Settings → Pages → Deploy from `main` branch root.

## Features
- 🛩️ Live ADS-B + MLAT aircraft positions (updates every 12 seconds)
- 🎨 Aircraft colored by altitude
- 🖱️ Click any plane for full details (hex, registration, squawk, speed, etc.)
- 🔍 Search by callsign, ICAO hex, or registration
- 🎖️ Military filter
- 🟢 Smooth refresh progress bar
- 🌑 Dark radar aesthetic, zero dependencies except Leaflet

## How to use locally
Just open `index.html` in a browser — no build step needed.

## Deploy to GitHub Pages
1. Push this repo to GitHub
2. Go to **Settings → Pages**
3. Set source to `main` branch, `/ (root)`
4. Visit `https://yourusername.github.io/your-repo-name`

## Data source
[adsb.fi open data API](https://github.com/adsbfi/opendata) — free, no key required.  
Personal/non-commercial use only. Please consider [contributing a feeder](https://adsb.fi/get-started/).

## License
MIT
