# Profile README Refresh Implementation Plan

> **For agentic workers:** REQUIRED SUB-SKILL: Use superpowers:subagent-driven-development (recommended) or superpowers:executing-plans to implement this plan task-by-task. Steps use checkbox (`- [ ]`) syntax for tracking.

**Goal:** Build a recruiter-focused GitHub profile README aligned with `saeedghofrani.xyz`.

**Architecture:** This is a static GitHub profile repository. The implementation updates `README.md` only for user-facing content and adds workflow documentation under `docs/superpowers/`.

**Tech Stack:** GitHub profile README markdown, HTML-compatible markdown, existing local SVG/PNG assets, external GitHub stats widgets.

---

### Task 1: Replace Profile README

**Files:**
- Modify: `README.md`

- [x] Replace the old badge-heavy profile with a portfolio-aligned hero, recruiter signal table, capability map, proof map, review paths, core stack, current focus, and cleaned-up GitHub activity.
- [x] Reuse existing local banner, social icons, language icons, framework icons, and database icons.
- [x] Keep GitHub stats widgets below the main recruiter story.

### Task 2: Add Workflow Documentation

**Files:**
- Create: `docs/superpowers/specs/2026-07-01-profile-readme-refresh-design.md`
- Create: `docs/superpowers/plans/2026-07-01-profile-readme-refresh.md`

- [x] Save the approved design as a concise spec.
- [x] Save this execution plan with exact touched files and verification steps.

### Task 3: Verify and Publish

**Files:**
- Inspect: `README.md`
- Inspect: git diff

- [x] Run a local asset-reference check for README image paths.
- [x] Inspect `git diff -- README.md docs/superpowers/specs/2026-07-01-profile-readme-refresh-design.md docs/superpowers/plans/2026-07-01-profile-readme-refresh.md`.
- [ ] Commit with message `docs: refresh GitHub profile readme`.
- [ ] Push branch `codex/profile-readme-refresh` to `origin`.
