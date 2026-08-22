# 05 — Quality control

Quality control is perceptual, not a checklist of preset compliance.

Inspect the source and every output side by side:

1. at thumbnail size, about 25 percent;
2. at full resolution around identity details, field boundaries, and text.

Never approve from the prompt alone.

## Hard gates

Any failure rejects the output.

### H1 — Identity and geometry

The anchor, pose, count, product form, architecture, perspective, horizon, action, and critical details remain recognizable and factually consistent.

### H2 — One thesis and focal order

The image makes one coherent visual claim. The primary anchor reads first, the effect second, and quiet support last.

### H3 — Relation and topology

The field has a visible scene-derived origin, direction, density, scale, transition, and occlusion logic.

### H4 — Integrated grain

Coarse marks are visible at thumbnail scale and feel integrated. No wallpaper effect, pasted material mask, arbitrary partition, or unrelated literal-object collage.

### H5 — Text and facts

All required wording, logos, numerals, and factual details are exact. No invented metadata or accidental pseudo-text.

### H6 — Family coherence

When variants are requested, they preserve the same source lock, thesis, topology, hierarchy, and crop unless the user explicitly asked for structural alternatives.

## Diagnostic score

After the hard gates pass, score each dimension from 0 to 2:

| Dimension | 0 | 1 | 2 |
|---|---|---|---|
| Source fidelity | material drift | minor drift | exact where critical |
| Scene specificity | generic | partly derived | inseparable from source |
| Topology clarity | random | implied | immediately readable |
| Grain legibility | too fine or noisy | uneven | coarse and controlled |
| Hierarchy | competing | workable | decisive |
| Integration | pasted | partly integrated | native to scene |
| Palette and value | flattened | adequate | supports focal order |
| Typography or type restraint | wrong or intrusive | acceptable | exact and purposeful |

Pass threshold: at least 13 of 16, with no hard-gate failure.

For a no-text image, score typography as 2 only when omitting text is clearly the correct compositional decision.

## Named rejection patterns

### Wallpaper effect

The same texture covers most of the frame with no density or directional logic.

### Pasted material mask

The effect has a hard selection edge and does not share perspective, lighting, motion, or surface behavior with the source.

### Arbitrary split

Regions exist because the method demanded them, not because the scene supports them.

### Uniform coverage

Everything is equally active. There is no quiet support level.

### Directionless field

Marks have no origin, path, scale change, or dissipation.

### Literal material hallucination

Unrelated stones, flowers, food, tiles, or objects appear as content rather than abstract marks or finish.

### Repeated poster template

Typography, placement, outline, and crop repeat from previous outputs regardless of source.

### Identity drift

Face, anatomy, species, product, architecture, group count, action, or factual text changes.

### Texture stronger than meaning

The field is noticed first and does not point back to the anchor.

## Repair matrix

| Failure | Preserve | Change |
|---|---|---|
| Identity drift | crop, thesis, safe fields | restore protected core; reduce overlap |
| Wallpaper | anchor, mark family | rebuild origin, density, scale, quiet areas |
| Pasted mask | palette, thesis | replace hard boundary with topology-following transition |
| Literal collage | topology, hierarchy | abstract objects into marks and finish |
| Arbitrary split | source lock, primary relation | merge regions into continuous relation field |
| Weak hierarchy | topology, protected core | redistribute contrast, density, and quiet space |
| Fine invisible texture | thesis, crop | enlarge dominant marks; reduce micro-noise |
| Bad text | image treatment | remove optional text or restore exact wording |
| Variant drift | accepted anchor output | restore master brief; keep one controlled delta |
| Over-outlined subject | source lock | replace outline with value, hue, or density separation |

Repair the single dominant failure first. Do not make unrelated redesigns during a repair.

## Family-level inspection

View all variants together and ask:

- Do they clearly belong to one reconstruction family?
- Is each variant meaningfully different without changing the scene logic?
- Does D retain the source's color identity?
- Is C experimental in one controlled way rather than simply noisier?
- Does any output repeat a stock title, outline, or layout?

Reject the whole family only when the shared master brief is wrong. Otherwise regenerate only failing members.

## Final acceptance record

For each output record internally:

- hard gates: pass or fail;
- diagnostic score;
- dominant risk;
- repair count;
- final status.

Stop after two unsuccessful repair attempts. Use the safe fallback in references/04-generation-compiler.md and inspect once more.
