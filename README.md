<p align="center">
  <img
    src="https://lottie.host/cdb5e749-f393-4333-ad23-8200f121e8d3/Z4sIS9xKDC.svg?v=1"
    alt="dotLottie Animation"
    width="550"
  />
</p>


# Motion Design Skill

Universal motion design principles for AI agents. Philosophy-first, implementation-agnostic.

Teaches agents to think like motion directors — choosing the right timing, easing, choreography, and emotional intent before writing a single line of animation code. Works with any animation system (CSS, Framer Motion, GSAP, Lottie, Spring, etc.).

## Install

```bash
npx skills add LottieFiles/motion-design-skill
```

Supports [40+ agents](https://skills.sh) including Claude Code, Cursor, Codex, GitHub Copilot, and more.

## What's included

**Core** (`SKILL.md`) — Quick reference with the 8-step checklist, motion personality archetypes, duration/easing tables, property selection guide, common patterns, and quality rules.

**Philosophy** (`director/`) — Deep dives into the three pillars, Disney's 12 principles adapted for UI, emotion-to-motion mapping, choreography, narrative structure, and context adaptation.

**Patterns** (`patterns/`) — Ready-to-use recipes for entrance/exit animations, state feedback (success, error, loading, hover), ambient/continuous motion, and multi-element choreography.

**Reference** (`reference/`) — Lookup tables for timing and easing, property selection guide, quality checklist, and troubleshooting common animation problems.

## When it activates

The skill activates when you're working on:

- UI animations (buttons, cards, modals, page transitions)
- Micro-interactions and feedback animations
- Loading, success, or error states
- Scroll-triggered or progress-based animations
- Establishing brand motion identity
- Multi-element choreography and sequencing

## Example prompts

```
Add a playful entrance animation to these card components
```

```
Create a loading → success → error state transition for this form submit button
```

```
Choreograph the entrance sequence for this dashboard — hero chart first, then stats cards, then sidebar
```

```
Review my animation code and suggest improvements based on motion design principles
```

## Skill structure

```
skills/motion-design/
├── SKILL.md                          # Main skill instructions (< 500 lines)
├── director/
│   ├── core-philosophy.md            # Three Pillars deep dive
│   ├── decision-framework.md         # Full decision pipeline
│   ├── disney-principles.md          # 12 principles, UI-adapted
│   ├── motion-personality.md         # 4 archetypes + brand identity
│   ├── emotion-mapping.md            # Emotion → motion translation
│   ├── choreography.md              # Multi-element coordination
│   ├── narrative-structure.md        # Micro-story framework
│   └── context-adaptation.md         # Platform, a11y, performance
├── patterns/
│   ├── entrance-exit.md              # Entrance/exit recipes
│   ├── state-feedback.md             # Success, error, loading, hover
│   ├── ambient-continuous.md         # Looping, breathing, parallax
│   └── multi-element.md             # Stagger + choreography recipes
└── reference/
    ├── timing-easing-tables.md       # Duration + easing lookups
    ├── property-selection.md         # Property communication guide
    ├── quality-checklist.md          # Evaluation criteria
    └── troubleshooting.md           # Animation smells + fixes
```

## License

MIT
