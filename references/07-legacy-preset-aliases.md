# 07 — Legacy preset aliases

Read this file only when the user explicitly names an earlier Grain Fields preset, a material category, or an exact granular unit.

Automatic mode must not load the legacy catalog.

## Translation rule

Translate every legacy name into:

1. scene relation;
2. effect topology;
3. abstract mark family;
4. surface finish;
5. mark behavior.

The user-selected name constrains the mark or finish. It does not override identity fidelity, scene geometry, topology, or quality gates.

## Category router

| Legacy category | Default mark family | Default finish | Typical topology |
|---|---|---|---|
| 印刷 / 油墨 | dot, ink gap, stroke | print or ink | contour-echo, structural-grid, negative-field |
| 像素 / 数字方块 | pixel, tile | digital | structural-grid, depth-fade, fragmentation |
| 梦幻 / 半透明 | aperture, cell, patch | optical or translucent | flow, clustered-organic, depth-fade |
| 拼豆 / 手工 | cell, tile, dot | textile or handmade | structural-grid, contour-echo |
| 马赛克 / 瓷砖 | chip, tile, cell | mineral or mosaic | surface-following, structural-grid |
| 纸张 / 拼贴碎片 | patch, chip, ink gap | paper or collage | fragmentation, contour-echo, negative-field |
| 绘画 / 颜料 | patch, stroke, chip | paint | surface-following, flow, clustered-organic |
| 自然物质 | patch, chip, fiber, cell | mineral, paint, or handmade | clustered-organic, flow, depth-fade |
| 纺织 / 毛绒 | fiber, stroke, cell | textile or handmade | surface-following, flow |
| 光学 / 圆形 | aperture, dot, cell | optical or translucent | radial, depth-fade, clustered-organic |
| 几何大颗粒 | tile, pixel, aperture, chip | digital or industrial | structural-grid, radial, negative-field |
| 破损 / 衰败 | chip, ink gap, patch | industrial, paper, or paint | fragmentation, surface-following |
| 食物 / 糖果式 | dot, cell, patch | paint or translucent | clustered-organic, radial |
| 金属 / 工业 | tile, aperture, chip | industrial | structural-grid, surface-following |
| 特殊艺术化 | choose by scene | choose by scene | choose by scene |

## Literalness boundary

If the user asks for “mosaic,” “candy,” “petals,” “stones,” or another material:

- default to abstract marks carrying that finish;
- do not generate recognizable piles of unrelated objects;
- allow literal units only when the user's wording clearly requests them as content;
- even then, orient and scale them according to the chosen topology.

For example, “糖果质感” means rounded translucent cells and saturated highlights by default, not a field made of recognizable candy pieces.

## Exact legacy lookup

If an exact old preset name cannot be resolved here:

1. search section 3.7 of references/08-legacy-v1-art-direction.md;
2. read only the matching entry and its category context;
3. extract its mark and finish characteristics;
4. translate them into the current functional grammar;
5. return to the current generation compiler and quality control.

Do not copy the old preset's fixed region counts, coverage quotas, mandatory outline, or automatic-selection behavior.

## Precedence

1. exact user request;
2. protected identity and facts;
3. current scene relation and topology;
4. legacy mark or finish character;
5. optional typography and decorative detail.
