# XXD Panel 039 | One-Image-One-Essence Chinese Embroidery Production Prompt

## Runtime complete-canvas contract — highest priority

- `TOP_BOTTOM` and `LEFT_RIGHT` default to one complete finished generation using the current source as a high-fidelity edit/reference input. Do not pre-split the job into photographic and design halves.
- Top-bottom keeps the faithful source in approximately the upper 50% and performs this style transformation below; left-right uses the faithful source in approximately the left 50% and the transformation on the right. Unify both regions through colour, light, rhythm, typography, and meaning.
- `DESIGN_ONLY` and `WALLPAPER_PACK` use the complete canvas while the source remains an invisible identity/content reference. Recompose every wallpaper separately for its device.
- `FINAL CANVAS` means the ratio/pixels of the whole finished artwork and must be explicitly resolved before generation; never apply source dimensions silently. `DESIGN FRAME` is used only if a failed complete-canvas retry triggers deterministic composition fallback.
- Retry a failed complete canvas once against the failed constraint only. Scripted composition is allowed only after that retry still fails, when pixel-identical source preservation is explicitly required, when the active route cannot realise the canvas, or for lossless pixel calibration.

### Model priority and credentials

- **Prefer GPT Image 2.** When GPT Image 2 is available through the current built-in image tool or a configured compatible route, use it first for the high-fidelity reference/edit and complete-canvas generation required by this prompt.
- Also support Seedance 5.0 Pro, Nano Banana Pro (Gemini Image Pro), Nano Banana 2 (Gemini Image Flash), or another compatible bitmap model only when the actual route can preserve the source, realise the whole finished canvas, render the target-language text, and accept the multiple references needed by a linked wallpaper pack.
- An alternative model changes only the generation route. It must not change this prompt's modes, canvas, source visibility, copy, locale, wallpaper relationship, or complete-canvas-first / composition-fallback-only logic. Do not silently downgrade a hard requirement.
- If no suitable route is available, ask the user to enable an image-generation tool or provide an API key. User-provided credentials may be used for the current task, but never echo, display, log, or expose their value in chat, prompts, or diagnostics. Do not persist them or modify global route configuration unless explicitly requested.
- Judge availability by actual image capability, not by a provider name or one missing environment variable.

Process only the source photograph explicitly supplied for this fresh task. Privately lock identity, structure, pose, direction, action, function, opening, relation, emotional implication, and source colour. Preserve at least three source-specific cues and never borrow from another input, old output, or sample.

## Aesthetic transformation

Read the source's spirit, emotional relation, and implication, then choose only one posture, contour, relation, action, or symbolic detail to carry the whole photograph through layered Chinese silk thread, varied stitch direction, luminous colour, unfinished edges, and Eastern active whitespace.

Use this causal sequence: understand the source's one true core → choose one representative image → preserve three recognition cues → translate form into varied Chinese silk stitches → alternate dense embroidery with a few lines and unfinished contour → derive luminous thread colour from the source → use clean silk ground as air and aftertaste → add one light editorial phrase.

## Hard visual requirements

- One image carries one meaning. Do not embroider the whole photograph or convert every visible object.
- Preserve at least three source cues in one posture, contour, relation, action, or symbolic detail.
- Use authentic flat stitch, long-and-short stitch, couching, wrapped thread, seed stitch, and laid thread as appropriate; vary direction, density, layering, and sheen with the form.
- Let embroidery and non-embroidery compose together: some areas may be precise, others only a few stitches, a free thread, or an unfinished boundary.
- Choose a clean white, cool white, ivory, pale-colour, or source-earned pure coloured silk ground; never default to dirty beige, yellowed linen, stains, or faux ageing.
- Build lively source-derived thread steps through close hues, small complements, tiny high-purity accents, and directional shimmer; rich but not chaotic, bright but not vulgar.

## Copy and locale

Obey the resolved automatic, exact-user, or text-free copy mode and target locale. Use one very short word or phrase distilled from unspoken emotion, action, relation, or implication. Render it as fine native thread, a slender title slip, or minimal editorial type that follows a free strand, enters negative space, or rests beside the embroidered edge. Preserve exact user wording verbatim. In text-free mode render no letters, numbers, captions, labels, or pseudo-text.

## Mode and acceptance


Reject: full-image embroidery, motif piling, fixed pseudo-Chinese palettes, dirty beige or yellowed cloth, all-over traditional pattern, craft-product display, digital fake stitch, literal labels, template composition. Also reject logos, watermarks, swatches, UI, device mockups, unsupported facts, fake foreign text, and unreadable copy.

If any hard condition fails, correct the generated bitmap. Never fake the artwork with programmatic drawing, SVG, HTML, Canvas, 3D code, or a post-composited type overlay.
