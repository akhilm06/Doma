# Lacuna

## An open-source atlas of synthesized lost work profiles from classical antiquity. 

### Pre-alpha; seeking funding. 

## What is Lacuna?
Most of ancient literature has been lost to history. For example, we know Aristotle wrote an estimated 200 works, but we only have access to 31. The existence of these lost works is known to us through fragments, quotations, references, et cetera. 

Specialists devote their careers to collecting and annotating this evidence, but what they provide is often dense, paywalled, and generally inaccessible to nonacademics (for example: Brill's New Jacoby). A useful analogy is the difference between a book on the industrial revolution versus a Wikipedia article on it -- both serve useful functions, and are in fact complementary.

Lacuna aims to serve the latter functionality, harnessing modern software and AI-assisted workflows to transform fragments and scattered references of lost works into living profiles, all displayed alongside known works on an interactive node graph.

## Old Lacuna

Example screenshot from old basic prototype below (rebuild in progress). Consider it a stale artifact, and this repository to be the source of truth. 

<img width="1920" height="991" alt="image" src="https://github.com/user-attachments/assets/acb04bc1-e203-4ced-8868-c12032e0584f" />

<br>Old repo: https://github.com/akhilm06/Lacuna-OLD.
<br>Old demo: https://lacuna-two.vercel.app/.

## Interactive Node Graph (ING)
- ING refers to lost works as ghost works, represented in a pale blue color with dashed border.
- ING refers to known works as known works, represented in an olive green color with solid border. 
- ING displays ghost works and known works together, enabling spatial navigation. Click to enter.
- ING visually displays edges to represent relation (direct quote, commentary, et cetera).
- ING creates a visceral display of how much of a corpus has been lost, making the absences the focus.

## Lost Work Profile Synthesis
- Profiles are written to be deliberately dry and encyclopedic, like Wikipedia, with an uncertainty system. 
- Profiles include introductions, concepts, contested, et cetera.
- Profiles include terse interpretation sections, drawn from a holistic understanding of the work, and surrounding context drawn from Wikipedia.
  - Apart from this section, profile synthesis is formed solely from hard evidence. 
- Profile generation includes forced citations and verification loop.
- Profiles include transparent decision log, used both by human and AI (see data backbone).

## Data Backbone (The Real Product)
- Quellenforschung is a centuries old field dedicated to source tracing. I don't expect to have an immediate, neat answer.
- Evidence contains taxonomy, provenance, and rubric scoring.
- Scoring includes transparent decision log, used both by human and AI.
  - Decision logs record written justifications of any informed choice.
  - Decision logs consult and cite Wikipedia articles, and from which source that claim is derived, rather than relying on model training data. 
  - Decisions can be flagged for human review.
    
## Philosophy
- Commitment to factuality and transparency.
- Commitment to delightful and intuitive user experience.
- Commitment to provide real intellectual value.

## Additional Benefits
- Increased accessibility of domain to students, autodidacts, and curious people. No paywall.
- Valuable open data layer. Supports independent research, future digital humanities projects. 
- Less laborious and time consuming to create and deploy. 
- Greater surface area of knowledge.

## Risks
- Fragment epistemology (taxonomy, provenance, scoring against criteria).
- Compounding drift and error (synthesis, verification loop, decision log, forced citations).
- Scholarly trust (dispositionally conservative attitude, transparency).
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
    - Deliverable: a public alpha covering all three tragedians.
  - Concurrently:
    - Run outreach on professors, teachers, provide simple lesson plan.
    - Make dev log videos.
    - Make public documentation.
  - Deliverable: finish tragedians.  

## Built On
- Perseus Digital Library
- CLTK (Classical Language Toolkit)
- react-force-graph

## Contributing
Coming Soon. 

## License
- MIT

## About (written 10/31/2026)

I came up with the concept for Lacuna about six months ago. I was listening to some podcast, and offhand, the host or guest mentioned how the majority of ancient literature has been lost to history. This induced a deep level of sadness within me, and, as I continued to dwell on that feeling, it bloomed into the concept for Lacuna. 

Now, half a year later still, I just can't seem to get Lacuna out of my head, and I'd like to dedicate a portion of my youth working on a project that contributes something of real intellectual value.  

### About Me

I'm 20, and attended WashU for a couple semesters, and then worked on Gr0ve: a startup that transformed open-text feedback into context-aware and actionable business intelligence. If funded, I go full time, and if not, I am interviewing, so part time. My living costs are low, so all funds go directly into the work. 

Email Me: akhil.muthyala@outlook.com

 



