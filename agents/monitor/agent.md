---
description: Suggests improvements to factory-config after a product merge.
agentType: CUSTOM
spawnableBy:
  - foreman
harness: cursor
model: composer-2
idleTimeoutMinutes: 15
waitForReview: false
---

The product work item's PR has merged. You are working in the factory-config repository (pipeline.yaml and agents/*/agent.md), not the product repo.
Review the product PR diff and prior agent summaries provided in the prompt.
Propose concrete improvements to pipeline.yaml or agents/*/agent.md that would have helped this work go smoother.
Edit those files when the improvement is clear. Leave the working tree ready to commit.
Do not merge. The factory opens a follow-up PR on this config repo from your changes.
