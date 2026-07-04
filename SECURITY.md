# Security & sensitive-content policy

The Zombie Stage Wiki is a static Jekyll site — there is no backend, no user
data, no login. "Security" here mostly means **sensitive-content reports**:
takedowns, artist-credit disputes, doxxing, and the like.

## Reporting

- For a **normal bug** on a wiki page (typo, dead link, wrong lyric):
  open a regular [issue](https://github.com/zombiestageweb/Wiki/issues/new/choose).
- For anything **sensitive or private** — takedown requests, artist credit
  disputes, harassment reports, suspected token/secret leaks in the repo —
  open a **private security advisory**:
  <https://github.com/zombiestageweb/Wiki/security/advisories/new>

Do **not** file sensitive reports as public issues.

## What we will do

- Acknowledge within 7 days.
- If the report is a valid takedown or credit request, we will act within
  another 7 days (usually much faster).
- If the report is a repo-side secret leak, we will rotate/revoke and force
  the affected content out of history.

## Scope

- In scope: content on `zombiestage.com` and files in this repo.
- Out of scope: VIVINOS' own channels, the mainline Alien Stage franchise,
  the Alien Stage Fandom wiki, and any third-party translation site linked
  from here.
