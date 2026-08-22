# 04 — Generation compiler

Convert analysis into a short, image-specific generation brief. Long catalogs weaken control.

## Internal design contract

Complete this structure before prompting:

    visual_thesis:
    source_lock:
    protected_core:
    soft_lock:
    transformable_fields:
    field_map:
    effect_relation:
    effect_topology:
      origin:
      direction:
      density:
      scale:
      edge_transition:
      occlusion:
    grain_language:
      mark_family:
      surface_finish:
    hierarchy:
      primary:
      secondary:
      tertiary:
    palette:
    typography:
      mode:
      exact_text:
      compositional_role:
    composition:
    failure_guards:

Do not send the contract verbatim if several fields repeat the same idea.

## Prompt order

Compile in this order:

1. task and source lock;
2. one-sentence visual thesis;
3. protected core;
4. field map;
5. topology and mark behavior;
6. mark family and finish;
7. visual hierarchy;
8. palette and typography;
9. composition and crop;
10. up to four failure guards.

Aim for roughly 120–220 English words or equivalent concise Chinese. Use concrete spatial language.

## Compact template

    Reconstruct the supplied image, preserving [source lock].
    Visual thesis: [scene-specific relationship and intended reading].
    Keep [protected core] exact; allow restrained treatment on [soft lock].
    Build [field count] visual field(s): [field map].
    The effect [origin, direction, density, scale, transition, occlusion].
    Use visible coarse [mark family] with a [finish] finish.
    Reading order: [primary], then [secondary], with [tertiary] kept quiet.
    Palette: [roles]. Typography: [mode and exact wording, or none].
    Keep [composition/crop].
    Avoid [dominant failure guards].

Replace every bracket with source-specific content.

## Source-lock language

Use observable constraints:

- same person, expression, pose, and hand placement;
- same animal species, head shape, posture, and action;
- same product silhouette, logo, label, and proportions;
- same architecture, openings, perspective, and horizon;
- same group count, spacing, and interaction;
- same landmark, reflection axis, crop, and camera angle.

Do not say only “preserve the subject.”

## Field-map language

Describe field behavior rather than decorative coverage:

- begins at the ball-contact point and fans along the court perspective;
- follows the reflection axis, breaking into larger cells toward the camera;
- gathers in the façade modules, then thins across the sky;
- traces the garment folds while leaving face and hands quiet;
- occupies negative space around the product with a narrow density falloff;
- scales down through atmospheric depth toward the horizon.

Avoid phrases such as “fill the background with texture.”

## Variant compilation

First compile a master brief containing the shared:

- source lock;
- thesis;
- protected core;
- field map;
- topology;
- hierarchy;
- composition.

Then add one delta per variant:

| Variant | Allowed delta |
|---|---|
| A | print/ink finish, sharper grouping, editorial contrast |
| B | tactile finish, narrower tonal palette, softer transitions |
| C | one scene-justified experimental behavior |
| D | source-color lock, finish change without hue redesign |

Do not rewrite the protected core or effect origin between variants.

## Negative constraints

Use no more than four and target actual risks:

- no identity or geometry drift;
- no uniform full-frame texture;
- no unrelated literal material objects;
- no invented or misspelled text;
- no thick sticker outline;
- no field that ignores perspective or motion;
- no merged faces or missing limbs;
- no effect stronger than the focal anchor.

Too many negatives dilute the positive design.

## Repair patches

On failure, retain the accepted brief and append one patch.

### Identity drift

    Restore the source's exact identity-bearing geometry. Reduce marks across [protected detail] and move the main density to [safer field].

### Pasted texture

    Rebuild the field from [origin] along [direction]. Vary density and scale with [scene relation]; remove uniform coverage and hard mask edges.

### Literal material collage

    Translate [material] into abstract [mark family] and surface finish. Remove recognizable unrelated objects.

### Weak hierarchy

    Make [primary] the first read, [field] the second, and quiet [support area]. Reduce competing contrast elsewhere.

### Arbitrary region split

    Remove the semantic partition. Let one continuous [relation] connect [areas] with a graded transition.

### Bad typography

    Remove unrequested text, or reproduce only the exact wording “[exact text]” in [real type space].

### Family drift

    Return to the approved master topology and crop. Change only [finish, palette, or one experimental behavior].

## Safe fallback

If two repairs fail:

- use a surface-following, contour-echo, or depth-fade topology;
- reduce effect intensity;
- keep the protected core fully source-faithful;
- remove optional typography;
- retain original-color logic.

Source fidelity outranks spectacle.
