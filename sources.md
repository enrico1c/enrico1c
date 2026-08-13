# About this page

Every graphic here is generated, not embedded from anyone else's server.
`ascii.svg` is a photo pushed through a character ramp by
[`scripts/make_portrait.py`](scripts/make_portrait.py); the stat graphics and
these section headings are drawn by [a scheduled action](.github/workflows/stats.yml)
straight from the GitHub GraphQL API, once a day, committing only what changed.

They animate with SMIL inside the SVG, because GitHub strips scripts from
READMEs — and since nothing loads from a third party, nothing here can
rate-limit or go dark. The headings are SVGs for the same reason: GitHub also
strips CSS, so an image is the only way to put this page's own typeface on them.

The typeface is [JetBrains Mono](scripts/fonts), subset to just the characters
each graphic draws and inlined as base64. That isn't only for looks: the
portrait's grid assumes an advance width of exactly 0.600 em, and a viewer whose
default monospace is narrower would otherwise see it squeezed.

Language totals cover public repositories only. `year.svg` uses the portrait's
character ramp: `:` `+` `#` `@`, quiet to loud.
