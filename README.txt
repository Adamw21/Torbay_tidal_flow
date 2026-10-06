RTYC Tor Bay Tidal Flow Viewer v0.8.1

Upload to GitHub Pages root:
- index.html
- data-v081.json
- background-v081.png

Fix in this version
-------------------
The v0.8.0 dynamic arrows were accidentally drawn at about 1 pixel at 100% speed.
This version scales a 100% peak-current arrow to about 58 pixels.

Therefore changing the hour now visibly:
- grows/shrinks arrows through the tidal cycle
- reaches zero at the model slack stages
- reverses the arrows for ebb

A Current strength readout is also shown in the side panel.

Not for navigation.
