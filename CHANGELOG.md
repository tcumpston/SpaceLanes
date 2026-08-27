# Changelog

## 1.0 — 28 August 2026

First public release for Windows. Space Lanes has been playable in a browser at
wombyland.com; this is the same game as a native download.

**The game**

- Sixteen sectors, from *First Light* to *The Wake*, each a distinct lane-shaping
  problem rather than a harder version of the last.
- Lanes are tuned, not drawn: parameters on the control deck reshape a curve
  through the sector, and a live FIT reading shows how close it is.
- Beacons must be threaded and hazards avoided. ENGAGE names any beacon you
  missed rather than simply refusing.
- Two levels of help, neither hidden: NUDGE moves the single worst parameter
  toward a working value and says which one it touched; REVEAL draws the charted
  lane in gold alongside yours.
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
