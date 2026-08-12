# AGENTS.md — ShadowWalkerNC

> **Extends:** `ShadowWalkerNC/.github/AGENTS.md` — all global rules apply unconditionally.
> **Purpose:** Project-specific overrides and context for AI agents working in this repository.
> **Auto-loaded by:** Claude Code · GitHub Copilot · OpenAI Codex · Cursor · Windsurf

---

## Project Identity

```
Project:      ShadowWalkerNC
Description:  GitHub Profile README
Status:       active
Phase:        Profile maintenance
Priority:     active
```

---

## Tech Stack

```
Language:     Markdown · HTML · CSS (inline in README)
Framework:    None — plain GitHub profile README
Database:     None
Hosting:      GitHub Pages / raw.githubusercontent.com (assets)
Key APIs:     External badge & image services: capsule-render.vercel.app, komarev.com,
              shields.io, readme-typing-svg.demolab.com, github-readme-stats.vercel.app,
              streak-stats.demolab.com, github-readme-activity-graph.vercel.app
CI/CD:        Manual commits to main
```

---

## Repository Structure

```
README.md          ← the profile page content (THE key file)
AGENTS.md          ← this file — agent context for this repo
assets/
  Shadow-Realm.PNG ← profile logo (must stay optimized, used at width="96")
```

---

## Key Files for Every Agent Session

```
README.md          ← entire deliverable — the profile page that renders on github.com/ShadowWalkerNC
AGENTS.md          ← this file
```

> ARCHITECTURE.md, TODO.md, CHANGELOG.md, and `.env.example` do **not** exist in this repo.
> This is a docs-only repository — the README *is* the product.

---

## Active Agents for This Project

Default agents per AGENT_DISPATCH activation matrix. List any project-specific overrides:

```
Always active:  COHERENCE · SECURITY · DOCS
Project default on-demand: DOCS (primary) — every change to this repo is documentation
Rarely needed:  ENGINEER · DATABASE · UX · QA · BUSINESS · AI
```

---

## Project-Specific Rules

List any rules that override or extend the global AGENTS.md for this project only.
Global Tier 1–3 rules cannot be overridden here.

```
- Keep the README accurate: project statuses, repo links, and milestones must match the
  real state of the public repos they point to — never link a repo that is private or missing.
- Optimize every image before committing. Target < 200 KB per file. The logo is displayed
  at width="96" — do not commit oversized source images.
- The profile README relies on external badge/image services. When adding one, verify it
  renders and that its URL pattern will not expire or depend on private repo data.
- Do not commit files that are not referenced by the README (or this file).
- Direct commits to main are fine for this repo; commits must be small and focused
  (one concern per commit).
```

---

## Environment Variables

| Variable | Required | Description |
|---|---|---|
| *(none)* | — | This repo has no environment variables or secrets. |

Never commit values. Always use `.env.example` for the key list.

---

## Current Phase Context

```
Phase goal:     Keep the profile accurate, fast-loading, and professional while the
                CulinaryOS suite and other projects are in active development.
Definition of done: Every project table row, badge, and repo link reflects the current
                public state; assets are optimized; no broken images or dead links.
Blocking issues: None.
Next phase:     Update the "Now Building" milestones as CulinaryOS / KitchenKit /
                CulinaryOps / Post-Pilot progress or launch.
```

---

## Known Issues / Watch List

List anything an agent should be aware of before working in this repo:

```
- All dynamic badges/stats depend on third-party services (vercel, komarev, shields.io,
  demolab). If one is down or rate-limited, the profile will show broken images — the
  README itself is not at fault.
- github-readme-stats `count_private` only reflects public activity; private repo work
  will not show in the contribution graph widgets.
- The README is large (~35 KB). GitHub fully renders profile READMEs, but keep additions
  lean — prefer details/summary blocks for long content.
- Repo links must be validated when projects are renamed or archived (e.g. Shoreline → 
  ShorelineOps, RestRevive-AI → CulinaryOps).
```

---

## Agent Confirmation for This Repo

After loading this file, the agent must add to its `DISPATCH CONFIRMED` block:

```
Project AGENTS.md: loaded
Project: ShadowWalkerNC
Stack: Markdown / HTML / CSS — GitHub profile README
Phase: Profile maintenance
Project rules active: 5 overrides
Known issues noted: yes
```

---

*Filled from template 1.0 | Extends: ShadowWalkerNC/.github/AGENTS.md | Repo: [ShadowWalkerNC](https://github.com/ShadowWalkerNC/ShadowWalkerNC)*
