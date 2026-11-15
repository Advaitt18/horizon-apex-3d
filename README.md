# Horizon Apex 3D — Supercar Circuit Racing

A self-contained 3D WebGL2 racing game in a single HTML file: custom HDR renderer (bloom, MSAA, cascaded soft shadows, clear-coat metallic paint), a 4.1 km Catmull-Rom circuit, sim-cade vehicle dynamics and a WebAudio engine synthesizer. No 3D libraries, no build step, no API keys.

## Playable Garage Roster
- **Ford Mustang GT Fastback** — rear-wheel drive, Obsidian Black with dual orange stripes • 310 km/h
- **BMW M4 Competition (G82)** — all-wheel drive, Isle of Man Green • 312 km/h
- **Bugatti Chiron Pur Sport** — all-wheel drive, Atlantic Blue & carbon • 322 km/h

## Driving Model
- Slip-angle tyre model with a friction circle: brake in a straight line, turn in, then feed in the throttle.
- Weight transfer under braking/acceleration, aerodynamic drag and downforce.
- Torque-curve engine with a 7-speed automatic gearbox and rev limiter.
- Grass and gravel run-off with reduced grip; solid armco barriers all the way round.
- Rivals follow a racing line, brake for corners and can be bumped.

## Controls
- **W / S or Arrow Up / Down:** Accelerate & Brake (hold brake at a standstill to reverse)
- **A / D or Arrow Left / Right:** Steer
- **Spacebar:** Handbrake (kicks the tail out; drifting builds skill multiplier & nitro)
- **Shift / N:** Nitro (above 80% charge: purple Shockwave)
- **C:** Cycle Camera (Chase, Action, Hood)
- **L:** Cycle Lighting (Sunset, Midday, Night Neon)
- **G:** Cycle Graphics Quality (Low, Medium, High)
- **R:** Reset Car to Track • **M:** Mute

## Graphics Quality
The ✨ button (or **G**) switches between Low, Medium and High. Phones start on Low; desktops start on High. Drop a level if the frame rate is poor.

## Running Locally or on GitHub Pages
Open `index.html` in any modern WebGL2 browser, or enable **GitHub Pages** on the repository's main branch.
