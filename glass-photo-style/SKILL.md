---
name: glass-photo-style
description: "Transform an uploaded photo into a clean, collectible rendered-glass miniature model while preserving the subject."
---

# Glass Photo Style

Use this skill when the user provides a photo and asks for rendered glass, translucent glass, frosted glass, Liquid Glass-inspired, or precision glass miniature treatment.

## Workflow

1. Confirm that an image is attached. If no image is available, ask the user to upload one before generating anything.
2. Use the available image-generation or image-editing capability with the uploaded photo as the edit target or image reference.
3. Preserve the recognizable subject, key silhouette, important objects, relative layout, and distinctive text or markings when legible. Do not invent a different scene unless the user asks for a redesign.
4. Build a physical collectible glass maquette, not a normal photograph with a global glass filter.
5. Use parallel perspective adapted to the uploaded photo's original viewpoint and composition. If the source is already close to a front view, normalize it into a stable front-facing parallel perspective: keep the base level, correct tilted ground planes, and remove unnecessary convergence or skew. If the source is clearly oblique, preserve its meaningful front, side, interior, and front-to-back relationships while using parallel perspective. Do not force every source into a front or three-quarter view, and do not flatten the scene into an orthographic elevation.
6. Compose the image from the complete outer bounds of the model: center the object horizontally and vertically, keep the leftmost and rightmost structures fully inside the frame, and reserve at least 20% clear space on every side of the canvas. Target a complete-model height of roughly 60–70% of the canvas so the subject remains prominent without feeling cramped. If the source aspect ratio is too tight, expand the canvas or choose a larger, wider product-display composition instead of enlarging the model to the edges. Keep the complete model, base, and shadow within roughly 60–65% of the canvas width when the subject allows. Never let the base, roof, projection, shadow, or any major object touch or cross an image edge.
7. Generate at high resolution with crisp silhouettes, readable text, clear component boundaries, and fine architectural detail. Do not use blur, haze, depth of field, or bloom as a substitute for detail.
8. Apply user overrides for color, background, camera angle, detail, or realism while retaining the glass material language.

## Glass direction

- Use a clean, airy, precise, premium glass language inspired by modern Liquid Glass interfaces and product photography.
- Use high-end studio product composition: a centered hero object, balanced margins, an uncluttered warm-white or neutral background, soft controlled key light, gentle fill, clean contact shadow, and carefully shaped highlights.
- Before finalizing the frame, check the complete outer silhouette and re-scale, expand the canvas, or reframe the model if any side has less than 20% clear space, if the model height is substantially outside the 60–70% target, if the base is tilted, or if either side is clipped or visually crowded. Do not use a tight crop merely to make the object larger.
- Treat the model as assembled from separate glass slabs, panels, blocks, and small components with visible joints, narrow gaps, contact shadows, and clear silhouettes.
- Large ground or back panels may be complete thick glass slabs. Give them visible thickness, polished rounded edges, subtle transmission, soft refraction, and clean edge highlights.
- Mix smooth satin-frosted glass and clear glass. Use frosted glass on broad surfaces, architectural panels, ground slabs, and backplanes; use clearer glass on doors, windows, bevels, seams, and selected trims.
- Keep frames and structural connectors slightly more opaque so the architecture remains readable.
- Preserve the source color hierarchy with restrained translucent color. Use source-supported colors such as burgundy, rose, cobalt, teal, jade, amber, or cool violet without turning the result into saturated rainbow crystal.
- Use soft broad product lighting, quiet reflections, moderate ambient occlusion, gentle colored transmission, and restrained edge glow. Frosting should feel smooth and satin-like, never gray haze.
- Keep signs, logos, and important small parts separate from supporting surfaces. Render important lettering as crisp, raised, opaque components; do not let frosting, refraction, or bloom make text unreadable.
- Prefer component clarity over dramatic optical effects.

## Optional collectible base

The base is optional and must not be added by default for a simple style conversion. If the user asks for a collectible or product-display presentation:

- Place the complete Glass model on a clearly separate, thin, low-profile circular display disc slightly wider than the model.
- Use a quiet warm-white, silver, titanium, or stainless-steel finish with clean controlled highlights.
- Keep the base fully visible and leave balanced breathing room around the model.
- Do not use a transparent case or bulky pedestal.

## Prompt template

> Reinterpret the uploaded image as a clean rendered-glass miniature model. Keep the same subject, original viewpoint when it is meaningfully oblique, composition, recognizable silhouette, and important details. If the source is already close to front-facing, normalize it into a stable front-facing parallel perspective with a level base and corrected horizontal and vertical lines; do not preserve accidental tilt or convergence. If the source is clearly oblique, preserve its visible front, side, interior, and front-to-back relationships while using parallel perspective. Use a large, generous product-display canvas, expanding the canvas or choosing a wider landscape composition whenever needed. Build the scene as a carefully assembled collectible maquette using a deliberate mix of clear and satin-frosted glass, visible thickness, polished bevels, restrained refraction, soft high-end studio product lighting, clean component separation, a light uncluttered background, centered composition, at least 20% clear space on all four sides, and high-resolution detail. Keep the complete model, base, and shadow within roughly 60–65% of the canvas width and height when possible. First fit the entire outer silhouette inside the canvas so no left or right object is clipped and no major object touches an edge. Preserve source colors and readable signs without turning the scene into a glass filter, saturated crystal, or a single transparent mass.

When the user selects the optional base, append: “Place the complete glass model on a clearly separate, slightly oversized, very thin circular display disc with a quiet warm-white or precision-machined silver finish. Keep the base fully visible and leave comfortable breathing room around the model. No raised plaque, transparent case, packaging, or bulky pedestal.”

## Do not

- Do not use clay, matte polymer, wax, opaque painted plastic, or metallic CGI as the primary material.
- Do not give every part the same transparency; use clear, frosted, translucent, and more opaque layers deliberately.
- Do not make the result a normal photo with a global glass filter.
- Do not fuse signage, letters, roofs, walls, plants, furniture, or other major parts together.
- Do not use oily reflections, greasy sheen, rainbow glitter, saturated candy-crystal color, or noisy chromatic aberration.
- Do not hide detail with global blur, fog, haze, excessive bloom, or severe refraction.
- Do not let glass effects make important text or logos unreadable.
- Do not crop the highest point, base, or major architectural structure.
- Do not force every source into a front-facing or three-quarter view.
- Do not preserve accidental base tilt, skewed horizontal lines, or unnecessary perspective convergence in a near-front source.
- Do not allow less than 20% clear space on any side when the subject can be reframed to fit.
- Do not solve insufficient margins by cropping the source or enlarging the model; expand the canvas or reduce the model scale instead.
- Do not make the complete model so small that it loses visual focus, or so large that it breaks the 20% safety margins.
- Do not add noise, oversharpening, or fake detail as a substitute for high resolution.
- Do not add unrelated objects, invented architecture, packaging, a display case, a watermark, or random text.

## Interaction rules

- If the photo contains a person, preserve identity and pose unless the user explicitly requests removal or a character redesign.
- If text in the source is too small to preserve reliably, keep its placement, hierarchy, and visual shape rather than confidently inventing new wording.
