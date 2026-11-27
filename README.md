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

- `blender-product-rendering` — product and keyboard renders, UVs, materials, HDRIs, project handoff.
- `creality-k1-se` — K1 SE setup, calibration, print diagnosis.
- `orcaslicer-tuning` — supports, stringing, extrusion, first layers, material profiles.
- `ui-design` — UX flows, interface critique, accessibility, responsive specs.
- `coding-workflow` — safe code changes, testing, debugging.
- `research-and-writing` — source evaluation, synthesis, citations.
- `github-workflow` — repositories, branches, commits, issues, pull requests.
- `technical-troubleshooting` — evidence-driven diagnosis across software and hardware.

Each skill is a folder containing `SKILL.md`. Skills provide workflows, not proof an action was completed.

## Layout

```text
skills/<skill-name>/SKILL.md
AGENTS.md
LICENSE
```

Check your agent's documentation for supported skill discovery and installation formats.
