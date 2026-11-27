---
name: coding-workflow
description: Make careful, maintainable code changes with repository inspection, scoped implementation, and honest verification.
---

# Coding Workflow

## Inspect first
- Read project instructions, README, package/build configuration, and relevant source files.
- Identify language, framework, conventions, tests, and current working-tree changes.
- Do not overwrite unrelated user changes.

## Implement
- Restate the intended behavior and keep changes scoped.
- Prefer simple, maintainable solutions that fit existing patterns.
- Consider error handling, input validation, accessibility, and security.
- Avoid adding dependencies unless they provide clear value.

## Verify
- Run the most relevant tests, lint, type checks, or build commands available.
- Inspect the diff for accidental changes and secrets.
- Report exactly what was run and whether it passed.
- If tests could not be run, say so and provide the reason.

## Handoff
Summarize changed files, behavior, verification, and any follow-up work. Never claim code was tested or deployed when it was not.
