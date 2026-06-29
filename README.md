# Yamaha YZF-R6 (2000) — Carb Tuning Setup

European spec, Keihin CVK34 carbs.

## Modifications

- K&N air filter
- Dynojet Stage 1 jet kit (E4161)
- OEM exhaust
- OEM airbox

## Current Setup

| Component       | Setting                                                       |
| --------------- | ------------------------------------------------------------- |
| Pilot jets      | #42 (Keihin N424-74C-42)                                      |
| Main jets       | Highest in Dynojet kit (DJ140)                                |
| Needle position | 4th groove from top (the grooved end)                         |
| Needle washers  | 3 (above E-clip, per Dynojet spec)                            |
| Fuel screws     | 2.5 turns out                                                 |
| Float height    | ~6mm from bowl gasket mating surface (≈ OEM 17.5–18.5mm spec) |

## Factory Carb Differences (Important)

Outer and inner carbs are NOT identical from the factory:

| Component               | Carbs 1 & 4 (outer) | Carbs 2 & 3 (inner) |
| ----------------------- | ------------------- | ------------------- |
| OEM main jet            | #152                | #148                |
| OEM jet needle          | N7SB                | N7SA                |
| OEM pilot air jet       | #105                | #110                |
| Diaphragm cover marking | "883 2"             | "883 1"             |

Don't swap diaphragm covers between carbs — they're matched to their respective bodies.

## Reference — Pilot Jet Part Numbers

Keihin N424-74C series — M4 thread, fits CVK OEM type carbs.

| Size | Part Number |
| ---- | ----------- |
| #38  | N424-74C-38 |
| #40  | N424-74C-40 |
| #42  | N424-74C-42 |

I used 4 sets of these: <https://www.aliexpress.com/item/1005008321349191.html>

**NOT compatible:**

- N424-21 series (M5 thread — for FCR/PWK race carbs)
- 99101-357 series (different thread — for Honda/Kawasaki CVKs)

## Reference — Dynojet Stage 1 Kit Specs (E4161)

Per official Dynojet instructions for 1999–2000 European YZF-R6:

- Needles: groove 5 from top (kit recommendation — running 4th in practice)
- Washers: 3 above E-clip
- Fuel screws: 2.5 turns out
- Main jets (OEM exhaust): DJ136 baseline, DJ140 max in kit

## Setup History

| Setting                                                | Result                                                                                                                                                  |
| ------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------- |
| #38 pilots, 3rd groove + 2 washers, screws 3–3.5 turns | Lean, hesitation under 8000rpm, decel pop                                                                                                               |
| #38 pilots, 5th groove + 3 washers                     | Sluggish top end (note: airbox may have been leaking at the time.)                                                                                      |
| #40 pilots, 4th groove + 3 washers, screws 2.5 turns   | Runs well overall, but hanging idle (slow return from 4000→1000), cold start needed throttle assist + choke until 60°C                                  |
| #40 pilots, 4th groove + 3 washers, screws 3 turns     | Hanging idle improved, choke could come off at 40–50°C, low RPM response better. Still needed full choke + throttle to start cold. Decel pop acceptable |
| **#42 pilots, 4th groove + 3 washers, screws 2.5 turns** | **Current setup.** Cold start works without choke at 40°C. Stable idle, fast RPM return after blip, improved 1000–2000rpm response.                   |

## Known Issues To Address

1. **Decel popping** — still present on hard engine braking from high RPM. Acceptable for the setup, not chasing further.
2. **Snap throttle hesitation at low RPM** — partly normal CV carb behaviour. Better with #42s but not perfect. Carb sync may improve.

## To-Do List

1. ~~Wind fuel screws out to 3 turns — test for hanging idle improvement~~ ✅ Done
2. ~~If 3 turns helps significantly but feels like it wants more → consider #42 pilots, reset screws to 2–2.5 turns~~ ✅ Done — #42s installed
3. Carb sync — last done ~2 years ago, may need refresh
4. Inspect ACV diaphragms next time carbs are off
5. Monitor #42 + 2.5 turns through full range of seasonal temperatures — fine tune fuel screws between 2–3 turns as needed

## Key Lessons Learned

- Float height of ~6mm from gasket mating surface is the OEM spec equivalent (verified via YouTube reference: katanawarriorx, May 2020)
- Fuel screws past 3 turns = pilot jets too small. **Stuck at 3 turns and still lean = jump to next size up**
- European spec carbs may run richer than US-spec on same kit settings — Dynojet's groove 5 recommendation was too rich, 4th groove works better
- Loose airbox boots cause symptoms identical to lean jetting — always check first
- 4th groove + 3 washers appears to be the sweet spot for European cold-to-warm conditions
- **Cold start choke-off temperature is a useful diagnostic indicator** — needing choke past 50°C suggests lean pilot circuit even if other symptoms feel okay
- **Idle return speed after throttle blip is the single best indicator** of correct pilot circuit sizing
- Garage ambient temperature matters more than outside ambient for "hot day" cold starts — the engine and carbs are at garage temp regardless

## Useful Resources

- **OEM parts (EU):** cmsnl.com (Netherlands)
- **Carb info reference:** sportbikeguy.com/garage/floor/r6carbinfo.html
- **General R6 reference:** yamahayzfr6.com
- **Dynojet install guide:** dynojet.com/installguide/E4161
- **Float height video:** youtube.com/watch?v=6-yGChQIorQ
