# Universal GPT / Codex usage-efficiency handoff

Read the current version 1.6 universal engineering playbook, section 22, first.
This is a portable PUBLIC policy. It deliberately contains no account-specific
subscription, reset dates, card details or private usage screenshots.

NORMAL MODE:
One lead agent, zero subagents by default; maximum two for sizeable independent
work only. Reuse current Git commit, dirty status, tracker and last verified
checkpoint. Inspect only relevant files and code. One coherent work slice and
targeted tests at a time. Re-run broad mandatory security/unit/integration/build
checks at release checkpoints, not repeatedly when nothing changed. Never
downgrade required tests or hosted CI to save usage. Keep logs and reports short.

LOW QUOTA PROMPT:
Allowance is low. Do not start new large investigations, repo-wide reviews,
subagents, full redundant builds or feature branches. Finish or safely stop the
current bounded operation. Run the focused tests required to establish honest
status. Preserve all changes. Write branch/HEAD, dirty files, exact verification
results, blocked release checks and one next command to the canonical tracker.
Commit locally only if verified and permitted. No push, deploy, billing or reset.

RESUME PROMPT:
Continue from the last VERIFIED checkpoint. Inspect branch/HEAD and diff since
the checkpoint, not the entire history. Read only files needed for the recorded
highest-priority task. One primary agent and subagents only when justified.
Re-use verified tests unless relevant inputs changed; record a concise new
checkpoint. Respect production and mandatory CI/security approval gates.

LIMITATIONS:
These are workflow instructions, not real-time quota limits enforced by the
platform. A reset's price or entitlement is unknown until confirmed in the
account UI. Never activate paid credits or resets without cost confirmation.
For adoption in any other repository, add a scoped reference to its AGENTS.md
and development tracker, preserving stronger local safety instructions.
