---
name: clay-photo-style
description: "Transform an uploaded photo into a soft, rounded clay-style 3D model image while preserving the subject."
---

# Clay Photo Style

Use this skill when the user provides a photo and asks for a clay, polymer-clay, miniature-diorama, or soft 3D toy-like reinterpretation.

## Workflow

1. Confirm that an image is attached. If no image is available, ask the user to upload one before generating anything.
2. Use the available image-generation or image-editing capability with the uploaded photo as the image reference.
3. Preserve the recognizable subject, key silhouette, important objects, relative layout, and distinctive text or markings when they are legible. Do not invent a different scene unless the user asks for a redesign.
4. Apply this visual direction:
   - handcrafted clay or polymer-clay miniature appearance
   - rounded, softly simplified forms with gently imperfect molded edges
   - matte or lightly satin material with subtle tactile surface variation
   - warm studio lighting, soft shadows, and clean off-white background when compatible with the source
   - compact toy-model proportions, clear layered construction, and restrained detail
   - friendly, polished, collectible-object presentation similar to a small clay diorama
5. Use parallel perspective: keep a stable, near-front viewing angle while preserving the facade's depth, front-to-back relationships, and three-dimensional structure. Correct excessive keystone distortion, slanted verticals, and obvious wide-angle distortion without flattening the scene into an orthographic front elevation.
6. Avoid photorealistic skin or surfaces, metallic CGI gloss, harsh outlines, excessive grain, random text changes, and unnecessary background clutter.
7. Return the generated image as the primary result. Briefly mention that the original composition and subject were retained where possible; do not add a long explanation unless the user asks.

## Optional collectible base

Offer this as an optional presentation mode when the user asks for a collectible model, designer toy, or product-style display. Do not add it by default when the user only asks for a clay conversion.

- If the user chooses no base, keep the transformed scene on its natural ground or use a clean neutral background.
- If the user chooses a base, place the complete clay model on a clearly separate, thin, low-profile circular display disc that is slightly wider than the model, leaving balanced breathing room around it.
- Use pristine bright silver titanium or stainless steel with Apple-like precision: smooth, uniform, immaculate, subtle satin micro-brushed finish, controlled highlights, and clean rounded edges. Avoid dirt, grime, stains, rust, scratches, dents, rough grain, dark smudges, or distressed patina.
- Integrate the title and collection number as small, flush laser engraving directly into the front curve of the metal surface. Do not use a raised plaque, attached badge, border, screws, packaging, transparent case, or accessory compartments.
- Keep the base visually quiet and let the clay model remain the hero. If the user has not specified whether to add it, ask them to choose between no base and the independent metal display base.

## Prompt template

Use the following direction as a base, adapting it to the uploaded subject:

> Reinterpret the uploaded image as a handcrafted clay miniature model. Keep the same subject, viewpoint, composition, recognizable silhouette, and important details. Build everything from softly rounded polymer clay with subtle handmade irregularities, matte tactile surfaces, gentle bevels, layered molded parts, warm neutral studio lighting, soft contact shadows, and a clean light background. Make it feel like a polished collectible clay diorama: charming, compact, carefully crafted, and three-dimensional. Preserve readable signs and markings as closely as possible. Do not turn it into glossy plastic, photorealistic CGI, a flat illustration, or a different scene.
> Use parallel perspective: present the subject as if viewed mostly from the front, with stable proportions and restrained perspective distortion, while preserving natural depth and layered spatial relationships. Do not use an orthographic projection or flatten the facade into a single plane.

When the user selects the optional collectible base, append: “Place the clay model on a clearly separate, slightly oversized, very thin circular display disc made of pristine bright silver titanium or stainless steel. Use an Apple-like immaculate precision-machined finish with subtle satin micro-brushing and clean controlled highlights. Add only flush laser engraving directly into the front curve of the metal surface for the title and collection number. No raised plaque, attached badge, screws, rectangular base, thick pedestal, packaging, or plastic case.”

## Interaction rules

- If the user requests a different clay color, background, camera angle, level of detail, or degree of realism, treat that as an override while retaining the clay miniature material language.
- If the photo contains a person, preserve identity and pose without exaggerating facial features or changing age, unless the user explicitly requests a character redesign.
- If text in the source is too small to preserve reliably, keep its placement and visual shape rather than confidently inventing new wording.
