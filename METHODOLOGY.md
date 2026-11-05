# Methodology

> Early concept, not near finalized, and a deliverable of month one. High leverage product decisions are downstream of this significant document. Expect this to change substantially, and get gradually more fleshed out, as I progress in the completion of doma.

Quellenforschung is a centuries-old field dedicated to source tracing. I don't expect to have an immediate, neat answer.

Let's work our way up.

## Principles
- Every granular aspect of a claim or decision must be rigorously cited with a source. Do not rely on model data for context.
  - Sources can be evidence, which make up the content of a profile, or Wikipedia, which grounds the why of a decision in something past model training data. Interpretation is not an exception.
- Conservative disposition: err towards less, always. Allow thinness.
- Embrace ambiguity and fuzziness. Uncertainty is shown, no speculation dressed up as confident fact.
- Write plainly and encyclopedically: no flourish or rhetoric.
- Prioritize ultra simplicity and robustness and versatility. No clever implementations.
- Human in the loop: doma believes humans and artificial intelligences serve unique complementary functions, and harnesses the ability of both. Specialist humans have authority over AI.

## Sourcing and Copyright
- Evidence is curated by human hand.
- Evidence is sourced solely from public-domain and openly licensed material.
- Modern editions, such as Radt, TrGF are used as an index, not reproduced.
- Wikipedia is cited by permanent revision link and access date, never by live article.

## Records
- Lost work: id, title, author, genre, date of composition.
- Evidence: a piece of evidence for a lost work, linked to it by id.

## Evidence

### Content
- Evidence is recorded in Ancient Greek, with both public domain and machine assisted translations (only the latter if necessary).

### Taxonomy (what kind of thing is this?)
- Evidence type: fragment or testimonium; verbatim quotation, paraphrase, et cetera.

### Provenance (where it came from, and how?)
- Source and locus.
- Modern index number.
- Translator or model.
- Who entered this evidence and when.
- License.

## Initial Ingestion
- Index-driven.
- AI drafts remaining fields to speed this up.
- Human confirmation, always.

## Lost Work Node and Profile Synthesis

### Profile form
- Profiles include introduction, concepts, contested, terse interpretation sections, et cetera.
  - Introduction and interpretation sections are allowed to additionally draw from Wikipedia, with sources marked.
  - Profiles are written with a strict form per section, including an uncertainty system.
- Profile length scales with evidence. Thin profiles are celebrated.
- Informed choices are logged in the decision log.

### Profile synthesis workflow
- Will delve further in month two.

### Decision log
- Decision logs record written justifications of any informed choice with links to relevant sources (evidence or Wikipedia).
- Decisions can be flagged for human review.
- Humans can use decision log, but are subject to the same rigor and level of transparency.

### Verification loop
- Profile generation and decisions require strict citations with no hallucinated information.
- A verification loop checks that every claim is supported by its cited evidence.
- The loop runs for a maximum number of rounds. Claims still unsupported are flagged for human review.
- Verification status is recorded per claim, with the model and date that ran it.

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
