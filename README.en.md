<div align="center">

# 颗粒分域 · Grain Fields

**Let the image breathe again through content zoning, and let one part of the scene grow into grain.**

**Visual Skill for Content Zoning · Large-Grain Reconstruction · Color Direction**

Author: [**autainmo**](https://github.com/autainmo)  
Social handle: **独自艺人**

<p>
  <a href="./README.md">简体中文</a> ·
  <b>English</b> ·
  <a href="#installation">Get Started</a>
</p>

</div>

---

**Grain Fields** believes that every photograph already contains an order that can grow again.

## What is Grain Fields?

### Aesthetics: grain is structure, not noise

The core grain field must be one complete, continuous background content region, usually covering about **1/3–1/2** of the entire image, and larger when the content allows. The grain itself must also be coarse enough that, at normal viewing size, individual particles, large dots, large-scale halftones, coarse print grain, or an equivalent structure are immediately recognizable—not merely subtle film noise.

The remaining background regions stay relatively clean or retain only light texture, creating a clear **coarse–clean, dense–sparse** contrast. The grain field still preserves the original scene's broad contours, light–dark relationships, and spatial structure, while local details are collectively abstracted into the grain structure.

### Composition: zone by real content, not mechanical slicing

The background is first organized into 2–3 regions according to real scene elements, spatial depth, materials, and continuous structures—for example sky, water, rock, architecture, roads, vegetation, walls, or ground. Boundaries follow the content itself rather than mechanically splitting the image into “left / center / right” or “top / middle / bottom.”

A complete person, animal, building, mountain, vehicle, or object is never forcibly split merely to create a zoning effect. The main subject always takes priority: identity, silhouette, structure, proportions, pose, material qualities, and key recognizable details are preserved, with a clear contour line added along the true outer edge, pure white by default. A more suitable high-contrast outline color is used only when a large white background area would make the white contour ineffective.

### Coupled direction: color, grain region, copy, and format are decided together

Concepts 1–3 do not begin by fixing one shared aspect ratio and one shared grain region and then merely swapping colors. Each concept independently selects the **most suitable output ratio and core large-grain background region** according to its own color logic, light–dark structure, relationship to the subject, text breathing room, and visual center of gravity; copy is also arranged separately for each concept.

As a result, the three recolored concepts may differ simultaneously in color direction, grain-region selection, copy, and aspect ratio, but those differences must not be produced through random combinations. Every concept still needs an internally coherent, subject-centered optimum.

### Default four concepts

| Concept | Color direction | Grain region | Copy | Format / composition |
|---|---|---|---|---|
| **Concept 1** | Independent visual direction A, not constrained by the original background palette | Independently selected according to the current palette, subject, breathing room, and visual center | Follow user-supplied text; otherwise automatically match text to this concept | Independently select the most suitable aspect ratio for this concept |
| **Concept 2** | Clearly different from Concept 1 in warm–cool balance, value, saturation, overall hue, contrast, or narrative mood | Does not inherit Concept 1's grain region by default | May use a different text direction from Concept 1 | Does not inherit Concept 1's ratio by default |
| **Concept 3** | Switch to another visual lane again; near-identical recoloring is prohibited | Re-evaluate candidate regions for this concept | Re-match copy to this concept | Re-match format to this concept |
| **Concept 4** | **Preserve the original image's main palette** | Choose one complete grain region according to the original palette and composition | Follow the same factual constraints | **Preserve the original ratio, subject placement, and primary composition by default** |

All four concepts must keep the subject's identity and structure stable. Primary text should avoid high-density grain regions whenever possible. Facts such as location, date/time, camera gear, subject identity, event, weather, and credit must not be fabricated when they have not been supplied and cannot be reliably confirmed.

### Continuous generation: every new set branches out again

After all 4 concepts in a set have been generated and passed quality control, the Skill asks whether another set is needed. The user can simply reply “yes” to enter the next round immediately, or specify any combination of **color direction, grain region, copy, and format** for the next set.

Any item explicitly specified by the user becomes a hard constraint and must not be replaced in the name of “optimization.” Unspecified variables are re-optimized around the subject and the existing hard constraints. The 4 concepts in a new set must be clearly different from all earlier concepts in the current run; merely tweaking the same palette, slightly shifting the grain field, changing one line of copy, or making a tiny ratio adjustment is not enough. At the same time, each concept must still optimize the **color × grain region × copy × format × subject relationship** under the current constraints. Unless the user explicitly overrides its default rule, Concept 4 continues to preserve the original palette, original composition, and original ratio.

---
## Work Archive

The following examples show how Grain Fields combines content zoning, subject contours, zone-based color direction, and large-grain language within a single reconstruction.

### 01｜Coastal Amusement Park: the three-layer relationship of city / rides / waterfront

| Original | Grain Fields Reconstruction |
|---|---|
| ![Original coastal amusement park](assets/showcase/01-coast-amusement-original.png) | ![Grain Fields reconstruction of coastal amusement park](assets/showcase/01-coast-amusement-grain-fields.png) |

**Reconstruction approach:** Preserve the Ferris wheel, amusement facilities, and shoreline structure, while treating the urban building cluster as a large-area grain field. Keep the water relatively clean and use it as the text zone, allowing the dense urban grain to breathe against the open water. Light contours re-extract the main facilities from the high-density background.

### 02｜Intertidal Moment: the backlit relationship of water / reef / bird

| Original | Grain Fields Reconstruction |
|---|---|
| ![Original intertidal bird photograph](assets/showcase/02-tide-bird-original.png) | ![Grain Fields reconstruction of intertidal bird photograph](assets/showcase/02-tide-bird-grain-fields.png) |

**Reconstruction approach:** Treat the water, reef, and bird as three distinct visual roles while preserving the bird's pose and backlit outline. High-contrast zoning and coarse grain materials simplify the water and reef, transforming complex reflections into clearer color fields and texture rhythms.

### 03｜Bloom / Concrete: flowering branches and architectural skin

| Original | Grain Fields Reconstruction |
|---|---|
| ![Original cherry blossom and architecture photograph](assets/showcase/03-bloom-concrete-original.png) | ![Grain Fields reconstruction of cherry blossom and architecture photograph](assets/showcase/03-bloom-concrete-grain-fields.png) |

**Reconstruction approach:** Keep the flowering branch as a complete subject, preserving the pink blossoms, yellow-green leaves, and branch structure, then extract it with a white contour. Translate the building wall into a large-grain mineral / terrazzo-like field, while keeping the dark window openings relatively clean for minimal typography.

### 04｜One Point: large-dot reconstruction of an arena floor

| Original | Grain Fields Reconstruction |
|---|---|
| ![Original table-tennis match photograph](assets/showcase/04-table-tennis-original.png) | ![Grain Fields reconstruction of table-tennis match photograph](assets/showcase/04-table-tennis-grain-fields.png) |

**Reconstruction approach:** Keep the athlete and table in their original positions and actions, using contour lines to reinforce the competitive subject. Transform the large court area into a highly recognizable coarse-dot / oversized-halftone grain field, darken the spectator area, and use highly saturated accent colors on the advertising barriers so attention converges around the table.

### 05｜The Circle Widens: ripples become a grain field

| Original | Grain Fields Reconstruction |
|---|---|
| ![Original gull-on-water photograph](assets/showcase/05-gull-ripple-original.png) | ![Grain Fields reconstruction of gull-on-water photograph](assets/showcase/05-gull-ripple-grain-fields.png) |

**Reconstruction approach:** Keep the gull and its reflection clear. Select the complete water area around the ripples as the grain field, rebuilding the continuous water pattern into large crystalline / pebble-like units. Keep the surrounding water soft and clean so the grain field feels as though it naturally grows outward from the subject rather than being pasted onto the surface.

---
## Installation

### Codex

User-level Codex Skills are stored by default in `$CODEX_HOME/skills`, usually `~/.codex/skills`. Place the complete repository in that directory and make sure `SKILL.md` is located at the root of `grain-fields/`.

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

Restart Codex after installation so the Skill can be rediscovered. You can then invoke it with `$grain-fields`.

### Other platforms that support Agent Skills / `SKILL.md`

1. Download or clone the entire repository;
2. Keep the `grain-fields/` directory structure intact;
3. Place the directory in the platform's required Skills path, or use its GitHub / local Skill import function;
4. Ensure that both the root `SKILL.md` and `references/` can be read;
5. The host environment must provide usable image-generation / image-editing capabilities.

Do not copy only `SKILL.md`: scene analysis, transformation boundaries, art direction, generation compilation, and quality control are stored separately in `references/`.

---
## Usage Guide

The simplest invocation is:

```text
Use $grain-fields to reconstruct this image.
```

Default behavior:

- Automatically identify the main subject, key environmental elements, and scene relationships;
- Organize the background into 2–3 complete content-based regions;
- Generate 4 concept images directly without waiting for a second confirmation;
- Concepts 1–3 redesign color independently and separately choose the grain region, copy, and aspect ratio that best fit each visual direction;
- Concept 4 preserves the original image's main palette, composition, subject placement, ratio, and primary scene relationships;
- All four images must contain one large, clearly visible coarse-grain region;
- Add a clear contour along the true outer edge of the primary subject, pure white by default;
- If one image fails quality control, repair and regenerate only the failed concept;
- After one set is complete, ask whether another set should be generated.

### Optional user input template

All fields are optional. Fill in only what you actually want to control:

```text
【Title:】
【Subtitle:】
【Body:】
【Location:】
【Date / Time:】
【Camera:】
【Lens / Focal Length:】
【Exposure Settings:】
【Person / Subject Info:】
【Event / Theme:】
【Weather / Environment:】
【Photographer / Credit:】
```

Processing principles:

- Titles, subtitles, and body text supplied by the user retain their core meaning; only line breaks, size, placement, weight, and alignment may be adjusted for layout;
- Location, date/time, camera, lens, exposure settings, subject identity, event, weather, credit, and other factual fields must not be fabricated when they are not supplied and cannot be reliably confirmed;
- When the user supplies no text, each concept may independently choose the most suitable text type and automatically write copy according to its own palette, subject, background, story, and negative space;
- If the user explicitly requests no text, no text is added to any of the four images.

### How large-grain treatment is executed

The current Skill **does not maintain a separate preset library of named “large-grain materials.”** Instead, it defines inspectable structural standards for grain:

- It must cover one complete, continuous background content region;
- As a rule, it covers about 1/3–1/2 of the image, and may be larger when the content allows;
- Use coarse grain, large dots, large-scale halftone, coarse print grain, or an equivalent clearly visible structure;
- Individual grain units must be recognizable at normal viewing size;
- It must not collapse into fine noise, subtle film grain, or a transparent filter;
- The original region's broad contour, tonal structure, and spatial relationship must remain recognizable;
- Other regions stay relatively clean, establishing a coarse–clean, dense–sparse visual hierarchy.

If the user explicitly specifies a grain treatment, follow that request as long as it does not conflict with the core invariants.

---

### Generate another set

After one set of 4 images is complete, reply:

```text
yes
```

to generate the next set immediately without another confirmation. You can also specify some conditions for the next set at the same time, for example:

```text
yes, next set:
【Color: blue–orange high contrast】
【Grain region: sky】
【Copy: none】
【Format: 4:5】
```

Specified items are preserved as hard constraints. Unspecified items are re-optimized around the subject. The four concepts in the new set must be clearly different from all previous results in the current run.

---
## Complete Preset List

Preset content uses `references/03-art-direction.md` as its sole current data source. Presets help the AI route and branch out; they are not rigid templates and may not override subject preservation, content zoning, mandatory large-grain treatment, factual constraints, or Concept 4's original-image lock rules.

<details>
<summary><strong>Color Presets (click to expand)</strong></summary>

> For routing and variation only; preset names and descriptions are not final prompts.

#### Emotion / Atmosphere

| Color preset | Description |
|---|---|
| Violent Aesthetics | Highly saturated, strongly contrasting colors that emphasize danger, power, and impact |
| Sports Competition | Bright high contrast emphasizing speed, strength, and competitive tension |
| Hot-Blooded Youth | Strong contrast between red-orange warm tones and dark colors, full of drive |
| Cool Restraint | Cool neutrals dominate, creating a quiet, detached, rational mood |
| Dark Oppression | Deep black, charcoal, and heavy dark tones combine for visible pressure and force |
| Gentle Whisper | Soft low-saturation colors, quiet, delicate, and intimate |
| Solitary Narrative | Cool gray, dark blue, and small warm accents emphasize distance and inward emotion |
| Compassionate Documentary | Low-saturation warm grays and dark layers, restrained, weighty, and real |
| Glimmer of Hope | A restrained base with small bright warm highlights that emphasize points of light |
| Romantic Haze | Soft pink, misty purple, creamy white, and other gentle colors with strong atmosphere |
| Resolute Coldness | Cold black, steel gray, ice blue, and other hard colors with a decisive attitude |
| Calm Healing | Pale green, light blue, off-white, and other soothing tones, clean and gentle |
| Ethereal Silence | Light gray, cool white, pale cyan, and other negative-space colors, quiet and open |
| Solemn Ceremony | Deep red, deep blue, black-gray, and other weighty colors with ritual gravity |
| Mysterious Unknown | Black-purple, deep blue, and tiny bright accents, mysterious and restrained |
| Bright & Light | Clear, high-value colors with an upbeat, weightless quality |
| Sweet-Cool Contrast | Soft sweet colors placed against black, gray, and other dark tones |
| Primal Wildness | Earth brown, deep green, and charcoal, rough, raw, and full of life |
| Idealism | Bright neutrals with warm accents, clean and resolute |
| Emotional Release | High-purity clashing colors with strong subjectivity |
| Quiet Negative Space | Low-contrast neutrals and broad pale areas emphasizing calm and space |
| Suppressed Murmur | Low-value, low-saturation colors, emotionally heavy but restrained |
| Cheerful Optimism | Clear bright colors balanced with white, easy and positive |
| Sharp Rationality | Cool gray, black, pure white, and one bright accent, crisp and precise |
| Soft-Fog Emotion | Overall colors lightly misted, low in saturation but airy |

#### Era / Retro / Nostalgia

| Color preset | Description |
|---|---|
| Retro Poster | Warm aged tones with dark colors and a period-print feel |
| News Documentary | Black, white, and gray with one accent color, information-forward |
| Newspaper Print | Off-white, ink black, and limited spot colors with traditional publishing character |
| Archival Image | Yellowed tones, brown-gray, and ink black, evoking historical records |
| Old Photograph | Warm brown, gray-yellow, and faded tones, soft and nostalgic |
| Nostalgic Film | Gentle warm colors with slight cyan-green shadows and everyday film character |
| Hong Kong Film | Warm yellow, dark green, and dark red with rich urban period atmosphere |
| Hong Kong Night Cinema | Deep green, dark red, and tungsten yellow, highly dramatic |
| 1990s | Faded blue, aged red, and beige-yellow with everyday nostalgia |
| 1980s | Highly saturated red, blue, and yellow with dark tones, retro-pop energy |
| 1970s | Mustard yellow, olive green, burnt orange, and brown |
| 1960s Pop | Bold blocks of red, yellow, blue, and other clashing primaries |
| American Retro | Cream white, aged red, and deep blue with classic advertising and road-trip character |
| Soviet Propaganda | Red, off-white, and deep black, solemn and forceful |
| Old Shanghai | Dark green, dark red, beige-yellow, and golden brown, glamorous old-city atmosphere |
| Republican-Era Press | Beige-yellow, black-gray, and dark red with archival old-print character |
| VHS Tape | Low-definition blue-gray with purple/green shifts, simulating analog image distortion |
| Photocopier | High-contrast black, white, and gray with coarse grain, rough experimental publishing feel |
| Old Television | Low-purity colors with slight casts, simulating vintage television imagery |
| Polaroid | Soft warm tones with lightly faded highlights and instant-film character |
| Old Magazine | Off-white, dark red, dark green, and warm gray, evoking vintage magazines and ads |
| Old Movie Poster | Warm brown, dark red, aged yellow, and black with theatrical hand-printed character |
| Projector Film | Warm dark base with local highlights, evoking cinema projection and period atmosphere |
| Old Postcard | Cream yellow, faded blue, and light brown, like an old travel keepsake |
| Old Record Sleeve | Dark red, brown, aged black, and cream with nostalgic music character |
| Cassette Cover | Aged gray, muted color, off-white, and monochrome titling, evoking the cassette era |
| Old Brochure | Limited spot colors and paper-based tones with vintage commercial-promotion character |
| Vintage Package Printing | Faded primaries, off-white, and black linework with strong package-graphic character |

#### Sports / Competition

| Color preset | Description |
|---|---|
| Extreme Sports | Fluorescent brights colliding with a dark base, highly energetic and fast |
| Racing Livery | High-contrast main colors with black-and-white support, emphasizing speed |
| Football Pitch | Grass-derived colors combined with team-kit accents |
| Street Basketball | Warm orange, deep black, and court colors with urban sports character |
| Ice & Snow Competition | Ice blue, pure white, and deep blue, bright and cold |
| Outdoor Technical | Mountain natural tones with visible functional accents, reliable and exploratory |
| Expedition Documentary | Earth tones, military green, and warm gray, authentic and rugged |
| Esports Energy | Blue-violet, neon cyan, hot pink, and a black base |
| Fight Ring | Black, red, and white in strong conflict, highly confrontational |
| Fresh Marathon | Sky blue, white, bright orange, and other clean high-value colors |
| Strength Training | Iron black, steel gray, deep red, and other hard heavy tones |
| Sunny Surf | Ocean blue, white, warm yellow, and fluorescent accents |
| Skate Street | Concrete gray with jumping accent colors, casual and rough |
| Classic Boxing | Deep red, black, and cream with retro competitive character |
| Sneaker Trend | Bright colors against neutral bases, contemporary sports-fashion feel |
| Track & Field | Brick red, white, deep blue, or fluorescent accents emphasizing speed lines |
| Water Sports | High-purity blue-cyan and white, fresh and kinetic |
| Off-Road Rally | Dust/sand tones, black-gray, and warning brights, rough and mechanical |

#### Technology / Future / Digital

| Color preset | Description |
|---|---|
| Cyber Future | Cool dark base with blue-violet and cyan-green highlights |
| Digital Glitch | RGB-like displaced clashes with experimental electronic distortion |
| Future Silver Gray | Silver gray, cool white, and a small number of bright highlights |
| Tech Blue | Cool blue layered with gray-white, clean, rational, and precise |
| Deep Space | Deep blue-black, violet-gray, and cool bright accents |
| Acid Visual | Unconventional collisions of fluorescent green, purple, yellow, and more |
| Y2K Millennium | Silver gray, baby blue, hot pink, and other light-tech colors |
| Holographic Iridescence | Cool white, silver gray, and iridescent hues, futuristic and dreamlike |
| Interface System | Cool gray, deep blue, and cyan-green accents with control-console character |
| Data Visualization | White, gray, blue-green, and a small number of warning colors, logical and structured |
| Medical Clean | White, blue-white, and cyan, clean and precise |
| Laboratory Cold Light | Cool white, pale blue, and light gray, rational and sterile |
| Quantum Cool Purple | Blue-violet, silver gray, and black with abstract scientific character |
| Robotic Industrial | Steel gray, machine silver, and warning yellow, strongly mechanical |
| Thermal Imaging | Black-to-red-orange-yellow temperature-gradient character |
| X-Ray Blue | Cool blue, blue-black, and bright white, evoking scanning and translucency |
| Aerospace | White, deep blue, and red accents with technological order |
| Core Server Room | Cool dark base with blue-green indicators, precise and electronic |
| Electronic Chip | Deep green, black, silver gray, and small bright accents with circuit-board character |
| Metaverse | Blue-violet, cyan, and pink-violet with virtual-space character |
| AI Neural Network | Deep blue-black with cyan-violet node colors, abstract algorithmic feel |
| Terminal Green Screen | Black base with fluorescent green or cyan-green, retro computer-terminal feel |
| Radar Scan | Deep black-green with bright green linear accents, monitoring-system character |
| Industrial Warning Tech | Dark gray with warning yellow, orange, and red, combining technology and safety signage |

#### Urban / Industrial / Utility

| Color preset | Description |
|---|---|
| Street Trend | Black-gray base with highly saturated accent colors, free and rebellious |
| Punk Rock | Strong black-red, purple-black, and similar combinations, rough and defiant |
| Neon Night Ride | Deep dark backgrounds with neon highlights, urban nightlife atmosphere |
| Steam Machinery | Copper brown, iron gray, and coal black, industrial period character |
| Industrial Hardcore | Concrete gray, iron black, rust red, and other low-saturation heavy colors |
| Workwear Utility | Military green, sand, black, and gray, practical and hard-edged |
| Military Tactical | Olive green, earth yellow, and black-brown, restrained and serious |
| Architectural Minimal | Architectural neutrals with one accent color, emphasizing geometry and space |
| Architectural Avant-Garde | Strongly zoned color clashes emphasizing massing and lines |
| Urban Cool Gray | Steel gray, cool blue, and black, modern and detached |
| Urban Warm Night | Deep black, warm yellow, and dark red with nighttime storytelling character |
| City Neon | Blue-violet, magenta, and cyan highlights, prosperous and rain-soaked |
| Modern Metropolis | Black, white, and gray with a high-purity accent, fashionable and crisp |
| Premium Business | Deep blue, charcoal, and white, reliable and professional |
| Parking-Garage Cold Light | Cool gray, white light, and small warning accents, empty and mechanical |
| Concrete Architecture | Pale gray, concrete white, and iron black, emphasizing material mass |
| Verdigris Oxidation | Copper green, brown, and gray-black with aged industrial material character |
| Rusted Metal | Rust red, dark brown, and iron gray, worn and rough |
| Metro System | Gray, white, and route accent colors, orderly and fast |
| Nightclub City | Black base with bright purple-blue-pink, nightlife and music atmosphere |
| Dockside Warehousing | Cool gray, navy blue, and rust red, coastal heavy-industry character |
| Overpass Cool Gray | Steel gray, blue-gray, and cool white emphasizing urban structure |
| Construction Warning | Concrete gray with orange-yellow warning colors, construction and engineering feel |
| Airport Terminal | Silver gray, glass blue, white, and wayfinding brights, modern transportation character |

#### Nature / Landform / Material

| Color preset | Description |
|---|---|
| Natural Forest | Deep and light greens, earth brown, and off-white, natural and stable |
| Moss Forest | Moss green, deep brown, and gray-green, damp and quiet |
| Grassland Sky | Grass green, sky blue, and warm yellow, open and relaxed |
| Silent Snowfield | White, pale blue-gray, and deep gray, cold and quiet |
| Mountain Earth | Rock gray, earth brown, and vegetation green, weighty and natural |
| Rock & Mineral | Stone gray, rust, and sandy brown emphasizing geological materiality |
| Volcanic Lava | Black-gray, lava red, and burnt orange, primal and forceful |
| Aurora Iridescence | Deep blue-black with cyan-green and purple highlights, mysterious and dreamlike |
| Glacier Blue | Ice blue, cyan-white, and deep blue, pure and vast |
| Ocean Blue-Green | Deep blue, blue-green, and white, fresh and deep |
| Island Sunlight | Ocean blue, sand yellow, and bright white, open and cheerful |
| Desert Warmth | Sand yellow, ochre, and burnt orange, dry and expansive |
| Wild West | Sand brown, dark red, and denim blue, rugged road-movie character |
| Danxia Red Earth | Ochre red, orange-brown, and sand yellow, strongly geological |
| Coral Coast | Coral pink, ocean blue, and sand white, bright seaside feel |
| Wetland Waterfront | Gray-green, blue-gray, and mud brown, calm ecological atmosphere |
| Stream-Valley Bluestone | Stone blue, gray-green, and moist pale white, cool and delicate |
| Salt-Alkali White | White-gray, pale blue, and earth yellow, open and silent |
| Dense Rainforest | Deep green, ink green, and dark brown, dense and humid |
| Thin-Air Plateau | Pale blue, gray-brown, and cool white, transparent and spacious |
| Hard Island Reef | Rock gray, ocean blue, and cool white, hard and crisp |
| Terracotta Mineral | Terracotta red, warm brown, and mineral gray, earthy and handcrafted |
| Jade Veins | Cyan-white, gray-green, and stone gray, warm and mineral-like |
| Desert Mineral Gray | Gray-brown, sand white, and rust accents, austere terrain feel |
| Mist-Blue Lake | Mist blue, gray-white, and deep blue, calm water atmosphere |
| Black-Sand Coast | Black-gray, cool blue, and pale white with strong material contrast |

#### Art / Print / Graphics

| Color preset | Description |
|---|---|
| Screen Printing | A few high-purity color zones with clear blocks and strong grain |
| Woodcut Print | Black and off-white with a few heavy colors, rough and handmade |
| Pop Art | Highly saturated primaries and strong clashes, exaggerated and graphic |
| Comic Printing | High-purity colors, black outlines, and halftone dots, direct and eye-catching |
| Editorial Magazine | Restrained base with precise accents, modern editorial design feel |
| Registration Printing | Simulated separated-color overprinting with clear color relationships |
| Halftone Overprint | Zoned color combined with visible dots and print grain |
| Reduced-Color Print | A few large color fields with black-white structure, simple and forceful |
| Color Cut-and-Paste | Regions feel re-cut and reassembled, with independent but coordinated colors |
| Iconic Graphics | Flatter, more explicit color, emphasizing symbol recognition |
| Artistic Smear | Overall color relationships with hand-applied cover and overlap |
| Spray Graffiti | Jumping accents, spray-paint character, and irregular edges |
| Poster Color Collision | Clearly separated regional color fields with strong graphic expression |
| Promotional Layout | Color serves information hierarchy and reading order |
| Paper Collage | Colors feel assembled from different paper stocks |
| Dirty Ink | Dirty plate, ink bleed, and registration-shift character |
| Two-Color Printing | Build hierarchy with only two main colors, concise and impactful |
| Three-Color Composition | Control three core colors for clear visual order |
| Risograph Printing | Limited bright inks, registration shifts, grain, and handmade publishing character |
| Two-Color Screen Print | Two-color registration combined with coarse halftone, strong graphic impact |
| Newspaper Black + Red | Black-gray primary image with one red accent, newspaper-print character |
| Four-Color Comic | CMYK-like high-purity separation with exaggerated print character |
| Papercut Color Blocks | Large color fields with clear boundaries, emphasizing flat composition |
| Paper Dye | Overall color derived from paper base plus local dyeing, materially unified |

#### Fashion / Editorial / Premium

| Color preset | Description |
|---|---|
| Fashion Editorial | Sophisticated neutrals with one strong color, emphasizing subject styling |
| Sophisticated Gray | Layered low-saturation gray, greige, blue-gray, and similar tones |
| Black & White Minimal | Strong black-white relationship emphasizing structure, contour, and negative space |
| Off-White Minimal | Warm white, beige, and light gray, soft and quiet |
| Cool Minimal | Cool white, silver gray, and pale blue-gray, rational and modern |
| Dark Minimal | Black, charcoal, and a small bright accent, cold and powerful |
| Nordic Cool | White, gray-blue, and light wood tones, fresh and natural |
| Japanese Clear | Milky white, pale blue, and light green, airy and transparent |
| Korean Cream | Milky white, cream yellow, pale pink, and light brown, soft and clean |
| French Retro | Cream, burgundy, and dark green, romantic and restrained |
| Italian Richness | Deep red, olive green, and warm yellow, mature and full |
| British Classic | Burgundy, dark green, navy, and beige, traditional and steady |
| German Rational | Black, white, and gray with red or blue, highly ordered and functionalist |
| Swiss Design | Red-black-white or pure color blocks, rational and geometric |
| Bauhaus | Red, yellow, and blue with black and white, structurally clear |
| Memphis | Pink, blue, yellow, and green accent clashes, playful and geometric |
| Cream Retro | Cream yellow, pale orange, off-white, and soft brown, warm and gentle |
| Commercial Display | Clean, ordered colors serving subject presentation |
| Perfume Advertising | Black-white-gray or warm-white base with a premium accent |
| Jewelry Luxury | Dark base with bright gold and jewel tones, focused on luxury |
| Art-Book Collection | Neutrals with low-saturation accents, art-catalog character |
| Black-Gold Luxury | Large black base with gold accents |
| White-Gold Luxury | Warm white, ivory, and gold, bright and refined |
| Gemstone Luxury | Emerald green, sapphire blue, burgundy, and gold |
| Royal Blue & Gold | Deep blue with gold, solemn and elegant |
| Burgundy Red | Deep wine red, black-brown, and cream, mature and weighty |
| Midnight Blue | Deep blue, gray-black, and cool white, calm and restrained |
| Mother of Pearl | Milky white, light gray, pale pink, and cool blue, soft luminous luxury |

#### Youth / Lightness / Fantasy

| Color preset | Description |
|---|---|
| Dopamine Youth | High-value, highly saturated clashes, lively, happy, and young |
| Candy Sweet-Cool | Candy brights with black-gray, balancing sweetness and edge |
| Girlish Pastel | Pink, lavender, and pale blue, soft and dreamy |
| Macaron | Low-saturation pale multicolor combination, light and sweet |
| Cotton Candy | Soft pink-blue-purple gradation with airy dream character |
| Dreamcore | Unreal soft pink, pale blue, aged yellow, and similar tones |
| Weirdcore | Inharmonious bright and dark colors together, strange and surreal |
| Surreal Dream | Unnatural color combinations, mysterious and floating |
| Fairy-Tale Fantasy | Soft high-value colors, gentle and dreamlike |
| Enchanted Forest | Deep green, blue-green, purple, and small bright accents |
| Fantasy Epic | Heavy deep blue, dark red, gold, and similar colors |
| Mysticism | Black-purple, deep blue, and dark gold with ritual character |
| Gothic Dark | Black, deep red, and dark purple, solemn and gloomy |
| Vampire Red | Deep black, blood red, and cool white, dangerous and ornate |
| Fairy Fluorescence | Light overall palette with fluorescent accents |
| Wandering Amusement Park | Highly colorful multicolor combinations, playful and joyful |
| Childhood Picture Book | Soft but clear colors, simple and warm |
| Milky Cloud | Milky white, pale blue, and light pink, soft and pressure-free |
| Plastic Toy | High-value pure-color combinations, direct and childlike |
| Jelly Transparency | Light bright colors with highlight white, clear and translucent |
| Comic Youth | Bright yellow, sky blue, pink, and other pure colors, young and active |

#### Eastern / Traditional / Cultural

| Color preset | Description |
|---|---|
| Eastern Cinnabar | Cinnabar red, ink black, and off-white, traditional and powerful |
| Eastern Blue-Green | Mineral blue, mineral green, and off-white, classical and elegant |
| Ink Black & White | Ink black with gray-white layers, emphasizing negative space and rhythm |
| Colored Ink | Ink as the structural base with a small amount of traditional color |
| Dunhuang Mural | Earth red, mineral blue, mineral green, and ochre yellow, ancient and weighty |
| Song-Dynasty Elegance | Moon white, dark teal, tea brown, and beige, subtle and refined |
| Tang Rich Color | Cinnabar red, blue-green, and gold yellow, rich and solemn |
| New Chinese | Ink black and off-white with cinnabar or blue-green, balancing tradition and modernity |
| Blue-and-White Porcelain | Blue and porcelain white, elegant and concise |
| Jade Cyan-White | Cyan-white, gray-green, and pale beige, warm and Eastern |
| Vermilion Architecture | Cinnabar red, dark tile gray, and beige-yellow, strongly identifiable traditional architecture |
| Zen Neutrals | Off-white, light gray, wood tones, and ink, quiet with negative space |
| Guochao Neon | Traditional saturated red-blue-green combined with modern neon |
| Opera Brilliance | Bright red, royal blue, gold, and black, theatrical and decorative |
| Tea-Room Wood | Tea brown, warm wood, gray-white, and ink, quiet and restrained |
| Old Scholarly Paper | Aged xuan-paper tone, ink black, and pale brown, handmade book-paper feel |
| Lacquer Black & Red | Deep black, cinnabar red, and a little gold, concise and solemn |
| Porcelain Glaze Cyan-White | Cyan-white, gray-blue, and warm beige, clear and restrained |
| Miao Embroidery High Color | High-purity red-blue-green-yellow contrasts with folk decorative character |
| Tibetan Mineral Color | Cinnabar, Tibetan blue, earth yellow, and mineral green, weighty religious-art character |

#### Method / Zoning / Color Preservation

| Color preset | Description |
|---|---|
| Local Gray Focus | Divide background into 2–3 regions; turn one whole region gray while retaining and refining the original colors, texture, saturation, and contrast elsewhere |
| Gray–Color Contrast | Compress one part into black-white-gray while preserving and intensifying color in another |
| Single-Region Desaturation | Fully desaturate or strongly reduce saturation in one complete background region while intensifying the others |
| Local Cooling | Shift one region to cool gray or a cool desaturated tone while refining the original colors elsewhere |
| Local Warm Compression | Shift one region to warm gray, brown-gray, or muted warmth while intensifying color elsewhere |
| Main-Region Fade | Fade and age one large region while making the others more vivid |
| Color–Gray Narrative | Let the gray region carry mood while the colored region carries the information focus |
| Local Mute | Lower saturation and contrast in one region while increasing clarity and material quality elsewhere |
| Focus Color Retention | Neutralize most regions while retaining one vivid colored zone |
| Dual-Region Temperature Split | Give two main regions clearly different warm–cool relationships |
| Three-Stage Progression | Gradually shift value or saturation across 2–3 regions |
| Monochromatic Layering | Separate regions through value, chroma, and material differences within one hue family |
| Complementary Collision | Use complementary colors in two regions with a third region acting as a neutralizer |
| Analogous Transition | Use neighboring hues across regions for a harmonious, smooth overall relation |
| High-Contrast Zoning | Create strong regional separation in both lightness and hue |
| Low-Saturation Zoning | Keep all regions muted and build hierarchy through subtle color differences |
| Warm Field, Cool Accent | Keep the image broadly warm while shifting one region to cool color or cool gray |
| Cool Field, Warm Accent | Keep the image broadly cool while shifting one region to warm color or warm gray |
| Light–Shadow Color Split | Differentiate color by lit, backlit, and shadow content layers |
| Material-Based Color Split | Assign colors according to material content such as sky, rock, vegetation, architecture, and ground |
| Spatial Color Split | Vary purity or temperature according to real foreground, midground, and background layers |
| Emotional Reversal | Give the area around the subject and distant regions opposing emotional color logic |
| Documentary De-Saturation | Preserve the original overall color relationship while reducing vividness in selected regions |
| Cinematic Zoning | Assign atmospheric color to content regions according to narrative function |
| Advertising Zoning | Use clear colors, clear zoning, and strong contrast to strengthen subject information |
| Magazine Zoning | Regional color serves layout and readability |
| Exhibition Zoning | Different regions carry different informational roles with restrained order |
| Aged-Paper Color Split | Create regional color differences from an aged-paper print palette |
| Gray Base, Color Pop | Keep most regions gray while allowing only selected regions to remain highly colorful |
| Mist-Based Color Split | Soften and gray one region while keeping another clear and vivid |
| Dramatic Stage | Let content regions take on different color roles like theatrical lighting |
| Narrative Acts | Different content regions behave like chapters with distinct emotional roles |
| Natural Neutral | Preserve original natural color while locally adjusting contrast, chroma, and value |
| Restrained Enhancement | Avoid major hue changes; enhance saturation, contrast, and clarity region by region |
| Original-Color Enhancement | Preserve the original overall palette as much as possible while improving hierarchy and transparency |
| Single-Region Grain Emphasis | Choose one complete large region for strong grain while keeping the rest clean |
| Chroma-Imbalance Reconstruction | Deliberately widen saturation differences between regions to create visual rhythm |
| Single-Region Inverse Accent | Give one complete region an opposing color tendency while keeping the others coordinated |
| B&W Subject, Color Background | Keep the subject black-and-white or low-color while strengthening color in zoned background regions; subject must remain recognizable |
| Color Subject, Gray Background | Preserve the subject's main colors while neutralizing and layering the background |
| Original Gamut Compression | Keep the overall original hue identity but compress it into a more limited gamut and clearer hierarchy |
| Original Gamut Expansion | Preserve the original color logic while moderately increasing color separation and depth without changing its palette identity |

#### Travel / Life / Food / Commercial

| Color preset | Description |
|---|---|
| Fresh Travel | Sky blue, pale green, and warm white, bright and clean |
| Urban Travel | Architectural gray and sky blue with visible accents, modern documentary feel |
| Road Trip | Sky blue, sand, and aged red, open and free |
| Humanistic Travel | Warm gray, earth yellow, and deep red with local everyday character |
| Pastoral Nature | Wheat yellow, grass green, and pale blue, gentle and lived-in |
| Caramel Warm Brown | Caramel, brown, and cream, warm and rich |
| Coffee Cinema | Coffee brown, black-brown, and warm beige with steady storytelling character |
| Amber Glow | Amber yellow, warm brown, and deep orange, rich and warm |
| Appetizing Warmth | Red-orange-yellow warm palette, rich and energetic |
| Fresh Food | Cyan-green, white, and pale yellow, clean and fresh |
| Coffee & Baking | Brown, cream, and caramel, mellow and everyday |
| Milk-Tea Shop Poster | Milk brown, pale yellow, and off-white, gentle and friendly |
| Convenience-Store Packaging | Bright main colors on white with a few support colors, direct and everyday |
| Tropical Promotional Art | Bright green, hot pink, vivid yellow, and ocean blue, exuberant and decorative |
| Beer & Malt | Golden yellow, brown, and milky white, warm and full |
| Tavern Barrel | Deep brown, burgundy, and dim yellow, mature and slightly tipsy |
| Vintage Tobacco Box | Earth yellow, dark green, and brown, old commercial-packaging character |
| Jewelry Window | Dark base with bright jewel tones, refined and focused |
| Cosmetics Poster | Soft neutral haze with small high-chroma accents, fashionable and refined |
| Product Technology | Cool gray and blue-white with bright accents, precise and clean |
| Product Trend | High-purity clashing background colors reinforcing object contour and youthfulness |
| Product Luxury | Dark background with metallic colors emphasizing premium material quality |

#### Film / Stage / Music

| Color preset | Description |
|---|---|
| Film Trailer | Deep dark palette with one bright accent, narrative suspense |
| Road Movie | Warm sand, aged blue, and sunset orange, free and story-driven |
| Art-House Film | Low-saturation palette, soft and understated |
| Suspense Film | Cool green, blue-black, and dark yellow, tense and uncertain |
| Crime Film | Black-gray, dark red, and cool white, dangerous high contrast |
| Romance Film | Soft pink, warm red, and cream, romantic and intimate |
| Youth Film | Bright blue-green, warm yellow, and white, light and lively |
| Epic Film | Deep heavy colors with gold or red accents, grand and solemn |
| Disaster Film | Gray-black, burnt orange, and warning red, urgent and destructive |
| Stage Lighting | Black base with strong red-blue-purple light, theatrical performance feel |
| Music Festival | Highly saturated multicolor clashes, hot, free, and rhythmic |
| Jazz Night | Black, burgundy, dark gold, and smoky blue, mature musical atmosphere |
| Ballet Stage | Dusty pink, milky white, and smoky purple, light and elegant |
| Rock Live | Black, red, purple, and stage-white light, high energy |
| Electronic Music | Black base with bright blue-violet-cyan, electronic rhythm and nightlife feel |
| Theater Red Curtain | Deep red, black, and gold, classic theatrical ceremony |

</details>

<details>
<summary><strong>Text Presets (click to expand)</strong></summary>

> Before choosing a text type, first check which factual fields are available. Presets that require specific locations, dates/times, equipment, identities, or other facts may use only information actually supplied by the user or reliably confirmed.

#### Documentary / Information

| Name | Description |
|---|---|
| News Headline | Summarize the image's core event or content in one information-dense headline |
| Newspaper Lead | Follow the headline with an ultra-brief factual lead identifying people, place, and event |
| Image Caption | Explain what is happening in the image like a news-photo caption |
| Photojournalism Caption | Emphasize time, place, people, event, and the shooting scene |
| Documentary Photography Note | Describe the relationship between subject and scene in restrained, objective language |
| Archival Record | Build archival-feeling copy from identifiers, time, place, subject, and similar fields |
| Event Record | Briefly describe the background and on-site state of a specific event |
| On-Site Record | Emphasize immediacy and the sense of being here and now |
| Time & Place Record | Center date, time, and location while keeping other information minimal |
| Person Identity Intro | Briefly state a person's name, identity, title, or role |
| Subject Encyclopedia | Introduce a building, animal, object, or other subject with a one-sentence definition plus minimal explanation |
| Architecture Info Card | Information-led layout using building name, location, era, designer, use, and similar data |
| Landscape Info Card | Minimal introduction using landscape name, location, landform, or environmental characteristics |
| Animal Observation Record | Natural-observation information such as species, place, time, and behavior |
| Plant Observation Record | Concise record of plant name, location, and morphological features |
| Object Archive | Museum-style information such as name, era, material, and use |
| Vehicle Archive | Mechanical archive using model, year, location, parameters, and similar fields |
| Photography Work Info | Standard artwork information such as title, location, year, and photographer |
| Photography Info Card | Location, time, camera, lens, focal length, aperture, shutter, ISO, and other shooting parameters |
| EXIF Parameters | Make shooting parameters the primary text content and emphasize photographic properties |
| Film Photography Info | Film stock, camera body, lens, development/scanning method, and similar film-photography information |
| Aerial Photography Info | Aerial record using location, altitude, equipment, time, and related fields |
| Latitude–Longitude Coordinates | Use coordinates, elevation, and location as the core information |
| Geospatial Coordinate Archive | Combine coordinates, administrative area, elevation, orientation, and other geographic information |
| Weather Record | Use temperature, weather, wind speed, humidity, and similar environmental data to support the image |
| Travel Log | Build a travel record from date, location, route, and an ultra-brief impression |
| Itinerary Node | Describe the image as one node along a travel route |
| Numbered Archive | Use a number, numbered title, and short note to reinforce collection or survey character |
| Chronological Record | Make a year or date the visual core and add one or two factual sentences |
| Timeline Node | Treat the image as a key node on a timeline |
| Specimen Label | List name, location, date, and identifier like an academic specimen label |
| Museum Label | Minimal museum-style information: work name, era, material, author, collection |
| Exhibit Label | A title plus one very short explanation, like an exhibition wall label |
| Document Index | Index-style information such as document number, title, location, and date |
| Survey Record | Rational copy using survey object, time, location, and observational conclusion |
| Site Investigation Record | Field-investigation description for engineering, architecture, landforms, and similar subjects |
| Research Sampling | Scientific-record language using sample number, location, date, conditions, and related fields |
| Sports Event Info | Event name, matchup, time, place, score, athlete information, and similar data |
| Performance Info | Performance name, artist, venue, date, and related event-archive information |
| Activity Info | Standard information such as activity name, location, time, and participants |
| Meeting Record | Formal information such as meeting title, date, place, and attendees |
| Work Documentary | Project name, personnel, location, time, and work status |
| Engineering Record | Project name, milestone, location, date, and other project-record language |
| Construction Milestone | Construction stage, time, location, process, and other field information |
| Experiment Record | Experiment name, identifier, conditions, date, and other laboratory-archive text |

#### Keepsake / Check-In / Commemoration

| Name | Description |
|---|---|
| Minimal Check-In | Location and date plus one extremely short record, clean and direct |
| City Check-In | City name, landmark, date, and a short travel line |
| Attraction Check-In | Attraction name, time, location, and one relaxed observation |
| Landmark Commemoration | Use the landmark name as a large title with date and location |
| Photography Check-In | Place shooting parameters beside location and date, emphasizing the photographic record |
| Film Check-In | Film stock, camera body, location, and date form a nostalgic record |
| Travel Keepsake Photo | Location, time, companions, and one simple commemorative line |
| Been Here | Minimal place name plus date with a relaxed travel feel |
| Arrived Today | Center the moment of arriving somewhere and highlight the journey node |
| Passing Through | More casual, light travel-record tone |
| Present in This Moment | Emphasize the instant when person and place coexist |
| City Coordinates | Combine city name, coordinates, date, and a short line |
| Map-Coordinate Check-In | Coordinates plus place name and one travel sentence |
| Flight Travel | City codes, date, and flight-like numbering form a travel visual |
| Ticket Keepsake | Departure, destination, date, and train-ticket-style information |
| Mountain Climb Commemoration | Mountain name, elevation, date, route, or summit information |
| Seaside Check-In | Coastal location, date, and a short relaxed line |
| Road Check-In | Road name, mileage, coordinates, and date form journey-like copy |
| Ancient-Town Check-In | Ancient-town name, date, and one locally flavored short line |
| Campus Check-In | School name, year, place, and youth-memory text |
| Graduation Keepsake | School, class, year, and graduation message |
| Classmate Group Keepsake | Class, place, date, and collective commemorative note |
| Official Group-Photo Introduction | Formal group-photo data such as organization, activity, title, time, and place |
| Organization Group Keepsake | Organization name, activity name, date, and location |
| Team Keepsake Photo | Team name, project, date, and short commemorative line |
| Family Group Keepsake | Family members, time, place, and a gentle commemorative line |
| Friends Group Keepsake | Place, date, and an easy friendship line |
| Couple Travel Keepsake | Place, date, and restrained romantic wording |
| Anniversary | Anniversary number, date, and brief retrospective text |
| Birthday Commemoration | Age, date, and light or gentle birthday text |
| First Meeting | Place and date plus one line recording a first encounter |
| Reunion | Time, place, and a short expression of meeting again after separation |
| Return to a Familiar Place | Place and year with a slight past-vs-present contrast |
| Return to Alma Mater | School name, year, and revisit-style wording |
| Hometown Record | Place name, date, and a short hometown-emotion line |
| Homeward Record | Place, date, and concise wording centered on returning |

#### Person Feature / Portrait

| Name | Description |
|---|---|
| Person Name as Main Title | Center the person's name, with a subtitle explaining identity or story |
| Biographical | Name, year, and one sentence summarizing experience or character |
| Person Archive | Archival introduction using name, identity, location, date, and related fields |
| Person Interview | Magazine-interview-cover style emphasizing name and one viewpoint |
| Person Close-Up | Focus on one state or trait of the person and describe it with a minimal title |
| Person Story | Use one or two short sentences to imply the person's experience and situation |
| Person Quote | Use one representative self-statement or viewpoint as the main text |
| Person Manifesto | Use a short, strong first-person sentence to reinforce personality |
| Person Tags | Summarize identity, character, or role with a few keywords |
| Person Keywords | Name plus 3–5 short keywords for an editorial feel |
| Occupational Portrait | Occupation, name, workplace, and brief description |
| Worker Portrait | Plain language highlighting occupation, action, and the working scene |
| Youth Portrait | Name, age or state, plus a short youthful expression |
| Elder Portrait | Restrained text centered on years, experience, identity, and similar themes |
| Child Portrait | Simple, light, and childlike; avoid piling on adult-style expression |
| Women Feature | Use restrained, powerful, or gentle feature language according to the subject's character |
| Men Feature | Emphasize strength, stillness, or story according to the subject's state |
| Athlete Feature | Combine name, discipline, result, or competitive keywords |
| Artist Feature | Name, creative field, and one artistic viewpoint |
| Musician Feature | Name, work, or one lyric-like short line |
| Photographer Feature | Name, place, equipment, or photographic philosophy |
| Craftsperson Feature | Name, craft, place, and one line about the continuation of skill |
| Scholar Feature | Name, field, institution, and one viewpoint |
| Historical Figure Feature | Name, period, identity, and concise historical context |
| Anonymous-Person Documentary | Do not emphasize the name; center one person and one way of life |
| Group Portrait Feature | Summarize multiple subjects through shared identity, place, or event |
| Generational Group Portrait | Emphasize shared experience and historical context within one generation |
| City Person | Feature copy centered on the relationship between a person and a city |
| Hometown Person | Balance local identity, living state, and regional character |
| Strangers Series | Number, place, date, and extremely short observational text |

#### Literary / Poetic

| Name | Description |
|---|---|
| Classical Poetry Quote | Select a classical Chinese poetry line highly aligned with the image's mood |
| Classical Poetic Mood | Describe the scene in classical poetic language without directly quoting a famous line |
| Modern Poem Line | Express image mood and space in an extremely short modern-poetry line |
| Free Verse | Use line breaks, pauses, and negative space to create a modern literary feel |
| Prose Line | Add one or two image-rich prose sentences to extend the narrative |
| Literary Voice-Over | Extend the story behind the image like a novel or film voice-over |
| Novel Opening | Use one opening sentence with suspense or story energy |
| Novel Ending | Write like the final sentence after a story ends, with aftertaste and openness |
| Diary Fragment | Date plus a first-person short line, private and authentic |
| Notebook Note | More restrained than a diary, like a travel, observation, or everyday notebook |
| Letter Fragment | Use a line addressed to someone or taken from a letter-like voice to heighten emotion |
| Unsent Letter | First-person text with regret, restraint, and incompleteness |
| Postcard Literature | Place plus one line that could be written on the back of a postcard |
| Poetic Place Name | Use the place as an emotional entrance into extremely concise local literature |
| Landscape Prose | Concise literary description around mountains, coastlines, or cities |
| Mountain & River Literature | Build grand or quiet text from mountains, rivers, clouds, wind, and other natural elements |
| Coast Literature | Short lines around sea, tide, wind, and distance |
| City Literature | Urban emotion centered on streets, lights, buildings, and crowds |
| Road Literature | Roads, distance, speed, departure, and freedom as the core |
| Railway Literature | Stations, tracks, distant travel, farewell, and arrival as central imagery |
| Rainy-Day Literature | Rain, windows, streets, and sound form quiet or melancholic text |
| Literature of Wind | Use wind as the invisible narrative thread in the image |
| Light-and-Shadow Literature | Abstract expression around light, shadow, and space |
| Still-Life Literature | Expand from one object into memory, people, or everyday associations |
| Plant Literature | Express vitality through plant growth and form |
| Animal Literature | Use animal behavior to reflect freedom, solitude, companionship, and similar themes |
| Architectural Literature | Write the relationship between buildings and people through space, walls, windows, and traces of age |
| Ancient-Town Literature | Local literature centered on alleys, eaves, bluestone, waterways, and older ways of life |
| Jiangnan Literature | Soft, understated language around water lanes, rain, bridges, white walls, and dark roof tiles |
| Northern Literature | Heavier, plainer writing around wind, land, long roads, and old cities |
| Western Literature | Wilderness, highways, mountains, solitude, and distance |
| Island Literature | Islands, sea wind, tides, and distance form a lightly solitary voice |
| Hometown Literature | Hometown, old objects, relatives, roads, and memory as the core |
| Rural Literature | Plain narrative of land, villages, labor, and local life |
| Everyday Human Warmth | Food, lanes, lights, and human relationships express everyday warmth |
| Traces of Time | Write the marks left by time through old objects, buildings, or human states |
| Impermanence | Restrained writing about change, departure, and what cannot be repeated |
| Encounter Literature | Center meetings, chance, and brief intersections |
| Farewell Literature | Center parting, departure, and the final meeting |
| Reunion Literature | Emphasize the complex emotion of meeting again after time has passed |
| Waiting Literature | Develop around staying, waiting, lateness, and the unknown |
| Distant-Places Literature | Use distance to express longing, drifting, and uncertainty |
| Drifting Literature | Short lines about unfamiliar cities, travel, and lack of belonging |
| Homecoming Literature | Express emotion through returning home, old roads, and familiar scenery |
| Memory Fragments | Use fragmentary syntax to express hazy, broken memory |
| Dream Voice-Over | Hazy, non-logical text between reality and dream |
| Stream-of-Consciousness Line | Prioritize sensations and associations over complete narrative |
| Minimal Philosophy | Use an extremely short line to raise thoughts about life, existence, and similar themes |
| Existentialism | Develop around solitude, choice, freedom, meaning, and related themes |
| Reflection on Life | Draw a short line about growth, aging, or life from the subject's condition |
| Philosophy of Time | Center past, present, moment, and passing |
| Philosophy of Space | Express through distance, boundaries, inside/outside, near/far, and other spatial relations |

#### Youth / Emotion

| Name | Description |
|---|---|
| Youthful Pain | Restrained description of growing up, missing chances, regret, and unspoken emotion |
| Youth Film | Like subtitles or voice-over from a youth film, light with a touch of nostalgia |
| Youth Diary | Date, place, and everyday fragments in a young voice |
| Boyish Spirit | Short and direct, with momentum and a sense of the future |
| Girlish Sensibility | Light and delicate with a little romance and private emotion |
| Campus Youth | Campus-memory feel from playgrounds, classrooms, uniforms, and after-school time |
| Graduation Season | Farewell, future, classmates, and the last collective memory |
| Summer Boy | Sunlight, running, sweat, wind, and freedom |
| Hot-Blooded Youth | More slogan-like, emphasizing impulse, dreams, and action |
| Youthful Confusion | Lightly melancholic writing between future and uncertainty |
| Youthful Regret | Short expression about what was unsaid, unfinished, or missed |
| Secret Crush | Private, restrained emotion that does not directly confess love |
| First-Love Feeling | Green, gentle, concise, and never overdramatic |
| Breakup Monologue | Restrained first-person loss and self-dialogue |
| Young Person Leaves Home | Growth, distant travel, and the first real departure |
| Youth Ensemble | Shared memories, places, and era of a group |
| Youth Friendship | Emphasize experiences shared together rather than sentimentality |
| Youth Manifesto | Short and confident with slight rebellion |
| Youth Rebellion | More direct, aggressive, and noncompliant |
| Youth Freedom | Images of wind, running, distance, roads, and freedom |
| Reckless Youth | Slightly exaggerated, self-assured youthful tone |
| Unfinished Youth | Use incompleteness to imply an open ending and continued movement |
| Growing Pains | Begin from change, loss, and maturing |
| Before Adulthood | The threshold state between youth and adulthood |
| Literature of Twenty | Youth, confusion, freedom, desire, and future coexist |
| Midsummer Memory | Bright imagery paired with light nostalgia |
| After School | Relaxed everyday campus life with a short-film feel |

#### Love / Relationships

| Name | Description |
|---|---|
| Minimal Love | Express a relationship in one sentence without excessive ornament |
| Romance-Film Voice-Over | Restrained description of two people like a film subtitle |
| Short Love Letter | Direct but concise private expression |
| Secret-Crush Voice-Over | Show emotion through distance and details without saying “love” directly |
| First-Meeting Keepsake | Develop around the first meeting and the scene at that time |
| Everyday Love | Express intimacy through ordinary life details |
| Couple Check-In | Location, date, and brief relationship text |
| Long Companionship | Focus on time and companionship rather than romance itself |
| Long-Distance Relationship | Distance, cities, stations, waiting, and related keywords |
| Reunion Love | Complex feeling of meeting again after time |
| Farewell Love | Restrained expression where love remains but the relationship ends |
| Regretful Love | Missed chances, incompletion, and memory |
| Wedding-Vow Style | Names, date, and a minimal promise |
| Wedding-Commemoration Style | Location, date, names, and one commemorative sentence |
| Anniversary Style | Number of years, date, and a short relationship retrospective |
| Love in Old Age | Time, companionship, and shared life as the core |
| Family Affection | Center companionship, daily life, and family relationships |
| Father–Son Relationship | Restrained writing about growth, inheritance, and distance |
| Mother–Daughter Relationship | Delicate, everyday intergenerational expression |
| Brotherhood | Shared experience, standing side by side, and long-term bonds |
| Friendship | Easy and authentic without forced sentimentality |

#### Travel / Local Culture

| Name | Description |
|---|---|
| City Card | City name plus one highly representative local description |
| City Impression | Distill the city's character from light, streets, crowds, or architecture |
| Local Gazette | Concise local record using place name, history, and geographic information |
| Local Humanism | Enter local character through residents, streets, and ways of life |
| Local Customs | Balance local life, customs, and environmental information |
| Regional Culture | Emphasize distinctive cultural symbols and historical background |
| Ancient-City Journey | Combine city walls, streets, history, and travel feeling |
| Ancient-Town Journey | Travelogue copy around old streets, waterways, architecture, and everyday scenes |
| Street-Lane Observation | Write urban details through one street or one corner |
| Old-City Memory | Center old buildings, old shops, and urban change |
| New-City Observation | Modern buildings, roads, and a sense of urban renewal |
| Small-Town Story | Gentle everyday local text with lived-in atmosphere |
| Village Record | Village name, environment, residents, and living conditions |
| Fishing-Village Notes | Coastline, fishing boats, residents, and working life |
| Mountain-Village Notes | Mountains, village, roads, and living state |
| Border Travel | Place name, distance, boundary, and a sense of the faraway |
| Island Travel | Sea wind, island, transport, and the feeling of staying |
| Road Travel | Place, mileage, direction, and short journey lines |
| Railway Travel | Station, train, destination, and feeling of being en route |
| Hiking Record | Route, elevation, distance, and a brief impression |
| Mountain Log | Mountain name, elevation, date, and status record |
| Cycling Log | Route, kilometers, place, and simple feeling |
| Road-Trip Log | Route, location, and arrival information |
| City Walk | Neighborhood, time, weather, and easy observation |
| Night City Walk | Night view, streets, lights, and walking atmosphere |
| Old-Street Wandering | Street name, historical feeling, and light literary text |
| Everyday Street Observation | Markets, shops, crowds, and ordinary life as the core |
| Market Literature | Write everyday vitality through smells, sounds, prices, and crowds |
| Street-Side Shop | Shop name, neighborhood, and one everyday observation |
| Café Record | Shop name, location, date, and relaxed private wording |
| Bookstore Record | Bookstore name, location, and quiet reading atmosphere |
| Museum Check-In | Museum name, exhibition, date, and brief impression |
| Art-Museum Check-In | Exhibition title, artist, date, and one viewing impression |
| Architecture Pilgrimage | Building name, architect, location, and spatial impression |
| World-Heritage Style | Heritage name, location, era, and ultra-brief historical explanation |

#### History / Culture / Tradition

| Name | Description |
|---|---|
| Historical Archive | Period, event, people, and place form a historical record |
| Era as Title | Use the year as the main visual text with one contextual sentence |
| Historical Event | Explain one historical node with minimal facts |
| Historical Figure Quote | Select a genuine quotation highly relevant to the figure or event |
| Classical-Text Excerpt | Quote a short line from a classical text suited to the image context |
| Chronicle Style | Describe events in concise, restrained, slightly classical language |
| Local History | Place, period, and a brief local-history note |
| Cultural-Relic Description | Name, era, material, use, and provenance |
| Intangible Heritage Intro | Project name, region, craft, and cultural value |
| Folk-Custom Record | Festival, custom, location, and participant activity |
| Traditional Craft | Craft name, process, inheritor, or regional information |
| Ancient-Architecture Inscription | Building name, era, and one or two lines of historical context |
| Stele-Inscription Style | Extremely concise classical text suited to historic buildings and ruins |
| Plaque-Inscription Style | Highly condensed four-character or short phrase with traditional inscription character |
| Couplet Style | Two balanced lines suited to architecture and traditional scenes |
| Four-Character Title | Summarize image mood or theme in four Chinese characters |
| Eight-Character Inscription | More complete but still highly condensed traditional inscription |
| Painting/Calligraphy Colophon | Title, short line, time, and signature forming a colophon-like feel |
| Seal-Inscription Style | Minimal title with year/month, location, or credit information |
| Republican-Era Copy | Slightly formal and restrained with old-periodical diction |
| Revolutionary History | Solemn documentary introduction using time, place, people, and event |
| Historical Propaganda Poster | Short and forceful, with period-propaganda language characteristics |
| Old Family Photograph | Family name, year, location, and relationship description |
| Old Album Caption | Plain, short handwriting-like note as if written on the back of an old photograph |

#### Film / Screen / Music

| Name | Description |
|---|---|
| Film Title | Use one conceptual short title to summarize the entire image |
| Film Subtitle | Add one line of story context or emotion beneath the main title |
| Film Voice-Over | Explain or extend the image like a voice outside the frame |
| Film Subtitle Line | One extremely short sentence emphasizing the image's immediate emotion |
| Dialogue-Like Line | Write natural spoken copy that feels like dialogue without copying an existing work |
| End-Credits Style | Time, place, people, and one lingering line |
| Opening-Credits Style | Location, year, time, and one story-beginning line |
| Chapter Title | Summarize the image like a film chapter or episode title |
| Trailer Copy | Short, suspenseful, rhythmic copy that builds anticipation |
| Crime-Film Title | Short, hard, cold wording with an event or character implication |
| Suspense-Film Title | Use a question, location, or keyword to create uncertainty |
| Road-Movie Voice-Over | Center distance, roads, leaving, and arrival |
| Art-House Voice-Over | Restrained, subtle, and lightly literary |
| Youth-Film Voice-Over | Bright and everyday with slight regret or growth |
| Romance-Film Voice-Over | Concise lines about meeting, relationships, and time |
| Documentary Title | Strong factual quality, clear and direct |
| Documentary Voice-Over | Objective facts with a little human warmth |
| Person Documentary | Person name, identity, and one sentence summarizing a life |
| Album Title | Use a short independent concept word as the main title |
| Album Subtitle | Date, location, or one emotional line as supporting information |
| Lyric-Like Line | Write an original short line with lyrical rhythm |
| Vinyl Record Style | Artist name, track title, year, and numbering information |
| Concert Poster | Artist, venue, date, show number, and other structured information |
| Music Festival Style | Event name, artist, place, date, and one slogan |
| Jazz Night | Musicians, place, time, and relaxed nocturnal language |
| Rock Manifesto | Direct, short, aggressive, and attitude-driven |

#### Media / Editorial / Magazine

| Name | Description |
|---|---|
| Magazine Cover | Main title, person/theme name, and several ultra-short feature teasers |
| Person Magazine Cover | Center the person's name, with occupation and one thematic line |
| Fashion Magazine Cover | Very little text, emphasizing name, brand feel, and keywords |
| Photography Magazine | Work title, location, equipment, or photographic theme side by side |
| Travel Magazine | Large location title plus several travel keywords |
| Architecture Magazine | Building name, location, designer, and spatial keywords |
| Art Magazine | Center artist, artwork, or conceptual theme |
| Sports Magazine | Person, discipline, competition, and one competitive theme line |
| News Weekly | Large event headline with one concise context line |
| Special Report | One core theme plus 2–3 short hierarchical information items |
| Cover Story | Image subject plus one thematic line that summarizes the story |
| Editor's Lead | Explain why the subject matters in an extremely short paragraph |
| Section Header | Use a short category name like a recurring editorial section |
| Issue Number Style | Issue, date, theme, and number create periodical character |
| Newspaper Front Page | Strong headline, lead, and a small amount of time/place information |
| Newspaper Supplement | More literary, more everyday title and short copy |
| Culture Supplement | Short copy around literature, art, and local culture |
| Photography Book | Work title, location, year, and photographer |
| Exhibition Catalog | Exhibition title, artist, time, place, and curatorial theme |
| Curatorial Text | More conceptual, but kept within an extremely short paragraph |
| Editor's Note | A brief note written as if from an editor to the reader |
| Column Comment | One judgment plus a short viewpoint paragraph |
| Commentary Headline | A positioned but concise title summarizing the image theme |
| Visual Essay | Abstract title plus rational subtitle to create a research-like feel |

#### Slogan / Manifesto / Strong Type

| Name | Description |
|---|---|
| Minimal Slogan | A 2–8-character/word phrase, direct and impactful |
| Manifesto | One explicit attitude or position, suited to visually dominant subjects |
| Call to Action | Begin with a verb and emphasize immediate action |
| Youth Manifesto | Confident and direct with slight rebellion |
| Sports Slogan | Emphasize breakthrough, speed, winning/losing, and persistence |
| Team Slogan | Emphasize common goals, collaboration, and collective strength |
| City Slogan | One sentence summarizing city character or travel feeling |
| Brand Manifesto | Minimal and abstract with a clear value proposition |
| Life Attitude | Use a short line to express a way of living |
| Freedom Manifesto | Freedom, distance, choice, and action as the core |
| Rebellion Manifesto | Refuse obedience and explanation; state the attitude directly |
| Strength Manifesto | Emphasize resilience, strength, and continuing forward |
| Victory Manifesto | Highlight results, honor, and competition |
| Never Give In | Extremely short and conversational, with strong competitive and youthful energy |
| Push the Limit | Suited to sports, mountains, racing, and other high-intensity images |
| Leave Now | Suited to travel, roads, sports, and other action-oriented images |
| Keep the Passion | Gentle and positive, suited to youth, hobbies, and everyday records |
| Look Forward | Minimal and positive without depending on a specific subject |
| Grow Wild | Strong vitality, suited to youth, plants, or growth themes |
| Born Free | Emphasize freedom and subject independence |
| Refuse Definition | Suited to person features, youth culture, and individuality |
| Keep Running | Works for sports, life, and growth |
| Happening Now | Suited to news, street scenes, and immediate everyday life |

#### Official / Collective / Formal

| Name | Description |
|---|---|
| Official Group-Photo Introduction | Formal combination of organization, title, activity, time, place, and related information |
| Leadership Research Visit | Research theme, organization, place, date, and concise on-site note |
| Work Meeting Record | Meeting title, location, date, and participating organizations |
| Project Inspection Record | Project name, inspecting organization, location, and time |
| Group Photo Caption | Standard commemorative wording using team/organization, activity, and date |
| Symposium Record | Theme, participants, place, and date |
| Signing Ceremony Record | Both organizations, project name, date, and place |
| Launch Ceremony | Project/activity name, launch time, and location |
| Unveiling Ceremony | Organization name, unveiling item, time, and place |
| Groundbreaking Ceremony | Project name, place, date, and construction organization |
| Completion Commemoration | Project name, completion time, and construction information |
| Visit & Exchange | Organization, host, place, and date |
| Academic Exchange | Conference, speaker, institution, date, and place |
| Alumni Group Photo | School, graduating class/cohort, activity, and date |
| Class Group Photo | Class, school, year, and activity |
| Graduation Group Photo | School, college, class, year, and commemorative line |
| Award Commemoration | Award name, recipient, time, and place |
| Sports Podium | Discipline, placing, event, time, and place |
| Team-Building Commemoration | Team name, location, date, and activity theme |
| Volunteer Activity Record | Activity name, location, time, and organizing body |
| Public-Welfare Activity Record | Public-welfare theme, participants, place, and date |

#### Commercial / Product / Brand

| Name | Description |
|---|---|
| Product Name | Product name as the large title with one core feature |
| Product Parameters | Structured presentation of model, dimensions, materials, specifications, and similar data |
| Product Selling Points | Build commercial hierarchy from 3–5 concise selling points |
| New Product Launch | Product name, launch information, and one core concept |
| Brand Story | Brand name plus one concise background or idea |
| Brand Slogan | Brand name plus one value proposition |
| Model Archive | Model, year, parameters, and numbering create technical character |
| Automotive Ad | Vehicle model plus a short performance or lifestyle line |
| Camera Ad | Camera model, lens, and one photography idea |
| Watch Ad | Brand, model, and a time-oriented short line |
| Perfume Copy | Abstract, sensory, extremely short scent association |
| Fashion Editorial | Brand, collection, material, and keywords |
| Sneaker Trend | Model, colorway name, and one youth-oriented line |
| Interior Design | Design name, material, and spatial concept |
| Food Packaging | Product name, flavor, origin, and one appetite-oriented description |
| Coffee Info | Origin, processing method, roast level, and flavor keywords |
| Beverage Label | Name, year, origin, flavor, or alcohol content |
| Handmade Brand | Brand, material, production method, and a hand-crafted line |

#### Nature / Landscape / Flora & Fauna

| Name | Description |
|---|---|
| Landscape Title | Use place name or landscape name as the core title |
| Mountain Title | Mountain name, elevation, place, and one concise character description |
| River Title | River name, place, and an ultra-brief water-system text |
| Coast Title | Coast name, coordinates, date, and one spatial line |
| Lake Title | Lake name, location, and a concise description of calm, vastness, or similar qualities |
| Forest Title | Forest name, location, and a short ecological-atmosphere line |
| Wilderness Title | Place name plus one line about vastness, solitude, or natural force |
| Landform Archive | Science-oriented text using landform name, location, formation characteristics, and similar information |
| Animal Card | Species name, scientific name, location, and short behavior description |
| Wildlife Documentary | Time, location, species, and behavior state |
| Pet Portrait | Name, age, and one or two personality lines |
| Plant Card | Common name, scientific name, location, or morphological characteristics |
| Flower Title | Flower name plus short poetic or scientific information |
| Bird Observation | Bird name, location, date, and observed behavior |
| Marine-Life Observation | Species, location, waters, and behavior information |
| Nature Observation Note | Date, place, and one or two observational sentences |
| Nature Explainer | Name, classification, and concise core characteristics |
| National-Geographic Style | Location, species, or natural phenomenon plus an objective paragraph |
| Exploration-Channel Style | Narrative explanation emphasizing discovery, environment, and behavior |

#### Art / Experimental / Conceptual

| Name | Description |
|---|---|
| Concept Proposition | Define the image theme with one abstract word or short phrase |
| Artwork Title | Use a short, open-ended title like a contemporary artwork |
| Untitled | Use “Untitled” plus a number or year for exhibition character |
| Numbered Work | Downplay naming and build a series through numbering and year |
| Exhibition Proposition | Organize the image with one theme word that leaves room for thought |
| Bilingual Art Title | Chinese main title plus a short English subtitle |
| English Word Title | One conceptual English word as the visual core |
| Latin-Like Title | Use a very small amount of Latin or classical vocabulary to heighten ritual character |
| Philosophical Proposition | Guide reflection with a short question or judgment |
| Question Form | Explain the image with an open question rather than a conclusion |
| Rhetorical Question | Conceptual copy with slight conflict and attitude |
| Fragmented Text | Multiple incomplete short phrases create non-linear reading |
| Keyword Stack | Use 3–8 keywords to build thematic associations |
| Coordinate Numbering | Numbers, letters, coordinates, and identifiers form an experimental visual |
| System Log | Machine-language-style text using timestamps, identifiers, status, and similar data |
| Data Labels | Abstract image information into values, labels, and parameters |
| Glitch Text | Repeated, truncated, or displaced short text reinforces experimentation |
| Cipher Text | Numbers, symbols, and a small amount of readable text create mystery |
| Annotation System | Arrows, numbers, and short notes point to local image details |
| Handwritten Annotation | Leave observations and notes on the image as if directly written by the creator |
| Draft Notes | Keywords, arrows, dates, and casual notes create a sketchbook feel |
| Collaged Sentences | Short phrases of different lengths scatter and combine like paper scraps |
| Flyer Fragments | Broken lines resembling old flyers or torn printed scraps |
| Book-Page Excerpt | Use a short literary passage aligned with the image |
| Dictionary Definition | Turn the subject term into a headword plus definition |
| Encyclopedia Entry | Name, category, short definition, and supplementary information |
| Footnote Style | Very little main-title text; most content behaves like an academic footnote |
| Quotation | Use one short quotation as the image's only major text |
| Centered Quote | Place one line in quotation marks as the visual core |
| Blank Title | Leave almost no text—sometimes only one word—to emphasize visual negative space |

</details>

<details>
<summary><strong>Aspect Ratio / Format Presets (click to expand)</strong></summary>

> By default, the original image ratio is not changed proactively. This library is used only when the user explicitly specifies a medium / platform / ratio, or explicitly asks the AI to recommend an output ratio. Avoid damaging Concept 4's original composition merely to force a preset ratio.

#### Square / Square Formats

| Ratio preset | Description |
|---|---|
| Album Cover | 1:1 square; concentrated subject; suited to portraits, albums, single objects, and strong centered composition |
| Square Poster | 1:1; visually balanced; suited to centered subjects and modular layouts |
| Social Square | 1:1; balances mobile-feed display with text presentation |
| Polaroid Square | Near-1:1 photo area, optionally paired with a wider bottom border for instant-photo character |
| Vinyl Inner Sleeve | 1:1; suited to generous negative space, graphic design, and small text |
| Minimal Square Booklet | 1:1; like an art book or portfolio page |
| Nine-Grid Tile | 1:1; suited to building a nine-tile social-media series |
| Square Archive Card | 1:1; suited to subject, number, time, place, and other archival information |
| Square Magazine Cover | 1:1; balances large title, subject, and supporting information |
| Square Art Label | 1:1; suited to conceptual subjects and very little text |
| Podcast Cover | 1:1; suited to people, show title, and strong recognition |
| Playlist Cover | 1:1; suited to mood images and limited text |
| Circular Record | 1:1 base composition while accounting for final circular crop |
| Circular Avatar | 1:1 with edge safety for circular cropping |
| Badge Composition | 1:1 or a circular safe area, suited to a single subject and very little text |

#### Classic Photography / Film

| Ratio preset | Description |
|---|---|
| Classic Photography | 3:2, close to 35mm film and full-frame camera photography |
| Retro Film | 3:2, preserving traditional film-photography viewing habits |
| 35mm Film | 3:2, classic camera frame |
| Camera Original | 3:2, emphasizing the photograph itself and reducing over-designed layout |
| Photography Book | 3:2, suited to large-image display and minimal information |
| Travel Photography | 3:2, balancing people and environment |
| Street Photography | 3:2, suited to relationships between people and streets |
| Humanistic Documentary | 3:2, with a strong authentic-photography feel |
| Film Diary | 3:2, suited to date, place, and a small amount of photo information |
| Photojournalism | 3:2, consistent with common news-photography viewing conventions |
| Horizontal Postcard | About 3:2, suited to landscapes, places, and short text |
| Exhibit Card | About 3:2 or 4:3, suited to work title, artist, and minimal description |

#### Traditional Television / 4:3

| Ratio preset | Description |
|---|---|
| Classic Television | 4:3, evoking traditional TV, old video, and early digital imagery |
| Old-TV Frame | 4:3, suited to VHS, documentary footage, and home video |
| Retro Video | 4:3, compact composition that easily evokes 1990s video character |
| Medium-Format Photography | 4:3, steadier than 3:2 and suited to people, architecture, and still life |
| Traditional Digital Camera | 4:3, evoking early digital cameras and everyday records |
| Photography Archive | 4:3, suited to subject plus number, time, and location |
| Museum Catalog | 4:3, complete subject with orderly information |
| Old Newspaper Image | 4:3, suited to documentary, archives, and print grain |
| Surveillance Image | 4:3, suited to timestamps, numbering, and observational visuals |
| Home Video | 4:3, suited to everyday life, family, childhood, and nostalgia |
| VHS Caption Frame | 4:3, suited to timestamps, dates, and camcorder subtitles |
| Research Record Image | 4:3 or 3:2, highly compatible with subject, numbering, parameters, and notes |

#### Standard Widescreen / 16:9

| Ratio preset | Description |
|---|---|
| Widescreen Photography | 16:9, a common modern horizontal ratio suited to environmental narrative |
| Film/TV Frame | 16:9, standard screen-capture feel |
| Video Cover | 16:9, suited to large titles, subjects, and information zoning |
| Documentary Frame | 16:9, suited to person documentary, events, and scene description |
| Landscape Widescreen | 16:9, suited to mountains, coasts, and city skylines |
| Game Screenshot | 16:9, strong modern digital-content character |
| TV Documentary | 16:9, balancing informational captions and the subject image |
| Horizontal Story Page | 16:9, suited to dividing text and subject across left/right areas |
| Cinema Promotional Image | 16:9, suited to people, scenes, titles, and film-name layout |
| Display-Screen Frame | 16:9, suited to web hero images and large screens |
| Horizontal Video Cover | 16:9, suited to a large subject, title, and background narrative |
| Desktop Wallpaper | 16:9 or 16:10, suited to horizontal environments and offset subjects |
| News Broadcast Frame | 16:9, allowing a subtitle bar at the bottom |
| Sports Broadcast Frame | 16:9, suited to score, athlete names, and event information |
| Esports Broadcast Frame | 16:9, suited to people, game scenes, and layered information |

#### Cinematic Widescreen

| Ratio preset | Description |
|---|---|
| Letterboxed Cinema | About 2.39:1, classic ultra-wide-screen feel with strong narrative character |
| Widescreen Cinema | About 2.35:1, suited to juxtaposing people with large environments |
| CinemaScope | About 2.39:1, ultra-wide cinematic composition |
| Cinematic Black Bars | 2.39:1 or 2.35:1, creating a letterboxed film-still feel |
| Road Movie | About 2.39:1, suited to roads, vehicles, people, and distance |
| Western Widescreen | About 2.39:1, suited to wilderness, mountains, and vast environments |
| Epic Cinema | About 2.39:1, emphasizing scale, environment, and group layers |
| Art-House Cinema | About 2:1–2.39:1, with broad horizontal negative space for restrained narrative |
| Crime Cinema | About 2.39:1, suited to offset characters, dark areas, and negative space |
| Urban Cinema | About 2.39:1, suited to streets, buildings, vehicles, and layers of light |
| Univisium Cinema | 2:1, between 16:9 and ultra-wide cinema |
| Modern Cinema | 2:1, cinematic without becoming excessively flat |
| Streaming Series | 2:1, balancing people and environment |
| Horizontal Film Poster | 2:1, suited to title, large scene, and offset subject |
| Panoramic Narrative | 2:1, suited to multiple horizontal subjects or scene zoning |
| Golden Widescreen | About 1.85:1, classic theatrical ratio |
| American Cinema | 1.85:1, suited to character drama, city scenes, and interiors |
| Classic Theatrical | 1.85:1, slightly wider than 16:9 with a natural cinematic feel |
| Drama Film | 1.85:1, balanced ratio between people and setting |
| Art Cinema | 1.66:1, slightly retro European-cinema feel |
| European Cinema | 1.66:1, suited to people, architecture, and humanistic scenes |
| Academy Ratio | 1.37:1, classic early-cinema ratio |
| Silent-Film Ratio | About 1.33:1, suited to old films and black-and-white imagery |
| Old Film | 1.37:1, suited to black-and-white, grain, and subtitles |
| IMAX Film | About 1.43:1, taller frame suited to monumental architecture and landscapes |
| Digital IMAX | About 1.90:1, balancing widescreen with more vertical information |

#### Mobile Vertical / Social

| Ratio preset | Description |
|---|---|
| Vertical Cinema | 9:16, cinematic composition for a portrait phone screen |
| Mobile Story | 9:16, suited to full-screen mobile viewing |
| Short-Video Cover | 9:16, emphasizes people and allows text above/below |
| Vertical Documentary | 9:16, suited to people, street scenes, architecture, and field records |
| Phone Wallpaper | 9:16, keep the subject away from top/bottom system areas |
| Vertical Film Poster | 9:16, combines film-poster design with full-screen mobile display |
| Vertical Travel Card | 9:16, suited to architecture, peaks, people, and vertical landscapes |
| Vertical Person Close-Up | 9:16, with the person occupying the visual center |
| Vertical Architecture | 9:16, suited to towers, high-rises, mountains, and trees |
| Vertical Story Page | 9:16, arranging subject, text, and information from top to bottom |
| Instagram Story | 9:16, full-screen portrait format suited to people, check-ins, and short text |
| Vertical Short-Video Cover | 9:16, suited to large titles and a single subject |
| Phone Lock Screen | About 9:19.5–9:20, suited to full-screen smartphones |
| Full-Screen Phone Wallpaper | Extra-tall portrait frame; reserve top and bottom system areas |

#### Social Portrait / 4:5 / 3:4

| Ratio preset | Description |
|---|---|
| Mobile Post | 4:5, common portrait ratio for social media |
| Social Portrait | 4:5, natural person proportion with a large footprint in feeds |
| Vertical Photography | 4:5, more stable than 9:16 |
| Fashion Portrait | 4:5, common commercial and fashion-photography ratio |
| Magazine Person Page | 4:5, suited to full-body person, large title, and supporting information |
| Social Poster | 4:5, suited to mobile distribution and complete poster layouts |
| Product Key Visual | 4:5, emphasizes product while retaining a text zone |
| Art Portrait | 4:5, suited to subject contour, grain field, and text coexisting |
| Check-In Photo | 4:5, suited to location, date, people, and environment together |
| Youth Portrait | 4:5, visually full and suited to people with youth-oriented text |
| Instagram Portrait Post | 4:5, high screen occupancy on mobile |
| Classic Poster | 3:4, visually stable and suited to people, architecture, events, and information |
| Vertical Poster | 3:4, more compact than 2:3 |
| Person Feature | 3:4, suited to half-body person, name, and subtitle |
| Architecture Feature | 3:4, suited to a single building and explanatory information |
| Art Poster | 3:4, suited to combining zoning, grain, text, and subject |
| Documentary Cover | 3:4, combining photographic and editorial character |
| School Poster | 3:4, suited to people, event title, time, and place |
| Exhibition Key Visual | 3:4, suited to artistic subjects and stronger layout design |
| Sports Event Poster | 3:4, suited to athletes, event name, time, and place |
| Biography Cover | 3:4, makes person/text hierarchy easy to establish |
| Xiaohongshu Cover | 3:4, suited to title, people, and information hierarchy |
| Xiaohongshu Portrait | 3:4, comfortable for mobile reading |

#### Classic Portrait / 2:3 / 5:4

| Ratio preset | Description |
|---|---|
| Classic Portrait | 5:4, steady and formal, suited to portraits and still life |
| Medium-Format Portrait | 5:4, formal traditional medium-format feel |
| Art Portrait | 5:4, comfortable relationship between subject and negative space |
| Formal Group Photo | 5:4, suited to moderately sized groups |
| Product Photography | 5:4, suited to centered product and clean background |
| Art-Book Portrait | 5:4, suited to art publishing and portfolios |
| Vertical Magazine | About 2:3, close to traditional portrait photography and publishing covers |
| Classic Vertical | 2:3, equivalent to rotating 3:2 |
| Vertical Film | 2:3, traditional 35mm portrait-shot feel |
| Full-Body Person | 2:3, suited to complete body proportions and vertical breathing room |
| Full-Height Architecture | 2:3, suited to façades, towers, and tall subjects |
| Vertical Travel Photo | 2:3, suited to a person standing within an environment as a keepsake |
| Literary Vertical | 2:3, suited to offset people and large negative space |
| Exhibition Poster | 2:3, classic vertical-poster feel |
| Vertical Film Poster | 2:3, traditional movie-poster ratio |
| Photography Exhibition Poster | 2:3, ample room for image and typography |
| Book Cover | About 2:3, suited to title, author, subject, and negative space |
| Novel Cover | About 2:3, suited to strongly narrative vertical visuals |
| Comic Cover | About 2:3, allowing exaggerated subject and large title |
| Game Cover | About 2:3, suited to characters, scene, and large title |
| DVD Cover | About 2:3, traditional screen-media package ratio |

#### Standard Paper / Print

| Ratio preset | Description |
|---|---|
| A-Series Poster | About 1:√2, international A4/A3/A2/A1 paper ratio |
| A4 Flyer | 1:√2, suited to information-rich but clearly structured graphic/text layout |
| A3 Poster | 1:√2, suited to exhibitions, events, and formal visual design |
| A2 Exhibition Poster | 1:√2, suited to large titles, subject, and large-grain background |
| A1 Large Poster | 1:√2, suited to long-distance viewing and large-area visual effects |
| B-Series Poster | Close to 1:√2, oriented toward professional printing and display |
| Movie One-Sheet | About 27:40, traditional movie One Sheet ratio |
| American Movie Poster | About 27:40, mature hierarchy for key visual, title, cast/credits |
| Japanese Movie Poster | Close to B-series vertical format, suited to denser text plus subject |
| Exhibition Invitation | About 2:3 or 3:4, suited to artwork image, exhibition title, and date |
| Vertical Postcard | About 2:3, suited to architecture, people, and travel keepsakes |

#### Banners / Tickets / Ultra-Wide

| Ratio preset | Description |
|---|---|
| Ticket Stub | About 2:1–3:1, narrow horizontal banner suited to number, time, and place |
| Cinema Ticket | About 2.5:1, suited to film title, date, and seat-number design |
| Train Ticket | About 2.5:1–3:1, suited to origin/destination, date, and number |
| Boarding Pass | About 3:1, ultra-horizontal information structure suited to travel and coordinates |
| Admission Ticket | About 2.5:1, suited to event name, time, and ticket number |
| Film Strip | About 3:1–5:1, simulating continuous film and multiple frames |
| Contact Sheet | Ultra-wide multi-frame structure suited to continuous action or travel fragments |
| Panorama | About 3:1, suited to coasts, mountains, city skylines, and groups |
| Ultra Panorama | About 4:1–6:1, extremely strong horizontal extension |
| City Skyline | About 3:1–4:1, emphasizing continuity of buildings and the horizon |
| Mountain-River Scroll | About 4:1 or wider, suited to continuous mountains, architecture, and natural scenery |
| Eastern Handscroll | Ultra-wide horizontal ratio imitating the unfolding of a traditional handscroll |
| Banner Poster | About 3:1, suited to events, sports, architecture, and large titles |
| Website Banner | About 3:1–4:1, suited to top-of-page key visuals |
| Website Hero | About 2:1–3:1, offset subject with reserved text area |
| WeChat Official-Account Header | About 2.35:1, suited to title and subject side by side |
| Video Channel Banner | Ultra-wide horizontal composition suited to brand name, people, and extended background |
| LED Large Screen | About 3:1–5:1, suited to stages, conferences, and city screens |
| Stage Backdrop | Ultra-wide horizontal format; subject and text must remain readable from distance |
| Exhibition Backdrop | About 2:1–3:1, suited to brand, person, and theme |
| Fan Support Hand Banner | About 3:1–5:1, extremely long horizontal format suited to names, slogans, and idol subjects |
| Concert Hand Banner | About 4:1, emphasizing person name, short slogan, and long-distance recognition |
| Sports Support Banner | About 4:1–6:1, suited to team name, player name, and slogan |
| Stadium-Railing Banner | Extra-long horizontal banner suited to continuous text, team mark, and minimal subject |
| Fan Light Sign | About 2:1–3:1, suited to very few large characters and high contrast |
| Store Sign | About 3:1–5:1, typography first with subject as support |
| Storefront Ad | Ultra-wide ratio suited to brand name, large type, and few visual elements |
| Street Billboard | About 2:1–3:1, requiring strong contrast for long-distance viewing |

#### Long Image / Hanging Scroll / Extra-Tall

| Ratio preset | Description |
|---|---|
| Mobile Long Image | About 1:2–1:4, continuous vertical reading suited to stories and information feeds |
| Long Poster | Extra-tall portrait format that can arrange title, subject, and body from top to bottom |
| Vertical Long Scroll | About 1:3 or taller, suited to mountains, architecture, trees, and vertical narrative |
| Eastern Hanging Scroll | Extra-tall portrait format imitating a traditional hanging scroll, suited to landscapes, calligraphy, and negative space |
| Hanging-Scroll Poster | About 1:2.5–1:3.5, subject unfolds vertically |
| Tower Composition | Extra-tall format suited to towers, high-rises, full-body people, and peaks |
| Waterfall Long Image | Extra-tall portrait format suited to waterfalls, gorges, and other vertical natural subjects |
| Vertical LED Tower Screen | Extra-tall format suited to one person, brand name, or animation-like composition |
| Elevator-Door Ad | Near 1:2 tall portrait format suited to vertically arranged people or products |
| Building-Façade Screen | Extra-tall or extra-wide; elements must be extremely simplified |

#### Wallpaper / Screens

| Ratio preset | Description |
|---|---|
| Tablet Wallpaper | About 4:3, suited to broad environments and relatively centered subjects |
| Ultrawide Wallpaper | 21:9, suited to cities, mountains, games, and cinematic scenes |
| Dual-Screen Wallpaper | About 32:9, extremely wide panorama suited to continuous environments and dual subjects |
| Esports Ultrawide | 32:9, extremely extended horizontal visual |
| Exhibition Projection | 16:9, 4:3, or 2:1 depending on equipment and work requirements |
| Digital Signage | 9:16 or 16:9, suited to public information in malls and stations |
| Information Wall | 16:9 or 21:9, balancing key visual and data/text |
| Airport Large Screen | Ultra-wide banner suited to urban air travel and brand visuals |
| Stadium Screen | 16:9 or ultra-wide, suited to players, score, and team name |
| Wraparound-Screen Visual | Extra-long banner whose content supports continuous or repeating edges |

#### Social / Platform / Advertising Formats

| Ratio preset | Description |
|---|---|
| Instagram Square Post | 1:1, suited to visual series and centered composition |
| Livestream Cover | 16:9 or 9:16 depending on horizontal or vertical livestream |
| Bus-Stop Ad | About 2:3 portrait, suited to people, products, and large titles |
| Metro Lightbox | About 2:3 or 3:4, suited to information-dense advertising visuals |
| Mall Lightbox | Portrait or landscape, suited to people, products, and brand information |
| Outdoor Giant Screen | Extremely wide ratio; visual elements must be huge and simple |
| Elevator Poster | About 3:4 or 2:3, suited to close-range reading and complete information |
| Vehicle-Wrap Ad | Ultra-wide and often subject to irregular cropping |
| Bus Ad | Ultra-wide, suited to brand, people, and very little text |
| Metro-Car Ad | Long horizontal ratio suited to continuous layout and multiple information nodes |
| Hoarding Ad | Extra-long banner allowing repeated subjects and brand information |
| Construction Hoarding | Extra-long horizontal format suited to large graphics, project name, and city visuals |

#### Art Books / Multi-Panel / Cards

| Ratio preset | Description |
|---|---|
| Diptych | About 2:1 overall, composed of two related images side by side |
| Triptych | About 3:1 overall, composed of three continuous or contrasting images |
| Two-Page Art Book | About 2:1, like an open magazine spread |
| Magazine Spread | About 2:1, suited to large image, title, and left/right page information roles |
| Photography Spread | About 2:1, suited to horizontal landscape or distribution of person and text |
| Bi-Fold Brochure | About 2:1 when open, suited to two left/right content zones |
| Tri-Fold Visual | Ultra-wide divided into three sections, suited to three content zones or a continuous story |
| Foldout Scroll | Extra-long horizontal, unfolding multiple scenes and information levels |
| Stamp Ratio | About 3:4–2:3, small vertical rectangle suited to one subject and border |
| Collectible Card | About 5:7 or 2.5:3.5, suited to people, number, attributes, and small text |
| Sports Card | About 5:7, person-centered with clear name and event information |
| Fan Photocard | About 2.5:3.5, centered on idol subject, name, and concise information |
| Polaroid | Near-4:5 outer frame with a more square internal photo area |
| ID Photo | Commonly about 3:4, upright subject and clean background |
| Portrait Business Card | About 2:3 or 3:4, balancing person and name information |
| Horizontal Business Card | About 1.75:1, suited to name, identity, and limited brand visual |
| Vertical Business Card | About 1:1.75, more design-forward |
| Menu Card | About 2:3 or 3:4, suited to food subject and price information |
| Archive Card | About 4:3 or 3:2, suited to number, photo, and information fields |
| Postcard Archive | 3:2, combining image with travel information |
| Evidence Photo | 4:3 or 3:2, suited to identifier, scale, and archival text |

#### Architecture / Product / Packaging

| Ratio preset | Description |
|---|---|
| Architectural Elevation | 2:3, 3:4, or extra-tall, emphasizing the complete outer form |
| Architectural Panorama | 16:9–3:1, suited to building groups, blocks, and urban space |
| Interior Design Image | 4:3 or 3:2, naturally stable for spatial structure |
| Product Detail Hero | 1:1 or 4:5, with high product recognizability |
| E-Commerce Portrait | 3:4 or 4:5, suited to product plus selling-point layout |
| Product Square | 1:1, suited to platform thumbnails and centered product display |
| Food Menu Landscape | 3:2 or 16:9, suited to dishes, environment, and text information |
| Package Front | Commonly 2:3, 3:4, or 1:1, with product recognition as the core |
| Wine Label | About 2:3 or 3:4, suited to brand name, year, and origin |
| Perfume Label | About 3:4 or 1:1, suited to minimal branding and premium negative space |

#### Special Composition / Irregular Safe Areas

| Ratio preset | Description |
|---|---|
| Sticker Composition | No fixed ratio; build a compact irregular layout around the subject's outer contour |
| Stamp Border | About 3:4 or 2:3, centered subject with perforation-like outer space reserved |
| Framed Photograph | Traditional photography ratios such as 3:2, 4:3, or 5:4 |
| Folding-Screen Painting | Multiple vertical panels; each independent but continuous as a whole |
| Eastern Album Leaf | Near-square or lightly vertical, suited to small scenes, negative space, and inscription |
| Fan Composition | Flat horizontal or fan-shaped crop, suited to landscape, people, and traditional inscription |

</details>

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
│   ├── 04-generation-compiler.md
│   └── 05-quality-control.md
└── agents/
    └── openai.yaml
```

---
## Find the Author

**Author:** [**autainmo**](https://github.com/autainmo)  
The unified username on Douyin and other content platforms is `独自艺人`. Search this name on the platform you use to find the author and future works.

After the first two generations completed by each Skill within the same conversation, it gives a light reminder: `If shared publicly, you're welcome to credit: Visual Skill by @独自艺人`; from the third generation onward, it does not repeat the reminder.

---
## License

This project is licensed under the **MIT License**.

- [`LICENSE`](./LICENSE): official English license text;
- [`LICENSE.zh-CN.md`](./LICENSE.zh-CN.md): Chinese reading guide.

The Chinese guide is provided to aid understanding and does not replace the official English license text.
