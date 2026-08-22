# 03 — Art direction

Build the reconstruction as a functional grammar:

relation basis → effect topology → mark family → behavior → finish → palette → typography

Do not begin with a material noun.

## 1. Relation basis

Select the source relationship that carries meaning:

| Basis | Best evidence in the source | Useful effect |
|---|---|---|
| Geometry | planes, curves, axes, enclosures | clarify structure |
| Motion | gesture, wake, trajectory, impact | reveal action |
| Light | highlight, shadow, glow, value break | separate depth and focus |
| Material | transparent, rough, reflective, fibrous surfaces | translate surface logic |
| Depth | scale change, overlap, atmospheric loss | organize near-to-far |
| Repetition | modules, crowds, windows, foliage, waves | create rhythm |
| Reflection | mirror axis, distortion, refraction | link anchor and surface |
| Perspective | vanishing lines, floor grid, façade | preserve spatial direction |
| Contour | silhouette, rim, boundary echo | reinforce identity |
| Negative space | quiet void, opening, directional absence | isolate or point |

Use one primary basis and at most one support basis.

## 2. Effect topology

Topology describes where the field begins, how it travels, and how it ends.

### Surface-following

Marks conform to a surface, plane, fold, water layer, wall, garment, or product body.

Use when the source has readable volume or material. Change mark scale with perspective and curvature.

### Radial

Marks expand from a center such as impact, face, light, flower, wheel, sound source, or contact point.

Use density falloff and imperfect rings. Protect the origin from being buried.

### Flow

Marks follow a directional path: gesture, road, current, fabric, hair, smoke, crowd movement, or gaze.

Define a start, vector, acceleration, and dissipation.

### Contour-echo

Marks repeat, offset, break, or thicken around a silhouette or structural edge.

Use for portraits, animals, products, landforms, and graphic subjects. Keep identity-critical edges clean.

### Structural-grid

Marks inherit perspective, modules, tiling, windows, court lines, shelves, seating, or urban organization.

Use local irregularity so the result does not become a sterile grid.

### Clustered-organic

Marks gather in islands according to growth, foliage, foam, clouds, crowds, corrosion, or biological grouping.

Clusters need a cause and density hierarchy. Avoid random pebble scatter.

### Fragmentation

A continuous form breaks into displaced pieces along a justified stress, motion, light, or transition.

Keep enough original geometry to reconstruct the source mentally. Do not fragment faces or logos without explicit permission.

### Depth-fade

Mark size, contrast, sharpness, or spacing changes with distance.

Use for landscape, street, interior, group, and atmospheric scenes.

### Negative-field

Marks occupy the space around an anchor and define it by absence.

Use when the source has strong quiet space. Avoid accidental sticker cutouts.

## 3. Mark family

Choose one dominant family and optionally one subordinate family.

| Family | Character | Strong uses |
|---|---|---|
| Dot | measured, optical, granular | light, crowds, halftone, atmosphere |
| Patch | painterly, organic, tonal | water, foliage, skin-safe surroundings |
| Chip | fractured, mineral, energetic | impact, architecture, erosion |
| Stroke | directional, gestural | motion, fabric, wind, roads |
| Cell | connected, biological, modular | foam, growth, network, clustering |
| Tile | planar, constructed | architecture, product, surface rhythm |
| Pixel | digital, stepped, precise | screens, graphics, technical scenes |
| Fiber | tactile, flowing, handmade | textiles, hair-adjacent fields, vegetation |
| Aperture | light-bearing, perforated | glow, windows, bokeh, transparency |
| Ink gap | subtractive, printed, high contrast | editorial, silhouette, negative field |

The dominant marks must remain visible at thumbnail scale. Fine texture may support them but cannot replace them.

## 4. Mark behavior

Specify all six variables:

### Origin

The event, anchor, edge, plane, or depth band where marks begin.

### Direction

Radial, horizontal, vertical, diagonal, curved, perspective-convergent, contour-following, or locally turbulent.

### Density

State where marks are dense, moderate, sparse, and absent. Preserve a quiet support level.

### Scale

State how marks grow or shrink with depth, distance, curvature, importance, or energy.

### Edge transition

Sharp cut, staggered break, feathered fade, porous boundary, overlap, or clean exclusion.

### Occlusion

State which marks pass behind, across, or in front of soft-locked surfaces. Protected cores remain readable.

## 5. Surface finish

Finish controls appearance, not structure.

### Print or ink

Halftone, screenprint, risograph, dry ink, misregistration, stipple, linocut, or offset texture.

### Paper or collage

Torn edges, cut paper, pulp, layered print, handmade registration. Use only with deliberately graphic boundaries.

### Mineral or mosaic

Stone-like, ceramic, glass, terrazzo, aggregate, or crystalline finishes. Render as abstract chips or tiles unless the user requests literal material.

### Paint

Gouache, impasto, dry brush, watercolor granulation, enamel, or scraped pigment.

### Optical or translucent

Refraction, apertures, lensing, glassy cells, diffraction, or soft luminous layering.

### Digital

Pixel clusters, compression blocks, scanlines, vector cells, ordered dithering, or interface-like grids.

### Textile or handmade

Fiber, weave, embroidery-like marks, felt, stitch rhythm, or woven paper.

### Industrial

Perforation, stamped metal, rubber, concrete grain, machined cells, or modular panels.

Never introduce piles of unrelated literal objects simply because a finish name suggests them.

## 6. Palette

Build roles, not a list of colors:

- dominant field color;
- support color;
- anchor color;
- optional accent;
- quiet neutral.

Preserve value hierarchy. Recolored outputs may change hue logic but should retain the same focal order.

## 7. Typography

Choose one mode:

### Exact source text

Preserve wording, case, punctuation, and factual placement when identity depends on it.

### Headline

Use only when the user requests poster treatment or when clear negative space supports it. One concise line is usually enough.

### Caption

Small supporting text that explains rather than competes.

### Metadata

Use only user-provided facts. Never invent dates, coordinates, issue numbers, or credits.

### None

The default when text would weaken the image.

Typography must participate in composition. It is not a required brand stamp.

## 8. Variant family

The default four outputs share:

- source geometry;
- protected core;
- visual thesis;
- primary relation;
- effect topology;
- focal order.

They differ through controlled deltas:

### A — Editorial/graphic

Sharper grouping, clearer negative space, assertive but economical contrast, print or ink finish.

### B — Material/tonal

Richer surface depth, restrained hue range, tactile finish, softer transitions.

### C — Experimental

One bolder change in scale, occlusion, fragmentation, translucency, or color. It must remain justified by the same relation.

### D — Original-color logic

Keep the source's dominant hue relationships and recognizable material cues. Vary finish and mark behavior without recoloring the image into a new identity.

Do not create four unrelated concepts.

## 9. Automatic selection

When no style is named:

1. rank candidate relations;
2. choose the topology that best expresses the winner;
3. choose a mark family compatible with topology and source scale;
4. choose the lightest finish that makes the marks coherent;
5. set palette and typography last.

The phrase “automatic style” never means random preset selection.

## 10. Legacy names

If the user explicitly names an earlier preset or a material family, read references/07-legacy-preset-aliases.md. Translate that name into this functional grammar before prompting.
