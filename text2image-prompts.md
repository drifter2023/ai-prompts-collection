# 文生图 (Text-to-Image) Prompt 合集

*整合自: civitai-prompts.md, gemini-prompts.md*
*分类方式: 按主题/对象分类，跨平台重复条目合并*

---

## 目录

- [人像 / 人物](#人像--人物)
- [动物](#动物)
- [建筑 / 室内](#建筑--室内)
- [产品](#产品)
- [食物](#食物)
- [奇幻 / 科幻](#奇幻--科幻)
- [动漫 / 游戏角色](#动漫--游戏角色)
- [营销 / 设计](#营销--设计)
- [旅游](#旅游)
- [绘本](#绘本)
- [方法与技巧](#方法与技巧)
- [模板](#模板)

---

## 人像 / 人物

### 复古 80s 动漫女孩

**平台:** Civitai (#1, #2) | **模型:** waiIllustriousSDXL_v160

**Prompt (半身):**
```
<lora:Rogue80sIllustrious1.0JLFO-000015:0.85>  r0gue, 1girl, retro artstyle, bodysuit, white hair, red hair, jacket, multicolored hair, long hair, solo, gloves, yellow bodysuit, headband, two-tone hair, belt, green bodysuit,smile, makeup, lipstick, breasts,clenched hand, looking at viewer, hand on own hip, cowboy shot, simple background,, masterpiece, best quality, amazing quality, very aesthetic,...
```

**Prompt (上半身):**
```
<lora:Rogue80sIllustrious1.0JLFO-000015:1.0>  r0gue, 1girl, retro artstyle, bodysuit, white hair, red hair, jacket, multicolored hair, long hair, solo, yellow bodysuit, headband, two-tone hair, , green bodysuit,smile, makeup, lipstick,grin,   simple background,, masterpiece, best quality, amazing quality, very aesthetic, absurdres, upper body, portrait, looking at viewer, simple background,
```

**Negative:** `patreon username, patreon logo, artist name, signature,`

---

### 动漫女孩与巨龙

**平台:** Civitai (#5) | **模型:** sweethoneyIllus_v20

**Prompt:**
```
An anime-style illustration of a serene moment: a young-adult woman with short purple hair and purple eyes, wrapped in a white towel, sitting on a rocky ledge with her feet in a calm body of water, a massive dark dragon looming in the background, its red-glowing maw open, mountains in the distance, a misty atmosphere, soft diffused lighting, cool color palette dominated by grays, blues, and purple...
```

**Negative:** `watermark, text, nsfw, worst quality, bad quality, low quality, kids, children, lowres, anatomical nonsense, artistic error, bad anatomy, interlocked fingers, extra fingers, text, artist name, signatu...`

---

### 萨满少女 (纹身与头饰)

**平台:** Civitai (#8) | **模型:** sweethoneyIllus_v20

**Prompt:**
```
, masterpiece, best quality, good quality, very aesthetic, absurdres, newest, 8K, depth of field, focused subject, 1girl, solo, hoop earrings, black hair, exotic hair, (hair ornament:1.4), detailed headdress, exotic headdress, glowing hair, feather, dreadlocks, (shaman), long hair, back tattoo, looking at viewer, from side, blunt bangs, upper body, arm tattoo, dragon tattoo, eastern dragon, should...
```

**Negative:** `nsfw, worst quality, bad quality, low quality, lowres, anatomical nonsense, artistic error, bad anatomy, interlocked fingers, extra fingers, text, artist name, signature, bad feet, extra toes, ugly, p...`

---

### 电影级写实人像

**平台:** Civitai (#9) / Gemini (#7) / Nano Banana (#12)

**Civitai Prompt:** (模型: SDXL / FLUX)
```
cinematic portrait of a confident young woman, atmospheric lighting, shallow depth of field, creamy bokeh, 85mm lens look, realistic skin texture, natural color grading, ultra detailed, masterpiece, best quality
```
**Negative:** `lowres, blurry, bad anatomy, deformed face, extra fingers, watermark, text, logo, oversaturated`

**Gemini 模板:**
```
Create a cinematic portrait of {subject}. Use atmospheric lighting, shallow depth of field, natural skin texture, and a realistic 85mm lens look. Keep colors filmic and balanced, with soft background bokeh. High detail, professional photography style.
```
示例: `Create a cinematic portrait of a female violinist backstage, warm tungsten practical lights, subtle haze, realistic 85mm look, shallow DOF, filmic contrast.`

**Nano Banana Prompt:**
```
Create a hyper-real cinematic portrait of a {subject}, with natural skin texture, subtle film grain, 85mm lens compression, soft bokeh, atmospheric practical lighting, and balanced filmic color grading. Keep the face anatomically correct and highly detailed.
```

---

### 梦幻粉彩人像

**平台:** Civitai (#10) / Gemini (#8)

**Civitai Prompt:** (模型: SDXL)
```
ethereal portrait, soft pastel colors, dreamlike atmosphere, volumetric lighting, gentle glow, elegant composition, highly detailed, masterpiece
```
**Negative:** `harsh shadows, noisy image, low quality, distorted eyes, extra limbs, watermark, text`

**Gemini 模板:**
```
Generate an ethereal portrait of {subject} with soft pastel color palette, dreamlike atmosphere, volumetric light rays, and delicate highlights. Keep the mood calm, elegant, and poetic.
```
示例: `Generate an ethereal portrait of a young dancer in a pale pink dress, pastel lavender and peach tones, volumetric morning light, soft haze, elegant mood.`

---

### 赛博朋克女性改造人

**平台:** Civitai (#11) / Gemini (#9) / Nano Banana (#17)

**Civitai Prompt:** (模型: FLUX / SDXL + cyberpunk LoRA)
```
ultra-detailed cinematic portrait of a female cyborg, navy and white metallic limbs, exposed internal machinery, sharp facial features, intense expression, sci-fi concept art, dramatic rim light, clean background, 8k, masterpiece
```
**Negative:** `cartoonish, low detail, muddy textures, bad hands, extra fingers, watermark, text, logo`

**Gemini 模板:**
```
Design a futuristic cyberpunk character: {subject}. Include visible mechanical details, layered materials, high micro-texture fidelity, dramatic rim lighting, and clean composition suitable for concept art presentation.
```
示例: `Design a futuristic cyberpunk female engineer with white-blue prosthetic arms, exposed servos, tactical jacket, dramatic rim light, high detail concept art.`

**Nano Banana Prompt:**
```
Design a cyberpunk character concept of {subject}, layered technical costume, visible mechanical details, neon edge lighting, moody urban background, realistic materials, high-detail concept art finish.
```

---

### 35mm 胶片街头情侣

**平台:** Civitai (#12) | **模型:** SDXL photoreal checkpoints

**Prompt:**
```
high resolution candid shot of a couple hugging on a busy street, 35mm film look, Kodak Portra 400 tone, subtle motion blur, authentic emotion, cinematic lighting, detailed environment
```

**Negative:** `plastic skin, overprocessed, low quality, blur face, duplicate body, watermark, text`

---

### 水墨插画 — 末日女孩

**平台:** Civitai (#6)

**Prompt:**
```
High contrast black and white ink illustration, post apocalyptic ruined city canyon with collapsed buildings, twisted rebar and broken concrete, a cute woman named Elle -  long braid, simple dress and sneakers, calm innocent smile - is hugging a monster that is adorable yet terrifying, round plush like body with multiple big glossy eyes, one huge main eye and several smaller eyes around it, massiv...
```

---

### Nano Banana 时尚大片 (Editorial)

**平台:** Nano Banana (#13)

**Prompt:**
```
Generate a high-fashion editorial image of {subject} in a {location}, strong composition, dramatic rim lighting, clean wardrobe styling, premium magazine aesthetic, realistic fabric texture, sharp focus on subject.
```

---

### Nano Banana 儿童绘本插画风人物

**平台:** Nano Banana (#19)

**Prompt:**
```
Illustrate a warm storybook scene of {subject}, soft brush textures, gentle pastel palette, friendly expressions, cozy lighting, whimsical composition suitable for children's books.
```

---

### 黑白艺术人像（展览风）

**平台:** Nano Banana (#47)

**Prompt:**
```
Create a fine-art black-and-white portrait of {subject}, rich tonal range, sculpted light, deep contrast control, gallery print quality.
```

---

### 纪录片风街头抓拍

**平台:** Nano Banana (#48)

**Prompt:**
```
Generate a documentary-style street photograph of {scene}, authentic moment, natural imperfections, realistic motion cues, cinematic reportage tone.
```

---

### Gemini 写实人像模板

**平台:** Gemini/Imagen 3

**模板:**
```
photorealistic portrait of {subject}, {lighting}, {camera}, detailed skin texture, {background}, 8k, professional photography
```

**示例:**
- `a young woman with flowing red hair, golden hour sunlight, 85mm f/1.4 lens, bokeh garden background`
- `an elderly craftsman, soft window light, medium format film look, workshop background`
- `a child playing in autumn leaves, dappled sunlight, 50mm lens, shallow depth of field`

---

## 动物

### 睡猫

**平台:** Civitai (#4) | **模型:** sweethoneyIllus_v20

**Prompt:**
```
realistic, solo, cat, cute, sleeping, light_particles, nature, mountain, depth of field, the best quality, amazing quality, high quality, masterpiece,
```

**Negative:** `watermark, text, nsfw, worst quality, bad quality, low quality, kids, children, lowres, anatomical nonsense, artistic error, bad anatomy, interlocked fingers, extra fingers, text, artist name, signatu...`

---

### 麦克风狗

**平台:** Civitai (#7) | **模型:** waiANINSFWPONYXL_v140

**Prompt:**
```
<lora:Menchi_-_Excel_Saga (1):1>,  menchi, dog, no humans, spotlight, microphone, microphone stand, sitting, music, animal, instrument, stage, animal focus, solo, sheet music on stand, standing in front of microphone
```

---

### 宠物肖像（商业摄影感）

**平台:** Nano Banana (#44)

**Prompt:**
```
Create a studio-quality pet portrait of {pet type}, catchlight in eyes, clean backdrop, detailed fur texture, premium portrait lighting.
```

---

## 建筑 / 室内

### 梵蒂冈城航拍

**平台:** Civitai (#3)

**Prompt:**
```
Cinematic photorealistic aerial bird eye view from far away, Saint Peters Square in Vatican City at sunrise, the vast oval piazza and sweeping marble colonnades dominate the frame with Saint Peters Basilica glowing in the background, soft golden morning light and pastel sky, long clean shadows across the cobblestones and gentle mist in the air, two tiny beautiful nuns in black and white habits are...
```

---

### 现代极简建筑

**平台:** Civitai (#13) / Gemini (#10) / Nano Banana (#14)

**Civitai Prompt:** (模型: SDXL / architecture models)
```
architectural visualization of a modern minimalist house, glass and concrete materials, sunset lighting, clean composition, realistic shadows, ultra detailed, unreal engine quality
```
**Negative:** `cluttered scene, lowres, bad perspective, warped geometry, noisy render, watermark, text`

**Gemini 模板:**
```
Render a modern architectural scene of {building/space}, emphasizing material realism (glass, concrete, wood), accurate perspective, soft global illumination, and sunset cinematic color grading.
```
示例: `Render a minimalist hillside villa with exposed concrete and floor-to-ceiling glass, sunset GI lighting, clean landscaping, magazine-quality architectural visualization.`

**Nano Banana Prompt:**
```
Render a modern minimalist architectural scene: {building type}, concrete + glass + wood materials, accurate perspective, global illumination, sunset atmosphere, ultra-clean composition, publication-ready quality.
```

---

### Gemini 建筑与室内模板

**平台:** Gemini/Imagen 3

**模板:**
```
{style} {space}, {materials}, {lighting}, {atmosphere}, architectural photography, 8k render
```

**示例:**
- `modern minimalist living room, concrete and warm wood, floor-to-ceiling windows, golden hour light`
- `cozy library interior, mahogany and leather, warm ambient lighting, hygge atmosphere`
- `futuristic sci-fi interior, sleek white surfaces, holographic displays, cool blue ambient light`

---

### 客厅室内设计效果图

**平台:** Nano Banana (#30)

**Prompt:**
```
Render a modern living room interior with {style keywords}, physically plausible daylight, balanced warm accents, realistic materials, architecture magazine quality.
```

---

### 厨房室内设计效果图

**平台:** Nano Banana (#31)

**Prompt:**
```
Generate a high-end kitchen visualization, matte cabinetry, stone countertop, indirect lighting, realistic appliance finish, clean architectural composition.
```

---

### 房地产封面图（外立面）

**平台:** Nano Banana (#32)

**Prompt:**
```
Create a real-estate hero render of a contemporary residential facade at golden hour, believable landscaping, clean lines, inviting atmosphere, brochure-ready.
```

---

## 产品

### 奢侈香水产品图

**平台:** Civitai (#14) / Gemini (产品摄影模板)

**Civitai Prompt:** (模型: SDXL)
```
commercial product photography of a luxury perfume bottle, frosted glass with gold accents, controlled studio lighting, soft gradient background, sharp focus, reflective highlights, premium advertising style, 8k
```
**Negative:** `low quality, dirty background, incorrect labels, distorted bottle shape, watermark, text, logo artifacts`

**Gemini 产品摄影模板:**
```
professional product photo of {product}, {material}, {lighting}, {background}, commercial photography, sharp focus, 8k
```
示例:
- `luxury perfume bottle, frosted glass and gold accents, soft studio lighting, gradient background`
- `minimalist watch, brushed titanium, dramatic side lighting, pure white background`
- `artisan coffee cup, ceramic with hand-painted glaze, natural morning light, rustic wooden table`

---

### Nano Banana 产品广告图

**平台:** Nano Banana (#15)

**Prompt:**
```
Create a premium product hero shot of {product}, studio three-point lighting, soft gradient background, crisp reflections, fine material detail, luxury commercial photography style, 8k clarity.
```

---

### 电商白底主图（标准）

**平台:** Nano Banana (#23)

**Prompt:**
```
Generate a clean e-commerce product image of {product} on a pure white background, centered composition, soft shadow, accurate color reproduction, sharp edges, realistic material texture, catalog-ready.
```

---

### 电商氛围主图（高级感）

**平台:** Nano Banana (#24)

**Prompt:**
```
Create a premium e-commerce hero image of {product} in a minimal luxury setting, soft directional light, controlled reflections, elegant props, high-end brand tone.
```

---

### 电商细节特写（材质卖点）

**平台:** Nano Banana (#25)

**Prompt:**
```
Produce a macro close-up of {product detail}, emphasizing material texture, micro-scratches/fabric weave, precise highlights, commercial retouch quality.
```

---

### 美妆产品广告（液体/玻璃）

**平台:** Nano Banana (#26)

**Prompt:**
```
Generate a beauty product ad for {cosmetic product}, translucent liquids and glass textures, glossy highlights, clean gradient backdrop, editorial beauty lighting.
```

---

### 珠宝广告（高反光控制）

**平台:** Nano Banana (#27)

**Prompt:**
```
Create a luxury jewelry campaign image of {jewelry type}, black-to-charcoal background, precise specular control, gemstone sparkle, ultra-clean premium composition.
```

---

### 服饰平拍转大片

**平台:** Nano Banana (#28)

**Prompt:**
```
Generate a fashion campaign visual for {garment}, model in confident pose, realistic fabric drape, magazine-style lighting, modern editorial color grading.
```

---

### 鞋类广告（动势）

**平台:** Nano Banana (#29)

**Prompt:**
```
Create a dynamic footwear ad for {shoe model}, suspended motion, directional light streaks, crisp outsole details, sporty premium aesthetic.
```

---

## 食物

### Gemini 食物摄影模板

**平台:** Gemini/Imagen 3

**模板:**
```
food photography of {dish}, {presentation}, {lighting}, {props}, appetizing, 8k, editorial style
```

**示例:**
- `fresh sushi platter, elegant minimalist presentation, soft diffused light, bamboo mat and chopsticks`
- `rustic sourdough bread, crusty texture visible, warm side lighting, linen napkin and olive oil`
- `colorful smoothie bowl, overhead flat lay, bright natural light, fresh fruits scattered around`

---

### Nano Banana 食物商业摄影

**平台:** Nano Banana (#16)

**Prompt:**
```
Generate an appetizing food editorial image of {dish}, realistic steam/moisture detail, natural highlights on texture, soft side lighting, shallow depth of field, table styling with minimal props.
```

---

### 菜品海报（餐饮营销）

**平台:** Nano Banana (#41)

**Prompt:**
```
Generate a restaurant promotion image for {dish}, appetizing textures, warm directional light, shallow depth, garnish detail, menu-poster composition.
```

---

### 饮品广告（冰感与气泡）

**平台:** Nano Banana (#42)

**Prompt:**
```
Create a beverage advertisement of {drink}, visible condensation droplets, sparkling highlights, translucent liquid realism, refreshing summer mood.
```

---

## 奇幻 / 科幻

### Gemini 奇幻与科幻模板

**平台:** Gemini/Imagen 3

**模板:**
```
{genre} scene of {subject}, {environment}, {lighting}, {mood}, highly detailed, cinematic, 8k
```

**示例:**
- `epic fantasy, dragon perched on castle tower, stormy skies, lightning illumination, dramatic atmosphere`
- `cyberpunk street, neon signs reflecting on wet pavement, night rain, blade runner aesthetic`
- `underwater city, bioluminescent lights, ethereal blue glow, mysterious and serene`

---

### Nano Banana 奇幻史诗场景

**平台:** Nano Banana (#18)

**Prompt:**
```
Create an epic fantasy scene featuring {subject}, grand scale environment, volumetric light shafts, cinematic depth, rich atmospheric perspective, painterly realism, highly detailed world-building.
```

---

### 科技发布会主视觉

**平台:** Nano Banana (#38)

**Prompt:**
```
Create a futuristic tech keynote hero background for {product category}, abstract geometric forms, volumetric glow, corporate blue palette, minimal but dramatic.
```

---

## 动漫 / 游戏角色

### 动漫角色立绘（全身）

**平台:** Nano Banana (#33)

**Prompt:**
```
Generate a full-body anime character illustration of {character concept}, clean silhouette, expressive face, controlled cel-shading, detailed costume design, transparent-background-ready framing.
```

---

### 动漫场景插画（电影感）

**平台:** Nano Banana (#34)

**Prompt:**
```
Create a cinematic anime environment scene in {location}, layered depth, atmospheric particles, dramatic sky, painterly background with clean focal subject.
```

---

### 游戏角色卡面（RPG）

**平台:** Nano Banana (#35)

**Prompt:**
```
Design a collectible RPG character card art of {class/role}, iconic pose, fantasy UI-friendly composition, rich texture detail, high readability at small size.
```

---

### 角色一致性模板（同人设多场景）

**平台:** Nano Banana (#36)

**Prompt:**
```
Use the same character identity across scenes: {character DNA: face shape, hairstyle, eye color, outfit core}. Generate {scene}, preserving identity traits consistently, only changing environment and pose.
```

---

## 营销 / 设计

### 品牌海报（留白排版）

**平台:** Nano Banana (#20, #37)

**Prompt (通用):**
```
Generate a modern advertising poster for {brand/topic}, keep a clear negative space area for typography, bold visual hierarchy, cinematic background treatment, clean composition, high-contrast focal point.
```

**Prompt (Key Visual):**
```
Generate an advertising key visual for {campaign topic} with strong focal subject and intentional negative space for headline/subcopy, clean hierarchy, modern brand-safe composition.
```

---

### 社媒封面图（16:9）

**平台:** Nano Banana (#39)

**Prompt:**
```
Generate a 16:9 social media cover image for {topic}, bold central motif, readable contrast zones for overlaid text, modern visual storytelling.
```

---

### 高点击缩略图

**平台:** Nano Banana (#40)

**Prompt:**
```
Create a high-CTR thumbnail style image: exaggerated focal contrast, simplified background, strong subject isolation, vivid but controlled color pops.
```

---

### 信息图背景图（低干扰）

**平台:** Nano Banana (#46)

**Prompt:**
```
Generate a subtle abstract background for infographic use, low visual noise, gentle gradients, geometric rhythm, high readability support for text overlays.
```

---

## 旅游

### 目的地旅游海报

**平台:** Nano Banana (#43)

**Prompt:**
```
Generate a destination campaign visual for {place}, iconic landmarks, cinematic weather, vibrant yet natural palette, aspirational travel mood.
```

---

## 绘本

### 儿童绘本分镜（连续故事）

**平台:** Nano Banana (#45)

**Prompt:**
```
Illustrate a children's story scene #{n}: {scene description}, keep character design consistent with prior scenes, soft colors, friendly expressions, page-layout-safe composition.
```

---

## 方法与技巧

### Gemini 结构化 JSON 方法

**平台:** Gemini (#11)

**模板:**
```
Use the following scene specification to generate one coherent image.
{
  "scene": {"location": "{location}", "time": "{time}", "atmosphere": "{atmosphere}"},
  "subject": {"identity": "{subject}", "pose": "{pose}", "expression": "{expression}"},
  "camera": {"framing": "{framing}", "lens": "{lens}", "angle": "{angle}"},
  "lighting": {"type": "{light_type}", "direction": "{direction}"},
  "style": {"theme": "{theme}", "palette": "{palette}", "detail": "high"}
}
```
示例场景: `surreal fashion walk in rocky desert, low-angle wide shot, high contrast sunlight, editorial sci-fi style`

---

### Nano Banana 结构化 JSON 方法

**平台:** Nano Banana (#21)

**模板:**
```
Generate one coherent image from this structured scene spec:
{
  "subject": {"type": "{subject}", "pose": "{pose}", "expression": "{expression}"},
  "environment": {"location": "{location}", "time": "{time}", "weather": "{weather}"},
  "camera": {"framing": "{framing}", "lens": "{lens}", "angle": "{angle}"},
  "lighting": {"setup": "{lighting setup}", "mood": "{mood}"},
  "style": {"genre": "{genre}", "palette": "{palette}", "detail": "very high"},
  "constraints": ["anatomically correct", "clean composition", "no watermark", "no text artifacts"]
}
```

---

### Nano Banana 质量增强后缀 v1

**平台:** Nano Banana (#22)

```
ultra-detailed, physically plausible lighting, balanced dynamic range, natural color science, clean background separation, anatomically correct, no text artifacts, no watermark
```

用法: 任意 prompt 末尾追加该后缀，提高稳定性与商业质感。

---

### Nano Banana 质量增强后缀 v2

**平台:** Nano Banana (#50)

```
high detail, physically plausible light, clean edge rendering, accurate anatomy, natural color science, professional composition, no watermark, no text artifacts, no deformed hands
```

---

### AI 海报多方案生成法

**平台:** Nano Banana (#49)

**模板:**
```
Generate 4 distinct visual directions for the same campaign topic: {topic}.
Direction A: minimalist luxury
Direction B: bold kinetic
Direction C: cinematic narrative
Direction D: abstract futuristic
Keep each direction compositionally unique and clearly separated in style language.
```

---

## 模板

### Civitai 自拍/人像模板

**模板:**
```
selfie, {subject}, {lighting}, {camera}, photorealistic, 8k, detailed skin texture
```

**示例:**
- `natural lighting, iPhone 15 Pro`
- `golden hour, DSLR 85mm`
- `ring light, mirror reflection`

---

### Civitai 艺术风格模板

**模板:**
```
{subject}, {art_style}, {color_scheme}, masterpiece, highly detailed
```

**示例:**
- `oil painting, warm tones`
- `digital art, cyberpunk neon`
- `watercolor, pastel colors`

---

### Civitai 赛博朋克模板

**模板:**
```
cyberpunk {subject}, neon lights, rain, futuristic city, cinematic lighting, 8k
```

**示例:**
- `portrait, glowing implants`
- `street scene, holographic ads`

---

### Civitai 动漫风格模板

**模板:**
```
{subject}, anime style, {studio}, {lighting}, vibrant colors, detailed
```

**示例:**
- `Makoto Shinkai style, soft lighting`
- `Studio Ghibli style, warm afternoon`

---

### Gemini 提示词结构公式

```
[主体] + [细节描述] + [光线] + [相机/风格] + [质量词]
```

---

### Gemini 质量增强关键词

| 类型 | 推荐词汇 |
|------|---------|
| 写实 | photorealistic, hyperrealistic, lifelike, detailed texture |
| 艺术 | masterpiece, museum quality, gallery art, professional |
| 摄影 | 8k, sharp focus, bokeh, depth of field, professional photography |
| 光线 | golden hour, soft natural light, dramatic lighting, studio lighting |

---

### Gemini 艺术创作模板

**模板:**
```
{art_style} of {subject}, in the style of {artist}, {color_scheme}, {lighting}, masterpiece, museum quality
```

**示例:**
- `oil painting, a serene mountain lake at dawn, Claude Monet style, soft pastel colors, impressionist lighting`
- `watercolor, blooming cherry blossoms, traditional Japanese style, delicate pink and white`
- `digital art, futuristic cityscape, Syd Mead style, neon and chrome, dramatic perspective`

---

### Gemini 特殊功能

- **文字生成**: 直接写 `"sign that says [文字]"` 或 `"poster with text [文字]"`
- **风格混合**: `"in the style of [艺术家A] and [艺术家B]"`
- **精确控制**: 使用 `[]` 强调重要元素
- **负面提示词**: `blurry, low quality, distorted, deformed, watermark, text error`

---

### 社区链接

- [Civitai](https://civitai.com) — 最大的 AI 生图社区
- [Lexica](https://lexica.art) — 搜索图片和 prompt
- [PromptBase](https://promptbase.com) — Prompt 市场
- [Tensor.Art](https://tensor.art) — 中文 AI 生图社区
- [r/GoogleGemini](https://reddit.com/r/GoogleGemini) — Gemini 官方社区
- [Google AI Studio](https://aistudio.google.com) — 官方 playground
- [Imagen 3 文档](https://ai.google.dev/gemini-api/docs/imagen) — 官方指南
