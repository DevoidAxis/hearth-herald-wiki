# Compatibility

Hearth & Herald detects overlapping mods and defers where another mod owns a
system. The rule everywhere is fail-soft: skip, never crash.

## How the mod stays out of the way

- **Clan-scoped by design.** Everything HH does is about *your* clan: your
  offices, your companions, your careers. It does not rewrite kingdom AI,
  economy models, or other clans' behavior, which is why it sits comfortably
  next to overhauls.
- **Buff-only.** Heralds and commissions never move heroes around, never
  auto-assign governors or parties. Nothing fights another mod for control of
  a hero.
- **Defers on contact.** Where a well-known mod owns a system, HH detects it
  and backs its own effect off rather than stacking or fighting.

## Known-mod behavior

| Mod | What happens with both installed |
|---|---|
| **Distinguished Service** | Fully independent - see below. |
| **TrueLimits** (Limits suite) | With the Limits suite on Auto, HH defers all companion/party limit changes wholesale to TrueLimits. Commission caps read your *effective* limit, so they scale with whatever TrueLimits grants. |
| **Improved Garrisons** | Garrison-touching herald effects back off where IG owns them; the Exchequer income decorator is written to survive IG's finance model. |
| **Diplomacy / Diplomacy Fixes** | A daily safety net keeps the Clan Home correct through fief swaps and brokered peace deals. |
| **Banner Kings** | HH economy effects back off. |
| **Marriage / romance overhauls** | HH does not override marriage suitability. The campaign's active marriage model decides, so overhaul rules apply cleanly. |
| **Party AI / order mods** (Party AI Controls etc.) | No overlap: commissions buff skills and titles, they never issue party orders. |

## Distinguished Service, specifically

Short version: **DS can keep running exactly as before - you lose nothing by
installing HH next to it.**

- DS promotes from its own after-battle honors flow. HH ennobles from **banked
  battle merit** (kills per troop type) through the review menu. Different
  triggers, different bookkeeping - the two never race for the same soldier.
- HH's commissions are **decoupled from HH's own ennoblement**: any companion
  can take a commission, whether they came from HH's review, from DS, from
  taverns, or from another mod. A DS-promoted veteran can become your
  Castellan.
- HH holds **zero code references to DS** - no patches, no detection, no
  shared state.

If you ever retire DS, HH's ennoblement (banked multi-promotion, backstory
presets, skill build) covers the same ground; until then, run both without
ceremony.

## Load order

The standard BUTR stack (Harmony, ButterLib, UIExtenderEx, MCM) before the
native modules, Hearth & Herald after. Launch through BLSE.

## Game versions

One download covers 1.2.9 and 1.3.14 through 1.4.1; the loader picks the right
assembly for your game version automatically.
