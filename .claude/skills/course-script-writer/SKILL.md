---
name: course-script-writer
description: Writes narration-ready course module scripts for WorkflowOS online courses. Use this skill whenever Nick asks to write, draft, script, outline, or revise any module or lesson for any course — even casually ("let's write Module 1", "draft the next lesson", "script the context window section", "write the narration for GATE"). Also use when reviewing or restructuring existing module scripts. This skill handles pedagogical structure, narration scripting, and production notes — it does NOT handle sales copy, social captions, or marketing (those belong to fsc-copy-generator). Triggers on any mention of module scripting, lesson writing, course content creation, narration drafts, or TTS script preparation.
---

# Course Script Writer

Write narration-ready module scripts for WorkflowOS self-paced online courses. Every script follows the five-phase pedagogical framework adapted from Huberman-style mechanism-first teaching, compressed for screen-based, time-constrained learners.

Before writing any script, read:
- `references/PEDAGOGY.md` — the full pedagogical framework, phase definitions, module variants, and research-backed constraints
- The relevant course's `REFERENCE.md` (e.g., `course/REFERENCE.md`) — locked structural decisions, module-specific rules, narrative arc
- Global `REFERENCE.md` — voice, banned words, quality tests

## The Five-Phase Framework

Every module script follows five phases. The phases are defined by their *function* (what they accomplish), not their format (how they look). Vary execution across modules to prevent template fatigue.

### Phase 1: HOOK (1-2 min)
**Function:** Make the student recognize themselves in a problem they didn't have language for.

Execution variants (rotate across modules):
- **The confession** — "You've probably done this..." followed by a specific, slightly embarrassing behavior the student will recognize.
- **The provocation** — A stat, claim, or reframe that challenges what the student thinks they know.
- **The failed prompt** — Show a real prompt and its disappointing output. Let the gap speak.

Rules:
- Never open with "In this module, you'll learn..." — that's a syllabus, not a hook.
- The hook must create a *felt gap* — the student should want the mechanism before you teach it.
- Include a MODULE BRIDGE at the top (30 sec) connecting to the prior module's takeaway. Module 1 skips this.

### Phase 2: MECHANISM (10-15 min, chunked into 5-min segments)
**Function:** Teach *why* the behavior exists before teaching what to do about it.

This is the Huberman signature, adapted. Explain the machine behavior, the research, the mental model. Each 5-minute chunk covers one idea and ends with a CHECKPOINT — a single-sentence restatement of the core concept. Not a quiz. A crystallization.

Rules:
- Honest scope claims only. If the research is limited, say so. If a stat applies to a narrow context, scope it. Overclaiming is a trust-killer for this buyer.
- Cite sources conversationally, not academically. "A 2025 paper out of [institution] found..." not "(Smith et al., 2025)."
- The mechanism must make the protocol feel *inevitable*. If the student could skip Phase 2 and still follow Phase 4, the mechanism section failed.
- Chunk breaks at 5-minute marks. One idea per chunk. Checkpoint after each.

### Phase 3: DEMONSTRATION (5-10 min)
**Function:** Show the mechanism in action inside the tool. Proof through behavior, not assertion.

This is where the format diverges from Huberman — he can't show you your dopamine receptors, but you *can* show Claude behaving. Screen recordings replace extended verbal explanation.

Rules:
- Demos use Nick's live voice, not TTS narration. Production note: mark DEMO sections clearly in the script so Nick knows where to record live.
- Show the behavior, then narrate what just happened. Don't narrate over the behavior in real-time — let the student see it first.
- Every demo must connect back to the mechanism: "Notice how [behavior] — that's [mechanism concept] in action."

### Phase 4: APPLICATION (5-10 min active student time)
**Function:** The student pauses, opens Claude, and does the thing. Active recall through doing.

This is the highest-leverage retention move in the framework. Design it to degrade gracefully for students who don't pause.

Structure:
1. **Setup** (narration, 1 min) — Specific prompt, specific task, specific expected outcome. No ambiguity about what to do.
2. **Pause prompt** — "Pause this video. Open Claude. [Do X]. When you're done, come back — I'll show you what you should see."
3. **Payoff** (narration + screen, 2-3 min) — Show the expected result. Walk through what a good output looks like and why. Students who paused get confirmation. Students who didn't still see the result and get partial benefit.

Rules:
- The application task must be completable in under 10 minutes. If it takes longer, scope it down.
- The task must produce a *visible result* the student can compare against the payoff.
- Never make the application feel optional. Frame it as the next step, not a sidebar.

### Phase 5: SYNTHESIS (3-5 min)
**Function:** Connect this module to the course arc. Give the student a capability statement and hand off to the next module.

Three beats:
1. **Restatement** — The core concept in one sentence. Different words than the checkpoints used earlier.
2. **Capability statement** — "You can now [concrete thing] that you couldn't before this module." This is the progress signal. It must be specific and testable — the student should be able to verify it.
3. **Forward link** — What the next module builds on top of this one. Creates pull to continue.

Rules:
- No "In this module we learned..." recaps. The student just watched it.
- The capability statement is the most important sentence in the synthesis. Get it right.

## Module Variants

Not every module fits the standard five phases. The framework has four variants:

### Standard (default)
HOOK → MECHANISM → DEMONSTRATION → APPLICATION → SYNTHESIS

Use for: Modules that teach one core concept with a clear mechanism and a demonstrable behavior.

### Nested-Loop (for multi-part frameworks)
HOOK → [MECHANISM → DEMO → APPLICATION] x N → SYNTHESIS

Use for: Modules that introduce a framework with multiple beats (e.g., DEFINE → GATE → BUILD → CHECK). Each beat gets its own mechanism-demo-application cycle, but the module shares a single hook and synthesis. Keep each inner loop to ~10 min to avoid bloat.

### Feature-Tour (for dense feature coverage)
HOOK → [MINI-MECHANISM (1 min) → DEMO (2 min)] x N → APPLICATION (one integrative task) → SYNTHESIS

Use for: Modules covering multiple features or tools. Each feature gets a compressed mechanism + demo, but the application phase is a single integrative task that uses several features together. This prevents the module from becoming a disconnected feature list.

### Capstone (for integration/closing modules)
HOOK → INTEGRATION (replaces mechanism) → DEMONSTRATION (full workflow) → APPLICATION (build your system) → HANDOFF

Use for: Final modules that integrate prior learning. INTEGRATION replaces MECHANISM — instead of new theory, it weaves together concepts from prior modules. HANDOFF replaces SYNTHESIS — it points the student to the next concrete step (e.g., the vault bonus module).

## Script Format

Scripts are written for two delivery modes:
- **Narration** (ElevenLabs TTS voice clone) — the default. All mechanism, hook, application setup, and synthesis sections.
- **Demo** (Nick's live voice over screen recording) — all demonstration sections and application payoffs.

### Narration Script Rules (TTS)
- Write for spoken delivery. No visual-only references ("as you can see below").
- Punctuation is pacing. Em dashes for mid-thought pauses. Periods for full stops. Commas for breath beats.
- Spell out abbreviations on first use: "LLM — large language model."
- No filler ("basically", "actually", "you know").
- Sentence length: mostly short (8-15 words). Occasional long sentence for rhythm, never back-to-back.
- Three-beat structures carry the WorkflowOS voice: "Build the prompt. Run the check. See what changes."

### Production Notes in Script
Mark sections clearly with production tags:

```
[NARRATION — TTS]
Script text here...

[DEMO — LIVE VOICE + SCREEN RECORDING]
Demo description and talking points here...
Nick records this section live over screen capture.

[PAUSE — STUDENT APPLICATION]
Application task setup narrated via TTS, then pause prompt.

[NARRATION — TTS]
Application payoff narrated...
```

## Timing Constraints

Research-backed guardrails:
- **Total video per module:** 25-45 min (standard), up to 60 min (nested-loop, with breaks)
- **Individual video segments:** 5-12 min max before a checkpoint or mode switch
- **Application active time:** 5-10 min (student's time, not video time)
- **Full course (7 modules + vault bonus):** 3.5-5.5 hours of video. Target the lower end.

If a module draft exceeds 45 min, compress the mechanism section first — it's the most likely to bloat.

## Quality Checks

Before finalizing any module script, verify:

1. **Mechanism earns the protocol.** Could the student skip Phase 2 and still follow Phase 4? If yes, the mechanism section is decorative. Rewrite.
2. **Honest scope.** Are all claims properly scoped? No stat used outside its research context? No "studies show" without naming the study?
3. **Application is specific.** Does the student know exactly what to type into Claude, what to expect back, and how to evaluate the result? Vague application tasks get skipped.
4. **Capability statement is testable.** Could the student verify the capability claim right now? "You understand context better" fails. "You can structure a 10-page document in Claude's context window and get consistent quality from beginning to end" passes.
5. **Voice check.** Read the hook and synthesis aloud. Does it sound like WorkflowOS or like a textbook? Check against global REFERENCE.md voice rules and banned words.
6. **Time check.** Estimate narration time (150 words/min for TTS, ~130 for live demo). Does it fit the timing constraints?
7. **Template fatigue check.** Does this module's hook use a different execution variant than the previous module? Does the synthesis feel distinct?

## Workflow

When Nick asks to script a module:

1. Read `references/PEDAGOGY.md` for the full research context
2. Read the course's `REFERENCE.md` for locked decisions about this module
3. Read global `REFERENCE.md` for voice and banned words
4. Identify the correct module variant (standard, nested-loop, feature-tour, capstone)
5. Draft the script in the five-phase structure with production tags
6. Run the seven quality checks
7. Flag any structural decisions that need locking before the script is final
