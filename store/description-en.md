# Lunar Lander — Store Submission Materials

## Short description (CrazyGames / GameDistribution / itch.io)

Pilot your lunar lander onto the moon's lit pads. Real physics, limited fuel,
and touchdown limits — come in slow, level, and on target. Narrower pads pay
up to ×5. How far can you fly?

## Details

- Genre: Arcade / Physics / Simulation
- Controls: Desktop — ←/→ rotate, ↑ or W main engine, Space/Enter for menus.
  Mobile — on-screen rotate buttons (bottom left) and thrust button (bottom right).
- Landing rules: vertical speed < 22 m/s, horizontal speed < 12 m/s, tilt < 12°,
  both feet on a lit pad. Otherwise: explosion.
- Scoring: fuel remaining ×2 + pad multiplier ×500 (pads pay ×2/×3/×5).
- Features: procedural moon terrain (valleys, plateaus, slopes), 3 pads per
  level, endless level progression (less fuel, narrower pads, faster drift),
  5 ships, altitude camera zoom, velocity warning indicators, best score and
  top level saved locally, mute toggle.
- Tech: Vanilla JavaScript, Canvas, WebAudio (synthesized engine noise and
  effects). Single-file HTML5, no external assets, no frameworks, no tracking.

## Tags

lunar-lander, physics, arcade, space, moon, landing, simulation, retro, single-file

## CrazyGames submission checklist
- [x] Self-contained index.html (SDK loads only on crazygames domains)
- [x] gameplayStart / gameplayStop / loadingStart / loadingStop / happytime events wired
- [x] Responsive (canvas fills viewport, portrait & landscape friendly)
- [x] No external links inside gameplay, no analytics
- [ ] Cover: cover-16x9.png (1280×720)
- [ ] Screenshots: screenshot-raw.png (1280×800)

## itch.io
- Upload zip (rename to lunar-lander-itch.zip), mark "This file is playable in
  browser", entry file: index.html, viewport: fits screen (900×1400 tested),
  kind: html
- Pricing: $0 (donations optional)
