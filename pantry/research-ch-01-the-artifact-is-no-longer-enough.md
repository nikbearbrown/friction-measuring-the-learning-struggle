# Research: Chapter 01 — The Artifact Is No Longer Enough
## Friction Traces: Measuring the Struggle That Proves the Learning

**Chapter one-line:** The reader learns that the decoupling of artifact from process is permanent, why detection cannot solve it, and what the right question actually is.
**Research date:** 2026-05-27

---

## 1. Primary Sources

### Foundational papers and texts

- **Bastani, H., Bastani, O., Sungu, A., Ge, H., Kabakci, O., & Mariman, R. (2025). Generative AI without guardrails can harm learning: Evidence from high school mathematics. *Proceedings of the National Academy of Sciences (PNAS)*.** N ≈ 1,000 Turkish high school students across 3 cohorts (9th–11th grade), 4 weeks, pre/post controlled with random within-classroom assignment. Three conditions: standard GPT-4 ("GPT Base"), tutor-guarded GPT-4 ("GPT Tutor"), no AI. On practice problems with AI, the GPT Base students improved 48% over control; GPT Tutor students improved 127%. **On the unassisted exam, GPT Base students scored 17 percentage points *worse* than no-AI controls; GPT Tutor students were statistically indistinguishable from controls.** Note correction: 10.1073/pnas.2518204122 (administrative correction; conclusions unchanged). The book's anchor finding.
- **Kestin, G., Miller, K., McCarty, L., Callaghan, K., & Deslauriers, L. (2024/2025). AI Tutoring Outperforms Active Learning. *Scientific Reports* / Harvard ScD working paper (Spring 2024 study, posted Research Square 2024).** Harvard physics RCT: 194 undergraduates, AI tutor (PEAR — Physics Educator AI Resource) vs. high-quality in-class active learning. The AI-tutored students learned **more than twice** as much in the same time and reported higher engagement. Critical contrast with Bastani: this AI was *prompt-engineered with pedagogical guardrails* (Socratic scaffolding, no full solutions, calibrated hints).
- **Bjork, R. A. (1994). Memory and metamemory considerations in the training of human beings.** In J. Metcalfe & A. Shimamura (Eds.), *Metacognition: Knowing about knowing* (pp. 185–205). MIT Press. The performance/learning distinction.
- **Soderstrom, N. C., & Bjork, R. A. (2015). Learning versus performance: An integrative review. *Perspectives on Psychological Science*, 10(2), 176–199.** Synthesis of the distinction.
- **Sadasivan, V. S., Kumar, A., Balasubramanian, S., Wang, W., & Feizi, S. (2023). Can AI-generated text be reliably detected? arXiv:2303.11156.** Theoretical and empirical argument that as generation quality rises toward human-text indistinguishability, the AUROC of *any* detector falls toward 0.5. Paraphrase and recursive-paraphrase attacks crater commercial detectors.
- **Liang, W., Yuksekgonul, M., Mao, Y., Wu, E., & Zou, J. (2023). GPT detectors are biased against non-native English writers. *Patterns*, 4(7), 100779.** 7 commercial detectors misclassified 61% of TOEFL essays from non-native writers as AI-generated; near-zero false positive on US-born 8th graders. The equity-breaking finding.
- **Bender, E. M., Gebru, T., McMillan-Major, A., & Shmitchell, S. (2021). On the dangers of stochastic parrots: Can language models be too big? *FAccT '21*.** Fluency without understanding — the conceptual basis for the fluency trap.
- **Mollick, E. R., & Mollick, L. (2023). Assigning AI: Seven approaches for students, with prompts. SSRN.** Wharton practitioner-facing taxonomy.

### Key empirical cases
- Bastani 2025 (above) — primary anchor
- Kestin 2025 (above) — contrast / guardrail case
- Lehmann, Cornelius, & Sting (2024) "AI Meets the Classroom" (working paper) — Swiss higher-ed, suggests *user-quality* moderation: stronger students gain, weaker students harmed
- Stadler et al. (2024) on ChatGPT and academic essay quality — quality up, learning down in the same students

---

## 2. The Core Concept — State of the Field

### What is settled
- Generative AI systems can produce artifacts (essays, code, problem solutions, clinical notes) indistinguishable from competent student work at increasingly low cost.
- AI detection tools have unacceptable false-positive rates against non-native English writers (Liang 2023) and against any prose that has been paraphrased or lightly edited (Sadasivan 2023).
- The performance/learning distinction (Bjork) — high immediate performance does not predict durable retention — is a foundational finding in learning science with decades of replication.

### What is disputed
- Whether AI tutoring helps or harms learning in any blanket sense. Bastani and Kestin together demonstrate the answer is *it depends on the wrapper*, not the model.
- Whether detection accuracy can be recovered through watermarking or statistical fingerprinting. Theoretical impossibility results (Sadasivan) are contested by watermarking advocates (Kirchenbauer 2023).
- The size and durability of AI-assisted learning effects across populations and disciplines. Most existing studies are short (≤ 1 term) and narrow (one subject).

### What has changed recently (last 5 years)
- 2020–2022: GPT-3 raised the ceiling on automatic text generation; AI detection was assumed feasible.
- 2023: ChatGPT public release; first wave of detector deployment (Turnitin AI, GPTZero); Liang and Sadasivan published; field began acknowledging detection's structural limits.
- 2024: Bastani's preprint; Kestin's RCT; pivot in policy discourse from "detect-and-punish" toward "assessment redesign."
- 2025: Bastani in PNAS; Mollick's framework adopted in K-12 PD; emerging consensus that *process evidence is required* — but no shared framework for what process evidence is.

---

## 3. Application Domain Examples

1. **High school mathematics (Bastani).** 9th–11th grade Turkish students used GPT Base on practice problems, looked engaged, scored worse on the closed-book exam. The classroom-level finding the book's primary reader (HS science chair) will recognize.
2. **Harvard undergraduate physics (Kestin).** Same model, scaffolded prompt, opposite outcome — the contrast that makes the book's "right wrapper" point.
3. **First-year writing (multiple US universities).** Faculty report polished, structurally sound essays from students whose in-class writing is incoherent. Anecdotal but pervasive; the "fluency trap" the chapter must explain.
4. **Nursing pharmacology.** Students submit accurate drug-interaction notes on take-home cases, then cannot apply the same reasoning on closed-book clinical reasoning exams (matches Bastani structure in clinical education).
5. **AP Biology lab reports.** Discussions/conclusions sections have become uniformly fluent across student ability levels — the variance compression diagnostic.

---

## 4. The Book's Thesis Connection

Chapter 1 establishes the *premise* the seven-signal architecture exists to address. The decoupling argument runs:

1. Pre-2023, artifact quality was a *valid proxy* for cognitive process because producing the artifact required the process.
2. Generative AI provides a *second causal pathway* to the artifact that bypasses the process.
3. Therefore artifact quality is no longer a sufficient statistic for learning.
4. Detection attempts to restore artifact validity by asking "did the human type this?" This is the wrong question — and Sadasivan/Liang show it is also a question that cannot be answered reliably.
5. The right question is "did the human *learn* this?" — which is answerable through evidence the *learning process* itself leaves behind. This is the entry point for the GLP framework.

The chapter does not introduce the seven signals. It opens the door. The "borrowed certainty" language that runs through Chapters 3–9 first appears here: a student who has the artifact but not the learning has *borrowed certainty* from a system that cannot itself know.

---

## 5. The AI Wayback Machine — Candidate Figures

**Candidate 1: Lauren Resnick (1936–2022).** Pittsburgh, situated cognition and assessment reform. Lesser-known than Bloom but the architect of the 1980s–90s argument that assessment must measure *thinking* not *answers*. Satisfies: woman, deceased (no PR risk), strong educational pedigree, accessible writing, *directly* relevant to the chapter's "right question" pivot. Sample prompt: "Lauren, when you argued in *Education and Learning to Think* (1987) that assessments should evidence reasoning rather than answers, you were facing standardized testing, not generative AI. What does your argument look like when the answer key itself can write the answer?"

**Candidate 2: Ference Marton (b. 1939, Sweden).** Phenomenography; the deep/surface learning distinction (1976). Non-Anglo, accessible, alive. Satisfies the non-Western preference imperfectly (Sweden is Western, but non-Anglo). His finding — that the same content produces qualitatively different *conceptions* depending on the learner's approach — anticipates the artifact/process decoupling. Sample prompt: "Ference, your students who memorized a text produced summaries; your students who sought meaning produced reorganizations. Both could pass a test. How is the situation today different from yours in 1976?"

**Candidate 3: Grant Wiggins (1950–2015).** Understanding by Design, *authentic assessment*. Famous but accessible; the practitioner reader will recognize him. Use only if Resnick is unavailable or feels redundant. Diversity flag: white male American — *do not double up* with another white male American across Ch 1–4.

**Diversity note across Ch 1–4:** Resnick (woman, American) covers gender for Ch 1. Save Ann Brown (woman) or Eleanor Maguire (woman) for Ch 2/4. Marton (non-Anglo) keeps the non-Anglo slot open for Ch 3 (Engeström, also Nordic) or Ch 4 (Ni, Hong Kong).

---

## 6. Pedagogical Delivery Research

The high school department chair reader needs three things from this chapter:

1. **Permission to stop fighting detection.** She has tried Turnitin AI. It has failed her. She needs an authoritative, citable reason to stop spending political capital on a losing strategy. Liang 2023 (false positives against non-native English writers — a legal and equity liability) is the strongest practitioner-facing case.
2. **A name for what she already knows.** She has seen the fluency trap. She does not have language for it. The chapter gives her *fluency trap*, *decoupling*, and *the wrong question* — three phrases she can use in faculty meetings.
3. **The Bastani story told as a measurement story, not a cheating story.** The reader's defensive crouch is around accusation. If the chapter is framed as "students cheat," she will brace. If it is framed as "the platform was measuring the wrong thing," she leans in.

Delivery sequence (TIKTOC Part 9 confirmed): opening case → causal chain → why detection fails → the right question → preview of seven signals.

---

## 7. Representation and Display Research

Chapter 1 is *not* a Y1–Y7 chapter, so it does not require a "How to observe without a platform" section. But the chapter must end with a *gestural commitment* that observation is possible — otherwise the reader closes the book demoralized.

Suggested figures:
- **The two-pathways diagram.** Pre-2023: Genuine Learning → Cognitive Process → Artifact (one arrow). Post-2023: same chain *plus* AI Generation → Artifact. Visual emphasizes the artifact has two upstreams. The book's load-bearing image.
- **The Bastani triple-bar.** Practice performance vs. exam performance for the three conditions. Engagement-learning gap visible at a glance. Adapt directly from the PNAS figure but redraw with clearer labels for K-12 audience.
- **The fluency trap example.** Side-by-side: one polished AI-written paragraph and one rougher genuine-student paragraph on the same prompt. Visual proof that polish is not signal.

For a textbook for practitioners, *avoid* effect-size forest plots and confidence-interval ribbons. Use simple two-bar comparisons with the magnitude annotated in plain language ("17 points lower").

---

## 8. Open Questions and Research Gaps

- **Is Bastani-style decoupling visible at the level a single teacher can detect in her own class, or only at population scale?** The TIKTOC Open Question 3 — does a K-12-level story land better than the Bastani Turkish RCT? Likely yes; the book may need a composite classroom story alongside Bastani.
- **What is the right tier of evidence for the practitioner reader?** Bastani is one RCT in one country in one subject. The book's credibility depends on 2–3 supporting findings at the same evidentiary tier (TIKTOC Part 10 explicit risk). Lehmann 2024 and Stadler 2024 are candidates but need vetting.
- **The "harder to game" claim for process evidence over artifact evidence** — is there any direct empirical comparison, or is this still a structural argument? (Likely still structural; flag.)
- **No outside-of-Humanitarians-AI literature on the GLP framework itself** — the book must source the *components* from established learning science and assemble the framework as a synthesis claim.

---

## 9. Sourcing Notes

- Bastani et al. 2025 — public PNAS publication; full study design, effect sizes, and correction (10.1073/pnas.2518204122) are citable. Use the corrected version.
- Kestin et al. 2025 — *Scientific Reports* publication recommended over the earlier Research Square preprint; verify final venue before citation.
- Sadasivan 2023 and Liang 2023 — public arXiv / *Patterns*. Both have been heavily cited (>1000 each as of 2026).
- Bjork 1994 chapter — printed in *Metacognition* (Metcalfe & Shimamura, MIT Press); request through library ILL if not already on hand.
- Stochastic Parrots — public, freely available.
- Mollick & Mollick — SSRN; ensure the version cited matches the 2023 paper, as the Mollicks have updated multiple times.
- **Cross-chapter overlap:** Bastani and Bjork return in Ch 2, Ch 3, Ch 6, Ch 8. Establish full citations and standard short-form references in Ch 1 to avoid restating in later chapters.
- **Proprietary framework flag:** GLP, Frictional, seven-signal architecture — Humanitarians AI internal. No outside primary sources exist or will exist for these. Component-mechanism literature (cognitive load, prediction error, ZPD, spacing effect) is abundant and must do the heavy lifting.
