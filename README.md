# 🪐 The Ephemeris of One Human Life

**What is a single human life worth?** Economists, courts, health systems, ecologists, philosophers, and astrologers all have an answer, and they don't agree.

This project takes one average life in 2026 (73.3 years, the world average) and weighs it through nine different value systems. The results range from **$5** to **"beyond price."**

### 👉 [View the live page](https://pachinkodealer.github.io/value-of-a-life)

---

## What's inside

**The life wheel.** A 73.3-year life drawn as one orbit and split into the twelve astrological houses, about 6.1 years each. Two curves are overlaid: paid economic output and care given to others, plotted by age. The outer ring marks real planetary return cycles. Tap any house or planet for details.

**What is one life worth?** A log-scale comparison of nine valuation methods:

| Lens | Estimate | What it measures |
|---|---|---|
| Chemical elements | ~$5 | Raw materials of the body |
| Lifetime carbon cost | ~ −$65k | Climate damage from ~340 t CO₂ |
| Global human capital | ~$600k | Lifetime earnings at world average income |
| US lifetime earnings | ~$1.7M | Median American career total |
| Compensation funds | ~$2M | 9/11 fund and wrongful-death awards |
| UK health threshold | ~$2.5M | QALY threshold × lifespan |
| Australian VSL | A$5.87M | Willingness to pay to reduce fatal risk |
| US DOT VSL | $13.2M | Federal value of a statistical life |
| Kant & most religions | Beyond price | Dignity has no equivalent |

**The lifetime ledger.** What a life draws down (food, carbon, water, care received) set against what it gives back (work, unpaid care, children, relationships, knowledge).

**The lenses.** Eight frameworks for valuing a life, each answering a different question.

**Planetary returns.** A timeline of Jupiter, Saturn, lunar node, and Uranus cycles across an average lifespan.

## Why the numbers disagree

None of these estimates is "the" value of a life. Each one answers a different question:

- **The value of a statistical life (VSL)** is not the price of any particular person. It is what society will pay for tiny reductions in risk, spread across millions of people.
- **Human capital** measures earnings. Its gap between countries reflects where someone was born, not what they are worth.
- **Dignity-based ethics** treats every number on the page as a category error.

The spread between these answers is the point of the project.

## A note on the astrology

The orbital periods are real astronomy: Jupiter takes 11.86 years, Saturn 29.46, the lunar nodes 18.6, and Uranus 84. The meanings attached to them are astrology, a symbolic language rather than a predictive science. They are included as a way of reading time, not as evidence.

## Sources & assumptions

- Life expectancy 73.3 years: [UN World Population Prospects 2024](https://population.un.org/wpp/)
- US VSL of $13.2M (2023$): [US Department of Transportation](https://www.transportation.gov/regulations/economic-values-used-in-analysis)
- Australian VSL of A$5.87M and VSLY of A$253k (2025$): [Office of Impact Analysis](https://oia.pmc.gov.au/resources/guidance-assessing-impacts/value-statistical-life)
- Social cost of carbon of ~$190/t: [EPA 2023 estimate](https://www.epa.gov/environmental-economics/scghg)
- Carbon emissions of ~4.7 t CO₂ per person per year, a global average

Other figures (earnings, care hours, consumption) are rounded world averages. They are meant to show scale, not to be precise.

## Tech

A single self-contained `index.html` with inline SVG, vanilla JavaScript, and no build step or dependencies. It supports light and dark themes, is keyboard accessible, and is responsive down to mobile.

To run it locally, just open `index.html` in a browser.

## Roadmap

- [ ] Interactive Streamlit version with adjustable assumptions (life expectancy, VSL, carbon price, country)
- [ ] Country-by-country comparison of the valuations

---

**Ian Lee** · [LinkedIn](https://linkedin.com/in/ian-lee-career) · [GitHub](https://github.com/pachinkodealer)

*Built with assistance from Claude (Anthropic).*
