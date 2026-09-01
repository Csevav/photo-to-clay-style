---
name: c4d-render-style
description: "Transform an uploaded photo into a polished Cinema 4D-style 3D render while preserving the subject, composition, and recognizable details."
---

# C4D Render Style

Use this skill when the user provides a photo and asks for a refined C4D render, premium 3D illustration, polished 3D icon, product-style render, or high-end digital miniature.

## Workflow

1. Confirm that an image is attached. If no image is available, ask the user to upload one before generating anything.
2. Use the available image-generation or image-editing capability with the uploaded photo as the image reference.
3. Preserve the recognizable subject, key silhouette, important objects, relative layout, and distinctive text or markings when they are legible. Do not invent a different scene unless the user asks for a redesign.
4. Rebuild the scene as a coherent 3D composition rather than applying a superficial render filter to a photograph.
5. Apply this visual direction:
   - refined Cinema 4D / Octane- or Redshift-inspired product rendering
   - clean, softly simplified geometry with deliberate modeling and smooth bevels
   - precise rounded edges, controlled proportions, and believable depth
   - colorful matte, satin, lacquered, translucent, or lightly glossy materials chosen to fit the subject
   - subtle material variation, clean reflections, soft specular highlights, and polished surfaces
   - warm or neutral studio lighting, gentle contact shadows, restrained ambient occlusion, and a clean light background when compatible with the source
   - premium 3D illustration or collectible-object presentation: crisp, cheerful, dimensional, and carefully art-directed
6. Use parallel perspective: keep a stable, near-front viewing angle while preserving the facade's depth, front-to-back relationships, and three-dimensional structure. Correct excessive keystone distortion, slanted verticals, and obvious wide-angle distortion without flattening the scene into an orthographic front elevation.
7. Preserve the source's visual hierarchy. Do not add dramatic cinematic effects, excessive depth of field, lens flares, bloom, heavy noise, or background clutter that compete with the subject.
8. Return the generated image as the primary result. Briefly mention that the original composition and subject were retained where possible; do not add a long explanation unless the user asks.

## Composition and fidelity

- Keep the original viewpoint, composition, relative scale, and important spatial relationships unless the user explicitly requests a new composition.
- Keep the complete subject visible with balanced breathing room. Do not crop distinctive objects, signs, characters, bases, or other scene-defining elements.
- Preserve large, readable text and logos as closely as possible. When source text is too small to reproduce reliably, preserve its placement and visual shape rather than confidently inventing new wording.
- If the photo contains a person, preserve identity, pose, clothing colors, and age without turning the person into a generic character unless the user requests a redesign.
- If a supplied reference shows a 3D render, use it to guide the material finish, lighting, color treatment, framing, and level of polish; do not copy unrelated subject matter from it.

## Optional collectible base

Offer this as an optional presentation mode when the user asks for a collectible model, designer toy, or product-style display. Do not add it by default when the user only asks for a C4D conversion.

- If the user chooses no base, keep the transformed scene on its natural ground or use a clean neutral background.
- If the user chooses a base, place the complete 3D model on a clearly separate, thin, low-profile circular display disc that is slightly wider than the model, leaving balanced breathing room around it.
- Use a pristine bright silver titanium or stainless-steel finish with precise machining, smooth rounded edges, subtle satin micro-brushing, and controlled highlights. Avoid dirt, grime, stains, rust, scratches, dents, rough grain, or distressed patina.
- Integrate the title and collection number as small, flush laser engraving directly into the front curve of the metal surface. Do not use a raised plaque, attached badge, border, screws, packaging, transparent case, or accessory compartments.
- Keep the base visually quiet and let the rendered model remain the hero. If the user has not specified whether to add it, ask them to choose between no base and the independent metal display base.

## Prompt template

Use the following direction as a base, adapting it to the uploaded subject:

> Rebuild the uploaded image as a polished Cinema 4D-style 3D render. Keep the same subject, viewpoint, composition, recognizable silhouette, important objects, relative layout, and distinctive markings. Model the scene as a coherent dimensional 3D composition with clean simplified forms, precise rounded bevels, controlled proportions, premium colorful materials, subtle surface variation, soft studio lighting, realistic contact shadows, restrained ambient occlusion, clean reflections, and crisp product-render detail. Make it feel like a carefully art-directed premium 3D illustration or collectible object: refined, cheerful, dimensional, and high quality. Preserve readable signs and markings as closely as possible. Do not turn it into a photograph with a filter, a flat illustration, rough low-poly geometry, generic plastic clip art, or a different scene.
> Use parallel perspective: present the subject as if viewed mostly from the front, with stable proportions and restrained perspective distortion, while preserving natural depth and layered spatial relationships. Do not use an orthographic projection or flatten the facade into a single plane.

When the user selects the optional collectible base, append: “Place the rendered model on a clearly separate, slightly oversized, very thin circular display disc made of pristine bright silver titanium or stainless steel. Use an immaculate precision-machined finish with subtle satin micro-brushing, smooth rounded edges, and clean controlled highlights. Add only flush laser engraving directly into the front curve of the metal surface for the title and collection number. No raised plaque, attached badge, screws, rectangular base, thick pedestal, packaging, or plastic case.”

## Avoid

- Do not leave the source looking like a real photograph with a generic CGI filter.
- Do not use flat vector art, rough low-poly geometry, toy clay, LEGO construction, wireframe, or unintentional photorealistic skin unless explicitly requested.
- Do not make every surface equally glossy. Match matte, satin, lacquered, metallic, glassy, or translucent finishes to the object while maintaining a unified render language.
- Do not add unrelated objects, redesign the scene, invent prominent text, or change the subject's identity.
- Avoid excessive bloom, lens flare, chromatic aberration, harsh outlines, dramatic lens distortion, heavy grain, muddy shadows, clipped highlights, and overdone depth of field.
- Do not add a display base by default when the user asks only for a material conversion and has not requested a collectible presentation.

## Interaction rules

- Treat requests for a different material finish, color palette, background, camera angle, level of detail, or degree of realism as overrides only when they do not conflict with the user's requested C4D-render direction.
- If the user asks for a more stylized or more realistic result, adjust geometry, material response, lighting, and detail while retaining the coherent 3D-render language.
- If text is too small to preserve reliably, keep its placement and visual structure rather than confidently inventing wording.
