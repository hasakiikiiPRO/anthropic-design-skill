---
name: anthropic-design
description: "Apply the official Anthropic and Claude.ai frontend design system and aesthetic. Use when designing, building, or styling web pages, landing pages, UI components, HTML/CSS layouts, or Tailwind templates with the authentic Claude look: warm parchment (#f5f4ed), terracotta accents (#c96442), warm near-black (#141413), editorial serif typography, warm neutrals, and ring-based shadows."
---

# Anthropic / Claude.ai Frontend Design System

> **Design Philosophy**: *"A literary salon reimagined as a product page — warm, unhurried, and quietly intellectual."*  
> Unlike conventional tech interfaces that lean into cold neon glows, deep blues, or sterile grays, Anthropic's visual identity radiates human warmth, editorial authority, and bookish craftsmanship. It feels like reading a beautifully set essay or exploring a premium print publication on fine cream paper.

---

## 1. Core Visual DNA & Foundations

### 1.1 The Six Cornerstones
1. **Parchment Canvas (`#f5f4ed`)**: The default page background is warm cream with a faint yellow-green undertone, evoking high-grade archival paper rather than a digital monitor.
2. **Warm Near Black (`#141413`)**: Primary text and dark surfaces avoid pure `#000000`. They carry an ultra-subtle warm/olive tint that is soft on the eyes and texturally rich.
3. **Terracotta Brand Accent (`#c96442`)**: A warm, burnt orange-brown reserved for primary call-to-actions, badges, and focal brand moments. Deliberately organic and un-tech.
4. **Exclusively Warm Neutrals**: Every gray in the palette carries a yellow-brown undertone (`#5e5d59`, `#87867f`, `#4d4c48`, `#e8e6dc`, `#f0eee6`). **Zero cool blue-grays** exist anywhere in the core design.
5. **Editorial Serif Headings (Strictly Weight 500)**: All headline hierarchy relies on a medium-weight serif (`Newsreader`, `Source Serif 4`, or `Georgia`) with tight line-heights (1.10–1.25), while functional UI and body text use a clean, friendly sans-serif.
6. **Ring Shadows & Whisper Elevations**: Depth is communicated through warm border rings (`0px 0px 0px 1px`) and diffuse whisper shadows (`rgba(20,20,19,0.05) 0px 4px 24px`), never heavy, muddy drop shadows.

---

## 2. Complete Color Palette & Token Reference

| Token Name | Hex Code | RGB | Semantic Role |
|:---|:---|:---|:---|
| **Parchment** | `#f5f4ed` | `245, 244, 237` | Light-mode base canvas / page background |
| **Ivory** | `#faf9f5` | `250, 249, 245` | Elevated surface (cards, dialogs, containers on parchment) |
| **Pure White** | `#ffffff` | `255, 255, 255` | Maximum contrast light surfaces, pill badges |
| **Warm Sand** | `#e8e6dc` | `232, 230, 220` | Secondary buttons, subtle dividers, active tabs |
| **Terracotta Brand** | `#c96442` | `201, 100, 66` | Primary action buttons, brand focus, key highlights |
| **Terracotta Hover** | `#b85736` | `184, 87, 54` | Hover state for primary buttons |
| **Coral Accent** | `#d97757` | `217, 119, 87` | Text accents, link highlights on dark surfaces |
| **Near Black** | `#141413` | `20, 20, 19` | Primary text in light mode, canvas background in dark mode |
| **Dark Surface** | `#30302e` | `48, 48, 46` | Dark mode card containers, navigation bars, dark dividers |
| **Charcoal Warm** | `#4d4c48` | `77, 76, 72` | Secondary dark text, button text on warm sand |
| **Olive Gray** | `#5e5d59` | `94, 93, 89` | Standard secondary body text, captions, subtitles |
| **Stone Gray** | `#87867f` | `135, 134, 127` | Tertiary metadata, footnotes, inactive icons |
| **Warm Silver** | `#b0aea5` | `176, 174, 165` | Light body text on dark mode backgrounds |
| **Border Cream** | `#f0eee6` | `240, 238, 230` | Subtle hairline borders on light surfaces |
| **Border Warm** | `#e8e6dc` | `232, 230, 220` | Section dividers, emphasized light borders |
| **Border Dark** | `#30302e` | `48, 48, 46` | Structural borders on dark surfaces |
| **Ring Warm** | `#d1cfc5` | `209, 207, 197` | Outline ring on interactive hover/focus states |
| **Ring Deep** | `#c2c0b6` | `194, 192, 182` | Active/pressed ring outline |
| **Focus Blue** | `#3898ec` | `56, 152, 236` | Accessibility focus rings on form inputs (the only cool tone) |
| **Error Crimson** | `#b53333` | `181, 51, 51` | Warm red for alerts and validation errors |
| **Success Olive** | `#3d7a40` | `61, 122, 64` | Earthy green for status badges and success moments |

---

## 3. Typography & Hierarchy System

Anthropic uses a disciplined dual-typeface structure:
- **Headlines / Titles**: Editorial Serif (`Anthropic Serif` → Google Fonts fallback: `Newsreader` / `Source Serif 4` / `Georgia`).
  - **Rule**: Weight is always **Medium (500)**. Never use bold (`700`) or light (`300`).
  - **Leading**: Tight (1.10–1.25), creating the gravitas of a printed volume.
- **Body / Interface**: Warm Modern Sans (`Anthropic Sans` → Google Fonts fallback: `Plus Jakarta Sans` / `Inter` / system-ui).
  - **Rule**: Weights are 400 (regular) and 500 (medium for labels/emphasis).
  - **Leading**: Generous (1.55–1.65), providing effortless readability like long-form essays.
- **Code & Terminals**: Warm Monospace (`Anthropic Mono` → Google Fonts fallback: `JetBrains Mono` / `Geist Mono` / `Fira Code`).

### Typographic Scale

| Role | Font Family | Size | Weight | Line Height | Tracking |
|:---|:---|:---|:---|:---|:---|
| **Display / Hero** | Serif | 4rem (64px) | 500 | 1.10 | `-0.02em` |
| **H1 / Section Header** | Serif | 3rem (48px) | 500 | 1.15 | `-0.015em` |
| **H2 / Sub-Section** | Serif | 2.25rem (36px) | 500 | 1.20 | `-0.01em` |
| **H3 / Card Header** | Serif | 1.5rem (24px) | 500 | 1.25 | `normal` |
| **Feature Title** | Serif | 1.25rem (20px) | 500 | 1.30 | `normal` |
| **Body Large / Lead** | Sans | 1.125rem (18px) | 400 | 1.60 | `normal` |
| **Body Standard** | Sans | 1rem (16px) | 400 | 1.60 | `normal` |
| **Body Small** | Sans | 0.875rem (14px) | 400 | 1.50 | `normal` |
| **UI Label / Meta** | Sans | 0.75rem (12px) | 500 | 1.40 | `0.04em` |
| **Code Block** | Mono | 0.875rem (14px) | 400 | 1.60 | `-0.01em` |

---

## 4. Shadow, Elevation & Border Radius

### 4.1 Elevation System
Anthropic avoids generic Gaussian drop shadows. Elevation is rendered with warm rings and ultra-low-opacity whisper spreads:
- **Level 0 (Base)**: `box-shadow: none;`
- **Level 1 (Subtle Outline)**: `box-shadow: 0 0 0 1px #f0eee6;` (or `border: 1px solid #f0eee6;`)
- **Level 2 (Ring Halo / Button Hover)**: `box-shadow: 0 0 0 1px #d1cfc5;`
- **Level 3 (Whisper Lift - Cards)**: `box-shadow: 0 4px 24px rgba(20, 20, 19, 0.05);`
- **Level 4 (Elevated Feature Card)**: `box-shadow: 0 0 0 1px #e8e6dc, 0 8px 32px rgba(20, 20, 19, 0.06);`
- **Level 5 (Inset Pressed State)**: `box-shadow: inset 0 0 0 1px rgba(20, 20, 19, 0.12);`

### 4.2 Radii System
- `rounded-md` (`6px`–`8px`): Small badges, compact tooltips, code snippets.
- `rounded-lg` (`8px`): Default cards, standard buttons, tabs.
- `rounded-xl` (`12px`): Primary CTA buttons, form input fields, floating cards.
- `rounded-2xl` (`16px`): Featured containers, modal dialogs, media embeds.
- `rounded-3xl` (`24px`–`32px`): Hero section wrapper cards, preview windows.
- `rounded-full` (`9999px`): Status pills, avatar frames, filter tags.

---

## 5. Web Font Imports & CSS Variables

### 5.1 Web Fonts Setup (HTML `<head>` or CSS `@import`)
```html
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=JetBrains+Mono:wght@400;500&family=Newsreader:ital,opsz,wght@0,6..72,400;0,6..72,500;1,6..72,400&family=Plus+Jakarta+Sans:wght@400;500;600&display=swap" rel="stylesheet">
```

### 5.2 Pure CSS Tokens (`:root` & `.dark`)
```css
:root {
  /* Surfaces */
  --claude-parchment: #f5f4ed;
  --claude-ivory: #faf9f5;
  --claude-white: #ffffff;
  --claude-sand: #e8e6dc;
  --claude-dark-surface: #30302e;
  --claude-near-black: #141413;

  /* Brand Accents */
  --claude-terracotta: #c96442;
  --claude-terracotta-hover: #b85736;
  --claude-coral: #d97757;

  /* Warm Neutrals */
  --claude-charcoal: #4d4c48;
  --claude-olive: #5e5d59;
  --claude-stone: #87867f;
  --claude-silver: #b0aea5;

  /* Borders & Rings */
  --claude-border-cream: #f0eee6;
  --claude-border-warm: #e8e6dc;
  --claude-border-dark: #30302e;
  --claude-ring-warm: #d1cfc5;
  --claude-ring-deep: #c2c0b6;

  /* System States */
  --claude-focus-blue: #3898ec;
  --claude-crimson: #b53333;
  --claude-success-olive: #3d7a40;

  /* Shadows */
  --claude-shadow-whisper: 0 4px 24px rgba(20, 20, 19, 0.05);
  --claude-shadow-elevated: 0 0 0 1px #e8e6dc, 0 8px 32px rgba(20, 20, 19, 0.06);

  /* Font Families */
  --font-claude-serif: 'Newsreader', 'Source Serif 4', Georgia, serif;
  --font-claude-sans: 'Plus Jakarta Sans', Inter, -apple-system, BlinkMacSystemFont, sans-serif;
  --font-claude-mono: 'JetBrains Mono', 'Geist Mono', monospace;
}

.dark {
  --claude-parchment: #141413;
  --claude-ivory: #1c1b1a;
  --claude-near-black: #faf9f5;
  --claude-olive: #b0aea5;
  --claude-stone: #87867f;
  --claude-border-cream: #262523;
  --claude-border-warm: #30302e;
  --claude-shadow-whisper: 0 4px 24px rgba(0, 0, 0, 0.35);
}
```

---

## 6. Tailwind CSS Configurations

### 6.1 Tailwind CSS v3 (`tailwind.config.js`)
```javascript
/** @type {import('tailwindcss').Config} */
module.exports = {
  darkMode: 'class',
  theme: {
    extend: {
      colors: {
        claude: {
          parchment: '#f5f4ed',
          ivory: '#faf9f5',
          sand: '#e8e6dc',
          terracotta: {
            DEFAULT: '#c96442',
            hover: '#b85736',
          },
          coral: '#d97757',
          black: '#141413',
          surface: '#30302e',
          charcoal: '#4d4c48',
          olive: '#5e5d59',
          stone: '#87867f',
          silver: '#b0aea5',
          border: {
            cream: '#f0eee6',
            warm: '#e8e6dc',
            dark: '#30302e',
          },
          ring: {
            warm: '#d1cfc5',
            deep: '#c2c0b6',
          },
          focus: '#3898ec',
          crimson: '#b53333',
        },
      },
      fontFamily: {
        serif: ['Newsreader', 'Source Serif 4', 'Georgia', 'serif'],
        sans: ['"Plus Jakarta Sans"', 'Inter', 'system-ui', '-apple-system', 'sans-serif'],
        mono: ['"JetBrains Mono"', '"Geist Mono"', 'monospace'],
      },
      boxShadow: {
        whisper: '0 4px 24px rgba(20, 20, 19, 0.05)',
        elevated: '0 0 0 1px #e8e6dc, 0 8px 32px rgba(20, 20, 19, 0.06)',
        'ring-warm': '0 0 0 1px #d1cfc5',
        'ring-terracotta': '0 0 0 1px #c96442',
      },
      borderRadius: {
        '2xl': '16px',
        '3xl': '24px',
        '4xl': '32px',
      },
    },
  },
  plugins: [],
};
```

### 6.2 Tailwind CSS v4 (`@theme` syntax)
```css
@import "tailwindcss";

@theme {
  --color-claude-parchment: #f5f4ed;
  --color-claude-ivory: #faf9f5;
  --color-claude-sand: #e8e6dc;
  --color-claude-terracotta: #c96442;
  --color-claude-terracotta-hover: #b85736;
  --color-claude-coral: #d97757;
  --color-claude-black: #141413;
  --color-claude-surface: #30302e;
  --color-claude-charcoal: #4d4c48;
  --color-claude-olive: #5e5d59;
  --color-claude-stone: #87867f;
  --color-claude-silver: #b0aea5;
  --color-claude-border-cream: #f0eee6;
  --color-claude-border-warm: #e8e6dc;
  --color-claude-border-dark: #30302e;
  --color-claude-ring-warm: #d1cfc5;
  --color-claude-ring-deep: #c2c0b6;
  --color-claude-focus: #3898ec;
  --color-claude-crimson: #b53333;

  --font-serif: "Newsreader", "Source Serif 4", Georgia, serif;
  --font-sans: "Plus Jakarta Sans", Inter, system-ui, sans-serif;
  --font-mono: "JetBrains Mono", "Geist Mono", monospace;

  --shadow-whisper: 0 4px 24px rgba(20, 20, 19, 0.05);
  --shadow-elevated: 0 0 0 1px #e8e6dc, 0 8px 32px rgba(20, 20, 19, 0.06);
  --shadow-ring-warm: 0 0 0 1px #d1cfc5;
}
```

---

## 7. Ready-to-Use Component Library

### 7.1 Global Page Skeleton
```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Anthropic Design Experience</title>
  <!-- Google Fonts: Newsreader (Serif 500), Plus Jakarta Sans, JetBrains Mono -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=JetBrains+Mono:wght@400;500&family=Newsreader:ital,opsz,wght@0,6..72,400;0,6..72,500;1,6..72,400&family=Plus+Jakarta+Sans:wght@400;500;600&display=swap" rel="stylesheet">
  <script src="https://cdn.tailwindcss.com"></script>
  <script>
    tailwind.config = {
      theme: {
        extend: {
          colors: {
            parchment: '#f5f4ed',
            ivory: '#faf9f5',
            sand: '#e8e6dc',
            terracotta: { DEFAULT: '#c96442', hover: '#b85736' },
            coral: '#d97757',
            nearblack: '#141413',
            surface: '#30302e',
            charcoal: '#4d4c48',
            olive: '#5e5d59',
            stone: '#87867f',
            silver: '#b0aea5',
            cream: '#f0eee6',
            warmborder: '#e8e6dc',
            ringwarm: '#d1cfc5',
            focusblue: '#3898ec'
          },
          fontFamily: {
            serif: ['Newsreader', 'Georgia', 'serif'],
            sans: ['"Plus Jakarta Sans"', 'Inter', 'sans-serif'],
            mono: ['"JetBrains Mono"', 'monospace'],
          },
          boxShadow: {
            whisper: '0 4px 24px rgba(20, 20, 19, 0.05)',
            ring: '0 0 0 1px #d1cfc5',
          }
        }
      }
    }
  </script>
</head>
<body class="bg-parchment text-nearblack font-sans antialiased selection:bg-terracotta/20 selection:text-nearblack">
  <!-- Content renders here -->
</body>
</html>
```

---

### 7.2 Navigation Bar (Sticky with Warm Backdrop Blur)
```html
<header class="sticky top-0 z-50 w-full bg-parchment/85 backdrop-blur-md border-b border-cream">
  <div class="max-w-6xl mx-auto px-6 h-16 flex items-center justify-between">
    <!-- Brand Wordmark -->
    <a href="#" class="flex items-center gap-2 group">
      <span class="font-serif font-medium text-2xl tracking-tight text-nearblack">Claude</span>
      <span class="inline-block w-1.5 h-1.5 rounded-full bg-terracotta"></span>
    </a>

    <!-- Navigation Links -->
    <nav class="hidden md:flex items-center gap-8 text-sm font-medium text-olive">
      <a href="#models" class="hover:text-nearblack transition-colors">Models</a>
      <a href="#research" class="hover:text-nearblack transition-colors">Research</a>
      <a href="#pricing" class="hover:text-nearblack transition-colors">Pricing</a>
      <a href="#docs" class="hover:text-nearblack transition-colors">Documentation</a>
    </nav>

    <!-- Nav Action Buttons -->
    <div class="flex items-center gap-3">
      <button class="px-3.5 py-1.5 text-sm font-medium text-charcoal bg-sand hover:bg-[#dedcd0] border border-transparent rounded-lg shadow-[0_0_0_1px_#d1cfc5] transition-all">
        Sign in
      </button>
      <button class="px-4 py-1.5 text-sm font-medium text-ivory bg-terracotta hover:bg-terracotta-hover rounded-xl shadow-[0_0_0_1px_#c96442] transition-colors">
        Try Claude
      </button>
    </div>
  </div>
</header>
```

---

### 7.3 Editorial Hero Section
```html
<section class="relative pt-24 pb-20 px-6 max-w-5xl mx-auto text-center">
  <!-- Overline Badge -->
  <div class="inline-flex items-center gap-2 px-3 py-1 rounded-full bg-sand/80 border border-warmborder text-xs font-medium text-charcoal mb-8 tracking-wide">
    <span class="w-1.5 h-1.5 rounded-full bg-terracotta"></span>
    <span>Introducing Claude 3.7 Sonnet</span>
  </div>

  <!-- Editorial Headline (Strictly Serif 500, tight line-height) -->
  <h1 class="font-serif font-medium text-5xl md:text-6xl lg:text-7xl leading-[1.08] text-nearblack tracking-tight mb-8 max-w-4xl mx-auto">
    Intelligence that feels <br class="hidden sm:inline" />
    natural, thoughtful, and human.
  </h1>

  <!-- Subtitle (Sans, relaxed 1.6 leading, olive gray) -->
  <p class="font-sans text-lg md:text-xl text-olive leading-relaxed max-w-2xl mx-auto mb-10">
    Claude is Anthropic's next-generation AI assistant, engineered for thoughtful analysis, deep reasoning, and fluid creative collaboration.
  </p>

  <!-- CTA Button Pair -->
  <div class="flex flex-wrap items-center justify-center gap-4">
    <button class="px-6 py-3 text-base font-medium text-ivory bg-terracotta hover:bg-terracotta-hover rounded-xl shadow-[0_0_0_1px_#c96442] transition-all flex items-center gap-2">
      <span>Start with Claude</span>
      <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24">
        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M14 5l7 7m0 0l-7 7m7-7H3"/>
      </svg>
    </button>
    <button class="px-6 py-3 text-base font-medium text-charcoal bg-sand hover:bg-[#dfddd2] rounded-xl shadow-[0_0_0_1px_#d1cfc5] transition-all">
      Read the research
    </button>
  </div>
</section>
```

---

### 7.4 Button Variants Guide
```html
<div class="flex flex-wrap items-center gap-4 p-6 bg-parchment rounded-2xl border border-cream">
  <!-- 1. Primary CTA: Brand Terracotta -->
  <button class="px-4 py-2 text-sm font-medium text-ivory bg-terracotta hover:bg-terracotta-hover rounded-xl shadow-[0_0_0_1px_#c96442] transition-colors">
    Primary Terracotta
  </button>

  <!-- 2. Secondary: Warm Sand (Asymmetric or Standard) -->
  <button class="px-4 py-2 text-sm font-medium text-charcoal bg-sand hover:bg-[#dedcd0] rounded-lg shadow-[0_0_0_1px_#d1cfc5] transition-colors">
    Secondary Warm Sand
  </button>

  <!-- 3. White Surface (Elevated Pill) -->
  <button class="px-4 py-2 text-sm font-medium text-nearblack bg-white hover:bg-ivory rounded-xl border border-cream shadow-[0_1px_3px_rgba(20,20,19,0.06)] transition-all">
    White Elevated
  </button>

  <!-- 4. Dark Charcoal Inverted -->
  <button class="px-4 py-2 text-sm font-medium text-ivory bg-surface hover:bg-nearblack rounded-lg shadow-[0_0_0_1px_#30302e] transition-colors">
    Dark Surface
  </button>

  <!-- 5. Ghost / Subtle Link -->
  <button class="px-3 py-2 text-sm font-medium text-olive hover:text-nearblack rounded-lg transition-colors">
    Ghost Action
  </button>
</div>
```

---

### 7.5 Content & Feature Cards (Ivory on Parchment + Whisper Shadow)
```html
<div class="grid grid-cols-1 md:grid-cols-3 gap-6 max-w-6xl mx-auto px-6">
  <!-- Feature Card 1 -->
  <div class="bg-ivory border border-cream rounded-2xl p-7 shadow-whisper hover:shadow-[0_0_0_1px_#e8e6dc,0_8px_30px_rgba(20,20,19,0.06)] transition-all">
    <div class="w-10 h-10 rounded-xl bg-sand flex items-center justify-center text-terracotta mb-5">
      <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24">
        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 6.253v13m0-13C10.832 5.477 9.246 5 7.5 5S4.168 5.477 3 6.253v13C4.168 18.477 5.754 18 7.5 18s3.332.477 4.5 1.253m0-13C13.168 5.477 14.754 5 16.5 5c1.747 0 3.332.477 4.5 1.253v13C19.832 18.477 18.247 18 16.5 18c-1.746 0-3.332.477-4.5 1.253"/>
      </svg>
    </div>
    <h3 class="font-serif font-medium text-xl text-nearblack mb-2">Deep Comprehension</h3>
    <p class="font-sans text-sm text-olive leading-relaxed">
      Analyze long documents, synthesize multifaceted research papers, and surface nuanced insights with calibrated accuracy.
    </p>
  </div>

  <!-- Feature Card 2 -->
  <div class="bg-ivory border border-cream rounded-2xl p-7 shadow-whisper hover:shadow-[0_0_0_1px_#e8e6dc,0_8px_30px_rgba(20,20,19,0.06)] transition-all">
    <div class="w-10 h-10 rounded-xl bg-sand flex items-center justify-center text-terracotta mb-5">
      <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24">
        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M10 20l4-16m4 4l4 4-4 4M6 16l-4-4 4-4"/>
      </svg>
    </div>
    <h3 class="font-serif font-medium text-xl text-nearblack mb-2">Code & Systems</h3>
    <p class="font-sans text-sm text-olive leading-relaxed">
      Architect complex software systems, refactor production codebases, and generate resilient tests with end-to-end reliability.
    </p>
  </div>

  <!-- Feature Card 3 -->
  <div class="bg-ivory border border-cream rounded-2xl p-7 shadow-whisper hover:shadow-[0_0_0_1px_#e8e6dc,0_8px_30px_rgba(20,20,19,0.06)] transition-all">
    <div class="w-10 h-10 rounded-xl bg-sand flex items-center justify-center text-terracotta mb-5">
      <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24">
        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m5.618-4.016A11.955 11.955 0 0112 2.944a11.955 11.955 0 01-8.618 3.04A12.02 12.02 0 003 9c0 5.591 3.824 10.29 9 11.622 5.176-1.332 9-6.03 9-11.622 0-1.042-.133-2.052-.382-3.016z"/>
      </svg>
    </div>
    <h3 class="font-serif font-medium text-xl text-nearblack mb-2">Constitutional Safety</h3>
    <p class="font-sans text-sm text-olive leading-relaxed">
      Rooted in frontier AI safety principles, ensuring helpful responses while proactively avoiding deceit and vulnerability exploitation.
    </p>
  </div>
</div>
```

---

### 7.6 Model Comparison Tier Grid (Opus / Sonnet / Haiku)
```html
<div class="max-w-6xl mx-auto px-6 py-16">
  <div class="text-center mb-12">
    <h2 class="font-serif font-medium text-3xl md:text-4xl text-nearblack mb-3">The Model Family</h2>
    <p class="font-sans text-base text-olive">Right-sized intelligence for every tier of compute and complexity.</p>
  </div>

  <div class="grid grid-cols-1 md:grid-cols-3 gap-6 items-stretch">
    <!-- Card: Haiku -->
    <div class="bg-ivory border border-cream rounded-2xl p-6 flex flex-col justify-between shadow-whisper">
      <div>
        <div class="flex items-center justify-between mb-4">
          <h3 class="font-serif font-medium text-2xl text-nearblack">Haiku</h3>
          <span class="px-2.5 py-0.5 rounded-full bg-sand text-xs font-medium text-charcoal">Fastest</span>
        </div>
        <p class="font-sans text-sm text-olive mb-6">Near-instant responsiveness for high-volume, latency-critical production tasks.</p>
        <div class="border-t border-cream pt-4 space-y-2 text-xs text-olive font-sans">
          <div class="flex justify-between"><span>Speed</span><span class="text-nearblack font-medium">Ultra-fast</span></div>
          <div class="flex justify-between"><span>Context Window</span><span class="text-nearblack font-medium">200K tokens</span></div>
          <div class="flex justify-between"><span>Ideal For</span><span class="text-nearblack font-medium">Customer support, triage</span></div>
        </div>
      </div>
      <button class="mt-8 w-full py-2 text-sm font-medium text-charcoal bg-sand hover:bg-[#dedcd0] rounded-lg shadow-[0_0_0_1px_#d1cfc5] transition-colors">
        Deploy Haiku
      </button>
    </div>

    <!-- Card: Sonnet (Highlighted with Terracotta Accent) -->
    <div class="bg-ivory border-2 border-terracotta/40 rounded-2xl p-6 flex flex-col justify-between shadow-[0_4px_24px_rgba(201,100,66,0.08)] relative">
      <div class="absolute -top-3 left-1/2 -translate-x-1/2 px-3 py-0.5 rounded-full bg-terracotta text-ivory text-[11px] font-medium tracking-wide">
        RECOMMENDED
      </div>
      <div>
        <div class="flex items-center justify-between mb-4 mt-1">
          <h3 class="font-serif font-medium text-2xl text-nearblack">Sonnet</h3>
          <span class="px-2.5 py-0.5 rounded-full bg-terracotta/10 text-xs font-medium text-terracotta">Balanced Power</span>
        </div>
        <p class="font-sans text-sm text-olive mb-6">The ideal balance of frontier intelligence and speed for enterprise coding and writing.</p>
        <div class="border-t border-cream pt-4 space-y-2 text-xs text-olive font-sans">
          <div class="flex justify-between"><span>Coding</span><span class="text-nearblack font-medium">State-of-the-art</span></div>
          <div class="flex justify-between"><span>Context Window</span><span class="text-nearblack font-medium">200K tokens</span></div>
          <div class="flex justify-between"><span>Reasoning</span><span class="text-nearblack font-medium">Hybrid extended</span></div>
        </div>
      </div>
      <button class="mt-8 w-full py-2 text-sm font-medium text-ivory bg-terracotta hover:bg-terracotta-hover rounded-xl shadow-[0_0_0_1px_#c96442] transition-colors">
        Deploy Sonnet
      </button>
    </div>

    <!-- Card: Opus -->
    <div class="bg-ivory border border-cream rounded-2xl p-6 flex flex-col justify-between shadow-whisper">
      <div>
        <div class="flex items-center justify-between mb-4">
          <h3 class="font-serif font-medium text-2xl text-nearblack">Opus</h3>
          <span class="px-2.5 py-0.5 rounded-full bg-sand text-xs font-medium text-charcoal">Deep Thought</span>
        </div>
        <p class="font-sans text-sm text-olive mb-6">Maximum depth for high-stakes analysis, scientific synthesis, and complex strategies.</p>
        <div class="border-t border-cream pt-4 space-y-2 text-xs text-olive font-sans">
          <div class="flex justify-between"><span>Comprehension</span><span class="text-nearblack font-medium">Maximal</span></div>
          <div class="flex justify-between"><span>Context Window</span><span class="text-nearblack font-medium">200K tokens</span></div>
          <div class="flex justify-between"><span>Ideal For</span><span class="text-nearblack font-medium">Novel synthesis, logic</span></div>
        </div>
      </div>
      <button class="mt-8 w-full py-2 text-sm font-medium text-charcoal bg-sand hover:bg-[#dedcd0] rounded-lg shadow-[0_0_0_1px_#d1cfc5] transition-colors">
        Deploy Opus
      </button>
    </div>
  </div>
</div>
```

---

### 7.7 Form Inputs & Focus States (Accessible `#3898ec` Ring)
```html
<div class="max-w-md mx-auto p-6 bg-ivory border border-cream rounded-2xl shadow-whisper space-y-5">
  <div>
    <label class="block text-xs font-medium text-charcoal uppercase tracking-wider mb-2">API Project Name</label>
    <input 
      type="text" 
      placeholder="e.g. Constitutional Research Workspace" 
      class="w-full px-3.5 py-2.5 bg-parchment text-nearblack placeholder:text-stone text-sm rounded-xl border border-warmborder focus:outline-none focus:border-transparent focus:ring-2 focus:ring-[#3898ec] transition-all"
    />
  </div>

  <div>
    <label class="block text-xs font-medium text-charcoal uppercase tracking-wider mb-2">System Prompt Instructions</label>
    <textarea 
      rows="3" 
      placeholder="Describe how the assistant should respond..." 
      class="w-full px-3.5 py-2.5 bg-parchment text-nearblack placeholder:text-stone text-sm rounded-xl border border-warmborder focus:outline-none focus:border-transparent focus:ring-2 focus:ring-[#3898ec] transition-all resize-none"
    ></textarea>
  </div>

  <div class="flex items-center justify-between pt-2">
    <span class="text-xs text-olive">Saved in local session</span>
    <button class="px-4 py-2 text-sm font-medium text-ivory bg-terracotta hover:bg-terracotta-hover rounded-xl shadow-[0_0_0_1px_#c96442] transition-colors">
      Save Configuration
    </button>
  </div>
</div>
```

---

### 7.8 Editorial Code Block & Terminal Component
```html
<div class="max-w-3xl mx-auto rounded-2xl overflow-hidden border border-surface bg-nearblack text-silver shadow-2xl">
  <!-- Code Header / Mac-like minimal tab -->
  <div class="px-4 py-3 bg-[#1d1d1c] border-b border-surface flex items-center justify-between text-xs">
    <div class="flex items-center gap-2">
      <span class="w-2.5 h-2.5 rounded-full bg-[#444341]"></span>
      <span class="font-mono text-stone">claude_client.py</span>
    </div>
    <button class="flex items-center gap-1.5 text-stone hover:text-silver transition-colors text-xs font-mono">
      <svg class="w-3.5 h-3.5" fill="none" stroke="currentColor" viewBox="0 0 24 24">
        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M8 16H6a2 2 0 01-2-2V6a2 2 0 012-2h8a2 2 0 012 2v2m-6 12h8a2 2 0 002-2v-8a2 2 0 00-2-2h-8a2 2 0 00-2 2v8a2 2 0 002 2z"/>
      </svg>
      <span>Copy code</span>
    </button>
  </div>

  <!-- Code Body with Anthropic Syntax Tones -->
  <pre class="p-5 font-mono text-xs md:text-sm leading-relaxed overflow-x-auto text-[#d4d2c9]">
<code><span class="text-stone"># Initialize the Anthropic client</span>
<span class="text-coral">import</span> anthropic

client = anthropic.Anthropic()

message = client.messages.create(
    model=<span class="text-[#99b378]">"claude-3-7-sonnet-20250219"</span>,
    max_tokens=<span class="text-[#e0a96d]">1024</span>,
    messages=[
        {<span class="text-[#99b378]">"role"</span>: <span class="text-[#99b378]">"user"</span>, <span class="text-[#99b378]">"content"</span>: <span class="text-[#99b378]">"Explain the literary aesthetic of Claude."</span>}
    ]
)

<span class="text-stone"># Stream response gracefully</span>
<span class="text-coral">print</span>(message.content[<span class="text-[#e0a96d]">0</span>].text)</code></pre>
</div>
```

---

### 7.9 Light-to-Dark Chapter Alternation Section
Anthropic alternates between **Parchment light** and **Warm Near Black dark** sections to create the sensory rhythm of turning chapters in a book.

```html
<!-- Dark "Chapter" Section -->
<section class="w-full bg-nearblack text-ivory py-24 px-6 mt-20 border-t border-surface">
  <div class="max-w-5xl mx-auto">
    <div class="max-w-2xl">
      <span class="text-xs font-mono uppercase tracking-widest text-coral mb-4 block">Section II &mdash; Safety by Architecture</span>
      <h2 class="font-serif font-medium text-4xl md:text-5xl text-ivory leading-tight mb-6">
        Constitutional AI and empirical alignment.
      </h2>
      <p class="font-sans text-silver text-base md:text-lg leading-relaxed mb-8">
        We train AI systems using principles derived from the Universal Declaration of Human Rights and best practices in safety research, creating models that are steerable, honest, and harmless by default.
      </p>
      <div class="flex items-center gap-4">
        <button class="px-5 py-2.5 text-sm font-medium text-ivory bg-terracotta hover:bg-terracotta-hover rounded-xl shadow-[0_0_0_1px_#c96442] transition-colors">
          Explore Alignment Papers
        </button>
        <button class="px-5 py-2.5 text-sm font-medium text-silver hover:text-ivory bg-surface rounded-xl border border-surface transition-colors">
          View Model Card
        </button>
      </div>
    </div>
  </div>
</section>
```

---

## 8. The 10 Inviolable Design Rules (Do's & Don'ts)

| # | Rule | Authentic Practice (DO) | Severe Violation (DON'T) |
|---|:---|:---|:---|
| 1 | **Canvas Tone** | Always use warm Parchment (`#f5f4ed`) or Ivory (`#faf9f5`) for light backgrounds. | Never use pure white (`#ffffff`) as a page-wide canvas. |
| 2 | **Headings** | Always use serif fonts (`Newsreader`/`Georgia`) strictly at **weight 500**. | Never use bold `700` or thin `300` on serif headlines; never use sans-serif for main titles. |
| 3 | **Accent Restraint** | Reserve Terracotta (`#c96442`) exclusively for primary CTAs and brand moments. | Do not paint cards, banners, or regular text blocks in terracotta. |
| 4 | **Neutral Undertones** | Every gray must possess a warm, yellow-olive tint (`#5e5d59`, `#87867f`, `#4d4c48`). | Never use cold zinc/slate blue-grays (`#64748b`, `#71717a`). |
| 5 | **Depth Strategy** | Use ring halos (`0 0 0 1px`) and ultra-soft whisper shadows (`rgba(20,20,19,0.05)`). | Never use heavy black drop shadows (`box-shadow: 0 10px 30px rgba(0,0,0,0.2)`). |
| 6 | **Corner Radii** | Employ soft, approachable radii (`8px`–`16px` on UI elements, `24px`–`32px` on containers). | Never use hard 90° sharp corners (`rounded-none` / `0px`) on modern Claude interfaces. |
| 7 | **Line Heights** | Keep headline leading tight (1.10–1.25) and body leading generous (1.55–1.65). | Never cram body text into tight line-heights (e.g. 1.2–1.35). |
| 8 | **Dark Mode Tone** | Use Warm Near Black (`#141413`) and Warm Charcoal (`#30302e`). | Never use pitch-black `#000000` or cold navy darks (`#0f172a`). |
| 9 | **Interactive Ring** | Use `#d1cfc5` for warm secondary buttons and `#3898ec` exclusively for accessibility input focus. | Do not use random purple/indigo focus outlines. |
| 10 | **Page Pacing** | Alternate between Parchment and Near Black chapters with generous vertical whitespace (`py-20`–`py-28`). | Never create monotonous, wall-to-wall single-tone feeds without reading pauses. |

---

## 9. Agent Execution Instructions for Pi

When instructed to generate, redesign, or style any website, dashboard, or HTML component using the Anthropic aesthetic:

1. **Invoke the Typography Hierarchy**:
   - Apply `font-serif font-medium` to all headings (`h1` through `h4`).
   - Apply `font-sans` with `leading-relaxed` (1.6) to all paragraphs and body copy.
   - Apply `font-mono` to any code or technical snippet.

2. **Establish the Warm Ground**:
   - Set the body background to `bg-[#f5f4ed]` and text to `text-[#141413]`.
   - Elevated cards must use `bg-[#faf9f5] border border-[#f0eee6] rounded-2xl shadow-[0_4px_24px_rgba(20,20,19,0.05)]`.

3. **Deploy the Brand CTA**:
   - The primary button must be `bg-[#c96442] hover:bg-[#b85736] text-[#faf9f5] rounded-xl shadow-[0_0_0_1px_#c96442]`.
   - Secondary button must be `bg-[#e8e6dc] hover:bg-[#dedcd0] text-[#4d4c48] rounded-lg shadow-[0_0_0_1px_#d1cfc5]`.

4. **Verify Neutrals**:
   - Inspect all gray utility classes: replace any default `text-gray-*` or `text-slate-*` with the warm tokens: `#5e5d59` (secondary text) and `#87867f` (metadata).
