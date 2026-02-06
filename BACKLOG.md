# BACKLOG

## Freight Heat Map Visualizer

**Vision:** Contour map overlaid on North America (or globe) showing freight cost OR lead time based on:
- Origin: Austin, TX (Blitzpanel warehouse)
- Destination: Any location
- Load size: Panel dimensions + weight

**Output:** Geographic heat map with color-coded contours showing:
- Cost zones (e.g., $100, $200, $500 shipping from Austin)
- Lead time zones (e.g., 1-day, 3-day, 5-day delivery)

**UI:**
- Toggle between "Cost View" and "Lead Time View"
- Slider for load size (updates map dynamically)
- Click location → get exact quote

**Use case:**
- Quote freight to customers instantly
- Visualize shipping economics (where is expensive to ship?)
- Optimize warehouse location strategy
- Price transparency for sales

**Tech stack:**
- Map: Mapbox/Leaflet/Google Maps API
- Freight data: FedEx/UPS/Freightquote APIs
- Frontend: Web app (React/Vue) or local tool

**Data sources needed:**
- Freight carrier APIs (FedEx Freight, UPS Freight, etc.)
- LTL carrier rates
- Dimensional weight calculations

---
