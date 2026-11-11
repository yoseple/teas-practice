# TEAS Practice (teas-practice)

A free, single-page study site with three ATI TEAS 7 practice exams and 183 original questions. Everything lives in `index.html` (plain HTML, CSS and JavaScript, no build step); progress is saved only in the browser's `localStorage`. Repo: github.com/yoseple/teas-practice (public). Live: https://yoseple.github.io/teas-practice/ (GitHub Pages deploys from `main`). See `README.md` for features and accuracy notes.

## Project manager (standing rule)

The project's PM is the `project-manager` agent: `.claude\agents\project-manager.md` (tailored from `~/.claude/agents/project-manager.md`). It reports to the owner (the Supervisor) in the fixed PM REPORT format.

- **Use it** at the start of any multi-step task, when work finishes, when something is blocked, and whenever the owner asks for status.
- **It owns the vault Task Board:** `C:\Users\yosep\AI-Software-Factory\00-Obsidian-Vault\07-Build-Tickets\TEAS Practice\Task Board.md`. Every open task has exactly one owner from the Dashboard's **Team & Roles** roster.
- **Every task ends with a PM report.** The PM updates this project's row in `00-Obsidian-Vault\00-Supervisor\Portfolio Board.md` and adds the report to `00-Supervisor\PM Reports\<YYYY-MM>.md`.

If the vault path doesn't exist on this machine (someone else's clone), skip this section.

## Obsidian brain (standing rule)

The project's persistent brain lives in the owner's master Obsidian vault:

```
C:\Users\yosep\AI-Software-Factory\00-Obsidian-Vault\07-Build-Tickets\TEAS Practice\
  TEAS Practice Dashboard.md   (hub + map of content + key decisions)
  STATUS.md                    (THE live resume anchor — open first)
  Build Log.md                 (append-only changelog, newest on top)
```

If the vault path doesn't exist on this machine (someone else's clone), skip this section.

**After every meaningful change — a completed task, phase, shipped fix, or decision (once per task, NOT once per commit) — before the turn ends:**

1. **Build Log.md** — add a dated entry at the TOP: `## YYYY-MM-DD — <summary>` with what changed, why, and how it was checked.
2. **STATUS.md** — refresh where things stand, the next action, the HEAD hash, and the frontmatter `updated:` date.
3. **TEAS Practice Dashboard.md** — update it if facts changed (status line, live URL, decisions, links); bump `updated:`.

Conventions: frontmatter keys `type/project/updated/purpose` on every vault note; NO hashtags; plain short sentences; wikilinks path-qualified for colliding basenames (e.g. `[[07-Build-Tickets/TEAS Practice/STATUS|STATUS]]`). Never write secrets or personal data into the vault.
