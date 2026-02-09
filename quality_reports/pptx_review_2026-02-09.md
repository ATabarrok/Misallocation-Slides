# Review: "Price Controls Cause Chaos.pptx"

**Reviewer:** Claude Code
**Date:** February 9, 2026
**File:** `Slides/Price Controls Cause Chaos.pptx`
**Slides:** 31 | **Dimensions:** 13.3" × 7.5" (widescreen 16:9)

---

## Overall Assessment

This is a strong research talk with a compelling narrative arc: motivation via historical puzzle → theory (corner allocations, chaos theorem) → empirics → broader implications. The core ideas are powerful and clearly articulated. The deck has some text errors, font inconsistencies, and places where pedagogical flow could be sharpened.

**Note:** Slides 9, 15, 17, 18, 19, and 25 contain substantial math-heavy content stored in PowerPoint's Office 2010+ equation format (`a14` namespace). This content is fully visible in PowerPoint but invisible to Python extraction tools.

**Estimated Score: 80/100** — strong deck, needs a proofreading pass and some visual polish.

---

## 1. ERRORS & TYPOS

### Factual/Spelling Errors

| Slide | Issue | Fix |
|-------|-------|-----|
| **8** | "**Glaser** and Luttmer (2003)" — misspells Glaeser | Change to **"Glaeser and Luttmer (2003)"** |
| **8** | "Bulow and Klemperer study when random allocation **result** in large misallocation" | Change to **"results"** (subject-verb agreement) |
| **23** | "August 1971: Nixon freezes all wages and prices**/**" — trailing slash | Remove the trailing **"/"** |
| **27** | "Similar story with cows**,** and pigs." — comma splice / awkward | Rephrase: "Similar dynamics with cattle and hogs." |
| **27** | "Cull now when future price<current price." — missing space around `<`, reads like code | Use: "Cull now when future price **<** current price" or rephrase entirely |
| **14** | Speaker notes: "When **prizes** are frozen" | Should be **"prices"** |

### Punctuation & Style Issues

| Slide | Issue | Fix |
|-------|-------|-----|
| **5** | "That is**,** it assumes that the Qc of output…" — missing comma after "That is" | Add comma: "That is**,** it assumes…" |
| **11** | "As a result **a+b>c**" — missing formatting/spaces | Should be: "As a result, **a + b > c**" |
| **13** | "Linear program**->**Corner solutions." — ASCII arrow, missing space | Use: "Linear program → corner solutions." |
| **27** | "Small cost wedges**->**vertex" — same ASCII arrow issue | Use: "Small cost wedges → vertex" |
| **26** | "Controlled prices + small cost wedges**→** large shifts" — inconsistent; some slides use `->`, others `→` | Standardize to **→** throughout |
| **3** | "Answer: Efficient allocation requires price variation. A binding ceiling explicitly **forbids** it." — this is strong and good, but the sentence before it ("Why should some markets clear while others run dry?") is a question that should probably end the key-question section, not precede the answer in the same text block | Consider separating the question and answer visually |

---

## 2. STRUCTURAL NOTES

### Equation-Heavy Slides (a14 format)

Slides 9, 15, 17, 18, 19, and 25 contain rich content with mathematical equations stored in PowerPoint's `a14` (Office 2010+) format. Summary of their actual content:

| Slide | Title | Content |
|-------|-------|---------|
| **9** | Setup: Two Segments/Submarkets | Two-market setup with D₁(p), D₂(p), price ceiling p̄, feasibility constraints |
| **15** | From Two to Many | n submarkets, flexible "submarket" definition (geographic/temporal/product/production), feasible set F as convex polytope with vertex characterization |
| **17** | Theorem 1 (Worst Case) | Worst-case allocation at corner of F, intuition via concavity, cutoff λ characterization |
| **18** | Markets are Smooth | Free-market surplus maximization, Berge's Maximum Theorem → continuity in θ |
| **19** | Under Price Controls: Cost Minimization | Cost minimization LP under ceiling, markets filled by increasing cost, discontinuity result |
| **25** | The Identification Problem | Local identification problem, CES example, robust bounds framing |

### Missing Title

| Slide | Issue |
|-------|-------|
| **16** | Has body text but **no title** — the text discusses "Without price controls…" / "Under price controls…" |

**Recommendation:** Add a title like "Markets vs. Price Controls: Interior vs. Corner Solutions" or fold this content into slide 15 ("From Two to Many").

---

## 3. VISUAL & DESIGN ISSUES

### Font Inconsistency

The deck mixes at least **4 different fonts**:

| Font | Where Used | Role |
|------|------------|------|
| Default (theme font) | Most body text | Primary |
| **Garamond** | Slides 2, 3, 5, 27 | Quotes and captions |
| **Segoe UI Historic** | Slides 5, 6, 7, 12 | Annotations on figures |
| Theme title font | Slide titles | Titles |

**Recommendation:** Unify all body text to one serif or sans-serif family. Use Garamond *only* for block quotes if you want a distinguished quote style — but use it consistently. Remove all Segoe UI Historic usage.

### Font Size Variation

Body text ranges from **12pt to 32pt** across slides:

- 12pt: Figure annotations (Slides 6, 7) — possibly too small for a talk
- 14pt: Figure annotations (Slide 5)
- 20pt: Attribution (Slide 26)
- 24pt: Quote (Slide 2)
- 25pt: Body text (Slides 4, 30)
- 28pt: Body text (Slides 4, 14, 23, 26, 30)
- 32pt: Body text (Slide 29)

**Recommendation:** Standardize body text to 24–28pt. Figure annotations should be no smaller than 16pt for readability in a lecture hall.

### Text-Heavy Slides (Overflow Risk)

These slides have high text density and may overflow or appear cramped:

| Slide | Title | Chars | Paras | Risk |
|-------|-------|-------|-------|------|
| 3 | The Patchwork of Rationing | 720 | 12 | **High** |
| 8 | Random Allocation | 578 | 6 | Medium |
| 20 | The Chaos Theorem | 610 | 6 | Medium |
| 23 | Illustration: 1971–1974 Oil Crisis | 631 | 10 | **High** |
| 26 | The Chaos Mechanism in General | 609 | 11 | **High** |
| 28 | Supply-Chain Breaking | 552 | 8 | Medium |

**Recommendation:** Split the densest slides. Slide 3 tries to show data + make the key argument + include a map + add a caption — it's doing 4 things. Slide 23 packs 8 historical bullet points into one slide; consider splitting into "Timeline" (1971–1973) and "Crisis" (1973–1974).

### Image Format Issues

| Slide | Image Format | Issue |
|-------|-------------|-------|
| 10 | WMF (Windows Metafile) | May not render on macOS/Linux; poor cross-platform support |
| 11 | WMF | Same issue |
| 27 | WMF (3.4 MB!) | Very large WMF; should be converted to PNG or SVG |

**Recommendation:** Convert all WMF images to high-resolution PNG for maximum compatibility. The WMF on slide 27 (baby chicks image) is 3.4 MB — it should be re-exported.

### Slide 24 Layout

Slide 24 ("The Data: AAA Station Surveys") has a title and a single photo ("Sorry No Gas") but no data or explanation. The title promises data but delivers only a photo. Either:
- Add the actual AAA survey data points, or
- Retitle to something like "The Gasoline Crisis in Pictures" and add a brief caption

---

## 4. NARRATIVE & PEDAGOGICAL ISSUES

### Slides 6–7: Near-Identical Duplicates

Slides 6 and 7 both have:
- Title: "Random Allocation"
- Identical body text (word-for-word)
- Very similar figures (slight variation in shading)
- Same "Harberger Triangle" annotation

**Recommendation:** These appear to be progressive-reveal slides (showing different areas on the S&D diagram). If so, they work as an animation pair — but the body text should change between them to guide the audience through what's being revealed. Currently the text is identical, which wastes the second slide.

### Robust Bounds Coverage

Slide 25 ("The Identification Problem") introduces the robust bounds idea — the local identification problem, the CES example, and the framing question. This is lighter coverage than the Beamer version (which devotes ~8 slides including the 1D optimization characterization and empirical bounds). Consider whether adding 1–2 more slides on the actual bounds methodology and results would strengthen the talk for technical audiences.

### Slide 29 (Political Economy) Feels Disconnected

The political economy slide makes an important point (price controls create demand for bureaucratic allocation) but comes after the historical examples without clear setup. Consider moving it to follow the chaos theorem directly, as a "policy implication," then proceed to the empirical evidence.

### Final Slide is Image-Only

Slide 31 ("Final Words") is a nice closing image with a memorable quote, but consider adding:
- A brief summary of the main takeaway
- Contact information or paper link
- The paper title and author list for the audience to photograph

---

## 5. CONTENT IMPROVEMENTS

### Slide 2: Attribution Needed for Quote

The Yergin (1991) quote is excellent but has no visible attribution in the PPTX (the Beamer version adds "— Yergin (1991)"). Add it.

### Slide 5: Pedagogical Clarity

The text asks "How can the consumers with the highest willingness to pay outbid consumers with a lower WTP when prices are fixed by law?" — this is the key insight and it's buried in a paragraph. Consider making this the **highlighted takeaway** in a box or larger font.

### Slide 8: Clarify Bulow & Klemperer Point

The sentence "Requires information on log convexity, log concavity etc. of demand curves. Not obvious!" is informal and could be sharper. Something like: "Their results depend on specific functional form assumptions about demand (log-convexity/concavity) — hard to verify in practice."

### Slide 12: Feasible Set Diagram

The feasible set slide has a geometric figure with dots and arrows but very little explanatory text. The audience needs to understand what the axes represent and why the feasible set is a convex polytope. Add axis labels or a brief caption.

### Slide 14: The "Knife-Edge" Section

The four-step logic on slide 14 is one of the most compelling parts of the talk. Consider giving each step its own visual emphasis (numbered boxes or a step diagram) rather than plain bullet points.

### Slide 22: Simulation Figure

The 100-city simulation (Figure 4) is excellent but the slide text says "Red is served. Yellow is zero allocation." In the actual figure, orange = served and white/yellow = zero. Verify color descriptions match the figure.

### Slide 26: Missing Attribution for Congressional Testimony

The quote "Phases 3 and 3A have created price anomalies..." is attributed to "1973 Congressional testimony" — who said it? Add the speaker's name for credibility.

---

## 6. WHAT WORKS WELL

- **Opening hook** (Slides 2–3): The 1974 oil crisis + choropleth map immediately establishes the puzzle. Very effective.
- **"Feast or famine" framing** (Slide 2 callout box): Memorable and punchy.
- **Four-step logic** (Slide 14): Clean, elegant derivation of why corners emerge.
- **Baby chicks example** (Slide 27): Vivid, memorable, demonstrates the real-world stakes.
- **Simulation grid** (Slide 22): Excellent visual — the contrast between smooth free-market allocations and chaotic price-control allocations is immediately visible.
- **Closing image** (Slide 31): Strong final message about "hidden misallocation."
- **Free Markets vs. Price Controls comparison** (Slide 21): The side-by-side box with math notation is clean and effective.

---

## 7. PRIORITY RECOMMENDATIONS

### Must Fix (Before Presenting)

1. **Fix the Glaeser misspelling** (Slide 8)
2. **Fix "prices/" typo** (Slide 23)
3. **Fix "prizes" → "prices"** in Slide 14 speaker notes
4. **Convert WMF images to PNG** for cross-platform compatibility

### Should Fix (Quality Polish)

6. Unify fonts (eliminate Segoe UI Historic, standardize Garamond for quotes)
7. Split the densest slides (3, 23, 26)
8. Differentiate slides 6 and 7 (duplicate text)
9. Add a title to slide 16
10. Add Yergin attribution to slide 2 quote

### Nice to Have (Excellence)

11. Add a transition slide between theory and empirics
12. Enhance slide 14 with visual step-by-step formatting
13. Add speaker name to Congressional testimony quote (slide 26)
14. Add contact info / paper link to final slide
15. Standardize arrow notation (→ not ->)

---

## Comparison with Beamer Version

The Beamer deck (`Price_Controls_Chaos.tex`, 871 lines) covers similar ground with some differences:
- Has a more detailed **Robust Bounds** section (Part V, ~8 slides vs. 1 slide in PPTX)
- Has a **Toy Example** section (Part VI) not in the PPTX
- Has consistent LaTeX typography throughout
- Contains more speaker notes

The PPTX has strengths the Beamer lacks: richer historical examples (baby chicks, supply-chain breaking, political economy), more vivid quotes, and the "Sorry No Gas" photo. The two decks complement each other well for different audiences.
