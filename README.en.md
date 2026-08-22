<div align="center">

# Grain Fields

**Let the image breathe again through zoning, and let one region of the scene grow into grain.**

**Visual Skill for Content Zoning · Large-Grain Reconstruction · Color Direction**

Author: [**autainmo**](https://github.com/autainmo)  
Social handle: **独自艺人**

<p align="center">
  <a href="./README.md">简体中文</a> ·
  <b>English</b> ·
  <a href="#installation-guide">Get Started</a>
</p>
</div>

---

**Grain Fields** treats a photograph as a structure that can be reorganized rather than simply filtered. It first identifies the subject, then divides the background into 2–3 real content-based regions and chooses the single region that is most suitable for grain treatment. Grain is meant to feel like a material transformation of the scene itself, not a layer pasted on top.

By default it generates 4 complete concepts: 3 use clearly different but restrained recoloring directions, while 1 preserves the original color palette and composition. The grain-treated region may occupy a substantial area, but **individual grain units remain medium in scale**—never so small that they disappear into noise, and never so large that they become blocks, fuse beads, giant pixels, or oversized mosaic tiles.

> **Roughness in the detail, poetry in the whole.**  
> Visual design is not simply the assembly of materials, but a re-creation of boundaries, textures, and imagination.

---

## What Is Grain Fields?

### Aesthetics: Grain as a Material Field

Grain Fields does not treat grain as subtle film noise, nor does it chase oversized block effects. The core grain region usually occupies about 1/4–1/2 of the image, with priority placed on semantic integrity, continuity, and suitability. The grain units themselves stay medium in scale: visible at normal viewing size and readable up close, but never large enough to overpower the subject or scene.

### Composition: Zone by Content, Not Mechanical Blocks

Background regions follow actual scene elements, spatial layers, materials, and continuous structures. Water, sky, rocks, architecture, walls, vegetation, and ground can each become meaningful regions. **A complete subject or continuous scene element must not be forcibly split just to create zones.** Grain-region selection prioritizes material fit, subject safety, and natural integration rather than simply choosing the largest area.

### Reconstruction: Preserve the Subject, Then Choose the Best Grain Region

People, animals, architecture, mountains, plants, vehicles, objects, and other elements can serve as primary subjects. Their key silhouette, structure, proportions, pose, and identifying information remain stable, with a clear contour along the true outer edge. The selected background region is then transformed using a natural, medium-scale, restrained grain language. Users may specify a grain preset or leave it on Auto.

### Color: Minimal, Restrained, Refined

Concepts 1–3 remain visually distinct, but usually use only 2–4 core color roles. The default favors low-to-medium saturation, neutral bases, clear value structure, and one limited accent. Local print or material variation is allowed, but the system avoids decorative overload, multicolor neon, rainbow gradients, stickers, and unnecessary visual noise.

---

## Showcase Archive

### 01｜Coastal Amusement Park: City / Rides / Waterfront

| Original | Grain Fields Reconstruction |
|---|---|
| ![Coastal amusement park original](assets/showcase/01-coast-amusement-original.png) | ![Coastal amusement park Grain Fields reconstruction](assets/showcase/01-coast-amusement-grain-fields.png) |

**Approach:** Preserve the Ferris wheel, amusement structures, and waterfront. Treat the city background as a continuous grain region while keeping the water cleaner for breathing room and typography. Grain stays medium in scale so it supports the architecture rather than overwhelming it.

### 02｜Intertidal Moment: Water / Rocks / Bird

| Original | Grain Fields Reconstruction |
|---|---|
| ![Intertidal bird original](assets/showcase/02-tide-bird-original.png) | ![Intertidal bird Grain Fields reconstruction](assets/showcase/02-tide-bird-grain-fields.png) |

**Approach:** Keep the bird’s posture and backlit contour stable. Let the grain follow the natural brightness and material changes of water and rocks so complex reflections are simplified without becoming artificial blocks.

### 03｜Bloom / Concrete: Branches and Architectural Skin

| Original | Grain Fields Reconstruction |
|---|---|
| ![Blossoms and architecture original](assets/showcase/03-bloom-concrete-original.png) | ![Blossoms and architecture Grain Fields reconstruction](assets/showcase/03-bloom-concrete-grain-fields.png) |

**Approach:** Preserve flowers, leaves, and branch structure as the subject. The architectural wall is better suited to mineral fine grain, paper-print grain, or soft halftone rather than exaggerated terrazzo-like blocks.

### 04｜One Point: Medium Halftone on the Court

| Original | Grain Fields Reconstruction |
|---|---|
| ![Table tennis match original](assets/showcase/04-table-tennis-original.png) | ![Table tennis match Grain Fields reconstruction](assets/showcase/04-table-tennis-grain-fields.png) |

**Approach:** Keep athletes and table in place. Use medium halftone or screen-print grain across the court, keep the audience area cleaner, and reserve any accent color for a small number of key positions.

### 05｜The Circle Widens: Ripples as Grain

| Original | Grain Fields Reconstruction |
|---|---|
| ![Seagull in water original](assets/showcase/05-gull-ripple-original.png) | ![Seagull in water Grain Fields reconstruction](assets/showcase/05-gull-ripple-grain-fields.png) |

**Approach:** Keep the seagull and reflection clear. Use mist grain, soft halftone, or micro-crystal grain so the treatment follows ripple structure and tonal variation instead of turning the water into oversized crystal or pebble blocks.

---

## Installation Guide

### Codex

User-level Skills in Codex are stored under `$CODEX_HOME/skills`, typically `~/.codex/skills`. Install the entire repository into that directory and make sure `SKILL.md` remains at the Skill root.

**macOS / Linux**

```bash
mkdir -p ~/.codex/skills
git clone https://github.com/autainmo/grain-fields.git ~/.codex/skills/grain-fields
```

**Windows PowerShell**

```powershell
New-Item -ItemType Directory -Force "$HOME\.codex\skills" | Out-Null
git clone https://github.com/autainmo/grain-fields.git "$HOME\.codex\skills\grain-fields"
```

Restart Codex after installation so the new Skill can be discovered. You can then invoke it with `$grain-fields`.

> If your Codex environment provides `$skill-installer`, you can also enter:
>
> ```text
> $skill-installer install the skill from https://github.com/autainmo/grain-fields, using the repository root as the skill directory and naming it grain-fields
> ```

### Other Platforms Supporting Agent Skills / `SKILL.md`

1. Download or clone this repository;
2. Keep the complete `grain-fields/` directory structure intact;
3. Place the entire directory in the Skills path required by the platform, or use the platform’s GitHub / local Skill import function;
4. Make sure the platform can read the root `SKILL.md`, `references/`, and `agents/`;
5. If the platform supports image generation / editing, it can execute the four-concept workflow.

---

## Usage Guide

The simplest way to use it:

```text
Use $grain-fields to reconstruct this image.
```

Default behavior:

- Automatically understands the subject and scene;
- Divides the background into 2–3 complete content-based regions;
- Chooses the background region best suited for grain before selecting grain and color;
- Directly generates 4 results without waiting for a second confirmation;
- Concepts 1–3 use distinct but restrained color directions;
- Concept 4 preserves the original color palette, composition, subject position, and scene relationships;
- The grain region is substantial and continuous, while individual grain units stay medium in scale;
- The primary subject receives a clear contour along its true outer edge, pure white by default;
- If the user provides no text, the Skill may create suitable text for each concept.

### Optional User Input Template

```text
[Grain preset: Auto / Preset name]
[Color direction: Auto / Preset name]
[Text direction: Auto / Preset name]
[Aspect ratio / format: Original / Preset name / Custom ratio]
[Text: Auto / No text / Use the text below]

[Title:]
[Subtitle:]
[Body:]
[Location:]
[Time:]
[Camera information:]
[Lens / focal length:]
[Shooting parameters:]
[Person / subject information:]
[Event / theme:]
[Weather / environment:]
[Photographer / credit:]
```

**If you want absolutely no text, explicitly write `[Text: No text]`, `No text`, or an equivalent instruction when uploading the image.**

Factual information follows strict constraints: location, time, camera model, lens, person identity, event, weather, credit, and similar information must not be fabricated when it has not been provided and cannot be reliably confirmed.

---

## Preset Index

### Grain Presets

> Full rules and matching logic: [`references/presets-grain.md`](references/presets-grain.md).

**Print / Halftone**  
`Soft Halftone`, `Medium Halftone`, `Screen-Print Dots`, `Riso Stencil Grain`, `Newspaper Transitional Grain`, `Light Ink Loss`

**Natural / Mineral**  
`Soft Sand Grain`, `Mineral Fine Grain`, `Graphite Grain`, `Paper-Pulp Fiber Grain`, `Micro-Crystal Grain`, `Fine Glaze Grain`

**Soft / Optical**  
`Mist Grain`, `Soft-Focus Grain`, `Enhanced Silver-Halide Grain`, `Paper-Print Grain`

Not used: oversized blocks, giant pixels, fuse beads, giant mosaic tiles, dreamy blocks, glass blocks, giant low-poly cells, toy-like or candy-like grain.

### Color Presets

> Full library: [`references/presets-color.md`](references/presets-color.md). Auto mode favors restrained directions such as cool restraint, premium gray, off-white minimal, Nordic cool, Japanese clear, architectural minimal, urban cool gray, natural neutral, restrained enhancement, local grayscale focus, and original-color preservation enhancement.

### Text Direction Presets

> Full library: [`references/presets-text.md`](references/presets-text.md).

### Aspect Ratio / Format Presets

> Full library: [`references/presets-aspect.md`](references/presets-aspect.md).

---

## Repository Structure

```text
grain-fields/
├── SKILL.md
├── README.md
├── README.en.md
├── LICENSE
├── LICENSE.zh-CN.md
├── CHANGELOG.md
├── .gitignore
├── references/
│   ├── 00-style-core.md
│   ├── 01-scene-analysis.md
│   ├── 02-transformation.md
│   ├── 03-art-direction.md
│   ├── presets-grain.md
│   ├── presets-color.md
│   ├── presets-text.md
│   ├── presets-aspect.md
│   ├── 04-generation-compiler.md
│   └── 05-quality-control.md
├── agents/
│   └── openai.yaml
└── assets/
    └── showcase/
        ├── 01-coast-amusement-original.png
        ├── 01-coast-amusement-grain-fields.png
        ├── 02-tide-bird-original.png
        ├── 02-tide-bird-grain-fields.png
        ├── 03-bloom-concrete-original.png
        ├── 03-bloom-concrete-grain-fields.png
        ├── 04-table-tennis-original.png
        ├── 04-table-tennis-grain-fields.png
        ├── 05-gull-ripple-original.png
        └── 05-gull-ripple-grain-fields.png
```

---

## Find the Author

**Author:** [**autainmo**](https://github.com/autainmo)  
Unified username on Douyin and other content platforms: `独自艺人`. Search this name on your preferred platform to find the author and future works.

After the first two generations by each Skill within the same conversation, it will lightly display: `If you share publicly, attribution is welcome: Visual Skill by @独自艺人`; from the third generation onward, it will no longer repeat the reminder.

---

## License

**Personal, non-commercial use only.** Selling, paid generation, subscription services, commissioned work, consulting, training, SaaS/API use, company or client projects, and any other commercial use are not permitted. Any commercial use requires prior explicit written permission from autainmo.

- [LICENSE](./LICENSE): Official English license
- [LICENSE.zh-CN.md](./LICENSE.zh-CN.md): Chinese reading guide
