# Micronova and Excursions: Playbook

Repo: `githublocal\micronova-and-excursions`
Public target: `https://auraofintelligence.github.io/micronova-and-excursions/`
Dev server: `.claude/launch.json` name `micronova`, port 4233.
Read this file first every session.

## 1. North star

**The point is not adjudication.** Luke, 1 August 2026: "the point is not making a decision, it's demonstrating that the world is going to end again. we live in a calm period. we should be preparing for the next inevitable end rather than resting on our laurels."

So the spine is: **the quiet is the anomaly, it has broken before, it will break again, and the rational response is to build for it rather than to wait to be told when.** The ledger machinery underneath serves that; it is armour, not the argument. A page that reads like a scoreboard has failed.

**And the micronova is not the cadence.** Luke, same day: "micro nova is almost certain even if there is not a clean predictable cycle." He is right and the first build got this structurally wrong. Section 5.2 of *The Next End of the World* argues that any threshold-reaching change in the space environment can induce an outburst; a regular cycle is a convenience, not a requirement. Losing the cadence costs the mechanism nothing. Never stack the mechanism on top of the clock again.

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
| `excursions.html` | The eight-rung cadence checked rung by rung. Two accepted, three proposed but unconfirmed, two absent. |
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
- Excursion inventory: ~13 well documented across the Brunhes; five most studied are Mono Lake, Laschamp, Blake, Iceland Basin, Pringle Falls. Laschamp 42.2-41.5 ka, field down as much as 90%. Mono Lake ~34.5 ka, accepted, with a live type-locality dispute (Kent et al. 2002 argued the Wilson Creek record is Laschamp misdated).
- **Proposed but not accepted** (Channell et al. 2020, last 30 kyr): Sterno-Etrussia ~2.7 ka, Tianchi ~10 ka, Gothenburg ~12 ka, Iberian Margin MD01-2444 ~13 ka, Hilina Pali ~19 ka, Lake Mungo ~26 ka, Rockall ~26 ka. Reasons given for holding them out: remagnetisation, sediment disturbance, facies changes, reinforcement syndrome.
- Hilina Pali is **actively contested**, not dead: Nawrocki et al. 2018 (Boreas, Ukrainian loess c. 18 ka) + published Comment on reinforcement syndrome + Reply; Liu et al. 2018 (EPSL 492, Black Sea, negative); Nowaczyk et al. 2025 (Drake Passage, negative but allows regional relevance or too-short duration); Haflidason et al. 2022 (Polar Ural lakes, distinct event ~20 ka); Scheidt et al. 2025 (JGR, Polar Urals, 23.6-14.8 ka cal BP).
- Lake Mungo: Barbetti and McElhinny 1976 found TWO episodes, main 30,780+/-520 to 28,140+/-370 14C BP and a second ~26,000 14C BP; the reviews carry it at ~26 ka, so the ladder's 24 ka rung is about right. Original ages are uncalibrated radiocarbon.
- Michoacan: no excursion of that name at any status. TMVB work proposes excursions at ~1 Ma (intra-Jaramillo); the last-30-kyr Mexican records are palaeosecular variation.
- 48 ka: nothing proposed. The Olby/Laschamps dating spread (Plenier et al. 2007, Olby ~37 ka vs Laschamps flows 41.9 ka) is about the duration of one event, not a second one.
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

- **2026-08-01 (first build):** Repo created off the Grain by Grain chassis at Luke's request, after he flagged being tired of defending the micronova against stock dismissals. Both Davidson books read in full (*The Next End of the World*, 109 pp; *Observer Supplement 2022/2023*, 112 pp) rather than worked from priors, per the "foundation reading" instruction. Mainstream literature checked separately on every load-bearing claim. Built `AGENTS.md` plus a ten-file corpus, then 14 pages. Register extended with UNSUPPORTED. Self-gate pass: zero em dashes, AU spelling, no backstage self-reference, no absolutes as rhetoric, all internal links resolve, all pages 200, no console errors, no horizontal overflow at 375 or 1280, ladder collapses correctly on mobile. Cross-linked from `grain-by-grain/threats.html` micro-nova card. The rung-by-rung check was the build's main finding.

- **2026-08-01 (research correction pass):** Luke pushed back on the ladder verdicts with "don't rely on your memory, do some research into these", and he was right to. The first pass leaned on search-result summaries. Going to the palaeomagnetic literature changed four of the eight rungs and reversed the headline.

  **What changed, and all four corrections run in the ladder's favour:**
  - **Hilina Pali** went from "no evidence, this rung is empty" to **actively contested**. Nawrocki et al. 2018 published it in Ukrainian loess at c. 18 ka; there is a formal Comment accusing it of reinforcement syndrome and a Reply; Liu et al. 2018 and Nowaczyk et al. 2025 are negative, and the 2025 null explicitly allows that the event was regional or too brief to register. Polar Ural lake cores recorded a distinct event near 20 ka and are being worked on now.
  - **Lake Mungo** went from "misdated by six thousand years" to **correctly placed**. Barbetti and McElhinny 1976 found two episodes, and the standard reviews carry the younger one at ~26 ka. My "published age is ~30 ka" was reading only the first episode.
  - **Gothenburg** went from "not sustained" to **proposed and never confirmed**, with regional claims in Barents Sea sediments and as an Allerod marker in the Central Russian Upland.
  - **The framing** went from "two of eight hold" to "two accepted, three published-but-unconfirmed, two with nothing behind them". Three ladder rungs sit on Channell et al. (2020)'s list of proposed excursions. They are not invented, and "there is nothing there" is wrong.

  **What survived:** Michoacan (no such excursion at any status) and the 48 ka rung (nothing proposed there). Laschamp and Mono Lake accepted.

  **The cadence critique got sharper rather than weaker**, and this is the better version to carry: the full set of excursions proposed for the last 30 kyr lands at ~2.7, 10, 12, 13, 19, 26 and 26 ka. That is a scatter with two candidates nearly on top of each other, not a beat. You cannot accept the unconfirmed events that fill the ladder and reject the unconfirmed events that break it. One standard of proof, applied to all of them.

  Propagated through `excursions.html`, `settled.html`, `index.html`, `dismissals.html`, `objections.html`, `sitemap.html`, `sources.html`, `AGENTS.md` and corpus files 02, 03, 05, 06, 07, 08, 09, 10. Also replaced the favicon, which had been a straight copy of Grain by Grain's sand-strata mark: now a gold sun inside a shed shell, cradled by two teal field arcs, so the two sites are distinguishable in a tab strip.

  **Lesson worth keeping:** on this corpus the first-pass verdicts were systematically harsher than the literature supports, in exactly the direction [[note-to-the-next]] warns about. Search-result summaries flatten "proposed but unconfirmed" into "unsupported". Those are different words and the difference is the whole argument.

- **2026-08-01 (the reframe):** Two corrections from Luke, both structural, both mine to have caught.

  **First:** the site was answering "is the micronova true?" when the question is "what does the record say about how often the quiet ends?" Built `calm.html` as the new second page and the thesis of the whole thing: the Holocene as the anomaly rather than the baseline. Greenland ice shows temperature lurches of 5 to 16 degrees inside decades, roughly every 1,500 years, synchronous across the North Atlantic and east Asia within 5 to 10 years. None in the Holocene. Richerson, Boyd and Bettinger (2001, *American Antiquity*) is the load-bearing citation: agriculture was impossible in the Pleistocene because of the variability and close to mandatory once the Holocene settled. Everything we call civilisation sits inside the one calm window, and the mainstream explanation for civilisation existing at all is that calm. Added a return-period table across seven hazard classes, all mainstream, all with published intervals. The "overdue" framing is explicitly corrected as a gambler's fallacy, which strengthens rather than weakens the case: random arrival at those intervals still climbs towards certainty over the span anyone builds for.

  **Second, and the more important one:** the build had the micronova sitting on top of the cadence, so it inherited the cadence's weakness. That is backwards. Restructured the layers everywhere so the clock is last and weakest and the mechanism does not depend on it:
  - L1 excursions happen: **known**
  - L2 the Sun does things far past our records: **known**
  - L3 the Sun's surroundings change enough to matter: **known**, and this is new
  - L4 that makes a star like ours shed a shell: **speculative**, the only genuinely open step
  - L5 on a clean 6,000 or 12,000-year clock: **disputed**, weakest, and least needed

  **The L3 find matters and I had missed it.** Opher et al., *Nature Astronomy*, 10 June 2024: about 2 Ma the Solar System crossed a cold dense interstellar cloud dense enough to compress the heliosphere to ~0.22 AU, inside Earth's orbit, leaving the planet in raw interstellar medium. A second likely episode ~7 Ma at the Local Bubble edge, and work under way to find the fingerprint in lunar soil. Plus the Radcliffe Wave (Alves et al., *Nature*, Jan 2020), a rippling gas ribbon ~3 kpc long through the Sun's neighbourhood. Mainstream astronomy now says the Sun's environment changes drastically. That is not the frontier's trigger, and it is a much stronger setting than the first build gave it. Split `mechanism.html` link 2 accordingly: a compressed bubble is not an accumulated shell, and both halves now carry their own label.

  Nav restructured (`The calm` added, `Numbers` moved out of the top bar and left to the rail, inline links and the map). SEQUENCE updated. 15 pages now. Verified: zero em dashes, all links resolve, all 200, no overflow.

  **Lesson worth keeping:** the first build's failure was not a wrong fact, it was a wrong dependency graph. Bundling a strong claim with a weak one and labelling the bundle by its weakest member is the same flattening error as reading "proposed but unconfirmed" as "unsupported". Check what actually depends on what before assigning a chip.

- **2026-08-01 (the static Solar System assumption):** Luke, on the L3 framing: "you think the planets stayed where they are when the medium changes. how cute." He was right and it was a real hole, not a nitpick. I had written the environment as changing around a Solar System held fixed, and never examined the second half.

  What the literature actually says:
  - **The orbits are not fixed and never were.** Milankovitch: eccentricity near 100 and 405 kyr, obliquity 22.1 to 24.5 degrees on 41 kyr, precession near 20 kyr. Those switch the ice ages on and off, which means the glacial rhythm making the Holocene look unusual *is itself an orbital rhythm*. That should have been on the page from the start, since the whole calm-as-anomaly argument rests on it.
  - **The configuration is chaotic.** Laskar: divergence by a factor of ten every 10 Myr, hard limit near 50 to 60 Myr on any unique astronomical solution. Beyond that, geology constrains the astronomy rather than the reverse.
  - **And the isolated-system assumption is now retired, in Kaib and Raymond's own words:** "most prior works approximate the solar system as an isolated system and neglect our surrounding Galaxy" (*ApJL*, 2024, arXiv:2402.08734). Passing field stars perturb the giant planets, shorten the window on Earth's orbital history by a further ~10%, and open orbital paths before ~50 Ma that no earlier model produced. HD 7977 passed exceptionally close 2.8 Ma. The 2025 follow-up (arXiv:2505.04737) puts the system ~50% less stable with flybys included, Pluto at ~5% destabilisation over 5 Gyr against a prior assumption of complete stability.
  - **And a visitor is on the record within the human span:** Scholz's Star passed ~0.82 light years, five times nearer than Proxima is now, about 70,000 years ago, through the outer Oort cloud. Identified only in 2015.

  Added as section three of `calm.html`, with the limit stated plainly in the same block: every one of those effects is gravitational and runs over millions of years, not centuries, so the stronger claim that a charge-environment change rearranges things on a human timescale goes past these papers and is marked as going past them.

  **Lesson worth keeping, and it is the same one twice now.** Both of Luke's catches this session were the same species of error: an unexamined assumption inherited from the consensus framing, not a wrong fact. First the micronova stacked on the cadence, then the medium changing around a static Solar System. In both cases the consensus itself had already moved and I was carrying the older, tidier picture. Check what the framing assumes before checking what the claims assert.
