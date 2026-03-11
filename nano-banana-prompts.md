# 🍌 Nano Banana API 风格化 Prompt 完整合集

*基于 img2img 最佳实践设计 | 适用于 Nano Banana API | 包含高保真文本渲染与高级特性*

---

## 📋 目录

- [风格迁移](#风格迁移)
- [质感与摄影增强](#质感与摄影增强)
- [图像增强](#图像增强)
- [局部编辑](#局部编辑)
- [特色编辑（含文本渲染）](#特色编辑含文本渲染)
- [创意重绘](#创意重绘)
- [奇幻创意重绘](#奇幻创意重绘)
- [API 调用示例](#api-调用示例)
- [参数指南](#参数指南)

---

## 🎨 风格迁移

### 1. 吉卜力动画风格

```json
{
  "prompt": "Studio Ghibli animation style, hand-painted aesthetic, soft watercolor textures, whimsical atmosphere, warm lighting, detailed background, anime art, cel shading, dreamy colors, Miyazaki inspired",
  "negative_prompt": "photorealistic, 3d render, western cartoon, blurry, low quality, distorted",
  "strength": 0.75,
  "guidance_scale": 7.5
}
```

**关键词:** `ghibli`, `anime`, `hand-painted`, `watercolor`

---

### 2. 赛博朋克霓虹风格

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

### 3. 伦勃朗油画风格

```json
{
  "prompt": "oil painting in the style of Rembrandt, dramatic chiaroscuro lighting, rich textures, visible brush strokes, classical art, golden age painting, deep shadows, warm tones, masterpiece quality",
  "negative_prompt": "photograph, digital art, smooth, modern, lowres, cartoon",
  "strength": 0.80,
  "guidance_scale": 7.0
}
```

**关键词:** `oil painting`, `rembrandt`, `classical art`, `dramatic lighting`

---

### 4. 水彩画风格

```json
{
  "prompt": "watercolor painting, soft edges, flowing colors, artistic interpretation, paper texture, translucent layers, pigment bleeding, delicate brushwork, ethereal atmosphere, impressionist style",
  "negative_prompt": "photorealistic, sharp edges, digital art, 3d render, harsh lines",
  "strength": 0.75,
  "guidance_scale": 7.5
}
```

**关键词:** `watercolor`, `soft`, `artistic`, `flowing colors`

---

### 5. 复古合成器波风格

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

### 6. 动漫赛璐珞风格

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

### 7. 印象派风格

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

### 8. 赛博哥特风格

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

### 9. 浮世绘风格

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

### 10. 蒸汽朋克风格

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

### 11. 3D 折纸艺术风格

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

### 12. 教堂彩色玻璃风格

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

## 📸 质感与摄影增强

### 13. 微距摄影质感

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

### 14. 复古胶片质感

```json
{
  "prompt": "vintage 35mm film photography, Kodak Portra 400 style, subtle light leaks, film grain, nostalgic warm color grading, cinematic classic, analogue aesthetic",
  "negative_prompt": "digital crisp, modern, hyper-realistic, oversaturated, plastic",
  "strength": 0.40,
  "guidance_scale": 7.0
}
```

**关键词:** `35mm film`, `grain`, `light leaks`, `analogue`

---

## ✨ 图像增强

### 15. 4K 超高清增强

```json
{
  "prompt": "upscaled to 4K resolution, enhanced details, sharp focus, professional photography quality, crisp edges, refined textures, high fidelity, premium quality, ultra detailed",
  "negative_prompt": "blurry, lowres, pixelated, compression artifacts, noise",
  "strength": 0.45,
  "guidance_scale": 7.0
}
```

---

### 16. 人像美颜增强

```json
{
  "prompt": "professional portrait retouching, enhanced skin texture, sharp eyes, natural skin tones, professional lighting, polished look, maintain natural features, high end photography",
  "negative_prompt": "overprocessed, plastic skin, unnatural, doll-like, distorted",
  "strength": 0.40,
  "guidance_scale": 6.5
}
```

---

### 17. HDR 效果增强

```json
{
  "prompt": "HDR quality, improved dynamic range, vivid colors, enhanced contrast, brightened shadows, recovered highlights, cinematic color grading, vibrant tones, professional finish",
  "negative_prompt": "flat lighting, washed out, underexposed, overexposed, dull",
  "strength": 0.42,
  "guidance_scale": 7.0
}
```

---

### 18. 细节锐化

```json
{
  "prompt": "sharpened focus, enhanced micro-details, crystal clear, crisp definition, fixed motion blur, enhanced clarity, professional sharpening, edge enhancement",
  "negative_prompt": "blurry, soft focus, out of focus, motion blur, hazy",
  "strength": 0.35,
  "guidance_scale": 6.5
}
```

---

## 🔧 局部编辑

### 19. 日落海滩背景替换

```json
{
  "prompt": "golden hour sunset beach background, warm orange and pink sky, ocean waves, golden sand, keep the subject exactly the same, seamless integration, natural lighting match",
  "negative_prompt": "mismatched lighting, floating subject, disconnected background, harsh edges",
  "strength": 0.65,
  "guidance_scale": 7.5
}
```

---

### 20. 城市夜景背景替换

```json
{
  "prompt": "night cityscape background, bokeh lights, urban skyline, neon reflections, wet pavement, keep subject unchanged, atmospheric depth, cinematic night setting",
  "negative_prompt": "daylight, natural setting, mismatched shadows, floating subject",
  "strength": 0.68,
  "guidance_scale": 7.5
}
```

---

### 21. 冬季雪景转换

```json
{
  "prompt": "winter wonderland scene, soft falling snow, frosty atmosphere, snow-covered landscape, cool blue tones, cozy winter lighting, magical snow effect, seasonal transformation",
  "negative_prompt": "summer, green leaves, warm weather, rain, autumn",
  "strength": 0.70,
  "guidance_scale": 7.5
}
```

---

### 22. 添加皇冠/珠宝元素

```json
{
  "prompt": "add elegant crown and royal jewelry, diamond tiara, precious gems, regal appearance, luxurious accessories, maintain facial features, natural placement, sparkling details",
  "negative_prompt": "different face, distorted features, cheap looking, plastic, oversized",
  "strength": 0.60,
  "guidance_scale": 7.0
}
```

---

### 23. 晚礼服换装

```json
{
  "prompt": "wearing elegant black silk evening gown, formal attire, sophisticated look, maintain same pose, keep background unchanged, detailed fabric texture, flowing silhouette",
  "negative_prompt": "different person, changed face, casual clothes, distorted body",
  "strength": 0.62,
  "guidance_scale": 7.0
}
```

---

### 24. 移轴微缩效果

```json
{
  "prompt": "tilt-shift miniature effect, toy-like appearance, shallow depth of field, diorama style, selective focus, tiny world aesthetic, boosted saturation, dreamy bokeh",
  "negative_prompt": "normal perspective, full depth of field, realistic scale, documentary style",
  "strength": 0.72,
  "guidance_scale": 7.5
}
```

---

## 🔠 特色编辑（含文本渲染）

### 25. 精准霓虹灯文字

```json
{
  "prompt": "cinematic glowing neon sign reading 'NANO', bright yellow and cyan letters, rain-slicked dark brick wall background, sharp text rendering, vibrant reflections",
  "negative_prompt": "misspelled, gibberish, broken letters, daylight, soft lighting",
  "strength": 0.70,
  "guidance_scale": 8.5
}
```

**关键词:** `neon sign`, `reading 'NANO'`, `sharp text`, `brick wall`

---

### 26. 硬核机甲换装

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

## 🎭 创意重绘

### 27. 水下世界场景

```json
{
  "prompt": "underwater scene transformation, coral reef surroundings, tropical fish swimming, caustic light effects, bubbles rising, submerged aesthetic, blue-green tones, marine life atmosphere",
  "negative_prompt": "dry land, normal air, no water effects, boring background",
  "strength": 0.78,
  "guidance_scale": 8.0
}
```

---

### 28. 太空宇宙场景

```json
{
  "prompt": "floating in deep space, nebula background, distant galaxies, stars everywhere, zero gravity effect, cosmic lighting, purple and blue cosmic colors, ethereal space atmosphere",
  "negative_prompt": "earth landscape, gravity, normal sky, grounded",
  "strength": 0.80,
  "guidance_scale": 8.0
}
```

---

### 29. 花卉艺术重绘

```json
{
  "prompt": "made entirely of flowers and botanical elements, floral composition, petals and leaves, organic transformation, nature art, blooming aesthetic, colorful petals, garden fantasy",
  "negative_prompt": "synthetic materials, metal, plastic, harsh textures",
  "strength": 0.82,
  "guidance_scale": 7.5
}
```

---

### 30. 金色雕像风格

```json
{
  "prompt": "transformed into golden statue, metallic gold surface, sculptural quality, ancient artifact style, polished bronze look, museum piece aesthetic, reflective metal texture",
  "negative_prompt": "organic skin, normal colors, fabric, wood, stone",
  "strength": 0.75,
  "guidance_scale": 7.5
}
```

---

### 31. 像素艺术风格

```json
{
  "prompt": "8-bit pixel art style, retro game aesthetic, limited color palette, blocky pixelated look, nostalgic video game style, crisp pixels, arcade game graphics",
  "negative_prompt": "smooth gradients, photorealistic, high detail, modern 3d",
  "strength": 0.85,
  "guidance_scale": 8.0
}
```

---

## 🔮 奇幻创意重绘

### 32. 科幻全息投影效果

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

### 33. 神秘塔罗牌插画

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

## 📡 API 调用示例

### Python 示例

```python
import requests
import base64

# Nano Banana API 调用
url = "https://api.nano-banana.com/v1/img2img"

# 读取并编码图片
with open("input.jpg", "rb") as f:
    image_base64 = base64.b64encode(f.read()).decode()

# 吉卜力风格迁移示例
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
result = response.json()
```

---

### cURL 示例

```bash
curl -X POST https://api.nano-banana.com/v1/img2img \
  -H "Authorization: Bearer YOUR_API_KEY" \
  -H "Content-Type: application/json" \
  -d '{
    "image": "'$(base64 -i input.jpg)'",
    "prompt": "cyberpunk aesthetic, neon lights, futuristic cityscape, blade runner style",
    "negative_prompt": "natural lighting, daylight, rural, vintage",
    "strength": 0.70,
    "guidance_scale": 8.0
  }'
```

---

## ⚙️ 参数指南

### Strength（重绘强度）

| 强度值 | 效果描述 | 适用场景 |
|--------|----------|----------|
| 0.3–0.4 | 轻微调整 | 图像增强、调色 |
| 0.4–0.5 | 细节优化 | 锐化、美颜、HDR |
| 0.5–0.7 | 风格迁移 | 油画、水彩、动漫化 |
| 0.6–0.8 | 局部编辑 | 换背景、换装 |
| 0.7–0.9 | 大幅重绘 | 创意转换、场景替换 |

### Guidance Scale（引导系数）

| 系数值 | 效果描述 |
|--------|----------|
| 5.0–6.5 | 更自由、更有创意 |
| 6.5–7.5 | 平衡模式（推荐） |
| 7.5–9.0 | 更严格遵循提示词 |
| 9.0+ | 提示词优先级极高 |

### 推荐组合

| 任务类型 | Strength | Guidance | Steps |
|----------|----------|----------|-------|
| 轻微增强 | 0.40 | 7.0 | 25 |
| 风格迁移 | 0.75 | 7.5 | 30 |
| 背景替换 | 0.68 | 7.5 | 28 |
| 大幅创意 | 0.80 | 8.0 | 35 |
| 人像美颜 | 0.40 | 6.5 | 25 |

---

## 🏷️ 关键词速查

### 艺术风格

```
oil painting, watercolor, pencil sketch, charcoal, impressionist, expressionist, surrealist, art nouveau, art deco, pop art, minimalist, abstract, realism, origami, stained glass
```

### 动漫 / 游戏

```
studio ghibli, makoto shinkai, 90s anime, cel shading, pixar, disney, valorant style, fortnite style, zelda style, pixel art
```

### 氛围 / 光线

```
golden hour, blue hour, dramatic lighting, cinematic lighting, neon glow, soft lighting, rim light, volumetric lighting, foggy, misty, holographic
```

### 材质 / 纹理

```
metallic, wooden, fabric, glass, crystal, marble, rusted, polished, rough, smooth, glittering, carbon fiber, craft paper
```

### 质量 / 质感增强

```
masterpiece, best quality, 8k, ultra detailed, sharp focus, professional, award winning, high fidelity, macro, bokeh, 35mm film, film grain
```