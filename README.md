# Anthropic / Claude.ai Frontend Design Skill 🎨

[![License](https://img.shields.io/badge/license-Apache--2.0-blue.svg)](LICENSE)
[![Style](https://img.shields.io/badge/aesthetic-Claude.ai%20%2F%20Anthropic-c96442.svg)](https://claude.ai)
[![Agent Ready](https://img.shields.io/badge/agent-Pi%20%7C%20Claude%20Code%20%7C%20Cursor-3898ec.svg)](#installation--usage)

> *"A literary salon reimagined as a product page — warm, unhurried, and quietly intellectual."*

A publication-grade, agent-executable frontend design system embodying the authentic **Claude.ai / Anthropic** visual identity. 

Designed specifically for AI Coding Agents (**Pi**, **Claude Code**, **Cursor**, **Codex CLI**) and web developers who want to generate, style, or redesign landing pages, dashboards, documentation, and web apps with authentic human warmth, editorial authority, and bookish craftsmanship.

---

## 🌟 Live Demo Preview

A standalone, zero-dependency HTML showcase is included at [`examples/demo.html`](examples/demo.html).

You can open it directly in any browser to inspect the full design palette in action:
- **Parchment canvas** (`#f5f4ed`) & warm near-black (`#141413`)
- **Newsreader Serif 500** headlines with tight literary leading
- **Sticky navigation** with warm backdrop blur & terracotta accent
- **Opus / Sonnet / Haiku** model comparison tiered cards
- **Terminal code blocks** and alternating dark "chapter" transitions

---

## 🚀 Enhancements over Upstream (`open-design`)

This skill originated from the pioneering [nexu-io/open-design](https://github.com/nexu-io/open-design) Claude design specification, but has been **heavily refactored, modernized, and expanded** (from ~320 lines to over 680 lines) into an end-to-end engineering asset:

| Feature | Upstream (`nexu-io/open-design`) | This Enhanced Skill (`anthropic-design`) |
| :--- | :--- | :--- |
| **Tailwind v4 Support** | ❌ (CSS vars only) | ✅ Native `@theme` directive syntax for Tailwind CSS v4 |
| **Tailwind v3 Config** | ❌ None | ✅ Complete `tailwind.config.js` theme extension |
| **Ready-to-Use Components** | ⚠️ Concept snippets only | ✅ **9 Full, copy-pasteable HTML/Tailwind components** |
| **Visual Hierarchy Rules** | ⚠️ Generic advice | ✅ **The 10 Inviolable Do's & Don'ts Table** |
| **Agent Execution Protocol** | ⚠️ Basic prompt hints | ✅ **Step-by-step Pi / Claude Code execution guide** |
| **Accessibility Compliance** | ⚠️ Implicit | ✅ Strict `#3898ec` accessibility focus ring rules |

---

## 🎨 The Six Visual Foundations

1. **Parchment Canvas (`#f5f4ed`)**: Evokes archival acid-free book paper rather than a digital monitor. Pure `#ffffff` is strictly forbidden as a global light background.
2. **Warm Near Black (`#141413`)**: Soft, texturally rich olive-tinted dark base. No harsh `#000000`.
3. **Terracotta Accent (`#c96442`)**: Organic, earthy burnt orange reserved for focal call-to-actions and brand accents.
4. **Exclusively Warm Neutrals**: Every gray carries a yellow-brown/olive undertone (`#5e5d59`, `#87867f`, `#4d4c48`). Cold blue-grays/slate/zinc are banned.
5. **Editorial Serif Headings (Strictly Weight 500)**: Medium-weight serifs (`Newsreader`, `Source Serif 4`, or `Georgia`) with tight line-heights (1.08–1.25).
6. **Whisper Elevations & Ring Shadows**: Depth is communicated via hairline border rings (`0 0 0 1px #d1cfc5`) and diffuse whisper shadows (`rgba(20,20,19,0.05)`).

---

## 📦 What's Inside `SKILL.md`

- **§1 Core Visual DNA & Foundations**: Complete breakdown of the aesthetic philosophy.
- **§2 Complete Color Palette & Token Reference**: Hex, RGB, and semantic roles for 21 core color tokens.
- **§3 Typography & Hierarchy System**: Strict type scales, weight allocations, and font pairings.
- **§4 Shadow, Elevation & Border Radius**: Ring borders, elevation tiers, and pill/container radii.
- **§5 Web Font Imports & CSS Variables**: Ready-to-paste Google Fonts imports and `:root` / `.dark` tokens.
- **§6 Tailwind CSS Configurations**:
  - `6.1` Tailwind v3 configuration snippet (`tailwind.config.js`)
  - `6.2` Tailwind v4 configuration snippet (`@theme`)
- **§7 Ready-to-Use Component Library**:
  - `7.1` Global Page Skeleton (HTML5 + CDN)
  - `7.2` Navigation Bar (Sticky with Warm Backdrop Blur)
  - `7.3` Editorial Hero Section (with Sonnet badge)
  - `7.4` Button Variants Guide (Primary / Secondary / Ghost)
  - `7.5` Content & Feature Cards
  - `7.6` Model Comparison Tier Grid (Opus / Sonnet / Haiku)
  - `7.7` Form Inputs & Focus States
  - `7.8` Editorial Code Block & Terminal Component
  - `7.9` Light-to-Dark Chapter Alternation Section
- **§8 The 10 Inviolable Design Rules**: Tabular Do's and Don'ts check-gate.
- **§9 Agent Execution Instructions for Pi / Claude Code**: Step-by-step instructions for AI coding agents.

---

## 💻 Installation & Usage

### Method 1: Use with Pi Coding Agent (`pi`)

Copy `SKILL.md` directly into your global or project skills directory:

```bash
mkdir -p ~/.pi/agent/skills/anthropic-design
cp SKILL.md ~/.pi/agent/skills/anthropic-design/SKILL.md
```

Then simply instruct `pi`:
> *"Refactor this dashboard using the `anthropic-design` skill."*

---

### Method 2: Use with Claude Code (`claude`)

Include the skill directly in your `.claude/rules` or project prompt:

```bash
mkdir -p .claude
cp SKILL.md .claude/anthropic-design.md
```

Add to `.claude/CLAUDE.md`:
```markdown
When building or styling web pages, follow the guidelines in .claude/anthropic-design.md.
```

---

### Method 3: Use with Cursor / Windsurf / Copilot

Add `SKILL.md` as `.cursorrules` or `.windsurfrules` in your repository root, or paste §6 and §7 into your frontend project.

---

## 📋 Color Token Quick Reference

| Token | Hex | Role |
| :--- | :--- | :--- |
| **Parchment** | `#f5f4ed` | Base canvas background (Light) |
| **Ivory** | `#faf9f5` | Elevated surface / Cards |
| **Near Black** | `#141413` | Primary text & Dark canvas |
| **Terracotta** | `#c96442` | Primary brand CTA |
| **Sand** | `#e8e6dc` | Secondary button & Accent border |
| **Olive** | `#5e5d59` | Secondary body text |
| **Stone** | `#87867f` | Muted metadata & timestamps |
| **Focus Blue** | `#3898ec` | Accessibility focus ring |

---

## 📜 Attribution & Credits

This project builds upon and significantly extends the Claude design tokens originally published in the open-source project **[nexu-io/open-design](https://github.com/nexu-io/open-design)**.

We express our gratitude to the `open-design` contributors for their foundational curation of tech design languages.

- **Upstream Project**: [nexu-io/open-design](https://github.com/nexu-io/open-design)
- **Original License**: Apache License 2.0 (Copyright 2026 Open Design contributors)
- **Modifications & Enhancements**: Tailored for coding agents with Tailwind v3/v4 configurations, full component libraries, strict agent constraints, and standalone HTML showcases by [@hasakiikiiPRO](https://github.com/hasakiikiiPRO).

---

## 📄 License

This repository is licensed under the [Apache License 2.0](LICENSE). See [NOTICE](NOTICE) for original attribution details.
