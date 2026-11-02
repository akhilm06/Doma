# Lacuna

## An open-source atlas of synthesized lost work profiles from classical antiquity. 

### Pre-alpha; seeking funding. 

## What is Lacuna?
Most of ancient literature has been lost to history. For example, Aristotle wrote an estimated 200 works. We only have access to 31. The existence of these lost works is known to us through fragments, quotations, references, et cetera. 

Specialists devote their careers to collecting and annotating this evidence, but what they provide is often dense, paywalled, and generally inaccessible to nonacademics (for example: Brill's New Jacoby). A useful analogy is the difference between a book on the industrial revolution and a Wikipedia article on it -- both serve useful functions, and are in fact complementary.

Lacuna aims to serve the latter functionality, harnessing modern software and AI-assisted workflows to transform fragments and scattered references of lost works into living profiles, all displayed alongside known works on an interactive node graph.

## What Lacuna Isn't
- Reconstructions in the voice of author.
- Speculation presented as fact.
- Replacement for specialist scholarship.

## Old Lacuna

Example screenshot from old basic prototype below (rebuild in progress). Consider it a stale artifact, and this repository to be the source of truth. 

<img width="1920" height="991" alt="image" src="https://github.com/user-attachments/assets/acb04bc1-e203-4ced-8868-c12032e0584f" />

<br>Old repo: https://github.com/akhilm06/Lacuna-OLD.
<br>Old demo: https://lacuna-two.vercel.app/.

## Interactive Node Graph (ING)
- ING represents lost works in a pale blue color with dashed border.
- ING represents known works in an olive green color with solid border.
- ING displays ghost works and known works together, enabling spatial navigation. Click to enter.
- ING contains four types of lost works (each will be made visually distinct):
  - Ghost work (title and author known).
  - Orphan work (title known, author unknown).
  - Stray work (title unknown, author known).
  - Adespota (title and author unknown).
- ING visually displays edges to represent relation (direct quote, commentary, et cetera).
- ING visually displays how much of a lost work is known through node opacity and size. 
- ING creates a visceral display of how much of a corpus has been lost, making the absences the focus.

## Work Profile Synthesis
- Profiles are written to be deliberately dry and encyclopedic, like Wikipedia, with an uncertainty system. 
- Profiles include introductions, concepts, contested, et cetera. Thin profiles are a feature, but less emphasized.
- Profiles include terse interpretation sections, drawn from a holistic understanding of the work, and surrounding context drawn from Wikipedia.
  - Apart from this section, profile synthesis displayed is formed only from hard evidence. 
- Profile generation includes forced citations for every claim and a verification loop.
- Profiles include transparent decision log, used both by human and AI (see data backbone).

## Data Backbone
- Quellenforschung is a centuries-old field dedicated to source tracing. I don't expect to have an immediate, neat answer.
- Scoring includes transparent decision log, used both by human and AI.
  - Decision logs record written justifications of any informed choice.
  - Decision logs consult and cite Wikipedia articles for additional historical context when needed, while also evaluating the origin of that claim, rather than relying solely on model training data.
  - Decisions can be flagged for human review.

## Sources and Copyright
The standard editions covering the tragedians are under copyright and inaccessible to Lacuna. Instead:
- Evidence is sourced solely from public-domain and openly licensed material.
- Each piece of evidence carries license, taxonomy, provenance, and rubric scoring.
- Translations are public domain where available. Otherwise machine-assisted and labeled as such.
    WILL COMPLETE COPY RIGHT STUFF TOMMOROW beginning hand made, then delegated to AI. 
## Philosophy
- Commitment to factuality and transparency.
- Commitment to delightful and intuitive user experience.
- Commitment to providing real intellectual value.

## Additional Benefits
- Increased accessibility of domain to autodidacts, students, and curious people. No paywall.
- Valuable open data layer. Supports independent research, future digital humanities projects. 
- Faster to build and expand surface area of knowledge. Exists as a complement to specialist resources which require years of expert labor and time.

## Risks
- Fragment epistemology (taxonomy, provenance, scoring against criteria).
- Compounding drift and error (synthesis, verification loop, decision log, forced citations).
- Scholarly trust (maintain dispositionally conservative attitude, transparency).
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
    - Pilot on one author.
    - Evaluations.
    - Deliverable: about 80 Aeschylus profiles and published evaluation results. 
  - Month three (ING):
    - Build the interactive node graph.
    - Add search, filter, and error flag functionality.
    - Expand to Sophocles and Euripides.
    - Upload short explainer video.
    - Get project production ready.
    - Upload online to Hacker News, Less Wrong, et cetera.
    - Run outreach on intellectuals who would value Lacuna. 
  - Concurrently:
    - Run outreach on professors, teachers, provide simple lesson plan.
    - Make dev log videos.
    - Make public documentation.
  - Milestone one deliverable: a public alpha covering all three tragedians.

## Built On
- Public-domain fragment editions (Nauck, Pearson, Smyth)
- Perseus Digital Library and First1KGreek
- papyri.info
- CLTK (Classical Language Toolkit)
- react-force-graph

## License
- Code: MIT
- Data: CC BY-SA 4.0

## Contributing
Coming Soon. 

## About (written 10/31/2026)

I came up with the concept for Lacuna about six months ago. I was listening to some podcast, and offhand, the host or guest mentioned how the majority of ancient literature has been lost to history. This induced a deep level of sadness within me, and, as I continued to dwell on that feeling, it bloomed into the concept for Lacuna. 

Now, half a year later still, I just can't seem to get Lacuna out of my head, and I'd like to dedicate a portion of my youth working on a project that contributes something of real intellectual value.  

### About Me

I'm 20, and attended WashU for a couple semesters, and then worked on Gr0ve: a startup that transformed open-text feedback into context-aware and actionable business intelligence. If funded, I go full time, and if not, I am interviewing, so part time. My living costs are low, so all funds go directly into the work. 

Email Me: akhil.muthyala@outlook.com

 



