# Chapter 8 — Y6: Retrieval Strength Decay Signature

*Genuine learning shows the spacing effect — performance holds up better after distributed practice than after massed practice. Borrowed certainty shows monotonic decay. The decay curve shape is the signal.*

---

## Opening: the three-week gap

Two students score 85% on a quiz the day after the unit ends.

Three weeks later — no announcement, no review session, no extra study — the instructor gives a short five-item quiz on the same material. Student A scores 78%. Student B scores 42%.

Same content. Same teacher. Same starting score. Identical immediate performance.

The quiz score on day one was not sufficient evidence. The artifact lied. Both students looked equally prepared. What the artifact could not show is the *shape of what each student walked away with*. Student A walked away with storage. Student B walked away with a fluent moment.

The chapter is about the difference between those two students. The difference is invisible on a single test. It is visible — cleanly, robustly, in data that already exists — in the decay curve.

This is also the chapter where Chapter 2's storage/retrieval distinction earns its keep. We introduced it abstractly there. Y6 is the chapter where it becomes operational.

---

## What Retrieval Strength Decay Signature measures

**Y6 — Retrieval Strength Decay Signature (RSDS)** [Humanitarians AI internal framework] is the sixth friction-trace component. It measures three things about a student's performance on the same material at three different time points: immediate, short delay, and long delay. The diagnostic is the **shape of the decay curve** — and, when the curriculum permits, the **spacing benefit**, which is the improvement that comes from distributing practice across time rather than massing it.

Some vocabulary, brought up from Chapter 2. **Retrieval strength** = how accessible something is *right now*. Fluctuates with recency, context, cues. **Storage strength** = how thoroughly something is encoded. Slow-changing, effectively monotonic. The key counter-intuitive result, from **Bjork and Bjork (1992)** — the New Theory of Disuse — is that *conditions which produce high retrieval strength can produce lower gains in storage strength*. Cramming, restudy, fluent AI explanation: high retrieval strength on the day of the test, low storage strength a month later. Spaced retrieval practice: lower retrieval strength on the day of the test, much higher storage strength a month later.

The artifact-based assessment regime is structurally insensitive to this distinction. A quiz given on Tuesday measures retrieval strength on Tuesday. The decay curve over three weeks measures storage strength. You cannot get the second signal from a single quiz, no matter how well-designed.

Two more pieces of vocabulary. The **forgetting curve** (Ebbinghaus 1885) is the empirical shape of retention loss over time — roughly exponential, with a fast initial drop and a slower later decline. Every textbook reproduces it. The **spacing effect** (Cepeda et al. 2006, meta-analyzing 317 experiments) is the finding that distributing practice across time produces dramatically better long-term retention than massing the same total practice time into one session. It is one of the most replicated findings in cognitive psychology and not seriously contested.

**Practitioner implication:** if you only measure performance once, you are measuring retrieval strength and reporting it as if it were learning. The decay curve is the more honest measure of what the student walked away with.

---

## Where the decay-shape difference comes from

Why do two students with the same immediate quiz score decay at different rates?

The single cleanest empirical demonstration is **Roediger and Karpicke (2006)**. Two groups of students studied a brief science passage. Group 1 restudied the passage four times. Group 2 studied it once, then attempted to retrieve it three times — recall what they had read, write it down, no looking back at the passage. On an immediate test (five minutes later), the restudy group scored slightly higher. On a one-week test, the retrieval group held substantially more. The crossover happens inside a single two-condition study. Same material. Different decay curves.

The follow-up by **Karpicke and Roediger (2008)** sharpened the point. Repeated retrieval produced 80% retention at one week; repeated restudy produced 33%. Same time-on-task. Same starting material. Two-and-a-half-fold difference in storage at one week.

The mechanism is exactly the one Chapter 6 hinted at. Retrieval practice produces failures. The student tries to remember, almost remembers, sometimes fails, sometimes succeeds. Each failure is a cue: *not yet stored*. The student now restudies the specific items they failed to retrieve. The cycle drives storage. Restudy does not produce failures. The student reads, the words feel familiar, the cue says *stored*, and the cycle skips. High retrieval strength on the day. Low storage strength later.

This is also where AI-assisted study has its mechanistic problem. The student asks the AI for an explanation. The AI provides a clean, fluent, complete explanation. The student reads it. The reading feels successful. No retrieval is attempted. No failure occurs. No storage is built. The student emerges with retrieval strength (the material was just in front of them, fluently presented) and almost no storage strength.

A second mechanism is **the spacing effect itself**. Cepeda and colleagues (2008) showed a *temporal ridgeline*: the optimal gap between practice sessions scales with the desired retention interval, at roughly 10–20%. If you want students to remember in six months, space practice three to six weeks apart. If you want them to remember in two weeks, space practice one to three days apart. The precise function is contested in detail, but the qualitative finding is settled: any non-zero spacing beats massing. Massed practice produces immediate performance. Distributed practice produces durable storage.

A third piece. **Bahrick (1984)** ran a cross-sectional study of Spanish retention 0–50 years after the original course. He found a stable "permastore" plateau after about three to six years — material that survived that long was likely to survive indefinitely. The shape of the long-term decay curve is a real property of how something was learned. Surface familiarity does not produce permastore. Schema-based learning, with retrieval practice, does. Whether all genuinely-learned material has a permastore plateau is less settled — Bahrick's work covers Spanish vocabulary and mathematical principles primarily — but the existence of long-tail retention for *some* material is established.

A meta-analytic anchor: **Adesope, Trevisan, and Sundararajan (2017)** synthesized 118 practice-testing studies (15,427 participants). The testing effect produces an effect size of approximately *g* = 0.6, large by educational research standards, and it holds across age groups, materials, and delay intervals.

**Practitioner implication:** the decay curve shape is the mechanistic residue of how the student studied. Retrieval practice produces a flatter decay. AI-assisted "study" produces a steep one.

---

## The genuine Y6 signature

When a student's learning is genuine — when retrieval practice has happened, when spacing has had time to do its work — the decay-curve pattern is identifiable.

**Slower decay.** Performance at long delay is substantially better than what a forgetting-curve prediction from immediate performance would suggest. The drop from immediate to two-week to six-week tests is modest. The curve flattens.

**Spacing benefit present.** When the practitioner has the data — and many do, structurally, because most curricula contain some natural spacing — students who experienced distributed practice outperform students who experienced massed practice on long-delay items, even when immediate-performance scores were similar.

**Performance on legacy items holds up.** This is the practitioner-side translation. Items from material covered three to six weeks ago, embedded into a current quiz unannounced, are answered at rates close to the rates achieved when the material was current. The student has not forgotten the way the simple forgetting curve would predict.

**Long-tail retention shows up.** On end-of-term cumulative assessments, performance on early-unit material is not catastrophically worse than performance on late-unit material. Some loss, yes. Cliffhanger drop-off, no.

**Practitioner implication:** the genuine signature is a curve that bends gently. Look for the bend.

---

## The borrowed-certainty Y6 signature

The pattern is structurally clean and emerges fastest in classrooms where AI-assisted study is widespread.

**Monotonic, steep decay.** Performance collapses between immediate and short-delay assessments and is near floor by long-delay. The curve is closer to a cliff than a slope.

**No spacing benefit.** Even when the curriculum provides some natural spacing, students do not show the predicted retention boost. The reason is that what they did during the spacing intervals was not retrieval. They re-asked the AI. The AI re-delivered fluent explanation. No storage was built between sessions.

**Decay-probe performance collapses by mid-term even when current-unit performance stays high.** This is the most diagnostic single observation. A student looks fine on the new material. The new material is in front of them, the AI is helping, the immediate quiz performance is fine. But ask a question from four weeks ago — same student — and they cannot recover the answer. The storage was never there.

**Performance collapses entirely without continued AI access.** A student who has been borrowing certainty all term, given a closed-book final, scores far below their term-average artifact performance would predict. This is the Bastani 2025 pattern at the individual level [verify] — the engagement metrics were strong, the immediate performance was strong, and the unassisted exam collapsed.

The Bastani 2025 study itself is the strongest available evidence for the Y6 borrowed-certainty pattern at the population level, though it is one RCT in one country in one subject and the chapter is honest about that. Bastani measured exam performance after AI exposure; the exam-performance drop is consistent with the steep-decay prediction but the study did not measure a full decay curve.

**Practitioner implication:** borrowed certainty's Y6 signature is most visible in items that were never expected to be on the test. The legacy items reveal what fluent current-unit performance hides.

---

## How to observe Y6 without a platform

This is the cheapest of the seven implementations because the instrument is also the intervention. Embedding legacy items in current quizzes both *measures* decay and *produces* spacing. You do not need to choose between assessment and instruction. The same questions do both.

**Method 1 — embedded legacy items.** Each weekly quiz includes two to four items drawn from material covered three or more weeks earlier. Do not announce in advance which items are legacy and which are current. Track performance on legacy items separately from current-unit items. The gap between the two — student by student, week by week — is the Y6 signal.

A pragmatic rule for which items to embed: prefer items from the same item bank as the original assessment, with similar past-class success rates. This controls for difficulty. If the legacy items are systematically harder than the current items, you cannot distinguish decay from difficulty.

**Method 2 — three-time-point testing.** For a high-value concept, test the same item bank at three time points: immediately after teaching, two weeks later, six or more weeks later. The slope from time-1 to time-3 is the decay rate. More work than Method 1 but produces a cleaner curve per item. Useful for the few concepts where you most want to know.

**Method 3 — cumulative final exam, scored by unit.** Many courses already have a cumulative final. The Y6 move is to score the final *by unit of origin* — not as a single percentage but as a per-unit retention number. Some units will hold up. Some will not. The unit-level data reveals which content stuck and which decayed. Often the school has already collected this data and has been aggregating it away. Stop aggregating.

**Method 4 — the spaced-homework restructure.** Restructure homework problem sets to be 70% current unit and 30% drawn from previous units. The 30% legacy items *are* the decay probes. The student is also experiencing forced spaced retrieval as a side effect. This is the cleanest "instrument is the intervention" implementation in the seven-component framework.

**Method 5 — the student-self-test prompt.** At the start of a new unit, ask: "Without consulting your notes, write everything you remember from Unit 3." The depth and accuracy of the recall is a qualitative Y6 read. Best for low-stakes formative use, not summative grading. **Roediger and Karpicke's test-enhanced learning** framework predicts that this exercise also strengthens what gets retrieved — the instrument-is-intervention property holds here too.

A practitioner cost note. Method 1 is the cheapest to implement and the most diagnostic per minute spent. Method 4 is more invasive but provides the strongest pedagogical benefit alongside the measurement. Most practitioners should start with Method 1.

A practitioner caution. **Difficulty matching matters.** If legacy items are noticeably harder than current items, a low legacy score may be decay, or may be the items. The chapter's working rule: when in doubt, embed *more* legacy items rather than fewer. The average rate stabilizes faster, the noise from item-level difficulty washes out, and the per-student signal becomes cleaner.

A second practitioner caution. The legacy-item move only works if students do not know in advance which items are legacy. If you announce a review session before each quiz, the spacing effect kicks in for the announced items but the diagnostic signal is contaminated. The decay-probe items have to be silent.

**Practitioner implication:** add two legacy items to your next quiz. Do not announce. Score separately. You are now collecting Y6 data with zero extra grading time.

---

## What a platform adds

The platform-side version of Y6 is **FSRS** — the Free Spaced Repetition Scheduler — and the older **SM-2** algorithm from SuperMemo. These compute, per concept node and per student, the optimal interval until the next review. They use a three-component memory model — difficulty, stability, retrievability — fit to large-scale user data. FSRS in particular has emerged as the practical state of the art over the last few years, though the academic literature on it is thinner than the practitioner record. (Most documentation lives on Jarrett Ye's blog and on the open-spaced-repetition GitHub project, not in peer-reviewed journals. The chapter is honest about this.)

A Y6-aware platform identifies high-decay concepts at the class level — material that consistently fails to stick across many students. That is an instructional-design signal, not just a student-level signal. It tells the practitioner where the unit needs redesign, not just which students need help.

None of this is required to start. The signal exists in pencil-and-paper data. The platform improves scheduling precision and scale.

---

## Worked example: the history instructor and the unannounced decay probe

A high school history instructor teaches a year-long survey course. She has read this chapter. She decides to add three legacy items to each weekly quiz starting in week four. The legacy items are drawn from material covered three to six weeks earlier — not unit-final material, just specific facts and analyses she wants to know whether students have retained. She does not announce that this is happening. She scores legacy items as a separate column in her gradebook.

By week eight, she has four weeks of legacy data on each student.

**Student F.** Current-unit performance: hovering around 78–82% all term. Legacy-item performance: week 4 = 75%, week 5 = 73%, week 6 = 70%, week 7 = 72%, week 8 = 71%. The legacy curve is almost flat. F is retaining the material. The current-unit and legacy scores are within five points consistently. Genuine Y6 signature.

**Student G.** Current-unit performance: hovering around 80–85% all term. Legacy-item performance: week 4 = 65%, week 5 = 52%, week 6 = 38%, week 7 = 32%, week 8 = 25%. The legacy curve is in free fall while the current-unit performance looks fine. The gap between current and legacy was 20 points in week 4. It is 55 points in week 8. Borrowed-certainty signature. G is performing well on whatever is in front of her. She is retaining almost nothing.

The instructor's read: G is using an AI assistant to handle current-week assignments and is not building storage. The current-week artifact does not reveal this. The legacy column does. The Y6 data tells the instructor something the existing grade book has actively concealed all term.

**Student H.** Current-unit performance: variable, 60–72%. Legacy-item performance: week 4 = 50%, week 5 = 55%, week 6 = 62%, week 7 = 65%, week 8 = 68%. The legacy curve is *rising* over time. H is doing late-night cumulative review on her own and is in fact retaining better than her current-unit scores suggest. The legacy data reveals genuine Y6 in a student whose current-week artifact has been mediocre. The intervention here is encouragement, not concern.

The instructor uses the data the way the practitioner is supposed to. She does not change anyone's grade. She has different conversations. She invites G in for office hours and shows her the gap — not the gap in artifact quality (there isn't one) but the gap between current-week and legacy performance. The conversation is anchored in data G can see. The conversation does not have to start with "I think you've been using AI." It can start with "I notice that the material from earlier this term doesn't seem to be sticking the way the new material is. Let's talk about how you're studying."

This is the second evidence stream in action. The Y6 column did the work that no single artifact could have done.

**Practitioner implication:** the worked example is the chapter. Add two or three legacy items per quiz. Score separately. Watch the gap.

---

## Exercises

**Exercise 1 (Apply).** Add two decay-probe questions, drawn from material covered three or more weeks ago, to each of your next four weekly quizzes. Do not announce. Score legacy items as a separate column. Track per-student decay across the four weeks: for each student, plot or list legacy-item performance over time. Describe, in one paragraph, the patterns you observe. Identify one student whose legacy performance pattern surprised you.

**Exercise 2 (Analyze).** For one concept you teach in your domain, identify the highest-value piece of knowledge — the single thing — that a student should still be able to recover six months after the unit ends. Write it in one sentence. Then describe, in three or four sentences, how you would *know* whether a former student still has it. What item would you give them? What would the right answer look like? What does "no longer accessible" look like and how is it distinguishable from "I never knew this"?

**Exercise 3 (Create).** Design a four-week spaced retrieval schedule for one unit in your course, using only paper-and-pencil tools (no app, no platform). Specify, week by week, what gets re-tested when. Use the Cepeda 10–20% rule as a starting point: if you want students to retain at six months, space practice three to six weeks apart; if you want them to retain at end-of-term, space practice one to two weeks apart. Justify the spacing intervals you chose. Specify how you will measure whether the schedule produced more retention than your current approach.

---

## What would change my mind

Evidence that AI-assisted students who use the AI specifically for *retrieval practice* — using AI-generated practice questions and attempting them without seeing the answer — produce decay curves comparable to genuine unassisted retrieval practice would change part of the chapter's framing. The chapter's argument is that AI-as-explanation defeats retrieval. AI-as-practice-question-generator may not. This is an empirical question the literature has not yet answered.

A finding that classroom-paced spaced retrieval does not in fact produce the spacing benefit predicted by Cepeda et al. — that the laboratory-scale finding does not generalize to year-long courses — would substantially weaken Method 4 in particular. The chapter's recommendation is based on a generalization from the lab; the generalization is empirically defensible but not bulletproof.

A controlled demonstration that the FSRS algorithm produces substantively better retention than simpler embedded-legacy-item approaches in classroom contexts would change the "what a platform adds" framing. Currently, the chapter treats the platform as precision-on-top-of-an-already-working-instrument. If the platform turns out to add far more than that, the recommendation shifts.

---

## Still puzzling

The optimal-spacing function for classroom contexts is not settled. Cepeda et al. 2008's temporal ridgeline is a useful approximation; the precise function for school-paced material is contested. The chapter's practitioner-actionable rule is: any non-zero spacing beats massing. Precise optimization is a platform problem.

FSRS performance in classroom contexts is well-validated on Anki user data but controlled classroom RCTs are thin. The chapter mentions FSRS as the current platform-side state of the art and flags the academic literature as still consolidating.

AI's specific effect on decay curves is predicted (steeper decay for AI-assisted students) and consistent with Bastani 2025 [verify], but no published study to my knowledge has measured a full decay curve under controlled AI-assisted conditions. This is the cleanest empirical study the field still needs.

Item-difficulty matching for embedded decay probes is a measurement-design problem. The chapter's rule (use items from the same bank, prefer items with similar past-class success rates, when in doubt embed more) is workable but not optimal.

The "AI-as-study-tool" failure mode — students using AI to *answer* practice items rather than to *retrieve* them — defeats the testing effect even when the practice format is right. This is a structural problem with AI access during practice that Chapter 11 will need to address in the implementation discussion.

Whether Bahrick's permastore plateau generalizes beyond his domains (Spanish vocabulary, mathematics) is less clear. The chapter treats long-tail retention as achievable; the specific shape varies by material.

---

## The wayback callout: Hermann Ebbinghaus

Hermann Ebbinghaus was a German psychologist who, in 1885, measured his own forgetting curve by memorizing 2,300 nonsense syllables — strings like ZOL, DAX, BEK, chosen specifically to be free of pre-existing associations — and then re-testing his retention at varying delays. He used the **savings method**: he measured not how much he remembered cold, but how much faster he could relearn material that had decayed. This let him quantify partial retention even when explicit recall had failed. He worked alone, self-experimenting for years, against the philosophical-psychology orthodoxy of his time which held that memory could not be studied scientifically because it was a private mental event. Ebbinghaus showed that memory could be studied scientifically by treating it as the residue of measurable behavior. He published one short book in 1885 that became the empirical foundation of an entire subfield. Every textbook reproduction of the forgetting curve is his data, retraced. The spaced-repetition research that emerged a century later — SM-2, FSRS, Anki, the Cepeda meta-analyses — sits on top of his nonsense syllables. He is the original decay-curve researcher.

---

## Bridge to Chapter 9

Six signals so far. Time on difficulty. Errors that cohere and update. Transfer that survives clothing change. Confidence that tracks knowledge. Discussion that has texture. And, now, retention that does not collapse.

The seventh signal is the last one and it is, in a way, the most diagnostic of partial understanding. A student stuck on a problem can be helped in two ways. You can give them a partial hint — point to the structure, name what kind of problem this is — or you can give them the full answer. A student with genuine partial understanding responds to the partial hint almost as well as to the full hint. They have something for the hint to activate. A student with borrowed certainty does not respond to the partial hint at all. The full answer is the only thing that produces visible improvement, because there is no developing mental model to activate.

The Zone of Proximal Development is not a metaphor. It is a structural property of a genuinely developing mental model, and it is directly observable in hint-response patterns. Chapter 9 is Y7: Scaffolding Response Curve. The last of the seven signals.
