# SLIP//STREAM

An endless **gravity-surf racer** — carve an infinite procedural ribbon of light through five shifting zones. Single HTML file, Three.js + Web Audio, no build step, no assets.

**▶ Play it: [arecibo-sys.github.io/slipstream](https://arecibo-sys.github.io/slipstream/)** — works on desktop, phone and iPad.

A completely different genre from [voxel-robots](https://github.com/arecibo-sys/voxel-robots) / [voxel-robots-dark-ultimate](https://github.com/arecibo-sys/voxel-robots-dark-ultimate), built to the same bar: one file, procedural everything, smooth at 60fps.

**Controls:** `A`/`D` or `◄`/`►` steer · `SHIFT`/`SPACE` boost · `ESC` pause · mobile: drag to steer + boost button

## What's in it

- **Procedural infinite track** — a curving, undulating ribbon generated ahead of you from a seeded RNG, with pooled tiles, rails, obstacles and scenery (fixed memory footprint no matter how far you go)
- **5 zones** every 1200m — DAWN · MIRAGE · ABYSS · ION · ECLIPSE — each re-themes the entire scene (canvas-gradient sky dome, fog, sun, track, obstacles, UI accent) *and* switches the soundtrack
- **5 procedural soundtracks** — dreamy 100bpm dawn synth, 118 groove, 124 deep techno, 142 storm drive, 92 heavy eclipse — all Web Audio, no samples, intensity rises with distance and boost
- **Hazards** — blocks, twin blocks, gap gates, moving sliders — density and speed scale with distance
- **Flow rewards** — shard arcs, score rings, boost pads, shield pickups
- **Near-miss chain** — shave past hazards to build a combo multiplier; it decays if you play safe
- **SLIPCHARGE boost** — earned through shards, pads and near-misses; speed + FOV surge with trail particles
- **3 modes** — Classic (one hull, one run), Cruise (no game over — scrape and flow), Daily (UTC-seeded, same track for everyone)
- **Juice** — speed-reactive FOV, camera roll into turns, screen shake, hit flash, slow-mo crash, particle bursts, floating popups, milestone toasts, zone banners, glassmorphic HUD
- **Cross-platform** — desktop keyboard + mobile touch (drag steering, boost button, safe-area aware)
- **Persistence** — versioned localStorage best run · auto-pause on blur · WebGL context-loss recovery

## Run it

```bash
python3 -m http.server 8000
# open http://localhost:8000
```

Three.js loads from CDN — no build step, no dependencies.
