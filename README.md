# Hi, I'm Ken Nobak

Building **[FractalCycles](https://fractalcycles.com)**, a platform for detecting statistically validated cycles in financial market data using signal processing and rescaled range analysis.

I started out in data analytics (Excel, SQL, Power BI) and kept pulling the thread until I landed in applied DSP and quantitative methods. FractalCycles is where that path ended up.

---

## What I'm Building

**[FractalCycles](https://fractalcycles.com)** applies classical signal processing to price data:

- **Goertzel DFT** for spectral analysis of individual frequencies
- **Bartels test** for statistical significance of detected cycles
- **Hurst exponent (R/S analysis)** for regime classification (mean-reverting vs trending vs random walk)
- **Composite wave reconstruction** for visualising the dominant cyclical structure

The platform runs across equities, FX, commodities, and crypto. Free tier available.

---

## Open Source

- **[hurst-calculator](https://github.com/Osamwonyi18/hurst-calculator)**: standalone Python implementation of rescaled range analysis for estimating the Hurst exponent. Same methodology used inside FractalCycles, stripped down for clarity.

---

## Technical Stack

**Languages:** Python, TypeScript, SQL
**Backend:** Node.js, Fastify, PostgreSQL, Redis, Prisma
**Frontend:** Next.js 14, React, Tailwind, TanStack Query
**Data:** NumPy, signal processing (Goertzel, FFT, rescaled range)
**Infra:** Docker, Railway, GitHub Actions

## Earlier Data Analytics Work

Before FractalCycles, I completed a data analytics bootcamp with JustIT Training UK. Those projects are still pinned below if you want to see the progression.

---

## Contact

- Website: [fractalcycles.com](https://fractalcycles.com)
- Email: drken18@gmail.com

Open to conversations about quant methods, signal processing applied to markets, or cycle detection generally.
