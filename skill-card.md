---
name: heirloom-provenance
description: Capture heirloom stories before the knowers are gone — registry, interview kit, estate reports, QR tags, fair wish-list distribution.
version: 1.0.0
author: Denis Voronin
license: MIT
tags: [heirlooms, family-history, provenance, estate, oral-history]
---

# Heirloom Provenance

**The stories die with their keepers. Capture them first.**

Provenance system for family objects: registry (origin, owner chain,
append-only dated stories, values), interview kit with the 7 core
story-unlocking questions, estate-ready provenance reports for executors
and appraisers, storybook narrative export, printable DO-NOT-DISCARD tags
with QR payload, and distribution fairness — sealed wish-lists, dual-#1
conflict detection before the family meeting, seeded rotation draft with
equalization for value gaps only.

## Quick Start
```bash
python3 scripts/heirloom.py interview "Aunt Maria"
python3 scripts/heirloom.py story append HL001 --text "..." --source "Maria 2026"
python3 scripts/heirloom.py wish add HL001 --by Sam --rank 1
python3 scripts/heirloom.py draft --people Sam,Alex
```

100% local — family data stays in the family.
