# Compatibility

Hearth & Herald detects overlapping mods and defers where another mod owns a
system - fail-soft everywhere: skip, never crash.

| Mod | Behavior |
|---|---|
| TrueLimits | With the Limits suite on Auto, HH defers all limit changes wholesale to TrueLimits. |
| Improved Garrisons | Garrison-touching effects back off when IG owns them; the Exchequer income decorator survives IG's finance model. |
| Diplomacy / Diplomacy Fixes | A daily safety net keeps the Clan Home correct through fief swaps and brokered peace deals. |
| Banner Kings | Economy effects back off. |
| Distinguished Service | No interaction at all - HH holds zero references to DS. Run both if you like; HH's ennoblement (banked multi-promotion + skill build) covers the same ground if you retire DS. |
| Marriage / romance overhauls | HH does not override marriage suitability; the campaign's active marriage model decides, so overhaul rules apply cleanly. |

## Load order

The standard BUTR stack (Harmony, ButterLib, UIExtenderEx, MCM) before the
native modules, Hearth & Herald after. Launch through BLSE.

## Game versions

One download covers 1.2.9 and 1.3.14 through 1.4.1; the loader picks the right
assembly for your game version automatically.
