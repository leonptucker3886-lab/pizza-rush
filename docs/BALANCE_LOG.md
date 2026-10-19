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
