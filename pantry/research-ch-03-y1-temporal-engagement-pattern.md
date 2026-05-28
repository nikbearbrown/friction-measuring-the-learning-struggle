# Research: Chapter 03 — Y1: Temporal Engagement Pattern
## Friction Traces: Measuring the Struggle That Proves the Learning

**Chapter one-line:** Genuine engagement distributes time according to difficulty. Borrowed certainty distributes time according to output length. The correlation between the two is the signal.
**Research date:** 2026-05-27

---

## 1. Primary Sources

### Foundational papers and texts

- **Sweller, J. (1988). Cognitive load during problem solving: Effects on learning. *Cognitive Science*, 12(2), 257–285.** Cognitive load theory; intrinsic load is the load inherent in the relationships among the material's elements ("element interactivity"). The chapter's mechanistic anchor: harder material requires more processing time *when the student is doing the processing*.
- **Sweller, J., van Merriënboer, J. J. G., & Paas, F. G. W. C. (1998). Cognitive architecture and instructional design. *Educational Psychology Review*, 10(3), 251–296.** The canonical CLT statement; intrinsic, extraneous, germane load.
- **Sweller, J., van Merriënboer, J. J. G., & Paas, F. (2019). Cognitive architecture and instructional design: 20 year update. *Educational Psychology Review*, 31(2), 261–292.** Updated CLT including element interactivity as the operational measure of intrinsic load.
- **Karweit, N. (1984). Time-on-task reconsidered: Synthesis of research on time and learning. *Educational Leadership*, 41(8), 32–35.** Foundational time-on-task synthesis: allocated time ≠ engaged time ≠ academic learning time. The original argument that gross time-on-task is a weak learning predictor; *quality* of time matters.
- **Berliner, D. C. (1990). What's all the fuss about instructional time?** In M. Ben-Peretz & R. Bromme (Eds.), *The nature of time in schools* (pp. 3–35). Teachers College Press. The "academic learning time" framework — time engaged with material at appropriate difficulty.
- **Plant, E. A., Ericsson, K. A., Hill, L., & Asberg, K. (2005). Why study time does not predict grade point average across college students: Implications of deliberate practice for academic performance. *Contemporary Educational Psychology*, 30(1), 96–116.** Hours studied does not predict GPA; *deliberate practice* time does. Strongest single piece of evidence that *gross* time is the wrong measure.
- **Henrie, C. R., Halverson, L. R., & Graham, C. R. (2015). Measuring student engagement in technology-mediated learning: A review. *Computers & Education*, 90, 36–53.** LMS engagement measurement review — clickstream/dwell-time validity. The "what clickstream data actually measures" critique.
- **Wise, A. F., & Cui, Y. (2018). Learning communities in the crucible of change: Environmental harshness and group structure predict the survival of student discussion threads. *Computers & Education*, 125, 30–43.** Wise's broader work on the *interpretation* problem in learning analytics — what behavioral traces *mean* depends on context.
- **Ericsson, K. A., & Simon, H. A. (1993). *Protocol analysis: Verbal reports as data* (Revised ed.). MIT Press.** The think-aloud method; the practitioner-level alternative to clickstream. (Original 1980 *Psychological Review*: "Verbal reports as data.")
- **Chi, M. T. H. (1997). Quantifying qualitative analyses of verbal data: A practical guide. *Journal of the Learning Sciences*, 6(3), 271–315.** Bridge between protocol analysis and classroom-feasible coding.

### Key empirical cases
- **Soares et al.** on Canvas LMS analytics validity — Canvas time-on-task vs. actual engagement; multiple studies converge on weak predictive validity of gross dwell.
- **Plant et al. 2005** (above) — the GPA-time disconnect.
- **AI-assisted work and time-difficulty correlation** — *the literature is genuinely thin*. Flag explicitly. Bastani 2025 hints at the pattern but does not analyze time-on-difficulty distribution. Stadler 2024 may have time data; verify. Lehmann 2024 may also have time data.

---

## 2. The Core Concept — State of the Field

### What is settled
- **Gross time-on-task is a weak learning predictor.** Karweit, Berliner, Plant et al. — converged finding across forty years.
- **Engaged time at appropriate difficulty is a stronger predictor.** Berliner's "academic learning time" — time spent on material the student is *productively struggling with* — predicts learning gains.
- **Cognitive load theory's prediction** that harder material requires more processing time *when the load is genuine* is uncontested at the theoretical level.
- **LMS dwell time is a noisy proxy.** Henrie et al. — dwell time correlates weakly with engagement, near-zero with learning when the platform doesn't distinguish active from passive presence.

### What is disputed
- **How to operationalize "engaged time" without a platform.** Think-alouds are gold standard but expensive. Self-report is biased. Observational coding is labor-intensive. The practitioner-feasibility question is open.
- **Whether element-interactivity can be reliably scored** by instructors in the field. Sweller's group has produced rubrics; classroom adoption is rare.
- **Whether AI-assisted work flattens the time-difficulty correlation in the way the GLP framework predicts.** *No published direct evidence yet.* The structural argument is strong; empirical confirmation is the framework's open empirical bet.

### What has changed recently (last 5 years)
- Process-mining approaches to LMS clickstream (Bogarín 2018; Saint et al. 2020) have improved beyond simple dwell time.
- Wise's group (Simon Fraser) has pushed for *theory-driven* learning analytics — interpret traces in light of learning theory, not in isolation.
- The Bastani 2025 finding raised the stakes for the time-on-task validity question. If students with AI access produced higher engagement metrics but lower learning, then *what the engagement metrics were tracking* is exactly the question Y1 addresses.

---

## 3. Application Domain Examples

1. **High school chemistry — stoichiometry problem set.** Pre-AI, students predictably bunched time on limiting-reagent problems (the hard ones). Post-AI, time distribution flattens — students spend the same time on every problem regardless of difficulty. The annotation exercise in the chapter's worked example operationalizes this for the practitioner.
2. **Middle school math — fraction operations.** Students who struggle with division-of-fractions show predictable time-bunching there. AI-assisted students show uniform pacing. The teacher can see this without a platform by asking students to log start/stop times on each problem.
3. **Higher ed — undergraduate economics problem sets.** PDF problem sets in Canvas — time-stamped submissions of partial work reveal whether time was spent on hard concepts.
4. **Nursing — medication calculation practice.** Students traditionally spend more time on dosage-conversion problems. AI-assisted shortcuts produce uniform timing; the time-difficulty correlation collapses.
5. **AP physics — kinematics graphing.** Conceptual questions (interpret a position-time graph) typically take longer than computational questions for genuine engagement. Borrowed certainty inverts the pattern — computational questions, requiring more output, take longer because the AI produces more text.

---

## 4. The Book's Thesis Connection

Y1 is the *first* of the seven signals and the chapter that introduces the **borrowed certainty signature** as a recurring construct. The argument structure:

1. **The neurobiological prediction.** Cognitive load theory predicts that genuine processing of difficult material requires sustained working-memory engagement — observable as time. The harder the material's element-interactivity, the more processing time required.
2. **The genuine signature.** Time-on-task correlates *positively* with item difficulty for a given student. The correlation is the signal — not the absolute time.
3. **The borrowed certainty signature.** When an AI does the processing, time-on-task no longer correlates with the *student's* cognitive load — it correlates with the *AI's output length*, which tracks the *displayed* complexity (typically the prompt length) rather than the *conceptual* difficulty.
4. **The seven-signal architecture point.** Y1 is *necessary but insufficient* — a student could fake Y1 by deliberately slowing down on hard items. But faking Y1 *requires knowing which items are hard*, which itself is a piece of the learning the student is trying to fake. This previews the ensemble argument in Ch 10.
5. **Independence from artifact quality.** A student can produce a polished artifact with flat time-difficulty distribution. The artifact says "competent." Y1 says "did not process the difficulty distribution." Y1 is the first *independent* evidence stream.

The chapter must establish Y1 as *concrete, observable, and worth the trouble* — because the reader's belief in the *rest* of the framework depends on the first signal being legible.

---

## 5. The AI Wayback Machine — Candidate Figures

**Candidate 1: David Berliner (b. 1938, US).** Arizona State / formerly UWisc; academic learning time framework; lesser-known than his contemporaries but the architect of the *quality-of-time* argument. Sample prompt: "David, you argued that 'time-on-task' was the wrong unit — that what mattered was time engaged with material at appropriate difficulty. Forty years later, students are spending hours with AI tutors and learning less than students who spent fewer hours alone. What would you say is being measured?" *Diversity flag:* white male American. Save Berliner only if the chapter wants the practitioner-recognizable name.

**Candidate 2: Yrjö Engeström (b. 1948, Finland).** Cultural-historical activity theory; *Learning by Expanding* (1987). Non-Anglo, alive, accessible (he writes for practitioners as well as researchers). His framing — that learning is an *activity* embedded in cultural-historical tools — directly anticipates the "what does it mean when the tool does the thinking?" question. Sample prompt: "Yrjö, in activity theory the tool mediates between the subject and the object. When the tool is a generative AI that produces the object directly, what happens to the subject's activity — and to learning?" **Preferred for non-Anglo diversity slot.**

**Candidate 3: Anders Ericsson (1947–2020, Sweden/US).** Deliberate practice; the chapter's most natural fit; popularized by Gladwell ("10,000 hours") but the actual finding is about *quality of practice*, not quantity. Famous; the reader may have heard the misquoted version. Sample prompt: "Anders, your 10,000-hour figure was famously misunderstood — you weren't talking about gross hours, you were talking about *deliberate practice*: effortful work at the edge of current ability, with feedback. What is the deliberate-practice version of a student writing an essay with an AI?" *Diversity flag:* white male, Swedish-American. Compromise candidate.

**Diversity assessment (running tally):** Ch 1 Resnick (woman), Ch 2 Maguire (woman). Ch 3 should swing to a non-Anglo male — **Engeström is the preferred selection** (Finnish; satisfies non-Anglo; aliveness allows for the imagined-conversation framing). Saves Ann Brown / Ni for Ch 4.

---

## 6. Pedagogical Delivery Research

The reader (HS science chair / instructional designer) needs:

1. **A working operational definition** of "time-difficulty correlation" she can hold in her head without arithmetic. The chapter should give her a *pattern recognition* tool: "if a student spends about the same time on every problem regardless of how hard the problem is, that's a flat correlation." The numerical correlation can come later.
2. **Permission to ignore LMS time data she has been told is meaningful.** Canvas reports time-in-page. Most instructors have been encouraged to look at these reports. The chapter should be direct: Canvas time-in-page is not Y1, and the reasons (passive dwell, multi-tabbing, ambient background) should be named.
3. **A specific small move she can make tomorrow.** The annotation exercise (check easy / question mark hard) from the TIKTOC worked example. Single-class implementation, zero technology required. The first "process-based assessment" the reader will actually do.

Tone rule (TIKTOC Part 9): the chapter is not an introduction to cognitive load theory. It is a working tool for the reader. CLT appears as the *reason* the pattern exists, briefly, then yields to the practitioner-facing implementation.

---

## 7. Representation and Display Research

**Y1–Y7 chapters require a "How to observe without a platform" section.** For Y1 specifically:

**Low-cost classroom observation methods for Y1:**

- **The annotation exercise.** Students mark each problem as easy / hard *as they go*. Compares annotation pattern to test performance and to time logs. The "did the student perceive the difficulty distribution?" question. Cost: zero. Already in the TIKTOC worked example.
- **The start/stop log.** Students record the time they start and end each problem on a paper sheet attached to the problem set. Aggregated across the class, the time-difficulty correlation becomes visible. Cost: 30 seconds per problem; one Excel column per item.
- **Think-aloud sampling.** Two or three students per week perform a brief think-aloud while solving a problem set in the instructor's presence. The think-aloud reveals whether the student is *processing* the hard problems or pattern-matching. Cost: 15 minutes per student per sampling event. Ericsson & Simon protocol is overkill; Chi 1997 has classroom-feasible coding schemes.
- **The version-history check.** For digital work, the document revision history (Google Docs, Word version control) shows time spent in document. Pauses on hard concepts produce visible gaps; uniform smooth writing without pauses produces a flat profile. Cost: instructor time per document, but the data exists without new collection.
- **Draft timestamps if students submit work in stages.** Required submission of an outline at T1, draft at T2, final at T3. Time between submissions reveals where the work happened.

**What a platform adds:** sub-paragraph clickstream granularity; automatic difficulty-time correlation per item; the Y1 score computed across many problems with confidence intervals.

**Suggested figures:**
- **The difficulty-time scatter, two panels.** Genuine: positive slope. Borrowed certainty: flat. Single most important visual for the chapter.
- **The annotation grid.** Five problems, each student's annotation pattern (check/question-mark) against the test's actual difficulty ranking. Visible alignment for genuine students; visible misalignment for borrowed-certainty students.
- **Canvas time-in-page vs. Y1.** Side-by-side: what Canvas reports vs. what Y1 measures. The "engagement analytics measure the wrong thing" visual.

Avoid: clickstream waterfall diagrams (research-paper convention; loses the practitioner).

---

## 8. Open Questions and Research Gaps

- **No published direct evidence of the time-difficulty correlation collapse under AI assistance.** This is the framework's empirical bet. Bastani 2025 has time data — does the dataset support an item-level reanalysis? Flag for the GLP preprint.
- **Self-reported difficulty perception (the annotation exercise) — how reliable is it?** Some literature on student difficulty perception (e.g., judgments of learning, JOLs) exists; needs review to confirm it is *useful enough* for the annotation method.
- **Whether the time-difficulty correlation works for *creative* assignments** (essays, design projects) where "difficulty" is harder to operationalize. The chapter examples are problem-set-heavy. The book should acknowledge this limitation.
- **The "students who deliberately slow down on hard items to fake Y1" question.** Y1 alone is insufficient; gaming Y1 requires knowing which items are hard, which is itself a signal. Ch 10 will return to this; the chapter should foreshadow.

---

## 9. Sourcing Notes

- Sweller 1988 / 1998 / 2019 — *Cognitive Science*, *Educational Psychology Review*. The 2019 update is the most current operational statement.
- Karweit 1984, Berliner 1990 — both available through educational research databases; Berliner's piece is in an out-of-print edited volume; ILL likely needed.
- Plant et al. 2005 — *Contemporary Educational Psychology*; widely cited.
- Henrie et al. 2015 — *Computers & Education*; open access via institutional repositories.
- Ericsson & Simon 1993 — MIT Press book; Chi 1997 (*Journal of the Learning Sciences*) is the practitioner-friendlier alternative.
- **Cross-chapter overlap with Ch 2:** Sweller's CLT returns from Ch 2's mention; this chapter is its operational deployment. Establish in Ch 2, deploy in Ch 3.
- **Cross-chapter overlap with Ch 4:** Y2's reward-prediction-error mechanism shares the same *type* of argument structure ("neurobiological event → behavioral consequence"). The reader's training begins in Ch 3; she should recognize the pattern when Ch 4 arrives.
- **Cross-chapter overlap with Ch 8 (Y6):** Time and decay both involve longitudinal observation; the data collection routine started for Y1 can serve Y6 too. Note this for the practitioner.
- **Proprietary framework flag:** Y1 (Temporal Engagement Pattern) is Humanitarians AI's term. The component-mechanism literature (CLT, time-on-task, deliberate practice) is the chapter's evidentiary backbone. The framework label sits on top.
