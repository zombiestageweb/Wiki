---
layout: default
title: "Contribute — Zombie Stage Wiki"
description: "How to add lyrics, characters, and episode information to the Zombie Stage Wiki. Every page is a Markdown file editable on GitHub."
permalink: /contribute/
---

This wiki is 100% community-run. Every page is a **Markdown file** in the
[`zombiestageweb/Wiki`](https://github.com/zombiestageweb/Wiki) repo. You do not need to know Git —
GitHub's web UI lets you edit any file, and it will open a pull request for you automatically.

## The one-minute path

1. Open the page you want to fix.
2. Click **"Edit this page on GitHub"** at the bottom.
3. Make your change.
4. Click **"Commit changes"** — GitHub opens a PR against `main`.
5. A maintainer reviews and merges. Done.

## What we most need help with

- **Verified lyrics** for [Little Bunny](/songs/little-bunny/) and [Candy Scar](/songs/candy-scar/), sourced from the official YouTube upload.
- **Round 2+ recaps** the moment new Rounds drop.
- **Character pages** for the rest of the ALNST cast in their Zombie Stage forms (Till, Ivan, Luka, Hyuna, Hyunah…).
- **Comic translation links** — official Patreon source + community English / Spanish sets.
- **Fanart and cosplay reference lists** (link only, no re-hosting without artist permission).

## Editorial rules

- **Cite official sources** where possible — VIVINOS' YouTube, Patreon, Alien Stage Fandom.
- **Mark speculation as speculation.** Fan analysis is welcome; do not present it as canon.
- **Respect artists.** Link, don't re-host. Credit every artist you reference.
- **No spoilers in titles** for the current-most Round for the first 7 days after its release.
- **License:** contributions are CC-BY-SA 4.0 for prose, MIT for code.

## Directory layout

```
_songs/            Song pages         → /songs/<slug>/
_characters/       Character pages    → /characters/<slug>/
_rounds/           Round recaps       → /rounds/<slug>/
lore/              Explainers         → /lore/<slug>/
comics/, watch/, release-schedule/, timeline/, contribute/
_layouts/          Page templates
_config.yml        Site config
```

## Report a problem

Open an issue: [github.com/zombiestageweb/Wiki/issues/new](https://github.com/zombiestageweb/Wiki/issues/new).
