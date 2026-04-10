# INDEX.md — Project Vault Registry
# ─────────────────────────────────────────────────────────────────────────────
# This is the first file Claude reads every session.
# It is a registry only — no content lives here, only pointers.
# Keep it short. Keep it current.
# ─────────────────────────────────────────────────────────────────────────────

## HOW TO USE THIS FILE
# At the start of every session, instruct Claude to:
# 1. Read this file first
# 2. Read ACTIVE.md to see open loops
# 3. Pull only the reference files the task requires

## VAULT FILES

| FILE             | SCOPE                                  | STATUS   | PULL WHEN                          |
|------------------|----------------------------------------|----------|------------------------------------|
| ACTIVE.md        | Open loops + session log               | live     | Every session — always read first  |
| REFERENCE.md     | [Your domain rules, voice, constraints]| locked   | [Any task involving your domain]   |

## STATUS DEFINITIONS
# locked   → stable, pull on demand, changes rarely
# live     → actively used, may evolve
# in-flux  → currently being built or revised, treat as incomplete

## SESSION PROTOCOL (paste this at the start of new conversations)
#
# Start every session by:
# 1. ORIENT — Read INDEX.md, then ACTIVE.md. Know what's open and what exists.
# 2. PULL — Based on the task, load the relevant reference files listed above.
# 3. CLOSE — Before ending: update ACTIVE.md, progress or close loops, log session.

## NOTES
# Add any vault-level notes here — things Claude should know about how this
# project is structured that don't belong in a specific reference file.
