# STAR VANGUARD

A neon space-warrior **lane-runner**: steer your squadron of starfighters through
**energy gates** (`×2`, `+15`, `−8`, `÷2`) to grow — or shrink — your legion, blast the
alien blockers, then take down the **boss mothership** at the end of each sector.

Inspired by the "Last War" gate-runner ad minigame, reskinned for deep space.

- **One self-contained file** (`index.html`) — HTML5 canvas, no build, no dependencies.
- **Installable PWA** — add it to your phone's home screen and it runs fullscreen, offline.

## Play

- **Steer:** drag / touch, or `A` `D` / arrow keys
- Pick the better gate as each pair scrolls past
- Survive to the mothership and destroy it to clear the sector

Just open `index.html` in any modern browser, or install it from the hosted URL below.

## Install on a phone (PWA)

Open the hosted HTTPS URL on your phone:

- **Android (Chrome):** tap the ⋮ menu → **Install app** / **Add to Home screen**
- **iPhone (Safari):** tap **Share** → **Add to Home Screen**

It then launches from a home-screen icon with no browser chrome and works offline.

## Files

| File | Purpose |
|------|---------|
| `index.html` | The entire game |
| `manifest.webmanifest` | PWA metadata (name, icons, standalone display) |
| `sw.js` | Service worker — offline caching |
| `icons/` | App icons (192, 512, maskable, apple-touch) |

## Tuning

Gameplay knobs live in the `C = { … }` config block near the top of the script in
`index.html` (speed, gate values, boss HP, damage). Edit and reload.
