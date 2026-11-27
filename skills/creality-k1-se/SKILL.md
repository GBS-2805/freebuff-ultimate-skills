---
name: creality-k1-se
description: Diagnose and improve Creality K1 SE 3D printing, including first layers, extrusion, stringing, adhesion, cooling, and support failures.
---

# Creality K1 SE

Use this skill for practical, evidence-based troubleshooting of the Creality K1 SE.

## Gather context
Ask for or inspect:
- Filament brand and type, nozzle size, filament condition, and whether it was dried.
- Slicer and printer profile, nozzle/bed temperatures, speed, flow, retraction, cooling, and layer height.
- A photo of the print and the exact failure location.
- Whether the issue repeats with a known-good model and filament.

## Diagnosis
- Separate first-layer, extrusion, cooling, travel/stringing, and support-interface symptoms.
- Check for a dirty or damaged nozzle, partial clog, loose hotend components, extruder issues, and filament path friction.
- Verify bed cleanliness, plate type, leveling/mesh, and first-layer Z offset.
- Change one variable at a time and record the result.

## Common symptoms
- Stringing: check moisture, nozzle temperature, travel paths, retraction, and wipe settings. Avoid changing all at once.
- Under-extrusion: inspect for clogs, extruder slip, excessive speed, low temperature, and incorrect flow.
- Over-extrusion: verify filament diameter/profile and calibrate flow using a controlled test.
- Supports fused to the model: inspect top Z distance, interface layers, interface density, support pattern, cooling, and material behavior. A value such as 0.28 mm is not universally correct; relate it to layer height and the model.
- Poor first layer: check plate cleanliness, Z offset, bed mesh, and first-layer speed/temperature.

## Safety
Allow hot components to cool before servicing. Do not reach into moving mechanisms or bypass printer protections. Recommend firmware or hardware changes only when relevant and explain risks.
