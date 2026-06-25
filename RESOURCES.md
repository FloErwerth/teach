# AI-Assisted Coding (Human-in-the-loop) Resources

## Knowledge

- [Local skill: `grill-with-docs/SKILL.md`](file:///Users/forli/.agents/skills/grill-with-docs/SKILL.md)
  **Primary source.** The actual installed skill that defines the grilling loop:
  relentless one-question-at-a-time interview, recommend an answer each time,
  explore the codebase instead of asking when possible, update `CONTEXT.md` and
  ADRs inline. Use for: anything about how a grill session should run.
- [Local: `grill-with-docs/CONTEXT-FORMAT.md`](file:///Users/forli/.agents/skills/grill-with-docs/CONTEXT-FORMAT.md)
  Canonical format for the project glossary. Use for: how to write CONTEXT.md.
- [Local: `grill-with-docs/ADR-FORMAT.md`](file:///Users/forli/.agents/skills/grill-with-docs/ADR-FORMAT.md)
  When and how to record an architectural decision. Use for: the 3-part ADR test.

## Wisdom (Communities)
- [AI Hero — "things people get wrong with grill-me and grill-with-docs"](https://www.aihero.dev/things-people-get-wrong-with-grill-me-and-grill-with-docs)
  Matt Pocock. **Learner-endorsed** (pointed us here directly). The 9 common
  grilling mistakes. Source for: grill with a strong model (parametric vs.
  contextual knowledge), scope one grill small, the grill→prototype→grill loop for
  high-fidelity questions, "a conversation, not an interview" (don't go passive),
  and don't `/clear` after a grill. Woven into Lessons 1–3 and the Playbook.

## Tooling
- [Matt Pocock's skills repo](https://github.com/mattpocock/skills) +
  [skills.sh CLI](https://skills.sh). Install globally with
  `npx skills@latest add mattpocock/skills --global`. Verified on this machine:
  global installs land in `~/.agents/skills/<skill>` and symlink into each agent
  dir (e.g. `~/.claude/skills/grill-with-docs -> ../../.agents/skills/grill-with-docs`).
  Use `-s/--skill` to pick skills, `-a/--agent` to pick agents, `-l/--list` to list.
  Cross-platform (macOS + Linux). Source for Lesson 0.

## Gaps
- No verified community/forum for AI-assisted-engineering practice yet.
