# MATTBEAR PROJECT SYSTEM vCHAOS™

Shared source-of-truth template for MBK and all connected MATTBEAR ecosystem projects.

## Core Philosophy

```text
FAST > PERFECT
WORKING > CLEAN
PLAYABLE > IMPRESSIVE
MODULAR > FRAGILE
CHAOS → SIGNAL
DO NOT BREAK THE FUN
```

Primary quality metric:

```text
FUN
FAST
UNDERSTANDABLE
DOESN'T FIGHT THE USER
```

## Default Structure

```text
/ROOT
├── index.html
├── README.md
├── manifest.json
├── sw.js
├── /LIVE
├── /WILD
├── /FIX
├── /PATCHES
├── /CORE
├── /SYSTEM
├── /ASSETS
├── /SOURCES
├── /SCRAPBOOK
├── /DOCS
├── /BACKUPS
└── /TRASH
```

## Folder Rules

- `/LIVE` = stable public build. Must remain usable.
- `/WILD` = experimental chaos lab. Can break.
- `/FIX` = temporary repairs.
- `/PATCHES` = isolated hotfixes before merging into CORE.
- `/CORE` = protected foundational systems.
- `/SYSTEM` = reusable utilities.
- `/ASSETS` = production-ready files only.
- `/SOURCES` = reference material. Never auto-loaded into runtime.
- `/SCRAPBOOK` = screenshots, mockups, weird discoveries.
- `/DOCS` = roadmap, changelog, maintenance, known chaos.
- `/BACKUPS` = rollback protection.
- `/TRASH` = soft-delete holding area.

## Visual Language

Approved direction:

- neon cyan/pink/green
- blueprint grids
- CRT scanlines
- industrial UI
- rainy cyber-diner atmosphere
- tactile interfaces
- chunky controls
- large readable typography
- organized chaos

Avoid:

- sterile SaaS styling
- generic casino visuals
- tiny controls
- overloaded menus
- fake corporate minimalism

## Mobile-First Rules

Every project must prioritize:

- touch responsiveness
- low scroll
- large controls
- immediate feedback
- fast startup
- audio unlock handling
- mobile-safe performance

## Audio Rules

```text
ONE LOOP PER PAD
GLOBAL CHOKE OPTIONAL
NO DOUBLE LOADING
QUANTIZE DEFAULT
RECORDING REPLACES DEMO LOOP
```

Requirements:

- pre-normalized samples
- short attack sounds
- mobile-safe volume
- centralized choke logic
- quantized triggering where applicable
- fallback audio behavior

## Play Mode vs Edit Mode

Projects should support:

```text
?mode=play
?mode=edit
```

Play mode is viewer-safe, clean, and simple.

Edit mode may include upload tools, diagnostics, meters, stress testing, patch controls, and debugging tools.

## Maintenance Workflow

Before push:

```text
[ ] Syntax check
[ ] Mobile check
[ ] Audio duplication scan
[ ] Asset path check
[ ] Touch latency check
[ ] Volume normalization
[ ] Visual alignment scan
[ ] Dead button scan
[ ] README updated
[ ] Version incremented
[ ] Live test verified
```

## Safe Push Standard

A build is safe to push if:

```text
Audio works
Buttons work
Mobile works
Nothing explodes
```

Not required:

- perfection
- enterprise architecture
- over-optimization

## Failure Recovery

Major projects should eventually support:

```text
/recover.html
```

Recovery page responsibilities:

- clear cache
- restore backups
- bypass broken UI
- emergency navigation
- reset audio systems

## Versioning

```text
v1.0.0 = first stable
v1.0.X = fixes
v1.X.0 = major feature branch
```

WILD builds may remain rough. LIVE builds must remain usable.

## README Standard

Every repo README should explain:

1. What the project is
2. How to start using it immediately
3. Core controls
4. Mobile behavior
5. Known issues if relevant

## Cross-Project Application

These rules apply retroactively and going forward across the MATTBEAR ecosystem.

Retroactive targets:

- MBK
- MATTMACHINE
- HiberNation
- WORD$LOTS
- SPELL$LOTS
- MATTBEARCADE
- Future experimental repos
- Creative landing pages
- Interactive music systems

Legacy repo upgrade priority:

1. Mobile responsiveness
2. Audio duplication/choke fixes
3. README clarification
4. Visual consistency
5. Asset cleanup
6. Recovery/fallback systems
7. Admin/edit separation
8. Ecosystem linking

Unless explicitly overridden:

```text
All new MATTBEAR projects are assumed to belong to the connected ecosystem.
```

## Final Rule

Never optimize the personality out of the project.
