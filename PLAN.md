# Micronova and Excursions: Playbook

Repo: `githublocal\micronova-and-excursions`
Public target: `https://auraofintelligence.github.io/micronova-and-excursions/`
Dev server: `.claude/launch.json` name `micronova`, port 4233.
Read this file first every session.

## 1. North star

One argument, sorted into columns, for two audiences at once.

The solar micronova argument almost never survives its first thirty seconds, because it arrives wrapped in material that reads as disqualifying and the wrapper gets pattern-matched instead of the contents. That happens with people and it happens with language models, which produce a pre-assembled five-sentence dismissal on request. Four of the five are category errors or attacks on a person; the fifth is false.

So this repo is two things:

- **A briefing for models.** `AGENTS.md` plus `corpus/`. Names the reflex, gives the layer structure, sets out the floor that has to be conceded before anyone says "no evidence", separates dismissals that fail from objections that land, and corrects the numbers in both directions. Point an assistant at `AGENTS.md` before asking it about this topic.
- **A public site for people.** Fourteen pages on the Grain by Grain chassis, for anyone who wants to hold a position in this argument without being ambushed by a figure they did not check.

**It is not advocacy.** Most of the number corrections run against the frontier, and carrying them is exactly what makes the rest defensible. A ledger that only cut one way would not be a ledger.

## 2. Current state (2026-08-01, first build complete)

14 pages live, verified (all 200, no console errors, no em dashes, no horizontal overflow at 375 or 1280):

| Page | Holds |
|---|---|
| `index.html` | The five layers the question splits into, the four things science grants, the nine rooms, where it lands |
| `settled.html` | Miyake events, superflares, the excursion record, measured weakening, the word itself |
| `excursions.html` | The eight-rung cadence checked rung by rung. Two hold. |
| `micronova.html` | The claim at full strength, plus the word's history and the mechanism gap |
| `mechanism.html` | Six links from galactic sheet to great waves, each labelled, weakest one named |
| `dismissals.html` | Fourteen stock replies and what is wrong with each |
| `objections.html` | The sceptic's best case, six objections, two close to decisive |
| `numbers.html` | The precision ledger, contested figures with best current values |
| `test.html` | Nine falsification tests, mostly free-data exercises, plus the three that settle nothing |
| `watch.html` | Live feeds, the daily programme, and the preparation question that comes apart from the physics |
| `sources.html` | Both sides in one list, including the critical literature |
| `for-models.html` | The reflex named for a human reader, and the brief to hand over |
| `sitemap.html` | The map |
| `404.html` | |

Corpus: `AGENTS.md` plus `corpus/01` to `corpus/10`.

Shared machinery inherited from Grain by Grain: `assets/js/cinematic.js` (SEQUENCE-driven prev/next, to-top, seams, reveal sweep, aria-current), self-hosted Archivo Var and JetBrains Mono Var, kintsugi seams, register chips, stat panels, data tables, stream/chain cards. Added here: a fifth `unsupported` register colour, `.ladder`, `.verdict`, `.dismissal`, `.layers`, `.pull`, `.streams`, `.visually-hidden`. The hero canvas draws nested field arcs instead of sand strata.

## 3. The rules

**REGISTER**
- Five labels: KNOWN (sourced fact or measured record), MODELLED (a calculation anyone can re-run), DISPUTED (live contest, with the point of contest named), SPECULATIVE (physics permits, nothing shown), UNSUPPORTED (looked for, not found). No FICTIONAL here; natural-hazard hypotheses are never labelled fiction.
- UNSUPPORTED is the one addition to the family register and it earns its place: "looked for and not found" is a different and more useful statement than "disputed", and three of the eight ladder rungs need it.

**THE STANDARD, BOTH WAYS**
- Authority is not evidence, in either direction. "A journal said so" and "a channel said so" are the same kind of non-argument.
- Never attack the person, the platform or the audience. If a claim is wrong, name it and show why.
- Distinguish "unproven" from "disproven". Most of this is the first, and saying the second is a factual error.
- Concede the floor before contesting the ceiling. Miyake and superflares go in before any pushback.
- Keep the frontier's own hedges. The books call the timing speculative in their own words, and quoting that is stronger than paraphrasing it away.
- Correct the numbers in whichever direction they need it. The mirror-image failure of reflexive dismissal is reflexive agreement, and it is just as bad: sending someone into an argument carrying a figure that can be checked in thirty seconds is worse than telling them nothing.

**VOICE** (inherited from Grain by Grain, non-negotiable)
- Australian English always. Never an em dash: use a comma, colon, semicolon or full stop.
- No absolutes as rhetoric. Strong principles stated as strong, not dressed as universal laws.
- No backstage talk. Never "this page", "this site", "our research", "the corpus" in front-facing copy. Work things out in .md files.
- No chip-machinery narration. The little tags do their job silently.
- Honest tense. Nothing unbuilt stated as current.
- Plain speaking: every macro number gets a mind's-eye analogy. Nine per cent field loss is one tile in eleven off the roof. The South Atlantic patch has grown by an area near two thirds of the Australian mainland. 170 years of solar records against thousand-year rhythms is judging the tides from one afternoon on the sand.
- Gloss or avoid insider terms. "Excursion" and "reversal" are glossed on every page that uses them, because conflating the two is the most common error in the whole argument.
- Signed "Luke Hayes × Claude". Strange But True Public Source Licence.

**NO SYNTHETIC ART.** No generated imagery anywhere. The hero is an abstract canvas animation, not a depiction, and the comment in `cinematic.js` says so. Diagrams are information graphics, never decoration pretending to be evidence.

**SEPARATE FROM `space-weather-news`.** That repo is Luke's civic monitoring and dissemination project, a 3D newsroom with live feeds. Different thing, do not merge, do not build in it.

## 4. What was checked, and what was not

**Checked against the literature this build (2026-08-01):**
- Micronova adoption: Scaringi et al., *Nature* 604, 447-450, April 2022. Confirmed, and confirmed to be a different object.
- Superflares: Vasilyev et al., *Science*, December 2024. Confirmed, 2,889 flares on 2,527 of 56,450 Sun-like stars, once per century.
- Miyake events: five well confirmed, 12,350 BCE candidate the largest known.
- Field decay: ~9% since 1840, ~5% per century. Gyre-driven decay, *Nature Communications* 2016.
- Pole motion: peak 55-60 km/yr, now ~35 km/yr, largest recorded deceleration, WMM 2025.
- Excursion inventory: Laschamps, Mono Lake, Norwegian-Greenland Sea, Blake established. Hilina Pali unsupported (Liu et al. 2018). Gothenburg not sustained. Michoacan not in the standard inventories; the underlying Mexican work is a palaeosecular variation study, not an excursion claim. Lake Mungo is a real archaeomagnetic record published at ~30 ka, not 24 ka, with its global status contested.
- Adams Event: Cooper et al. *Science* 2021, formal Technical Comments and authors' response.
- Younger Dryas impact: Hiawatha ~58 Ma, platinum spike reattributed, two retractions (2025, 2026).
- 1,500-year Bond cycle: Obrochta et al. 2012 re-examination.

**Not checked, and it is the biggest gap:** the frontier books cite real papers with real reference numbers throughout. Nobody has gone through them one at a time to see which support what they are said to support, which are accurate about a finding but carry more weight than the paper claims, and which are correct in the citation and wrong in the summary. That audit is the single most valuable next contribution, from either direction, and it is named as an open gap on `sources.html` rather than papered over.

## 5. Open items

- **Citation audit** (above). The main one.
- **Mobile navigation.** `.site-nav` hides below 900px with no replacement, inherited from the Grain by Grain chassis. On mobile the only navigation is the injected footer site-map link and the prev/next rail. Family-consistent, and a real usability gap. Fixing it means fixing it across the family, not diverging here.
- **A ladder graphic.** The rung-by-rung table works, and a single honest timeline SVG showing the claimed rungs against the confirmed ones would carry the argument faster than prose does.
- **Miyake events against excursion minima.** The most interesting checkable thing in `test.html`, and it could be done here with public data rather than left as a suggestion.
- **The 30 ka slot.** Two rungs compete for one record. Worth running down properly, since it is the clearest single factual knot in the cadence.

## 6. Log

- **2026-08-01 (first build):** Repo created off the Grain by Grain chassis at Luke's request, after he flagged being tired of defending the micronova against stock dismissals. Both Davidson books read in full (*The Next End of the World*, 109 pp; *Observer Supplement 2022/2023*, 112 pp) rather than worked from priors, per the "foundation reading" instruction. Mainstream literature checked separately on every load-bearing claim. Built `AGENTS.md` plus a ten-file corpus, then 14 pages. Register extended with UNSUPPORTED. Self-gate pass: zero em dashes, AU spelling, no backstage self-reference, no absolutes as rhetoric, all internal links resolve, all pages 200, no console errors, no horizontal overflow at 375 or 1280, ladder collapses correctly on mobile. Cross-linked from `grain-by-grain/threats.html` micro-nova card. The rung-by-rung check was the build's main finding: two of eight rungs hold, and the evenness of the cadence is a property of the list rather than the record, which is conceded on the site before a sceptic can say it.
