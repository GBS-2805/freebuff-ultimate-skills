---
name: blender-product-rendering
description: Plan, prepare, troubleshoot, and render polished product images in Blender while preserving scene structure, UVs, materials, node trees, lighting, and linked assets.
---

# Blender Product Rendering

Use this skill for product visualization, especially detailed keyboard and keycap renders.

## Before changing anything
1. Identify the Blender version, render engine, output resolution, color management, and current scene.
2. Inspect object hierarchy, collections, modifiers, UV maps, material assignments, node trees, image textures, HDRIs, and linked assets.
3. Save a separate working copy before major edits. Never overwrite the only source file.
4. Check whether textures and external assets are packed or use stable relative paths.

## Preserve project data
- Keep existing UV maps and material node networks intact unless the user asks to change them.
- Preserve keycap material assignments, procedural nodes, HDRIs, camera setup, and collection organization.
- When transferring a scene, use File > External Data > Pack Resources when appropriate, or collect dependencies into a project folder.
- For large `.blend` files, inspect dependencies and remove only confirmed-unused data. Do not blindly purge data.

## Product-render workflow
1. Confirm the product, camera angle, intended background, and output use.
2. Establish clean composition and readable silhouette before increasing samples.
3. Use controlled area lighting and reflections to reveal shape and surface finish.
4. Check material roughness, normals, bevel highlights, and contact shadows.
5. Render a low-cost preview first; inspect noise, clipping, color, and texture resolution.
6. Increase samples and output resolution only after the preview is approved.
7. Save final renders separately from the source project.

## Troubleshooting
- Missing textures: verify image paths, pack resources, and reopen the file to test.
- Materials changed after transfer: inspect node links, image inputs, color space, and missing assets.
- Noisy renders: check lighting, samples, denoising, caustics, and overly dark areas.
- Soft details: verify camera focus, render resolution, texture resolution, and output scaling.
- Slow renders: use a representative crop or reduced-resolution preview before a full render.

Explain trade-offs and verify the final file opens with its dependencies available.
