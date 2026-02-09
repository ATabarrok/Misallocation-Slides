# Review: "Price Controls Cause Chaos.pptx"

**Reviewer:** Claude Code
**Date:** 2026-02-09
**File:** `Slides/Price Controls Cause Chaos.pptx` (31 slides, 7.0 MB)
**Slide Dimensions:** 13.3" × 7.5" (widescreen)

---

## Executive Summary

The deck presents a compelling argument about the misallocation costs of price controls, grounded in the Albrecht, Tabarrok & Whitmeyer (2026) paper. The core narrative—moving from Harberger triangles to corner solutions to chaos—is strong. However, the presentation has several issues that undermine its effectiveness: **6 nearly empty slides** that appear to be placeholders, **spelling/factual errors**, **inconsistent typography**, **text-heavy slides** that risk losing the audience, and a **missing section on robust bounds** (contribution #3 of the four advertised contributions). Below is a detailed slide-by-slide analysis.

---

## I. Errors & Typos

### Factual/Spelling Errors

| Slide | Issue | Severity |
|-------|-------|----------|
| **8** | "**Glaser** and Luttmer (2003)" — should be "**Glaeser** and Luttmer (2003)" | **High** — misspelling a prominent economist's name |
| **8** | "Bulow and Klemperer study when random allocation **result** in large misallocation" — subject-verb disagreement; should be "**results**" | Medium |
| **23** | "August 1971: Nixon freezes all wages and prices**/**" — trailing slash instead of period | Low |
| **14** | Speaker notes: "When **prizes** are frozen" — should be "**prices**" | Medium (affects delivery if reading notes) |
| **24** | Speaker notes: "6,1m stations" — likely should be "6,100 stations" or "6.1k stations"; also "qasoline" should be "gasoline" | Medium |
| **27** | "Similar story with cows, and pigs. Cull now when future price**<**current price." — raw `<` symbol; needs proper formatting or wording | Low |
| **27** | "Small cost wedges**->**vertex" — inconsistent arrow notation; elsewhere uses "→" | Low |

### Missing Attribution

| Slide | Issue |
|-------|-------|
| **2** | The Yergin quote lacks a citation (the Beamer version correctly attributes it to Yergin 1991). The book cover image of "The Prize" is shown but no source credit. |
| **26** | "1973 Congressional testimony" quote lacks specific attribution (which committee? which witness?) |

---

## II. Structural Issues

### Title-Only Section Headers

Slides 9, 15, 17, 18, 19, and 25 are title-only slides that serve as **section dividers** where the presenter delivers content verbally or at the board — an intentional design choice.

### Missing Slide Title

| Slide | Issue |
|-------|-------|
| **16** | No title at all. Body text discusses free markets vs. price controls corner solutions. Needs a title (e.g., "Free Markets vs. Price Controls: Interior vs. Corner"). |

### Missing Content: Robust Bounds (Contribution #3)

Slides 4 and 30 both promise **four contributions**, including "3. Robust Bounds on Welfare" — described as "Sharp welfare bounds without assuming a demand functional form. Computation reduces to a 1D optimization." However, **no slide in the deck actually presents the robust bounds methodology, equations, or results.** The empirical application section (slides 23–25) also lacks the welfare bound estimates that the paper produces.

**Recommendation:** Add 2–3 slides covering:
- The identification problem and partial identification approach
- The 1D optimization characterization (key equation from the paper)
- Empirical welfare bounds for the 1973–74 gasoline crisis (the paper's headline finding that misallocation losses exceed the Harberger triangle)

---

## III. Visual & Design Issues

### Font Inconsistency

The deck mixes multiple font families inconsistently:

| Font | Where Used | Issue |
|------|-----------|-------|
| Default theme font | Most body text | OK |
| **Garamond** | Quotes on slides 2, 3, 5, 27 | Intentional for quotes — acceptable |
| **Segoe UI Historic** | Labels on slides 5, 6, 7, 12 | Inconsistent with body text; looks accidental |

**Recommendation:** Standardize annotation/label fonts. Either use the theme font for diagram labels or consistently use a single secondary font.

### Font Size Chaos

Body text font sizes vary wildly across slides:

- Slide 4: body at 25pt, headings at 28pt
- Slide 14: body at 28pt throughout
- Slide 23: last line jumps to 28pt mid-paragraph
- Slide 26: quote attribution drops to 20pt
- Slide 29: one line inflates to 32pt

**Recommendation:** Establish a consistent type hierarchy: title size, body size, emphasis size, caption size. Stick to it.

### Text-Heavy Slides (Overflow Risk)

13 of 31 slides (42%) have over 400 characters of text — a high density for presentation slides. The worst offenders:

| Slide | Characters | Paragraphs | Topic |
|-------|-----------|------------|-------|
| 3 | 720 | 12 | The Patchwork of Rationing |
| 23 | 631 | 10 | 1971–1974 Oil Crisis |
| 20 | 610 | 6 | The Chaos Theorem |
| 26 | 609 | 11 | Chaos Mechanism in General |
| 8 | 578 | 6 | Random Allocation (literature) |
| 5 | 572 | 10 | Harberger Triangle |

**Recommendation:** Follow the "one key idea per slide" principle. Split dense slides:
- Slide 3: Separate the data (map + statistics) from the interpretive framing ("The question is not why...")
- Slide 23: Timeline would work better as a visual (timeline graphic) rather than 10 bullet points
- Slide 26: Split product-mix and temporal misallocation into two slides

### Image Quality Concerns

| Slide | Issue |
|-------|-------|
| **10** | Uses WMF format (Windows Metafile) — may not render on Mac/Linux or in web-based presentation tools |
| **11** | Same WMF issue |
| **27** | WMF image of baby chicks (3.4 MB) — very large for a presentation; consider converting to PNG |
| **22** | Simulation grid image (Fig. 4) includes the caption text baked into the image — at slide resolution, the caption and grid numbers are likely too small to read |
| **24** | Newspaper photo is 4.1 MB — unnecessarily large; compress for presentation use |

### Slides 6 & 7: Near-Duplicate

Slides 6 and 7 both have the title "Random Allocation" and **identical body text** ("A natural response is to ask what happens under random allocation?...Two neat visuals."). They appear to show two different diagrams but the text is copy-pasted. The text says "Two neat visuals" but shows only one per slide.

**Recommendation:** Either:
- Combine into one slide with both diagrams side by side (the text promises "two neat visuals")
- Differentiate the text on each slide to explain what each specific diagram shows

---

## IV. Pedagogical & Narrative Improvements

### Narrative Arc Assessment

The current slide order:

```
1.  Title
2.  Oil Crisis (motivation)
3.  Patchwork of Rationing (data)
4.  Four Contributions (roadmap)
5.  Harberger Triangle (Econ 101)
6-7. Random Allocation (two near-identical slides)
8.  Random Allocation literature
9.  [EMPTY] Setup: Two Segments
10. Shadow Price Equalization
11. Equally Feasible Allocation
12. Harberger Is Minimum DWL
13-14. Why Corners?
15. [EMPTY] From Two to Many
16. [NO TITLE] Free markets vs. price controls
17. [EMPTY] Theorem 1
18. [EMPTY] Markets are Smooth
19. [EMPTY] Under Price Controls
20. Chaos Theorem
21. Chaos Intuition (diagram)
22. Chaos Simulation
23. Oil Crisis Timeline
24. AAA Station Data
25. [EMPTY] Identification Problem
26. Chaos Mechanism: General
27. Baby Chicks
28. Supply-Chain Breaking
29. Political Economy
30. Summary
31. Final Words
```

### Structural Recommendations

1. **Roadmap mismatch:** Slide 4 advertises four contributions but the deck effectively covers only two fully (corner allocations and the chaos theorem). Robust bounds (#3) is entirely absent. The empirical application (#4) is thin — it provides historical narrative but no quantitative results from the paper.

2. **The "dead zone" (slides 15–19):** Five consecutive slides, four of which are empty/near-empty, create a hole in the middle of the presentation. This is where the generalization from 2 to N markets and the formal theorem should live. Currently the audience sees a sequence of title screens.

3. **Late empirical payoff:** The empirical application doesn't arrive until slide 23 (of 31). Consider moving the "headline number" (misallocation >> Harberger triangle) earlier as a teaser, then returning to prove it.

4. **Missing "so what" for welfare bounds:** Slides 30 and 4 both claim "Misallocation generates more welfare loss than the quantity reduction" but the deck never shows the actual numbers or methodology that supports this claim.

5. **Section transitions:** The deck lacks clear section dividers. Adding brief transition slides (e.g., "Part I: Motivation," "Part II: Theory," "Part III: Empirics") would help the audience track where they are.

### Specific Slide Suggestions

| Slide | Suggestion |
|-------|-----------|
| **2** | Strong opening. The "Sorry NO GAS" photo is effective. Consider adding a source/date caption for the photo. |
| **3** | The choropleth map is excellent. Consider enlarging it — the right-side text caption (in Garamond) competes with the bullet points on the left. |
| **4** | Good roadmap but overpromises given current deck content. Either add the missing sections or reduce to the contributions actually covered. |
| **5** | "But why should this be?" is a great rhetorical question. The annotation arrows (pointing to "Demanders with Highest WTP") are good but in a different font (Segoe UI Historic) than the body. |
| **8** | Literature review slide — consider whether this is needed in a seminar talk. It interrupts the flow between the motivating puzzle and the model. Could be moved to an appendix or condensed to one line. |
| **12** | The feasible set diagram is one of the deck's strongest visuals. But the labels ("Vertex Allocations") are in a different font. The dots marking the vertices are only 0.06" — they may be invisible from the back of a room. |
| **14** | "The knife-edge" framing is excellent and memorable. This is one of the deck's best slides. |
| **20** | The Chaos Theorem statement is dense. Consider breaking it into: (a) statement of the theorem, (b) interpretation/implication, on two separate slides. |
| **21** | The "Free Markets → Price Controls" comparison diagram is clean and effective. One of the best visuals in the deck. |
| **22** | The simulation grid is a powerful visual but may be hard to read in a large room. Consider showing one pair (free market vs. price control) enlarged, then the full grid. |
| **27** | The baby chicks example is memorable and effective storytelling. Consider whether the WMF image renders correctly on all systems. |
| **29** | "Shortage-chaos → demand for quantity management → regulations" — this political economy point is important but underdeveloped. It deserves more than four bullets. |
| **31** | The closing quote ("the main cost is not the familiar triangle, but the hidden misallocation behind it") is strong. |

---

## V. Comparison with Beamer Deck

The Beamer version (`Price_Controls_Chaos.tex`, 871 lines) is substantially more complete:

| Feature | PowerPoint | Beamer |
|---------|-----------|--------|
| Total slides | 31 | ~45 |
| Empty/placeholder slides | 6 | 0 |
| Robust bounds section | Missing | Present |
| Empirical results (quantitative) | Missing | Present |
| Section dividers | None | Yes (Part I–VIII) |
| Consistent typography | No | Yes (LaTeX-enforced) |
| Custom environments (keybox, etc.) | No | Yes |
| Speaker notes | Sparse (4 slides) | N/A |
| Source citations | Incomplete | Complete |

**Recommendation:** If this PowerPoint is intended to be the primary presentation format, port the missing content from the Beamer deck. If it's a supplementary version, consider marking it as "draft" and directing effort to the Beamer slides.

---

## VI. Summary Scorecard

| Category | Score | Notes |
|----------|-------|-------|
| **Content accuracy** | 7/10 | Glaeser misspelling, missing attribution, typos in notes |
| **Completeness** | 5/10 | 6 empty slides, missing robust bounds section, missing empirical results |
| **Visual design** | 6/10 | Good figures but inconsistent fonts, text-heavy, WMF format issues |
| **Narrative flow** | 6/10 | Strong opening and closing but "dead zone" in the middle |
| **Pedagogical clarity** | 7/10 | Key intuitions (knife-edge, corners, chaos) are well-explained |
| **Technical rigor** | 5/10 | Theorem stated without proof sketch; welfare claims lack supporting numbers |
| **Overall** | **60/100** | Solid foundation but needs significant work to be presentation-ready |

---

## VII. Priority Action Items

### Must Fix (Before Any Presentation)
1. **Fill the 6 empty slides** or remove them from the deck
2. **Fix "Glaser" → "Glaeser"** on slide 8
3. **Add a title** to slide 16
4. **Fix the trailing slash** on slide 23 ("prices/")
5. **Fix the font inconsistencies** (Segoe UI Historic labels)

### Should Fix (Before a Seminar)
6. **Add robust bounds section** (2–3 slides) — this is contribution #3
7. **Add empirical welfare results** — the headline numbers from the paper
8. **Split text-heavy slides** (3, 5, 8, 20, 23, 26)
9. **Convert WMF images to PNG** for cross-platform compatibility
10. **Deduplicate slides 6/7** or differentiate their text
11. **Add section transition slides** for navigation

### Nice to Have
12. Compress oversized images (slides 24, 27)
13. Add speaker notes to key slides
14. Add page numbers / progress indicator
15. Standardize quote formatting (some in Garamond italic, some in body font)
16. Consider adding a "preview of key result" slide early (e.g., after slide 4)
