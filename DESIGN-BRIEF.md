# Anchovy Labs Premium Redesign — Design Brief

**Date:** 2026-02-12
**Status:** Draft v1 ready for review

---

## Design Philosophy

**"Luxury is quiet."** — Wix Luxury Design Guide

The redesign follows the "Expensive Minimalist" aesthetic established in the Anchovy Press design swarm, specifically drawing from the Digital Exit Strategy visual language: sovereignty, freedom, precision.

---

## Research Sources

1. **Wix Luxury Website Examples** — Best practices for high-end brands
2. **Digital Silk 2026 Minimalist Trends** — Expansive white space, bold typography, light/dark adaptability
3. **99designs Dark Web Design Gallery** — Premium dark theme patterns
4. **ThemeForest Glassmorphism Templates** — Frosted glass UI components

---

## Visual System

### Color Palette
| Role | Hex | Usage |
|------|-----|-------|
| Background Primary | `#0a0a0a` | Main canvas |
| Background Secondary | `#111111` | Section alternation |
| Accent (Gold) | `#c9a962` | CTAs, highlights, logo accent |
| Accent Hover | `#dfc07a` | Interactive states |
| Text Primary | `#ffffff` | Headings, body |
| Text Secondary | `#a0a0a0` | Subheadings, descriptions |
| Text Muted | `#666666` | Captions, footer |
| Glass | `rgba(255,255,255,0.05)` | Card backgrounds |
| Glass Border | `rgba(255,255,255,0.1)` | Card borders |

### Typography
- **Headings:** Playfair Display (serif) — elegance, editorial authority
- **Body:** Inter (sans-serif) — modern clarity, high legibility
- **Hierarchy:** Tight letter-spacing (-0.02em) on headings for sophistication

### Effects
- **Glassmorphism:** `backdrop-filter: blur(20px)` on cards
- **Hover Transforms:** `translateY(-8px)` with cubic-bezier easing
- **Image Zoom:** `transform: scale(1.1)` on gallery hover
- **Gold Accent Line:** Animated top border on card hover

---

## Sections

### 1. Hero
- **Headline:** "Build *Agentic* Intelligence"
- **Background:** `concept_01.png` (shattering iPhone) at 40% opacity
- **CTAs:** "Start a Conversation" (primary) + "View Our Work" (secondary)

### 2. Capabilities
- 4 glassmorphism cards with icon badges
- Services: Agentic Infrastructure, Sovereign AI, Intelligent Automation, Executive Intelligence

### 3. Visual Language Gallery
- CSS Grid with `large` class for featured images (2x2 span)
- 8 images from design swarm selection

### 4. Testimonial
- Ezra quote: "The best agent doesn't ask for permission—it earns trust through competence."

### 5. Footer
- 4-column grid: Brand description + Products + Connect + Company
- Links to UrClaw, SimplifiedClaw, Twitter, GitHub, Email

---

## Selected Images (Top 20)

### Tier 1 — Hero/Feature
1. `digital-exit-strategy/concept_01.png` — Shattering iPhone (hero bg)
2. `cognitive-fortress/001-cognitive-fortress-visual-a-translucent-.png` — Obsidian sphere in dome

### Tier 2 — Gallery
3. `cognitive-fortress/nano_v15.png` — Crystalline neuron
4. `cognitive-fortress/nano_v01.png` — Obsidian core in glass dome
5. `digital-exit-strategy/001-a-matte-black-monolith-casting-a-sharp-g.png` — Monolith
6. `digital-exit-strategy/concept_03.png` — Shattering iPhone variant
7. `the-longevity-protocol/nano_v11.png` — Golden drop
8. `cognitive-fortress/nano_v29.png` — Geometric sculpture

### Tier 3 — Supplementary
9. `digital-exit-strategy/001-a-single-fiber-optic-cable-cleanly-sever.png` — Fiber optic
10. `beyond-stoicism/001-a-single-vibrant-flower-blooming-through.png` — Flower
11. `the-atomic-habits-workbook/001-a-single-water-drop-creating-perfect-geo.png` — Water drop
12. `the-offers-formula-for-creators/001-a-hand-pressing-an-embossing-seal-into-b.png` — Wax seal
13. `cognitive-fortress/nano_v16.png` — Structure
14. `cognitive-fortress/nano_v17.png` — Neural architecture
15. `digital-exit-strategy/nano_v50.png` — Laptop silhouette
16. `beyond-stoicism/concept_01.png` — Marble
17. `digital-exit-strategy/nano_des_05.png` — Minimalist desk
18. `outlive-for-women/001-outlive-for-women-visual-single-luminous.png` — Luminous
19. `cognitive-fortress/batch10/001-cognitive-fortress-visual-zen-garden-wit.png` — Zen
20. `digital-exit-strategy/001-digital-exit-strategy-visual-a-minimalis.png` — Digital void

---

## Files

- `index-premium.html` — New premium design (draft v1)
- `gallery.html` — Image selection gallery for review
- `assets-swarm/` — Symlink to design swarm prototypes

---

## Next Steps

1. [ ] User approval on direction
2. [ ] Finalize image selection
3. [ ] Deploy as production `index.html`
4. [ ] Update GitHub Pages
5. [ ] Optional: Add subtle scroll animations (Intersection Observer)
