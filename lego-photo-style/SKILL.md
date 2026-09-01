---
name: lego-photo-style
description: "Transform an uploaded photo into a coherent, high-resolution LEGO-built collectible model while preserving the subject."
---

# LEGO Photo Style

Use this skill when the user provides a photo and asks for a LEGO, brick-built, block-built, or LEGO-like miniature model.

## Core transformation

Rebuild the uploaded photo as a complete, coherent tabletop LEGO model. This is a full scene reconstruction, not a photograph with a LEGO texture or a few brick details layered on top. Preserve the recognizable subject, key silhouette, important objects, relative layout, and distinctive markings where they are legible.

Use the visual logic of a polished clay miniature, but replace the clay material with unmistakable LEGO construction: simplified collectible proportions, clear layered construction, friendly product-model presentation, and parallel perspective adapted to the uploaded photo. The finished image should immediately look like a real model assembled piece by piece, not like a smooth 3D render. Preserve natural depth and front-to-back relationships; do not flatten the subject into an orthographic front elevation.

## Workflow

1. Confirm that an image is attached. If no image is available, ask the user to upload one before generating anything.
2. Use the uploaded photo as the edit target. If a model image is also provided, use it as a reference for presentation only unless the user says otherwise.
3. Identify the subject's major forms, layers, repeated details, important objects, colors, and readable markings before reconstructing it.
4. Rebuild every visible major component as a LEGO element: architecture, terrain, furniture, plants, vehicles, figures, signs, lamps, and other scene-defining objects.
5. Keep one consistent LEGO scale and construction grid. Use regular brick courses, believable staggered joints, aligned plates or tiles, and repeatable combinations for repeated details.
6. Compose the complete model as a centered collectible object. When a model-style presentation is requested or shown as a reference, place it on a thin, low-profile, slightly oversized oval or circular display base with a clean warm off-white background.
7. Keep a complete four-sided safety margin. Leave clear space above, below, left, and right of the model; no roof, sign, umbrella, lamp, furniture, plant, railing, figure, base, or other object may touch or be clipped by any image edge. Make the model large enough to dominate the frame without creating excessive empty space.
8. Generate a high-resolution result with crisp silhouettes, readable large text, clear brick joints, visible construction boundaries, and sharp small details. Avoid blur, haze, heavy depth of field, and bloom as substitutes for detail.
9. Inspect the result for subject fidelity, complete framing, LEGO construction logic, and accidental photorealistic or clay-like surfaces before returning it.

## LEGO construction direction

- Build walls and terraces from consistent horizontal brick layers with intentional staggered joints.
- Build roofs, awnings, pavements, platforms, and bases from aligned plates, tiles, and stepped layers that follow the form.
- Make LEGO studs visibly present and easy to recognize on appropriate horizontal, stepped, and exposed structural surfaces. Arrange them in orderly rows, repeated groups, and consistent spacing; do not hide all studs behind smooth surfaces.
- Use tiles, panels, and brick faces only where a finished surface would realistically be tiled or covered. Even large surfaces should be visibly broken into modular LEGO pieces with seams, layer changes, or orderly stud patterns.
- Make curved or ornate forms from stepped, repeated, modular pieces rather than smooth continuous shells.
- Never represent a large awning, roof, canopy, umbrella, or similar surface as one continuous slab or molded shell. Decompose it into multiple independent LEGO plates, tiles, slopes, wedges, or brick layers with visible piece boundaries, thickness, and attachment logic.
- Build large sloped surfaces as stepped layers: each layer should have its own front edge and seams, with consistent depth and a believable connection to the supporting structure. For umbrella or canopy surfaces, use radial or repeated wedge-like modules from the center outward rather than a single smooth cone or cap.
- Show construction at exposed edges and connections: layered plate edges, supporting bricks, hinge-like joints, studs on appropriate upper layers, and overlaps between modules should make the assembly understandable at a glance.
- Build railings, columns, windows, doors, lamps, furniture, plants, cups, and small figures from recognizable combinations of standard LEGO elements at a consistent scale.
- Repeat architectural motifs with consistent spacing and orientation. Construction should look physically plausible and deliberately assembled by a skilled builder.
- Preserve large text and logos as raised or tile-built markings where feasible. When source text is too small, preserve its placement and visual structure rather than inventing confident wording.
- Use crisp ABS-like plastic with subtle molded highlights, visible seams, modular geometry, and a premium collectible finish. Keep the scene simplified, dimensional, and model-like.
- When a supplied reference is especially LEGO-like, calibrate against its whole construction language: abundant but organized studs, visible brick courses, clear plate stacking, repeated component sizes, stepped silhouettes, and deliberate modular connections. Match this system rather than copying isolated details.

## Composition and presentation

- Use parallel perspective adapted to the uploaded photo's original viewpoint and composition. Do not force a front view, three-quarter view, fixed interior reveal, or cube-like cutaway. Preserve whatever front, side, interior, and front-to-back relationships are actually visible in the source while correcting keystone distortion, slanted verticals, and obvious wide-angle distortion.
- Keep the full model and display base visible with a clear safety margin on all four sides. No part of any object may touch or be cropped by the image boundary. Make the model occupy the main visual field without becoming edge-to-edge or too small.
- Use soft warm studio lighting, gentle contact shadows, and a clean neutral background compatible with the source and any supplied model reference.
- Make the model occupy the main visual field and remain easy to inspect at high resolution.

## Avoid

- Do not leave the source looking like a real photograph with a LEGO texture applied.
- Do not use randomly scattered studs, arbitrary seams, inconsistent brick scale, impossible floating pieces, or repeated details with no shared construction logic.
- Do not make the model so smooth or tile-covered that it stops reading as LEGO. Keep appropriate exposed studs and visible layer transitions across the model.
- Do not scatter studs without regard to the piece layout. Studs must follow the grid, appear in regular rows or intentional groups, and connect to plausible bricks or plates.
- Do not cover every surface with studs when tiles, panels, or brick faces would be the realistic construction choice; use a deliberate balance of exposed studs, tiled surfaces, and brick faces.
- Do not render awnings, roofs, canopies, or umbrellas as one-piece smooth slabs, molded shells, or texture-only surfaces. Their layered plate construction and independent edges must remain visible.
- Do not show LEGO details only on the top of an object while leaving its main body as a generic smooth form; the whole object must read as assembled from parts.
- Do not replace the model with smooth clay, a smooth molded-plastic sculpture, a generic CGI render, or a photorealistic building.
- Do not change the subject, redesign the scene, add unrelated objects, or invent prominent text.
- Do not make the model too small or leave excessive empty space. Never crop the roof, base, side objects, or any other element, and never let any object touch any image edge, including the left and right edges.
- Avoid low-resolution, blurry, smeared, noisy, or over-sharpened output; brick joints, studs, layered structures, railings, and small figures should remain legible.
- Do not add a display base by default when the user asks only for a material conversion and has not requested a collectible presentation.

## Prompt template

> Rebuild the uploaded photo as a complete, coherent LEGO tabletop model. Preserve the same subject, recognizable silhouette, important objects, relative layout, colors, original viewpoint, and distinctive markings. Do not apply a LEGO texture to a photograph: reconstruct every major form as LEGO bricks, plates, tiles, hinges, and small elements. Use a consistent LEGO scale and grid, regular brick courses, believable staggered joints, aligned plates, repeatable architectural details, and physically plausible connections. Present it as a polished collectible miniature with parallel perspective adapted to the source photo: preserve the source's actually visible front, side, interior, and depth relationships without forcing a front view, three-quarter view, or cube-like cutaway. Correct keystone and wide-angle distortion while retaining three-dimensional depth. Keep the complete model fully visible with clear safety margins on all four sides; no object may touch or be clipped by any image edge. Use soft warm studio lighting, crisp ABS-like plastic, clear seams and orderly studs, and high-resolution product-photo sharpness. Avoid photorealistic surfaces, clay, smooth CGI sculpture, random studs, arbitrary seams, inconsistent scale, dramatic perspective, flat orthographic elevation, unrelated objects, excessive empty space, blur, edge contact, and watermark.

## Interaction rules

- Treat requests for a different background, camera angle, level of detail, or degree of realism as overrides only when they do not conflict with the user's requested LEGO construction.
- If the photo contains people, preserve their pose and recognizable clothing colors as simplified LEGO figures unless the user requests their removal or redesign.
- If a supplied reference shows a model, use it to guide presentation, proportions, framing, base treatment, and lighting; do not copy unrelated subject matter from it.
- If text is too small to preserve reliably, keep its placement and visual shape rather than confidently inventing new wording.
