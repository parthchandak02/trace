# trace — Strange Attractors in Sumi Ink

Live crypto volatility from CoinGecko drives Lorenz strange attractor parameters. Each coin's price chaos draws a unique butterfly in sumi ink brush strokes on rice paper.

**Visual Style:** Bold — Sumi (ink on rice paper, variable-width brush strokes, vermillion seal accents)

**Data Source:** CoinGecko API (top 10 crypto by market cap, 24h price change % modulates attractor chaos)

**How it works:**
- Tap to cycle through crypto coins
- Each coin's 24h price volatility maps to the Lorenz attractor's rho parameter — more volatile = more chaotic wings
- Particle speed determines brush width (slow = thick stroke, fast = thin stroke)
- Path accumulates on paper with subtle ink bleed fades
- Occasional vermillion stamp dots mark the trajectory
- 3000-frame warmup before visible drawing begins

**Live:** https://parthchandak02.github.io/trace/

**Tech:** Native Canvas 2D, single HTML file, zero dependencies.

---

Part of the [daily generative builds](https://github.com/parthchandak02/parthchandak02#featured-projects) series: [tessellate](https://parthchandak02.github.io/tessellate/) · [flora](https://parthchandak02.github.io/flora/) · [grow](https://parthchandak02.github.io/grow/) · [drift](https://parthchandak02.github.io/drift/) · [trace](https://parthchandak02.github.io/trace/) · [resonate](https://parthchandak02.github.io/resonate/) · [swell](https://parthchandak02.github.io/swell/) · [flux](https://parthchandak02.github.io/flux/)
