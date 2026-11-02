# Lacuna

## An open-source atlas of synthesized lost work profiles from classical antiquity. 

Pre-alpha; seeking funding. 

## What is Lacuna?
Most of ancient literature has been lost to history. For example, Aristotle wrote an estimated 200 works. We only have access to 31. The existence of these lost works is known to us through fragments, quotations, references, et cetera. 

Specialists devote their careers to collecting and annotating this evidence, but what they provide is often dense, paywalled, and generally inaccessible to nonacademics (for example: Brill's New Jacoby). A useful analogy is the difference between a book on the industrial revolution and a Wikipedia article on it -- both serve useful functions, and are in fact complementary.

Lacuna aims to serve the latter functionality, harnessing modern software and AI-assisted workflows to transform fragments and scattered references of lost works into living profiles, all displayed alongside known works on an interactive node graph.

## What Lacuna Isn't
Lacuna is primarily a conceptual innovation enabled by technological innovation. It is not:

- Reconstructions in the voice of authors.
- Speculation presented as fact.
- Replacement for specialist scholarship.
- A traditional startup. 

## Related Work
- Specialist fragment editions: Tragicorum Graecorum Fragmenta, Brill's New Jacoby.
- Leipzig Open Fragmentary Texts Series.
- Ithaca, Aeneas, Vesuvius Challenge.
- Lost Plays Database (closest analog).
- Wikipedia.

## Old Lacuna

<img width="1920" height="991" alt="image" src="https://github.com/user-attachments/assets/acb04bc1-e203-4ced-8868-c12032e0584f" />

Screenshot from old basic prototype above (rebuild in progress). Consider it a stale artifact, and assume this repo as source of truth. 

Old repo: https://github.com/akhilm06/Lacuna-OLD.

Old demo: https://lacuna-two.vercel.app/.

## Interactive Node Graph (ING)
- ING represents lost works in a pale blue color with dashed border.
- ING represents known works in an olive green color with solid border.
- ING displays known and lost works together, enabling spatial navigation. Click to enter.
- ING contains four types of lost works (each will be made visually distinct):
  - Ghost work (title and author known).
  - Orphan work (title known, author unknown).
  - Stray work (title unknown, author known).
  - Adespota (title and author unknown).
- ING visually displays edges to represent relation (direct quote, commentary, et cetera).
- ING visually displays how much of a lost work is known through node opacity and size.
- ING creates a visceral display of how much of a corpus has been lost, making the gaps, the lacunae, the focal point.

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

## Additional Benefits
- Increased accessibility of domain to autodidacts, students, and curious people. No paywall.
- Valuable open data layer with concordance table. Supports independent research, future digital humanities projects. 
- Faster to build and expand surface area of knowledge. Exists as a complement to specialist resources which require years of expert labor and time.

## Risks
- Fragment epistemology (taxonomy, provenance, scoring against criteria).
- Compounding drift and error (synthesis, verification loop, decision log, forced citations).
- Scholarly trust (maintain dispositionally conservative attitude, transparency).
- Copyrighted materials access (open sources only for evidence, outdated materials flagged). 
- Navigation at scale (filters, search, clustering).

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
  - Milestone one deliverable: public alpha covering Aeschylus.
- Milestone two:
  - Milestone two deliverable: public alpha covering all three tragedians.
- Future deliverables:
  - Timeline format.
  - Frames: preset filters of ING users can explore.
  - Community can submit evidence and receive recognition for contribution.

## Milestone One Tech Stack
- Website: Next.js + TypeScript.
- Data: JSON files in repo, with Zod validation.
- Pipeline: Python + Claude API.
- Hosting: Vercel.

## Built On
- Public-domain editions of quoting authors (Stobaeus, Athenaeus, et cetera).
- Public-domain fragment editions (Nauck, Pearson, Smyth).
- Perseus Digital Library and First1KGreek.
- papyri.info.
- CLTK (Classical Language Toolkit).
- react-force-graph.

## License
- Code: MIT
- Data: CC BY-SA 4.0

## Contributing
Coming Soon. 

## About (written 10/31/2026)

I came up with the concept for Lacuna about six months ago. I was listening to some podcast, and offhand, the host or guest mentioned how the majority of ancient literature has been lost to history. This induced a deep level of sadness within me, and, as I continued to dwell on that feeling, it bloomed into the concept for Lacuna. 

Now, half a year later still, I just can't seem to get Lacuna out of my head, and I'd like to dedicate a portion of my youth working on a project that contributes something of real intellectual value.  

### About Me

I'm 20, and attended WashU for a couple semesters, and then worked on Gr0ve: a startup that transformed open-text feedback into context-aware and actionable business intelligence. If funded, I go full time, and if not, I am interviewing, so part time.

My living costs are low, so all funds go directly into the work. 

Email Me: akhil.muthyala@outlook.com

 



