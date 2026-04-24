# Adult Visual Novels Preservation Project

> Documenting, organizing, and preserving adult visual novels as legitimate digital media, interactive storytelling, and historical artwork.

---

## Table of Contents

- [Overview](#overview)
- [What Is a Visual Novel?](#what-is-a-visual-novel)
- [The Adult Visual Novel Scene](#the-adult-visual-novel-scene)
- [Common Themes and Content Categories](#common-themes-and-content-categories)
- [Why Adult Visual Novels Matter](#why-adult-visual-novels-matter)
- [Why Preservation Is Important](#why-preservation-is-important)
- [Major Community Databases](#major-community-databases)
- [Curated Completed Collection Concept](#curated-completed-collection-concept)
- [Metadata Standards](#metadata-standards)
- [Archival Packaging Standards](#archival-packaging-standards)
- [Long-Term Goals](#long-term-goals)

---

# Overview

Visual novels are one of the largest yet most under-preserved forms of digital entertainment. They combine written narrative, music, character art, animation, user interaction, and branching story paths into a single interactive medium.

Adult visual novels represent a major subculture within that space. Thousands of titles have been created globally by independent developers, studios, hobbyists, and translation groups. Many are distributed digitally only, updated frequently, removed without notice, or lost when websites disappear.

This project proposes a curated preservation effort focused on **completed adult visual novels**, archived in standardized formats with rich metadata.

---

# What Is a Visual Novel?

A visual novel (VN) is an interactive narrative game built primarily around:

## Core Components

- Written story text
- Character dialogue
- Background artwork
- Character sprites
- CG scenes (event illustrations)
- Music / ambient audio
- Sound effects
- Branching choices
- Multiple endings
- Route progression systems
- Save/load systems

## Common Technical Formats

- Windows executable engines
- Ren'Py
- RPG Maker hybrids
- Unity
- HTML5 / Web builds
- TyranoBuilder
- Custom engines

## Typical User Experience

The player reads story text while advancing scenes, making decisions that alter character relationships, routes, endings, and unlockable content.

---

# The Adult Visual Novel Scene

Adult visual novels include erotic or explicit material alongside narrative gameplay. Many titles range from simple dating sims to lengthy story-driven experiences with hundreds of thousands of words.

## Major Subcategories

- Dating simulators
- Sandbox progression games
- Kinetic novels (no choices)
- Choice-driven romance stories
- RPG/VN hybrids
- Corruption stories
- Transformation narratives
- Sci-fi / fantasy adult fiction
- Psychological drama
- Comedy / parody

## Production Scale

Adult VNs may be created by:

- Solo developers
- Indie teams
- Commercial studios
- Patreon-funded creators
- Crowdfunded projects
- Regional publishers
- Translation communities

Some projects take years to complete and receive dozens of public builds before final release.

---

# Common Themes and Content Categories

Like books, cinema, comics, and games, adult VNs cover a wide spectrum of themes.

## Narrative Subjects

- Romance
- Betrayal
- Family drama
- Power dynamics
- Adventure
- Mystery
- Horror
- Science fiction
- Slice of life
- Fantasy worlds

## Fetish / Niche Markets

The medium often serves niche audiences overlooked by mainstream publishing.

Examples include:

- Monster girls
- Mind control fiction
- Transformation
- Corruption arcs
- Alternate realities
- Dominance/submission fiction
- Gender transformation
- Pregnancy fiction
- Creature fantasy
- Extreme parody scenarios

## Taboo Fiction

Some titles deliberately explore taboo subjects in fictional settings. As with literature and film, this can include controversial or boundary-pushing material intended for fantasy, shock, satire, or psychological exploration.

Preservation does **not** imply endorsement. It recognizes historical existence, market trends, and media scholarship.

---

# Why Adult Visual Novels Matter

Adult VNs are often dismissed due to sexual content, yet they can contain:

- Strong writing
- Complex branching narratives
- Original music
- Detailed illustration
- Experimental storytelling
- Independent artistic voices
- Cultural attitudes of their era
- Fan translation history
- Emerging game engine trends

Many developers use adult content as a funding model to support ambitious storytelling projects.

---

# Why Preservation Is Important

Digital media disappears quickly.

## Risks of Loss

- Dead download links
- Removed storefront pages
- Patreon shutdowns
- DMCA removals
- Lost patches
- Engine incompatibility
- Translation project abandonment
- Broken update chains
- Website closures
- Region locks

## Historical Value

Adult books, magazines, pulp novels, underground comics, VHS media, and print erotica are widely collected by archivists and researchers. Adult visual novels deserve equal consideration as born-digital cultural artifacts.

They reflect:

- Changing technology
- Online creator economies
- Independent publishing models
- International fan communities
- Artistic trends
- Social boundaries in fiction

---

# Major Community Databases

## F95Zone

A major community forum focused on adult games, modding, updates, developer threads, user feedback, and release tracking.

Used for:

- Development threads
- Patch notes
- Mirrors
- User bug reports
- Discovery of new indie projects

## VNDB

The Visual Novel Database is one of the most important cataloging resources for the broader VN medium.

Used for:

- Title indexing
- Staff credits
- Release variants
- Tags
- Platform support
- Language releases
- Character metadata

Together, community hubs like these document **tens of thousands** of visual novels worldwide.

---

# Curated Completed Collection Concept

A preservation-first collection should prioritize:

## Inclusion Rules

- Completed main story
- Publicly released final build
- Stable downloadable package
- Verified installability
- Clean file integrity checks
- Version identified
- Metadata captured

## Exclusion Rules

- Tech demos
- Abandoned early access titles
- Broken builds
- Missing essential files
- Placeholder scam releases
- Incomplete prototypes

## Standardization Goals

Every title should be normalized for archival consistency.

---

# Metadata Standards

Each archived title includes machine-readable metadata in HTML + JSON formats.

## Required Fields

```json
{
  "title": "",
  "thread_url": "",
  "source_url": "",
  "metadata": {},
  "overview": "",
  "developer": "",
  "platform": "",
  "censorship": "",
  "version": "",
  "language": "",
  "genre": [],
  "installation": "",
  "changelog": "",
  "extra_fields": {},
  "thread_updated": "",
  "release_date": "",
  "developer_notes": "",
  "download_links": []
}

## Licensing

Original source code, scripts, tooling, and hand-authored documentation and
metadata in this repository are licensed under the MIT License.

Archived game data, binaries, firmware, media assets, and other third-party
materials are **not** covered by the MIT License and remain the property of
their respective copyright holders.

See the `LICENSE` and `NOTICE` files for full details and scope clarification.

---

## CREDITS

Created for the Visual Novel preservation community by Eggman, with Claude’s help turning ideas into code.

---