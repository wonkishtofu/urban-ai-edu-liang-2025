# Urban AI Education — an interactive reading of Liang (2025)

A two-page interactive companion to Xiaofan Liang's working paper **"Educating Urban AI: A Pedagogical Framework for Teaching Artificial Intelligence in Urban Planning"** (SocArxiv, 2025).

**Live site:** https://wonkishtofu.github.io/urban-ai-edu-liang-2025/

---

## What this is

Two self-contained HTML pages, no build step, no dependencies:

- **[`index.html`](./index.html)** — an interactive summary in the spirit of Bret Victor's explorable explanations. Seven hands-on widgets: the criticality matrix, a tension map for pedagogical trade-offs, a data-center siting calculator, zoning failure-mode reader, task-reshuffling exercise, and more.
- **[`guide.html`](./guide.html)** — a guided reading of the paper itself. Ten stops with a sticky table of contents, scroll-spy, hover annotations, and inline interactives at the spots where the argument turns.
- **[`style-guide.html`](./style-guide.html)** — *Conservatory v0.1*, a biophilic design system (tokens, type, components, motion, and mockups for mobile / GIS / CRM / AI surfaces). Influenced by Gardens by the Bay.
- **[`style-guide-v02.html`](./style-guide-v02.html)** — *Conservatory v0.2*, repositioned as **Tropical Civic Futurism** — heavier framing, institutional contrast, demoted green, climatological motion, three operational density modes, and a proper tropical civic cartography. Hosted alongside the paper site for convenience.
- **[`style-guide-v03.html`](./style-guide-v03.html)** — *Conservatory v0.3*, evolved into a **Spatial Operating System**. Adds spatial primitives (district, corridor, node, layer-stack), cognitive zones, an urban-intelligence cartography, temporal layers (historical / live / future), an explicit trust layer (lineage, confidence band, policy badge, temporal validity, review status), monsoon logic, Review Room mode, Scenario Theatre, and Urban Memory strata.

The two paper pages link to each other; start from either.

## Why

Liang's paper makes a structural case for Urban AI as a distinct subfield — one that foregrounds governance, professional identity, and the socio-technical consequences of AI in cities, rather than treating AI as a neutral tool. The pages are designed to make that argument *legible by manipulation*: you can drag the criticality matrix, reshuffle planning tasks under AI, and feel the trade-offs the paper names.

## Visual design

The theme is **Cloud Forest Conservatory** — pale-mint paper, deep forest ink, and warm bronze accents, with subtle greenhouse-grid backgrounds. A biophilic palette inspired by Singapore's Gardens by the Bay.

## Running locally

```bash
git clone https://github.com/wonkishtofu/urban-ai-edu-liang-2025.git
cd urban-ai-edu-liang-2025
open index.html
```

No server, no toolchain. Plain HTML, vanilla JS, SVG.

## Source

Liang, Xiaofan. (2025). *Educating Urban AI: A Pedagogical Framework for Teaching Artificial Intelligence in Urban Planning.* SocArxiv preprint.

## License

MIT — see [LICENSE](./LICENSE). The interactive site is an independent reading of the paper; the paper itself remains the author's work.
