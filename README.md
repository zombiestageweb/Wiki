# Zombie Stage Wiki

> **Read the wiki:** https://zombiestage.com
> **Contribute:** open a Pull Request in this repo, or start a [Discussion](https://github.com/zombiestageweb/Wiki/discussions).

Open, community-curated reference for **Zombie Stage** — the *Alien Stage* (ALNST) alternate
universe by [VIVINOS](https://www.youtube.com/@vivinos).

[![Main site](https://img.shields.io/badge/read-zombiestage.com-e63946?style=flat-square)](https://zombiestage.com)
[![Discussions](https://img.shields.io/github/discussions/zombiestageweb/Wiki?style=flat-square)](https://github.com/zombiestageweb/Wiki/discussions)
[![Issues](https://img.shields.io/github/issues/zombiestageweb/Wiki?style=flat-square)](https://github.com/zombiestageweb/Wiki/issues)
[![Content license: CC BY-SA 4.0](https://img.shields.io/badge/content-CC%20BY--SA%204.0-brightgreen?style=flat-square)](https://creativecommons.org/licenses/by-sa/4.0/)

---

## What this repo is (and isn't)

This repo is the **community workshop** behind zombiestage.com:

- **Read the finished pages** on **[zombiestage.com](https://zombiestage.com)** — lyrics, character profiles, guides, timeline, quiz, tools.
- **This repo** is where fans propose corrections, add translations, verify lyrics against the official YouTube uploads, and drop new lore. Merged PRs get pulled to the main site.

If you just want to *read*, go to the main site. If you want to *fix a typo, add a translation, or transcribe a Korean line*, you're in the right place.

## Ways to contribute

| I want to… | Do this |
|---|---|
| Report a wrong lyric line | Open an [Issue](https://github.com/zombiestageweb/Wiki/issues/new/choose) with the YouTube timestamp |
| Add or correct a character page | Open a Pull Request against `_characters/<name>.md` |
| Add a translation of the comic / a song | PR into `comics/` or `_songs/` |
| Ask a lore question | Start a [Discussion](https://github.com/zombiestageweb/Wiki/discussions) |
| Track when Round 2 drops | Watch [Issue #9](https://github.com/zombiestageweb/Wiki/issues/9) |

Full editorial rules: **[CONTRIBUTING.md](CONTRIBUTING.md)**.
Community rules: **[CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md)**.

## Content areas

- **Songs / Lyrics** — `_songs/*.md` → publishes to `zombiestage.com/lyrics/…`
- **Characters** — `_characters/*.md` → publishes to `zombiestage.com/characters/…`
- **Rounds & Recaps** — `_rounds/*.md` → publishes to `zombiestage.com/guide/round-N-recap/`
- **Lore & Explainers** — `lore/`, `timeline/`, `comics/` → publishes to `zombiestage.com/guide/…`

Every markdown file in this repo carries the target main-site URL at the top, so contributors always know where their work will land.

## Licensing

- **Prose content** — [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/).
- **Code** (layouts, CSS, config) — [MIT](LICENSE).
- **Not affiliated** with VIVINOS or the *Alien Stage* production team. Character names,
  song titles, and story elements are the property of their respective owners; we cover them
  under fair use for commentary and reference.

## Local preview (optional)

```bash
bundle install
bundle exec jekyll serve
# open http://localhost:4000
```

The Jekyll build here is a **contributor preview only** — the live wiki at zombiestage.com uses a separate front-end.

## Maintainers

- [@zombiestageweb](https://github.com/zombiestageweb)

Questions we can't answer in an Issue? [`SECURITY.md`](SECURITY.md) for security reports, otherwise open a Discussion.
