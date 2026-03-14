# CLAUDE.md

## gstack

Use the `/browse` skill from gstack for all web browsing. Never use `mcp__claude-in-chrome__*` tools.

Available skills:
- `/plan-ceo-review` — Rethink the problem from a founder/CEO perspective. Find the 10-star product.
- `/plan-eng-review` — Lock in architecture, data flow, diagrams, edge cases, and tests.
- `/review` — Paranoid staff engineer review. Find bugs that pass CI but break in production.
- `/ship` — Sync main, run tests, push, open PR. For a ready branch.
- `/browse` — Headless browser for QA. Navigate, click, screenshot, verify.
- `/qa` — Systematic QA testing. Diff-aware, full, quick, or regression modes.
- `/setup-browser-cookies` — Import cookies from your real browser for authenticated testing.
- `/retro` — Team-aware engineering retrospective with metrics and per-person feedback.

If gstack skills aren't working, run `cd .claude/skills/gstack && ./setup` to build the binary and register skills.
