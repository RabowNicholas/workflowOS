# COURSE — REFERENCE

Locked structural decisions for the Claude Power User Course. Pull for any course scripting, module structure, sales copy, or positioning decision. For voice and banned language, also pull global REFERENCE.md.

<course_structure>
CLAUDE POWER USER COURSE — vault bonus rule.

The free WorkflowOS vault PDF stays the lead magnet, unchanged. It teaches the concept and ships working templates. Its job is awareness at the top of the funnel.

The Claude Power User Course includes a Vault Bonus Module as its closing deliverable. Rules:

- Position: AFTER Module 7, not before Module 1. The course's tone benchmark is "mechanism before protocol" — teaching the vault install before the mechanism would violate the rule the course is built on. Module 7's "now you know" is designed to hand off to a real artifact.
- Format: ONE video, ~30–45 min. "Your First Vault Session" — narrated live run-through on a real task, showing the close-out protocol and file updates. Compounding gets explained inside the video, not spread across multiple sessions.
- Companion: one-page Week 1 Field Guide (written, lightweight). Day 3 and Day 7 touchpoints. Video is the activation, guide is the scaffolding.
- Differentiator from the free lead magnet: the paid version is a watch-me demo, not more PDFs. Never ship the bonus as another written artifact.
- Sales page framing: "by the end of this course you'll be watching a real vault session and walking away with yours running." Concrete outcome, not abstract understanding. This also resolves the prerequisite question — cold and warm buyers converge on the same deliverable.

MODULE 1 — framing and opening arc.

- Universal vs Claude-specific: the course's frameworks are largely LLM-universal; the application is Claude-specific. Module 1 names this honestly, early, in one paragraph. Do NOT force fake Claude differentiation into every lesson of Modules 2–4 and 6–7. The Claude-ness lives in Module 5, the vault bonus, and the fact that every demo/example/screen recording is inside Claude.
- Opening hook is Constitutional AI / RLAIF, NOT "you asked it something and it was confidently wrong." Cold-buyer ChatGPT power users already know next-token prediction; they don't know (or don't have a name for) Claude's training difference. Lead with the one thing they can't get from any other model.
- Revised Module 1 arc:
  1. Constitutional AI as opener (~5 min) — "you've probably noticed Claude feels different. Here's the technical fact that explains most of it."
  2. Predictive machine mental model (~15 min) — Mollick's Infinite Copies of Steve, weather forecasting, etc.
  3. Five behaviors the mental model explains (~15 min) — hallucinations, inconsistency, confidence ≠ correct.
  4. Close the loop back to Constitutional training (~10 min) — why it matters for Modules 2–7.
- Voice constraint: the Mollick analogies are Mollick's. The Constitutional AI explanation must be unmistakably WorkflowOS voice — this is the lead hook and the buyer's first trust signal.
- Production note: ElevenLabs voice clone handles narration; Nick's live voice is reserved for demos. Module 1's Constitutional AI opener is narration, so the script must be written for TTS — unambiguous pronunciations, punctuation as pacing, no throwaway filler.

HEADLINE IP — the course's named framework.

- The course's headline IP is DEFINE → GATE → BUILD → CHECK. Not "understand how Claude works." Module 1 is the mechanism that earns the right to teach the framework; the framework is the destination.
- GATE is the distinguishing feature inside the framework — Nick's original named technique, academically anchored to Laban et al. 2025 and QAP (Yugeswardeenoo et al.). GATE alone is a technique; the four-beat is a discipline. Always lead with the four-beat, use GATE as its sharpest tooth.
- Four-beat maps to four failure modes: DEFINE fixes "no success sentence," GATE fixes "let Claude fill gaps with probability," BUILD fixes "magic phrasing instead of intent+context+examples+format," CHECK fixes "iterate on vibes instead of verifying against success sentence."
- Module 4's title includes the framework: "Prompting as a Discipline: DEFINE → GATE → BUILD → CHECK." The IP belongs in the table of contents.
- Sales page hero is the framework promise, NOT "understand how Claude works." In voice: lead with the four-beat as the named fix for the #1 reason prompts fail.
- Module 7 capstone gives the full four-beat its own air in the Six Frameworks in Six Lines section — one line per beat, not collapsed.
- Defensible IP claim: the four-beat ordering, the GATE technique, and the specific failure-mode mapping. DEFINE/BUILD/CHECK have analogues across prompting discourse — do not overclaim originality on those beats. Overclaim is a trust-killer for this buyer.

PRODUCTION — voice and TTS rules.

- ElevenLabs voice clone: narration (all module voiceover).
- Nick's live voice: demos only (screen recording walkthroughs).
- All narration scripts written for TTS: unambiguous pronunciations, punctuation as pacing, no filler, no ambiguous acronyms without context on first use.
- Pop culture references: movies and TV shows used as teaching analogies throughout. These are recognition anchors — the student hears something they know and wires the concept to existing memory. References should feel natural to WorkflowOS voice (builder-to-builder, not "as the great philosopher Yoda once said"). Clip-friendly: written so short scenes can be cut into the video alongside narration.

MODULE 2 — 1M context rewrite.

- Treat as a content revision, not a find-and-replace. Core thesis flips from scarcity to curation.
- New core thesis: context engineering is curation, not budgeting. The window is bigger than you'll usually fill, but attention isn't uniform, position still matters, and persistent context across sessions is where the real compounding happens.
- Token counts: Opus 4.6 / Sonnet 4.6 = 1M tokens. Haiku 4.5 = 200K.
- Real-world counts (1 page ≈ 400 tokens, etc.) stay accurate but reframe as "how much you could fit" — emphasize most users never hit the ceiling on a single task.
- "Lost in the Middle" paper is Claude 1.3 era. Cite as the origin of the phenomenon (attention non-uniformity), NOT as current Claude behavior. Specific percentages do not transfer to Claude 4.6 at 1M.
- Cut entirely: the "degradation starts at ~20% context usage" claim. Unverified for current models and doesn't survive the 1M transition.
- No published benchmarks for Claude 4.6 at 1M context exist. Lesson leans on attention non-uniformity as a general principle; acknowledge the research gap honestly.
- What survives: Mr. Meeseeks opening hook, Karpathy CPU/RAM analogy, Lütke quote, XML tags for separation, top/bottom vs middle composition rule.
- Lesson 4 (Projects and Persistent Context) gets reframed as "the real payoff" — single sessions can hold entire codebases, persistent context across sessions is where compounding happens. Explicit foreshadow of the vault bonus: "this is the infrastructure you're building yours on."
- Closing protocol: audit last 3 sessions. Where did important info sit? You were probably working at 200K assumptions. Restructure one session using the 1M framing. Compare output.

NARRATIVE ARC — course-level one-liner.

Locked: Understand the machine → understand its core variable → choose the right tool → apply prompting as a discipline → compound it with the features only Claude has → debug systematically → build one system you actually use.

- "Compound" is the chosen verb for Module 5's role in the arc. Module 5's features (Projects, Prompt Caching, Adaptive Thinking, MCP, Dispatch, Computer Use, Citations, Batch, Files API, CLAUDE.md auto-memory) compound the DEFINE → GATE → BUILD → CHECK framework into something no other model can replicate. This also makes Module 5's Claude-specificity explicit in the course's top-line description.

VAULT BONUS — cascade edits to Modules 5 and 7.

- Module 5: when the lesson hits Projects and CLAUDE.md auto-memory, narration acknowledges (two-sentence foreshadow each) that the bonus module shows both running inside a real vault. Not a rewrite — a framing. Features still get taught as features; the student just hears "this is what you're about to build on" at the right moment.
- Module 7 closing: keep the thesis line ("the machine is predictable when you treat it predictably"). Add a three-beat handoff after it: thesis restated → acknowledgment of what the student just learned → direct handoff to the bonus. Example: "The machine is predictable when you treat it predictably. You know the machine now. The next step is building the room it lives in — that's the bonus module. Meet me there." "Meet me there" is the first moment the narration becomes relational instead of instructional, which is the right beat at the handoff point.

SALES / POSITIONING — mastery, not outcomes.

- The course sells mastery, not outcomes. All sales copy, course descriptions, and testimonial requests frame the value as understanding, discipline, and mental model — never as templates, results, or job-specific outputs. Outcome testimonials ("I 10x'd my output") pull the wrong buyer; mastery testimonials ("I finally understand why Claude was ignoring half my instructions") pull the right one.
- Niche courses ($497–$997) are positioned as the natural next step AFTER the framework is learned, not as an alternative. The $97 → $497 jump is justified by applying the framework to a specific role with real workflows and examples — not by adding more content volume.
- Sales page must include a declarative (not defensive) "this is not a template course" section. Language like: "This is not a cold email course. Not a LinkedIn course. Not 47 prompts you can copy and paste. It's the discipline underneath all of those." Filters wrong buyer, flatters right buyer, reframes absence of templates as feature.
- Sales page must include a "who this is NOT for" section near the bottom. Honest, no mercy. Buyers who self-exclude here don't refund.
- No refund policy. Mastery courses with clear "not for" sections have low refund rates; a policy invites friction at the $97 price point without changing the purchase decision meaningfully. The clarity of the "not for" section replaces the refund as the buyer's trust signal.
- Tone benchmark reinforcement: Huberman-style mechanism-first content. Rigor in the promise, accessibility in the delivery, outcomes implied but never explicitly promised.

PEDAGOGICAL FRAMEWORK — five-phase module structure.

Locked 2026-04-10. All modules use the five-phase framework defined in the course-script-writer skill. Phases: HOOK → MECHANISM → DEMONSTRATION → APPLICATION → SYNTHESIS. Four module variants: standard, nested-loop (Module 4), feature-tour (Module 5), capstone (Module 7). Module 1 uses standard with a comparison demo for Constitutional AI.

Key constraints:
- Total video per module: 25-45 min (standard), up to 60 min (nested-loop)
- Individual segments: 5-12 min max before checkpoint or mode switch
- Mechanism section: 30-40% of module time, never more than 15 min
- Application tasks: completable in under 10 min, produce visible result, degrade gracefully
- Each synthesis includes a testable capability statement
- Hook variants rotate across modules (confession, provocation, failed prompt)
- Module bridges connect to prior module's takeaway (Module 1 skips)

Module variant assignments:
- Module 1 (Constitutional AI): Standard, comparison demo
- Module 2 (Context window): Standard
- Module 3 (Model selection): Standard
- Module 4 (DEFINE → GATE → BUILD → CHECK): Nested-loop, four inner cycles
- Module 5 (Claude features): Feature-tour, cap at 5-6 features with full treatment
- Module 6 (Debugging): Standard
- Module 7 (Capstone): Capstone variant, integration + handoff to vault bonus

Teaching style: Huberman-adapted mechanism-first pedagogy, compressed for screen-based self-paced learners. Full research and rationale in course-script-writer skill's references/PEDAGOGY.md.

MODULE 6 — 41.8% stat correction.

- The 41.8% figure is REAL but was misframed in the original outline. Verified source: Cemri, Pan & Yang (2025), "Why Do Multi-Agent LLM Systems Fail?", arXiv:2503.13657. The paper analyzes 1,642 multi-agent system execution traces across seven MAS frameworks and finds: specification and system design issues 41.8%, inter-agent misalignment 36.9%, verification failures 21.3%.
- The stat is about multi-agent systems specifically, NOT all LLM systems. The "specification and design" category includes multi-agent-specific failure modes (duplicate agent roles, missing termination conditions) that do not exist in single-conversation workflows. The target student is not building multi-agent systems.
- DO NOT ship the original Module 6 core thesis ("41.8% of all LLM system failures are specification problems") — it's an overclaim that a careful reader will catch in 30 seconds and lose trust over.
- Replacement core thesis (directional, defensible across multiple sources): "Across the research on why LLM systems fail — single-agent and multi-agent, simple and complex — specification and design problems dominate. The model usually isn't broken. Your description of the task is." Anchored by Cemri et al. 2025 (multi-agent), Laban et al. 2025 (single-agent, already cited in M4), and arXiv:2602.07338 (intent mismatch, already in M6 sources).
- The 41.8% stat still lands, but in the right place: later in Module 6, when the lesson talks about what happens as workflows grow complex enough to need multi-agent thinking. In that context: "In multi-agent systems — the kind you'll build if you stick with this — 41.8% of failures are specification and system design issues (Cemri et al. 2025). Even when the architecture gets harder, the failure mode doesn't change. You're still mis-specifying."
- Reference list cleanup: the outline lists both "OpenReview fAjbYBmonr" and "arXiv:2503.13657" as separate sources; they are the same Cemri et al. paper hosted in two places. Collapse to one citation: Cemri, Pan & Yang (2025), arXiv:2503.13657. The fAjbYBmonr URL in the outline is malformed (arxiv.org prefix with OpenReview paper ID) — remove.
</course_structure>
