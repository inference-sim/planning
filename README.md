# AI Native Systems & LLM-D — Planning Slides

## Prerequisites

[Node.js](https://nodejs.org/) (includes `npx`)

## Slide Decks

| Deck | File | Description |
|------|------|-------------|
| Planning | `slides.md` | Workstreams, goals, and status |
| Playback — Mar 31 2026 | `playback.mar31.2026.md` | Methodology & llm-d findings |

## Viewing the slides

Start either deck by passing its filename to Slidev:

```bash
# Planning slides (default)
npx slidev slides.md

# March 31 playback
npx slidev playback.mar31.2026.md
```

Each command opens the presentation at `http://localhost:3030`.
To run both simultaneously, give the second one a different port:

```bash
npx slidev playback.mar31.2026.md --port 3031
```

## Exporting to PDF

```bash
npx slidev export slides.md
npx slidev export playback.mar31.2026.md
```
