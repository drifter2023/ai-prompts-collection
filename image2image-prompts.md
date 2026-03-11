# 图生图 (Image-to-Image) Prompt 合集

*整合自: img2img-prompts.md, nano-banana-prompts.md*
*分类方式: 按主题/对象分类，跨平台重复条目合并*

---

## 目录

- [人像 / 人物](#人像--人物)
- [场景 / 环境](#场景--环境)
- [产品 / 商业](#产品--商业)
- [建筑](#建筑)
- [创意 / 艺术](#创意--艺术)
- [图像质量](#图像质量)
- [模板与公式](#模板与公式)
- [参考资料](#参考资料)

---

## 人像 / 人物

### 伦勃朗油画风格肖像

**平台:** Midjourney / Nano Banana

**Midjourney Prompt:**
```
[image URL] Transform this photo into an oil painting in the style of Rembrandt, dramatic lighting, rich textures, --iw 1.5 --s 750
```
参数: --iw 1.5 (图像权重), --s 750 (风格化)

**Nano Banana Prompt:**
```json
{
  "prompt": "oil painting in the style of Rembrandt, dramatic chiaroscuro lighting, rich textures, visible brush strokes, classical art, golden age painting, deep shadows, warm tones, masterpiece quality",
  "negative_prompt": "photograph, digital art, smooth, modern, lowres, cartoon",
  "strength": 0.80,
  "guidance_scale": 7.0
}
```

**关键词:** `oil painting`, `rembrandt`, `classical art`, `dramatic lighting`, `style transfer`

---

### 吉卜力动画风格重绘

**平台:** Midjourney / X/Twitter / Nano Banana

**Midjourney Prompt:**
```
[image URL] Reimagine this as a Studio Ghibli animation, soft colors, hand-drawn aesthetic, whimsical atmosphere --iw 1.2
```
参数: --iw 1.2 保持原图特征

**X/Twitter Prompt:** (@AIArtistDaily)
```
[image] Transform into Studio Ghibli style, hand-painted aesthetic, soft watercolor textures --iw 1.3
```
标签: #GhibliStyle, #AIArt, #ImageToImage

**Nano Banana Prompt:**
```json
{
  "prompt": "Studio Ghibli animation style, hand-painted aesthetic, soft watercolor textures, whimsical atmosphere, warm lighting, detailed background, anime art, cel shading, dreamy colors, Miyazaki inspired",
  "negative_prompt": "photorealistic, 3d render, western cartoon, blurry, low quality, distorted",
  "strength": 0.75,
  "guidance_scale": 7.5
}
```

**关键词:** `ghibli`, `anime`, `hand-painted`, `watercolor`, `cartoon`

---

### 赛博朋克霓虹风格

**平台:** Midjourney / Nano Banana

**Midjourney Prompt:**
```
[image URL] Convert to cyberpunk aesthetic, neon lights, futuristic cityscape background, blade runner style --iw 1.0 --s 500
```
参数: --iw 1.0 允许更多变化

**Nano Banana Prompt:**
```json
{
  "prompt": "cyberpunk aesthetic, neon lights, futuristic cityscape, blade runner style, purple and cyan neon glow, rain reflections, high tech, dystopian atmosphere, cinematic lighting, 8k detail",
  "negative_prompt": "natural lighting, daylight, rural, vintage, lowres, blurry",
  "strength": 0.70,
  "guidance_scale": 8.0
}
```

**关键词:** `cyberpunk`, `neon`, `futuristic`, `sci-fi`

---

### 水彩画风格

**平台:** Midjourney / Nano Banana

**Midjourney Prompt:**
```
[image URL] Transform into a watercolor painting, soft edges, flowing colors, artistic interpretation, paper texture --iw 1.3
```
参数: --iw 1.3 保持构图

**Nano Banana Prompt:**
```json
{
  "prompt": "watercolor painting, soft edges, flowing colors, artistic interpretation, paper texture, translucent layers, pigment bleeding, delicate brushwork, ethereal atmosphere, impressionist style",
  "negative_prompt": "photorealistic, sharp edges, digital art, 3d render, harsh lines",
  "strength": 0.75,
  "guidance_scale": 7.5
}
```

**关键词:** `watercolor`, `soft`, `artistic`, `flowing colors`, `painting`

---

### 复古合成器波风格

**平台:** Midjourney / X/Twitter / Nano Banana

**Midjourney Prompt:**
```
[image URL] Turn this into a 1980s retro synthwave artwork, vibrant purple and pink gradients, chrome reflections, palm trees, grid floor --iw 1.1
```
参数: --iw 1.1

**X/Twitter Prompt:** (@RetroAI_Art)
```
[image] Reimagine as 80s retro album cover, neon gradients, chrome typography, synthwave vibes --iw 1.0
```
标签: #Synthwave, #RetroArt, #AIEdit

**Nano Banana Prompt:**
```json
{
  "prompt": "1980s retro synthwave artwork, vibrant purple and pink gradients, chrome reflections, palm trees, grid floor, sunset backdrop, vaporwave aesthetic, retro futuristic, neon grid, dreamy nostalgic",
  "negative_prompt": "modern, realistic, photorealistic, muted colors, dark, gloomy",
  "strength": 0.72,
  "guidance_scale": 8.0
}
```

**关键词:** `synthwave`, `retro`, `80s`, `vaporwave`, `neon`

---

### 动漫赛璐珞风格

**平台:** Nano Banana

```json
{
  "prompt": "1990s anime cel shading, vibrant colors, clean bold lines, detailed face, nostalgic anime style, Japanese animation aesthetic, bright palette, hand-drawn look, classic anime art",
  "negative_prompt": "photorealistic, 3d render, western cartoon, realistic proportions, blurry",
  "strength": 0.78,
  "guidance_scale": 7.5
}
```

**关键词:** `anime`, `cel shading`, `90s anime`, `vibrant`

---

### 印象派风格

**平台:** Nano Banana

```json
{
  "prompt": "impressionist painting style, visible brush strokes, dappled light, Monet inspired, soft color palette, outdoor scene, natural lighting, loose brushwork, atmospheric perspective, romantic feel",
  "negative_prompt": "photorealistic, sharp focus, digital art, modern style, lowres",
  "strength": 0.75,
  "guidance_scale": 7.0
}
```

**关键词:** `impressionist`, `monet`, `brush strokes`, `dappled light`

---

### 赛博哥特风格

**平台:** Nano Banana

```json
{
  "prompt": "cybergoth aesthetic, dark neon, industrial elements, Victorian gothic meets cyberpunk, dark palette with neon accents, ornate machinery, dramatic shadows, mysterious atmosphere",
  "negative_prompt": "bright, cheerful, natural, minimal, simple",
  "strength": 0.73,
  "guidance_scale": 8.0
}
```

**关键词:** `cybergoth`, `dark neon`, `industrial`, `gothic`

---

### 浮世绘风格

**平台:** Nano Banana

```json
{
  "prompt": "ukiyo-e woodblock print style, Hokusai inspired, bold outlines, flat colors, Japanese art aesthetic, wave patterns, traditional composition, limited color palette, decorative patterns, Edo period art",
  "negative_prompt": "photorealistic, 3d, western art, gradient shading, realistic",
  "strength": 0.80,
  "guidance_scale": 7.5
}
```

**关键词:** `ukiyo-e`, `hokusai`, `woodblock print`, `japanese art`

---

### 蒸汽朋克风格

**平台:** Nano Banana

```json
{
  "prompt": "steampunk aesthetic, brass gears, copper pipes, steam-powered machinery, Victorian era fashion, intricate clockwork, warm metallic tones, retro-futuristic invention, detailed mechanical elements",
  "negative_prompt": "modern technology, plastic, minimalist, clean lines, digital",
  "strength": 0.75,
  "guidance_scale": 7.5
}
```

**关键词:** `steampunk`, `brass`, `gears`, `victorian`, `mechanical`

---

### 3D 折纸艺术风格

**平台:** Nano Banana

```json
{
  "prompt": "3D origami art style, folded paper textures, crisp geometric edges, colorful craft paper, soft studio lighting, miniature paper world aesthetic, macro view",
  "negative_prompt": "flat, 2d, drawing, painting, photorealistic, messy lines",
  "strength": 0.80,
  "guidance_scale": 7.5
}
```

**关键词:** `origami`, `folded paper`, `geometric`, `craft paper`

---

### 教堂彩色玻璃风格

**平台:** Nano Banana

```json
{
  "prompt": "stained glass window style, vibrant transparent colors, thick black lead lines, divine lighting shining through, colorful light dispersion, church window aesthetic",
  "negative_prompt": "photorealistic, 3d render, soft painting, muted colors",
  "strength": 0.75,
  "guidance_scale": 8.0
}
```

**关键词:** `stained glass`, `transparent colors`, `lead lines`, `divine lighting`

---

### 人像美颜增强

**平台:** Nano Banana

```json
{
  "prompt": "professional portrait retouching, enhanced skin texture, sharp eyes, natural skin tones, professional lighting, polished look, maintain natural features, high end photography",
  "negative_prompt": "overprocessed, plastic skin, unnatural, doll-like, distorted",
  "strength": 0.40,
  "guidance_scale": 6.5
}
```

---

### 人像保脸 + 光线重置 (Face Lock + Relight)

**平台:** Midjourney / SD img2img

```
[image URL] Keep the exact same identity and facial geometry, regenerate with cinematic side lighting, clean skin texture, subtle film grain, shallow depth of field, realistic 85mm lens rendering --iw 2.0
```

**关键词:** `face consistency`, `relight`, `portrait enhancement`

---

### 折射玻璃肖像重绘（Reeded Glass Distortion）

**平台:** Midjourney / SD img2img

```
[image URL] Re-render this portrait as if photographed through thick vertically reeded architectural glass, strong vertical optical refraction, soft studio light, pale neutral background, keep subject identity recognizable --iw 1.4
```

---

### 蓝图科技风叠加（Blueprint Overlay）

**平台:** SDXL img2img + ControlNet lineart

```
[image URL] Transform into a sci-fi concept sheet style with subtle blueprint line overlays and technical sketch annotations around the subject, keep core silhouette and facial features --iw 1.3
```

---

### 电影感肤质保留增强（Skin-Preserving Cinematic Grade）

**平台:** Midjourney / SD img2img (人像精修流程)

```
[image URL] Apply cinematic color grading with natural skin tone preservation, shallow depth-of-field simulation, gentle bokeh background, maintain original facial structure exactly --iw 1.8
```

---

### 35mm Portra 胶片风格

**平台:** img2img / Nano Banana

**img2img Prompt:**
```
[image URL] Convert this image into a 35mm Kodak Portra-style film photograph, subtle grain, realistic contrast roll-off, slight motion energy, documentary street mood --iw 1.2
```
适用: 人文/街拍图像

**Nano Banana Prompt:**
```json
{
  "prompt": "vintage 35mm film photography, Kodak Portra 400 style, subtle light leaks, film grain, nostalgic warm color grading, cinematic classic, analogue aesthetic",
  "negative_prompt": "digital crisp, modern, hyper-realistic, oversaturated, plastic",
  "strength": 0.40,
  "guidance_scale": 7.0
}
```

**关键词:** `35mm film`, `grain`, `light leaks`, `analogue`, `portra`

---

### 赛博材质替换（Cyber Material Swap）

**平台:** Midjourney / SD img2img (角色风格化)

```
[image URL] Replace clothing and accessories with reflective black alloy cyberpunk materials, add precise mechanical detailing and neon rim light, preserve pose and composition --iw 1.5
```

---

### 发型与发色变更

**平台:** Midjourney / SD img2img

```
[image URL] Keep face identity unchanged, change hairstyle to layered shoulder-length cut with silver-lavender hair color, natural strands, realistic volume, studio portrait quality --iw 1.8
```

**关键词:** `hairstyle transfer`, `identity-safe edit`

---

### 服装材质升级

**平台:** Midjourney / SD img2img

```
[image URL] Keep person identity and pose unchanged, replace clothing fabric with black silk and metallic accents, realistic folds, specular highlights, editorial fashion look --iw 1.7
```

**关键词:** `outfit swap`, `material editing`

---

### 添加皇冠/珠宝

**平台:** Midjourney / Nano Banana

**Midjourney Prompt:**
```
[image URL] Add a crown and royal jewelry to the person, regal pose, maintain facial features --iw 1.8
```
参数: --iw 1.8 保持面部特征

**Nano Banana Prompt:**
```json
{
  "prompt": "add elegant crown and royal jewelry, diamond tiara, precious gems, regal appearance, luxurious accessories, maintain facial features, natural placement, sparkling details",
  "negative_prompt": "different face, distorted features, cheap looking, plastic, oversized",
  "strength": 0.60,
  "guidance_scale": 7.0
}
```

**关键词:** `add elements`, `accessories`, `jewelry`, `crown`

---

### 晚礼服换装

**平台:** Midjourney / Nano Banana

**Midjourney Prompt:**
```
[image URL] Change the outfit to a formal evening gown, black silk, elegant, keep the pose and background --iw 1.5
```
参数: --iw 1.5 保持姿态和背景

**Nano Banana Prompt:**
```json
{
  "prompt": "wearing elegant black silk evening gown, formal attire, sophisticated look, maintain same pose, keep background unchanged, detailed fabric texture, flowing silhouette",
  "negative_prompt": "different person, changed face, casual clothes, distorted body",
  "strength": 0.62,
  "guidance_scale": 7.0
}
```

**关键词:** `clothing change`, `fashion`, `dress`, `evening gown`

---

### 硬核机甲换装

**平台:** Nano Banana

```json
{
  "prompt": "wearing sleek futuristic mecha armor, carbon fiber textures, glowing LED accents, robotic exoskeleton, sci-fi military gear, keep facial features intact",
  "negative_prompt": "casual clothes, medieval armor, soft fabric, distorted face",
  "strength": 0.65,
  "guidance_scale": 7.5
}
```

**关键词:** `mecha armor`, `carbon fiber`, `exoskeleton`, `sci-fi`

---

### 精准霓虹灯文字渲染

**平台:** Nano Banana

```json
{
  "prompt": "cinematic glowing neon sign reading 'NANO', bright yellow and cyan letters, rain-slicked dark brick wall background, sharp text rendering, vibrant reflections",
  "negative_prompt": "misspelled, gibberish, broken letters, daylight, soft lighting",
  "strength": 0.70,
  "guidance_scale": 8.5
}
```

**关键词:** `neon sign`, `sharp text`, `text rendering`

---

### 写实照片转动漫

**平台:** Midjourney / SD img2img

```
[image URL] Reinterpret this photo in high-quality anime style, clean linework, cel-shading, expressive eyes, controlled color blocks, keep original pose and camera framing --iw 1.3 --stylize 600
```

**关键词:** `photo to anime`, `stylization`

---

### 动漫转写实

**平台:** Midjourney / SD img2img

```
[image URL] Convert anime illustration into photorealistic cinematic portrait, natural skin texture, physically plausible lighting, realistic materials and depth, preserve hairstyle and outfit silhouette --iw 1.5
```

**关键词:** `anime to real`, `realism transfer`

---

### 线稿上色 (Sketch-to-Render)

**平台:** Midjourney / SD img2img

```
[image URL] Colorize and fully render this line art into polished concept art, retain original line composition, add material definition, global illumination, and production-quality shading --iw 1.7
```

**关键词:** `sketch to render`, `concept art`

---

### 运动模糊增强

**平台:** Midjourney / SD img2img

```
[image URL] Keep the main subject readable but add directional motion blur to limbs/background, dynamic shutter feel, action-photography energy, realistic light streak behavior --iw 1.3
```

**关键词:** `motion enhancement`, `action stylization`

---

### 老照片修复 + 上色

**平台:** Midjourney / SD img2img

```
[image URL] Restore this old damaged photo: remove scratches and noise, reconstruct missing details, natural skin tones, historically plausible colorization, preserve original expression and composition --iw 1.9
```

**关键词:** `restoration`, `colorization`

---

## 场景 / 环境

### 日落海滩背景替换

**平台:** Midjourney / Nano Banana

**Midjourney Prompt:**
```
[image URL] Change the background to a sunset beach scene, golden hour lighting, keep the subject exactly the same --iw 2.0
```
参数: --iw 2.0 强制保持主体

**Nano Banana Prompt:**
```json
{
  "prompt": "golden hour sunset beach background, warm orange and pink sky, ocean waves, golden sand, keep the subject exactly the same, seamless integration, natural lighting match",
  "negative_prompt": "mismatched lighting, floating subject, disconnected background, harsh edges",
  "strength": 0.65,
  "guidance_scale": 7.5
}
```

**关键词:** `background change`, `scene replace`, `sunset`, `beach`

---

### 城市夜景背景替换

**平台:** Nano Banana

```json
{
  "prompt": "night cityscape background, bokeh lights, urban skyline, neon reflections, wet pavement, keep subject unchanged, atmospheric depth, cinematic night setting",
  "negative_prompt": "daylight, natural setting, mismatched shadows, floating subject",
  "strength": 0.68,
  "guidance_scale": 7.5
}
```

---

### 冬季雪景转换

**平台:** X/Twitter / Nano Banana

**X/Twitter Prompt:** (@PhotoEditAI)
```
[image] Change season to winter, add snow, frosty atmosphere, keep composition --iw 1.8
```
标签: #SeasonChange, #WinterVibes, #AIEditing

**Nano Banana Prompt:**
```json
{
  "prompt": "winter wonderland scene, soft falling snow, frosty atmosphere, snow-covered landscape, cool blue tones, cozy winter lighting, magical snow effect, seasonal transformation",
  "negative_prompt": "summer, green leaves, warm weather, rain, autumn",
  "strength": 0.70,
  "guidance_scale": 7.5
}
```

---

### 白天改夜景 (Day-to-Night Conversion)

**平台:** Midjourney / SD img2img

```
[image URL] Convert this daytime street scene into night, add neon signage reflections on wet ground, cool ambient shadows, practical light sources from shop windows, cinematic contrast --iw 1.6
```

**关键词:** `day to night`, `relighting`, `environment conversion`

---

### 天气改造：晴天转雨天

**平台:** Midjourney / SD img2img

```
[image URL] Transform clear weather into rainy atmosphere, add rainfall streaks, wet surfaces, puddle reflections, overcast sky, realistic moisture on materials while preserving original composition --iw 1.5
```

**关键词:** `weather transfer`, `rain effect`, `mood change`

---

### 季节迁移：夏到冬

**平台:** Midjourney / SD img2img

```
[image URL] Change season from summer to winter, replace foliage with sparse frosted branches, add thin snow cover, cool color temperature, soft winter haze, keep perspective and structure unchanged --iw 1.4
```

**关键词:** `season transfer`, `environment swap`

---

### 赛博朋克街景背景替换

**平台:** Midjourney / SD img2img

```
[image URL] Preserve subject scale and position, replace background with futuristic cyberpunk street, holographic ads, atmospheric fog, wet pavement reflections, strong depth perspective --iw 1.6
```

**关键词:** `background replacement`, `scene expansion`

---

### 水下世界场景

**平台:** Nano Banana

```json
{
  "prompt": "underwater scene transformation, coral reef surroundings, tropical fish swimming, caustic light effects, bubbles rising, submerged aesthetic, blue-green tones, marine life atmosphere",
  "negative_prompt": "dry land, normal air, no water effects, boring background",
  "strength": 0.78,
  "guidance_scale": 8.0
}
```

---

### 太空宇宙场景

**平台:** Nano Banana

```json
{
  "prompt": "floating in deep space, nebula background, distant galaxies, stars everywhere, zero gravity effect, cosmic lighting, purple and blue cosmic colors, ethereal space atmosphere",
  "negative_prompt": "earth landscape, gravity, normal sky, grounded",
  "strength": 0.80,
  "guidance_scale": 8.0
}
```

---

## 产品 / 商业

### 商业产品棚拍重构 (Product Hero Relight)

**平台:** img2img 增量 / img2img 全类型

**增量 Prompt (专业棚拍):**
```
[image URL] Rebuild this object into a premium commercial hero shot with controlled three-point studio lighting, clean gradient backdrop, crisp reflections, and ad-quality detail --iw 1.6
```
适用: 产品图升级/电商主图

**全类型 Prompt (随手拍→商业图):**
```
[image URL] Turn this casual product photo into a premium studio advertisement shot, clean gradient background, controlled highlights, micro-detail texture, sharp edges, luxury branding aesthetic --iw 1.8
```

**关键词:** `product relight`, `ad photography`, `commercial`

---

### 商品场景化 (Packshot to Lifestyle)

**平台:** Midjourney / SD img2img

```
[image URL] Keep the product shape and branding exact, place it naturally in a lifestyle scene (e.g., modern desk/cafe/bathroom), realistic shadows and contact lighting, commercial-grade composition --iw 1.7
```

**关键词:** `packshot to lifestyle`, `scene integration`

---

### 微距摄影质感

**平台:** Nano Banana

```json
{
  "prompt": "macro photography, extreme close-up, highly detailed textures, beautiful smooth bokeh, narrow depth of field, 85mm lens, crisp sharp focus on subject",
  "negative_prompt": "wide angle, landscape, blurry subject, flat lighting, painting",
  "strength": 0.45,
  "guidance_scale": 6.5
}
```

**关键词:** `macro`, `close-up`, `bokeh`, `depth of field`

---

## 建筑

### 建筑旧改新 (Facade Renovation)

**平台:** Midjourney / SD img2img

```
[image URL] Redesign this building facade into modern minimalist architecture, replace exterior materials with concrete/glass/wood, balanced daylight, realistic construction details, keep structural proportions --iw 1.5
```

**关键词:** `architecture redesign`, `facade remaster`

---

## 创意 / 艺术

### 花卉艺术重绘

**平台:** Nano Banana

```json
{
  "prompt": "made entirely of flowers and botanical elements, floral composition, petals and leaves, organic transformation, nature art, blooming aesthetic, colorful petals, garden fantasy",
  "negative_prompt": "synthetic materials, metal, plastic, harsh textures",
  "strength": 0.82,
  "guidance_scale": 7.5
}
```

---

### 金色雕像风格

**平台:** Nano Banana

```json
{
  "prompt": "transformed into golden statue, metallic gold surface, sculptural quality, ancient artifact style, polished bronze look, museum piece aesthetic, reflective metal texture",
  "negative_prompt": "organic skin, normal colors, fabric, wood, stone",
  "strength": 0.75,
  "guidance_scale": 7.5
}
```

---

### 像素艺术风格

**平台:** Nano Banana

```json
{
  "prompt": "8-bit pixel art style, retro game aesthetic, limited color palette, blocky pixelated look, nostalgic video game style, crisp pixels, arcade game graphics",
  "negative_prompt": "smooth gradients, photorealistic, high detail, modern 3d",
  "strength": 0.85,
  "guidance_scale": 8.0
}
```

---

### 科幻全息投影效果

**平台:** Nano Banana

```json
{
  "prompt": "glowing holographic projection, translucent blue and cyan tech lines, digital wireframe, sci-fi hologram effect, floating in dark room, cyberpunk tech",
  "negative_prompt": "solid matter, opaque, natural lighting, flesh, photorealistic",
  "strength": 0.85,
  "guidance_scale": 8.0
}
```

**关键词:** `holographic`, `wireframe`, `translucent`, `glowing lines`

---

### 神秘塔罗牌插画

**平台:** Nano Banana

```json
{
  "prompt": "mystical tarot card illustration, intricate esoteric symbols, flat decorative composition, gold leaf details, mysterious occult aesthetic, vintage mystical art",
  "negative_prompt": "modern photography, 3d render, plain background, realistic",
  "strength": 0.80,
  "guidance_scale": 7.5
}
```

**关键词:** `tarot card`, `esoteric`, `gold leaf`, `mystical art`

---

### 移轴微缩效果

**平台:** X/Twitter / Nano Banana

**X/Twitter Prompt:** (@CreativeAI_Daily)
```
[image] Turn into a miniature tilt-shift diorama, toy-like appearance, shallow depth of field --iw 1.2
```
标签: #TiltShift, #Miniature, #CreativeEdit

**Nano Banana Prompt:**
```json
{
  "prompt": "tilt-shift miniature effect, toy-like appearance, shallow depth of field, diorama style, selective focus, tiny world aesthetic, boosted saturation, dreamy bokeh",
  "negative_prompt": "normal perspective, full depth of field, realistic scale, documentary style",
  "strength": 0.72,
  "guidance_scale": 7.5
}
```

---

## 图像质量

### 4K 放大增强

**平台:** Midjourney / X/Twitter / Nano Banana

**Midjourney Prompt:**
```
[image URL] Upscale to 4K resolution, enhance details, sharp focus, professional photography quality, --iw 2.0 --q 2
```
参数: --iw 2.0, --q 2 (最高质量)

**X/Twitter Prompt:** (@EnhanceAI)
```
[image] Upscale to 8K, enhance micro-details, HDR processing, professional retouch --iw 2.0
```
标签: #Upscale, #8K, #PhotoEnhancement

**Nano Banana Prompt:**
```json
{
  "prompt": "upscaled to 4K resolution, enhanced details, sharp focus, professional photography quality, crisp edges, refined textures, high fidelity, premium quality, ultra detailed",
  "negative_prompt": "blurry, lowres, pixelated, compression artifacts, noise",
  "strength": 0.45,
  "guidance_scale": 7.0
}
```

**关键词:** `upscale`, `enhance`, `4K`, `quality`, `8K`

---

### HDR 效果增强

**平台:** Nano Banana

```json
{
  "prompt": "HDR quality, improved dynamic range, vivid colors, enhanced contrast, brightened shadows, recovered highlights, cinematic color grading, vibrant tones, professional finish",
  "negative_prompt": "flat lighting, washed out, underexposed, overexposed, dull",
  "strength": 0.42,
  "guidance_scale": 7.0
}
```

---

### 细节锐化

**平台:** Nano Banana

```json
{
  "prompt": "sharpened focus, enhanced micro-details, crystal clear, crisp definition, fixed motion blur, enhanced clarity, professional sharpening, edge enhancement",
  "negative_prompt": "blurry, soft focus, out of focus, motion blur, hazy",
  "strength": 0.35,
  "guidance_scale": 6.5
}
```

---

### 低清放大重绘 (HQ Upscale Regeneration)

**平台:** Midjourney / SD img2img

```
[image URL] Regenerate this low-resolution image into high-resolution detailed output, preserve overall composition, improve texture fidelity, clean edges, remove compression artifacts --iw 1.8
```

**关键词:** `upscale`, `super-resolution style regeneration`

---

### 景深重建：手机平图→电影感

**平台:** Midjourney / SD img2img

```
[image URL] Rebuild this flat smartphone shot with cinematic depth, strong subject separation, realistic foreground/background blur falloff, subtle filmic color grading --iw 1.4
```

**关键词:** `depth reconstruction`, `cinematic enhancement`

---

### LOGO/文字保留的海报重绘

**平台:** Midjourney / SD img2img

```
[image URL] Recompose into a modern poster design while preserving key logo/text areas exactly, enhance typography hierarchy, cinematic background graphics, clean visual balance --iw 1.9
```

**关键词:** `poster redesign`, `text-preserving img2img`

---

## 模板与公式

### Stable Diffusion img2img 模板

#### 图生图基础

**Prompt:**
```
masterpiece, best quality, (detailed face:1.2), (detailed eyes:1.3), [original subject], improved lighting, sharp focus
```
**Negative:** `(worst quality, low quality:1.4), blurry, deformed`
**Denoising:** 0.60-0.75

---

#### 风格重绘-油画

**Prompt:**
```
(oil painting:1.3), (impasto:1.2), visible brush strokes, rich colors, masterpiece, [subject], canvas texture
```
**Negative:** `photorealistic, digital art, smooth, lowres`
**Denoising:** 0.65-0.80

---

#### 动漫化

**Prompt:**
```
anime style, cel shading, vibrant colors, clean lines, detailed face, masterpiece, from photo, [subject]
```
**Negative:** `photorealistic, 3d render, western cartoon, blurry`
**Denoising:** 0.70-0.85

---

#### 写实增强

**Prompt:**
```
photorealistic, 8k, ultra detailed, (sharp focus:1.2), professional photography, enhanced, [subject]
```
**Negative:** `painting, drawing, cartoon, anime, lowres, blurry`
**Denoising:** 0.40-0.60

---

#### 场景替换

**Prompt:**
```
same [subject], (new background: [description]:1.2), consistent lighting, seamless integration, natural shadows
```
**Negative:** `mismatched lighting, floating, disconnected`
**Denoising:** 0.65-0.80

---

#### 角色换装

**Prompt:**
```
[subject], wearing [new outfit], same pose, same lighting, maintain identity, detailed fabric texture
```
**Negative:** `different person, changed face, distorted`
**Denoising:** 0.55-0.70

---

### Gemini/Imagen 3 编辑模板

#### 基础编辑

```
Based on this image, [描述修改]. Maintain the original composition but change [具体元素].
```
示例: `Based on this image, add a sunset background with orange and pink colors. Maintain the original composition but change the sky.`

---

#### 风格转换

```
Transform this image into a [艺术风格] version. Keep the subject the same but apply [风格特征].
```
示例: `Transform this image into a watercolor painting version. Keep the subject the same but apply soft edges and flowing colors.`

---

#### 元素添加

```
Add [元素] to this image. The [元素] should [描述] and blend naturally with the existing scene.
```
示例: `Add a cat sitting on the windowsill to this image. The cat should be orange and blend naturally with the existing scene.`

---

#### 元素移除

```
Remove the [元素] from this image and fill in the background naturally. The result should look seamless.
```
示例: `Remove the person from this image and fill in the background naturally. The result should look seamless.`

---

#### 颜色调整

```
Change the color scheme of this image to [色调]. Adjust the mood to be [氛围描述].
```
示例: `Change the color scheme of this image to warm autumn tones. Adjust the mood to be cozy and nostalgic.`

---

### 万能编辑公式

#### 风格迁移公式

```
[原图] + "transform into [风格]" + [质量词]
```
示例:
- `oil painting with visible brush strokes, Rembrandt lighting`
- `1970s anime cel shading, vibrant colors`
- `hyper-realistic digital art, 8k details`
- `van Gogh style with swirling brushwork`
- `cyberpunk neon aesthetic, futuristic`

推荐参数: SD Denoising 0.5-0.7 / MJ --iw 1.0-1.5

---

#### 局部编辑公式

```
[原图] + "[add/remove/change] [元素]" + [位置] + [细节]
```
示例:
- `Add sunglasses to the person, reflective lenses, modern style`
- `Remove the background crowd, fill with blurred cityscape`
- `Change the dress color to red, silk fabric, same lighting`

推荐参数: SD Denoising 0.6-0.8 / MJ --iw 1.5-2.0

---

#### 图像增强公式

```
[原图] + "upscale/enhance" + [目标质量] + [细节要求]
```
示例:
- `Upscale to 4K, enhance facial details, sharp eyes`
- `HDR quality, improve dynamic range, vivid colors`
- `Professional retouching, smooth skin, keep natural texture`

推荐参数: SD Denoising 0.3-0.5 / MJ --iw 1.8-2.0

---

#### 创意重绘公式

```
[原图] + "reimagine as" + [新概念] + [风格形容词]
```
示例:
- `Steampunk version with brass gears and steam pipes`
- `Underwater scene with coral reef and tropical fish`
- `Made entirely of flowers and botanical elements`
- `Floating in space with galaxies in background`
- `Miniature diorama with tilt-shift effect`

推荐参数: SD Denoising 0.7-0.9 / MJ --iw 0.8-1.2

---

## 参考资料

### 关键词速查手册

#### 风格迁移
```
oil painting, watercolor, pencil sketch, charcoal drawing, impressionist, expressionist, surrealist, art nouveau, art deco, bauhaus, minimalist, pop art, street art, graffiti, comic book, origami, stained glass, realism, abstract
```

#### 光线
```
golden hour, blue hour, magic hour, sunrise, sunset, soft lighting, hard lighting, dramatic lighting, moody lighting, rim lighting, backlight, side light, top light, cinematic lighting, studio lighting, neon glow, volumetric lighting, foggy, misty, holographic
```

#### 相机/技术
```
dslr, mirrorless, film camera, polaroid, 35mm lens, 50mm lens, 85mm lens, 135mm lens, 200mm lens, wide angle, telephoto, macro, fisheye, f/1.4, f/1.8
```

#### 编辑操作
```
style transfer, image to image, img2img, inpainting, outpainting, background removal, object removal, object addition, scene replacement, color grading, color correction, white balance, sharpening, denoising, upscaling
```

#### 质量增强
```
8k, 4k, high resolution, ultra detailed, masterpiece, best quality, award winning, sharp focus, crisp, clear, photorealistic, hyperrealistic, lifelike, professional, commercial quality, high fidelity, macro, bokeh, 35mm film, film grain
```

#### 艺术家风格
```
van gogh, monet, renoir, degas, picasso, dali, kandinsky, mondrian, mucha, klimt, hokusai, hiroshige, da vinci, michelangelo, raphael
```

#### 动漫/游戏风格
```
studio ghibli, makoto shinkai, hayao miyazaki, pixar, disney, dreamworks, laika, japanese anime, korean manhwa, chinese donghua, fortnite, valorant, overwatch, zelda, final fantasy, 90s anime, cel shading, pixel art
```

#### 材质/纹理
```
metallic, wooden, fabric, glass, crystal, marble, rusted, polished, rough, smooth, glittering, carbon fiber, craft paper
```

### 参数速查表

| 目标效果 | SD Denoising | MJ --iw | NB Strength | NB Guidance | 备注 |
|----------|-------------|---------|-------------|-------------|------|
| 轻微调色 | 0.3-0.4 | 2.0 | 0.30-0.40 | 6.5-7.0 | 几乎保持原图 |
| 增强细节 | 0.4-0.5 | 1.8-2.0 | 0.40-0.50 | 6.5-7.0 | 修复模糊照片 |
| 风格迁移 | 0.5-0.7 | 1.0-1.5 | 0.70-0.80 | 7.0-8.0 | 油画/水彩等 |
| 场景替换 | 0.6-0.8 | 1.5-1.8 | 0.65-0.70 | 7.5 | 换背景 |
| 局部编辑 | 0.5-0.7 | 1.5-1.8 | 0.60-0.68 | 7.0-7.5 | 换装/添加元素 |
| 大幅重绘 | 0.7-0.9 | 0.5-1.0 | 0.78-0.85 | 7.5-8.0 | 创意改造 |
| 人像美颜 | 0.3-0.5 | 1.8-2.0 | 0.40 | 6.5 | 保持自然 |

### 各平台操作指南

#### Midjourney
```
[图片URL] 你的提示词 --iw 1.5 --s 750
```
- `--iw 0.5-2.0`: 图像权重，越高越像原图
- `--s 0-1000`: 风格化程度
- `--q 2`: 最高质量

#### Stable Diffusion (WebUI)
1. 切换到 **img2img** 标签
2. 上传图片到 **Init Image**
3. 调整 **Denoising strength**:
   - 0.3-0.5: 轻微调整/增强
   - 0.5-0.7: 风格迁移
   - 0.7-0.9: 大幅重绘
4. 可选: 启用 **ControlNet** 保持姿态

#### ComfyUI 工作流
```
Load Image → VAE Encode → KSampler (img2img)
                ↓
         ControlNet Apply (可选)
                ↓
         VAE Decode → Save Image
```

#### Gemini API
```python
response = model.generate_content([
    '基于这张图片，添加一个日落背景',
    image
])
```

#### Nano Banana API
```python
import requests
import base64

url = "https://api.nano-banana.com/v1/img2img"

with open("input.jpg", "rb") as f:
    image_base64 = base64.b64encode(f.read()).decode()

payload = {
    "image": image_base64,
    "prompt": "Studio Ghibli animation style, hand-painted aesthetic, soft watercolor textures, whimsical atmosphere",
    "negative_prompt": "photorealistic, 3d render, western cartoon, blurry, low quality",
    "strength": 0.75,
    "guidance_scale": 7.5,
    "num_inference_steps": 30,
    "width": 1024,
    "height": 1024
}

headers = {
    "Authorization": "Bearer YOUR_API_KEY",
    "Content-Type": "application/json"
}

response = requests.post(url, json=payload, headers=headers)
```

### 推荐工具

| 工具 | 特点 | 适用场景 |
|------|------|---------|
| [AUTOMATIC1111](https://github.com/AUTOMATIC1111/stable-diffusion-webui) | 功能最全 | 本地 img2img |
| [ComfyUI](https://github.com/comfyanonymous/ComfyUI) | 节点工作流 | 复杂编辑流程 |
| [Fooocus](https://github.com/lllyasviel/Fooocus) | 简单易用 | 快速风格迁移 |
| [Leonardo.ai](https://leonardo.ai) | 在线工具 | 免安装编辑 |
| [Clipdrop](https://clipdrop.co) | Stability AI | 专业修图工具 |
