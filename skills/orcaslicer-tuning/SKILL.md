---
name: orcaslicer-tuning
description: Tune OrcaSlicer profiles systematically for reliable FDM printing, including supports, extrusion, stringing, cooling, and calibration.
---

# OrcaSlicer Tuning

## Start with the actual profile
Identify printer, nozzle, filament preset, process preset, layer height, temperatures, speeds, cooling, retraction, and support settings. Duplicate the profile before editing.

## Calibration order
1. Confirm filament and printer profiles are correct.
2. Check first layer and basic extrusion.
3. Run temperature and flow calibration where appropriate.
4. Tune pressure advance and retraction only when symptoms justify it.
5. Tune cooling and bridging.
6. Tune supports and interface settings for the specific geometry.

## Support tuning
- Distinguish support-to-model fusion from poor support stability or difficult removal.
- Review top Z distance relative to layer height, interface layers, interface spacing, XY separation, support style, and cooling.
- Organic/tree supports can still fuse if contact area, interface, temperature, or material behavior is unfavorable.
- Use a small test print before committing to a large model.

## Stringing and extrusion
- Check filament moisture and nozzle temperature before aggressive retraction changes.
- Inspect travel settings, wipe, retraction length/speed, and nozzle cleanliness.
- Use flow calibration rather than guessing based only on surface appearance.
- Do not change temperature, flow, and retraction simultaneously.

## Good practice
Keep notes of baseline values and each test. Change one variable at a time, compare equivalent prints, and save successful presets with clear names. Avoid presenting any single setting as universally correct.
