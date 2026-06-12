# CLAUDE.md — *The Fitting Room*

> Read first, every session. This is a **literary domestic suspense** novella built with The Novel Engine (`framework/`).

## Use these skills (mandatory)
The craft skills live in `.claude/skills/`. Load the relevant one for each task:
structure-storyteller (architecture), prose-craftsman (line voice), continuity-keeper
(`STORY-BIBLE.md` = source of truth), project-manager (`PRODUCTION-PLAN.md` = tracker),
revision-partner (stage/process), motivation-coach (unblocking), research-integrator (Bath geography, conservation-officer procedure, kintsugi).

## Drafting mode
- **Compressed drafting: TRUE.** Draft each chapter with the **compress-fiction** skill (~fewer output tokens) → `chapters-long/chNN-compressed.md`, composed at full literary quality and spelled compressed. Expand outside this env with `.claude/skills/compress-fiction/expand-prompt.md`. Keep compressed files as the source of truth; treat expanded prose as a build artifact.

## The framework
- **`framework/METHOD.md`** — the build pipeline (Phase 0 spec → 5 revise) + the non-negotiable Laws.
- **`framework/QUALITY-CHECKLIST.md`** — the per-scene / per-chapter / book gates.
- **`STORY-SPEC.md`** — the knobs (Phase 0, complete). `OUTLINE.md` (Phase 1), `STORY-BIBLE.md` (Phase 2), `PRODUCTION-PLAN.md` (Phase 3) — all complete.

## The story in one breath
An unreliable narrator (Daniel) buys his wife an anniversary scarf at closing time, never grasping the shopgirl is his mistress, the silk is a message, and his wife found out months ago and befriended the other woman. Ends on his delusion, not his punishment: *She must have stepped out to surprise me.* **Do not let Daniel ever realize; do not give Clare a POV; decode the truth through gaps, not exposition.**

## Production policy
- 5 chapters · **every chapter ≥ 6,000 words** · total ~37,500.
- Reach length via **three woven B-plots** (Mara's exit; the failing frontage; Clare's kintsugi), never padding (Law 4).
- Scenes marked `◆`, each tagged with POV.
- Develop on branch **claude/serene-mccarthy-jcwqyx**; commit + push after every pass (Law 7).

## Current next action
Phase 4 — draft `chapters-long/ch01-compressed.md` (Closing Time), then gate with `framework/QUALITY-CHECKLIST.md`, update the tracker, commit, push.
