# CAJAL SVG Generation Log — Friction: Measuring the Learning Struggle

## Run: 2026-05-29

Generated static Brutalist-style SVGs from `pantry/*-cajal.md` plans, then converted to 300 DPI PNG. Content was drawn from the actual chapter prose (the CAJAL plans carried generic placeholder labels and an Okabe-Ito palette; both were overridden — content extracted, Brutalist house style applied). Chapter files were not modified; no markdown references inserted.

| Cajal file | Figures | Generated | Skipped |
|---|---|---|---|
| 00-frontmatter-cajal.md | 0 | 0 | 0 |
| 01-the-artifact-is-no-longer-enough-cajal.md | 5 | 5 | 0 |
| 02-what-genuine-learning-leaves-behind-cajal.md | 0 | 0 | 0 |
| 03-y1-temporal-engagement-pattern-cajal.md | 5 | 5 | 0 |
| 04-y2-error-trajectory-coherence-cajal.md | 4 | 4 | 0 |
| 05-y3-cross-context-transfer-cajal.md | 5 | 5 | 0 |
| 06-y4-uncertainty-calibration-cajal.md | 5 | 5 | 0 |
| 07-y5-social-knowledge-texture-cajal.md | 5 | 5 | 0 |
| 08-y6-retrieval-strength-decay-cajal.md | 5 | 5 | 0 |
| 09-y7-scaffolding-response-curve-cajal.md | 5 | 5 | 0 |
| 10-the-ensemble-cajal.md | 5 | 5 | 0 |
| 11-building-your-second-evidence-stream-cajal.md | 5 | 5 | 0 |
| 99-back-matter-cajal.md | 0 | 0 | 0 |

## Summary
- Total cajal.md files processed: 13
- Files with zero figures (CAJAL declined — front/back matter + orientation ch.02): 3 (00, 02, 99)
- Total figures parsed: 49
- Total SVGs generated: 49
- Total skipped (already exist): 0
- PNG conversion: run completed — 49 PNGs at 300 DPI

## Verification
- xmllint --noout: all 49 SVGs valid
- viewBox 0 0 700 ...: all 49 conform; no `width`/`height` attrs on `<svg>`
- No rounded corners, no gradients/shadows
- No Okabe-Ito palette leakage (#0072B2/#56B4E9/#009E73/#E69F00/#D55E00 = 0 files)
- No forbidden fonts (Arial/Roboto/system-ui = 0 files)
- Visual spot-check: 01-fig-01 (decoupling two-pathway map), 08-fig-02 (Karpicke–Roediger 2008 retrieval/restudy crossover) — both accurate and on-style.

## Notes
- A few footer captions run close to the right margin (e.g. 08-fig-02); content is correct and legible. Flagged for the enrichment/finishing pass if tightening is wanted.
- Enrichment pass (inserting markdown image refs + D3 HTML + Prompts sections into chapters) NOT done here — separate step.
