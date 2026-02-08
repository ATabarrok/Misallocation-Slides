# Plan: "Price Controls Cause Chaos" Slide Deck

**Date:** 2026-02-08
**Paper:** Albrecht, Tabarrok & Whitmeyer (Feb 2026)
**Status:** AWAITING APPROVAL

---

## Paper Summary

"Price Controls Cause Chaos" develops a general theory of price controls across multiple markets. The key results:

1. **Chaos Theorem**: When prices are frozen, suppliers become indifferent → allocation depends on nuisance parameters → equilibria generically occur at corners → infinitesimal parameter changes cause discontinuous allocation jumps.

2. **Robust Bounds**: A partial-identification framework for welfare bounds that avoids parametric demand extrapolation. Sharp bounds attained by piecewise-linear inverse demands; computation reduces to 1D optimization.

3. **Empirical Application**: 1973–74 U.S. gasoline crisis. Misallocation losses ~1.1–9× the Harberger triangle (station-level); ~0.26–2.38× (state-level).

---

## Available Materials

| Source | Content | Format |
|--------|---------|--------|
| `Paper/Price_Controls Feb 7.pdf` | Full paper (60pp) | PDF/LaTeX |
| `supporting_slides/main_improved.pdf` | Robust bounds methodology (11 slides) | Beamer |
| `supporting_slides/robust_bounds_toy_example.pdf` | Toy example walkthrough (5pp) | LaTeX doc |
| `supporting_slides/Price Controls Cause Chaos.pptx` | Existing presentation | PowerPoint |

---

## Proposed Slide Structure

**Target:** ~45–55 slides for a ~60-minute seminar talk. Beamer format.

### Part I: Motivation & Puzzle (~8 slides)

| # | Slide Title | Content | Key Figure/Element |
|---|-------------|---------|-------------------|
| 1 | Title slide | Authors, affiliations, date | — |
| 2 | The 1974 Gasoline Crisis | "9% national shortfall, but..." quote from Yergin | — |
| 3 | The Patchwork | State-level rationing map (Figure 1 from paper) | Choropleth map |
| 4 | The Puzzle | CT 90%+ rationing, Idaho 0%. Overserved states are the sign of the problem | Highlight extremes |
| 5 | Reframing the Question | Not "why did some states ration?" but "why did others NOT ration?" | — |
| 6 | Standard vs. Actual | Harberger predicts proportional reduction; reality is feast-or-famine | Side-by-side conceptual |
| 7 | This Paper | Three contributions: Chaos Theorem, Robust Bounds, Empirical Application | Roadmap |
| 8 | Roadmap | Section overview | — |

### Part II: Two-Market Example (~8 slides)

| # | Slide Title | Content | Key Figure/Element |
|---|-------------|---------|-------------------|
| 9 | Two-Market Setup | Two submarkets, binding ceiling, total supply Q̄ | Notation |
| 10 | Panel A: Efficient Allocation | Shadow prices equalize, DWL = Harberger triangle | Figure 2 Panel A |
| 11 | Panel B: Corner Allocation | Market 1 gets everything, DWL >> triangle | Figure 2 Panel B |
| 12 | Key Insight | Harberger triangle is the MINIMUM loss, not the average | Emphasis box |
| 13 | The Geometry | Feasible set is a line segment; corners E1, E2 | Figure 3 |
| 14 | Why Corners? | Prices frozen → sellers indifferent → cost minimization → LP → corners | Step-by-step logic |
| 15 | The Knife-Edge | Nearly equal costs → small perturbation flips entire allocation | Intuition |
| 16 | Chaos in Two Markets | Small cost change → discontinuous jump between E1 and E2 | — |

### Part III: General Model (~5 slides)

| # | Slide Title | Content | Key Figure/Element |
|---|-------------|---------|-------------------|
| 17 | General Setup | n submarkets, decomposition, feasible set F as convex polytope | Formal notation |
| 18 | Welfare: Consumer Surplus | W_i(q_i), gross surplus, shadow prices | Definitions |
| 19 | Efficient Allocation | Equalizing shadow prices (Definition 2, Proposition 1) | — |
| 20 | Misallocation DWL | L^Mis definition, integral form, "forgone gains from trade" | Definition 3 |
| 21 | Worst-Case Allocation | Theorem 1: minimum at vertices, cutoff structure | Key result |

### Part IV: The Chaos Theorem (~6 slides)

| # | Slide Title | Content | Key Figure/Element |
|---|-------------|---------|-------------------|
| 22 | Setup for Chaos | Parameter space θ, demand regularity, cost continuity | Assumptions |
| 23 | Without Price Controls | Berge's Maximum Theorem → continuous allocation | Benchmark |
| 24 | Under Price Controls | Cost minimization LP, greedy fill by cost order | Key mechanism |
| 25 | Chaos Theorem (Theorem 2) | Statement: discontinuous jumps between vertices | Formal statement |
| 26 | Chaos Intuition | Pipeline repair, regulatory tweak → supply flips entirely | Plain-language |
| 27 | Simulation: 100 Markets | 10×10 grid, three cost draws | Figure 4 (6-panel) |

### Part V: Robust Bounds Framework (~8 slides)

*Draw heavily from `main_improved.pdf` and `robust_bounds_toy_example.pdf`*

| # | Slide Title | Content | Key Figure/Element |
|---|-------------|---------|-------------------|
| 28 | The Identification Problem | Corner allocations → demand identified only locally → extrapolation problem | Motivation |
| 29 | Our Approach | Partial identification: slope bounds + anchor + choke → sharp bounds | Overview |
| 30 | Step 1: Wedge | Slope bounds create wedge around anchor point | Wedge diagram |
| 31 | Step 2: Band | Invert wedge → pointwise quantity bounds ℓ_i(p) ≤ q_i(p) ≤ u_i(p) | Band diagram |
| 32 | Step 3: Feasible Shadow Prices | Aggregate bands → interval I | L(p), U(p) plot |
| 33 | Step 4: 1D Optimization | Welfare identity → linear in q_i(·) → endpoints dominate | Objective plot |
| 34 | Lemma 1: Heart of the Approach | Infinite-dimensional → 1D scalar optimization | Key result |
| 35 | Theorem 3: Piecewise-Linear Extremals | Sharp bounds attained by PW-linear demands | Sharpness |

### Part VI: Toy Example (Optional, ~3 slides)

| # | Slide Title | Content | Key Figure/Element |
|---|-------------|---------|-------------------|
| 36 | Toy: Setup | Two markets, observed points, slope bounds [-4, -1] | From toy example doc |
| 37 | Toy: Bounds | Φ̄ = 4 (flat), Φ = 1 (steep) | Figure 4 from toy doc |
| 38 | Toy: Lesson | Extremizers are boundary slopes; larger applications need joint optimization | Takeaway |

### Part VII: Empirical Application — 1973–74 Gasoline (~10 slides)

| # | Slide Title | Content | Key Figure/Element |
|---|-------------|---------|-------------------|
| 39 | Historical Context | Nixon price freeze → EPAA → embargo | Timeline |
| 40 | AAA Data | Station-level surveys, Feb 1974: 10% closed, 28% limiting, 62% open | Data description |
| 41 | Welfare Measures | L^Harb, L^Mis, Misallocation Ratio R | Definitions |
| 42 | Station-Level Calibration | Two markets (open vs. closed/limiting), p̄ = 0.8, ε ∈ [0.2, 0.4] | Setup |
| 43 | Demand Curves: No Choke | Higher-loss and lower-loss configurations | Figure 5 |
| 44 | Demand Curves: With Choke | M = 4 disciplines the upper bound | Figure 6 |
| 45 | Station-Level Results | R ∈ [1.13, 9.06] (no choke), upper → 6.23 with choke | **Key result** |
| 46 | Sensitivity to Price Control Depth | Table 1: deeper controls → wider interval | Table |
| 47 | State-Level Bounds | 48 states, adding-up discipline, R ∈ [0.26, 2.38] | Results |
| 48 | State Shadow-Price Map | Choropleth of upper/lower shadow prices | Figure 8 |

### Part VIII: Beyond Geography + Conclusion (~5 slides)

| # | Slide Title | Content | Key Figure/Element |
|---|-------------|---------|-------------------|
| 49 | Misallocation Beyond Geography | Product mix, temporal, input-output | Section 7.6 highlights |
| 50 | The Baby Chicks | Chicken farmers gassed a million chicks; controlled output + uncontrolled input | Striking example |
| 51 | Price Controls → Quantity Controls | Shortage-chaos → political demand for direct quantity management | Political economy |
| 52 | Conclusion | Three bullets: Chaos Theorem, Robust Bounds, Misallocation >> Harberger | Summary |
| 53 | The Broader Lesson | "The main cost is not the familiar triangle, but the hidden misallocation behind it" | Closing quote |

---

## Design Decisions

1. **Format:** Beamer (LaTeX), consistent with paper's LaTeX origin and existing supporting slides
2. **Figures:** Will need to recreate key figures from the paper (Figures 1–8). The paper was produced in LaTeX, so TikZ/pgfplots is the natural choice. Some figures (maps, simulations) may need to be included as pre-generated images.
3. **Mathematical notation:** Keep consistent with paper (P_i, q̄_i, F, W, L^Mis, etc.)
4. **Preamble:** Create a clean Beamer theme. We can draw from `header.tex` in `Preambles/` once created.
5. **Toy example section:** Marked as optional — can be included or dropped depending on audience. Good for a theory seminar; may be skipped for a policy audience.

## Key Figures to Create/Include

| Figure | Source | Method |
|--------|--------|--------|
| State rationing map (Fig 1) | Paper | Include as image (needs data/R script) |
| Two-market efficient vs corner (Fig 2) | Paper | TikZ/pgfplots |
| Feasible set geometry (Fig 3) | Paper | TikZ |
| Simulation grid (Fig 4) | Paper | Include as image (needs R/Python) |
| Station-level demand curves (Fig 5, 6) | Paper | TikZ/pgfplots |
| Shadow price ranges (Fig 7) | Paper | TikZ/pgfplots |
| State shadow-price map (Fig 8) | Paper | Include as image |
| Wedge/band/I diagrams | main_improved.pdf | Recreate in TikZ |
| Toy example plots | robust_bounds_toy_example.pdf | Recreate in TikZ |

## Files to Create

1. `Preambles/header.tex` — Beamer preamble with theme, colors, custom environments
2. `Slides/Price_Controls_Chaos.tex` — Main slide deck
3. `Bibliography_base.bib` — Update with all paper references

## Questions for You

1. **Audience:** Is this for a seminar (economics department), conference, or classroom? This affects depth of theory vs. empirics.
2. **Length:** ~55 slides for a 60-min talk, or shorter?
3. **Toy example:** Include the robust bounds toy example (slides 36–38), or skip for brevity?
4. **Figures:** Should I attempt to recreate figures in TikZ, or should we plan to include them as images extracted from the paper PDF?
5. **PowerPoint slides:** I couldn't read the `.pptx` file. Is there specific content from those slides you want preserved or adapted?
6. **Color scheme / theme:** Any preferences, or should I design something clean and professional?
