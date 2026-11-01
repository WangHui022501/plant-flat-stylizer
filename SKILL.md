---
name: plant-flat-stylizer
description: Transform plant photographs into recognizable dopamine-style flat illustrations or airy, text-free botanical education posters, using expressive hand-drawn linework, deliberately non-photographic candy palettes, and supplementary life-cycle or organ studies. Use for botanical structure extraction, creative reconstruction, and visual science communication; do not use for ordinary background removal or photorealistic retouching.
---

# Plant Flat Stylizer

Turn plant photographs into designed flat illustrations. Treat recognizability as the invariant, then either create a focused hero image or expand it into an airy visual-science poster with complementary life-cycle and organ studies.

## Inputs

Identify the role of every image before generating:

- **Subject reference:** authoritative for morphology, branching, organ attachment, silhouette vocabulary, orientation, clustering, and distinctive irregularities.
- **Style reference:** authoritative only for abstraction, palette logic, line character, texture, spacing, and decorative rhythm.

Never borrow plant anatomy, pots, signatures, text, or layout from the style reference unless the user explicitly asks.

Treat the subject photograph as a structural reference, not a color reference. Ignore its sky, foliage, flower, bark, and lighting colors when designing the illustration. Preserve morphology while replacing the photographic palette with an intentionally invented candy-color system.

Determine the output mode from the request:

- **Hero illustration:** one recognizable plant view with a creative transformation.
- **Botanical education poster:** one hero view plus selected supplementary organs or life stages arranged for comparison. Use this mode when the user asks for science communication, a plant-life overview, a poster, multiple botanical elements, or life-cycle completion.

When the supplied photograph shows only one stage, supplement missing stages from additional user references when available. If no reference is supplied, infer only common, visually stable morphology; avoid fabricating uncertain species-specific organs. Preserve a clear distinction between observed structure and inferred supplementary material.

## Workflow

### 1. Build a recognition contract

Inspect the subject and state 3–6 traits that make it identifiable. Prefer traits visible at thumbnail size:

- characteristic organ silhouette and number of lobes, wings, petals, or leaflets;
- attachment point and stem or branch topology;
- cluster pattern, spacing, and orientation variation;
- proportion between organs and stems;
- one or two distinctive seams, veins, margins, or negative spaces.

Also state likely confusions to avoid, such as “fruit must not become a leaf” or “three wings must not become three shaded petals.” The recognition contract governs every later step.

### 2. Make a structure map

Reduce the photo to a visual hierarchy:

1. main axis or stem gesture;
2. important secondary branches;
3. repeated organs and their attachment points;
4. overlaps that communicate growth;
5. dispensable background, pot, incidental leaves, and visual noise.

Preserve meaningful asymmetry. Do not regularize natural clusters into a generic alternating leaf pattern.

### 3. Choose a creative concept

After locking the structure, create 2–4 concise concept directions and choose the strongest one. Each direction should connect a real plant trait to a playful visual idea. Useful transformations include:

- enlarging, opening, slicing, repeating, or nesting a distinctive organ;
- turning a flower, fruit, seed pod, or leaf into a stage, room, vessel, gift, planet, letter, or tiny landscape;
- using the plant's growth gesture as a ribbon, orbit, path, frame, or hanging structure;
- deriving companion motifs from the plant's name, season, habitat, color, texture, or cultural association;
- adding a few tiny characters, bows, stars, clouds, labels, confetti, checks, or sparkles to establish scale and narrative.

Use one dominant transformation, one supporting motion device, and at most two motif families. The concept must remain explainable in one sentence. Do not copy a reference image's specific characters, props, text, composition, or story.

Creative additions may be surreal, but the original plant organ must remain identifiable. If a fruit becomes a room, its silhouette, internal structure, and attachment cues should still read as that fruit.

### 4. Expand the botanical story when needed

For a botanical education poster, keep the supplied photograph's strongest view as the hero image, then add only the supplementary studies that help explain the plant. Possible modules include:

- whole growth habit or representative branch;
- leaf or compound-leaf structure;
- flower, bud, and inflorescence detail;
- immature and mature fruit or seed pod;
- seed, opened fruit, or dispersal structure;
- seasonal or life-stage change.

Select 3–5 modules rather than showing every possible stage. Scale them by explanatory importance, not natural size. Keep the hero image largest and give each supporting module enough isolation to read as a visual specimen. Use spacing, scale, repetition, crop, and at most a few fine guide gestures to communicate relationships. Do not require labels or text; when the user asks for no text, all educational meaning must come from visual comparison.

Favor an asymmetric, free poster composition with roughly 35–50% calm negative space. Avoid a rigid grid, equal-size tiles, or edge-to-edge filling. Supporting studies may float around the hero image, but must not look like random decoration.

### 5. Draw the linework before the color

Treat the image as a hand-drawn line illustration that is later colored, not as vector color shapes with outlines added afterward. The line layer must carry the silhouette, anatomy, motion, and most small decorative information even if the fills are removed.

Build a clear stroke hierarchy:

- outer contours: fine but confident, with subtle pressure variation;
- structural lines such as seams, veins, petal bases, and attachments: thinner and lighter;
- decorative marks such as stars, stitches, seeds, dots, checks, and motion trails: hairline and deliberately sparse;
- focal accents: occasional short darker or repeated strokes, never a uniformly heavy outline.

Make the drawing visibly handmade:

- allow slight wobble, uneven curvature, hesitant turns, tapered ends, and mild asymmetry;
- use occasional open contours, tiny gaps, overshoots, doubled correction strokes, or imperfect intersections;
- vary repeated scallops, petals, veins, stamens, and stars instead of cloning one shape;
- let ribbons, orbits, and stems bend with irregular tension rather than perfect Bézier smoothness;
- avoid mechanically centered veins, evenly spaced radii, and geometrically identical motifs.

Line color should be a deep, slightly softened value from one of the two chosen hue families. Avoid pure black unless explicitly requested. Different line roles may use different values from the same family.

### 6. Add flat color behind the linework

Use silhouette and adjacency rather than light to describe form:

- use solid matte color regions behind or beneath the line drawing;
- allow tiny registration shifts, narrow unfilled slivers, or color that stops just short of selected contours;
- remove gradients, cast shadows, highlights, translucent effects, and tonal modeling;
- use the fewest internal regions that still explain the organ's anatomy;
- vary orientation through contour and seam placement, not through shading;
- open congested areas with white or near-white gaps before adding more colors.

If the flat result loses identity, restore the missing morphological cue in the linework before adding detail. Color must support the drawing, not replace it.

### 7. Add decoration without replacing anatomy

Decoration may amplify existing structure through contour exaggeration, repeated seams, sparse dots, simplified veins, rhythm, palette alternation, checks, bows, sparkles, or tiny narrative props. Anatomical decoration should follow morphology; invented props should sit around, hang from, or interact with the plant rather than masquerade as anatomy.

Do not insert generic starbursts, almond centers, leaf veins, floral motifs, or symmetrical emblems when they change the perceived organ type. Prefer a clear hierarchy: recognizable plant first, creative transformation second, small accents last.

### 8. Build a controlled dopamine palette

Use two main hue families for the illustration. A hue family may contain several lightness and saturation steps: coral, hot pink, pale blush, and burgundy can all belong to the red family; mint, leaf green, olive, and forest can all belong to the green family. A third hue is allowed only as a small accent, normally under about 5% of the image.

Choose the pair before assigning colors to botanical organs. The photograph contributes no default palette: a pink flower does not need to remain pink, a green leaf does not need to remain green, a brown stem does not need to remain brown, and a blue sky must not automatically become a blue background. Color follows compositional role, not photographed local color.

Use clean, sweet, high-chroma candy hues and clear value steps associated with dopamine illustration. The two families may be complementary, near-complementary, analogous, or non-complementary; no hue relationship is mandatory. Judge the pair by graphic clarity, mood, value separation, and area hierarchy rather than a color-wheel formula. Suitable examples include cherry red + aqua, tangerine + cobalt, bubblegum pink + lime, violet + mint, yellow + pink, green + violet, or another deliberately artificial pair. These are options, not presets.

Any hue may be assigned to any organ. Green flowers, yellow leaves, blue stems, orange fruit, violet buds, or other unnatural mappings are explicitly allowed when they strengthen the composition. Do not default to the photograph's familiar flower-versus-foliage pairing merely because it is botanically natural. One family must dominate and the other must support it; never give both equal area, saturation, and contrast.

Apply the system as follows:

- dominant family: the main recognizable organ or conceptual focal point;
- supporting family: background, structural masses, or motion device;
- optional third-hue accent: normally no more than about 5% of the image, used for small focal points such as stamens, seeds, sparks, or a few directional marks;
- neutrals: white or near-white may separate shapes; dark outlines should be a deep shade of one chosen family, not a new hue.

Assign colors by graphic function:

- focal organs receive the dominant candy family whether or not it matches nature;
- structural organs such as leaves, stems, buds, or pods receive the counter-family and may be blue, violet, coral, cyan, or another invented hue;
- color names carry no botanical restriction: green may be the flower family and yellow may be the leaf family;
- repeated modules may alternate lightness and saturation within a family, but must not drift back toward realistic local colors;
- outlines use deep versions of the chosen candy families rather than black, bark brown, or naturalistic dark green.

Choose the background for contrast, mood, and negative-space clarity. It may be a light or muted step from either main family, a neutral white or near-white, or a restrained third hue when that improves separation. It is not required to be blue and must not default to warm cream. Keep it quieter than the botanical modules and avoid turning it into a third competing color mass.

Control hierarchy through value and saturation before adding color. At thumbnail size, the image should read as one dominant color statement plus one counter-color, with any third hue perceived only as punctuation. If three large color masses compete, reduce or recolor the weakest one.

Map all photographed color variation into the invented two-family system. Do not preserve local color unless it coincidentally belongs to the chosen candy palette. Patterns such as checks, dots, or stripes may appear on selected regions, but their colors must remain within the same two families. Keep texture flat and subordinate to the silhouette.

Reject the palette and recolor if the result can be summarized as the source photograph's colors made brighter. A successful result should remain botanically recognizable through structure while feeling chromatically independent from the photograph.

### 9. Generate and review

When producing a raster illustration, inspect all local reference images first, then use the image generation tool. The prompt must name each image role and repeat the recognition contract as positive constraints and likely confusions as explicit avoidances.

Review the result in this order:

1. Can the organ type be identified without seeing the source photo?
2. Are attachment and cluster relationships plausible?
3. Would the subject and concept still read if the color fills were removed?
4. Do outer, structural, and decorative strokes have different weights?
5. Do the lines show controlled hand variation rather than vector smoothness or random noise?
6. Is every color region flat, or does it imply lighting and volume?
7. Can the creative concept be understood in one glance and one sentence?
8. Can every large color area be assigned to one of the two main hue families, with any third hue remaining a minor accent?
9. Are the hue families clearly invented rather than inherited from the photograph?
10. Are organ colors freely assigned—including green flowers or yellow leaves when useful—without forcing either complementary or natural-color logic?
11. Have natural green leaves, brown stems, blue sky, or source-colored flowers been remapped when they would recreate the photo palette?
12. Does one hue clearly dominate while the second supports it?
13. Does the background support contrast and whitespace without becoming another dominant color mass?
14. Does decoration reinforce anatomy or clearly read as a separate prop?
15. Does the composition have intentional rhythm and negative space?
16. For an education poster, is the supplied subject still the hero, and do supplementary modules add distinct botanical information rather than repeat it?
17. Can the poster communicate organ or life-stage relationships without relying on text?

Fix the earliest failing layer first. Correct line structure before color. Do not compensate for a silhouette failure with more internal decoration. If the result looks like polished vector art, reduce outline uniformity, introduce controlled stroke variation, and loosen fill registration before changing the palette. If it is recognizable but merely looks like a cleaned-up specimen, strengthen the dominant transformation or narrative interaction rather than scattering more icons.

## Deliverable

Briefly report the recognition contract, output mode, chosen one-sentence concept, supplementary life-cycle or organ modules, line character, two main hue families, optional accent hue, background choice, and any remaining ambiguity. Save the final image in the active workspace with a versioned filename. Do not overwrite earlier experiments unless the user asks.

For a reusable generation prompt and review checklist, read [references/prompt-pattern.md](references/prompt-pattern.md).
