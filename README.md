<div align="center">

<img src="./ascii.svg" width="460" alt="Enrico"/>

<img src="./stats.svg" width="620" alt="Contributions in the last year"/>

<!-- no site/socials on the GitHub profile yet — add a line here like:
[site](https://...) &nbsp;·&nbsp; [linkedin](https://...) &nbsp;·&nbsp; [email](mailto:...) -->

</div>

<img src="./hd-about.svg" width="620" alt="about"/>

> Finance tooling and automation. Algorithmic trading systems, market data<br>
> pipelines, and Claude Code skills that turn recurring workflows into repos.

Small, working tools over big unfinished ones — most of what's below shipped<br>
in a day or two and stayed in use. Currently deep in [algotrading-system](https://github.com/enrico1c/algotrading-system),<br>
a live 150 EUR strategy portfolio, and a Qt6 finance dashboard.

<img src="./hd-stack.svg" width="620" alt="stack"/>

<samp>python &nbsp; javascript &nbsp; typescript &nbsp; html &nbsp; css</samp>

<img src="./hd-projects.svg" width="620" alt="projects"/>

**[algotrading-system](https://github.com/enrico1c/algotrading-system)** &nbsp;·&nbsp; <samp>python</samp><br>
Modular algorithmic trading system — RSI2, Triple RSI, VECM pairs — running a<br>
live 150 EUR eToro-compatible portfolio on yfinance data.

**[market-chart](https://github.com/enrico1c/market-chart)** &nbsp;·&nbsp; <samp>javascript</samp><br>
TradingView-style candlestick charting with dual open data sources: Binance<br>
and Kraken for crypto, Yahoo Finance for stocks, forex, and indices.

**[global-trade-monitor](https://github.com/enrico1c/global-trade-monitor)** &nbsp;·&nbsp; <samp>javascript</samp><br>
Interactive global trade route monitor — sea lanes, air routes, disruptions,<br>
alternative routing, and monetary impact — built entirely on free open data.

**[auto-skill-factory](https://github.com/enrico1c/auto-skill-factory)** &nbsp;·&nbsp; <samp>claude code skill</samp><br>
Detects recurring workflows in a session and auto-generates matching Claude<br>
Code skills plus their GitHub repos.

<img src="./hd-stats.svg" width="620" alt="stats"/>

<div align="center">

<img src="./streak.svg" width="620" alt="Current and longest streak"/>

<img src="./langs.svg" width="620" alt="Top languages by bytes and by repo"/>

<img src="./year.svg" width="620" alt="The last year, one character per day"/>

</div>

<img src="./hd-about-this-page.svg" width="620" alt="about this page"/>

Every graphic here is generated, not embedded from anyone else's server.<br>
`ascii.svg` is a photo pushed through a character ramp by<br>
[`scripts/make_portrait.py`](scripts/make_portrait.py); the stat graphics and<br>
these section headings are drawn by [a scheduled action](.github/workflows/stats.yml)<br>
straight from the GitHub GraphQL API, once a day, committing only what changed.

They animate with SMIL inside the SVG, because GitHub strips scripts from<br>
READMEs — and since nothing loads from a third party, nothing here can<br>
rate-limit or go dark. The headings are SVGs for the same reason: GitHub also<br>
strips CSS, so an image is the only way to put this page's own typeface on them.

The typeface is [JetBrains Mono](scripts/fonts), subset to just the characters<br>
each graphic draws and inlined as base64. That isn't only for looks: the<br>
portrait's grid assumes an advance width of exactly 0.600 em, and a viewer whose<br>
default monospace is narrower would otherwise see it squeezed.

Language totals cover public repositories only. `year.svg` uses the portrait's<br>
character ramp: `:` `+` `#` `@`, quiet to loud.
