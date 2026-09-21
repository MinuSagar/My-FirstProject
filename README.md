# My-FirstProject

## BMad Method

This repo has the full [BMad Method](https://github.com/bmad-code-org/BMAD-METHOD) toolkit installed as Claude Code skills (all 30 skills from the `toolbox` and `method` modules), covering the whole product lifecycle from ideation through build, review, and retrospective.

### Installed skills

**Orientation**
- `bmad` — help agent; tells you what's installed and what to do next; also runs setup/update/doctor

**Agent personas** (talk to them by name)
- `bmad-agent-analyst` — Mary, Business Analyst — market research, competitive analysis, requirements
- `bmad-agent-pm` — John, Product Manager — PRD creation, requirements discovery
- `bmad-agent-architect` — Winston, System Architect — technical design
- `bmad-agent-ux-designer` — Sally, UX Designer — UI/UX specification
- `bmad-agent-dev` — Amelia, Senior Software Engineer — implements stories/code

**Ideation & discovery**
- `bmad-brainstorming` — brainstorming session using a wide range of creative techniques
- `bmad-forge-idea` — pressure-test a half-formed idea until it's actionable
- `bmad-prfaq` — Amazon-style "Working Backwards" press-release/FAQ exercise
- `bmad-deep-recon` — market/domain/technical/competitive research
- `bmad-advanced-elicitation` — deeper critique techniques (socratic, pre-mortem, red team, ...)
- `bmad-party-mode` — multi-agent roundtable / focus-group discussions

**Planning & specification**
- `bmad-product-brief` — product brief creation/validation
- `bmad-prd` — PRD creation/validation
- `bmad-spec` — condense ideas/briefs/PRDs into a short spec
- `bmad-architecture` — architecture decisions/document
- `bmad-ux` — DESIGN.md / EXPERIENCE.md UX vision docs
- `bmad-create-epics-and-stories` — break requirements into epics and stories
- `bmad-preview-ticketing` — slice initiatives into epics/stories and manage the board
- `bmad-sprint-planning` — implementation-readiness checks, sprint status

**Build & QA**
- `bmad-build` — implement a feature/story/fix end-to-end, reviewed and verified
- `bmad-build-auto` — one iteration of an unattended dev loop
- `bmad-qa-generate-e2e-tests` — generate API/E2E tests for implemented features
- `bmad-code-review` — parallel independent code reviewers + triage
- `bmad-review` — adversarial/edge-case/verification review lenses for diffs/PRs

**Process**
- `bmad-project-context` — set up/audit a repo's AGENTS.md agent instructions
- `bmad-correct-course` — assess impact of a significant mid-sprint change
- `bmad-retrospective` — evidence-based epic retrospective
- `bmad-walkthrough` — guided human review of a commit/PR/file
- `bmad-customize` — author overrides for any installed BMad skill

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
