# NovaPath agent harness

## NovaPath HQ

NovaPath HQ in Notion is the shared knowledge base: https://app.notion.com/p/3d15815a5a6681abbea8f68065e12156. Before writing to it, read "How we maintain NovaPath HQ": https://app.notion.com/p/3d55815a5a66818d903fd0b376660916.

Engineering detail (commits, deployments, test runs, verification, handoff notes) lives in this repo. The Notion project page carries current state, decisions and blockers, plus one change-log line per release linking back here. Update Notion only at a real milestone: a decision, a release, or a blocker.

## Agent skills

Matt Pocock's skills are vendored in `.claude/skills/` (MIT, see `LICENSE-mattpocock-skills` there).

### Issue tracker

GitHub Issues on `doommir/novapath-agent-harness`; cloud sessions use `gh api` REST calls. See `docs/agents/issue-tracker.md`.

### Triage labels

The five default labels: `needs-triage`, `needs-info`, `ready-for-agent`, `ready-for-human`, `wontfix`. See `docs/agents/triage-labels.md`.

### Domain docs

Single-context: `GLOSSARY.md` and `docs/adr/` at the repo root. See `docs/agents/domain.md`.
