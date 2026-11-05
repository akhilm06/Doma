# Design

> Early concept. Expect this to change substantially, and get gradually more fleshed out, as I progress up the stack.

## Analogies
- doma is an observatory: discovery, melancholy, beauty. 
- doma is a spaceship: play, data, wonder. 
- doma is an atlas: perspective, order, trust.

Borrow the feeling, never the imagery. No space visuals. 
*Never kitsch.*

## Principles

- Apple-like design philosophy and human interface guidelines:
  - Design with intentionality, simplicity, accessibility.
  - Remember the goal is craft and delight. 
- Omarchy's feel: 
  - Hard corners, thin borders, technical feel, disciplined aesthetic. 
    - doma is a scholarship tool from the future. Inspire awe.
- Sophistication:
  - doma is high-brow. Design with restraint. No gimmicks. Embrace dead space. 

## Rules 
- Monospace for technical aspects, serif for within profiles. 
- Color is supplemental cue only, always add visual distinction. 
- Hard edges, fixed position, never touch edges (ING exception).
- doma is lowercase.

## UI Concept 

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

- General:
  - Thin top bar that top left contains logo, then pages. Right side has binary toggles or drop downs.
  - Canvas beneath.
  - doma is a reddish color. Panel background is black tinted blue. 
- Interactive Node Graph (ING) Page
  - Nodes are round.
  - Known works: olive green with a solid border.
  - Lost works: pale blue with a dashed border.
  - Edges visually linked.
  - Top right: search bar with tab that pulls down for filters. 
  - Beneath search bar: where profile content is displayed. Click node to activate. 
  - Bottom left: key. 
- Library
  - The data set backbone, now as an instrument.
  - Feels like Omarchy's activity monitor: dense and granular and valuable. 
