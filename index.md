---
layout: default
title: "Zombie Stage Wiki — Songs, Rounds, Characters & Lore (Alien Stage AU)"
description: "The open, community-run wiki for Zombie Stage — the Alien Stage (ALNST) alternate universe by VIVINOS. Song lyrics, Round-by-Round episode guide, character profiles, comic translations, and release schedule."
permalink: /
---

**Zombie Stage** is an official **alternate universe** of the *Alien Stage* (ALNST) series by [VIVINOS](https://www.youtube.com/@vivinos), first released in **June 2026**. In this AU the infected cast are forced to perform in an underground, circus-like arena for the entertainment of wealthy, non-infected humans. When performers lose, their body parts are auctioned to “fans.” Round 1 centers on **Mizi** and **Sua**.

This wiki is an **open, fan-run reference** — every page is a Markdown file you can edit on GitHub. If you know something we don't, [send a pull request](/contribute/).

## Start here

<ul class="grid">
  <li><a href="/lore/what-is-zombie-stage/">What is Zombie Stage?</a><p>The premise, tone, and how the AU differs from mainline Alien Stage.</p></li>
  <li><a href="/songs/">All Songs &amp; Lyrics</a><p>Complete index of every Zombie Stage song, grouped by Round and AU.</p></li>
  <li><a href="/rounds/">Rounds (Episodes)</a><p>Round 1 → Round 6 recaps, songs, and characters.</p></li>
  <li><a href="/characters/">Characters</a><p>Mizi, Sua, and the rest of the Zombie Stage cast.</p></li>
  <li><a href="/comics/">Comic &amp; Translations</a><p>Official comic, Patreon, and community English translations.</p></li>
  <li><a href="/watch/">Where to Watch</a><p>Official channels, playlists, and mirrors.</p></li>
  <li><a href="/release-schedule/">Release Schedule</a><p>What's out, what's next, and when to expect Round 2.</p></li>
  <li><a href="/timeline/">AU Timeline</a><p>How Zombie Stage fits alongside mainline Alien Stage events.</p></li>
</ul>

## Latest songs

<ul class="grid">
{% assign songs = site.songs | sort: "round" %}
{% for s in songs %}
  <li><a href="{{ s.url }}">{{ s.title }}</a><p>Round {{ s.round }}{% if s.performers %} · {{ s.performers | join: ", " }}{% endif %}</p></li>
{% endfor %}
</ul>

## About this project

Zombie Stage Wiki is a **static, open-source wiki** hosted on GitHub Pages at
[github.com/zombiestageweb/Wiki](https://github.com/zombiestageweb/Wiki). It exists so fans can find
accurate information quickly — lyrics, character bios, episode recaps — and add what's missing
without waiting on any single moderator.

- **License:** content is CC-BY-SA 4.0; code is MIT.
- **Not affiliated** with VIVINOS or the *Alien Stage* production team.
- Questions or corrections? [Open an issue](https://github.com/zombiestageweb/Wiki/issues/new).
