# How to Use This Repository

A guide to working with the tSAC universe repository effectively.

---

## Repository Purpose

This repository is the canonical source of truth for all tSAC worldbuilding, game system mechanics, and story content. It is designed to work alongside AI models as persistent, portable context.

---

## Quickstart

### Starting a New AI Session

1. Open a new chat with your AI model of choice
2. Paste the contents of `AI_CONTEXT/prompt_seed.md`
3. Optionally paste `AI_CONTEXT/tsac_master_context.md` for full context
4. Paste any specific canon files relevant to your task
5. Describe your task

### Working on Canon

- Read the relevant files in `CANON/` before making changes
- Review `AI_CONTEXT/canon_rules.md` before adding or modifying anything
- Never edit canon files based on AI output alone — always verify first
- Once confirmed, update the appropriate `CANON/` file and update `INDEX.md` if a new file was added

### Working on System Mechanics

- System files live in `SYSTEM/`
- Changes to mechanics should be tested against the existing canon to ensure consistency
- Cross-reference with `CANON/metaphysics/` when mechanics touch on supernatural elements

### Working on Story

- Story arcs and outlines live in `STORY/`
- Story content is not canon until explicitly confirmed and moved to or referenced from `CANON/`
- Use `SCRATCHPAD/` for rough ideas before they are ready for `STORY/`

---

## File Naming Conventions

- All files use `snake_case.md`
- Canon files are named after the subject they describe
- No version numbers in filenames — use git history for versioning

---

## Workflow Summary

```
Idea → SCRATCHPAD/ → (review) → STORY/ or CANON/ → INDEX.md updated
```

---

## Keeping Context Fresh

When returning to a project after a gap:

1. Re-read `AI_CONTEXT/tsac_master_context.md`
2. Check `SCRATCHPAD/raw_conversation_extractions.md` for recent unprocessed ideas
3. Review `CANON/timelines/current_age.md` to re-orient on story present
4. Check `STORY/outlines/major_plot_threads.md` for active threads

---

## Sensitivity

This project is marked **private**. Do not share content from this repository in public forums or with third-party services without review.
