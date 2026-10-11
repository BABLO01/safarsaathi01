# Safar Saathi — Travel Companion PWA

## GitHub Pages
Upload the contents of this folder to the root of your repository, so `index.html` is at the repository root. Enable GitHub Pages from **Settings → Pages** and serve over HTTPS. Then open the URL in Chrome and use **Settings → Install app** or the browser menu.

## Included
- Leaflet + OpenStreetMap interactive online map, city centering for Karachi, Hyderabad and Moro
- GPS after permission, online place search, walking/driving route links and manual location sharing
- Local saved places, trip notes, Safar Check and compass where supported
- Mint, Midnight and Warm themes; motion toggle; language preference
- Export/import/clear local data; PWA manifest and service worker shell cache
- SVG logo/icon; responsive layout; Developer by Muhammad Usman

## Offline limitations
App shell and local features work offline after the first successful load; local data stays in this browser on this device. Leaflet is loaded from a CDN and map tiles/search use online services, so the map and fresh search are not available offline. No offline map tiles are bundled to keep the package small. GPS may still work offline if the device can determine location and permission is granted. Compass depends on device/browser support. Safar Check is manual/local only; there is no backend, live tracking, automatic alert, or push notification. The language setting stores preference; UI is currently English with a basic Urdu confirmation message.

Developer by Muhammad Usman
