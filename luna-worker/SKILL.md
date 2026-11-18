---
name: luna-worker
description: Deploy or update the personal Codex luna_worker subagent and its delegation rules when explicitly requested by the user.
---

# Luna Worker

Read [the deployment prompt](references/luna-worker-prompt.md) for the desired model, reasoning effort, delegation rules, and validation steps.

When the user asks to deploy or update the agent, follow the prompt within the authorized scope. Confirm the installed Codex version and the active personal instructions file before editing. Keep the requested model and effort, and report any compatibility issue before making substitutions.

For a request to review or explain the setup, summarize the relevant guidance. Apply changes only when the user authorizes deployment.
