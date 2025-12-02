# Crane Ops — 2D Crane Game (Mobile + PC)

A single-file **HTML5 Canvas** crane game that runs offline in any modern browser.
Designed for **desktop (keyboard)** and **mobile (touch controls)**, with a **crane hangar** featuring multiple real-world crane categories.

## Features
- ✅ One-file game: **no build, no dependencies**
- ✅ Desktop controls + Mobile touch overlay (auto-detect, configurable)
- ✅ Crane Hangar with unlock progression (medals)
- ✅ 12 levels across Warehouse / Yard / Construction / Heavy Lift
- ✅ Simplified load-chart + stability/overload warnings
- ✅ Local progress saved with `localStorage`
- ✅ Optional sound + effects toggles

## Play
### Option A: Run locally
1. Download `index.html`
2. Open it in Chrome/Edge/Safari/Firefox

### Option B: GitHub Pages (recommended)
1. Push this repo to GitHub
2. Go to **Settings → Pages**
3. **Build and deployment**
   - Source: **Deploy from a branch**
   - Branch: **main**
   - Folder: **/ (root)**
4. Your game will be live at:
   `https://<your-username>.github.io/<repo-name>/`

## Controls

### Desktop
- **A / D** or **Arrow Left / Right**: move
- **W / S**: hoist up/down
- **J / L**: slew (for slewing cranes)
- **Z / C**: telescope (or radius on towers)
- **Space**: attach / detach
- **Shift**: precision mode
- **R**: restart
- **Esc**: pause

### Mobile
- Left joystick: move
- Right slider: hoist
- Buttons: attach / precision / slew / telescope (where supported)

## Notes
- This project is a **game**, not an engineering tool. The “load chart” and stability are simplified for fun.
- Progress is stored in the browser only. Clearing site data resets unlocks.

## Roadmap (optional)
- Tower crane luffing animation + hook block
- Better collision response + load rotation
- Level editor
- More crane variants (e.g., ring cranes, floating cranes)

## License
MIT (see LICENSE).
