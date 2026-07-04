# Contributing to the Zombie Stage Wiki

Thanks for wanting to help. This wiki is 100% community-run — every page is a
Markdown file in this repo, and every fix ships as a pull request.

There is a fuller version of this document on the live site at
[/contribute/](https://zombiestage.com/contribute/); this file is the
GitHub-native summary that shows up on the New Issue / New PR screens.

## The one-minute path

1. Open the page you want to fix on [zombiestage.com](https://zombiestage.com).
2. Click **"Edit this page on GitHub"** at the bottom.
3. Make your change in the GitHub web editor.
4. Click **"Commit changes"** — GitHub opens a PR against `main`.
5. A maintainer reviews and merges.

You do not need Git installed. You do not need to run Jekyll locally.

## What we most need help with

- **Verified lyrics** for [Little Bunny](https://zombiestage.com/songs/little-bunny/)
  and [Candy Scar](https://zombiestage.com/songs/candy-scar/), transcribed from
  the official VIVINOS YouTube upload with a timestamp.
- **Round 2+ recaps** — the moment new Rounds drop.
- **Character pages** for the rest of the ALNST cast in their Zombie Stage
  forms (Till, Ivan, Luka, Hyuna, Hyunah…).
- **Comic translation links** — official Patreon source + community English /
  Spanish sets.
- **Fanart and cosplay reference lists** (link only, no re-hosting without the
  artist's permission).

Browse open [`good-first-content`][gfi] issues if you want a starter task.

[gfi]: https://github.com/zombiestageweb/Wiki/labels/good-first-content

## Editorial rules

- **Cite official sources** where possible — VIVINOS' YouTube, Patreon, the
  Alien Stage Fandom wiki.
- **Mark speculation as speculation.** Fan analysis is welcome, but it must
  never be presented as canon. Speculation lives under an explicit
  `## Speculation` heading and is tagged with the `speculation` label on PRs.
- **Respect artists.** Link, don't re-host. Credit every artist you reference.
- **No spoilers in titles** for the current-most Round for the first 7 days
  after its release. Spoiler content inside a page is fine if the page title
  and description do not spoil.
- **Keep it kind.** See our [Code of Conduct](./CODE_OF_CONDUCT.md).

## Repo layout

```
_songs/            Song pages         → /songs/<slug>/
_characters/       Character pages    → /characters/<slug>/
_rounds/           Round recaps       → /rounds/<slug>/
lore/              Explainers         → /lore/<slug>/
comics/, watch/, release-schedule/, timeline/, contribute/
_layouts/          Page templates
assets/            CSS, favicons, OG images
_config.yml        Site config
```

## Page front-matter conventions

Every content page starts with YAML front-matter. Copy an existing file in the
same directory and adjust — do not invent new front-matter keys without
opening a discussion first.

- `layout:` — one of `default`, `page`, `character`, `song`, `round`.
- `title:` — SEO-friendly, ~60 chars, ends with `— Zombie Stage` where useful.
- `description:` — one-line meta description, ~150 chars.
- `updated:` — ISO date (`YYYY-MM-DD`) of the last content update.
- For songs / characters / rounds also include the collection-specific fields
  (`name`, `role`, `number`, `summary`, …) — see existing pages for examples.

## Licensing

By opening a PR you agree that your contribution is dual-licensed:

- **Prose content** — [CC-BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/).
- **Code** (layouts, CSS, config) — MIT, see [LICENSE](./LICENSE).

## Report a problem

[Open an issue.](https://github.com/zombiestageweb/Wiki/issues/new/choose)
For anything sensitive (takedown request, artist credit dispute) see
[SECURITY.md](./SECURITY.md) instead.

## Not affiliated

This wiki is a fan project. It is not affiliated with VIVINOS or the *Alien
Stage* production team.
