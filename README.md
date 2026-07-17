# stl-webinar

GitHub Pages host for the **The Society That Learns** book webinar invite (22 July 2026, 9:00 AM Thailand time).

**Live page:** https://arnans.github.io/stl-webinar/

## This repo is a deploy target, not the source

`index.html` is a renamed **copy** of `society-that-learns-book/webinar-stl.html` from [arnans/paron-principle](https://github.com/arnans/paron-principle), which is the source of truth. This separate repo exists only to give the invite a short, clean URL.

**Do not edit `index.html` here directly** — changes will be overwritten by the next copy from the source repo.

## How to update the live page

1. Edit and push `society-that-learns-book/webinar-stl.html` in `paron-principle`.
2. Copy it into this repo's local clone (`C:\Users\arnan.s\Documents\stl-webinar`) as `index.html`.
3. Commit and push here. GitHub Pages redeploys automatically within a minute or two.
