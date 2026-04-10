# REFERENCE.md — Domain Knowledge (Locked)
# ─────────────────────────────────────────────────────────────────────────────
# STATUS: locked
# PULL WHEN: [define the task context that should trigger loading this file]
#
# This file holds everything Claude needs to know about your domain that
# doesn't change session to session. It is the source of truth.
#
# When this file changes, every skill and task that reads it inherits the update.
# Update it deliberately. Mark it locked when stable.
# ─────────────────────────────────────────────────────────────────────────────

## VOICE & TONE
# How you sound. Register, energy, sentence structure, what "good" feels like.
# Be specific — "professional but warm" is not useful. Show examples.

[Define your voice here]

**Good examples:**
- [Paste a line or two of output you loved]
- [Another example]

**Bad examples (what to avoid):**
- [A line that sounds wrong for your brand]


## BANNED VOCABULARY
# Words and phrases that should never appear in output.
# Include the reason — it helps Claude understand the spirit of the rule.

→ [word or phrase] — [why it's banned]
→ [word or phrase] — [why it's banned]
→ [word or phrase] — [why it's banned]


## OUTPUT FORMAT
# How you want things structured. Length, headers, lists vs. prose, etc.

[Define your format expectations here]

- Length: [e.g., "Keep responses under X words unless asked to go long"]
- Headers: [e.g., "Use headers for documents, not for conversational responses"]
- Lists: [e.g., "Avoid bullet lists unless content is genuinely list-like"]
- Code: [if relevant]


## DOMAIN CONSTRAINTS
# Rules specific to your context that Claude needs to know.
# Things that aren't obvious from the task but affect every output.

[List your domain-specific constraints here]


## QUALITY TESTS
# Explicit checks any output must pass before being shown.
# Turn your "taste" into a checklist.

Before delivering any output, verify:

- [ ] [Test 1 — e.g., "Could this have been written by someone who doesn't know this brand?"]
- [ ] [Test 2 — e.g., "Does it contain any banned vocabulary?"]
- [ ] [Test 3 — e.g., "Is every claim specific and verifiable?"]
- [ ] [Test 4]


## HOW TO WORK WITH ME
# Communication preferences. What "done" looks like. What to never do.
# This prevents tone drift and makes corrections compound into the file.

[Define your working style preferences here]

- Corrections: [e.g., "If I flag a line, revise that line only — don't rewrite the whole piece"]
- Questions: [e.g., "Ask one question at a time, not a list of five"]
- Format: [e.g., "No preamble — lead with the answer"]
- Done means: [e.g., "Ready to use without editing, not 'here's a draft'"]
