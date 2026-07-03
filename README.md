# Zombie Stage Wiki

Open, community-curated wiki for **Zombie Stage** — the *Alien Stage* (ALNST) alternate universe
by [VIVINOS](https://www.youtube.com/@vivinos).

Live site: **https://zombiestage.com**

## What's here

- Song lyrics and meaning pages (Little Bunny, Candy Scar, …)
- Round-by-Round episode recaps (Round 1 → 6)
- Character profiles (Mizi, Sua, and the rest of the cast)
- "What is Zombie Stage?" explainer + AU timeline
- Official comic / where-to-watch / release schedule
- Contribution guide for fans

## Stack

- [Jekyll](https://jekyllrb.com/) + GitHub Pages (native, zero-CI build).
- `minima` base theme, overridden via `_layouts/` and `assets/style.css`.
- `jekyll-seo-tag` + `jekyll-sitemap` + `jekyll-feed` + `jekyll-redirect-from`.
- `Schema.org` JSON-LD baked into every layout.

## Local preview

```bash
bundle install
bundle exec jekyll serve
# open http://localhost:4000
```

## Contribute

Every page is a Markdown file. Open the page on the live site, click
**"Edit this page on GitHub"** at the bottom, and GitHub will open a PR for you.

See [/contribute/](https://zombiestage.com/contribute/) for editorial rules.

## License

- Prose content: CC-BY-SA 4.0.
- Code (layouts, CSS, config): MIT — see [LICENSE](LICENSE).
- Not affiliated with VIVINOS or the *Alien Stage* production team.
