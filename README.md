# APRS2
HTML APRS viewers
<br><br>
Map & basemap

ArcGIS World Imagery satellite tile layer via Esri's tile server
Leaflet.js handles the map rendering, pan, zoom, and custom popups
<br><br>
"My Location" button

Uses the browser Geolocation API to fly the map smoothly to your coordinates
Drops a pulsing blue dot at your position with a coordinate popup
<br><br>
Station types & filters

Mobile (orange ▲), Weather (blue ☁), Fixed (green ●), and Objects (purple ◆) — each with their own marker icon
Toggle switches in the filter panel show/hide each type on the fly
<br><br>
Live data

The app queries the aprs.fi public API on load and whenever you pan/zoom the map (with an 800ms debounce), and auto-refreshes every 30 seconds
The bottom ticker shows an animated live stream of incoming packets with callsign, type, and position

<br><br>
Demo mode

Since the aprs.fi API requires a free registered key for real requests, the app automatically falls back to 30 realistic demo stations seeded across the US, with mobile stations continuously moving along their bearings
<br><br>

<br><br>


<b>To connect to real APRS data: Register a free API key at aprs.fi and replace the "demo" string in the source with your key — that's the 
only changeneeded.</b>
