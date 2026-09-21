# My-FirstProject

## Brainstorming with BMad Method

This repo has the [BMad Method](https://github.com/bmad-code-org/BMAD-METHOD) brainstorming toolkit installed as Claude Code skills, so you can run structured, divergence-focused brainstorming sessions on product ideas.

### Installed skills

- `bmad` — orientation/help agent; tells you what's installed and what to do next
- `bmad-brainstorming` — runs a brainstorming session using a wide range of creative techniques
- `bmad-agent-analyst` — "Mary", the business analyst persona, useful for market/requirements-flavored brainstorming

### Starting a session

In Claude Code, just ask to brainstorm — e.g. "help me brainstorm ideas for my product" — or invoke the skill directly:

```
/bmad-brainstorming
```

You'll be asked to pick a stance for the session:

- **Facilitator** — the coach asks questions, you generate all the ideas
- **Creative Partner** — the coach and you trade ideas together
- **Ideate for me** — the coach runs the session and shows you the result

Sessions log progress to `_bmad-output/` so they can be paused and resumed, and wrap up with a synthesized summary of the ideas generated.

### Updating / repairing the install

- `npx skills update` — pulls newer versions of the installed skills from BMAD-METHOD
- Ask Claude to "doctor the bmad installation" to repair a broken local setup
