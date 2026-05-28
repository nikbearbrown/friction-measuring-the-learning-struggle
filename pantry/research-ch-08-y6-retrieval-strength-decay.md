# Research: Chapter 08 — Y6: Retrieval Strength Decay Signature
## Friction Traces: Measuring the Struggle That Proves the Learning

**Chapter one-line:** Genuine learning shows the spacing effect — performance holds up better after distributed practice than massed practice. Borrowed certainty shows monotonic decay. The decay curve shape is the signal.
**Research date:** 2026-05-27

---

## 1. Primary Sources

### Foundational papers and texts

- **Bjork, R. A., & Bjork, E. L. (1992). "A New Theory of Disuse and an Old Theory of Stimulus Fluctuation." In A. F. Healy, S. M. Kosslyn, & R. M. Shiffrin (Eds.), *From Learning Processes to Cognitive Processes: Essays in Honor of William K. Estes* (Vol. 2, pp. 35–67). Erlbaum.** The single most important theoretical reference for this chapter. Distinguishes *storage strength* (how thoroughly something is encoded; effectively monotonic and slow-changing) from *retrieval strength* (how accessible something is right now; fluctuates with cues, context, recency). The central counter-intuitive result: conditions that produce high immediate retrieval strength (massing, restudy, AI-explained) can produce *lower* gains in storage strength than conditions that introduce desirable difficulties. This is the chapter's mechanistic core.
- **Ebbinghaus, H. (1885). *Über das Gedächtnis: Untersuchungen zur experimentellen Psychologie.* (English: *Memory: A Contribution to Experimental Psychology*, trans. Ruger & Bussenius, 1913.)** The forgetting curve. Nonsense syllables, savings method, the first empirical exponential decay function in psychology. Foundational. The "fast initial drop then slower decline" curve every textbook reproduces.
- **Cepeda, N. J., Pashler, H., Vul, E., Wixted, J. T., & Rohrer, D. (2006). "Distributed Practice in Verbal Recall Tasks: A Review and Quantitative Synthesis." *Psychological Bulletin* 132(3): 354–380.** The definitive meta-analysis. 317 experiments. Spacing effect is one of the most robust findings in cognitive psychology. Effect sizes are large and consistent across populations and materials. This is the meta-analytic foundation Y6 stands on.
- **Cepeda, N. J., Vul, E., Rohrer, D., Wixted, J. T., & Pashler, H. (2008). "Spacing Effects in Learning: A Temporal Ridgeline of Optimal Retention." *Psychological Science* 19(11): 1095–1102.** The "ridgeline" follow-up. The optimal gap between practice sessions scales with the retention interval — roughly 10–20% of the desired retention period. Practical translation for practitioners: if you want students to remember in 6 months, space practice ~3–6 weeks apart. If you want them to remember in 2 weeks, space ~1–3 days apart. Direct curriculum-design implication.
- **Adesope, O. O., Trevisan, D. A., & Sundararajan, N. (2017). "Rethinking the Use of Tests: A Meta-Analysis of Practice Testing." *Review of Educational Research* 87(3): 659–701.** The meta-analysis of the testing effect. 118 studies, 15,427 participants. Practice testing produces durable learning gains across age groups, materials, and time-delays. Effect size *g* ≈ 0.6. The retrieval-practice literature anchor.

### Key empirical cases

- **Roediger, H. L., & Karpicke, J. D. (2006). "Test-Enhanced Learning: Taking Memory Tests Improves Long-Term Retention." *Psychological Science* 17(3): 249–255.** The reference experiment. Students who restudied a passage performed *better* on an immediate test than students who retrieved it; students who retrieved it performed *substantially* better one week later. The decay-curve dissociation is visible inside a single 2-condition study. The cleanest possible demonstration of the storage/retrieval distinction.
- **Karpicke, J. D., & Roediger, H. L. (2008). "The Critical Importance of Retrieval for Learning." *Science* 319(5865): 966–968.** The follow-up. Students given repeated retrieval opportunities (vs. repeated study) showed 80% retention at one week vs. 33% retention for the restudy group. Same immediate performance; radically different decay curves.
- **Bahrick, H. P. (1984). "Semantic Memory Content in Permastore: Fifty Years of Memory for Spanish Learned in School." *Journal of Experimental Psychology: General* 113(1): 1–29.** Cross-sectional study of Spanish retention 0–50 years after the original course. Found a stable "permastore" plateau after ~3–6 years — material that survived that long was likely to survive indefinitely. The empirical basis for the claim that genuine learning has a long-tail retention that surface learning does not.
- **Wozniak, P. A., & Gorzelańczyk, E. J. (1994). "Optimization of Repetition Spacing in the Practice of Learning." *Acta Neurobiologiae Experimentalis* 54(1): 59–62.** The SM-2 algorithm in the academic literature. The algorithmic ancestor of all modern spaced-repetition scheduling, including Anki and FSRS. SuperMemo's SM-2 has been operational since 1985.
- **Ye, J., et al. (FSRS algorithm, 2022–2024, primarily blog and GitHub).** The Free Spaced Repetition Scheduler. A three-component memory model (difficulty, stability, retrievability) fit to large-scale Anki review data. Improvements over SM-2 are real but the academic literature on FSRS is thin — most documentation is on GitHub (open-spaced-repetition) and Jarrett Ye's blog. The chapter should mention FSRS as the "what a platform adds" example and flag the thin academic record honestly.
- **Cepeda, N. J., Coburn, N., Rohrer, D., Wixted, J. T., Mozer, M. C., & Pashler, H. (2009). "Optimizing Distributed Practice: Theoretical Analysis and Practical Implications." *Experimental Psychology* 56(4): 236–246.** The theoretical underpinning of why the temporal ridgeline shape emerges. Useful for the chapter's "why it works" section.

---

## 2. The Core Concept — State of the Field

### What is settled

The spacing effect is one of the most robust findings in cognitive psychology. Cepeda et al. 2006 is meta-analytically definitive. Distributed practice produces durable learning; massed practice produces immediate performance. This has not been overturned in any serious replication attempt for 40+ years.

The testing effect (retrieval practice) produces durable learning gains. Adesope, Trevisan, Sundararajan 2017 is the meta-analytic anchor; the Karpicke-Roediger lab has 20+ years of confirmatory work. Practice testing beats restudy on long-delay assessments; the immediate assessment shows the opposite, which is why the decay curve matters.

Storage strength and retrieval strength can dissociate. Bjork & Bjork 1992 is theoretically definitive; Karpicke & Roediger 2006 is empirically definitive. Immediate performance is not a reliable predictor of long-term retention. This is the single most important argument the chapter makes.

The forgetting curve is real and roughly exponential. Ebbinghaus 1885 has been replicated many times; the specific exponent varies with material and population, but the qualitative shape — fast initial drop, slower later decline — is universal.

Bahrick's permastore is established for some material (foreign language vocabulary, mathematical principles). Whether all genuinely-learned material has a permastore plateau is less settled, but the existence of long-tail retention for *some* material is uncontroversial.

### What is disputed

The optimal spacing function — the precise ratio of inter-study interval to retention interval — is contested in detail. Cepeda's 10–20% rule is a useful rule of thumb but the field has not converged on a definitive function. Practitioner translation: any non-zero spacing beats massing; precise optimization is a platform problem, not a teacher problem.

Whether FSRS substantially outperforms SM-2 in classroom contexts is currently a hobbyist/practitioner claim more than an academic finding. The FSRS team's own evaluations on Anki user data show clear improvements; independent academic replication is thin.

Whether AI-assisted learning specifically produces monotonic decay (the Y6 borrowed-certainty signature) is a clear prediction with thin direct evidence. Bastani 2025 is consistent — students who used AI heavily performed worse on a delayed test — but the study did not measure a full decay curve.

Whether the testing effect is mediated by retrieval per se or by the desirable-difficulty principle more generally is an active theoretical debate (Karpicke vs. Pyc & Rawson interpretations). Practitioner translation: the empirical fact is robust; the underlying mechanism is still being adjudicated.

### What has changed recently (last 5 years)

The FSRS algorithm has emerged from the Anki community as a significant practical improvement over SM-2. Open-source, well-documented (in blog form), increasingly default in Anki itself. Academic literature is catching up.

Generative AI's effect on spaced-repetition study is unclear. Some students use AI to generate flashcards from textbooks (a plausible productivity gain); others use AI to *answer* the flashcards (which defeats the retrieval-practice mechanism). The chapter should mention this without making it the main argument.

Several recent studies have looked at decay curves in AI-assisted learning environments. The pattern is consistent with prediction (steeper decay) but the literature is still consolidating.

Bjork's "desirable difficulties" framing has gained mainstream traction outside academia (Ericsson, Make It Stick, Lang's pedagogy books). This is good for the chapter — the reader may have encountered the framing before.

---

## 3. Application Domain Examples

**High school science (primary reader).** A physics teacher adds three "decay probe" questions to each weekly quiz, drawn from material covered 3–6 weeks earlier. Not announced in advance. Tracks each student's performance on decay probes vs. current-week questions. Students whose decay-probe performance holds up are showing genuine Y6. Students whose decay-probe performance collapses while current-week performance stays high are showing the borrowed-certainty signature: they look fine in the moment but the storage isn't there.

**High school math.** An algebra teacher integrates spaced retrieval as the homework structure: every problem set includes 70% current-unit, 30% previously-taught. The 30% legacy items *are* the decay probes. The teacher gets continuous Y6 data without any extra instrument.

**Higher ed introductory statistics.** A weekly low-stakes quiz includes a "from earlier" section. Students who consistently retain ANOVA logic from the early-term unit through the regression unit are showing genuine learning. Students whose earlier material collapses while current-unit performance is fine are showing the decay-curve signature.

**Clinical education (medical).** USMLE-style preparation has used spaced-retrieval for decades; the structure is already there. The Y6 question is whether students' decay curves on board-style material are consistent with genuine learning or with cramming. Most clinical educators already know this informally; Y6 formalizes it.

**Instructional design (secondary reader).** Designing for Y6 means redesigning curriculum to embed legacy items in current assessments. This is a structural intervention, not an add-on. The institutional benefit is large: every assessment becomes a measurement instrument for retention, not just for current-unit performance.

**Where Y6 is hardest.** Single-semester courses without follow-on assessment. The decay curve needs time to develop; a 6-week summer intensive can show short-delay decay but cannot show the 6-month permastore plateau. The chapter should be honest that Y6 is more powerful in year-long or sequenced courses.

---

## 4. The Book's Thesis Connection

Y6 is the chapter where the storage/retrieval distinction (Chapter 2) becomes operational. The chapter should explicitly reconnect: the reason the artifact is no longer enough is, in part, that artifact-based assessment measures retrieval strength at one moment in time. Genuine learning is fundamentally a storage-strength claim, and storage strength can only be measured by looking at *decay over time*. A single quiz cannot do this. A sequence of quizzes with legacy items can.

The borrowed-certainty mechanism is mechanistically clean. AI-assisted "study" looks like retrieval but isn't — the student reads the AI's explanation, recognizes it as familiar, judges themselves prepared. No retrieval failure occurs; no storage-strength gain accrues. The fluency cue (Chapter 6) inflates confidence; the absence of effortful retrieval prevents storage. The student performs well immediately and decays fast.

Y6 is also the cleanest signal for instructional design. Unlike Y5 (subjective) or Y3 (requires careful item design), Y6 can be implemented by changing the *structure* of existing assessment rather than by adding new instruments. Insert legacy items. Track performance. The signal emerges from data the school already collects.

The chapter must be honest about a methodological subtlety. The Y6 signal requires that the legacy items be matched in difficulty to current-unit items. If the legacy items are harder, a low score is ambiguous (decay vs. difficulty). If they're easier, a high score is ambiguous (retention vs. surface familiarity). The chapter should give the practitioner two practical moves: (a) use items from the same item bank, calibrated by past performance, and (b) when in doubt, embed *more* legacy items rather than fewer.

Y6 also has the strongest connection to the AI Wayback Machine — Ebbinghaus is the chapter's natural anchor, and his methodology (nonsense syllables, savings method, self-experimentation) is so concrete and historical that the practitioner reader can visualize it. The chapter benefits from this in a way other chapters do not.

---

## 5. The AI Wayback Machine — Candidate Figures

**Hermann Ebbinghaus (1850–1909, German psychologist).** The founding empiricist of memory research. Self-experimented with nonsense syllables for years to establish the forgetting curve and the savings method. Worked alone, against the philosophical-psychology orthodoxy of his time. Wrote one short book (1885) that became the foundation of an entire subfield. Accessible, vivid, historically central, perfect for a practitioner-readable wayback feature. Non-Anglo (German). **Recommended pick.**

**Frances A. Yates (1899–1981, Warburg Institute, UK).** Author of *The Art of Memory* (1966), the definitive history of memory palaces and classical/medieval/Renaissance mnemonics. Woman, English, historian rather than psychologist. The wayback feature on Yates could anchor a sidebar on "mnemonics before science" that contrasts the techniques (loci, association) with the empirical findings (spacing, retrieval). Doubles as a woman and as a corrective to the German-experimental story. Strong secondary candidate.

**Piotr Wozniak (Polish, b. 1962, SuperMemo founder).** Inventor of the SM-2 algorithm, the practical bridge between Ebbinghaus and modern spaced repetition. Polish, alive, accessible (writes extensively on supermemo.guru). Non-Anglo. Useful if the chapter wants a contemporary figure who connects the academic and practical traditions.

**Endel Tulving (1927–2023, Estonian-Canadian).** Episodic/semantic distinction, encoding-specificity principle. Recent death; foundational to the modern understanding of memory systems. The chapter doesn't lean heavily on Tulving but a wayback feature is plausible.

**Recommended pick for this book:** Ebbinghaus. The chapter is fundamentally about decay curves; the founding paper *is* the decay curve; the practitioner reader gets the satisfying experience of meeting the person whose name they've heard in education podcasts. Ebbinghaus also satisfies the non-Anglo dimension of the cross-chapter diversity goal.

**For the cross-chapter diversity tally:** if Hatano (Ch 5) is the non-Anglo pick and Lichtenstein or Resnick (Ch 6/7) is the woman, then Ch 8 can lean fully into Ebbinghaus as the historical anchor. If different choices were made in 5–7, Yates is a viable alternative.

---

## 6. Pedagogical Delivery Research

The chapter has the most concrete, ready-to-use intervention of any in the seven-signals sequence. The Feynman arc should be aggressive about this.

**Opening.** The TIKTOC two-students opening (same immediate score, different 3-week retention) is ideal. Don't replace it.

**Mechanism unfold.** Bjork & Bjork's storage/retrieval distinction in plain language. The chapter should walk through it explicitly because Chapter 2 introduced it abstractly; Y6 is where it earns its keep. Useful image: a library card system. Retrieval strength is how fast you can find the book on the shelf today; storage strength is whether the book is actually in the library. AI explanation puts the book in your hand right now but never adds it to the library.

**Single key mechanism dive.** The Karpicke-Roediger 2006 study walked through in detail. Two conditions, same passage, immediate test favors restudy, one-week test favors retrieval, the cross-over is the headline finding. This is the cleanest possible empirical anchor for the chapter's argument.

**Hand to reader.** A one-paragraph implementation: every weekly quiz includes three questions from material covered 3–6 weeks earlier. Track student performance on those questions specifically. The decay curve emerges from the data over the term. No platform required.

**Bonus move.** The chapter should explicitly tell the practitioner that the Y6 implementation also *produces* the spacing benefit it measures — students who anticipate legacy items will study spaced-rehearsally rather than mass-cramming. The instrument is also the intervention. This is uniquely Y6.

The exercises should follow TIKTOC's three-exercise structure: one Apply (design a decay-probe sequence for a current unit), one Analyze (interpret a sample decay curve), one Apply (predict and verify the spacing effect in their own classroom).

---

## 7. Representation and Display Research

How to observe Y6 without a platform.

**Method 1: Embedded legacy items.** Every quiz includes 2–4 items from material 3+ weeks old. Not announced. Track legacy-item performance vs. current-unit performance per student. The gap is the Y6 signal. Cheapest possible implementation, works with any existing assessment infrastructure.

**Method 2: Three-time-point testing.** Same item bank, tested at three time points: immediately after teaching, 2 weeks later, 6+ weeks later. The slope from time-1 to time-3 is the decay rate. More work than Method 1 but produces cleaner decay-curve data per item.

**Method 3: Cumulative final exam construction.** The final exam includes items from every prior unit, scored separately by unit. The "by-unit" score reveals which units stuck and which decayed. Many institutions already do this; the Y6 framing is to *use* the by-unit data, not just aggregate.

**Method 4: The spacing intervention itself.** Restructure homework so each problem set is 70% current unit, 30% mixed prior units. This is both the intervention (it produces spaced practice) and the measurement (the prior-unit items are decay probes). Cleanest possible "the instrument is the intervention" implementation.

**Method 5: The student-self-test prompt.** Ask students at the start of a new unit: "Without consulting your notes, write everything you remember from Unit 3." The depth and accuracy of the recall is a qualitative Y6 read. Best for low-stakes formative use, not summative.

**What a platform adds:** FSRS scheduling at the per-concept-node level, optimal review interval prediction, longitudinal decay curves per student per concept, identification of "high decay" concepts that need redesigned instruction. All useful at scale; none required to start.

---

## 8. Open Questions and Research Gaps

**The optimal-spacing function for classroom contexts.** Cepeda et al. 2008's temporal ridgeline gives a useful approximation; the precise function for school-paced material is not settled. Practitioner-actionable rule: any non-zero spacing beats massing.

**FSRS performance in classroom contexts.** The algorithm is well-validated on Anki user data; controlled classroom RCTs are thin. The chapter should mention FSRS as the current state-of-the-art platform-side scheduler and acknowledge the academic literature is still consolidating.

**AI's effect on Y6 specifically.** Predicted (steeper decay for AI-assisted students); empirically thin in controlled studies. Bastani 2025 is consistent but did not measure a full decay curve.

**Item-difficulty matching for embedded decay probes.** The chapter should give the practitioner a workable rule (use items from the same bank, prefer items with similar past-class success rates) and acknowledge that perfect difficulty-matching is a measurement-design problem.

**Whether the "long permastore plateau" generalizes beyond Bahrick's domains.** Bahrick's work covers Spanish vocabulary and mathematics; whether all durably-learned material has a plateau is less clear. Practitioner translation: long-tail retention is achievable, the specific shape varies by material.

**The "AI-as-study-tool" failure mode.** Students who use AI to *answer* practice items (rather than to *retrieve* them) lose the testing-effect benefit. This is a structural problem with AI access during practice. The chapter should mention it and connect to Chapter 11's implementation discussion.

**GLP / Frictional / seven-signal flag.** The Y6 signal as a composite operationalization (immediate, short-delay, long-delay performance with derived decay rate) is a Humanitarians AI specification. The component literature (Bjork, Cepeda, Roediger-Karpicke, Adesope) is foundational, replicated, and durable.

---

## 9. Sourcing Notes

Anchor citations are durable: Ebbinghaus 1885, Bjork & Bjork 1992, Cepeda et al. 2006/2008, Roediger & Karpicke 2006, Karpicke & Roediger 2008, Adesope/Trevisan/Sundararajan 2017, Bahrick 1984. These are foundational, replicated, and not subject to AI-era obsolescence.

The FSRS citation should be handled carefully: cite the GitHub repository (github.com/open-spaced-repetition) and Jarrett Ye's blog work, and explicitly flag that the academic literature is thin. The chapter should not present FSRS as having the same evidentiary weight as Bjork or Cepeda.

The SuperMemo / Wozniak citation is similar — primarily practitioner literature, supermemo.guru, the 1990 thesis and 1994 paper. Cite for completeness; don't lean.

The Make It Stick / Brown-Roediger-McDaniel (2014) book is not in the anchor set but should appear in a "further reading" footnote — it's the most accessible practitioner translation of the testing-effect literature and many readers will have encountered it.

Cross-chapter overlap: this file shares Bjork-Dunlosky-Kornell 2013 (referenced) and Karpicke & Roediger 2008 with Chapter 6 (Y4). The chapter should not re-introduce these in detail — refer back where appropriate. The Bjork & Bjork 1992 storage/retrieval distinction also connects to Chapter 2's introduction of the same concept; the chapter should explicitly call back.

Across the four chapters (5–8): minimal citation overlap is appropriate and reflects the genuinely distinct intellectual traditions each Y-signal draws on. Y3 = cognitive psychology of transfer. Y4 = metacognition. Y5 = sociocultural / dialogic education. Y6 = memory and learning sciences. The seven-signal architecture is partly justified by exactly this — different signals draw on different research traditions, which is why their combination produces independent information.
