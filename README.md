# pixel-journey-marketing-clips

**Pixel Journey Marketing Clips & Promo Video Concepts Repository**

> Retro-pixel premium meme-style video campaigns for PxWallet, Hot or Not, Pixals, and the broader Px ecosystem. Structured for high-velocity AI-assisted production while maintaining elite visual consistency, educational value, and joyful community energy.

**Status**: Bootstrapped with robust architecture + shared guide. Ready for concept population from Gemini thread.

**Aligned with**: `pixel-journey-standards` (Existing Public Primitives First, client-side excellence, on-chain entropy patterns) + `pixel-journey-design-system` visual language.

---

## Vision

Every marketing clip should feel like it belongs in the same premium retro-pixel universe:
- Joyful, meme-able, instantly shareable
- Subtly educational (viewers learn *why* self-custody / verifiable mechanics / Pixal ownership rules without feeling lectured)
- Visually cohesive across portrait (Reels/Stories), landscape (YouTube/X), and ad banner formats
- Production quality that makes the broader WAX/Antelope ecosystem proud

This repo exists so we (and future AI agents) can spin up new campaign concepts **fast** while never drifting from the Px brand.

---

## Repo Architecture (Proposed & Implemented)

```
pixel-journey-marketing-clips/
├── README.md
├── Px-Promo-Video-Consistency-Guide.md   # THE shared rulebook for tone, visuals, technical specs across ALL clips
├── shared/
│   ├── moodboard/                        # Common Px characters, UI elements, effects, color refs (static assets added manually)
│   │   ├── README.md
│   │   └── SPRINTS-TODO.md                 # Prioritized list of assets we still need to generate/source
│   ├── prompts/
│   │   └── base-production-prompt.yaml     # Reusable structured base prompt every concept extends
│   └── guides/                           # Future: audio, caption, export checklists
├── concepts/
│   ├── 01-pxwallet-godmode-self-custody/   # Example scaffold (replace/expand with real Gemini concepts)
│   │   ├── README.md                      # Full concept bible + scene breakdown
│   │   ├── production-prompt.yaml         # AI-optimized YAML prompt (extends base)
│   │   ├── moodboard/                     # Concept-specific still references
│   │   └── generated-videos/
│   │       └── README.md                 # Format completion matrix (landscape/portrait/banners) + status
│   ├── 02-hot-or-not-verifiable-chaos/
│   │   └── ... (same inner structure)
│   └── 03-pixal-surviving-mint-flex/     # etc.
└── (future) templates/new-concept-scaffold/
```

**Why this structure?**
- **One folder per concept** keeps everything self-contained and easy to hand to video editors or AI video tools.
- **YAML production prompts** are machine-readable and highly consistent.
- **Moodboards** (per-concept + shared) prevent visual drift.
- **generated-videos/README.md** acts as living status dashboard for multi-format deliverables (critical for Reels + YouTube + Twitter Ads + Stories).
- **Shared guide + base prompt** enforces the "Px Perfection Standard" across the entire campaign library.

---

## Quick Start (Humans & AI Agents)

1. Read `Px-Promo-Video-Consistency-Guide.md` (non-negotiable).
2. Read `shared/prompts/base-production-prompt.yaml`.
3. Pick or create a concept folder under `concepts/`.
4. Flesh out its `README.md` (full narrative + goals) and `production-prompt.yaml` (extends the base).
5. Add moodboard references.
6. Generate videos → update the status matrix in `generated-videos/README.md`.

For new concepts: Copy the scaffold structure from an existing one.

---

## Next Immediate Steps

- [ ] Populate real concepts from our Gemini conversation thread (paste key titles + script outlines here and I'll expand them into full folders).
- [ ] Add initial shared moodboard assets (Pixals, PxWallet hero visuals, Hot or Not arena frames, glassmorphic overlays, retro CRT references).
- [ ] Refine `Px-Promo-Video-Consistency-Guide.md` with exact brand voice examples.
- [ ] Create first 2-3 production prompts and generate v1 clips.

**Repo created & architecture live**: https://github.com/pixel-journey/pixel-journey-marketing-clips

*Built in the spirit of Pixel Journey — educational, joyful, pixel-perfect, and maximally leveraged.*

**Px Standards v0.95 alignment** — This repo itself follows the documentation rule, educational excellence bar, and client-side/public-primitive philosophy (all video production assets & prompts live here; generation happens client/AI-side).