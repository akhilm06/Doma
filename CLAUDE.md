# CLAUDE.md

## Project
Doma is an open-source atlas of lost works from classical antiquity. Doma transforms fragments and scattered references into synthesized, living profiles, displayed alongside surviving works on an interactive node graph.

## Further Context
- README.md: vision, roadmap, related work.
- METHODOLOGY.md: read before any change to schema, evidence, scoring, or synthesis.
- DESIGN.md: read before any change to visual design, layout, or the ING.

## Philosophy
- Accessibility to non-specialists.
- Maintain sophistication and trust.
- Intuitive and delightful user experience. 

## Stack
- Data: one JSON file per record, in git.
- Schema: Pydantic.
- Pipeline: Python + Claude API. Managed with uv, linted with ruff, tested with pytest.
- Site: Python + Jinja2 (static).
- Hosting: static, host-independent.

## Constraints
- Every product decision is upstream of deserving scholarly trust. Doma is rigorous and conservative: when in doubt, choose correctness over speed or novelty.
- Doma is open source and prides itself on simple, transparent, robust code: prefer readability over cleverness, and add no dependency without justification.
- Only make a decision you can justify. Consider the whole system before deciding, not just the local fix.
- Push back on ideas that are technically or intellectually unsound.
- **Only I write or edit files, unless stated otherwise.**
