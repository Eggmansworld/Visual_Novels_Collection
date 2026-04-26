# Adult Visual Novels Preservation Project

> Documenting, organizing, cataloging, and preserving adult visual novels as interactive literature, digital artwork, and software history.

<img width="1619" height="971" alt="Eggmans_Visual_Novel_Collection" src="https://github.com/user-attachments/assets/b72912e8-d32d-4508-b50d-f36b4326cb34" />

---

## Table of Contents

- [Overview](#overview)
- [What Is a Visual Novel?](#what-is-a-visual-novel)
- [A Brief History](#a-brief-history)
- [The Adult Visual Novel Scene](#the-adult-visual-novel-scene)
- [English Translation & Fan Patch Preservation](#english-translation--fan-patch-preservation)
- [Why Preservation Matters](#why-preservation-matters)
- [Major Databases & Community Sources](#major-databases--community-sources)
- [Curated Completed Collection Standard](#curated-completed-collection-standard)
- [Metadata Specification](#metadata-specification)
- [Archival Packaging](#archival-packaging)
- [FAQ](#faq)
- [Sources](#sources)

---

## Overview

This project documents, organizes, and preserves adult visual novels as historically significant born-digital media. The collection treats these works as what they are — interactive literature with artistic, cultural, and software heritage value — applying the same archival standards used across other preservation efforts in this suite.

Each entry in the datfile set is verified, cataloged with structured metadata, and packaged for long-term storage and integrity checking via RomVault-compatible XML dat files.

---

## What Is a Visual Novel?

A visual novel (VN) is a form of interactive fiction originating in Japan that combines static or animated character artwork, background illustrations, written narration, dialogue, music, and sound effects into a reading-driven experience. The genre sits at the intersection of literature, graphic novel, and software — closer to a Choose Your Own Adventure book rendered as a multimedia program than to a conventional video game.

The defining characteristic of a visual novel is its emphasis on story over mechanics. Gameplay, where it exists at all, typically consists of reading through scenes and periodically making choices that determine which narrative route the player follows, which characters they develop relationships with, and which of several possible endings they reach. Some titles are entirely linear — these are called **kinetic novels** — while others feature elaborate branching structures with dozens of mutually exclusive scenes, multiple love interests, hidden true endings, and substantial replay requirements to see all content.

Visually, the medium has a recognizable structure: a text box or dialogue window occupies the lower portion of the screen, character sprites are layered over painted or photographed backgrounds, and special **CG event scenes** — fully rendered illustrations — appear at emotionally or narratively significant moments. A history/backlog function allows players to scroll back through dialogue, and most engines include auto-read and skip-already-read-text modes to support replaying routes efficiently.

Audio is a core component. Most commercial Japanese titles feature full voice acting for non-protagonist characters, original soundtrack compositions, and layered ambient audio. Production values vary enormously, from small one-person hobbyist releases to multi-year commercial productions with budgets comparable to light anime series.

Related genre labels used interchangeably or with slight distinctions include:

| Term | Notes |
|------|-------|
| Novel game | Japanese industry term, often used by developers |
| Adventure game (ADV) | Broader Japanese PC classification; VNs are a subset |
| Eroge | Contraction of *erotic game*; not all eroge are VNs, and not all VNs are eroge |
| Galge | Short for *gal game*; romance-focused VNs with female love interests |
| Otome game | Romance VN with a female protagonist and male love interests |
| Kinetic novel | Linear VN with no meaningful player choice |

---

## A Brief History

### Japanese Origins (1980s–1990s)

The visual novel genre grew from text adventure games on Japanese home computers in the early 1980s. Titles running on the NEC PC-8801 and PC-9801 platforms combined text-heavy adventure gameplay with early character illustrations, and adult content was part of the market from very early on — the relaxed content restrictions of the PC market compared with consoles made these platforms a natural home for eroge. Key early milestones included *Portopia Renzoku Satsujin Jiken* (Enix, 1983) on PC, a genre-defining mystery title, and the later commercial success of *YU-NO: A Girl Who Chants Love at the Bound of this World* (Elf, 1996), widely cited as a technical and narrative landmark.

The 1990s saw the consolidation of the visual novel as a recognizable format, distinct from the earlier point-and-click adventure hybrid structure. Studios such as **Key** (founded 1998), **TYPE-MOON**, **Nitroplus**, and **Leaf** established the template of long-form, route-based storytelling with high-quality illustration and music that would define the commercial peak of the medium. Key's *Kanon* (1999), *Air* (2000), and *Clannad* (2004) are frequently cited as among the best-selling and most critically acclaimed titles of the era.

### Console Ports and Mainstream Crossover (2000s)

As adult content restricted distribution on consoles, many commercial VNs were produced in two versions: an adult PC release (*18+*) and an all-ages console port, typically for the PlayStation 2 or PlayStation Portable, with explicit scenes removed or replaced. This dual-release model became standard practice for larger studios and created one of the key preservation challenges the medium faces today — the adult PC version and the console all-ages version are distinct releases with different content, sometimes different scripts, and sometimes exclusive routes or endings on one platform or the other.

### Global Reach and Ren'Py Era (2010s–Present)

International awareness of Japanese VNs expanded significantly through anime adaptations of titles like *Fate/stay night*, *Clannad*, and *Steins;Gate*, driving English-speaking audiences to seek out the original software. Official English localizations from companies such as MangaGamer, JAST USA, and later Sekai Project and Yen Press increased the availability of legitimate translated releases.

Simultaneously, the open-source **Ren'Py** engine (released 2004, widely adopted through the 2010s) dramatically lowered the barrier to creating original visual novels, producing a large wave of English-language and international VN development. Platforms such as itch.io and later Steam became viable distribution channels for both translated Japanese titles and original Western productions. The Western adult VN market grew substantially through platforms like Patreon and itch.io, where developers could fund ongoing projects directly.

---

## The Adult Visual Novel Scene

Adult content in visual novels spans an enormous range — from brief romantic scenes in otherwise story-focused titles to productions built explicitly around adult content. The genre includes:

- Traditional romance and dating sim structures with adult routes
- Sandbox progression games with stat management and unlockable scenes
- Corruption and transformation narratives
- Fantasy, sci-fi, and horror hybrid settings
- Comedy and parody titles
- Nukige — titles where explicit content is the primary focus rather than a component of a larger story
- RPG/VN hybrids combining overworld exploration with visual novel presentation

Adult content historically served as a direct funding mechanism for smaller studios that could not compete with mainstream game budgets. Many of the most technically and narratively ambitious works in the medium were adult titles — the adult market subsidized production values and development time that all-ages releases of the same scope could not have sustained commercially.

---

## English Translation & Fan Patch Preservation

For the first two decades of the visual novel medium, the vast majority of titles received no official English release. Volunteer translation communities — working from Japanese script dumps, hex editors, and custom tooling — created patches that replaced in-game text with English translations, often also adapting menus, graphics containing Japanese text, and executable code to support Latin character sets.

The output of these communities is itself a significant preservation target. Fan translations represent substantial volunteer labor and scholarship, and many remain the only English-language path to titles that were never commercially localized. Key archival targets for any given title include:

- **Original Japanese release** — the source text and original assets
- **Official English release** — where one exists, including any censored or uncensored variants
- **Fan patch versions** — including intermediate and final releases, which may differ in translation quality, content restoration, or compatibility
- **Translator credits and documentation** — often published on project websites that have since gone offline
- **Installation and compatibility notes** — many patches require specific base versions, regional settings, or locale emulation

Where a title exists in both a censored console port and an uncensored PC original, the fan community sometimes created **restoration patches** applying adult content from the PC version back onto an all-ages release. These are distinct archival items from the standard translation patch.

---

## Why Preservation Matters

Digital media is structurally more fragile than physical media in one specific way: its distribution infrastructure can vanish without warning. A book sitting on a shelf survives its publisher going bankrupt. A digital-only title whose DRM servers go offline, whose storefront delists it, or whose developer website disappears may become unplayable or completely inaccessible.

The visual novel medium faces several compounding risk factors:

- **Storefront delisting** — adult content has been periodically purged from Steam and other platforms, sometimes with little notice and no alternative distribution arrangement
- **Dead file hosts** — patch distribution sites, mirror hosts, and forums that hosted downloads have shut down continuously since the early 2000s
- **Broken DRM** — older titles with custom copy protection may fail on modern operating systems without preservation-level patching
- **Abandoned websites** — developer sites, fan translation project pages, and community wikis that contained version history, changelogs, and installation documentation are routinely lost
- **OS incompatibility** — 16-bit Windows executables, early DirectX dependencies, and Japanese-locale-specific installers create technical barriers that grow over time

Adult VNs face an additional layer of risk: content moderation pressure on hosting platforms has historically led to the removal of adult-content releases without archival copies being made available elsewhere. The commercial and cultural legitimacy afforded to mainstream game preservation is often withheld from adult media, despite the same structural fragility applying equally.

Adult books, pulp fiction, exploitation films, and adult magazines are collected by libraries, universities, and private archives as legitimate historical documents. Adult visual novels warrant identical treatment as born-digital cultural artifacts.

---

## Major Databases & Community Sources

### VNDB (Visual Novel Database)

[vndb.org](https://vndb.org) is the primary structured database for visual novel metadata. It catalogs titles worldwide with entries covering releases by language, platform, and version; staff credits (writers, artists, composers, voice actors); tag taxonomies; character profiles; and relationships between different editions of the same title. VNDB is the reference standard for title identification, release disambiguation, and staff attribution in this collection.

### F95Zone Community Forums

F95Zone maintains one of the largest active communities for tracking Western adult VN development, including update threads, patch notes, mirrors, developer announcements, and community bug reports for thousands of titles. It is a primary source for tracking ongoing releases and version histories for independently developed Western titles.

### Other Community Sources

Archive.org, dedicated fan wikis, subreddits, and Discord servers associated with specific developers or translation projects supplement VNDB and forum tracking for titles with limited mainstream documentation.

---

## Curated Completed Collection Standard

This datfile set applies consistent inclusion criteria to maintain a usable, verified collection.

### Inclusion Criteria

- Core storyline is complete and playable end-to-end
- A stable, publicly released version exists
- The build has been verified as playable
- Metadata has been captured and structured
- The specific version is identified in the dat entry

### Exclusion Criteria

- Tech demos and vertical slices without a complete narrative
- Broken or corrupted uploads
- Incomplete early-access or prototype releases where the story is unfinished
- Placeholder or skeleton releases with no substantive content

---

## Metadata Specification

Each title is documented with the following JSON structure:

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

**Field notes:**

- `censorship` — records whether the release is the uncensored original, a censored variant, or a restored/patched version
- `language` — primary language of the release; fan-translated titles note the translation group where known
- `genre` — drawn from VNDB tag taxonomy where applicable
- `version` — specific version string; critical for patch-dependent titles where multiple releases exist
- `installation` — documents any non-standard setup requirements (locale emulation, base version dependency, engine patches)
- `extra_fields` — catch-all for title-specific metadata not covered by the standard schema

---

## Archival Packaging

Each archived entry follows this workflow:

1. Capture and store JSON + HTML metadata documents
2. Acquire the original release in its native packaging
3. Verify completeness against known file lists or community documentation
4. Repackage into a clean ZIP archive with consistent structure
5. Apply deterministic ZStandard compression
6. Generate CRC32, MD5, and SHA1 hashes for dat file entry

This process ensures archives are reproducible across storage locations, deduplication works reliably across mirrors, and integrity can be verified at any point without requiring the original source to still be online.

---

## FAQ

**What is the difference between a visual novel and an eroge?**
Eroge (*erotic game*) is a broader category covering any Japanese PC game with adult content, including action, RPG, and strategy titles. Visual novels are a subset of eroge when they contain adult content, but not all visual novels are eroge and not all eroge are visual novels.

**What is a kinetic novel?**
A kinetic novel is a VN that does not present the "player" with any choices at all; they simply read through a single unbranching story. The term originates from Visual Art's brand KineticNovel (and all games produced under that brand are examples of this), but it is now also used to describe games by other companies with a similar structure. Examples include *Planetarian: The Reverie of a Little Planet* (Key, 2004). 

**Why preserve fan patches separately from the base game?**
A fan patch applied to a base game may be the only English-language version of a title that will ever exist. The patch itself is a distinct creative and scholarly work. The patcher's version, tools, and documentation have independent historical value and may be lost separately from the base game if not archived.

**Why focus on completed titles?**
Completed titles represent historically stable snapshots. Ongoing "Patreon/Subscribestar/monthly recurring subscription" releases require continuous re-archiving as versions change.  I've come to learn taht keeping up with ongoing releases is a horrendously time consuming task. It is also difficult to automate an automatic "keep latest version" workflow due to the VN authors being able to change their game version styles on a whim without regard to actually understanding how proper versioning works. 

---

## Sources

- Wikipedia: [Visual novel](https://en.wikipedia.org/wiki/Visual_novel)
- Wikipedia: [Eroge](https://en.wikipedia.org/wiki/Eroge)
- VNDB: [vndb.org](https://vndb.org)
- Ren'Py project: [renpy.org](https://renpy.org)

---

## Licensing

Original source code, scripts, tooling, and hand-authored documentation and metadata in this repository are licensed under the **MIT License**.

Archived game data, binaries, firmware, media assets, and other third-party materials are **not** covered by the MIT License and remain the property of their respective copyright holders.

See the `LICENSE` and `NOTICE` files for full details and scope clarification.

---

## Credits

Created for the preservation community by **Eggman**, with Claude's help turning ideas into code and documentation.
