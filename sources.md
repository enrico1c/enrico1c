# About this page

The resume content (education, experience, projects, certifications, skills)
is plain hand-written markdown — no script touches it. Only the graphics
below the fold are generated, and every one of them is generated here, not
embedded from anyone else's server: the stat graphics and the section
headings are drawn by [a scheduled action](.github/workflows/stats.yml)
straight from the GitHub GraphQL API, once a day, committing only what
changed.

They animate with SMIL inside the SVG, because GitHub strips scripts from
READMEs — and since nothing loads from a third party, nothing here can
rate-limit or go dark. The headings are SVGs for the same reason: GitHub also
strips CSS, so an image is the only way to put this page's own typeface on
them.

The typeface is [JetBrains Mono](scripts/fonts), subset to just the characters
each graphic draws and inlined as base64. That isn't only for looks: `year.svg`'s
grid assumes an advance width of exactly 0.600 em, and a viewer whose default
monospace is narrower would otherwise see it squeezed.

Language totals cover public repositories only. `year.svg` uses a character
ramp — `:` `+` `#` `@`, quiet to loud — and, once the grid has revealed, a
short trail of the same characters sweeps across it once, column by column.
