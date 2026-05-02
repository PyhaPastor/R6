# Yamaha YZF-R6 (2000) — Carb Tuning Setup

European spec, Keihin CVK34 carbs.

## Modifications

- K&N air filter
- Dynojet Stage 1 jet kit (E4161)
- OEM exhaust
- OEM airbox

## Current Setup

| Component | Setting |
|-----------|---------|
| Pilot jets | #40 (Keihin N424-74C-40) |
| Main jets | Highest in Dynojet kit (DJ140) |
| Needle position | 4th groove from top (the grooved end) |
| Needle washers | 3 (above E-clip, per Dynojet spec) |
| Fuel screws | 2.5 turns out — testing 3 turns next |
| Float height | ~6mm from bowl gasket mating surface (≈ OEM 17.5–18.5mm spec) |

## Factory Carb Differences (Important)

Outer and inner carbs are NOT identical from the factory:

| Component | Carbs 1 & 4 (outer) | Carbs 2 & 3 (inner) |
|-----------|---------------------|---------------------|
| OEM main jet | #152 | #148 |
| OEM jet needle | N7SB | N7SA |
| OEM pilot air jet | #105 | #110 |
| Diaphragm cover marking | "883 2" | "883 1" |

Don't swap diaphragm covers between carbs — they're matched to their respective bodies.

## Reference — Pilot Jet Part Numbers

Keihin N424-74C series — M4 thread, fits CVK OEM type carbs.

| Size | Part Number |
|------|-------------|
| #40 | N424-74C-40 |
| #42 | N424-74C-42 |

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

| Setting | Result |
|---------|--------|
| #38 pilots, 3rd groove + 2 washers, screws 3–3.5 turns | Lean, hesitation under 8000rpm, decel pop |
| #38 pilots, 5th groove + 3 washers | Sluggish top end (note: airbox was leaking at this time) |
| #40 pilots, 4th groove + 3 washers, screws 2.5 turns | Current setup — runs well, slight hanging idle |

## Known Issues To Address

1. **Hanging idle** — RPM returns slowly from 4000 to 1000, inconsistent. Likely lean pilot circuit despite #40s.
2. **Slight hesitation on snap throttle** at low RPM — partly normal CV carb behaviour, possibly improved by sync.

## To-Do List

1. Wind fuel screws out to **3 turns** — test for hanging idle improvement
2. If 3 turns helps significantly but feels like it wants more → consider #42 pilots, reset screws to 2–2.5 turns
3. Carb sync — last done ~2 years ago, may need refresh
4. Inspect ACV diaphragms next time carbs are off

## Key Lessons Learned

- Float height of ~6mm from gasket mating surface is the OEM spec equivalent (verified via YouTube reference: katanawarriorx, May 2020)
- Fuel screws past 3 turns = pilot jets too small
- European spec carbs may run richer than US-spec on same kit settings
- Loose airbox boots cause symptoms identical to lean jetting — always check first
- 4th groove + 3 washers appears to be the sweet spot for European cold-to-warm conditions

## Useful Resources

- **OEM parts (EU):** cmsnl.com (Netherlands)
- **Carb info reference:** sportbikeguy.com/garage/floor/r6carbinfo.html
- **General R6 reference:** yamahayzfr6.com
- **Dynojet install guide:** dynojet.com/installguide/E4161
- **Float height video:** youtube.com/watch?v=6-yGChQIorQ
