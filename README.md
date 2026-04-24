# Adult Visual Novels Preservation Project

> Documenting, organizing, cataloging, and preserving adult visual novels as interactive literature, digital artwork, and software history.

---

# Table of Contents

- [Overview](#overview)
- [What Is a Visual Novel?](#what-is-a-visual-novel)
- [Structural Elements of Visual Novels](#structural-elements-of-visual-novels)
- [Japanese Origins and Global Growth](#japanese-origins-and-global-growth)
- [Adult Visual Novel Scene](#adult-visual-novel-scene)
- [English Translation & Fan Patch Preservation](#english-translation--fan-patch-preservation)
- [Why Preservation Matters](#why-preservation-matters)
- [Major Databases & Community Sources](#major-databases--community-sources)
- [Curated Completed Collection Standard](#curated-completed-collection-standard)
- [Metadata Specification](#metadata-specification)
- [Archival Packaging](#archival-packaging)
- [FAQ](#faq)
- [Sources](#sources)

---

# Overview

Visual novels (VNs) are narrative-focused digital games that combine text, artwork, music, and user interaction. Originating primarily in Japan, the medium later expanded globally.

A substantial portion of the historical market included adult content. These works often blend explicit scenes with long-form storytelling, route-based narratives, roleplaying systems, and detailed illustration.

---

# What Is a Visual Novel?

A visual novel usually emphasizes:

- Story over mechanical gameplay
- Reading-based progression
- Character relationships
- Choice-driven branching
- Multiple endings
- Audio-visual presentation
- Save/load route experimentation

Related labels may include:

- Novel game
- Adventure game (ADV)
- Eroge
- Galge
- Kinetic novel

Source: Wikipedia Visual Novel article.

---

# Structural Elements of Visual Novels

## Text Engine

- Dialogue windows
- Narration boxes
- History/backlog logs
- Auto-read mode
- Skip read text

## Character Presentation

- Layered sprites
- Facial expressions
- Outfit changes
- Pose variants

## Background Art

- Schools
- Homes
- Offices
- Streets
- Fantasy or sci-fi environments

## CG Event Scenes

Used for major emotional, romantic, dramatic, or adult scenes.

## Audio Layer

- Background music
- Voice acting
- Ambient audio
- Sound effects

## Route Structure

Choices may determine:

- Character routes
- Good/bad endings
- Hidden scenes
- True endings

---

# Japanese Origins and Global Growth

Visual novels became strongly associated with Japanese PC gaming during the 1990s. Lower production costs compared with large action titles allowed many studios to produce story-heavy works quickly.

Global growth later accelerated through:

- Anime adaptations
- Console ports
- Steam releases
- Fan translations
- Ren'Py and other accessible engines
- Original English-language VNs

Source: Wikipedia.

---

# Adult Visual Novel Scene

Adult visual novels range from small romance titles to large productions with hundreds of thousands of words.

Common formats:

- Dating sims
- Sandbox progression games
- Corruption stories
- Fantasy romance
- Mystery / horror hybrids
- RPG/VN hybrids
- Comedy parody titles

Adult content historically functioned as a viable funding model for smaller studios.

---

# English Translation & Fan Patch Preservation

For many years, numerous Japanese visual novels had no official English releases.

Volunteer translators expanded the audience by creating:

- English script patches
- UI translations
- Repacked installers
- Compatibility fixes
- Restoration patches
- Documentation

These communities helped preserve titles that otherwise remained inaccessible outside Japan.

Important archival targets:

- Original Japanese release
- Official English release
- Fan patch versions
- Translator credits
- Installation notes

Sources: Wikipedia, VNDB community references.

---

# Why Preservation Matters

Digital-only media is fragile.

Common loss events:

- Dead file hosts
- Deleted storefront pages
- Lost patches
- Broken DRM
- Unsupported operating systems
- Abandoned websites

Adult books, magazines, VHS media, and pulp fiction are already collected historically. Adult visual novels merit the same archival treatment as born-digital media.

---

# Major Databases & Community Sources

## VNDB

Useful for:

- Releases
- Languages
- Staff credits
- Tags
- Platforms
- Relationships between editions

## Community Forums / Release Trackers

Communities often track:

- Updates
- Patch notes
- Mirrors
- Bug reports
- Developer announcements

Together these sources document tens of thousands of titles worldwide.

---

# Curated Completed Collection Standard

## Inclusion Criteria

- Completed core storyline
- Stable public version
- Verified playable build
- Metadata captured
- Version identified

## Exclusion Criteria

- Tech demos
- Broken uploads
- Incomplete prototypes
- Placeholder releases

---

# Metadata Specification

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
```
---

# Archival Packaging

1. Store JSON + HTML metadata
2. Acquire original release
3. Verify completeness
4. Repackage into ZIP
5. Apply deterministic ZStandard compression
6. Generate hashes

Benefits:

- Reproducible archives
- Easier deduplication
- Reliable mirrors
- Integrity verification

---

# FAQ

## What is a kinetic novel?

A linear VN with little or no player choice.

## Why multiple endings?

Replayability and route depth are core genre traditions.

## Why preserve fan patches?

They may be the only path to accessibility for non-Japanese audiences.

## Why archive completed titles?

They provide historically stable snapshots.

---

# Sources

- Wikipedia: Visual Novel article  
- VNDB informational pages / FAQ resources

---

# Final Statement

Visual novels are a fusion of literature, illustration, music, software, and player agency. Preserving adult visual novels alongside their translations, metadata, versions, and community history protects an important part of digital culture.

## Licensing

Original source code, scripts, tooling, and hand-authored documentation and
metadata in this repository are licensed under the MIT License.

Archived game data, binaries, firmware, media assets, and other third-party
materials are **not** covered by the MIT License and remain the property of
their respective copyright holders.

See the `LICENSE` and `NOTICE` files for full details and scope clarification.

---

## CREDITS

Created for the preservation community by Eggman, with Claude’s help turning ideas into code.