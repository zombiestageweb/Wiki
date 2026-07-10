---
layout: default
title: "Zombie Stage Songs & Lyrics — Complete Index"
description: "Complete index of every song in Zombie Stage (Alien Stage AU by VIVINOS). Grouped by Round, with official titles, performers, and lyrics."
permalink: /songs/
---

> **Read this on the main wiki:** [https://zombiestage.com/lyrics/](https://zombiestage.com/lyrics/)  
> This markdown is the community draft. Corrections here get pulled into the main site.

Below is the **complete list of Zombie Stage songs** currently known, grouped by Round. Zombie Stage is the Alien Stage AU by VIVINOS; for mainline ALNST tracks (Sweet Dream, MY CLEMATIS, KARMA, Wiege…) see the [ALIEN STAGE Wiki on Fandom](https://alienstage.fandom.com/wiki/Songs).

<table>
  <thead><tr><th>Song</th><th>Round</th><th>Performer(s)</th><th>Lyrics</th></tr></thead>
  <tbody>
  {% assign songs = site.songs | sort: "round" %}
  {% for s in songs %}
    <tr>
      <td><a href="{{ s.url }}">{{ s.title }}</a></td>
      <td>Round {{ s.round }}</td>
      <td>{{ s.performers | join: ", " }}</td>
      <td>{{ s.lyrics_status | default: "Available" }}</td>
    </tr>
  {% endfor %}
  </tbody>
</table>

## About Zombie Stage songs

Zombie Stage songs are performed in-universe by **zombified idols** forced into an underground arena. Sonically they lean into the horror-carnival tone of the AU — twisted circus motifs, distorted idol-pop, and grotesque staging. Where mainline *Alien Stage* uses songs as emotional character beats, Zombie Stage songs double as **spectacle for the non-infected audience** watching the match.

## Missing a song or lyric?

If a new Round drops or you've transcribed lyrics from an official upload, please
[open a pull request](https://github.com/zombiestageweb/Wiki/tree/main/_songs) —
each song is one Markdown file under `_songs/`.

## Related
- [Rounds (episode guide)](/rounds/)
- [Characters](/characters/)
- [Where to watch Zombie Stage](/watch/)
