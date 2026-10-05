RTYC Tor Bay Tidal Flow Viewer

FILES TO UPLOAD TO GITHUB PAGES
- index.html
- data.json

Nothing else is required.

GitHub Pages:
1. Create a public repository.
2. Upload index.html and data.json into the repository root.
3. Settings > Pages.
4. Deploy from branch: main / root.
5. Open the github.io URL.

The viewer obtains Torquay high/low-water predictions at runtime from the free
OpenWaters tides API (no user API key required) and uses the predicted tidal
range to scale the RTYC current model.

Internet access is required for:
- the base map tiles
- tide prediction lookup

The flow-vector model itself is stored locally in data.json.

This is an experimental race-tactics model and must not be used for navigation.
