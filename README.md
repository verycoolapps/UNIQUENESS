<div align="center">

<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 900 320" width="900" height="320">
  <defs>
    <linearGradient id="bg" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#0a0a0f;stop-opacity:1" />
      <stop offset="50%" style="stop-color:#0d0d1a;stop-opacity:1" />
      <stop offset="100%" style="stop-color:#050510;stop-opacity:1" />
    </linearGradient>
    <linearGradient id="accent" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#6c3bff;stop-opacity:1" />
      <stop offset="50%" style="stop-color:#a855f7;stop-opacity:1" />
      <stop offset="100%" style="stop-color:#06b6d4;stop-opacity:1" />
    </linearGradient>
    <linearGradient id="accent2" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#06b6d4;stop-opacity:1" />
      <stop offset="100%" style="stop-color:#6c3bff;stop-opacity:1" />
    </linearGradient>
    <filter id="glow">
      <feGaussianBlur stdDeviation="3" result="coloredBlur"/>
      <feMerge><feMergeNode in="coloredBlur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
    <filter id="glow2">
      <feGaussianBlur stdDeviation="6" result="coloredBlur"/>
      <feMerge><feMergeNode in="coloredBlur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
    <radialGradient id="orb1" cx="30%" cy="40%" r="50%">
      <stop offset="0%" style="stop-color:#6c3bff;stop-opacity:0.15" />
      <stop offset="100%" style="stop-color:#6c3bff;stop-opacity:0" />
    </radialGradient>
    <radialGradient id="orb2" cx="70%" cy="60%" r="50%">
      <stop offset="0%" style="stop-color:#06b6d4;stop-opacity:0.12" />
      <stop offset="100%" style="stop-color:#06b6d4;stop-opacity:0" />
    </radialGradient>
  </defs>

  <!-- Background -->
  <rect width="900" height="320" fill="url(#bg)" rx="16"/>
  <rect width="900" height="320" fill="url(#orb1)" rx="16"/>
  <rect width="900" height="320" fill="url(#orb2)" rx="16"/>

  <!-- Grid pattern -->
  <g opacity="0.06" stroke="#a855f7" stroke-width="0.5">
    <line x1="0" y1="40" x2="900" y2="40"/>
    <line x1="0" y1="80" x2="900" y2="80"/>
    <line x1="0" y1="120" x2="900" y2="120"/>
    <line x1="0" y1="160" x2="900" y2="160"/>
    <line x1="0" y1="200" x2="900" y2="200"/>
    <line x1="0" y1="240" x2="900" y2="240"/>
    <line x1="0" y1="280" x2="900" y2="280"/>
    <line x1="60" y1="0" x2="60" y2="320"/>
    <line x1="120" y1="0" x2="120" y2="320"/>
    <line x1="180" y1="0" x2="180" y2="320"/>
    <line x1="240" y1="0" x2="240" y2="320"/>
    <line x1="300" y1="0" x2="300" y2="320"/>
    <line x1="360" y1="0" x2="360" y2="320"/>
    <line x1="420" y1="0" x2="420" y2="320"/>
    <line x1="480" y1="0" x2="480" y2="320"/>
    <line x1="540" y1="0" x2="540" y2="320"/>
    <line x1="600" y1="0" x2="600" y2="320"/>
    <line x1="660" y1="0" x2="660" y2="320"/>
    <line x1="720" y1="0" x2="720" y2="320"/>
    <line x1="780" y1="0" x2="780" y2="320"/>
    <line x1="840" y1="0" x2="840" y2="320"/>
  </g>

  <!-- Decorative orbs -->
  <circle cx="120" cy="80" r="40" fill="none" stroke="#6c3bff" stroke-width="0.5" opacity="0.3"/>
  <circle cx="120" cy="80" r="25" fill="none" stroke="#a855f7" stroke-width="0.5" opacity="0.4"/>
  <circle cx="120" cy="80" r="8" fill="#6c3bff" opacity="0.6" filter="url(#glow)"/>

  <circle cx="780" cy="240" r="40" fill="none" stroke="#06b6d4" stroke-width="0.5" opacity="0.3"/>
  <circle cx="780" cy="240" r="25" fill="none" stroke="#06b6d4" stroke-width="0.5" opacity="0.4"/>
  <circle cx="780" cy="240" r="8" fill="#06b6d4" opacity="0.6" filter="url(#glow)"/>

  <!-- Top accent line -->
  <rect x="0" y="0" width="900" height="3" fill="url(#accent)" rx="2" opacity="0.8"/>

  <!-- Bottom accent line -->
  <rect x="0" y="317" width="900" height="3" fill="url(#accent2)" rx="2" opacity="0.6"/>

  <!-- Geometric diamond accent -->
  <g transform="translate(450, 55)" filter="url(#glow2)">
    <polygon points="0,-12 10,0 0,12 -10,0" fill="none" stroke="url(#accent)" stroke-width="1.5" opacity="0.9"/>
    <polygon points="0,-6 5,0 0,6 -5,0" fill="url(#accent)" opacity="0.8"/>
  </g>

  <!-- Main title -->
  <text x="450" y="115" font-family="'SF Pro Display', 'Segoe UI', 'Helvetica Neue', Arial, sans-serif" font-size="72" font-weight="900" text-anchor="middle" letter-spacing="12" filter="url(#glow2)">
    <tspan fill="url(#accent)">UNIQUENESS</tspan>
  </text>

  <!-- Subtitle -->
  <text x="450" y="150" font-family="'SF Pro Display', 'Segoe UI', 'Helvetica Neue', Arial, sans-serif" font-size="14" font-weight="300" text-anchor="middle" fill="#94a3b8" letter-spacing="4">THE UNIVERSAL UNIQUENESS INTELLIGENCE ENGINE</text>

  <!-- Divider -->
  <line x1="300" y1="170" x2="600" y2="170" stroke="url(#accent)" stroke-width="0.5" opacity="0.6"/>
  <circle cx="450" cy="170" r="3" fill="#a855f7" opacity="0.8"/>

  <!-- Tagline -->
  <text x="450" y="198" font-family="'SF Pro Display', 'Segoe UI', 'Helvetica Neue', Arial, sans-serif" font-size="13" font-weight="400" text-anchor="middle" fill="#c4b5fd" font-style="italic" letter-spacing="1">
    "Discover What Makes Anything Unmistakably Different."
  </text>

  <!-- Feature pills -->
  <g transform="translate(450, 235)">
    <!-- Pill 1 -->
    <rect x="-390" y="-14" width="130" height="28" rx="14" fill="#6c3bff" fill-opacity="0.15" stroke="#6c3bff" stroke-width="0.8" stroke-opacity="0.5"/>
    <text x="-325" y="5" font-family="'SF Pro Display', 'Segoe UI', Arial, sans-serif" font-size="10" font-weight="600" text-anchor="middle" fill="#a78bfa" letter-spacing="0.5">12 INTEL ENGINES</text>

    <!-- Pill 2 -->
    <rect x="-240" y="-14" width="130" height="28" rx="14" fill="#a855f7" fill-opacity="0.15" stroke="#a855f7" stroke-width="0.8" stroke-opacity="0.5"/>
    <text x="-175" y="5" font-family="'SF Pro Display', 'Segoe UI', Arial, sans-serif" font-size="10" font-weight="600" text-anchor="middle" fill="#c084fc" letter-spacing="0.5">15D MATRIX</text>

    <!-- Pill 3 -->
    <rect x="-90" y="-14" width="130" height="28" rx="14" fill="#06b6d4" fill-opacity="0.12" stroke="#06b6d4" stroke-width="0.8" stroke-opacity="0.5"/>
    <text x="-25" y="5" font-family="'SF Pro Display', 'Segoe UI', Arial, sans-serif" font-size="10" font-weight="600" text-anchor="middle" fill="#67e8f9" letter-spacing="0.5">12 MODES</text>

    <!-- Pill 4 -->
    <rect x="60" y="-14" width="130" height="28" rx="14" fill="#6c3bff" fill-opacity="0.15" stroke="#6c3bff" stroke-width="0.8" stroke-opacity="0.5"/>
    <text x="125" y="5" font-family="'SF Pro Display', 'Segoe UI', Arial, sans-serif" font-size="10" font-weight="600" text-anchor="middle" fill="#a78bfa" letter-spacing="0.5">ALL DOMAINS</text>

    <!-- Pill 5 -->
    <rect x="210" y="-14" width="130" height="28" rx="14" fill="#a855f7" fill-opacity="0.15" stroke="#a855f7" stroke-width="0.8" stroke-opacity="0.5"/>
    <text x="275" y="5" font-family="'SF Pro Display', 'Segoe UI', Arial, sans-serif" font-size="10" font-weight="600" text-anchor="middle" fill="#c084fc" letter-spacing="0.5">EN · ID</text>
  </g>

  <!-- Version badge -->
  <g transform="translate(820, 30)">
    <rect x="-40" y="-12" width="80" height="24" rx="12" fill="#6c3bff" fill-opacity="0.2" stroke="#6c3bff" stroke-width="0.8"/>
    <text x="0" y="5" font-family="'SF Mono', 'Fira Code', monospace" font-size="10" font-weight="700" text-anchor="middle" fill="#a78bfa">v1.0 SAKTI</text>
  </g>

  <!-- Corner accents -->
  <path d="M0,0 L0,30 L3,30 L3,3 L30,3 L30,0 Z" fill="url(#accent)" opacity="0.6"/>
  <path d="M900,0 L870,0 L870,3 L897,3 L897,30 L900,30 Z" fill="url(#accent)" opacity="0.6"/>
  <path d="M0,320 L0,290 L3,290 L3,317 L30,317 L30,320 Z" fill="url(#accent2)" opacity="0.6"/>
  <path d="M900,320 L870,320 L870,317 L897,317 L897,290 L900,290 Z" fill="url(#accent2)" opacity="0.6"/>

  <!-- Bottom text -->
  <text x="450" y="295" font-family="'SF Pro Display', 'Segoe UI', Arial, sans-serif" font-size="10" font-weight="400" text-anchor="middle" fill="#475569" letter-spacing="2">A CLAUDE CODE SKILL · PRODUCTION-READY · WORLD-CLASS</text>
</svg>

<br/>

[![Claude Code Skill](https://img.shields.io/badge/Claude%20Code-Skill-6c3bff?style=for-the-badge&logo=anthropic&logoColor=white)](https://claude.ai/claude-code)
[![Version](https://img.shields.io/badge/Version-1.0%20SAKTI-a855f7?style=for-the-badge)](.)
[![Language](https://img.shields.io/badge/Language-EN%20%7C%20ID-06b6d4?style=for-the-badge)](.)
[![Domain](https://img.shields.io/badge/Domain-Universal-10b981?style=for-the-badge)](.)
[![Quality](https://img.shields.io/badge/Quality-World--Class-f59e0b?style=for-the-badge)](.)

</div>

---

<div align="center">

## ⚡ What is UNIQUENESS?

*UNIQUENESS is not a comparison tool. It's a **discovery engine**.*

</div>

Most tools tell you what's different. **UNIQUENESS tells you what makes that difference matter** — how rare it is, what it's worth, and how to turn it into an unmistakable advantage.

Whether you're comparing two AI models, two coffee shops, two logos, two scientific theories, two people's professional profiles, or anything else that exists — UNIQUENESS adapts its intelligence to find what actually sets something apart.

> *"Don't just compare what exists. Discover what makes it impossible to confuse with anything else."*

---

<div align="center">

<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 900 180" width="900" height="180">
  <defs>
    <linearGradient id="bg2" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#0a0a0f;stop-opacity:1" />
      <stop offset="100%" style="stop-color:#0d0d1a;stop-opacity:1" />
    </linearGradient>
    <linearGradient id="a1" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#6c3bff;stop-opacity:1" />
      <stop offset="100%" style="stop-color:#a855f7;stop-opacity:1" />
    </linearGradient>
    <linearGradient id="a2" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#a855f7;stop-opacity:1" />
      <stop offset="100%" style="stop-color:#06b6d4;stop-opacity:1" />
    </linearGradient>
    <linearGradient id="a3" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#06b6d4;stop-opacity:1" />
      <stop offset="100%" style="stop-color:#10b981;stop-opacity:1" />
    </linearGradient>
    <linearGradient id="a4" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#10b981;stop-opacity:1" />
      <stop offset="100%" style="stop-color:#f59e0b;stop-opacity:1" />
    </linearGradient>
    <filter id="g3">
      <feGaussianBlur stdDeviation="2" result="coloredBlur"/>
      <feMerge><feMergeNode in="coloredBlur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
  </defs>

  <rect width="900" height="180" fill="url(#bg2)" rx="12"/>
  <rect x="0" y="0" width="900" height="2" fill="url(#a1)" rx="1" opacity="0.6"/>

  <!-- Stat cards -->
  <!-- Card 1 -->
  <rect x="20" y="20" width="190" height="140" rx="10" fill="#0d0d1a" stroke="#6c3bff" stroke-width="0.8" stroke-opacity="0.4"/>
  <rect x="20" y="20" width="190" height="3" rx="2" fill="url(#a1)" opacity="0.8"/>
  <text x="115" y="75" font-family="'SF Pro Display', Arial, sans-serif" font-size="42" font-weight="900" text-anchor="middle" fill="#a78bfa" filter="url(#g3)">12</text>
  <text x="115" y="100" font-family="'SF Pro Display', Arial, sans-serif" font-size="11" font-weight="600" text-anchor="middle" fill="#6c3bff" letter-spacing="1">INTELLIGENCE</text>
  <text x="115" y="118" font-family="'SF Pro Display', Arial, sans-serif" font-size="11" font-weight="600" text-anchor="middle" fill="#6c3bff" letter-spacing="1">ENGINES</text>
  <text x="115" y="145" font-family="'SF Pro Display', Arial, sans-serif" font-size="9" font-weight="400" text-anchor="middle" fill="#475569">Context · Hidden · Synthesis</text>

  <!-- Card 2 -->
  <rect x="230" y="20" width="190" height="140" rx="10" fill="#0d0d1a" stroke="#a855f7" stroke-width="0.8" stroke-opacity="0.4"/>
  <rect x="230" y="20" width="190" height="3" rx="2" fill="url(#a2)" opacity="0.8"/>
  <text x="325" y="75" font-family="'SF Pro Display', Arial, sans-serif" font-size="42" font-weight="900" text-anchor="middle" fill="#c084fc" filter="url(#g3)">15</text>
  <text x="325" y="100" font-family="'SF Pro Display', Arial, sans-serif" font-size="11" font-weight="600" text-anchor="middle" fill="#a855f7" letter-spacing="1">UNIQUENESS</text>
  <text x="325" y="118" font-family="'SF Pro Display', Arial, sans-serif" font-size="11" font-weight="600" text-anchor="middle" fill="#a855f7" letter-spacing="1">DIMENSIONS</text>
  <text x="325" y="145" font-family="'SF Pro Display', Arial, sans-serif" font-size="9" font-weight="400" text-anchor="middle" fill="#475569">Functional · Cultural · Future</text>

  <!-- Card 3 -->
  <rect x="440" y="20" width="190" height="140" rx="10" fill="#0d0d1a" stroke="#06b6d4" stroke-width="0.8" stroke-opacity="0.4"/>
  <rect x="440" y="20" width="190" height="3" rx="2" fill="url(#a3)" opacity="0.8"/>
  <text x="535" y="75" font-family="'SF Pro Display', Arial, sans-serif" font-size="42" font-weight="900" text-anchor="middle" fill="#67e8f9" filter="url(#g3)">12</text>
  <text x="535" y="100" font-family="'SF Pro Display', Arial, sans-serif" font-size="11" font-weight="600" text-anchor="middle" fill="#06b6d4" letter-spacing="1">COMPARISON</text>
  <text x="535" y="118" font-family="'SF Pro Display', Arial, sans-serif" font-size="11" font-weight="600" text-anchor="middle" fill="#06b6d4" letter-spacing="1">MODES</text>
  <text x="535" y="145" font-family="'SF Pro Display', Arial, sans-serif" font-size="9" font-weight="400" text-anchor="middle" fill="#475569">Head-to-Head · Audit · Extreme</text>

  <!-- Card 4 -->
  <rect x="650" y="20" width="230" height="140" rx="10" fill="#0d0d1a" stroke="#10b981" stroke-width="0.8" stroke-opacity="0.4"/>
  <rect x="650" y="20" width="230" height="3" rx="2" fill="url(#a4)" opacity="0.8"/>
  <text x="765" y="70" font-family="'SF Pro Display', Arial, sans-serif" font-size="30" font-weight="900" text-anchor="middle" fill="#34d399" filter="url(#g3)">∞</text>
  <text x="765" y="95" font-family="'SF Pro Display', Arial, sans-serif" font-size="11" font-weight="600" text-anchor="middle" fill="#10b981" letter-spacing="1">UNIVERSAL</text>
  <text x="765" y="113" font-family="'SF Pro Display', Arial, sans-serif" font-size="11" font-weight="600" text-anchor="middle" fill="#10b981" letter-spacing="1">DOMAIN COVERAGE</text>
  <text x="765" y="135" font-family="'SF Pro Display', Arial, sans-serif" font-size="9" font-weight="400" text-anchor="middle" fill="#475569">Business · Tech · Creative</text>
  <text x="765" y="150" font-family="'SF Pro Display', Arial, sans-serif" font-size="9" font-weight="400" text-anchor="middle" fill="#475569">Science · Food · Games · People</text>
</svg>

</div>

---

## 🇬🇧 English Documentation

### Installation

```bash
# Install via Claude Code skill installer
/skill-installer uniqueness

# Or clone and install manually
git clone https://github.com/verycoolapps/UNIQUENESS.git
cd UNIQUENESS
# Follow your Claude Code skill installation procedure
```

### Quick Start

Just describe what you want to compare — UNIQUENESS figures out the rest:

```
"Compare iPhone 16 Pro vs Samsung Galaxy S25 Ultra"
"What makes my startup different from Notion?"
"Find the hidden uniqueness in this coffee shop"
"Bandingkan dua logo ini"
"Is this game concept truly original?"
"How can I make my personal brand unmistakable?"
```

### Core Capabilities

#### 🔥 12 Intelligence Engines

| Engine | Function |
|--------|----------|
| **Context** | Understands subjects, purpose, audience, environment |
| **Dimension Discovery** | Auto-generates relevant comparison axes |
| **Similarity** | Maps shared traits (surface + structural) |
| **Differentiation** | 7-layer difference analysis |
| **Hidden Uniqueness** | Finds what casual observers miss |
| **Novelty** | Classifies rarity on a 6-level spectrum |
| **Value** | Evaluates whether differences actually matter |
| **Combination** | Discovers rare attribute combinations |
| **Opportunity** | Identifies unexplored differentiation paths |
| **Strategic** | Translates findings into actionable strategy |
| **Evidence & Confidence** | Classifies every claim by evidence quality |
| **Synthesis** | Delivers a definitive uniqueness verdict |

#### 🗺️ 15-Dimension Uniqueness Matrix

Evaluates subjects through up to 15 analytical lenses — applied selectively, not as a mandatory checklist:

```
01 Functional    02 Design        03 Conceptual    04 Experiential
05 Emotional     06 Technical     07 Operational   08 Cultural
09 Strategic     10 Economic      11 Social        12 Intellectual
13 Combinational 14 Perceived     15 Future
```

#### ⚡ 12 Comparison Modes

```
MODE 01  Head-to-Head          → A vs B
MODE 02  Multi-Competitor      → One vs many (3–20)
MODE 03  One-to-Many           → One vs entire category
MODE 04  Self-Differentiation  → How to become more distinctive
MODE 05  Uniqueness Audit      → Full 360° assessment
MODE 06  Hidden Difference     → Find non-obvious distinctions
MODE 07  Market White Space    → Find unserved opportunities
MODE 08  Creative Originality  → Evaluate creative distinctiveness
MODE 09  Feature Differentiation → Compare specific capabilities
MODE 10  Positioning Battle    → Who owns the strongest position?
MODE 11  Combination Discovery → Find rare attribute combinations
MODE 12  Extreme Differentiation → Unconventional paths to stand out
```

#### 🌐 Universal Domain Coverage

| Domain | Examples |
|--------|---------|
| **Business & Commerce** | Companies, startups, brands, products, strategies |
| **Technology & AI** | AI models, apps, platforms, algorithms, frameworks |
| **Creative Industries** | Logos, films, games, music, visual identities, characters |
| **Human & Talent** | Skills, personalities, careers, leadership styles |
| **Education & Knowledge** | Learning methods, theories, courses, research |
| **Physical Products** | Food, clothing, electronics, vehicles, materials |
| **Experiences & Lifestyle** | Restaurants, hotels, events, communities |
| **Strategy & Ideas** | Business concepts, innovations, campaigns, philosophies |
| **Science & Nature** | Discoveries, biological traits, natural phenomena |
| **Anything Else** | Custom analytical frameworks generated dynamically |

### Scoring System

Each dimension scored 0–10, weighted by domain relevance:

```
 0    No identifiable differentiation
1–2   Extremely conventional
3–4   Slight differentiation
5–6   Moderately distinctive
7–8   Strongly distinctive
 9    Exceptionally distinctive
10    Outstandingly distinctive (within defined scope)
```

Default weights (domain-adaptive):
- Distinctiveness 20% · Originality 15% · Meaningfulness 15%
- Value Creation 15% · Rarity 10% · Audience Relevance 10%
- Combination Strength 10% · Defensibility 5%

### Novelty Classification

| Level | Meaning |
|-------|---------|
| **Common** | Widely shared in the category |
| **Less Common** | Present in minority of alternatives |
| **Uncommon** | Found in very few alternatives |
| **Rare** | Found in almost no alternatives |
| **Highly Distinctive** | Clearly sets the subject apart |
| **Potentially Unprecedented** | May not exist in defined scope (scope always stated) |

> ⚠️ UNIQUENESS never claims "world's first" or "absolutely unique" without defining research scope and gathering evidence.

### Evidence Classification

Every major claim is tagged:

| Tag | Meaning |
|-----|---------|
| 🟢 **VERIFIED FACT** | Supported by reliable, cited evidence |
| 🔵 **OBSERVATION** | Directly observable from available material |
| 🟡 **INFERENCE** | Reasonable interpretation from evidence |
| 🟠 **HYPOTHESIS** | Plausible explanation requiring testing |
| ⚪ **UNKNOWN** | Insufficient information — gaps stated |

### Standard Output Structure

```
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
⚡ UNIQUENESS ANALYSIS
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
📋 01  EXECUTIVE VERDICT
🔍 02  SUBJECT PROFILES
📊 03  COMPARISON MATRIX
🗺️ 04  UNIQUENESS MAP
🏆 05  TOP 10 UNIQUE DISCOVERIES
📈 06  UNIQUENESS SCORECARD
⚡ 07  THE BIGGEST DIFFERENCE
💡 08  HIDDEN OPPORTUNITIES
🎯 09  STRATEGIC RECOMMENDATIONS
🔮 10  FINAL UNIQUENESS VERDICT
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
```

### File Structure

```
UNIQUENESS/
├── SKILL.md                          ← Main skill (install this)
├── README.md                         ← This file
│
├── references/
│   ├── uniqueness-framework.md       ← Philosophical + analytical foundation
│   ├── comparison-methodology.md     ← Systematic comparison methods
│   ├── scoring-methodology.md        ← Scoring system + calibration
│   ├── research-standards.md         ← Evidence + research protocols
│   ├── domain-frameworks.md          ← Domain-specific lenses (10 domains)
│   ├── hidden-uniqueness-methods.md  ← Hidden discovery techniques
│   ├── differentiation-strategy.md   ← Strategic differentiation playbook
│   └── output-examples.md            ← 5 annotated analysis examples
│
├── workflows/
│   ├── head-to-head.md               ← A vs B workflow
│   ├── multi-competitor.md           ← Multi-competitor workflow
│   ├── uniqueness-audit.md           ← Full audit workflow
│   ├── hidden-difference.md          ← Hidden discovery workflow
│   ├── market-whitespace.md          ← White space identification workflow
│   ├── creative-originality.md       ← Creative analysis workflow
│   └── extreme-differentiation.md    ← Unconventional differentiation workflow
│
└── evals/
    ├── test-cases.md                 ← 17 comprehensive test scenarios
    ├── quality-rubric.md             ← 10-gate quality evaluation framework
    └── regression-tests.md           ← Regression + anti-pattern detection
```

---

## 🇮🇩 Dokumentasi Bahasa Indonesia

### Apa itu UNIQUENESS?

**UNIQUENESS** adalah Universal Uniqueness Intelligence Engine — mesin kecerdasan universal yang dirancang untuk membandingkan *apa saja* dengan *apa saja*, dan menemukan apa yang membuat sesuatu benar-benar berbeda, langka, orisinal, atau tak tertandingi.

Ini **bukan** alat perbandingan biasa. Ini **bukan** pembuat daftar pro-kontra. Ini **bukan** analisis SWOT generik.

UNIQUENESS adalah sistem kecerdasan canggih yang menemukan perbedaan yang tidak kasat mata, kombinasi atribut yang langka, dan peluang diferensiasi yang belum dimanfaatkan — di semua domain.

> *"Jangan hanya bandingkan apa yang ada. Temukan apa yang membuatnya mustahil untuk dikacaukan dengan hal lain."*

### Cara Penggunaan

Cukup deskripsikan apa yang ingin kamu bandingkan — dalam bahasa Indonesia atau Inggris:

```
"Bandingkan iPhone 16 Pro vs Samsung Galaxy S25 Ultra"
"Apa yang membuat startup saya berbeda dari Notion?"
"Temukan keunikan tersembunyi dari kedai kopi ini"
"Compare these two logos"
"Apakah konsep game ini benar-benar orisinal?"
"Bagaimana cara membuat personal brand saya tak terlupakan?"
"Audit keunikan bisnis saya secara menyeluruh"
"Siapa yang memiliki positioning paling kuat di antara 5 kompetitor ini?"
```

### Kemampuan Inti

#### 🔥 12 Mesin Kecerdasan

| Mesin | Fungsi |
|-------|--------|
| **Context** | Memahami subjek, tujuan, audiens, lingkungan |
| **Dimension Discovery** | Menghasilkan dimensi perbandingan yang relevan otomatis |
| **Similarity** | Memetakan kesamaan (permukaan + struktural) |
| **Differentiation** | Analisis perbedaan 7-lapis |
| **Hidden Uniqueness** | Menemukan apa yang luput dari pengamat biasa |
| **Novelty** | Mengklasifikasi kelangkaan dalam 6 level |
| **Value** | Mengevaluasi apakah perbedaan benar-benar bernilai |
| **Combination** | Menemukan kombinasi atribut yang langka |
| **Opportunity** | Mengidentifikasi jalur diferensiasi yang belum dijelajahi |
| **Strategic** | Menerjemahkan temuan menjadi strategi yang bisa dijalankan |
| **Evidence & Confidence** | Mengklasifikasikan setiap klaim berdasarkan kualitas bukti |
| **Synthesis** | Memberikan vonis keunikan yang definitif |

#### 🗺️ Matriks Keunikan 15 Dimensi

Mengevaluasi subjek melalui hingga 15 lensa analitis — dipilih secara selektif, bukan checklist wajib:

```
01 Fungsional    02 Desain        03 Konseptual    04 Pengalaman
05 Emosional     06 Teknis        07 Operasional   08 Kultural
09 Strategis     10 Ekonomis      11 Sosial        12 Intelektual
13 Kombinasional 14 Persepsi      15 Masa Depan
```

#### ⚡ 12 Mode Perbandingan

```
MODE 01  Head-to-Head          → A vs B
MODE 02  Multi-Competitor      → Satu vs banyak (3–20)
MODE 03  One-to-Many           → Satu vs seluruh kategori
MODE 04  Self-Differentiation  → Bagaimana menjadi lebih distinctive?
MODE 05  Uniqueness Audit      → Penilaian 360° menyeluruh
MODE 06  Hidden Difference     → Temukan perbedaan tak kasat mata
MODE 07  Market White Space    → Temukan peluang yang belum dilayani
MODE 08  Creative Originality  → Evaluasi keorisinelan kreatif
MODE 09  Feature Differentiation → Bandingkan kapabilitas spesifik
MODE 10  Positioning Battle    → Siapa yang menguasai posisi paling kuat?
MODE 11  Combination Discovery → Temukan kombinasi atribut langka
MODE 12  Extreme Differentiation → Cara tak konvensional untuk tampil beda
```

#### 🌐 Cakupan Domain Universal

| Domain | Contoh |
|--------|--------|
| **Bisnis & Perdagangan** | Perusahaan, startup, brand, produk, strategi |
| **Teknologi & AI** | Model AI, aplikasi, platform, algoritma |
| **Industri Kreatif** | Logo, film, game, musik, identitas visual |
| **Manusia & Bakat** | Skill, kepribadian, karier, gaya kepemimpinan |
| **Pendidikan & Ilmu** | Metode belajar, teori, kursus, penelitian |
| **Produk Fisik** | Makanan, pakaian, elektronik, kendaraan |
| **Pengalaman & Gaya Hidup** | Restoran, hotel, event, komunitas |
| **Strategi & Ide** | Konsep bisnis, inovasi, kampanye, filosofi |
| **Sains & Alam** | Penemuan, sifat biologis, fenomena alam |
| **Apa Saja Lainnya** | Framework analitis dibuat secara dinamis |

### Sistem Penilaian

Setiap dimensi dinilai 0–10, dengan bobot yang disesuaikan per domain:

```
 0    Tidak ada diferensiasi yang teridentifikasi
1–2   Sangat konvensional
3–4   Diferensiasi ringan
5–6   Cukup distinctive
7–8   Sangat distinctive
 9    Exceptionally distinctive
10    Outstandingly distinctive (dalam scope yang didefinisikan)
```

### Klasifikasi Bukti

Setiap klaim utama diberi label:

| Label | Arti |
|-------|------|
| 🟢 **FAKTA TERVERIFIKASI** | Didukung bukti yang dapat diandalkan dan dikutip |
| 🔵 **OBSERVASI** | Dapat langsung diamati dari materi yang tersedia |
| 🟡 **INFERENSI** | Interpretasi masuk akal yang diturunkan dari bukti |
| 🟠 **HIPOTESIS** | Penjelasan yang masuk akal namun perlu pengujian |
| ⚪ **TIDAK DIKETAHUI** | Informasi tidak cukup — kesenjangan dinyatakan |

### Filosofi Anti-Generik

UNIQUENESS **tidak akan pernah** menghasilkan:
- "Keduanya unik dengan caranya masing-masing" (tanpa substantiasi mendalam)
- "Tergantung preferensi pribadi" (tanpa menjelaskan dimensi preferensi)
- "Ini lebih inovatif" (tanpa bukti dan definisi inovasi)

Setiap temuan penting harus menjawab:
- **APA** yang berbeda secara spesifik?
- **BAGAIMANA** perbedaannya?
- **MENGAPA** berbeda?
- **SEBERAPA SIGNIFIKAN** perbedaannya?
- **SIAPA** yang diuntungkan?
- **BUKTI APA** yang mendukung kesimpulan?

Jika dua subjek sangat mirip — UNIQUENESS akan jujur mengatakannya. Temuan keterbatasan diferensiasi yang jujur lebih berharga dari keunikan yang diciptakan.

---

<div align="center">

<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 900 100" width="900" height="100">
  <defs>
    <linearGradient id="bg3" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#0a0a0f;stop-opacity:1" />
      <stop offset="100%" style="stop-color:#0d0d1a;stop-opacity:1" />
    </linearGradient>
    <linearGradient id="a5" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#6c3bff;stop-opacity:1" />
      <stop offset="50%" style="stop-color:#a855f7;stop-opacity:1" />
      <stop offset="100%" style="stop-color:#06b6d4;stop-opacity:1" />
    </linearGradient>
  </defs>
  <rect width="900" height="100" fill="url(#bg3)" rx="12"/>
  <rect x="0" y="0" width="900" height="2" fill="url(#a5)" rx="1" opacity="0.6"/>
  <text x="450" y="45" font-family="'SF Pro Display', 'Segoe UI', Arial, sans-serif" font-size="16" font-weight="700" text-anchor="middle" fill="#c4b5fd" letter-spacing="2">DIFFERENT IS NOT ENOUGH.</text>
  <text x="450" y="75" font-family="'SF Pro Display', 'Segoe UI', Arial, sans-serif" font-size="20" font-weight="900" text-anchor="middle" letter-spacing="3">
    <tspan fill="#6c3bff">BE </tspan><tspan fill="#a855f7">UN</tspan><tspan fill="#06b6d4">MIS</tspan><tspan fill="#10b981">TA</tspan><tspan fill="#f59e0b">KA</tspan><tspan fill="#a855f7">BLE</tspan><tspan fill="#6c3bff">.</tspan>
  </text>
</svg>

<br/>

**Built with precision. Designed to discover. Made to matter.**

*A Claude Code Skill by [verycoolapps](https://github.com/verycoolapps)*

</div>
