# Freebuff Ultimate Skills

This repository no longer ships its own skills.

The eight it used to contain were unsourced prose: no scripts, no reference files, no tests, and no record of anyone verifying the printer or slicer settings in them. They have been removed rather than dressed up. What follows points at packs that do have that evidence.

## What to install

| You need | Pack | Why that one |
| --- | --- | --- |
| Reviewing UI, accessibility | `vercel-labs/agent-skills` → `web-design-guidelines` | Vercel's own; rules pinned by commit SHA and checksum; ~900k installs |
| Designing a new interface | `anthropics/skills` → `frontend-design` | Names the tells that make generated pages obvious, then avoids them |
| Posters, artwork, print design | `anthropics/skills` → `canvas-design` | Two-phase design process; ships 38 licensed fonts |
| Blender work | `RobLe3/cc-blender-skill` | 30 skills, each with references, scripts and trigger tests; keeps its failed renders as evidence |
| OrcaSlicer | `OrcaSlicer/orcaslicer-mcp-skills` | From the OrcaSlicer organisation; 20 KB skill plus a 120 KB action reference |
| Klipper printers | `santiagomoneta/3d-printing-skills` | Real shell scripts for status, G-code and config upload. One developer — a starting point, not authority |
| PDFs, Word, Excel, PowerPoint | `anthropics/skills` → `pdf`, `docx`, `xlsx`, `pptx` | Official, and they bundle working scripts |
| Debugging, planning code | `obra/superpowers`, `mattpocock/skills` | Widely used engineering workflows |
| Security review | `trailofbits/skills` | Maintained by a security firm |

## Install

```bash
npx skills add vercel-labs/agent-skills --skill web-design-guidelines -a claude-code -g -y
npx skills add anthropics/skills --skill frontend-design -a claude-code -g -y
```

`-g` installs for your whole user account (`~/.claude/skills`) so the skill works in every project. Drop it to install into only the current folder. `-y` skips the prompts.

Swap the repo and `--skill` name for anything in the table above. The installer also prints independent security checks (Gen Agent Trust Hub, Socket, Snyk) before it installs.

## The 3D printing gap

There is no credible Creality K1 SE skill, from anyone. The nearest options are the official OrcaSlicer pack and a one-developer Klipper pack, both small.

Generic advice is not worth pretending otherwise. What would be worth trusting is your own log: filament, temperatures, the one setting you changed, and what actually happened. That record is the only K1 SE skill that will ever be better than guesswork.

## Old versions

Tags `v1.0.0` and `v1.0.1` still contain the eight original skills and are still installable from the tag:

```bash
npx skills add GBS-2805/freebuff-ultimate-skills@v1.0.1 --skill "*" -a claude-code -g -y
```

They are unchanged and were never tested or sourced. Installing from `main` no longer yields any skills, by design.
