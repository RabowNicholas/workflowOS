# Pedagogical Framework Reference

Research-backed decisions underlying the course-script-writer skill. Read this file when scripting any module to understand *why* the framework works the way it does.

## Table of Contents
- Core Teaching Model (Huberman Adaptation)
- Cognitive Load and Segment Length
- Application and Active Recall
- Self-Paced Completion and Structural Prevention
- Instructional Design Foundations
- Module Variant Rationale
- Known Risks and Mitigations

---

## Core Teaching Model (Huberman Adaptation)

The framework adapts Andrew Huberman's mechanism-first pedagogy for self-paced, screen-based learning.

**What Huberman does:** Opens with the biological/scientific "why" before touching a protocol. Spends extended time on mechanism so the protocol feels inevitable rather than prescribed. Calibrates trust through honest scope claims — acknowledging research limitations makes confident claims land harder. Repeats core concepts across multiple frames throughout an episode.

**What transfers directly:**
- Mechanism before protocol. Teach the machine behavior before teaching the fix. This is the single most important structural decision in the framework.
- Honest scope claims. The buyer is a ChatGPT power user who's heard a hundred people overpromise about AI. Candor about research gaps ("no published benchmarks exist for this") is a trust signal that separates the course from prompt-template products.
- Repetition across frames. Core concepts should appear in narration, then in demo, then in synthesis — different media, not just different words.

**What needs adaptation:**
- **Ratio compression.** Huberman spends ~60% on mechanism, ~40% on protocol. His audience self-selects for 2-3 hour deep dives. The course buyer is time-constrained. Target 30-40% mechanism, 60-70% protocol/demo/application.
- **Visual proof replaces verbal proof.** Huberman teaches systems you can't see (neuroscience). The course teaches a system the student can open in another tab. Screen recordings replace extended verbal explanation. Show the behavior, then explain it — don't explain it and hope the student imagines it.
- **Repetition across formats, not within narration.** Huberman repeats verbally because listeners are often half-attending (driving, running). Course students are sitting down. Restate once in narration, once in demo, once in synthesis. Three angles, three media — not four verbal restatements.

---

## Cognitive Load and Segment Length

**Core principle (Sweller, cognitive load theory):** Extraneous cognitive load must be minimized to preserve working memory for learning-relevant (germane) processing. Self-paced learners manage their own cognitive load without instructor pacing, making structural support critical.

**Video segment length:**
- MIT/edX research: attention drops sharply after 12 minutes of continuous video.
- Optimal range: 5-12 minutes per segment before a checkpoint or mode switch.
- In-video knowledge checks at ~8-10 minute intervals maintain 71-86% engagement (IEEE, 2015).

**Why this matters for the framework:** The MECHANISM phase is capped at 15 min total, chunked into 5-min segments with checkpoints. This isn't arbitrary — it's the ceiling before attention degrades. Mode switches (narration → demo → application) serve as natural cognitive resets.

**Microlearning context:** Microlearning (sub-10 min segments) boosts retention by up to 60% and achieves completion rates as high as 82%. The framework's chunking approach captures this benefit without sacrificing depth. The mechanism section provides depth; the chunking provides the micro-learning retention advantage.

---

## Application and Active Recall

**The science:** Active recall (testing/doing) strengthens memory traces more than passive review, even without feedback. Repeated recall improves retention to ~80%. Scenario-based exercises outperform recall-only quizzes.

**The self-paced paradox:** Application is the highest-leverage retention move, but self-paced students routinely skip optional exercises. No facilitator waits for them. No cohort creates social pressure.

**Framework solution — graceful degradation:**
- **Best case:** Student pauses, does the task, gets the full active-recall benefit.
- **Middle case:** Student watches the payoff section and follows along mentally. Still gets demonstration-level retention.
- **Worst case:** Student skips entirely but still gets mechanism + demo. The course doesn't break.

The APPLICATION phase is designed so all three cases deliver value. The payoff section (showing expected results) is not optional scaffolding — it's a structural requirement that ensures the module works even for students who don't pause.

**Formative feedback substitute:** In a self-paced course without an instructor, the payoff section acts as formative feedback. The student compares their result to the expected result and self-corrects. This is less effective than instructor feedback but dramatically better than no feedback.

---

## Self-Paced Completion and Structural Prevention

**The reality:** Self-paced completion rates: 3-20%. Cohort-based: 70-96%. This is the central challenge of the format.

**What predicts completion:**
1. **First-week engagement.** Students who submit an assignment within the first 3-5 days complete at dramatically higher rates. Students who follow prescribed sequences average 9.5 points higher than non-sequencers.
2. **Prescribed sequence with scaffolding.** Clear prerequisite structure and progressive difficulty reduce cognitive load and prevent procrastination.
3. **Visible progress.** Students need to see where they are in the sequence and feel capability gains.
4. **Low-stakes checkpoints.** Frequent, non-graded knowledge checks keep engagement alive and serve as early warning signals.

**What causes dropout:**
1. Time commitments / life interference (largely outside course control)
2. Course workload / difficulty mismatch
3. Lack of interaction / perceived isolation
4. Mental fatigue / lack of perceived progress
5. Procrastination and time management failure

**Framework mitigations:**
- Module 1 ends with an immediate application task that produces a visible result in under 10 minutes. This is the first-week engagement lever.
- Each SYNTHESIS includes a capability statement — concrete progress signal.
- Checkpoints after every 5-min mechanism chunk — low-stakes, non-graded crystallization moments.
- Modules are sequenced with explicit forward links (SYNTHESIS → next module's HOOK BRIDGE) to create pull.
- Total course length (3.5-5.5 hours of video) is in the sweet spot for self-paced completion (short courses at 5-10 total hours hit 40-60% completion).

---

## Instructional Design Foundations

Three frameworks inform the skill's structure:

**Merrill's First Principles of Instruction:**
1. Task-centered — learning is promoted when learners are engaged in solving real-world problems.
2. Activation — learning is promoted when existing knowledge is activated as a foundation.
3. Demonstration — learning is promoted when new knowledge is demonstrated to the learner.
4. Application — learning is promoted when new knowledge is applied by the learner.
5. Integration — learning is promoted when new knowledge is integrated into the learner's world.

The five-phase framework maps directly: HOOK activates (surfaces the problem), MECHANISM demonstrates (shows the why), DEMONSTRATION demonstrates (shows the how), APPLICATION applies, SYNTHESIS integrates.

**Bloom's Taxonomy (revised):** Remember → Understand → Apply → Analyze → Evaluate → Create.

The framework never stops at Understand. Every module pushes to Apply (APPLICATION phase) or higher. The capstone variant pushes to Create (student builds their own system). Quality check #4 (testable capability statement) enforces this — if the capability is about understanding rather than doing, the module hasn't gone far enough up Bloom's.

**Cognitive Load Theory:** The chunking, checkpoint, and mode-switch patterns all derive from CLT. Extraneous load is reduced by: consistent structure (the five phases become familiar by Module 3), clear signposting (production tags, bridges), and single-idea chunks. Germane load is maximized by: connecting new information to prior modules (bridges), using demos as concrete anchors, and requiring application.

---

## Module Variant Rationale

**Standard** — works when a module has one core concept. Most modules fit here. The five phases run once, linearly.

**Nested-Loop** — required when a module introduces a multi-part framework (e.g., four beats of DEFINE → GATE → BUILD → CHECK). Running the standard five phases once would force all four beats into a single mechanism section, making it too dense. The nested loop gives each beat its own mechanism-demo-application cycle while sharing the hook and synthesis. Risk: bloat. Each inner loop must stay under ~10 min or the module exceeds 60 min total.

**Feature-Tour** — required when a module covers multiple distinct features that don't share a single unifying mechanism. A standard module would either compress each feature to uselessness or bloat to 90+ min. The feature-tour compresses mechanism+demo to 3 min per feature and consolidates application into one integrative task. Risk: feels like a feature list rather than a lesson. The integrative application task is what prevents this — it forces the student to use multiple features together, creating synthesis that a feature-by-feature approach lacks.

**Capstone** — required for closing/integration modules. No new mechanism to teach, so the MECHANISM phase is replaced by INTEGRATION (weaving prior concepts together). No next module to link to, so SYNTHESIS is replaced by HANDOFF (pointing to the next concrete step). Risk: feels like a recap. The full-workflow demonstration prevents this — the student sees everything working together for the first time, which is genuinely new even though the individual pieces aren't.

---

## Known Risks and Mitigations

**Risk: Template fatigue.** If every module opens with "You've probably done this..." the student feels the structure by Module 3.
**Mitigation:** Three hook variants (confession, provocation, failed prompt). Quality check #7 requires rotation.

**Risk: Mechanism bloat.** The Huberman instinct is to go deep on the why. In a time-constrained course, this can push modules past 45 min.
**Mitigation:** Hard cap of 15 min on mechanism. If the mechanism needs more time, the module needs to be split. Compress mechanism first when a draft runs long.

**Risk: Application skip rate.** Self-paced students skip exercises. The framework can't force compliance.
**Mitigation:** Graceful degradation design. The payoff section ensures value even for non-participants. Frame the application as the next step, not a sidebar.

**Risk: Module 1 demonstration gap.** Constitutional AI / RLAIF can't be shown on screen the way context window behavior can.
**Mitigation:** Module 1 uses a comparison demo (same prompt in Claude vs. ChatGPT, showing behavioral differences that trace back to training). The mechanism explains *why* the behavior differs; the demo shows *that* it differs. This is a less direct demo than other modules but still provides visual proof.

**Risk: Feature-tour modules feeling disconnected.** Covering 10 features in one module can feel like a list, not a lesson.
**Mitigation:** Cap at 5-6 features that earn full treatment. Remaining features get a mention-and-link. The integrative application task creates coherence.

**Risk: Course obsolescence.** AI tools change fast. Feature walkthroughs age in months.
**Mitigation:** The framework teaches mechanism (why features exist) not procedure (how to click). Mechanism-level knowledge transfers across model versions. Module 5 (most at-risk for obsolescence) should focus on *what problem each feature solves* rather than step-by-step UI walkthrough. Production note: Module 5 is the most likely module to need re-recording — design it for modular updates (each feature as a separable segment).
