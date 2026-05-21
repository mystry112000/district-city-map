# 🛸 DISTRICT.CITY — Hacker Satellite Map

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![Leaflet](https://img.shields.io/badge/Leaflet-1.9.4-199900?logo=leaflet&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

> A cyberpunk-themed interactive satellite map with real-time data visualization, built with Leaflet.js. Track projects across India & Indonesia with a hacker terminal aesthetic.

![Map Preview](https://img.shields.io/badge/🗺_Live_Demo-Click_to_View-00ff41?style=for-the-badge)

**➡️ [Launch Live Map](https://yourusername.github.io/district-city-map/)**

---

## ✨ Features

| Feature | Description |
|---------|-------------|
| 🛰️ **5 Satellite Layers** | Google Satellite · Esri · Google Hybrid · Street (OSM) · Dark |
| 🇮🇳 **ISRO Bhuvan** | Indian government satellite tiles |
| 🇮🇩 **BIG Rupabumi** | Official Indonesia basemap tiles |
| 🏷️ **Search Bar** | Nominatim geocoder — type any address |
| 📍 **GPS Locate** | Find yourself on the map |
| 🎯 **34 Markers** | Real locations in Mumbai, Jakarta, Yogyakarta & more |
| 🔬 **Zoom 20** | Individual buildings visible |
| 🌀 **Matrix Rain** | Animated katakana rain overlay |
| 📺 **CRT Scanlines** | Retro terminal aesthetic |
| ⚡ **Glitch Text** | Animated glitch effects on title |
| 🎵 **Sound FX** | Square-wave beep toggle |
| 📊 **Live Clock** | Real-time system clock display |

---

## 🗺️ Map Layers

```
🛰 Google Satellite (default)   → zoom 20 · best worldwide
🛰 Esri Satellite               → zoom 20 · global backup
🛰 Google Hybrid (labels)       → satellite + street names
🗺 Street (OSM)                 → vector-like · instant load
🌙 Dark                         → cyberpunk aesthetic
🇮🇳 ISRO Bhuvan (India)         → Indian satellite data
🇮🇩 BIG Rupabumi (Indonesia)    → official Indonesia basemap
🏷 Labels                       → overlay names on any layer
```

---

## 📍 Project Locations

### 🇮🇳 India — Mumbai
- Imperial Towers · World One · Oberoi Oasis · BKC · Palladium Hotel
- Infinity Mall · Oberoi Splendor · Mindspace · Lodha Bellissimo
- Phoenix Marketcity · Sigma IT Park · Godrej Infinity · Marathon Maxima
- Viviana Mall · Lodha Amara · Hiranandani Estate · Eco Woods

### 🇮🇩 Indonesia
- **Jakarta** — Menara BCA · Menara Mandiri · Grand Indonesia
- **Surabaya** — Pakuwon City
- **Bali** — Jimbaran Beach Resort
- **Bandung** — Trans Studio Mall
- **Tangerang** — BSD City
- **Kalimantan** — IKN Nusantara Capital
- **Yogyakarta** — UNY · Kost Tari Dorm

---

## 🚀 Quick Start

```bash
# Clone the repo
git clone https://github.com/yourusername/district-city-map.git

# Open in browser — no build step needed!
open index.html
```

Or just serve with any static file server:

```bash
python -m http.server 8000
# or
npx serve .
```

---

## 🛠️ Built With

- **[Leaflet.js](https://leafletjs.com/)** — Lightweight interactive maps
- **[Leaflet.markercluster](https://github.com/Leaflet/Leaflet.markercluster)** — Marker clustering at low zoom
- **[Leaflet-control-geocoder](https://github.com/perliedman/leaflet-control-geocoder)** — Address search with Nominatim
- **Google Satellite Tiles** — High-resolution worldwide imagery
- **ISRO Bhuvan** — Indian satellite data
- **BIG Rupabumi** — Indonesia geospatial basemap

---

## 📸 Controls

| Button | Action |
|--------|--------|
| `≡` | Toggle sidebar |
| `◎` | Locate my position |
| `♪` | Sound effects on/off |
| `-` / `+` | Zoom in/out |
| `🔍` | Search any address |
| Layer icon | Switch map tiles |
| Click marker | Fly to location |

---

## 📜 License

MIT — use it freely, modify it, share it.

---

<p align="center">
  <sub>Made with 🖥️ by <a href="https://github.com/yourusername">yourusername</a></sub>
  <br>
  <sub>Satellite imagery © Google · Esri · ISRO · BIG</sub>
</p>
