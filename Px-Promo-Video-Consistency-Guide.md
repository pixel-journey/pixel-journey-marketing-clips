# Px-Promo-Video-Consistency-Guide.md

**THE Shared Rulebook for All Pixel Journey Marketing Clips**

*Part of pixel-journey-marketing-clips — Enforces the Px Perfection Standard across every promo video concept.*

---

## Core Philosophy (Non-Negotiable)

Every clip must feel like it was made by the same team that ships PxWallet and Hot or Not:
- **Joyful retro-pixel premium** — Not cheap meme, not corporate crypto. Think Press Start 2P meets glassmorphic depth with subtle CRT bloom.
- **Subtly educational** — Viewers absorb *why* self-custody matters, why on-chain entropy is magical, why surviving mint rank flexes, without ever feeling lectured.
- **Community-first & meme-able** — Designed to be screenshotted, remixed, and shared in Discord/Telegram/X.
- **Verifiable & Trustless Hero** — Whenever possible, surface the on-chain truth (TX hash entropy, AtomicAssets data, no hidden backend).

**If a clip doesn't make you smile *and* feel smarter about WAX/Px, revise it.**

---

## Visual Language (Strict Alignment with Design System)

- **Color Palette**: Deep space purples (#1A0F2E), electric cyan (#00F0FF), warm amber (#FFB800), mint accents. High contrast. Subtle neon glows on key elements.
- **Typography**: Primary headlines — Press Start 2P (or approved pixel variant). Body/UI — clean highly legible sans or carefully chosen pixel monospace for terminal vibes. Never mix more than two type families.
- **Motion**: Snappy, pixel-snapped where appropriate. Spring physics or stepped pixel easing. 60fps target. Respect `prefers-reduced-motion`. Subtle haptics-friendly timing.
- **Effects**: Glassmorphic layers with subtle frosted depth + retro CRT scanlines/bloom (used intentionally, not decoratively). Hard pixel edges on sprites/UI elements.
- **Safe Areas**: Text and key action must have generous margins. Pixel fonts need extra breathing room for legibility on mobile.

**Anti-Patterns**:
- Washed-out gradients or generic "Web3 neon"
- Overly saturated meme-coin colors unless intentionally ironic for a specific YEET-style bit
- Generic stock transitions or cheap particle effects
- Text too small or low-contrast on pixel fonts

---

## Narrative & Tone Pillars

1. **Empowerment over FOMO** — "You are in control. Here's the beautiful machine that proves it."
2. **Joyful Discovery** — Retro game energy. "Press Start to verify fairness on-chain."
3. **Community Flex** — Celebrate surviving mint ranks, tiered Pixal ownership (Holder → Kraken), Hot or Not wins.
4. **Transparent Magic** — Show the TX hash or block header derivation when using entropy. Make the verifiable part delightful, not technical.
5. **Short & Punchy** — 15-45s ideal for most formats. Every second earns its place.

**Voiceover / On-Screen Text Tone**: Friendly knowledgeable friend who also plays too much retro games. Witty one-liners welcome. No bro-crypto speak.

---

## Technical Production Standards

### Required Deliverable Formats (per concept)
- **Landscape (YouTube / X longform)**: 1920x1080 or 2560x1440 @ 60fps, H.264 MP4 master + optimized web version
- **Portrait (Reels / Stories / TikTok)**: 1080x1920 @ 60fps
- **Square / Ad Banners**: 1080x1080, 1200x628 (Facebook/IG), 1080x1350 (Stories), with safe text zones
- **Teaser GIF / WebP**: 3-8s looping highlights (under 5MB where possible)

**Naming Convention**:
`{concept-slug}-{format}-{version}.mp4` e.g. `pxwallet-godmode-1080p-landscape-v1.mp4`

**Frame Rate & Performance**: 60fps preferred. Smooth pixel movement. Test on mid-range mobile.

**Accessibility**:
- Burned-in captions (large, high-contrast, pixel-friendly font)
- Audio description or clear visual storytelling for key moments
- High contrast mode variant where feasible

---

## On-Brand Recurring Elements (Consistency Checklist)

Every clip **should** include (unless concept specifically excludes):
- [ ] Subtle Px logo or wordmark in corner or end card (glassmorphic treatment)
- [ ] At least one clear moment highlighting **verifiable / on-chain** aspect (TX hash, AtomicAssets query, entropy derivation)
- [ ] Pixal or Px-themed visual language (even if abstract)
- [ ] Call-to-action that feels native ("Connect with WharfKit", "Join the Hot or Not arena", "Claim your surviving rank flex")
- [ ] End card with repo or link + "Built on WAX — Self-custody is the new high score"

**Moodboard References**: Always pull from `shared/moodboard/` first before creating new assets.

---

## AI Prompt Discipline

All `production-prompt.yaml` files **must** extend `shared/prompts/base-production-prompt.yaml`.

Key rules for prompts:
- Explicitly reference this guide
- Define exact scene timings, camera language, text overlays, voiceover beats
- Specify which shared moodboard assets to feature
- List required output formats + status tracking expectations
- Include "educational delight moment" callout for the verifiable mechanic

---

## Workflow for New Concept

1. Create folder under `concepts/NN-slug-name/`
2. Copy structure from existing scaffold
3. Write rich `README.md` (goals, full script breakdown, target metrics)
4. Write `production-prompt.yaml` extending the base
5. Populate concept moodboard/
6. Generate → update `generated-videos/README.md` status matrix
7. Open PR with checklist from this guide

---

*This guide evolves with real campaign feedback. Propose improvements via standards-proposal style issues or direct PR.*

**Pixel Journey — Making self-custody and verifiable fun look this good.**