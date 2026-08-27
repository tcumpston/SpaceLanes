# Changelog

## 1.0 — 28 August 2026

First public release for Windows. Space Lanes has been playable in a browser at
wombyland.com; this is the same game as a native download.

**The game**

- Sixteen lanes across six sectors, each sector introducing a new kind of curve
  rather than a harder version of the last: quadratics, inflections, three
  dimensions, helices, Lissajous harmonics, and the deep charts.
- The lane is an equation, shown live with a slider per coefficient. Move `a`
  and the curvature changes; move `c` and the lane shifts. A FIT percentage
  reads out how close the curve comes to the beacons.
- Beacons must be threaded and hazards avoided. ENGAGE names any beacon you
  missed rather than simply refusing.
- Three levels of help, escalating and none hidden: SCAN names the coefficient
  furthest off and which way to move it, NUDGE moves it part of the way for you,
  and REVEAL draws the charted lane in gold — the only one that costs stars.
- Three-star rating per lane on how precisely you threaded it, with sectors
  unlocking as you go.
- Free orbit camera and a sector map for moving between levels.
- Transmissions between sectors carry the Cartographer's Guild framing.

**In this build**

- EXIT now quits on Windows. In the browser version the button returns you to
  wombyland.com, which is correct there and meaningless on a desktop; the two
  builds now behave appropriately for their platform.
- Skybox textures reduced to 2048 and compressed, taking the download from over
  500 MB to around 130 MB with no visible difference to a background.

**Known limitations**

- The game is not code-signed, so Windows SmartScreen will warn on first run,
  and Smart App Control may block it outright. See the README.
- No application icon yet; the game uses the default Unity icon.
