# Awesome GPT-Image-2 Prompts

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![Stars](https://img.shields.io/github/stars/Anil-matcha/Awesome-GPT-Store?style=flat-square)](https://github.com/Anil-matcha/Awesome-GPT-Store/stargazers)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](LICENSE)

A curated collection of high-quality prompts and output examples for **GPT-Image-2** via the OpenAI API. This repository is your go-to reference for prompt engineering with `gpt-image-2` — covering portraits, posters, UI mockups, character sheets, game screenshots, and more.

Whether you're building an image generation app, experimenting with the API, or looking for proven prompt patterns, you'll find ready-to-use prompts here that unlock GPT-Image-2's full potential.

Join subreddit https://www.reddit.com/r/gptimage2/ for discussions around GPT Image 2

> **Want to use GPT-Image-2 without an OpenAI account?** Try **[MuAPI](https://muapi.ai)** — a hosted API that gives you GPT-Image-2 text-to-image and image-to-image with a simple REST call. [Get your API key →](https://muapi.ai)

> **API Usage:** All prompts work with the [OpenAI Images API](https://platform.openai.com/docs/api-reference/images) using model `gpt-image-2`.

```python
import openai

client = openai.OpenAI()
response = client.images.generate(
    model="gpt-image-2",
    prompt="<paste any prompt from this list>",
    size="1024x1024",
    quality="high",
    n=1,
)
print(response.data[0].url)
```

---

## Related Projects

- [Generative-Media-Skills](https://github.com/SamurAIGPT/Generative-Media-Skills) — Run these prompts as AI agent skills in Claude Code, Cursor, and Gemini CLI
- [muapi-cli](https://github.com/SamurAIGPT/muapi-cli) — Run GPT-Image-2 prompts via CLI with MuAPI
- [ai-headshot-generator](https://github.com/SamurAIGPT/ai-headshot-generator) — Ready-made SaaS using GPT-Image-2 for professional headshots
- [nano-banana-generator](https://github.com/SamurAIGPT/nano-banana-generator) — Open-source SaaS for Nano Banana image generation
- [Free-AI-Social-Media-Scheduler](https://github.com/Anil-matcha/Free-AI-Social-Media-Scheduler) — Schedule your GPT-Image-2 generated visuals across all social platforms

## Why GPT-Image-2?

GPT-Image-2 is a significant leap over previous versions, offering:

- **Stronger world knowledge** — More accurate representations of real places, people, and scenes
- **Improved style fidelity** — Replicates specific art styles, game aesthetics, and UI patterns
- **Better prompt adherence** — Follows complex, multi-part instructions more reliably
- **Photorealistic output** — Generates images indistinguishable from real photographs or screenshots
- **Typography rendering** — Handles text-in-image far better than any prior generation model

---

## Table of Contents

- [Portrait & Photography](#portrait--photography)
- [Poster & Illustration](#poster--illustration)
- [Game & Entertainment Screenshots](#game--entertainment-screenshots)
- [UI / UX & App Mockups](#ui--ux--app-mockups)
- [Character Design & Reference Sheets](#character-design--reference-sheets)
- [Image Editing & Style Transfer](#image-editing--style-transfer)
- [Infographics & Typography](#infographics--typography)
- [Resources & API Docs](#resources--api-docs)
- [Contributing](#contributing)

---

## Portrait & Photography

Prompts for photorealistic portraits, editorial photography, and authentic candid-style images.

### Convenience Store Neon Portrait

**Prompt:**
```
35mm film photography with harsh convenience store fluorescent lighting mixed with colorful neon signs from outside, authentic film grain, high contrast, slight color cast, cinematic street editorial style, intimate medium shot, early 20s woman with ultra-realistic delicate features, seductive almond-shaped eyes with natural double eyelids, high nose bridge, small sharp V-shaped jawline, flawless porcelain skin with cool ivory undertone and visible specular highlights from fluorescent light, subtle skin texture and micro pores, natural dewy makeup with soft flush on cheeks, glossy natural pink lips slightly parted, long dark hair in a messy high ponytail with loose strands falling around face, wearing an oversized white button-up shirt loosely tied at the waist, paired with a tiny black pleated mini skirt, seductive casual leaning pose against the glass door of a 24-hour convenience store at late night, bright cold fluorescent store light from inside mixed with pink and blue neon glow from outside signs, realistic reflections on glass door, blurred convenience store interior in background, authentic 35mm film color grading, no plastic skin, no watermark, no text
```
**Source:** [@BubbleBrain](https://x.com/BubbleBrain)

---

### Cinematic Minimal Portrait

**Prompt:**
```
Generate a cinematic minimal portrait of a solitary man standing in an intense orange to red gradient environment, strong silhouette lighting, deep shadow contrast, reflective glossy floor, symmetrical composition, minimal
```
**Source:** [@iam_miharbi](https://x.com/iam_miharbi)

---

### Japanese Onsen Ryokan Portrait

**Prompt:**
```
35mm film photography, warm vintage Japanese onsen ryokan aesthetic, soft ambient wooden lantern lighting mixed with gentle natural window light, subtle film grain, gentle color shift, high atmosphere editorial style, intimate medium shot, early 20s woman with ultra-realistic delicate refined features, seductive almond-shaped fox eyes with natural double eyelids, flawless porcelain skin with warm ivory undertone, visible subtle skin texture, soft natural makeup with dewy glow, long dark hair tied in a loose low bun with some messy strands falling around face, wearing a loose white yukata deliberately slipped off one shoulder, warm wooden interior with paper sliding doors and distant steaming hot spring in soft focus, authentic vintage film color grading with warm tones, no plastic skin, no watermark, no text, authentic 35mm film Japanese onsen ryokan atmosphere
```
**Source:** [@BubbleBrain](https://x.com/BubbleBrain)

---

### Soft Airy 35mm Film Portrait

**Prompt:**
```
Analog 35mm film photography, soft airy Japanese-style aesthetic, gentle diffused natural window light, slight overexposure, pastel tones, low contrast, soft highlights, minimal indoor setting near a window with white curtains, clean light-colored wall, natural composition, eye-level, slightly closer full-body framing, young East Asian woman, natural minimal makeup, soft realistic skin texture, long slightly messy dark hair, oversized white button-up shirt, light casual shorts, barefoot, simple and relaxed styling, standing naturally with relaxed posture, facing camera, gentle soft smile, subtle stillness, focus on light, air, and quiet everyday mood, soft film grain, dreamy and understated atmosphere --ar 9:16
```
**Source:** [@BubbleBrain](https://x.com/BubbleBrain)

---

### Luxury Glam Beauty Portrait

**Prompt:**
```
Luxury Glam Beauty Portrait: Beautiful Black woman, youthful spirit, creamy vanilla, silk press, mahogany red, subtle confidence, textured fabric, sapphire blue, minimal jewelry, beachside breeze, lens flare effect, nostalgic, cinematic lens, symmetrical composition, soft focus, high fashion photography, monochromatic, dewy finish, mysterious tension, layered elements
```
**Source:** [@patrickassale](https://x.com/patrickassale)

---

### Mirror Selfie Bedroom Portrait

**Prompt:**
```
A stunning 18-year-old woman with a youthful, pure face and realistic skin texture, sitting on a cozy, slightly messy bed in her bedroom. She is taking a mirror selfie with a smartphone, capturing a natural and intimate moment. Wearing casual gray loungewear and neat white crew socks. Soft natural light (golden hour) streams in from a side window, creating a warm, moody, and cinematic atmosphere. 35mm lens, sharp focus on the subject in the mirror, depth of field with a beautifully blurred background (bokeh). Photorealistic, 8K, high resolution, studio quality, masterpiece. Aspect Ratio: 3:4.
```
**Source:** [@Shinning1010](https://x.com/Shinning1010)

---

### Korean Idol 3×3 Grid Portrait

**Prompt:**
```
9:16 vertical, Korean idol portrait photoshoot, 3x3 grid (nine frames), same person in all images, consistent facial features and styling, soft black mist filter effect, lowered contrast, blooming highlights, subtle glow around light sources
```
**Source:** [@BubbleBrain](https://x.com/BubbleBrain)

---

### CCD Camera Flash Candid

**Prompt:**
```
Mobile phone photo, old CCD camera aesthetic, harsh flash, grainy, dim messy indoor lighting, candid snapshot feeling, slight motion blur, young Korean female idol, soft innocent look
```
**Source:** [@BubbleBrain](https://x.com/BubbleBrain)

---

### Sam Altman Skatepark Snapshot

**Prompt:**
```
Sam Altman on a skateboard at a skatepark with no people.
```
**Source:** [@Malek1173989](https://x.com/Malek1173989)

---

### RAW iPhone Quality — Subway Station

**Prompt:**
```
Create a completely RAW quality, unprocessed, unedited image with full iPhone camera quality. A subway station in USA, a momentary blur. The subway is in motion. In front of the subway, there is an elderly woman and man.
```
**Source:** [@WolfRiccardo](https://x.com/WolfRiccardo)

---

### Apple Park Keynote Crowd Shot

**Prompt:**
```
Amateur iPhone photo at Apple Park during the iPhone 20 keynote, Tim Cook presenting on stage. Shot from the crowd at a distance
```
**Source:** [@patrickassale](https://x.com/patrickassale)

---

### Handwritten Notebook Photo

**Prompt:**
```
Amateur photo of an open notebook lying flat, filled with handwritten notes in black ballpoint pen. The handwriting is casual and slightly messy, like personal notes, natural imperfections, crossed out words, underlined headings. Shot from slightly above, natural daylight from a window, no flash. Casual desk setting, shot on iPhone
```
**Source:** [@patrickassale](https://x.com/patrickassale)

---

## Poster & Illustration

Prompts for creating high-quality posters, travel illustrations, city maps, and editorial artwork.

### Boston Spring City Poster

**Prompt:**
```
A striking Spring 2026 city poster for Boston with an elegant celebratory mood and a bold contemporary design. On a clean off-white textured background with large areas of negative space, a miniature single sculler rows across the lower right corner of the image on a narrow ribbon of reflective water. The wake from the oar sweeps upward in a dynamic calligraphic curve, gradually transforming into the Charles River and then into a dreamlike hand-painted panorama of Boston. Inside this flowing river-shaped composition are iconic Boston elements: the Back Bay skyline, Beacon Hill brownstones, Acorn Street, Boston Public Garden, Swan Boats, Zakim Bridge, Fenway-inspired details, historic brick architecture, harbor ferries, and the city's waterfront atmosphere. Soft morning fog, golden spring light, subtle festive accents in crimson and gold, rich detail, layered depth, sophisticated city-poster aesthetics, fresh and refined, visually powerful but not overcrowded. Elegant typography in the lower left reads "SPRING 2026" with a vertical slogan "BOSTON, A CITY OF RIVER, MEMORY, AND INVENTION", text clear and beautifully composed, premium graphic design, 9:16
```
**Source:** [@BubbleBrain](https://x.com/BubbleBrain)

---

### Vintage Amalfi Coast Travel Poster

**Prompt:**
```
Modern pencil illustration of a vintage travel poster depicting the Amalfi Coast, Italy, panoramic coastal cliff road scene, classic 1960s white car driving along a curved seaside road, deep blue Mediterranean sea with small sailboats, colorful pastel hillside village, bright blue sky with soft clouds, lemon tree branches with vibrant yellow lemons framing the foreground, warm summer sunlight, bold vibrant colors, retro 1950s travel poster style, cinematic composition, high detail, screen print texture, graphic illustration. Hand-drawn style with loose strokes and defined contours. High-contrast color palette, contemporary and decorative aesthetic.
```
**Source:** [@WolfRiccardo](https://x.com/WolfRiccardo)

---

### Futuristic Mandala Illustration

**Prompt:**
```
A near-future sci-fi version of a mandala — intricate geometric patterns mixed with holographic and cyberpunk aesthetics, glowing neon lines, deep space background, ultra-detailed symmetrical design
```
**Source:** [@4WEB1](https://x.com/4WEB1)

---

### Surreal Koi Nebula Illustration

**Prompt:**
```
A surrealist digital illustration with a low-angle upward perspective. A giant colorful koi fish swims through a dreamlike nebula, surrounded by vivid star clouds and bubbles. In the center of the frame stands a tiny human figure, back to the viewer, calmly gazing up at the massive koi looming overhead. Strong contrast in scale, ethereal and dreamlike atmosphere. 9:16 ratio
```
**Source:** [@liyue_ai](https://x.com/liyue_ai)

---

### Dreamy Watercolor Editorial Illustration

**Prompt:**
```
Watercolor illustration in a dreamy style of [subject], with light impressionist aesthetic, loose brushstrokes and translucent washes in tones of [color1] and [color2]. Soft blur over cold-pressed paper texture, delicate lighting, clean composition, minimalist approach, sense of calm, lightness and ephemeral beauty, high quality, editorial style.
```
**Source:** [@hmontilla_](https://x.com/hmontilla_)

---

### Science Encyclopedia Vertical Poster

**Prompt:**
```
Generate a high-quality vertical science popularization encyclopedia image based on [Theme].
```
**Source:** [@pfanis](https://x.com/pfanis)

---

### Epic Silhouette World Poster

**Prompt:**
```
A collectible epic poster featuring a character's side-profile silhouette. Inside the silhouette grows a complete world and iconic scenes. Overall style: cinematic poster meets dreamlike watercolor illustration. Quiet, grand, sacred, nostalgic. Paper grain, light haze, dry-brush strokes, premium negative space.
```
**Source:** [@Ghhhh3owi](https://x.com/Ghhhh3owi)

---

### Summer Citrus Soda Ad

**Prompt:**
```
Product advertising photo, seasonal summer product, carbonated beverage, name="Summer Citrus SODA", shape=500ml plastic bottle, research 2025 high-CTR drink ad designs and generate accordingly, aspect ratio 3:4
```
**Source:** [@old_pgmrs_will](https://x.com/old_pgmrs_will)

---

## Game & Entertainment Screenshots

Prompts that leverage GPT-Image-2's ability to replicate specific game aesthetics and generate authentic-looking gameplay screenshots.

### Hitman-Style In-Game Screenshot

**Prompt:**
```
A Hitman level where you are in the OpenAI HQ and your mission is to steal GPT-6 without getting caught
```
**Source:** [@flowersslop](https://x.com/flowersslop)

---

### GTA 6 In-Game Footage

**Prompt:**
```
GTA 6 in-game footage, very detailed, very realistic. Close-up shot taken from a stationary 4K monitor. (There's a slight blurriness in the image, as it feels like it was taken handheld). A wide, bright environment. Realistic details. The character is walking on the beach with a dog.
```
**Source:** [@WolfRiccardo](https://x.com/WolfRiccardo)

---

### Zelda: Tears of the Kingdom Scene

**Prompt:**
```
In the game Zelda TOTK, Link is in a custom e531 series train he built himself
```
**Source:** [@marmaduke091](https://x.com/marmaduke091)

---

### GTA San Andreas Gameplay Screenshot

**Prompt:**
```
Gameplay screenshot of a lion fighting against an NPC in GTA San Andreas
```
**Source:** [@flowersslop](https://x.com/flowersslop)

---

### Black Myth: Wukong Battle Scene

**Prompt:**
```
Generate a Black Myth: Wukong game scene where Wukong is knocked away by Erlang Shen
```

---

### Celebrities at a Movie Theater Counter

**Prompt:**
```
Sam Altman, Donald Trump, and Elon Musk working behind the counter of a busy movie theater
```
**Source:** [@flowersslop](https://x.com/flowersslop)

---

### Convenience Store Night Scene — Ultra Realistic

**Prompt:**
```
Create an ultra-realistic urban street group photo at a convenience store entrance at 10 PM on a summer night. 3-4 young people briefly chatting at the entrance, someone holding drinks, someone sitting on plastic outdoor chairs, someone standing looking at their phone. Bright white light streaming through the glass doors and windows, warm yellow street lights and distant car headlights outside. Characters in everyday clothes: T-shirts, shirts, shorts, jeans, sneakers. No influencer styling. Faces and postures must look like real pedestrians, not overly polished. Environment must include real convenience store elements: freezer stickers, promotional posters, trash cans, entrance mats, glass reflections, shared bikes on roadside. The image should look like an authentic life slice captured by a photographer in the city.
```

---

## UI / UX & App Mockups

Prompts for creating authentic-looking app interfaces, social media posts, and digital designs.

### One-Prompt UI Design System

**Prompt:**
```
Generate a complete UI design system for me in [style], including web pages, mobile screens, cards, controls, buttons, and other components
```
**Source:** [@austinit](https://x.com/austinit)

---

### Glassy UI Design System

**Prompt:**
```
Generate a glassy, translucent UI design system with frosted glass effects, soft shadows, and modern aesthetics. Include web, mobile, card, and button components.
```
**Source:** [@pfanis](https://x.com/pfanis)

---

### TikTok Live Stream Screenshot

**Prompt:**
```
Generate a realistic screenshot of a TikTok live stream featuring a content creator streaming to an active audience. Show viewer count, chat messages, reaction icons, and all standard live stream UI elements.
```

---

### YouTube Time Travel Video Screenshot

**Prompt:**
```
Screenshot of a YouTube video showing someone who time-traveled to the Middle Ages — complete with authentic YouTube UI, view count, video title, channel name, and comment section
```
**Source:** [@flowersslop](https://x.com/flowersslop)

---

### Historical Social Media Feed

**Prompt:**
```
"Song Dynasty People's Moments" / "SONG DYNASTY SOCIAL MEDIA FEED" — ancient and modern time-travel humor fusion interface. Simulate a mobile social media app, but all content is from the Song Dynasty. Avatar is a portrait of a Song Dynasty scholar. Username "Su Dongpo SuShi_Official". Post: "Just arrived in Huangzhou, demoted but feeling okay. Made Dongpo pork myself today, tastes amazing, recipe attached:" The attached image is a Gongbi-style close-up of Dongpo pork. Likes: "Huang Tingjian, Qin Guan, Fo Yin and 126 others". Comments: "Wang Anshi: Hehe" "Sima Guang: Still the same taste". Like icon replaced with Song Dynasty pattern. Status bar: "Great Song Mobile 5G" and "Third Year of Yuanfeng". Color scheme: dark mode + elegant Song Dynasty tones.
```
**Source:** [@Panda20230902](https://x.com/Panda20230902)

---

### E-Commerce App Homepage

**Prompt:**
```
Generate a high-fidelity mobile e-commerce app homepage screenshot. Extremely realistic interface with complete mobile app UI logic and commercial design sense. Top: status bar with time 9:41, 5G signal, battery icon. Search box area below. Main banner for a big sale promotion. 10-grid function area with icons. Below: flash sale module with countdown timer and product cards. Bottom: double-column product waterfall with at least 6 product cards, each with product image, title, price, monthly sales, shop name, rating. Bottom fixed Tab Bar. All text clear and readable, unified icons, realistic white space, card shadows, rounded corners. Must look like an authentic e-commerce app screenshot, not concept art.
```

---

### Music Player Interface

**Prompt:**
```
Create a high-fidelity music streaming app player interface screenshot, mobile portrait orientation, refined dark mode visuals. Background: album cover blurred diffused color. Center: large square album cover with subtle shadow and rounded corners. Top status bar. Navigation bar with back arrow and "Now Playing" title. Song name, artist, and album shown. Playback progress bar with current and total time. Control buttons: shuffle, previous, play/pause, next, repeat. Scrolling lyrics area with current line highlighted. Bottom: like, comment, download, add to playlist, share buttons. Overall must look like a directly publishable product interface.
```

---

### Momotaro Explainer Slide

**Prompt:**
```
Create an explainer slide presentation page for the Momotaro story, in a clean modern presentation style with clear visual hierarchy, icons, and infographic elements
```
**Source:** [@yammamon](https://x.com/yammamon)

---

## Character Design & Reference Sheets

Prompts for character consistency, anime expressions, and official-style character sheets.

### Anime Snapshot Conversion

**Prompt:**
```
Show me the attached image as a snapshot from an actual anime
```
**Source:** [@Thereallo1026](https://x.com/Thereallo1026)

---

### Official Character Reference Sheet

**Prompt:**
```
Based on this character and background, please create a character reference sheet similar to official design materials.
- Include three-view drawings: front, side, and back
- Add variations of the character's facial expressions
- Break down and display detailed parts of the clothing and equipment
- Add a color palette
- Include a brief explanation of the worldview setting
- Overall, use an organized layout (white background, illustration style)
High resolution, professional concept art style
```
**Source:** [@MANISH1027512](https://x.com/MANISH1027512) | [@Toshi_nyaruo_AI](https://x.com/Toshi_nyaruo_AI)

---

### Persona 5-Style Character Reference Card

**Prompt:**
```
Based on this character and background, create a character reference card in the style of Persona 5 setting materials.
- Includes three-view drawings: front, side, and back
- Add character facial expression variations
- Break down and display detailed parts of clothing and equipment
- Add a color palette
- Include a brief worldview description
- Overall use an organized layout (white background, illustration style), high resolution, professional concept art style
```
**Source:** [@iamrednightS](https://x.com/iamrednightS)

---

### 16-Panel Anime Expression Grid

**Prompt:**
```
Create a 16-panel expression grid of a silver-haired, blue-eyed anime girl. Her face shape, hairstyle, and clothing must remain highly consistent across all panels. The 16 expressions should include: happy, sad, angry, surprised, shy, speechless, evil grin, contemplative, curious, proud, wronged, disdainful, confused, scared, crying, and a heart expression.
```

---

### Gal Game Character Introduction Page

**Prompt:**
```
Using this chibi illustration and standing portrait, create a character introduction page that looks like a real website page — specifically a high-quality galge (visual novel) character introduction page. Should include: facial expression variations, a CG illustration, a chibi version, and the following info:

Name: [name here]
Image color: [color here]
Height: [height] cm
Weight: [weight] kg
Catchphrase: "[quote here]"
```
**Source:** [@09lyco](https://x.com/09lyco)

---

## Image Editing & Style Transfer

Prompts for reference-based generation, style transfer, and creative remixing.

### Pet Brand Collaboration Poster

**Prompt:**
```
Theme: "[Pet name] X KFC" collaboration poster. Generate a collaboration poster featuring the same pet (absolutely consistent in appearance and coloring) with KFC brand identity (red-white color scheme, classic logo, restaurant scenes). Have the pet wear a KFC employee uniform and hat, standing at the counter, selling fried chicken, burgers, and meals, interacting with chicken buckets, fries, soda, and other elements. Style should be lively and fun with a commercial collaboration feel, suitable for online promotion and event posters.
```

---

### Comic Page Colorization & Translation

**Prompt:**
```
Colorize this comic page and translate it into English, placing the translated text in the original speech bubble positions while maintaining the composition and image details consistently
```

---

### Movie Collage — Single Output

**Prompt:**
```
Entire Superman movie image collage, one shot, combined in a single output image
```
**Source:** [@chetaslua](https://x.com/chetaslua)

---

## Infographics & Typography

Prompts for creating detailed infographics, posters with text, and data-rich visual designs.

### Chinese Tea Drink Product Launch Poster

**Prompt:**
```
Design a 3:4 vertical poster for a new artisan tea drink launch. Brand name: "Mountain River Tea". Style: New Chinese aesthetic, light luxury, restrained. Colors: dark green, off-white, gold. Incorporate rice paper texture, negative space, elegant landscapes, modern layout design. Main subject: a visually appealing cold brew tea with tea leaves, citrus, ice cubes, and gold foil elements. The poster must accurately display this text hierarchy: brand name, product name, series name, launch tagline, limited-time price (medium and large sizes), in-store promotions, flavor descriptors, campaign dates, and QR code section. Requirements: Clear promotional hierarchy while maintaining sophistication, not cheap e-commerce style. Focus on small text, numbers, prices, info modules, and Chinese font aesthetics.
```

---

### Coffee Journey Infographic

**Prompt:**
```
Infographic poster themed "How a Cup of Coffee Reaches You". Style: High-end information design with educational and commercial visual appeal, clear layout with path arrows, data boxes, icons, simple illustrations, and modular cards. Color scheme: coffee brown, milk white, ink black, copper accents. Must include: 01 Planting (elevation 1200–2200m, temperature 18–24°C, harvest season), 02 Processing (sun-dried, washed, honey process), 03 Roasting (light = brighter, medium = balanced, dark = richer), 04 Grinding (pour-over = coarse, espresso = fine, cold brew = medium-coarse), 05 Extraction (ratio, temperature, time all affect flavor), flavor keywords (floral/citrus/nutty/caramel/chocolate/smoky). Must look like a high-quality display board, not a classroom slide.
```

---

### Character Relationship Diagram

**Prompt:**
```
Please generate a key character relationship diagram for "[Work Title]" — a visually compelling, design-forward relationship map poster showing all major characters, their relationships, and key plot connections.
```
**Source:** [@MrLarus](https://x.com/MrLarus) | [@yihui_indie](https://x.com/yihui_indie)

---

### Museum Catalog-Style Infographic

**Prompt:**
```
Please automatically generate a "museum catalog-style disassembly infographic" based on [Subject].

The image must combine a realistic main visual, structural disassembly, annotations, material descriptions, pattern meanings, color meanings, and core feature summaries. Automatically determine the most appropriate subject structure, style, key components, material craftsmanship, color scheme, and layout.

Overall style: national museum exhibition board, historical catalog, cultural/museum thematic infographic — NOT a poster, portrait, e-commerce page, or anime illustration. Background: paper texture (off-white, silk white, or light tea color). The layout is fixed as:
- Top: main title + subtitle + introduction
- Left: Structural disassembly area with annotated lead lines and close-up details
- Upper right: Material / craftsmanship / texture area with real texture samples
- Middle right: Pattern / color / meaning area with color palette, pattern samples, and cultural explanations
- Bottom: Composition flowchart + core feature summary

All text must be clear, neat, and readable. Focus on highlighting real structures, material differences, cultural explanations, and a catalog atmosphere.
```
**Source:** [@MrLarus](https://x.com/MrLarus)

---

### High-End Skincare Product Poster

**Prompt:**
```
High-end skincare e-commerce hero poster for "Clarifying Stabilizing Essence". Style: Clean, light luxury, strong scientific skincare feel. Center: a semi-transparent frosted glass essence bottle with golden liquid and water droplet reflections. Background: off-white to warm gray gradient with liquid flow and microscopic molecular structure decorations. Must include clearly readable copy with: product name, tagline (barrier repair, soothe redness, radiant skin), formula generation, key ingredients (ceramide, panthenol B5, centella extract, micro-liposomes), suitable skin types (sensitive, sleep-deprived, seasonal-instability skin), limited-time price, and gift bundle details. Fine print: "Individual results may vary, use consistently." Overall must be high-end, not tacky.
```

---

### Extreme Perspective Typography Poster

**Prompt:**
```
Scene: Side view of a cross-sea bridge, dramatic cinematic angle. Giant bold sans-serif text "[text]" painted onto the surface of the bridge, progressively foreshortened from near to far end, letterforms conforming to surface curvature, surface-integrated not floating. Text partially occluded by foreground elements, creating depth-layering effect. Oversized bright yellow + sharp orange outline, extreme perspective distortion aligned to vanishing point. Cinematic lighting, motion blur, poster-grade dynamic integrated typography, modern advertising aesthetics.
```
**Source:** [@xpg0970](https://x.com/xpg0970)

---

## Resources & API Docs

### Official API References
- [OpenAI GPT-Image-2 Documentation](https://platform.openai.com/docs/guides/image-generation)
- [OpenAI Images API Reference](https://platform.openai.com/docs/api-reference/images)
- [OpenAI Pricing](https://openai.com/api/pricing)

### API Quick Reference

```python
# Standard generation
response = client.images.generate(
    model="gpt-image-2",
    prompt="your prompt here",
    size="1024x1024",      # 1024x1024, 1536x1024, 1024x1536, auto
    quality="high",         # standard, high
    n=1,
)

# Image editing (inpainting)
response = client.images.edit(
    model="gpt-image-2",
    image=open("original.png", "rb"),
    mask=open("mask.png", "rb"),
    prompt="your edit prompt here",
)
```

### Prompt Engineering Tips

1. **Be specific about style** — Mention film stock (35mm), camera type (iPhone, CCD), or art movement
2. **Describe lighting explicitly** — "harsh fluorescent mixed with neon glow" beats "good lighting"
3. **Specify aspect ratio** — Add `--ar 9:16` or `aspect ratio 3:4` for non-square outputs
4. **Use negative cues** — "no plastic skin, no watermark, no text" helps avoid common artifacts
5. **Reference real-world context** — Mention specific games, apps, or brands for style replication
6. **Layer details** — GPT-Image-2 handles long, detailed prompts better than shorter ones

---

## Use GPT-Image-2 via MuAPI

[MuAPI](https://muapi.ai) provides GPT-Image-2 as a hosted API — no OpenAI account required. Supports both text-to-image and image-to-image (editing).

### Text-to-Image

```python
import httpx, time

API_KEY = "your-muapi-key"
BASE = "https://api.muapi.ai/api/v1"

# Submit
resp = httpx.post(
    f"{BASE}/gpt-image-2-text-to-image",
    headers={"x-api-key": API_KEY},
    json={"prompt": "A photorealistic image of a red panda in a bamboo forest at golden hour"},
)
request_id = resp.json()["request_id"]

# Poll
while True:
    result = httpx.get(f"{BASE}/predictions/{request_id}/result", headers={"x-api-key": API_KEY}).json()
    if result["status"] == "completed":
        print(result["outputs"])
        break
    time.sleep(3)
```

### Image-to-Image (Editing)

```python
# Upload your source image first
with open("source.png", "rb") as f:
    upload = httpx.post(f"{BASE}/upload_file", headers={"x-api-key": API_KEY}, files={"file": f})
image_url = upload.json()["url"]

# Submit edit
resp = httpx.post(
    f"{BASE}/gpt-image-2-image-to-image",
    headers={"x-api-key": API_KEY},
    json={"prompt": "Turn this into a watercolor painting", "image_url": image_url},
)
request_id = resp.json()["request_id"]
```

Get your API key at [muapi.ai](https://muapi.ai).

---

## Contributing

Contributions are welcome! Submit a Pull Request to add your best GPT-Image-2 prompts.

**Guidelines:**
- Include the full prompt text
- Provide the source link (X/Twitter, blog, etc.) if applicable
- Categorize appropriately
- Example images are encouraged but not required

---

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=Anil-matcha/Awesome-GPT-Store&type=Date)](https://star-history.com/#Anil-matcha/Awesome-GPT-Store&Date)

---

## License

This project is licensed under the Creative Commons Attribution 4.0 International License — see the [LICENSE](LICENSE) file for details.

*Community-maintained. Not affiliated with OpenAI.*
