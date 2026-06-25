# Mission: Deliberate, human-in-the-loop AI coding (no automated agents)

## Why
Ship pull requests that pass colleague review faster and with fewer rounds of
comments, by front-loading context with AI *before* any code is written and
locally reviewing AI output like a senior engineer — while staying personally in
control of every step (no autonomous agent workflows).

## Success looks like
- Before coding any non-trivial change, run a grilling session (`grill-with-docs`)
  that interrogates the plan until there is a shared, written understanding.
- Maintain a living `CONTEXT.md` glossary and sparse ADRs that sharpen the team's
  language and record real trade-offs.
- Review AI-generated diffs against a personal checklist and catch issues before
  a colleague ever sees them.
- Open PRs that reviewers approve quickly because the reasoning, scope, and
  trade-offs are already documented and CI is green.

## Constraints
- Professional environment, TypeScript / React Native / Expo / React.
- Reviews go through GitHub/GitLab-style PRs gated by required CI.
- Already a daily Claude Code user — wants *method and discipline*, not basics.
- Explicitly NO automated / autonomous agent workflows. Human drives each step.

## Out of scope (for now)
- Building or chaining autonomous agents, background runners, or CI bots.
- Prompt-engineering tricks divorced from a workflow.
- Non-TS ecosystems.
