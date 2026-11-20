# Horizon Apex 3D — Supercar Racing

A self-contained 3D WebGL2 racing game in a single HTML file: custom HDR renderer (bloom, MSAA, cascaded soft shadows, clear-coat metallic paint), two race environments, sim-cade vehicle dynamics and a WebAudio engine synthesizer. No 3D libraries, no build step, no API keys.

## How a race starts
1. **Garage** — pick a vehicle and press *Use this vehicle*.
2. **Environments** — pick where to race.
3. **Start Race** unlocks once both are chosen.

## Garage
- **Ford Mustang GT Fastback** — rear-wheel drive • 310 km/h
- **BMW M4 Competition (G82)** — all-wheel drive, easiest to drive • 312 km/h
- **Bugatti Chiron Pur Sport** — all-wheel drive, heavy but brutal • 322 km/h
- **Pagani Huayra** — rear-wheel drive, light and agile • 370 km/h
- **Koenigsegg Jesko** — rear-wheel drive, fastest in the garage • 420 km/h
- **Ferrari F80** — hybrid all-wheel drive, sharpest handler • 350 km/h
- **Kawasaki Ninja H2** — superbike, leans into corners, hardest to master • 300 km/h

All vehicles are stylised models built in code, not licensed replicas.

## Environments
**Races**
- **Horizon Apex Circuit** — 4.1 km, 3 laps, hills, forest and a hairpin. Gold: under 5:00.
- **Desert Highway** — 5 km sprint down a dead-straight 2-lane road with dunes, mesas and heat haze. Gold: under 1:10.

**Free roam** (no rivals, no timer, drive anywhere — trees, rocks and buildings are solid)
- **Horizon Valley** — the hills and forest around the circuit.
- **Mojave Desert** — the open desert around the highway.

Rivals are matched to the class of vehicle you pick.

## Driving Model
- Slip-angle tyre model with a friction circle: brake in a straight line, turn in, then feed in the throttle.
- Weight transfer, aerodynamic drag and downforce, 7-speed automatic gearbox.
- Run-off areas with reduced grip; solid barriers on both environments.

## Gearbox & sound
Choose **Automatic** or **Manual** when you pick a vehicle. Every vehicle has its own engine sound, gear-change sounds, rev-matching on downshifts and a stuttering rev limiter. Cars faster than 350 km/h also have a supercharger whine.

## Controls
- **W / S or Arrow Up / Down:** Accelerate & Brake (hold brake at a standstill to reverse)
- **A / D or Arrow Left / Right:** Steer
- **R / C:** Shift up / down (manual gearbox)
- **Spacebar:** Handbrake (kicks the tail out; drifting builds skill multiplier & nitro)
- **Shift / N:** Nitro (above 80% charge: purple Shockwave)
- **V:** Camera • **L:** Lighting (Sunset, Midday, Night) • **G:** Graphics quality • **Backspace:** Reset car • **M:** Mute • **Esc:** Quick menu (pauses)

## Graphics Quality
The ✨ option in the ☰ quick menu (or **G**) switches between Low, Medium and High. Phones start on Low; desktops start on High.

## Running Locally or on GitHub Pages
Open `index.html` in any modern WebGL2 browser, or enable **GitHub Pages** on the repository's main branch.
