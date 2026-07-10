---
layout: default
title: "Zombie Stage Rounds — Episode Guide (Round 1 → Round 6)"
description: "Round-by-round episode guide for Zombie Stage: what happens, which songs play, who performs, and when each Round released."
permalink: /rounds/
---

> **Read this on the main wiki:** [https://zombiestage.com/guide/](https://zombiestage.com/guide/)  
> This markdown is the community draft. Corrections here get pulled into the main site.

Zombie Stage is structured as **six Rounds**, mirroring the tournament format of mainline *Alien
Stage* but staged inside an underground zombie-arena run by wealthy non-infected humans. Below is
the current known map of Rounds.

<ul class="grid">
{% assign rounds = site.rounds | sort: "number" %}
{% for r in rounds %}
  <li>
    <a href="{{ r.url }}">{{ r.title }}</a>
    <p>{{ r.summary | default: "TBA" }}</p>
  </li>
{% endfor %}
</ul>

## How Rounds work

Each Round pits zombified performers against each other in a musical match staged for a paying
audience of non-infected humans. Losers are **dismembered** on-stage and their parts auctioned to
"fans" — the AU's most-discussed twist and the reason viewers keep asking whether Zombie Stage is a
horror musical (yes, functionally it is).

## Round 2 release date

There is no official Round 2 date at the time of writing. This page will be updated the moment
VIVINOS confirms one — [watch the schedule](/release-schedule/) or
[star the repo](https://github.com/zombiestageweb/Wiki).

## Related
- [All Songs & Lyrics](/songs/)
- [Characters](/characters/)
- [Timeline vs. mainline Alien Stage](/timeline/)
