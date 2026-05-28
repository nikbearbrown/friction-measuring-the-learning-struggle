# Chapter 3 — Y1: Temporal Engagement Pattern

*Genuine engagement distributes time according to difficulty. Borrowed certainty distributes time according to output length. The correlation between the two is the signal.*

---

## Opening case: forty-seven minutes that say nothing

A student spends forty-seven minutes on a module. Canvas logs forty-seven minutes. The dashboard renders the line item. The instructor, prompted to investigate the students who are "disengaged," scrolls past this student because her time-on-task looks healthy.

What Canvas does not log is whether those forty-seven minutes were spent on the three concepts the student found difficult, or distributed evenly across the module regardless of difficulty, or front-loaded on the first item and trailing off, or sitting in a background tab while the student did something else entirely. The number is gross dwell time. What learning science calls *engaged time* — time spent processing material at appropriate difficulty — is not what the number is. The two are correlated. They are not the same. And when AI access enters the picture, they decouple in a way that makes the gross number actively misleading.

Y1 — Temporal Engagement Pattern [Humanitarians AI internal framework] — is the friction trace that lives in this decoupling. It is not the *amount* of time. It is the *correlation between time and difficulty* — whether the student's clock bunches where the cognitive load actually is, or distributes itself in a way that has nothing to do with how hard each piece is.

**Implication for practice.** If you are reading time-on-task dashboards as if they measure engagement, you are reading them as the field read them in 1990. The forty years of work since says you are reading a noisy proxy whose validity has just been further damaged by a generation of tools that decouples output time from cognitive time.

---

## What Y1 measures

Y1 is the correlation, within a single student's body of work, between the *difficulty* of an item and the *time* she spent on it. Not the absolute time. The pattern.

A genuine learner working a problem set is bearing the cognitive load of the problems herself. Cognitive load theory's central prediction — Sweller's element-interactivity argument — is that harder items, by definition, contain more interacting elements and demand more working-memory capacity, and therefore take longer to process. A student who is doing her own processing will spend more time on the limiting-reagent problem than on the unit-conversion problem because the limiting-reagent problem is genuinely harder for her. The time-difficulty correlation is positive. The slope is not the point; the *positivity* is.

A student who is routing the cognitive work through an AI is producing artifacts whose time profile reflects something else — most often the length of the AI's output. An AI explanation of a hard concept and an AI explanation of an easy concept can be the same length, or the easy one can be longer (because there is more to say at the surface level), or the hard one can be longer (because the prompt was more complex). The relationship between item difficulty and time-on-task becomes noisy with respect to the *student's* cognitive load, because the student's cognitive load was not the variable producing the time.

The correlation, then, is the signal. Genuine engagement: positive correlation. Borrowed certainty: near-zero correlation, or a correlation driven by something that has nothing to do with what was hard for the student.

**Implication for practice.** You do not need a correlation coefficient. You need to know whether the pattern is *there* across the student's work. The recognition is qualitative. "Did she spend more time where it was harder?" is a question you can answer by looking. If the answer is no, the next question is *why*.

---

## Why Y1 exists: cognitive load theory in working language

Sweller's cognitive load theory has held up for nearly four decades because the underlying claim is structurally simple. Working memory has limited capacity. Some of the load on working memory is *intrinsic* — built into the material's element-interactivity, the number of pieces a learner has to hold in mind simultaneously to make sense of the relationship between them. Some of the load is *extraneous* — introduced by the way the material is presented (a confusing diagram, an irrelevant detail, a worksheet that requires the student to flip between two pages). Some of the load is *germane* — the work of building the schema that lets the learner stop having to hold everything in working memory at once.

The implication for time is direct. Holding more interacting elements in working memory takes more time. The student processing a hard limiting-reagent problem is, mechanically, doing more work in working memory than the student processing a one-step conversion. The processing time is the trace of the load. When the load goes elsewhere — to the AI — the time goes with it. The student is no longer holding the elements. She is reading an explanation that holds them for her, or she is copying an output that was produced without her working memory entering the loop.

This is not a metaphor about laziness. It is a structural claim about what cognitive load is and where it shows up behaviorally. The clock is one of the cleanest places where load is visible. The clock has been there the whole time. The field misread it by collapsing it to gross dwell.

Two adjacent findings keep the chapter honest. Karweit (1984) synthesized decades of time-on-task research and concluded that *allocated* time, *engaged* time, and *academic learning time* are three different things, with the last one — time spent on material at appropriate difficulty — being the predictor that actually correlates with learning. Berliner's "academic learning time" framework (1990) made the same case with finer-grained classroom observation. Plant and colleagues (2005) found that gross hours studied did not predict college GPA; *deliberate practice* time — effortful, feedback-rich, edge-of-current-ability time — did. Forty years of evidence say the same thing. The clock matters; what shows up on the clock depends on whether the student is doing the work.

**Implication for practice.** When you read a time number, the first question is not "how big?" but "doing what?" Y1 operationalizes that question by reading the time against the *difficulty distribution* of the items. The distribution is the discriminator. The dashboard you have does not show you the distribution.

---

## The genuine signature

A student who is doing her own cognitive work shows time bunched on the items that are genuinely hard *for her*. The pattern looks like:

- Time correlates positively with item difficulty, item by item, across her work.
- Re-reading is visible — she goes back over a paragraph or a problem statement more than once when the material is hard.
- Backtracking is visible — she writes something, decides it's wrong, returns to the prior step.
- Pauses are visible — she stops for ten or twenty seconds before continuing, more often at decision points than at routine steps.
- Drafts in stages show effort moving over time toward the parts that are hard.

The shape of the signature varies by domain and by student. The thing that is consistent is that the student's clock and the item's difficulty are *coupled*. If she rates an item as hard and her time on it is short, that is a signal worth investigating. If she rates an item as easy and her time on it is long, that may be a different signal — boredom, distraction, technical difficulty — but it is information.

The signature is also consistent with the student's *own* sense of difficulty. A student who can mark which items felt hard and whose marks align with where her time pooled is doing the cognitive work she is being asked to do. The marks-and-time alignment is itself a Y1 reading.

**Implication for practice.** Y1 does not require you to know the "true" difficulty of an item. The student's *perceived* difficulty is enough. The correlation can be read against either.

---

## The borrowed-certainty signature

When the student is routing the work through an AI, the time profile changes in ways that are diagnostic.

- The time-difficulty correlation flattens. The student spends roughly the same amount of time per item across the difficulty range, because what is driving the time is not her processing load.
- The time-output-length correlation strengthens. Items that produce longer AI responses take longer; items that produce shorter responses are faster. This is a sensible relationship from the AI's perspective and a *wrong* relationship from the cognitive-load perspective.
- Pauses, re-reading, backtracking thin out or disappear. The AI does not pause to re-read its own output. A student copying from the AI moves linearly.
- The hardest item in the set is no longer the slowest item in her record. Often a *moderately* hard item — one with a longer prompt or a longer expected answer — is the slowest. The actual difficulty ranking and her time ranking diverge.

The signature is not always clean. Some students mix genuine and AI-assisted work within the same assignment; some students use AI to translate the question and then work the problem themselves; some students use AI on the easy items and labor through the hard ones because they want to learn. The signature is a *pattern*, not a per-item verdict. Read across enough items and the pattern resolves; read across one and it doesn't.

There is also a more interesting failure mode worth naming up front: the student who *deliberately slows down on hard items to fake Y1.* This is possible. It is also self-defeating, because it requires the student to know which items are hard, which is itself part of the learning the framework is trying to evidence. Faking Y1 perfectly requires knowing the difficulty distribution; knowing the difficulty distribution requires the kind of engagement that produces Y1 in the first place. Chapter 10 takes this argument further as the ensemble logic. For Y1 alone, the answer is: yes, it can be faked; the cost of faking it well is non-trivial; that is part of why the framework combines Y1 with six other traces rather than relying on it alone.

**Implication for practice.** Read Y1 across the student's body of work, not against a single item. A flat correlation across many items is a stronger signal than a flat profile on one assignment, which might just be a bad day.

---

## How to observe Y1 without a platform

Y1 is the cheapest of the seven components to begin observing in your classroom. Five methods, in roughly increasing order of cost.

**The self-rated difficulty annotation.** On any problem set or assignment, ask students to mark each item as it felt to them — a check for easy, a question mark for hard, or a one-to-three rating. The instruction can be as light as a single sentence at the top of the page: *Mark each problem with how hard it felt as you worked it.* Compare the annotations to your sense of the item difficulty and to their performance on each item. Students whose marks align with the actual difficulty distribution are showing one piece of Y1 — they perceived the load as the load distributed itself. Students whose marks are random, absent, or anti-aligned are showing the borrowed-certainty signature, or some other signature you need to look at more carefully. Cost: a single sentence in the instructions; ten seconds of grading per student.

**The start-stop time log.** Attach a small log to the front of the problem set: *Write the time you start each problem and the time you finish.* Aggregated across the class, you can see whether the time bunched where the difficulty bunched. This is more work for students; it works best when framed as "here's data we're using to make the unit better," not as surveillance. Cost: thirty seconds per item for students; one Excel column per item for you.

**Think-aloud sampling.** Ask two or three students per week to think aloud while working a problem set in your presence — to say what they're noticing, what they're trying, what they're stuck on. Ericsson and Simon's (1993) protocol is the formal version; Chi (1997) developed coding schemes for classrooms. You do not need either. You need the qualitative observation: did the student narrate processing, or did she narrate retrieval-without-processing? The think-aloud reveals whether the time you are about to read is engaged time or dwell time. Cost: fifteen minutes per student per sampling event; less if you cluster it on a problem-set day.

**Version-history reads on digital writing.** For any writing produced in Google Docs, Word, or any editor with version history, the revision record shows where time pooled in the document. Pauses produce gaps. Re-reading produces editing in old paragraphs. Linear smooth production produces a flat profile. You are not looking for cheating; you are looking for whether the writing process matches the work the writing was supposed to demand. Cost: instructor time per document, but the data is there without new collection.

**Staged-submission timestamps.** For longer work, require an outline at T1, a draft at T2, and a final at T3. The intervals between submissions are partial Y1 evidence — they tell you where the work happened, even if you can't see what happened inside each interval. Cost: structural changes to your assignment; pays for itself in feedback opportunities anyway.

What a platform adds. A platform that captures sub-paragraph clickstream can compute Y1 automatically — item-level dwell, correlated against the item's pre-rated difficulty, summarized as a single number per student per assignment. The number is more precise. The diagnostic logic is the same logic you are using by hand with annotations and start-stop logs.

**Implication for practice.** The annotation method works in any classroom tomorrow. It is the place to start. The single most diagnostic addition to any problem set is a column in which the student rates how hard each problem felt. The data lives next to the answer key. The cost is one sentence in the instructions. The signal is real.

---

## Worked example: a chemistry teacher reads Y1 with checkmarks

A high school chemistry teacher has been grading stoichiometry problem sets the same way for fifteen years. Five problems per set, mixed difficulty — two unit conversions, two ordinary stoichiometry, one limiting-reagent. She has watched her students' AI use climb. The artifacts have gotten cleaner. She is not confident the cleanliness is hers.

She adds one sentence to the problem set: *Next to each problem, put a check if it felt easy and a question mark if it felt hard. There are no wrong marks.* She does not change anything else. She grades the problems as she always has and looks at the marks separately.

Three patterns emerge across thirty students.

Pattern one — the students whose question marks are on the limiting-reagent problem and on one of the harder stoichiometry items, and whose checks are on the unit conversions. Their marks align with her sense of the difficulty distribution. Their wrong answers, when they have them, are on the items they marked hard. These students are doing the cognitive work. The marks confirm what her impression of these students already was.

Pattern two — students whose marks are scattered without obvious pattern, sometimes including question marks on the unit conversions and checks on the limiting-reagent problem. Their wrong answers don't track their marks. Some are doing the work and have unusual difficulty perceptions; some are not engaging with the marks at all. These students require a closer look — a one-on-one conversation, a think-aloud the next problem set, more data.

Pattern three — students whose marks are uniformly all checks. Their answers are correct or near-correct across the set, including on the limiting-reagent problem. Nothing felt hard. The mark pattern and the artifact look strong; the time profile, when she checks the version history on their submitted documents, is also flat — about ten minutes total, very little variation between items. The borrowed-certainty signature is consistent across two readings.

She does not accuse anyone of anything. She does not change a single grade. What she does is open conversations with the pattern-three students next class — not "did you use AI" but "I noticed the limiting-reagent problem didn't feel hard. Can you walk me through how you set up the mole ratio?" The conversation gives her information the artifact could not have given her. Some of the pattern-three students walk through the setup confidently and accurately, and her concern resolves — she was over-reading a clean record. Some struggle with the setup in conversation in ways that don't match the clean submission, and the gap is the information she needed.

The whole intervention cost her one sentence on the problem set and ten minutes of conversation. It produced one piece of evidence she did not have before. That is the Y1 starting point. It is small. It is real.

**Implication for practice.** The first Y1 deployment in your practice does not need to be ambitious. It needs to be honest. One sentence on the page. One column in your grade book. One conversation with the students whose marks don't fit.

---

## Exercises

**1. (Apply) Design the difficulty-rating addition.** For your next assessment, write the one-sentence addition that asks students to rate how hard each item felt. Then write, in advance, what you will *do* with the data: which contrasts will you look at, which students will you talk with first, what would tell you the signal is meaningful versus noise? The act of pre-committing to a read is the act that turns the rating from "extra data" into a Y1 observation.

**2. (Analyze) Read a previous submission's time pattern.** Pick one student whose recent work you have access to — including, if possible, version history or staged submissions. Describe, in three or four sentences, the time-difficulty pattern you can infer from what you have. You will not have a clean number. You will have an impression. Write the impression down. The discipline of writing it down is the discipline of converting tacit teacher knowledge into evidence you can examine later.

**3. (Create) The student-facing explanation.** Write a one-paragraph explanation to your students of why you are asking them to mark hard versus easy items. The constraint: the paragraph must frame the practice as *learning support* (information that helps you and them locate where the work needs to happen) rather than as *surveillance* (information used to catch them). The Y5 chapter will return to the ethics of this distinction. For Y1, the wording of the explanation is the deployment. If your students hear "we're watching you," you will not get honest marks. If they hear "your perception of difficulty is data we both need," you will.

---

## What would change my mind

The chapter's claim is that the time-difficulty correlation flattens under AI assistance because the cognitive load goes to the AI rather than the student. The claim would need substantial revision if a body of evidence emerged showing that students using AI tutors maintain a positive time-difficulty correlation in their work — perhaps because they spend longer iterating with the AI on hard items, in a way that mirrors the cognitive load they would have borne without the tool. The Kestin et al. (2025) work with Socratic AI tutors hints that well-designed wrappers produce engagement patterns closer to genuine processing than to offloading; if the same were true for unguarded AI use in practice, the chapter's diagnostic story would have to bend. The current evidence (Bastani 2025 and adjacent) runs the other way, but the question is open and the framework's empirical case here is structural rather than fully validated.

## Still puzzling

- How well does the difficulty-rating annotation hold up across student populations? The literature on judgments of learning (JOLs) suggests self-reported difficulty perception is biased — students often underestimate the difficulty of material they have processed fluently and overestimate the difficulty of material they have not yet engaged with. The annotation method assumes the bias is consistent enough across students to be readable. That assumption is not fully tested.
- The chapter's examples are problem-set-heavy. The time-difficulty logic in creative work — essays, design projects, lab reports — is less clean, because "difficulty" is harder to define at the item level. How does Y1 generalize?
- What about the student who deliberately slows down on hard items to fake Y1? The faking is possible. The faking is expensive — you have to know which items are hard to slow down on the right ones. The ensemble argument in Chapter 10 takes this further. For Y1 alone, the open question is how often this happens and whether it is detectable as a pattern (e.g., uniform-deliberate-slowing on every hard item would itself look unusual relative to natural variation).
- The interaction between Y1 and accommodations for students with processing-speed differences is something the framework needs to handle carefully. A student with a documented processing-speed accommodation may show a *different* time profile that is not Y1 evidence in either direction. The chapter does not solve this; it flags it.

---

## Bridge to Chapter 4

Time-difficulty correlation is the first signal. The second is whether the student's *errors* follow a coherent path through misconception space — whether her mistakes cluster the way a developing mental model predicts they should, or scatter the way the outputs of a system with no mental model scatter. The clock told you whether she was processing. The errors will tell you whether the processing was producing a schema. Chapter 4.
