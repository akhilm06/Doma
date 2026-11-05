# doma

*An open-source atlas of synthesized lost work profiles from classical antiquity.*

δῶμα -- Ancient Greek for house.

> pre-alpha: seeking funding.

```
┌──────────────────────────────────────────────────────────────────────────────┐
│ doma   graph   library   method                                     settings │
├──────────────────────────────────────────────────────────────────────────────┤
│ Aeschylus:                                    ┌────────────────────────────┐ │
│ 70-90 plays written. 7 survive.               │ search works…              │ │
│                                               └────────────┬─────────┬─────┘ │
│            ●                                               │ filters │       │
│             ╲            ●                                 └─────────┘       │
│              ╲          ╱                                                    │
│       ● ─ ─ ─ ○────────○                      ┌────────────────────────────┐ │
│               │         ╲                     │ Myrmidons                  │ │
│               │          ● ─ ─ ●              │ ghost work · Aeschylus     │ │
│          ●    │                               │ ────────────────────────── │ │
│           ╲   ○                  ●            │                            │ │
│            ╲ ╱ ╲                ╱             │                            │ │
│             ●   ○─ ─ ─ ─ ─ ─ ─ ○              │                            │ │
│                                 ╲             │                            │ │
│                 ●                ●            │                            │ │
│                                               │       Content here.        │ │
│ ┌────────────────────┐                        │                            │ │
│ │                    │                        │                            │ │
│ │     Key here.      │                        │                            │ │
│ │                    │                        │                            │ │
│ │                    │                        │                            │ │
│ └────────────────────┘                        └────────────────────────────┘ │
│                                                                              │
└──────────────────────────────────────────────────────────────────────────────┘
```

Concept art.

## What is doma?
Most of ancient literature has been lost to history. For example, Aristotle wrote an estimated 200 works. We only have access to 31. The existence of these lost works is known to us through fragments, quotations, references, et cetera. 

Specialists devote their careers to collecting and annotating this evidence, but what they provide is often dense, paywalled, and generally inaccessible to nonacademics (for example: TrGF). A useful analogy is the difference between a book on the industrial revolution and a Wikipedia article on it -- both serve useful functions, and are in fact complementary.

doma aims to serve the latter functionality, harnessing modern software and AI-assisted workflows to transform fragments and scattered references of lost works into living profiles, all displayed alongside known works on an interactive node graph.

## What doma Isn't
doma is primarily a conceptual innovation enabled by technological innovation. It is not:
- Reconstructions in the voice of authors.
- Speculation presented as fact.
- Replacement for specialist scholarship.
- A traditional startup. 

## Related Work
- Specialist fragment editions: Tragicorum Graecorum Fragmenta (TrGF), Brill's New Jacoby.
  - Dense, narrow, often paywalled or difficult to access, built on years of expert labor.
- Leipzig Open Fragmentary Texts Series (LOFTS), Digital Fragmenta Historicorum Graecorum (DFHG).
  - Open digital editions that link fragments to their source texts. 
- FragTrag (Greek Fragmentary Tragedians Online).
  - Open edition of 45 minor tragedians. 
- papyri.info, Digital Corpus of Literary Papyri (DCLP).
  - Open papyrus transcriptions. Raw evidence.
- Ithaca, Aeneas, Vesuvius Challenge.
  - AI that restores lost text. 
- Lost Plays Database.
  - doma’s closest analog. doma applies its model to antiquity.
- Wikipedia.
  - Strong for famous lost works, otherwise sparse or nonexistent.
    
None I found turns evidence for antiquity's lost works into cited, living profiles.

doma does, built on top of a novel open data layer and concordance table that supports independent research and future digital humanities projects, while also keeping the knowledge work accessible to non-scholars: autodidacts, students, and curious people.

## Interactive Node Graph (ING)
- ING represents lost works in a pale blue color with dashed border.
- ING represents known works in an olive green color with solid border.
- ING displays known and lost works together, enabling spatial navigation. Click to enter.
- ING contains four types of lost works (each will be made visually distinct; see table below).
- ING visually displays edges to represent relation (direct quote, commentary, et cetera).
- ING visually displays how much of a lost work is known through node opacity and size.
- ING creates a visceral display of how much of a corpus has been lost, making the gaps, the lacunae, the focal point.

| Lost work type | Title   | Author  |
|----------------|---------|---------|
| Ghost work     | known   | known   |
| Orphan work    | known   | unknown |
| Stray work     | unknown | known   |
| Adespota       | unknown | unknown |

## Lost Work Profile Synthesis
- Profiles are written to be deliberately dry and encyclopedic, like Wikipedia, with an uncertainty system. 
- Profiles include introductions, concepts, contested, et cetera. Profile length scales with evidence. Thin profiles are celebrated.  
- Profiles include terse interpretation sections, drawn from a holistic understanding of the work, and surrounding context drawn from Wikipedia.
  - Apart from interpretation and context, profiles draw solely from hard evidence.
- Profile generation includes forced citations for every claim and a verification loop.
- Profiles include transparent decision log, used both by human and AI (see data backbone).

## Data Backbone
- Quellenforschung is a centuries-old field dedicated to source tracing. I don't expect to have an immediate, neat answer.
- Each piece of evidence carries license, taxonomy, provenance, and rubric scoring.
- Scoring includes transparent decision log, used both by human and AI.
  - Decision logs record written justifications of any informed choice with links to relevant evidences.
  - When necessary, decision logs additionally consult and cite Wikipedia articles for germane historical context, while also evaluating and pointing to the origin of that claim, rather than relying solely on model training data.
  - Decisions can be flagged for human review.

## Sourcing and Copyright
- Evidence is curated and entered by hand. AI-drafted fields are confirmed by a human.
- Evidence is sourced solely from public-domain and openly licensed material.
- Modern editions (for example: Radt, TrGF) are used as an index for sourcing evidence. They are cited, not reproduced.
- Translations are public domain where available. Otherwise machine-assisted and labeled as such.

## Roadmap 
- Milestone one (minimum lovable product):
  - Month one (data foundations):
    - Schema, evidence taxonomy, source provenance.
    - Evidence ingestion, deduplication, and evaluation workflow.
    - Research and read. Gather set of hand-picked evidence. Establish written culture.
    - Craft user experience, brand, value propositions, product thinking, et cetera.
    - Run outreach on classicists for advisor role and join community. 
    - Deliverable: working data set and public methodology document. 
  - Month two (profile synthesis):
    - Profile synthesis workflow: structure/sections, decision log, forced citations, et cetera.
    - Stable, citable versions.
    - Evaluations.
    - Deliverable: Aeschylus's profiles and published evaluation results. 
  - Month three (ING and launch):
    - Build the interactive node graph.
    - Add search, filter, and error flag functionality.
    - Explainer video and documents.
    - Launch on Hacker News, LessWrong, et cetera.
  - Concurrently:
    - Run outreach on professors, teachers, provide simple lesson plan.
    - Continue to iterate on previously implemented features.
    - Learn Ancient Greek.
  - Milestone one deliverable: public alpha covering Aeschylus.
- Milestone two:
  - Milestone two deliverable: public alpha covering all three tragedians.
- Future deliverables:
  - Timeline and shelf format.
  - Frames: preset filters of ING users can explore.
  - Community can submit evidence and receive recognition for contribution.

## Main Risks
- Fragment epistemology.
- Scholarly trust and error/drift.
- Copyrighted material access.

Each is addressed in the above sections. 

## Milestone One Tech Stack
- Data: one JSON file per record, in git.
- Schema: Pydantic.
- Pipeline: Python + Claude API. Managed with uv, linted with ruff, tested with pytest.
- Site: Python + Jinja2 (static).
- Hosting: static, host-independent.

## Built On
- Public-domain editions of quoting authors (Stobaeus, Athenaeus, et cetera).
- Public-domain fragment editions (Nauck, Pearson, Smyth).
- Perseus Digital Library and First1KGreek.
- papyri.info.
- CLTK (Classical Language Toolkit).
- sigma.js + graphology.

## License
- Code: MIT
- Data: CC BY-SA 4.0

## Contributing
Coming Soon. 

## About (written 10/31/2026)

I came up with the concept for doma about six months ago. I was listening to some podcast, and offhand, the host or guest mentioned how the majority of ancient literature has been lost to history. This induced a deep level of sadness within me, and, as I continued to dwell on that feeling, it bloomed into the concept for doma. 

Now, half a year later still, I just can't seem to get doma out of my head, and I'd like to dedicate a portion of my youth working on a project that contributes something of real intellectual value.  

### Prior Prototype

doma began as Lacuna, a basic prototype ([repo](https://github.com/akhilm06/Lacuna), [demo](https://lacuna-two.vercel.app/)). A full rebuild is in progress. Assume this repo as the source of truth.

<details>
<summary>Screenshot</summary>

<img width="1920" height="991" alt="Lacuna prototype" src="https://github.com/user-attachments/assets/acb04bc1-e203-4ced-8868-c12032e0584f" />

</details>

### About Me

I'm 20, and attended WashU for a couple semesters, and then worked on Gr0ve: a startup that transformed open-text feedback into context-aware and actionable business intelligence. If funded, I go full time, and if not, I am interviewing, so part time. 

My living costs are low, so all funds go directly into the work. 

Email Me: akhil.muthyala@outlook.com

PS: Just started learning Latin, but looks like I'm swapping to Ancient Greek :/.


