---
layout: default
title: "Zombie Stage Characters — Full Cast List"
description: "Every character in Zombie Stage (Alien Stage AU by VIVINOS). Mizi, Sua, and the rest of the zombified cast."
permalink: /characters/
---

Zombie Stage reuses the mainline *Alien Stage* cast but reimagines them inside the zombie-arena AU.
Below is the current cast map — expect it to grow as later Rounds drop.

<ul class="grid">
{% assign chars = site.characters | sort: "name" %}
{% for c in chars %}
  <li>
    <a href="{{ c.url }}">{{ c.title }}</a>
    <p>{{ c.role | default: "" }}</p>
  </li>
{% endfor %}
</ul>

## About the cast

In mainline *Alien Stage*, humans are prey to alien conquerors. In **Zombie Stage** the threat is
inverted: humans have turned into zombies, and the *non-infected* minority run the show. The core
emotional beats — Mizi & Sua, Till & Ivan, Hyuna, Luka — carry over, but each character's arc is
rewritten around commodification: their bodies, their voices, their remains.

## Related
- [What is Zombie Stage?](/lore/what-is-zombie-stage/)
- [Rounds](/rounds/) · [Songs](/songs/)
