# Chapter 4 — Y2: Error Trajectory Coherence

*Genuine misconceptions produce coherent errors that evolve predictably as the mental model develops. Random errors produce no coherent pattern. The coherence is the signal.*

---

## Opening case: three of the same mistake, then a different one, then five right

A student makes the same kind of mistake three times in a row on a fraction problem set. The fourth time, she makes a different kind of mistake. The next five problems, she gets right.

To the instructor, the pattern is recognizable. The first three errors were consistent with a specific misconception — say, treating fraction addition as if it operated on numerators and denominators separately (1/2 + 1/3 → 2/5). The change in error type at problem four signals that something in her mental model updated. The subsequent five correct answers confirm the update held. The student did not get lucky. She moved.

This is not a literary description. It is the reward-prediction-error mechanism doing its job. The first three errors generated a signal — an expectation, an outcome, a gap. The gap drove a small update in the underlying procedure. The fourth attempt was the updated procedure being tried out. The next five were the new procedure stabilizing.

Y2 — Error Trajectory Coherence [Humanitarians AI internal framework] — is the friction trace that lives in this kind of pattern. It is not the error rate. It is the *shape* of the errors across time. A student whose errors cluster around an identifiable misconception and then shift coherently as her model updates is showing genuine learning at the level the prediction-error mechanism produces. A student whose errors scatter across unrelated error types from one item to the next is showing something else.

**Implication for practice.** You probably already read error trajectories informally. You see the student who keeps making the same mistake and recognize the misconception underneath. You see the student whose mistakes are everywhere and worry that something different is going on. Y2 names what you are doing and makes it systematic enough that you can do it on purpose.

---

## What Y2 measures

Y2 is the *coherence of a student's errors across time and items* — specifically, whether the errors map to identifiable misconceptions and whether the misconception map updates in conceptually adjacent steps as the student's mental model develops.

Two pieces of vocabulary make the rest of the chapter readable.

A *misconception* is a specific incorrect way of thinking about a concept that produces predictable wrong answers. In fraction operations, "treat the operation as acting on numerators and denominators separately" is a misconception. It generates specific wrong answers across many problems. The wrong answers are not random; they are *generated*. The misconception is the generator.

*Conceptual adjacency* is the question of which misconceptions are one update away from each other. A student who holds the "operate-on-numerators-only" misconception is one update away from "operate on numerators, but also notice the denominators matter somehow" (an intermediate, still-wrong but closer model). She is several updates away from a correct schema. Her error trajectory, if her learning is genuine, traces edges in this conceptual adjacency space. She moves to an adjacent misconception, then to another, then to the target. She does not leap from one unrelated misconception to a wildly different one and back.

Y2 reads the *path*. Errors clustered around one misconception, shifting coherently to an adjacent misconception, then to the target, is the genuine signature. Errors distributed without pattern across conceptually unrelated error types — a sophisticated correct answer on one item, a wildly off-target error on the next, with no shared underlying misconception — is the borrowed-certainty signature.

**Implication for practice.** Y2 requires you to know your domain's misconceptions well enough to code errors against a small list of categories. Some domains have well-documented catalogs (Driver et al. 1994 for K-12 science; Brown and Burton 1978 BUGGY for elementary subtraction; the AAAS *Atlas of Science Literacy* across many domains). Some don't. Where catalogs exist, use them. Where they don't, you build one informally from your own teaching experience — and you'll find you already have one in your head; the work is writing it down.

---

## Why Y2 exists: the prediction-error mechanism in plain language

Chapter 2 introduced Schultz, Dayan, and Montague's (1997) finding: dopamine neurons signal the gap between expected and actual outcomes. The signal drives associative updates. The framework's claim is that the same kind of signal — at the cognitive level, not necessarily at the same cellular level — drives schema update in genuine learning. The student who expects one answer and produces another generates an internal mismatch. The mismatch is what makes the next try different from the last.

This has two consequences for what error trajectories look like.

**Errors are non-random.** They are generated by the student's current mental model. Brown and Burton (1978) demonstrated this with extraordinary clarity in elementary subtraction. They built a system called BUGGY that modeled children's subtraction errors as a small library of identifiable "bugs" — specific procedural mistakes (always subtract smaller from larger; borrow incorrectly across zeros; carry but forget to add the carry). The bugs *generated* errors. Knowing the bug let the system predict which problems a child would miss and how. The errors were structured. The structure was diagnostic. This is the foundational empirical demonstration that error patterns reveal mental models.

**Schema updates are cumulative and incremental.** A student does not jump from a wrong model to a correct model in one step. She moves to a slightly-less-wrong model — one update closer to target. Each prediction-error signal drives a small adjustment. Across many items, the adjustments accumulate, and the *trajectory* through misconception space is what learning looks like at the level of behavior. A student whose error type changes at certain transitions is showing the update events. A student whose error type is the same on twenty consecutive items has not yet had a productive update. A student whose error types are scattered without any pattern is, most likely, not generating the errors from a coherent model at all — which raises the question of where the answers are coming from.

Smith, diSessa, and Roschelle (1993) reframed the misconception conversation usefully here. Misconceptions are not always monolithic wrong beliefs; often they are fragmented "phenomenological primitives" — small, context-dependent intuitions that get loosely organized. The implication for Y2 is that error trajectories are sometimes about *reorganization* rather than *replacement*. The student does not delete a wrong belief; she connects pieces of intuition differently. The trajectory through reorganization is still coherent — it traces conceptually adjacent moves — but the moves are subtler than "wrong belief → less wrong belief." This matters for how you code errors. Code at the level of generator (what move is producing the wrong answer?), not at the level of belief (what does the student think?).

**Implication for practice.** When you read errors, ask: what move produced this answer? Could the same move produce a wrong answer on the next item too, or is this a one-off? Coherent errors are answers to the first question. Scattered errors are usually a sign that the answers are not being produced by a single move at all.

---

## The genuine signature

Genuine error trajectories show three features, in roughly this order across a unit:

**Clustering around a current misconception.** Within a short window — a few problems or a single assessment — the student's errors look like *the same kind of mistake*. They share a generator. The instructor reading them can name the misconception underneath without effort.

**Coherent transitions at update events.** When the misconception updates, the error type changes. The new errors are different — but they are conceptually adjacent. The student does not leap to an unrelated misconception; she moves to one that is one productive step away. Sometimes the new misconception is "almost right" — the student has fixed one piece but is still missing another. Sometimes the new misconception is "right enough to be correct on most cases but breaks on the edge cases." The pattern is recognizable as movement.

**Subsequent performance reflecting the updated model.** After the update, the student does better on items where the new model is sufficient and may still err on items that expose the *new* misconception. This is the heartbeat: error pattern → update → new error pattern. The trajectory is visible across enough items.

A useful diagnostic: a student whose error trajectory has visible *transitions* — points where the error type changes — is showing the signal cleanly. A student whose errors are all the same kind for the entire unit may be stuck (the prediction error signal isn't producing an update), but her errors are still *coherent*. Genuine learning is producing the coherence; what's missing is the update event, which is a different problem from the one the framework is built to detect. The intervention for "coherent but stuck" is targeted teaching. The intervention for "incoherent" is to figure out what is producing the answers, because it is not a developing mental model in the room.

**Implication for practice.** A student who is consistently wrong in the *same* way is closer to learning than a student who is sometimes right and sometimes wrong without pattern. Counterintuitive in the moment; foundational to how the framework reads error data.

---

## The borrowed-certainty signature

When a student is routing the work through an AI, her errors lose the generator-and-trajectory structure. Three features stand out.

**Random distribution across conceptually unrelated error types.** A sophisticated correct answer on item one, an off-target hallucinated error on item two, a different off-target error on item three, no shared misconception underneath. The AI is correct in some places and confidently wrong in others, but the wrong places don't share a generator. They share a *source* — the AI's particular failure modes — not a *mental model* that is updating.

**No coherent transitions.** The error type doesn't shift in conceptually adjacent ways across the unit. It is whatever the AI's particular failure was on the particular item. Across the unit, the pattern is noise.

**Error type doesn't predict subsequent performance.** In the genuine case, knowing the current misconception tells you which items the student will likely miss next. In the borrowed-certainty case, it doesn't. The student who got the limiting-reagent problem wrong in a strange way isn't reliably wrong on related items in related ways. The next item, she may be right; the one after, wrong in an unrelated way.

There is also the case of the *partially* AI-assisted student — the one who uses AI on some items and works the others herself. Her trajectory may look mixed: coherent error clusters where she worked, scattered errors where she didn't. This is a real pattern and a useful one. The Y2 reading of a mixed pattern is "something genuine is happening here, but not everywhere." That is an information the framework gives you that the artifact alone does not.

The hardest case is the student whose AI assistance produces answers that are, in fact, *aligned* with a common misconception by accident — the AI hallucinates an error that resembles what a struggling student would have produced. This happens. It is rare in any consistent way. Across enough items, the AI's distribution of errors is different from a coherent learner's distribution, even when occasional items align. Read across the body of work, not the single item.

**Implication for practice.** The student whose errors are coherent is doing the cognitive work, even when she is wrong. The student whose errors are scattered is the one you want to investigate further — not because she is necessarily cheating, but because the source of her answers is unclear and the conversation needs to be more specific.

---

## How to observe Y2 without a platform

Five methods, in roughly increasing order of effort.

**The misconception-coding spreadsheet.** Five columns: student, item, error category, date, notes. Build a small list of five to eight misconception categories for the unit you are teaching. For each wrong answer, code which category produced it. After five assessments, plot — informally; you can do this in your grade book — each student's category trajectory across the assessments. Genuine learners' categories shift toward target. Scattered patterns stand out. Cost: an hour to build the category list (mostly thinking, not writing); a few minutes per student per assessment to code.

**Two-tier diagnostic items (Treagust 1988).** Each item asks for the answer *and* the reasoning. The reasoning lets you read the misconception directly, rather than inferring it from the answer alone. Item banks exist for many K-12 science topics — *Force Concept Inventory* in physics, several published two-tier diagnostics in biology and chemistry, the AAAS *Atlas* in many domains. Adopt or adapt; you do not need to build from scratch. Cost: the diagnostic items themselves are a one-time investment; the coding is built into the item format.

**Error journals.** Students keep a running log: which problems they got wrong, what they think the wrong move was, what they would try differently. Two benefits — the log gives you self-coded misconception data, and the act of keeping the log is itself an intervention (it links to Y4 calibration, which Chapter 6 will develop). Cost: low for you, real for students; works best with explicit instruction in how to write a useful entry.

**Exit-ticket misconception probes.** One question at the end of class, written specifically to elicit one identified misconception if it is present. Track the proportion of the class that shows the misconception across weeks. The class-level trajectory of a single misconception across a unit is itself a coherence reading. Cost: thirty seconds at the end of class; a few minutes of pattern-reading per week.

**Cross-context error comparison.** Compare the error patterns a student shows in closed-book conditions (in-class quizzes) against open-book or take-home conditions (homework, take-home essays). A student whose closed-book errors are coherent and whose take-home errors are scattered is showing the Y2 signature *only* in the conditions where she is the one doing the work. The *contrast* between the two contexts is the diagnostic. Cost: you already have both kinds of data; the cost is in the comparison.

What a platform adds. Automated coding against a misconception adjacency matrix; per-student Y2 scores per concept; early-warning identification of students whose trajectories are stuck (coherent but not moving) or scattered (not coherent at all); cohort-level views of which misconceptions are stuck across many students at once.

**Implication for practice.** Start with the spreadsheet. It is the cheapest of the five methods and produces a record you can read across assessments. The act of coding errors — even imperfectly — converts the implicit pattern-recognition you already do into evidence you can examine, compare, and share with a colleague. Imperfect coding done consistently across the term is far more useful than perfect coding done once.

---

## Worked example: an algebra teacher reads the fraction unit

An algebra teacher running a fractions unit for ninth graders defines four misconception categories based on her years of teaching the unit:

- **N/D** — numerator-denominator confusion (treats the parts as independent quantities).
- **NUM** — operation-on-numerator-only (adds numerators, leaves denominators alone or copies one).
- **SIGN** — sign error (correct procedure, wrong sign).
- **OTHER** — anything she can't fit into the first three categories.

She gives five short assessments across the unit. After each, she codes the wrong answers into the four categories and notes them next to each student's name in a simple spreadsheet. She does not change her grading. The coding is for her.

By assessment five, three patterns are visible.

**Pattern one — the genuine trajectory.** Student M's wrong answers are mostly N/D in assessment one (six of seven errors), shift to NUM in assessment two (five of six errors — she's reorganized her thinking but still isn't tracking denominators correctly), shift to SIGN in assessment three (three of three errors — she has the operation right but is making computational sign mistakes), and resolve to one OTHER error in assessment five. Her error count drops over time, and the categories move in a recognizable conceptual order. She is updating. The trajectory is the signal.

**Pattern two — the stuck-but-coherent trajectory.** Student J's wrong answers are N/D in every single assessment, seven of seven, six of six, five of five, four of four, four of four. His error count is dropping a little, but the category is not moving. He is engaging — the errors are coherent — but he is stuck on the N/D misconception. The intervention for Student J is targeted teaching of the specific concept that is not updating. This is a genuine Y2 signature; it just happens to be the signature of a student who needs a different kind of help.

**Pattern three — the scattered trajectory.** Student R's wrong answers across the five assessments are: one N/D, one SIGN, two OTHER (one assessment). Then on the next: one NUM, two OTHER, no others. Then: zero errors. Then: three OTHER, one SIGN. Then: one NUM, one OTHER. The errors do not cluster around any one category, and they do not move coherently between categories. The pattern is noise. His artifact quality is variable — sometimes very strong, sometimes weak in odd ways. The OTHER category contains errors that don't look like things a developing fraction-arithmetic schema would produce — wildly inconsistent magnitudes, a moment where he wrote the answer to a different problem, an answer that is correct for a different operation than the one the problem asked for.

The teacher does not change a grade. She does have a different conversation with Student R the next class — not "did you use AI" but "I've been noticing your errors are pretty different from one problem to the next. Let me work one with you out loud and see where you are." The conversation, like the Y1 conversation in the previous chapter, gives her information the artifact could not. Some scattered students turn out to be having a genuinely hard time finding any consistent model, which is also useful to know. Some turn out to be importing answers from outside their own cognition. The next conversation is informed by which kind of pattern is in the room.

**Implication for practice.** The misconception spreadsheet is not a verdict generator. It is a structured reading of patterns you are already capable of seeing. The structure makes the reading reproducible, shareable, and trustworthy enough to act on.

---

## Exercises

**1. (Apply) The misconception list for your unit.** For one concept in your current teaching, list the three or four most common misconceptions students bring. Then sketch which misconceptions are *adjacent* — one productive update apart. Which misconception is closest to a target understanding? Which one is two updates away? You will be tempted to write more than four. Don't. The list is a working tool, not a research artifact. Four categories with clear distinctions are more useful than nine categories that overlap.

**2. (Analyze) Five submissions, coded.** Pull five recent student submissions on the same assignment. Code the errors by misconception type using the list you built in Exercise 1. Describe the trajectory pattern (or absence of pattern) for each student in one sentence. Then ask yourself: which of the five students would you most want to have a conversation with next week, and what would you ask? The act of pre-committing to a conversation is the act that turns Y2 from a coding exercise into a teaching tool.

**3. (Create) The one-page misconception map.** For one unit in your course, draft a one-page misconception map. List the four to six categories. For each, write one sentence describing what move generates the wrong answers in that category. Draw arrows where one misconception is conceptually adjacent to another. The map is for you, not for students. It is the artifact that lets you code consistently across the term. Building it is the most expensive part of starting Y2; once it exists, the per-assessment cost drops to a few minutes per student.

---

## What would change my mind

The chapter's central claim is that AI-assisted student work produces *scattered* errors with no coherent generator, distinct from the coherent error trajectories of genuine learning. The claim would need substantial revision if a body of evidence emerged showing that AI-assisted students *do* produce coherent error patterns — perhaps because the AI's particular failure modes consistently align with common misconceptions, or because students who use AI selectively (on items they find hard) end up with error distributions that look like a genuine struggling learner's. The current evidence on AI-assisted error patterns is genuinely thin — Bastani 2025 has the relevant item-level data but the published analysis does not focus on error coherence — and the structural argument is strong but unconfirmed. If the empirical case turns out to be that the AI's errors happen to look like coherent learner errors in many domains, Y2's diagnostic utility drops sharply and the framework leans more heavily on Y1, Y3, Y4, Y5, Y6, and Y7.

## Still puzzling

- Conceptual adjacency maps exist for some domains (mathematics, Newtonian mechanics, basic biology) and are sparse for others (history interpretation, second-language writing, ethical reasoning, clinical judgment). How does Y2 generalize to domains without formal misconception catalogs? The practitioner-build option works but the validity of an instructor-built map is harder to defend without external comparison.
- The Y2-Y4 boundary. A student whose error trajectory is moving correctly and whose confidence calibration is also improving is showing both signals. They are partially correlated. The framework's claim is that they carry partially independent information — there are students with good trajectories and poor calibration, and vice versa — but the degree of independence in practice is not fully measured.
- LLM-based misconception coding is getting better quickly. Recent (2024–2025) tools can classify open-response errors against published misconception taxonomies with reasonable accuracy in some domains. Whether the accuracy is sufficient for high-stakes use is open. The current framework's recommendation is to use LLM coding as a draft that the instructor reviews, not as a verdict.
- The "stuck-but-coherent" case is genuinely common and Y2 reads it correctly — the student is engaging, the model just isn't updating. But the intervention is different from the intervention for the scattered case, and the framework has not yet given the practitioner a clean decision rule for when to act on coherent-but-stuck versus when to let the student work through it.

---

## Bridge to Chapter 5

Time and errors are the first two signals. Both live inside a single context — the assignment, the problem set, the unit. The third signal asks a different question: whether the understanding the student has built can survive being asked in a different way. Whether the schema is portable, or whether what looked like understanding was a pattern matched to the particular surface features of the original problems. Transfer is the next trace. Chapter 5.
