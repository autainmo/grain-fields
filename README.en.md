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
>
> The default installation location is `$CODEX_HOME/skills/grain-fields`.

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

## Complete Preset Index

The following is the current grain, color, text, and aspect-ratio preset index.

### Grain Presets
> Full matching logic and execution rules: [`references/presets-grain.md`](references/presets-grain.md). The Chinese names below are the canonical preset names; English glosses are included for readability.

**Print / Halftone**  
`柔和网点 (Soft Halftone)`、`中等半调 (Medium Halftone)`、`丝网网点 (Screen-Print Dots)`、`Riso 孔版颗粒 (Riso Stencil Grain)`、`报纸细粗过渡 (Newspaper Transitional Grain)`、`油墨轻缺失 (Light Ink Loss)`

**Natural / Mineral**  
`柔砂颗粒 (Soft Sand Grain)`、`矿物细粒 (Mineral Fine Grain)`、`石墨颗粒 (Graphite Grain)`、`纸浆纤维颗粒 (Paper-Pulp Fiber Grain)`、`微晶颗粒 (Micro-Crystal Grain)`、`釉面细粒 (Fine Glaze Grain)`

**Soft / Optical**  
`雾化颗粒 (Mist Grain)`、`柔焦颗粒 (Soft-Focus Grain)`、`银盐颗粒强化 (Enhanced Silver-Halide Grain)`、`纸面印刷颗粒 (Paper-Print Grain)`

> The built-in grain library explicitly excludes oversized blocks, giant pixels, fuse beads, giant mosaic tiles, dreamy blocks, glass blocks, giant low-poly cells, and toy-like or candy-like grain.

### Color Presets
> Concise descriptions and selection guidance are available in [`references/presets-color.md`](references/presets-color.md). Auto mode favors restrained directions; explicitly requested presets remain available, but color count and decorative intensity are still controlled.

**Emotion / Atmosphere**
`Violent Aesthetics`, `Sports Competition`, `Hot-Blooded Youth`, `Cool Restraint`, `Dark Oppression`, `Gentle Whisper`, `Solitary Narrative`, `Compassionate Documentary`, `Glimmer of Hope`, `Romantic Haze`, `Resolute Coldness`, `Calm Healing`, `Ethereal Silence`, `Solemn Gravity`, `Mysterious Unknown`, `Bright and Light`, `Sweet-Cool Contrast`, `Primal Wildness`, `Idealism`, `Emotional Release`, `Quiet Negative Space`, `Suppressed Murmur`, `Bright Optimism`, `Sharp Rationality`, `Soft-Mist Emotion`

**Era / Retro / Nostalgia**
`Retro Poster`, `News Documentary`, `Newspaper Print`, `Archival Imagery`, `Old Photograph`, `Nostalgic Film`, `Hong Kong Film Look`, `Hong Kong Night Cinema`, `1990s`, `1980s`, `1970s`, `1960s Pop`, `American Retro`, `Soviet-Style Propaganda`, `Old Shanghai`, `Republican-Era Newspaper`, `VHS Tape`, `Photocopier`, `Old Television`, `Polaroid`, `Old Magazine`, `Vintage Movie Poster`, `Projector Film`, `Old Postcard`, `Vintage Record Sleeve`, `Cassette Cover`, `Old Brochure`, `Vintage Package Print`

**Sports / Competition**
`Extreme Sports`, `Racing Livery`, `Football Stadium`, `Street Basketball`, `Winter Sports`, `Outdoor Technical`, `Adventure Documentary`, `Esports Energy`, `Combat Ring`, `Fresh Marathon`, `Strength Training`, `Sunny Surfing`, `Street Skateboarding`, `Classic Boxing`, `Sneaker Trend`, `Athletics Track`, `Water Sports`, `Off-Road Rally`

**Technology / Future / Digital**
`Cyber Future`, `Digital Glitch`, `Future Silver Gray`, `Tech Blue`, `Deep Space`, `Acid Visuals`, `Y2K Millennium`, `Holographic Iridescence`, `Interface System`, `Data Visualization`, `Medical Clean`, `Laboratory Cold Light`, `Quantum Cold Purple`, `Robotic Industry`, `Thermal Imaging`, `X-Ray Blue`, `Aerospace`, `Core Data Center`, `Electronic Chips`, `Metaverse`, `AI Neural Network`, `Green Terminal Screen`, `Radar Scan`, `Industrial Warning Tech`

**City / Industrial / Utility**
`Street Trend`, `Punk Rock`, `Neon Nightwalk`, `Steam Machinery`, `Industrial Hardcore`, `Workwear Utility`, `Military Tactical`, `Architectural Minimalism`, `Architectural Avant-Garde`, `Urban Cool Gray`, `Urban Warm Night`, `City Neon`, `Modern Metropolis`, `Premium Business`, `Parking-Garage Cold Light`, `Concrete Architecture`, `Copper Patina`, `Rusty Metal`, `Subway System`, `Nightclub City`, `Dockside Warehousing`, `Elevated-Road Cool Gray`, `Construction Warning`, `Airport Terminal`

**Nature / Landform / Material**
`Forest Nature`, `Moss Forest`, `Grassland Blue Sky`, `Quiet Snowfield`, `Mountain Earth`, `Rock and Mineral`, `Volcanic Lava`, `Aurora Iridescence`, `Glacier Blue`, `Ocean Blue-Green`, `Island Sunlight`, `Desert Warmth`, `Wild West`, `Danxia Red Earth`, `Coral Coast`, `Wetland Waterfront`, `Valley Bluestone`, `Salt-Flat White Alkali`, `Rainforest Green`, `High-Plateau Thin Air`, `Hard Island Reef`, `Clay Mineral`, `Jade Veins`, `Desert Mineral Gray`, `Misty Lake Blue`, `Black-Sand Coast`

**Art / Print / Graphics**
`Screen Printing`, `Woodcut Print`, `Pop Art`, `Comic Printing`, `Editorial Magazine`, `Overprint`, `Halftone Overprint`, `Reduction Print`, `Colored Cut-Paper Collage`, `Iconic Graphics`, `Art Smearing`, `Spray-Paint Graffiti`, `Poster Color Collision`, `Propaganda Layout`, `Paper Collage`, `Dirty Ink`, `Two-Color Print`, `Three-Color Composition`, `Risograph Stencil Print`, `Two-Color Screen Print`, `Monochrome Newspaper with Red Overprint`, `Four-Color Comics`, `Papercut Color Blocks`, `Paper Dyeing`

**Fashion / Editorial / Premium**
`Fashion Editorial`, `Premium Gray`, `Black-and-White Minimal`, `Off-White Minimal`, `Cool Minimal`, `Dark Minimal`, `Nordic Cool`, `Japanese Clear`, `Korean Cream`, `French Retro`, `Italian Richness`, `British Classic`, `German Rationality`, `Swiss Design`, `Bauhaus`, `Memphis`, `Cream Retro`, `Commercial Display`, `Perfume Advertising`, `Luxury Jewelry`, `Collector Art Book`, `Black-and-Gold Luxury`, `White-and-Gold Luxury`, `Gemstone Luxury`, `Royal Blue and Gold`, `Burgundy Red`, `Midnight Blue`, `Mother of Pearl`

**Youth / Lightness / Fantasy**
`Youth Dopamine`, `Candy Sweet-Cool`, `Girlhood Pastels`, `Macaron`, `Cotton Candy`, `Dreamcore`, `Weirdcore`, `Surreal Dream`, `Fairy-Tale Fantasy`, `Enchanted Forest`, `Fantasy Epic`, `Mysticism`, `Gothic Dark`, `Vampire Red`, `Fairy Fluorescence`, `Wandering Amusement Park`, `Childhood Picture Book`, `Milky Cloud`, `Plastic Toys`, `Jelly Transparency`, `Comic Youth`

**Eastern / Traditional / Cultural**
`Eastern Cinnabar`, `Eastern Blue-Green`, `Ink-Wash Black and White`, `Colored Ink Wash`, `Dunhuang Murals`, `Song-Dynasty Elegant Colors`, `Tang-Dynasty Rich Colors`, `New Chinese Style`, `Blue-and-White Porcelain`, `Jade Blue-White`, `Ancient-Architecture Vermilion`, `Zen Neutrals`, `Neo-Chinese Neon`, `Opera Splendor`, `Tea-Room Wood Tones`, `Old-Paper Bookish`, `Lacquer Black and Red`, `Porcelain-Glaze Blue-White`, `Miao Embroidery High Color`, `Tibetan Mineral Colors`

**Method / Zoning / Color Preservation**
`Local Grayscale Focus`, `Gray-Color Contrast`, `Single-Zone Desaturation`, `Local Cooling`, `Local Warm Compression`, `Main-Zone Fading`, `Color-Gray Narrative`, `Local Muting`, `Focus Color Retention`, `Dual-Zone Temperature Contrast`, `Three-Stage Progression`, `Monochromatic Layering`, `Complementary Collision`, `Analogous Transition`, `High-Contrast Zoning`, `Low-Saturation Zoning`, `Warm Zone with Cool Accent`, `Cool Zone with Warm Accent`, `Light-and-Shadow Color Separation`, `Material Color Separation`, `Spatial Color Separation`, `Emotional Reversal`, `Documentary Desaturation`, `Cinematic Zoning`, `Advertising Zoning`, `Magazine Zoning`, `Exhibition Zoning`, `Old-Paper Color Separation`, `Gray Base with Color Pop`, `Mist Color Separation`, `Theatrical Stage`, `Narrative Acts`, `Natural Neutral`, `Restrained Enhancement`, `Original-Color Preservation Enhancement`, `Single-Zone Grain Enhancement`, `Saturation-Imbalance Reconstruction`, `Single-Zone Inversion Accent`, `Black-and-White Subject / Color Background`, `Color Subject / Gray Background`, `Original-Gamut Compression`, `Original-Gamut Expansion`

**Travel / Lifestyle / Food / Commercial**
`Fresh Travel`, `Urban Travel`, `Road Trip`, `Humanistic Travel`, `Pastoral Nature`, `Caramel Warm Brown`, `Coffee Cinema`, `Amber Warm Light`, `Appetite Warm Colors`, `Fresh Food`, `Coffee Roasting`, `Milk-Tea Shop Poster`, `Convenience-Store Packaging`, `Tropical Poster`, `Beer Malt`, `Tavern Barrel`, `Vintage Tobacco Box`, `Jewelry Window`, `Cosmetics Poster`, `Product Tech`, `Product Trend`, `Product Luxury`

**Film / Stage / Music**
`Movie Trailer`, `Road Movie`, `Art-House Film`, `Suspense Film`, `Crime Film`, `Romance Film`, `Youth Film`, `Epic Film`, `Disaster Film`, `Stage Lighting`, `Music Festival`, `Jazz Night`, `Ballet Stage`, `Rock Live`, `Electronic Music`, `Theater Red Curtain`

### Text Direction Presets
> Concise descriptions and selection guidance are available in [`references/presets-text.md`](references/presets-text.md).

**Documentary / Information**
`News Headline`, `Newspaper Lead`, `Image Caption`, `News-Photo Caption`, `Documentary-Photo Description`, `Archival Record`, `Event Record`, `On-Site Record`, `Time-and-Place Record`, `Subject Identity Introduction`, `Subject Encyclopedia`, `Architecture Information Card`, `Landscape Information Card`, `Animal Observation Record`, `Plant Observation Record`, `Object Archive`, `Vehicle Archive`, `Photography Work Information`, `Photography Information Card`, `EXIF Parameters`, `Film Information`, `Aerial-Photography Information`, `Latitude/Longitude Coordinates`, `Geographic-Coordinate Archive`, `Weather Record`, `Travel Log`, `Itinerary Node`, `Numbered Archive`, `Chronological Record`, `Timeline Node`, `Specimen Label`, `Museum Label`, `Exhibit Plaque`, `Document Index`, `Survey Record`, `Field Survey Record`, `Research Sampling`, `Competition Information`, `Performance Information`, `Event Information`, `Meeting Record`, `Work Documentary`, `Engineering Record`, `Construction Milestone`, `Experiment Record`

**Keepsake / Check-In / Commemoration**
`Minimal Check-In`, `City Check-In`, `Attraction Check-In`, `Landmark Commemoration`, `Photography Check-In`, `Film Check-In`, `Travel Souvenir Photo`, `I Was Here`, `Arrived Today`, `Passed Through Here`, `Present in This Moment`, `City Coordinates`, `Map-Coordinate Check-In`, `Flight Travel`, `Ticket Souvenir`, `Climbing Commemoration`, `Seaside Check-In`, `Road Check-In`, `Old-Town Check-In`, `Campus Check-In`, `Graduation Keepsake`, `Classmate Group Keepsake`, `Cadre Group-Photo Keepsake Introduction`, `Organization Group Keepsake`, `Team Commemorative Photo`, `Family Group Keepsake`, `Friends Group Keepsake`, `Couple Travel Keepsake`, `Anniversary`, `Birthday Commemoration`, `First Meeting`, `Reunion Keepsake`, `Return to an Old Place`, `Return to Alma Mater`, `Hometown Record`, `Journey-Home Record`

**People Feature / Portrait**
`Person Name as Large Headline`, `Biographical Profile`, `Person Archive`, `Person Interview`, `Portrait Feature`, `Person Story`, `Person Quote`, `Person Manifesto`, `Person Tags`, `Person Keywords`, `Occupational Portrait`, `Worker Portrait`, `Youth Portrait`, `Elder Portrait`, `Child Portrait`, `Women’s Feature`, `Men’s Feature`, `Athlete Feature`, `Artist Feature`, `Musician Feature`, `Photographer Feature`, `Craftsperson Feature`, `Scholar Feature`, `Historical-Person Feature`, `Anonymous-Person Documentary`, `Group Portrait Feature`, `Generational Group Portrait`, `Urban People`, `Hometown People`, `Strangers Series`

**Literary / Poetic**
`Poetry or Classical Quote`, `Classical-Poetry Mood`, `Modern-Poetry Short Line`, `Free Verse`, `Prose Short Line`, `Literary Voiceover`, `Novel Opening`, `Novel Ending`, `Diary Fragment`, `Notebook Style`, `Letter Fragment`, `Unsent Letter`, `Literary Postcard`, `Poetic Place Name`, `Landscape Prose`, `Mountain-and-River Literature`, `Coastal Literature`, `Urban Literature`, `Road Literature`, `Railway Literature`, `Rainy-Day Literature`, `Literature of Wind`, `Light-and-Shadow Literature`, `Still-Life Literature`, `Plant Literature`, `Animal Literature`, `Architecture Literature`, `Old-Town Literature`, `Jiangnan Literature`, `Northern Literature`, `Western Literature`, `Island Literature`, `Hometown Literature`, `Rural Literature`, `Everyday Human Warmth`, `Traces of Time`, `Sense of Impermanence`, `Encounter Literature`, `Farewell Literature`, `Reunion Literature`, `Waiting Literature`, `Distant-Places Literature`, `Wandering Literature`, `Homecoming Literature`, `Memory Fragments`, `Dream Voiceover`, `Stream-of-Consciousness Short Line`, `Minimal Philosophy`, `Existentialism`, `Reflections on Life`, `Philosophy of Time`, `Philosophy of Space`

**Youth / Emotion**
`Youth Pain`, `Youth Film`, `Youth Diary`, `Boyish Youthfulness`, `Girlish Youthfulness`, `Campus Youth`, `Graduation Season`, `Summer Youth`, `Hot-Blooded Youth`, `Youth Confusion`, `Youth Regret`, `Secret Crush`, `First-Love Feeling`, `Heartbreak Monologue`, `Youth Leaving Home`, `Youth Ensemble`, `Youth Friendship`, `Youth Manifesto`, `Youth Rebellion`, `Youth Freedom`, `Young and Reckless`, `Unfinished Youth`, `Growing Pains`, `Before Adulthood`, `Twenty-Year-Old Literature`, `Midsummer Memory`, `After School`

**Love / Relationships**
`Minimal Love`, `Romance-Film Voiceover`, `Love-Letter Short Line`, `Secret-Crush Voiceover`, `First-Meeting Keepsake`, `Everyday Love`, `Couple Check-In`, `Long-Term Companionship`, `Long-Distance Relationship`, `Reunion Love`, `Farewell Love`, `Regretful Love`, `Wedding Vow`, `Wedding Commemoration`, `Anniversary Style`, `Love in Old Age`, `Family Affection`, `Father-Son Relationship`, `Mother-Daughter Relationship`, `Brotherhood`, `Friendship`

**Travel / Local Culture**
`City Card`, `City Impression`, `Local Gazetteer Style`, `Local Humanities`, `Local Customs`, `Regional Culture`, `Ancient-City Travelogue`, `Old-Town Travelogue`, `Street-and-Alley Observation`, `Old-City Memory`, `New-City Observation`, `Small-Town Story`, `Village Record`, `Fishing-Village Chronicle`, `Mountain-Village Chronicle`, `Border Travel`, `Island Travel`, `Road Trip`, `Railway Travel`, `Hiking Record`, `Mountaineering Log`, `Cycling Log`, `Self-Drive Log`, `City Walk`, `Night City Tour`, `Old-Street Walk`, `Street-Life Observation`, `Market Literature`, `Street-Side Shop`, `Cafe Record`, `Bookstore Record`, `Museum Check-In`, `Art-Museum Check-In`, `Architecture Tour`, `World-Heritage Style`

**History / Culture / Tradition**
`Historical Archive`, `Era Headline`, `Historical Event`, `Historical-Person Quote`, `Classical-Text Excerpt`, `Historical-Chronicle Style`, `Local History`, `Artifact Description`, `Intangible-Cultural-Heritage Introduction`, `Folk-Custom Record`, `Traditional Craft`, `Ancient-Architecture Inscription`, `Stele Inscription`, `Plaque Inscription`, `Couplet Style`, `Four-Character Title`, `Eight-Character Inscription`, `Painting-and-Calligraphy Colophon`, `Seal Inscription`, `Republican-Era Copy`, `Revolutionary-History Style`, `Historical-Propaganda-Poster Style`, `Family Old-Photo Style`, `Old-Album Caption`

**Film / Screen / Music**
`Film Title`, `Film Subtitle`, `Film Voiceover`, `Film Subtitles`, `Film-Dialogue Feel`, `End-Credit Style`, `Opening-Credit Style`, `Chapter Title`, `Trailer Copy`, `Crime-Film Title`, `Suspense-Film Title`, `Road-Movie Voiceover`, `Art-House-Film Voiceover`, `Youth-Film Voiceover`, `Romance-Film Voiceover`, `Documentary Title`, `Documentary Voiceover`, `Character Documentary`, `Album Title`, `Album Subtitle`, `Lyric-Like Short Line`, `Vinyl-Record Style`, `Concert-Poster Style`, `Music-Festival Style`, `Jazz Night`, `Rock Manifesto`

**Media / Editorial / Magazine**
`Magazine Cover`, `Person Magazine Cover`, `Fashion Magazine Cover`, `Photography Magazine`, `Travel Magazine`, `Architecture Magazine`, `Art Magazine`, `Sports Magazine`, `News Weekly`, `Feature Report`, `Cover Story`, `Editorial Lead`, `Column Title`, `Issue-Number Style`, `Newspaper Front Page`, `Newspaper Supplement`, `Culture Supplement`, `Photography Book`, `Exhibition Catalog`, `Curatorial Text`, `Editor’s Note`, `Column Commentary`, `Review-Headline Style`, `Image-Essay Style`

**Slogan / Manifesto / Strong Type**
`Minimal Slogan`, `Manifesto Style`, `Call to Action`, `Youth Manifesto`, `Sports Slogan`, `Team Slogan`, `City Slogan`, `Brand Manifesto`, `Life Attitude`, `Freedom Manifesto`, `Rebellion Manifesto`, `Power Manifesto`, `Victory Manifesto`, `Never Give Up`, `Push the Limit`, `Set Out Now`, `Stay Passionate`, `Look Forward`, `Grow Wild`, `Born Free`, `Undefined`, `Keep Running`, `Happening Now`

**Official / Collective / Formal**
`Cadre Group-Photo Keepsake Introduction`, `Leadership Field-Visit Documentary`, `Work-Meeting Documentary`, `Project-Inspection Documentary`, `Group-Photo Description`, `Symposium Documentary`, `Signing-Ceremony Documentary`, `Launch Ceremony`, `Unveiling Ceremony`, `Groundbreaking Ceremony`, `Completion Commemoration`, `Visit and Exchange`, `Academic Exchange`, `Alumni Group Photo`, `Class Group Photo`, `Graduation Group Photo`, `Award Commemoration`, `Competition Award Ceremony`, `Team-Building Commemoration`, `Volunteer-Activity Documentary`, `Public-Welfare Activity Documentary`

**Commercial / Product / Brand**
`Product Name Style`, `Product Parameters`, `Product Selling Points`, `New-Product Launch`, `Brand Story`, `Brand Slogan`, `Model Archive`, `Automotive Advertising`, `Camera Advertising`, `Watch Advertising`, `Perfume Copy`, `Fashion Editorial`, `Sneaker Trend`, `Interior Design`, `Food Packaging`, `Coffee Information`, `Alcohol Label`, `Handmade Brand`

**Nature / Scenery / Flora and Fauna**
`Landscape Title`, `Mountain Title`, `River Title`, `Coast Title`, `Lake Title`, `Forest Title`, `Wilderness Title`, `Landform Archive`, `Animal Card`, `Wildlife Documentary`, `Pet Portrait`, `Plant Card`, `Flower Title`, `Bird Observation`, `Marine-Life Observation`, `Nature Observation Notes`, `Nature Science Style`, `National-Geographic Style`, `Discovery-Channel Style`

**Art / Experimental / Conceptual**
`Concept Proposition`, `Artwork Title`, `Untitled Style`, `Numbered Artwork`, `Exhibition Proposition`, `Bilingual Art Title`, `English-Word Title`, `Latin-Flavored Title`, `Philosophical Proposition`, `Question Style`, `Rhetorical Question`, `Fragmented Text`, `Keyword Stack`, `Coordinate Numbering`, `System-Log Style`, `Data-Label Style`, `Glitch Text`, `Cipher Text`, `Annotation System`, `Handwritten Annotation`, `Draft Notes`, `Collaged Sentences`, `Flyer Fragment`, `Book Excerpt`, `Dictionary Definition`, `Encyclopedia Entry`, `Footnote Style`, `Quotation Style`, `Quotation-Centered`, `Blank Title`

### Aspect Ratio / Format Presets
> Concise descriptions and selection guidance are available in [`references/presets-aspect.md`](references/presets-aspect.md).

**Square / Square Formats**
`Record Cover`, `Square Poster`, `Square Social Post`, `Polaroid Square`, `Vinyl Inner Sleeve`, `Minimal Square Booklet`, `Nine-Grid Single Tile`, `Square Archive Card`, `Square Magazine Cover`, `Square Exhibition Label`, `Podcast Cover`, `Playlist Cover`, `Circular Record`, `Circular Avatar`, `Badge Composition`

**Classic Photography / Film**
`Classic Photography`, `Retro Film`, `35mm Film`, `Camera Original`, `Photography Book`, `Travel Photography`, `Street Photography`, `Humanistic Documentary`, `Film Diary`, `News Photography`, `Landscape Postcard`, `Exhibition Label Card`

**Traditional Television / 4:3**
`Classic Television`, `Old-TV Frame`, `Retro Video`, `Medium-Format Photography`, `Traditional Digital Camera`, `Photography Archive`, `Museum Catalog`, `Old-Newspaper Image`, `Surveillance Footage`, `Home Video`, `VHS Subtitle Frame`, `Research Record Image`

**Standard Widescreen / 16:9**
`Widescreen Photography`, `Film/TV Frame`, `Video Cover`, `Documentary Frame`, `Widescreen Landscape`, `Game Screenshot`, `Television Documentary`, `Horizontal Story Page`, `Cinema Promo Image`, `Display-Screen Frame`, `Horizontal Video Cover`, `Desktop Wallpaper`, `News-Live Frame`, `Sports-Broadcast Frame`, `Esports-Broadcast Frame`

**Cinematic Widescreen**
`Matted Cinema`, `Widescreen Cinema`, `CinemaScope`, `Cinema Letterbox`, `Road Movie`, `Western Widescreen`, `Epic Film`, `Art-House Film`, `Crime Film`, `Urban Film`, `Univisium Cinema`, `Modern Cinema`, `Streaming Series`, `Horizontal Movie Poster`, `Panoramic Narrative`, `Golden Widescreen`, `American Cinema`, `Classic Cinema`, `Drama Film`, `Art Film`, `European Cinema`, `Academy Ratio`, `Silent-Film Ratio`, `Old Cinema`, `IMAX Cinema`, `IMAX Digital`

**Mobile Vertical / Social**
`Vertical Cinema`, `Mobile Story`, `Short-Video Cover`, `Vertical Documentary`, `Mobile Wallpaper`, `Vertical Movie Poster`, `Vertical Travel Card`, `Vertical Person Close-Up`, `Vertical Architecture`, `Vertical Story Page`, `Instagram Story`, `Vertical Short-Video Cover`, `Phone Lock Screen`, `Full-Screen Wallpaper`

**Social Portrait / 4:5 / 3:4**
`Mobile Post`, `Portrait Social Image`, `Vertical Photography`, `Fashion Portrait`, `Magazine Person Page`, `Social Poster`, `Product Key Visual`, `Art Portrait`, `Check-In Photo`, `Youth Portrait`, `Instagram Portrait Post`, `Classic Poster`, `Vertical Poster`, `Person Feature`, `Architecture Feature`, `Art Poster`, `Documentary Cover`, `School Poster`, `Exhibition Key Visual`, `Competition Poster`, `Biographical Cover`, `Xiaohongshu Cover`, `Xiaohongshu Vertical Image`

**Classic Portrait / 2:3 / 5:4**
`Classic Portrait`, `Medium-Format Portrait`, `Art Portrait`, `Formal Group Photo`, `Product Photography`, `Album Portrait`, `Magazine Portrait`, `Classic Vertical`, `Vertical Film`, `Full-Body Portrait`, `Full-Height Architecture`, `Vertical Travel Photo`, `Literary Vertical Photo`, `Exhibition Poster`, `Vertical Movie Poster`, `Photography-Exhibition Poster`, `Book Cover`, `Novel Cover`, `Comic Cover`, `Game Cover`, `DVD Cover`

**Standard Paper / Print**
`A-Series Poster`, `A4 Flyer`, `A3 Poster`, `A2 Exhibition Poster`, `A1 Large Poster`, `B-Series Poster`, `Movie One-Sheet Poster`, `American Movie Poster`, `Japanese Movie Poster`, `Exhibition Invitation`, `Vertical Postcard`

**Banner / Ticket / Ultra-Wide**
`Ticket Stub`, `Movie Ticket`, `Train Ticket`, `Boarding Pass`, `Admission Ticket`, `Film Negative Strip`, `Film Contact Sheet`, `Panorama`, `Ultra-Panorama`, `City Skyline`, `Mountain-and-River Scroll`, `Eastern Handscroll`, `Banner Poster`, `Website Banner`, `Website Hero`, `Official-Account Header`, `Video-Channel Banner`, `LED Large Screen`, `Stage Backdrop`, `Exhibition Backdrop`, `Fan Support Hand Banner`, `Concert Hand Banner`, `Sports Support Banner`, `Stadium-Fence Banner`, `Fan Light Sign`, `Shop Sign`, `Storefront Advertising`, `Street Billboard`

**Long Image / Hanging Scroll / Ultra-Vertical**
`Mobile Long Image`, `Long Poster`, `Vertical Long Scroll`, `Eastern Hanging Scroll`, `Hanging-Scroll Poster`, `Tower Composition`, `Waterfall Long Image`, `Vertical LED Tower Screen`, `Elevator-Door Advertising`, `Building-Curtain-Wall Screen`

**Wallpaper / Screen**
`Tablet Wallpaper`, `Ultra-Wide Wallpaper`, `Dual-Screen Wallpaper`, `Esports Ultra-Wide`, `Exhibition Projection`, `Digital Signage`, `Information Display`, `Airport Display`, `Stadium Display`, `Circular-Screen Visual`

**Social / Platform / Advertising Formats**
`Instagram Square Post`, `Live-Stream Cover`, `Bus-Stop Advertising`, `Subway Lightbox`, `Mall Lightbox`, `Outdoor Giant Screen`, `Elevator Poster`, `Vehicle Wrap`, `Bus Advertising`, `Subway-Car Advertising`, `Construction-Hoarding Advertising`, `Architectural Hoarding`

**Booklet / Multi-Panel / Card**
`Diptych`, `Triptych`, `Two-Page Booklet`, `Magazine Spread`, `Photography Spread`, `Bi-Fold Flyer`, `Tri-Fold Visual`, `Foldout Scroll`, `Stamp Ratio`, `Collectible Card`, `Sports Card`, `Fan Support Card`, `Polaroid`, `ID Photo`, `Portrait Business Card`, `Horizontal Business Card`, `Vertical Business Card`, `Menu Card`, `Archive Card`, `Postcard Archive`, `Evidence Photo`

**Architecture / Product / Packaging**
`Architectural Elevation`, `Architectural Panorama`, `Interior Design Image`, `Product Detail Hero Image`, `E-Commerce Portrait Image`, `Square Product Image`, `Horizontal Food Menu Image`, `Packaging Front`, `Wine Label`, `Perfume Label`

**Special Composition / Irregular Safe Area**
`Sticker Composition`, `Stamp Border`, `Framed Photo`, `Folding-Screen Painting`, `Eastern Album Leaf`, `Fan-Shaped Composition`

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
