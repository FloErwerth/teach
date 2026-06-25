# Working Notes & Preferences

## About the learner
- Daily Claude Code user. Skip beginner framing. Treat as a peer practitioner.
- Stack: TypeScript, React Native, Expo, React.
- Handoff: PRs gated by required CI.
- Wants a *deliberate, manual* method — explicitly rejects automated/agentic workflows.

## How to teach this person
- Ground every lesson in a real change they'd actually make to their codebase.
- Prefer "run this on a real ticket today" tasks over toy exercises.
- Keep lessons short; they're busy professionals.

## Process notes
- The `grill-with-docs` skill is installed locally at
  `~/.agents/skills/grill-with-docs/` — that SKILL.md is our ground-truth primary source.
- Install mechanics (verified this session): `skills` CLI via
  `npx skills@latest add mattpocock/skills --global` → source in `~/.agents/skills/<skill>`,
  symlinked into each agent dir (`~/.claude/skills/...`). Lesson 0 teaches this.
- Learner-endorsed external sources now in play (no longer "unverified"): the AI Hero
  "things people get wrong with grill-me/grill-with-docs" article and the mattpocock/skills
  repo. The learner pointed us to both directly. See RESOURCES.md.
- The AI Hero "9 mistakes" are woven into Lessons 1–3 + the Playbook (model choice,
  scope, prototype-handoff, active steering, don't-clear-the-context).
- No code-review skill is installed; we teach review as a learner-driven practice.
