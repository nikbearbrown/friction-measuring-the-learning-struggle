# Chapter 1 — The Artifact Is No Longer Enough

*Why the essay, the exam, and the project no longer prove what they used to prove — and why detection cannot patch the gap.*

---

## Opening case: the platform that measured success and missed the learning

A university deployed GPT-4 as a tutoring assistant for a math course. The roll-out went well by every metric the platform was built to track. Time-on-task climbed. Student satisfaction climbed. Performance on the assisted practice problems landed forty-eight percent above the no-AI control group. The dashboards looked like the kind of slide you would put in front of a provost.

Then the closed-book end-of-term exam arrived. The students who had used the AI most heavily scored seventeen percentage points *below* the students who had used no AI at all. [verify — Bastani et al. 2025 PNAS; figure subject to the administrative correction at 10.1073/pnas.2518204122; conclusions unchanged]

The engagement metrics showed success. The exam showed something else.

This is the Bastani 2025 finding. Roughly a thousand Turkish high school students, ninth through eleventh grade, four weeks, three randomly assigned conditions: unguarded GPT-4 ("GPT Base"), a guardrailed teacher-designed wrapper ("GPT Tutor"), and no AI. The GPT Tutor students improved on the assisted practice and held their ground on the unassisted exam. The GPT Base students improved most on the assisted practice and collapsed worst on the exam. Same model. Same students. Same content. The difference was the wrapper.

It is tempting to read that as a cheating story. It isn't. The students weren't running a scam. They were using a tool that produced fluent answers and felt useful. The platform was watching engagement and reporting engagement. What no one was measuring — what no one could measure without a different kind of evidence — was whether the engagement was producing the cognitive changes that "learning" actually names.

This is a measurement story. And it is the story this book is about.

**Implication for practice.** If your dashboard is built on time-on-task, click depth, satisfaction ratings, or practice-problem performance, the dashboard can show success while learning quietly evaporates. The dashboard is not lying. It is answering the question it was built to answer. The question it was built to answer is no longer the question you need answered.

---

## The causal chain that broke

Before 2023, the assessment system every educator inherited rested on a single causal chain. Genuine learning happened inside the student's head. That learning produced a cognitive process — drafting, problem-solving, reasoning through. That cognitive process produced an artifact — the essay, the exam answer, the lab report. Three links in one direction:

**Genuine Learning → Cognitive Process → Artifact**

The artifact was the only link the teacher could actually see, but the chain only ran one way. If the artifact was good, you could read backwards through it: the cognitive process must have happened, and the learning must have happened to produce that process. The artifact was a valid proxy because it was the only thing on the menu that could plausibly produce it. The proxy worked because there was no other supplier.

Generative AI is the other supplier. It opens a second causal pathway to the artifact that does not run through the student's cognition at all:

**AI Generation → Artifact**

The student now sits adjacent to a system that produces artifacts on demand. The output of that system is, increasingly, indistinguishable from competent student work. The proxy fails not because students are cheating but because the artifact now has two upstreams, and from the teacher's seat the two upstreams are visually identical.

This decoupling is not temporary. It is not a transitional problem that will resolve when detection catches up or when students "settle down" or when policy clarifies. It is a structural feature of the system the field is now teaching inside of. The chain that ran one way runs two ways. Treating the artifact as proof of the process is treating a piece of evidence as if it had one source when it has two.

**Implication for practice.** Any assessment whose validity rests on "if I see a good artifact, the student must have learned" is now resting on a premise that is false. Some artifacts are still valid evidence — proctored handwritten work, live demonstrations, conversations in the room. The first job is to figure out which assessments in your current practice are still on the safe side of the chain and which are not.

---

## Why detection cannot solve this

The instinct that runs through most institutional responses is to fix the broken chain by restoring artifact validity — to ask, "did a human type this?" If the detector can answer that question, the proxy works again. The detector approach is intuitive, defensible, and structurally a dead end. There are three reasons.

**First, detection is temporally bounded.** Every detector is trained against the generation models that exist when the detector is built. The generation models then improve. Sadasivan and colleagues (2023) made the theoretical case directly: as generated text approaches indistinguishability from human text, the area under the ROC curve of any detector approaches one-half — the coin flip. Recursive paraphrasing and light editing already crater commercial detectors. You are not building a detector. You are funding a maintenance contract on a perpetually losing arms race.

**Second, detection asks the wrong question.** "Did a human type this?" was a proxy for "Did a human learn this?" back when the two questions had the same answer. They no longer do. A human can type something she has not learned; a human can fail to type something she has learned. The detector, even when it works perfectly, gives the institution an answer to a question that has stopped being load-bearing.

**Third, detection breaks the equity of the assessment system in ways that are now publicly documented.** Liang and colleagues (2023) ran seven commercial AI detectors against TOEFL essays from non-native English writers and against US-born eighth-grade essays. The detectors misclassified sixty-one percent of the TOEFL essays as AI-generated and produced near-zero false positives on the US-born eighth graders. This is not a calibration problem you can fix with a slider. The detectors were learning the statistical fingerprint of *non-native fluency*, which overlaps with the statistical fingerprint of *AI fluency*, because both involve syntactic regularization. If your detector flags eight percent of submissions, you are not catching eight percent of the cheating. You are catching some unknown mixture of AI-use and of the writing patterns of your second-language students, and you cannot tell them apart at the level of the individual submission.

There is a fourth, quieter problem. Detection creates perverse incentives. When the system is the detector, the student's job becomes "produce text the detector accepts," which is a problem the AI is exceptionally good at helping the student solve. The student doesn't learn the material. The student learns to launder the AI's output through paraphrase and tone-shifting. The institution has trained the student to game the detector. The detector is now the curriculum.

**Implication for practice.** The political capital you are spending on better detection is capital you cannot spend on a measurement framework that asks a question that is both more important and answerable. Liang 2023 is the strongest practitioner-facing case for stopping. It is one paper, but it is the paper that turns the detection question from a pedagogy problem into a civil-rights liability.

---

## The right question

Detection answers, "Did a human type this?" The right question is, "Did a human learn this?"

The two questions sound similar. They are not. The first is a property of the artifact. The second is a property of the student. The first can be defeated by any system that produces sufficiently human-looking text. The second cannot be defeated by such a system, because no such system can cause the student to learn. The AI can write the essay. The AI cannot, by writing the essay, place the schema in the student's head. The schema either formed or it didn't, and the question of whether it formed is independent of the question of how the page got filled.

This sounds philosophical. It is operational. If you can find behavioral evidence that the schema formed — evidence that does not run through the artifact — you have an evidence stream that the AI cannot produce on the student's behalf. The student who had the AI write the essay can hand you the artifact. She cannot hand you the trace of having struggled through the material that the AI was solving for. The traces of genuine cognitive engagement are *behavioral consequences of learning happening inside a particular brain* — and that brain either ran the process or it didn't.

The question is more important than the detection question because it is the one that connects to outcomes the institution actually cares about: retention, transfer, durable competence. It is also more answerable, because it doesn't require you to win an arms race against models that improve monthly. It requires you to look at the student rather than the artifact, and at the right things on the student rather than the convenient ones.

You will hear a Bjork distinction inside that paragraph if you've spent time in the learning sciences. Bjork and Soderstrom (2015) wrote the canonical synthesis of *performance versus learning*: immediate performance is what the student can do right now, and it is a famously bad predictor of durable retention. Performance is what most assessment captures. Learning is what assessment is supposed to evidence. The two have always been partially independent. AI access widens the gap dramatically — the student with the AI can perform without learning at a scale the assessment system was not built to handle.

Two cultural shifts ride along with this question change. The first is that the conversation with the student stops being adversarial. "Did you use AI?" is a question with one of two answers — yes or no — and one of the two requires the student to admit something that may have consequences. The honest student and the dishonest student have the same incentive to say no. The question collapses into a contest neither party wins. "What would tell me you learned this?" is a different conversation. It is the conversation a teacher and a student already know how to have. It is also the conversation that, when you have it, sometimes reveals genuine learning you didn't expect, and sometimes reveals gaps the artifact had been hiding for you both.

The second cultural shift is that artifact quality stops being the only thing carrying assessment weight. It does not become irrelevant. Some artifacts will continue to be valid evidence because the conditions under which they were produced make them so — handwritten in-class work, oral presentation, proctored exam, observed performance. Other artifacts become *partial* evidence — useful but no longer self-sufficient, requiring a second evidence stream to read confidently. The teacher does not have to choose between trusting the artifact and disbelieving the student. She has to develop an additional way of looking that lets her read both at once.

**Implication for practice.** Stop asking "did you use AI?" and start asking "what would tell me you learned this?" The first question is unanswerable and adversarial. The second is answerable, professionally familiar, and reframes the conversation with the student from accusation to evidence.

---

## What this book will do

This book argues that genuine learning leaves seven kinds of behavioral traces — partially independent of each other, each grounded in well-established learning science, each observable by a working teacher with no special technology. Together these seven traces form a second evidence stream that the teacher reads alongside artifact quality, in whatever proportion her professional judgment warrants. The framework is called the *Genuine Learning Probability* framework, or GLP. The seven components are labeled Y1 through Y7. The framework, the labels, and the term "friction traces" are internal to Humanitarians AI [Humanitarians AI internal framework]; the underlying mechanisms are not.

The companion GLP preprint makes the formal argument with effect sizes and validation evidence. This book is the practitioner translation. It does not require you to read the preprint. It does not assume research literacy. Every piece of evidence cited is translated into plain language before it is used.

The book has three acts. Act One — this chapter and the next — establishes why the artifact is no longer enough and why genuine learning leaves traces in the first place. Act Two walks through each of the seven components: what it measures, why it works, what genuine looks like, what borrowed certainty looks like, and how to begin observing it in your classroom without any platform at all. Act Three combines the seven into an evidence stream you can actually use and gives you a starting point for your own context.

A note on the contrast that anchors the book. Bastani 2025 is not the only finding in the field. Kestin and colleagues at Harvard ran a parallel RCT with undergraduate physics students using a guardrailed AI tutor — Socratic prompting, no full solutions, calibrated hints. Their students learned roughly twice as much in the same time as students in a high-quality active-learning condition, and reported higher engagement to match (Kestin et al. 2025). Same generation, opposite outcome. The model isn't the variable; the wrapper is. The decoupling is permanent, but the wrapper can be designed to put the cognitive process back in front of the artifact rather than around it. The book's framework is not anti-AI. It is anti-pretending-the-artifact-is-still-the-proof.

**Implication for practice.** You do not need to wait for institutional policy, a platform purchase, or a new credential to begin. You need to know what to look for. Chapter 2 explains why the traces exist. The chapters after that explain what each one is. By Chapter 11 you will have two or three components you can start observing this term.

---

## Worked example: the Bastani study walked through

The Bastani study is the most cited demonstration of the engagement-learning gap. It is worth walking carefully because the design is exactly the design every reader of this book will recognize when she looks at her own AI rollout.

Roughly a thousand Turkish high school students, randomly assigned within classroom to one of three conditions during a four-week math unit. Condition one: standard GPT-4, used as the student preferred. Condition two: a GPT-4 wrapper designed by the research team — pedagogical prompting, scaffolded hints, no full-solution dumps. Condition three: no AI access. All three conditions did the same practice problems and took the same closed-book unassisted exam at the end.

The practice-problem performance — the *engagement* metric, the dashboard number — looked like this. The unguarded GPT students were performing forty-eight percent above control. The guarded GPT students were performing one hundred and twenty-seven percent above control. Both AI conditions looked like a roaring success.

The closed-book exam performance told a different story. The guarded students were statistically indistinguishable from the control group; the wrapper had not harmed them. The unguarded students scored seventeen points below the control [verify — figure subject to the 10.1073/pnas.2518204122 correction]. The unguarded condition, which had looked best on the engagement metric, was the worst-performing condition on the actual learning measure. The platform had measured one variable and reported on a different one.

Now place the Bastani result next to Kestin et al. (2025). Same generation. Different wrapper. Different outcome. The Harvard students with the well-designed AI tutor learned about twice as much as students in high-quality active-learning sections. Bastani is not "AI hurts learning." Kestin is not "AI helps learning." Together they are: *the artifact looks the same regardless of what the wrapper does to the cognitive process behind it.* You cannot read the wrapper from the artifact. The artifact is no longer enough.

This is the failure of the artifact-as-proxy in its cleanest experimental form. The engagement-metric dashboard would have rated Condition One as the best of the three. The exam said it was the worst. The information the dashboard was not collecting was process information — what the student was doing with her cognition during those forty-eight-percent-above-control practice problems. The student was, increasingly, not doing it. The AI was.

It is worth saying out loud that this happened with GPT-4, which is by the standards of generation models a relatively modest tool. The wrapper around it was nothing exotic — a standard chat interface, used as the students preferred. The "unguarded" condition is the condition most school and university AI deployments are running today, whether by policy or by default. The conditions of the Bastani study are not the conditions of a future scenario the field has time to prepare for. They are the conditions of last year's pilot in most institutions.

Bastani is one RCT in one country in one subject. It is the strongest currently published evidence of the gap, but it is not settled. Replication is the appropriate next move for the field. Lehmann and colleagues' 2024 working paper on a Swiss higher-education sample suggests user-quality moderation — stronger students gain from AI assistance, weaker students are harmed — which would complicate any single-line claim about AI effects. Stadler and colleagues (2024) report ChatGPT improving essay quality while degrading subsequent learning in the same students, consistent with the artifact-cognition decoupling. The book uses Bastani as the cleanest published demonstration because the RCT design forecloses the most obvious confounds. The framework in this book is designed to be useful whether or not the seventeen-point figure replicates exactly. The structural argument — that a second causal pathway to the artifact breaks the artifact-as-proxy — does not depend on any specific effect size. The Bastani finding is the demonstration. The decoupling is the diagnosis.

---

## Exercises

**1. (Analyze) The reliable-vs-unreliable inventory.** In your current practice, name one assessment where you are still confident the artifact is reliable evidence of genuine learning. Name one where you are not. What is structurally different between the two? Pay attention to whether the difference is *what you assess* or *under what conditions you assess it.* If the difference is conditions, that is information about how to expand the safe-side list without abandoning the work you care about.

**2. (Analyze) The question you actually want to ask.** A student submits an essay that is markedly more polished than her in-class writing. You suspect AI involvement but cannot prove it. Write, in one or two sentences, the question you actually want to ask her — not "did you use AI?" but a question that probes whether the schema is in her head. The test of a good question here is whether her honest answer would tell you something useful regardless of whether she used AI.

**3. (Evaluate) The eight-percent figure.** Your institution's AI detector flags eight percent of student submissions as AI-generated. Name two ways this figure is simultaneously an undercount and an overcount. Be specific about who is in each category. The Liang 2023 finding is one piece of the answer; what is the other?

---

## What would change my mind

If a large multi-site replication of Bastani showed that unguarded AI tutoring produced *neutral* or *positive* effects on unassisted exam performance — not just on the assisted practice — the central argument of this chapter would need to be revised substantially. The chapter does not claim that AI assistance always damages learning. It claims that artifact quality has been decoupled from process. But if it turned out that, in practice, the artifact-quality and learning effects were so tightly correlated that the decoupling was a measurement artifact, the case for an independent process-evidence stream would weaken sharply. The current evidence does not support that revision; the chapter remains exposed to it.

## Still puzzling

- Is the Bastani-style decoupling visible at the level of a single teacher's classroom, or only at population scale? An individual teacher who runs an unguarded AI rollout for one unit may not have enough students to see the seventeen-point gap above noise. What is the smallest unit at which the gap is actually legible?
- How quickly does wrapper design close the gap? Bastani's "GPT Tutor" closed it almost completely; Kestin's outperformed even strong active learning. What features of the wrapper are doing the work? Are they teachable to practitioners who are not prompt engineers?
- The detection problem against non-native English writers — does it remain this bad for the current generation of detectors, or are recent calibration approaches changing the false-positive rate in a way that should change the chapter's recommendation? The structural argument against detection holds; the equity argument has the most empirical exposure to change.
- Is there a non-AI baseline rate of "borrowed certainty"? Students copied from each other and from solution manuals long before generative models. How much of what the framework will measure is genuinely new versus how much is an old problem that now scales?

---

## Bridge to Chapter 2

Detection answers the wrong question. The right question requires measuring the process, not the artifact. The good news is that the process leaves traces — physical traces, behavioral traces, structural traces that are present when the cognition happened and absent when it didn't. Chapter 2 explains why those traces exist. Not as metaphor. As mechanism.
