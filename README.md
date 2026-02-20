# Scrap Team

A comedic demo of [Claude Code Agent Teams](https://code.claude.com/docs/en/agent-teams) — a dysfunctional scrum team inspired by The Office runs a full sprint to build features for a kanban task tracker.

## The Cast

| Character | Role | Signature Move |
|---|---|---|
| **Michael Scarn** | Product Owner | Changes requirements mid-sprint after "shower thoughts" |
| **Sergei Overthinkov** | Architect | Proposes 12 microservices for a single HTML file |
| **Chad "10x" Broseph** | Tech Lead | Rewrites everyone's code with dramatic sighs |
| **Tiffany Testcase** | QA/Tester | Files P0 blocker: "button is 1px off" |
| **Dave "Daily" Standupson** | Scrum Master | Calls a meeting about why there are too many meetings |
| **Junior McStackoverflow** | Junior Dev | "It works on my machine!" |

## How to Run

### Prerequisites
- [Claude Code CLI](https://docs.anthropic.com/en/docs/claude-code) installed
- Agent Teams enabled (already configured in `.claude/settings.json`)

### Launch the Scrap Team
```bash
cd scrap-team
claude
```

Then type:
```
/scrap-team
```

Watch the team run a full scrum sprint:
1. **Feature Brief** — Michael writes a buzzword-filled brief
2. **Refinement** — Dave facilitates while Sergei overengineers and Chad argues
3. **Sprint Planning** — Dave creates and assigns tasks
4. **Development** — Junior codes, Chad reviews, Sergei "guides", Michael changes requirements
5. **Testing** — Tiffany finds impossible edge cases
6. **Sprint Review & Retro** — Dave schedules a retro about the retro

## The Project

`index.html` is a simple kanban task tracker (ScrApp Tracker) that the team adds features to during the sprint. Open it in a browser to see the result.

## Tips
- Use `Shift+Down` to cycle between teammates and watch their conversations
- The team actually modifies `index.html` — check the file after the sprint!
- For split-pane mode (see all teammates at once), run inside tmux
