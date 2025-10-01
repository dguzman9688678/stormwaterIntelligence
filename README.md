

# Stormwater Intelligence

This Single Page Application (SPA) demonstrates the architecture and core features of the **Stormwater Intelligence** platform. It is intended for technical demonstration, reference, and professional review by state contractors, federal agencies, and project stakeholders.

---

## Key Features

- **StormVerse Interactive Workspace**
  - **Global Location Selector:** Search for any location using public geocoding (Nominatim/OpenStreetMap).
  - **Live Weather Widget:** Real-time data from Open-Meteo API, with compliance risk logic.
  - **Interactive Map Editor:** Draw and export BMP zones as GeoJSON using Leaflet Draw.

- **Component Architecture (Clickable Cards)**
  - **StormGPT (AI Compliance Engine):** Regulatory RAG, autonomous daemons, multi-format output.
  - **StormVerse (Desktop Platform):** Field-first Electron app, offline support, advanced mapping.
  - **ARCSEC Protocol:** SHA-256 cryptographic sealing, immutable audit trail, chain-of-custody.

- **Performance Metrics**
  - Horizontal bar chart (Chart.js) visualizing max data processing speeds (NOAA ingestion, compliance analysis, reporting).

- **Integrated Compliance Workflow**
  - Five-phase process: Project Initialization, Data Collection, Compliance Verification, Documentation, ARCSEC Sealing.
  - Click workflow steps for detailed explanations.

- **ARCSEC Protocol Example**
  - Shows notarization JSON block for cryptographic document sealing and audit-proof output.

---

## Audience & Data Privacy

- This site is designed **for review by state contractors and federal agencies**.
- **No client or project data is ever collected, stored, or processed by this demo site.**
- All sensitive project/client data remains on agency/contractor-controlled networks and servers.
- All interactive features use public or open-data APIs only.

> **Data Privacy Statement:**  
> “This platform is for demonstration and technical reference only. All sensitive client/project data is managed and stored exclusively on agency/contractor-controlled networks and servers. No client data is ever transmitted to or retained by this public site.”

---

## Usage

1. **Clone or Download**
   - Download the HTML file and open directly in your browser (no server required).
   - Or host on [GitHub Pages](https://pages.github.com/) or similar static site host.

2. **Interactive Workspace**
   - Enter a city/address and click "APPLY" to update the map and weather data.
   - Draw BMP polygons on the map and export as GeoJSON.
   - Click "Refresh Forecast" for live weather updates.

3. **Component Details**
   - Click on any component card to view technical specs and architecture breakdown.

4. **Workflow**
   - Click workflow steps to understand the full compliance process.

---

## Tech Stack

- [Tailwind CSS](https://tailwindcss.com/) for styling
- [Chart.js](https://www.chartjs.org/) for bar chart metrics
- [Leaflet](https://leafletjs.com/) & [Leaflet Draw](https://leaflet.github.io/Leaflet.draw/) for interactive GIS
- [Open-Meteo](https://open-meteo.com/) for live weather (no API key required)
- [Nominatim](https://nominatim.openstreetmap.org/) for address geocoding

---

## Security & Compliance

- No sensitive data or personal information is collected or stored.
- All API calls are public and require no authentication.
- All sensitive data is handled off-platform by project owners on their own secure infrastructure.

---

## Attribution

- Built by Daniel Guzman | [Stormwater Intelligence](https://github.com/dguzman9688678)
- Open-source mapping tiles by [OpenStreetMap](https://www.openstreetmap.org/)

---
