# Freebuff Ultimate Skills

A practical collection of agent skills for creative workflows, 3D printing, coding, research, and troubleshooting.

## Install

Install all skills:

```bash
npx skills add GBS-2805/freebuff-ultimate-skills --skill "*" --yes
```

Install one skill:

```bash
npx skills add GBS-2805/freebuff-ultimate-skills --skill blender-product-rendering
```

## Included skills

- `blender-product-rendering`
  Use when you need a polished product shot in Blender (especially keyboards and keycaps), or when a scene has to move between machines without losing UVs, materials or HDRIs.

- `creality-k1-se`
  Use when a K1 SE print comes out wrong: rough first layers, under-extrusion, stringing, or supports welded to the model.

- `orcaslicer-tuning`
  Use when OrcaSlicer output is unreliable and you need to tune a profile in a sensible order instead of changing several settings at once.

- `ui-design`
  Use when planning a screen or flow, critiquing an existing interface, or checking responsiveness, empty/error states and accessibility.

- `coding-workflow`
  Use before changing code in an unfamiliar repository, or when a fix needs scoped edits and honest test reporting.

- `research-and-writing`
  Use when a claim needs credible sources and citations, or when the writing must separate sourced fact from interpretation.

- `github-workflow`
  Use when committing, branching, opening a pull request, or working out what actually reached GitHub.

- `technical-troubleshooting`
  Use when something breaks and you need to isolate the cause without risking data, hardware or working settings.

Each skill is a folder containing `SKILL.md`. Skills provide workflows, not proof an action was completed.

## Layout

```text
skills/<skill-name>/SKILL.md
AGENTS.md
LICENSE
```

Check your agent's documentation for supported skill discovery and installation formats.
