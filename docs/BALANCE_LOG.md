# Balance Log
| Value | Old | New | Rationale | Build |
|---|---|---|---|---|
| Base fall speed | — | 2 + score/40 | Initial ramp | 0.1 |
| Burnt chance | — | 22% | Initial | 0.1 |
| Lives | — | 3 | Initial | 0.1 |
| Game tick | per frame | fixed 60/s | Same speed on 120/144 Hz screens | 0.3 |
| Wide-tray power-up | — | 3.5% spawn, tray 90→140px for 8s, no life lost if missed | Comeback tool for fast late game | 0.4 |
| Heart pickup | — | 1.2% spawn, +1 life (cap 5), no life lost if missed; wide-tray share now 1.3% | Rare recovery for long runs | 0.5 |

## Build 0.6 (2026-10-19)
- Floating +N score popups on each catch (40 frames, fade out; frozen while paused).
- "NEW BEST!" shown on game over when the best score is beaten.
- No balance numbers changed.

## Build 0.7 (2026-10-19)
- Fixed: page header showed v0.5; now v0.7.
- HUD shows Level 1-6 (Level = 1 + floor((speed-2)/1.4); speed cap 9 = Level 6). Combo moved down a line.
- Title screen shows best score.
- No balance numbers changed.

## Build 0.8 (2026-10-19)
- Added: game over screen shows final score.
- Fixed: red burnt-crust flash no longer fades while paused.
- Header now v0.8. No balance numbers changed.

## Build 0.9 (2026-10-19)
- Added: "LEVEL N" banner (90 frames, fades) + chime when Level goes up.
- Fixed: dragging no longer moves the tray while paused.
- Header now v0.9. No balance numbers changed.

## Build 1.0 (2026-10-20)
- Added: red "MISS" popup where a missed topping falls.
- Added: game over screen shows the level reached.
- Header now v1.0. No balance numbers changed.

## Build 1.1 (2026-10-20)
- Added: gold "COMBO!" popup + chime when a combo reaches 5 (the +1 bonus starts).
- Fixed: game now auto-pauses when the tab is hidden (mobile app switch / tab change), not just on window blur.
- Header now v1.1. No balance numbers changed.

## Build 1.2 (2026-10-20)
- Added: game over screen shows toppings caught and best combo for the run.
- Header now v1.2. No balance numbers changed.

## Build 1.3 (2026-10-20)
- Added: lives shown as pink heart icons on the HUD.
- Header now v1.3. No balance numbers changed.
