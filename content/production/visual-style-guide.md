---
type: style-guide
title: Visual Style Guide
source: Discord channel 1004497855651790930 (art-prompts)
scraped: 2026-03-17
tags:
  - art-direction
  - midjourney
  - style-guide
  - production
---

# Visual Style Guide

Extracted visual style rules from 549 Midjourney prompts spanning 2022-2026. This documents the DM's art direction language and how it evolved across the campaign.

## Midjourney Version Evolution

| Era | Engine | Syntax | Visual Character |
|-----|--------|--------|-----------------|
| **Phase 1** (Aug-Nov 2022) | MJ v3, `--test --creative` | Freeform + tags | Painterly, dreamlike, sometimes abstract |
| **Phase 2** (2023) | MJ v4-v5 | `+ tag` chains | Sharper detail, more literal interpretation |
| **Phase 3** (2024-2025) | MJ v6.0 | `+ tag + --v 6.0` | Photorealistic tendency, character consistency |
| **Phase 4** (Mar 2026) | **niji 7** + `--style raw` | Long-form cinematic descriptions | Anime-influenced, panel-ready, animation-grade |

### Version Usage (from scraped data)

- `niji 7`: 475 prompts
- `v 6.0`: 62 prompts
- `v 7.0`: 10 prompts

> **Key shift**: Phase 4 moved entirely to `niji 7` for anime-style output suitable for the webcomic/animation pipeline. The `--style raw` flag (0 prompts) is used for more literal, less stylized interpretations.

## Aspect Ratios

| Ratio | Count | Usage |
|-------|-------|-------|
| `16:9` | 252 | Cinematic panels, establishing shots, landscapes |
| `9:16` | 149 | Vertical character portraits, full-body shots |
| `2:3` | 53 | Portrait compositions, character close-ups |
| `1:1` | 18 | Item spotlights, emblems, mood boards |
| `3:1` | 16 | Ultra-wide panoramic panels, scene transitions |
| `3:4` | 12 | Medium portraits, environmental portraits |

## Color Palette System (Phase 4)

The 2026 production sprint introduced explicit hex color codes into prompts -- a major evolution toward production-ready art direction.

### Extracted Color Codes

| Code | Family | Context |
|------|--------|--------|
| `#001F54` | Cool blue/mystic | Extracted from mood boards |
| `#003366` | Cool blue/mystic | Extracted from mood boards |
| `#0047AB` | Cool blue/mystic | Extracted from mood boards |
| `#008080` | Neutral/mixed | Extracted from mood boards |
| `#00A86B` | Verdant/nature | Extracted from mood boards |
| `#00CED1` | Cool blue/mystic | Extracted from mood boards |
| `#00aa88` | Verdant/nature | Extracted from mood boards |
| `#0A0A0A` | Deep black/shadow | Extracted from mood boards |
| `#0a0015` | Deep black/shadow | Extracted from mood boards |
| `#0a0a0a` | Deep black/shadow | Extracted from mood boards |
| `#1A0A2E` | Deep black/shadow | Extracted from mood boards |
| `#1A1A1A` | Deep black/shadow | Extracted from mood boards |
| `#1A1A2E` | Deep black/shadow | Extracted from mood boards |
| `#1A1A3E` | Cool blue/mystic | Extracted from mood boards |
| `#1a0a2a` | Deep black/shadow | Extracted from mood boards |
| `#1a1a2e` | Deep black/shadow | Extracted from mood boards |
| `#1a1a3e` | Cool blue/mystic | Extracted from mood boards |
| `#2244CC` | Cool blue/mystic | Extracted from mood boards |
| `#2244cc` | Cool blue/mystic | Extracted from mood boards |
| `#2C1810` | Deep black/shadow | Extracted from mood boards |
| `#2D0A4E` | Cool blue/mystic | Extracted from mood boards |
| `#2D4A22` | Verdant/nature | Extracted from mood boards |
| `#2D5A27` | Verdant/nature | Extracted from mood boards |
| `#2E0854` | Cool blue/mystic | Extracted from mood boards |
| `#2E5E3F` | Verdant/nature | Extracted from mood boards |
| `#2d0a4e` | Cool blue/mystic | Extracted from mood boards |
| `#2d2d6b` | Cool blue/mystic | Extracted from mood boards |
| `#2d4a22` | Verdant/nature | Extracted from mood boards |
| `#3B0F70` | Cool blue/mystic | Extracted from mood boards |
| `#3a2040` | Cool blue/mystic | Extracted from mood boards |
| `#3d5c3a` | Verdant/nature | Extracted from mood boards |
| `#4682B4` | Cool blue/mystic | Extracted from mood boards |
| `#4A0078` | Cool blue/mystic | Extracted from mood boards |
| `#4A4A4A` | Neutral/mixed | Extracted from mood boards |
| `#4A7C3F` | Verdant/nature | Extracted from mood boards |
| `#4A8B3F` | Verdant/nature | Extracted from mood boards |
| `#4A9EFF` | Cool blue/mystic | Extracted from mood boards |
| `#4B0082` | Cool blue/mystic | Extracted from mood boards |
| `#4a4a4a` | Neutral/mixed | Extracted from mood boards |
| `#4a7c3f` | Verdant/nature | Extracted from mood boards |
| `#4a9eff` | Cool blue/mystic | Extracted from mood boards |
| `#4aff4a` | Verdant/nature | Extracted from mood boards |
| `#5A5A5A` | Neutral/mixed | Extracted from mood boards |
| `#5A7A52` | Verdant/nature | Extracted from mood boards |
| `#5a6a7a` | Cool blue/mystic | Extracted from mood boards |
| `#5a7a52` | Verdant/nature | Extracted from mood boards |
| `#6A0DAD` | Cool blue/mystic | Extracted from mood boards |
| `#6A7A8A` | Cool blue/mystic | Extracted from mood boards |
| `#6B3A2A` | Crimson/fire | Extracted from mood boards |
| `#6B6B6B` | Neutral/mixed | Extracted from mood boards |
| `#6a7a8a` | Cool blue/mystic | Extracted from mood boards |
| `#708090` | Cool blue/mystic | Extracted from mood boards |
| `#722F37` | Crimson/fire | Extracted from mood boards |
| `#7B2FBE` | Cool blue/mystic | Extracted from mood boards |
| `#7b2fbe` | Cool blue/mystic | Extracted from mood boards |
| `#87CEEB` | Cool blue/mystic | Extracted from mood boards |
| `#8B0000` | Crimson/fire | Extracted from mood boards |
| `#8B7355` | Warm amber/gold | Extracted from mood boards |
| `#8F9779` | Verdant/nature | Extracted from mood boards |
| `#8a8a40` | Neutral/mixed | Extracted from mood boards |
| `#8b0000` | Crimson/fire | Extracted from mood boards |
| `#9A9A8A` | Neutral/mixed | Extracted from mood boards |
| `#9b59b6` | Cool blue/mystic | Extracted from mood boards |
| `#A0522D` | Warm amber/gold | Extracted from mood boards |
| `#B22222` | Crimson/fire | Extracted from mood boards |
| `#B57EDC` | Cool blue/mystic | Extracted from mood boards |
| `#B8860B` | Warm amber/gold | Extracted from mood boards |
| `#C41E3A` | Crimson/fire | Extracted from mood boards |
| `#C44000` | Crimson/fire | Extracted from mood boards |
| `#C8A040` | Warm amber/gold | Extracted from mood boards |
| `#C8DBE6` | Cool blue/mystic | Extracted from mood boards |
| `#CC0000` | Crimson/fire | Extracted from mood boards |
| `#CC4411` | Crimson/fire | Extracted from mood boards |
| `#D4A017` | Warm amber/gold | Extracted from mood boards |
| `#D4A040` | Warm amber/gold | Extracted from mood boards |
| `#D4CCB8` | Warm amber/gold | Extracted from mood boards |
| `#D4D4D4` | Neutral/mixed | Extracted from mood boards |
| `#DAA520` | Warm amber/gold | Extracted from mood boards |
| `#E0F0FF` | Cool blue/mystic | Extracted from mood boards |
| `#E8E0D0` | Warm amber/gold | Extracted from mood boards |
| `#E8E0D8` | Warm amber/gold | Extracted from mood boards |
| `#E8E8F0` | Cool blue/mystic | Extracted from mood boards |
| `#E8F0F5` | Cool blue/mystic | Extracted from mood boards |
| `#F5E6D3` | Warm amber/gold | Extracted from mood boards |
| `#F5F5F5` | Neutral/mixed | Extracted from mood boards |
| `#FF6600` | Warm amber/gold | Extracted from mood boards |
| `#FF8C00` | Warm amber/gold | Extracted from mood boards |
| `#FFBF00` | Warm amber/gold | Extracted from mood boards |
| `#FFD700` | Warm amber/gold | Extracted from mood boards |
| `#FFF5D0` | Warm amber/gold | Extracted from mood boards |
| `#FFFFF0` | Neutral/mixed | Extracted from mood boards |
| `#FFFFFF` | Neutral/mixed | Extracted from mood boards |
| `#a0522d` | Warm amber/gold | Extracted from mood boards |
| `#b8860b` | Warm amber/gold | Extracted from mood boards |
| `#c44000` | Crimson/fire | Extracted from mood boards |
| `#c8dbe6` | Cool blue/mystic | Extracted from mood boards |
| `#cc2200` | Crimson/fire | Extracted from mood boards |
| `#d4760a` | Warm amber/gold | Extracted from mood boards |
| `#d4a017` | Warm amber/gold | Extracted from mood boards |
| `#d4a040` | Warm amber/gold | Extracted from mood boards |
| `#d4a868` | Warm amber/gold | Extracted from mood boards |
| `#d4d8a0` | Verdant/nature | Extracted from mood boards |
| `#e8a0a0` | Warm amber/gold | Extracted from mood boards |
| `#e8e0d0` | Warm amber/gold | Extracted from mood boards |
| `#e8f0f5` | Cool blue/mystic | Extracted from mood boards |
| `#ffd700` | Warm amber/gold | Extracted from mood boards |
| `#fff5d0` | Warm amber/gold | Extracted from mood boards |
| `#ffffff` | Neutral/mixed | Extracted from mood boards |

### Emotional Color Mapping

From the mood board prompts, the following color-emotion system emerges:

| Emotion | Primary Colors | Lighting | Dominant Element |
|---------|---------------|----------|-----------------|
| **Fear** | Deep cool blue-black, desaturated purple | Single failing light source, unnatural angles | Vast pressing darkness |
| **Rage** | Hot crimson, burning orange vs absolute black | Harsh firelight from below | Elemental fire, hungry and consuming |
| **Wonder** | Not yet generated | -- | -- |
| **Grief** | Not yet generated | -- | -- |

## Camera Language (Phase 4)

The 2026 prompts use explicit cinematographic language:

### Shot Types
- **Extreme close-up**: Face details, emotional beats ("two faces pressed together")
- **Portrait/Medium**: Character interactions, dialogue scenes
- **Wide shot/Establishing**: Environments, group compositions
- **Vertical composition**: Nature magic, ship masts, tall structures
- **Split screen**: Before/after, contrast between groups
- **Three-way split**: Parallel actions, simultaneous divinations

### Camera Direction
- "Camera holds on..." -- static emotional beat
- "Phase 1/2/3" -- timed animation sequence with transitions
- "LEFT HALF / RIGHT HALF" -- split composition
- "foreground/background" -- depth staging
- "lit from below" -- threat/horror lighting
- "single failing light source" -- isolation/vulnerability

## Tag Vocabulary (Phase 4 -- Top 30)

The most frequently used descriptive tags in 2026 production prompts:


## Prompt Architecture

### Phase 1-3 Pattern (2022-2025)
```
[subject description] + [genre tag] + [lighting tag] + [mood tag] + --v X.X
```
Example: `a gnomish wizard who is able to see the future + character portrait + dungeons and dragons + magic + medieval fantasy + diviner`

### Phase 4 Pattern (2026 Production)
```
[Shot type]. [Detailed scene description with specific visual details,
color codes, character positions, emotional state]. [Camera/composition
notes]. [Lighting description] --niji 7 --ar [ratio] --style raw
```
Example: `Portrait of Nyx sitting on the ship's deck, cobalt blue cloak pulled around her, barn owl dozing beside her. She is small on the large deck the Thornberry Shade dwarfs her. Warm amber twilight (#d4a040) catches the owl's feathers. --niji 7 --ar 2:3 --style raw`

### Key Style Tags by Era

| Tag | Era | Purpose |
|-----|-----|---------|
| `+ dynamic lighting` | All eras | Consistent across entire history |
| `+ medieval fantasy` | Phase 1-3 | Genre anchoring |
| `+ dungeons and dragons` | Phase 1-3 | Genre anchoring |
| `+ character portrait` | Phase 2-3 | Framing directive |
| `+ cinematic staging` | Phase 3+ | Camera-aware composition |
| `+ cinematic pose` | Phase 3 | Action/pose direction |
| `--niji 7 --style raw` | Phase 4 | Anime pipeline, literal interpretation |
| Hex color codes | Phase 4 | Production-grade color control |

## Style References (--sref)

- `--sref <https://s.mj.run/eDUvgrVWXrY>`

## Production Notes

### What Works
- Long-form descriptive prompts (200+ words) with niji 7 produce animation-ready frames
- Explicit hex color codes give consistent palette control
- Split-screen and multi-phase descriptions create storyboard-quality compositions
- The `+ dynamic lighting` tag has been used since Day 1 and remains the most consistent quality enhancer

### What to Carry Forward
- The color-emotion mapping system (fear=blue-black, rage=crimson-orange) should be codified in the animation color script
- Phase 4's camera language (shot types, phase timing) translates directly to animatic timing
- Character descriptions have accumulated enough detail across 4 years to build definitive model sheets

---

## Related Files

- [[art-direction-index]] -- Master index of all prompts by character and location
- [[character-visual-specs]] -- Per-character appearance compilation
- [[production-sequence]] -- Overall Mardov production pipeline
