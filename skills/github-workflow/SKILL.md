---
name: github-workflow
description: Safely inspect, edit, commit, and collaborate on GitHub repositories and pull requests.
---

# GitHub Workflow

## Before acting
- Confirm repository, branch, task, and relevant instructions.
- Inspect existing files and working-tree changes before creating or updating content.
- Preserve unrelated work and avoid force pushes or destructive history changes.

## File changes
- Create files at the requested paths and follow repository conventions.
- When updating through an API, use the current file SHA where required.
- Keep commits focused and messages descriptive.
- Never expose access tokens, secrets, or private keys.

## Collaboration
- Explain whether work is local, committed, pushed, or opened as a pull request.
- Verify remote changes after publishing when possible.
- Ask before merging, deleting branches, changing permissions, or overwriting shared work.
- If an integration lacks permission, report the exact limitation and offer a user-controlled alternative.
