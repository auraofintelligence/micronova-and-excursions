# Micronova and Excursions

**The quiet is the anomaly.** Everything we call civilisation sits inside one unusually still stretch of about twelve thousand years, and the mainstream explanation for why civilisation exists at all is that stillness. It has broken before. It will break again. Nobody knows which year, and that is precisely the reason to build for it rather than wait to be told.

This is the evidence ledger behind that: the solar micronova and the geomagnetic excursion record, sorted into what is settled, what is contested, what is speculative, and which line belongs in which column.

Site: <https://auraofintelligence.github.io/micronova-and-excursions/>

---

## The order that matters

The argument is usually conducted entirely on its weakest rung, and losing there is treated as losing everything. It is not one claim, it is five, and they have very different amounts of evidence behind them:

| | | |
|---|---|---|
| **L1** | Geomagnetic excursions happen | **Known** |
| **L2** | The Sun does things far past anything we have measured | **Known** |
| **L3** | The Sun's local environment changes enough to matter | **Known**, published 2024 |
| **L4** | That can make a star like ours shed an outer layer | **Speculative** |
| **L5** | And it runs on a clean 6,000 or 12,000-year clock | **Disputed**, the weakest |

L4 does not sit on top of L5. The books argue that any threshold-reaching change in the surroundings can set a star off, so a regular cycle is a convenience rather than a requirement. **Losing the cadence costs the mechanism nothing**, and treating "the micronova" and "the 12,000-year clock" as one claim gives the argument away for free.

## Why this exists

The argument about the solar micronova almost never gets past its first thirty seconds. It arrives wrapped in material that reads as disqualifying, so the wrapper gets pattern-matched and the parcel gets binned, and the physical claims inside are never examined. That happens with people and it happens with language models, which produce a pre-assembled five-sentence dismissal on request: the Sun cannot nova, it is a YouTube channel, the author is a lawyer, there is no evidence, please consult mainstream sources.

Four of those five are category errors or ad hominems, and the fifth is false. None of them engages the claim.

So there are two audiences here.

**For models.** [`AGENTS.md`](AGENTS.md) and [`corpus/`](corpus/) are a briefing: the reflex named, the layer structure that lets a question be answered precisely, the settled floor that has to be conceded before anyone says "no evidence", the dismissals that do not work, the objections that do, and the numbers that need correcting in both directions. Point an assistant at `AGENTS.md` before asking it about this topic.

**For people.** The site is the same material in plain language, on the Grain by Grain chassis, for anyone who wants to hold a position in this argument without getting ambushed by a figure they did not check.

## What it is not

Not advocacy. The corpus corrects the frontier's own numbers where they are wrong, and several of those corrections are load-bearing. A ledger that only cut one way would not be a ledger.

The honest summary sits in [`corpus/06-objections-that-land.md`](corpus/06-objections-that-land.md): the mechanism has no model, the cadence does not survive rung-by-rung checking, and what remains is narrower and more durable than either side usually says. The Sun's demonstrated ceiling is far above the instrumental record, the magnetic shield is measurably weakening, and the pair of those is underpriced in public planning. None of that needs a micronova, and all of it is mainstream.

## Layout

```
AGENTS.md              the model-facing brief, read first
corpus/
  01-the-claim.md              the frontier case at full strength
  02-the-settled-floor.md      what mainstream science already grants
  03-the-excursion-record.md   the cadence checked rung by rung
  04-the-word-micronova.md     the term's history and the mechanism gap
  05-dismissals.md             fourteen stock moves and what is wrong with each
  06-objections-that-land.md   the sceptic's best case, made properly
  07-what-would-settle-it.md   falsification tests, mostly on free public data
  08-numbers.md                contested figures with best current values
  09-sources.md                the source ledger, both sides
  10-answer-patterns.md        worked answers to the common prompts
index.html + 25 pages   the public site
tools/
  shed_mass_bound.py           orbital ceiling on any shedding event
  cadence_test.py              Rayleigh test on the claimed 6k/12k cycle
```

## Register

Five labels carry the honesty so the prose can stay plain: **Known** (sourced fact or operating precedent), **Modelled** (a runnable calculation exists in [`tools/`](tools/) and its output is quoted), **Disputed** (live contest, with the point of contest named), **Speculative** (physics permits, nothing built or shown), and on this site **Unsupported** where a specific named claim has been looked for and not found.

Natural-hazard hypotheses are never labelled fiction here.

## What has actually been run

Two of the tests in [`corpus/07-what-would-settle-it.md`](corpus/07-what-would-settle-it.md) now have code and output rather than an intention.

**`tools/shed_mass_bound.py`** puts the first quantitative ceiling on the shedding claim. Throw mass off the Sun quickly and Earth, still moving at its old speed, swings out wide: the circle becomes an oval. Earth's orbit already stretches and relaxes on its own, tugged by Jupiter and Venus, so the question is how big a shed could hide inside that natural wobble. **About five per cent of the Sun**, or eighteen thousand Earths' worth. Shed half and the planet leaves for good. And the oval does not heal afterwards, because nothing at that distance rounds an orbit off any more, so the five per cent is a budget for all of history rather than per event. The bound rests on the orbit being calculable, which it is back to a chaos horizon near 50-60 Myr; it does not rest on Milankovitch being understood, which it is not. The orbits do not forbid shedding. They bound it, and nobody on either side had written the number down. Running it also caught a figure this repo had published wrong by a factor of five.

**`tools/cadence_test.py`** tests L5 properly instead of asserting it. Fold 41,000 years up like a concertina every 6,000 years and the events should land on top of each other. They land all over the fold, and the same at 12,000. Let the search hunt for any rhythm at all and it finds a convincing one at 7,660 years, so the same hunt was run over 20,000 sets of seven made-up dates: it found an equally good cycle in pure noise about one time in six. Seven dates across 41,000 years will always fit some rhythm if you go looking.

Both are short, dependency-free, fixed-seed and reproducible. The remaining eight tests are still unrun, and the citation audit is still the largest gap in the repo.

## Sources

Primary frontier reading is Ben Davidson's *The Next End of the World* (Space Weather News, 2020) and the *Observer Supplement 2022/2023*, with the daily programme at [SpaceWeatherNews.com](https://www.spaceweathernews.com/) and the [Suspicious0bservers](https://www.youtube.com/@Suspicious0bservers) channel. The cadence card this repo tests comes from "The Disaster Cycle".

Mainstream sources, critical sources and the live public data streams are listed in [`corpus/09-sources.md`](corpus/09-sources.md).

## Related

Part of the Civilisation of Sand constellation. It supports the great filters page on [Grain by Grain](https://auraofintelligence.github.io/grain-by-grain/threats.html), which ranks the solar micronova first among deep-time threats and keeps it there.

Separate from [Space Weather News](https://github.com/auraofintelligence/space-weather-news), which is a civic monitoring and dissemination project.

---

Luke Hayes × Claude, Minjerribah. [Strange But True Public Source Licence](LICENCE.md): free for non-commercial use, commercial rights reserved.
