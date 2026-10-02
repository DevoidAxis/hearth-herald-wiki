# Ennoblement & Commissions

## Ennoblement: the soldier, raised

Every kill your troops score in your own party banks **merit** for that troop
type. When a type crosses the threshold (default 50 kills, tunable in Mod
Options under **Ennoblement**), one of them can be ennobled into a full
companion who keeps the troop's culture, level, skills, and battle gear.

**Banked elevations**: over-killing a type banks several promotions - 165 kills
at a 50 threshold is three veterans ready. The review shows one row per banked
elevation and you can promote up to the per-review cap (default 3, tunable up
to 50 since 1.12.0) in one sitting. Promoting draws down the merit and carries
the remainder.

**Bulk intake (since 1.12.0)**: pick more than one veteran and the review asks
how to shape the intake.

- **Shape them alike** gives the whole group one commission, and one calling
  too when Skill build at promotion is on (off by default): two decisions
  instead of two per head. Each veteran still draws from their
  own pool, so a preset applied to twenty does not flatten them into identical
  officers. The commission cap is shown before you choose, not discovered
  after: each track reports what it already holds and how many of this
  selection would still fit. Granting stops at the cap and says how many took
  it up; whoever does not fit stays an ordinary companion, commissionable
  later through your Master Herald.
- **Shape each one** keeps the familiar per-veteran walk, in turn. It is still
  the only way to hand-pick skills for an individual, and it is what you fall
  back to if you X out of the shaping question instead.

Custom is deliberately absent from the bulk screen: its pickers read one
hero's improvable skills, so there is no honest way to answer them once for
everybody.

**The skill build (optional, off by default)**: with "Skill build at promotion"
enabled, ennobling opens **Shape the Officer**: "Throughout their battles, this
soldier was known as..." - pick a backstory and the build is done in one click.

- **Marshal, Castellan, or Caravan Master** invests that career's defining
  skills automatically, most important first, every round to the same skills
  (so a small skills-per-round setting still lands the ones that matter).
  Hover a card for the full flavor and the skills it trains.
- **"...something else"** opens the manual rounds: each round you pick up to
  four skills; every picked skill gains the round's amount (round 1 the full
  base, round 2 half). Picking the same skill across rounds stacks.

Kills earned beyond the threshold add to the budget either way. A chosen
backstory also carries forward: the commission offer that follows leads with
that track marked **"their calling"**.

## Commissions: careers for the people you raised

Commission a companion into one of four tracks:

| Track | Skills invested | Actively serving means |
|---|---|---|
| Marshal | party-leader skills + Tactics, Leadership | leading their own party |
| Castellan | governing skills | governing a settlement |
| Caravan Master | trade-road skills | running a caravan |
| Thegn | the full combat package + Tactics, Leadership | fighting in a party, yours or their own |

The **Thegn** (added in 1.11.0) is the martial commission for the companions
who fight rather than administer: a field champion, deliberately without the
map and logistics skills that stay the Marshal's domain. Perks are role-picked
on appointment and reclaimed cleanly on revoke. The governor and party-leader
pickers do not offer a Thegn, so your champion is never mistaken for an
administrator.

At appointment the clan invests a flat package (default +75 per track skill)
and the companion takes the title in their name. While they hold the
commission those skills grow daily - three times faster while actually doing
the job. Growth stops at a ceiling (default 275).

**Revoking** reclaims the invested package but keeps everything earned in
service; titles are stripped and perks re-picked if any orphan.

**Naming and recalling several at once (since 1.12.0)**: both commissioning
and revoking now take more than one companion in a single pick. When the
split is worth asking about, a scope question comes first: riding with you,
elsewhere, or all of them. A clan where everyone falls on one side never sees
the extra screen, and a single pick still goes straight to the richer
per-hero picker.

Herald offices carry titles the same way since 1.11.0: a seated herald is
named Exchequer Herald, Watch Herald, Muster Herald, or Arms Herald for as
long as they serve. One hero holds one title: a commissioned companion who
takes a herald office trades the commission for it.

**Caps** are percentage shares of your effective companion limit (defaults
derived from a 2 Marshal / 4 Castellan / 3 Caravan Master mix at clan tier 6),
so limit mods and the Limits suite's Companions sliders scale them
automatically. At low tiers each enabled track always fits at least one.

Commissions never place anyone for you: you decide who leads a party, governs,
or runs a caravan. A commission is the investment and the title; the job is
still yours to assign.

## Mentoring

Any adult clan member can mentor another (one mentor per mentee): a capped
daily XP drip in the mentor's strongest skill, with a small reciprocal share
back. Commissioned officers make natural mentors - their strongest skills are
the ones the commission built.
