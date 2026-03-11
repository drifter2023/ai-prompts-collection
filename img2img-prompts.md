# 🖼️ AI 图像编辑 (img2img) Prompt 日报

*生成时间: 2026-02-27 17:00 UTC*  
*类型: 图生图 | 风格迁移 | 图像编辑 | 局部修改*

---

## 📊 今日内容

| 平台 | 模板数量 |
|------|---------|
| Midjourney | 9 个 |
| Stable Diffusion | 6 个 |
| Gemini/Imagen 3 | 5 个 |
| X/Twitter | 5 个 |
| 通用公式 | 4 个 |

---

## 🎨 Midjourney 图像编辑

### 风格迁移 — 照片转伦勃朗油画风格

**Prompt:**
```
[image URL] Transform this photo into an oil painting in the style of Rembrandt, dramatic lighting, rich textures, --iw 1.5 --s 750
```

**参数:** --iw 1.5 (图像权重), --s 750 (风格化)

**关键词:** style transfer, oil painting, classical art

---

### 风格迁移 — 吉卜力动画风格重绘

**Prompt:**
```
[image URL] Reimagine this as a Studio Ghibli animation, soft colors, hand-drawn aesthetic, whimsical atmosphere --iw 1.2
```

**参数:** --iw 1.2 保持原图特征

**关键词:** anime, ghibli, cartoon

---

### 风格迁移 — 赛博朋克风格转换

**Prompt:**
```
[image URL] Convert to cyberpunk aesthetic, neon lights, futuristic cityscape background, blade runner style --iw 1.0 --s 500
```

**参数:** --iw 1.0 允许更多变化

**关键词:** cyberpunk, neon, sci-fi

---

### 风格迁移 — 水彩画风格

**Prompt:**
```
[image URL] Transform into a watercolor painting, soft edges, flowing colors, artistic interpretation, paper texture --iw 1.3
```

**参数:** --iw 1.3 保持构图

**关键词:** watercolor, painting, artistic

---

### 风格迁移 — 复古合成器波风格

**Prompt:**
```
[image URL] Turn this into a 1980s retro synthwave artwork, vibrant purple and pink gradients, chrome reflections, palm trees, grid floor --iw 1.1
```

**参数:** --iw 1.1

**关键词:** synthwave, retro, 80s, vaporwave

---

### 局部编辑 — 更换背景为日落海滩

**Prompt:**
```
[image URL] Change the background to a sunset beach scene, golden hour lighting, keep the subject exactly the same --iw 2.0
```

**参数:** --iw 2.0 强制保持主体

**关键词:** background change, scene replace, sunset

---

### 局部编辑 — 添加皇冠和珠宝

**Prompt:**
```
[image URL] Add a crown and royal jewelry to the person, regal pose, maintain facial features --iw 1.8
```

**参数:** --iw 1.8 保持面部特征

**关键词:** add elements, accessories, jewelry

---

### 元素替换 — 更换服装为晚礼服

**Prompt:**
```
[image URL] Change the outfit to a formal evening gown, black silk, elegant, keep the pose and background --iw 1.5
```

**参数:** --iw 1.5 保持姿态和背景

**关键词:** clothing change, fashion, dress

---

### 图像增强 — 放大到4K并增强细节

**Prompt:**
```
[image URL] Upscale to 4K resolution, enhance details, sharp focus, professional photography quality, --iw 2.0 --q 2
```

**参数:** --iw 2.0, --q 2 (最高质量)

**关键词:** upscale, enhance, 4K, quality

---

## ⚙️ Stable Diffusion img2img

| 类型 | Denoising | 说明 |
|------|-----------|------|
| 图生图基础 | 0.60-0.75 | 基础图生图，提升细节 |
| 风格重绘-油画 | 0.65-0.80 | 厚涂油画风格 |
| 动漫化 | 0.70-0.85 | 照片转动漫 |
| 写实增强 | 0.40-0.60 | 写实照片增强 |
| 场景替换 | 0.65-0.80 | 替换背景 |
| 角色换装 | 0.55-0.70 | 角色换装，保持身份 |

### 详细设置

#### 图生图基础

**Prompt:**
```
masterpiece, best quality, (detailed face:1.2), (detailed eyes:1.3), [original subject], improved lighting, sharp focus
```

**Negative:**
```
(worst quality, low quality:1.4), blurry, deformed
```

**Denoising:** 0.60-0.75 | 基础图生图，提升细节

---

#### 风格重绘-油画

**Prompt:**
```
(oil painting:1.3), (impasto:1.2), visible brush strokes, rich colors, masterpiece, [subject], canvas texture
```

**Negative:**
```
photorealistic, digital art, smooth, lowres
```

**Denoising:** 0.65-0.80 | 厚涂油画风格

---

#### 动漫化

**Prompt:**
```
anime style, cel shading, vibrant colors, clean lines, detailed face, masterpiece, from photo, [subject]
```

**Negative:**
```
photorealistic, 3d render, western cartoon, blurry
```

**Denoising:** 0.70-0.85 | 照片转动漫

---

#### 写实增强

**Prompt:**
```
photorealistic, 8k, ultra detailed, (sharp focus:1.2), professional photography, enhanced, [subject]
```

**Negative:**
```
painting, drawing, cartoon, anime, lowres, blurry
```

**Denoising:** 0.40-0.60 | 写实照片增强

---

#### 场景替换

**Prompt:**
```
same [subject], (new background: [description]:1.2), consistent lighting, seamless integration, natural shadows
```

**Negative:**
```
mismatched lighting, floating, disconnected
```

**Denoising:** 0.65-0.80 | 替换背景

---

#### 角色换装

**Prompt:**
```
[subject], wearing [new outfit], same pose, same lighting, maintain identity, detailed fabric texture
```

**Negative:**
```
different person, changed face, distorted
```

**Denoising:** 0.55-0.70 | 角色换装，保持身份

---

## 🤖 Gemini/Imagen 3 编辑

### 基础编辑

**模板:**
```
Based on this image, [描述修改]. Maintain the original composition but change [具体元素].
```

**示例:**
```
Based on this image, add a sunset background with orange and pink colors. Maintain the original composition but change the sky.
```

💡 直接描述你想要的修改

---

### 风格转换

**模板:**
```
Transform this image into a [艺术风格] version. Keep the subject the same but apply [风格特征].
```

**示例:**
```
Transform this image into a watercolor painting version. Keep the subject the same but apply soft edges and flowing colors.
```

💡 Gemini 擅长理解和应用艺术风格

---

### 元素添加

**模板:**
```
Add [元素] to this image. The [元素] should [描述] and blend naturally with the existing scene.
```

**示例:**
```
Add a cat sitting on the windowsill to this image. The cat should be orange and blend naturally with the existing scene.
```

💡 详细描述新元素的外观和位置

---

### 元素移除

**模板:**
```
Remove the [元素] from this image and fill in the background naturally. The result should look seamless.
```

**示例:**
```
Remove the person from this image and fill in the background naturally. The result should look seamless.
```

💡 Gemini 会自动补全被移除区域的背景

---

### 颜色调整

**模板:**
```
Change the color scheme of this image to [色调]. Adjust the mood to be [氛围描述].
```

**示例:**
```
Change the color scheme of this image to warm autumn tones. Adjust the mood to be cozy and nostalgic.
```

💡 描述情绪比具体RGB值更有效

---

## 🐦 X/Twitter 热门编辑 Prompt

> 关注这些账号获取更多 prompt：
> @AIArtistDaily @RetroAI_Art @PhotoEditAI @EnhanceAI @CreativeAI_Daily
> 
> 搜索标签: `#AIPrompt` `#ImageToImage` `#AIEditing` `#StyleTransfer`

### 风格迁移 — Ghibli 风格转换

**Prompt:**
```
[image] Transform into Studio Ghibli style, hand-painted aesthetic, soft watercolor textures --iw 1.3
```

**作者:** @AIArtistDaily  
**标签:** #GhibliStyle, #AIArt, #ImageToImage

---

### 风格迁移 — 复古合成器波风格

**Prompt:**
```
[image] Reimagine as 80s retro album cover, neon gradients, chrome typography, synthwave vibes --iw 1.0
```

**作者:** @RetroAI_Art  
**标签:** #Synthwave, #RetroArt, #AIEdit

---

### 局部编辑 — 季节转换

**Prompt:**
```
[image] Change season to winter, add snow, frosty atmosphere, keep composition --iw 1.8
```

**作者:** @PhotoEditAI  
**标签:** #SeasonChange, #WinterVibes, #AIEditing

---

### 图像增强 — 8K 放大增强

**Prompt:**
```
[image] Upscale to 8K, enhance micro-details, HDR processing, professional retouch --iw 2.0
```

**作者:** @EnhanceAI  
**标签:** #Upscale, #8K, #PhotoEnhancement

---

### 创意编辑 — 移轴微缩效果

**Prompt:**
```
[image] Turn into a miniature tilt-shift diorama, toy-like appearance, shallow depth of field --iw 1.2
```

**作者:** @CreativeAI_Daily  
**标签:** #TiltShift, #Miniature, #CreativeEdit

---

## 🧮 万能编辑公式

### 风格迁移公式

**公式:**
```
[原图] + "transform into [风格]" + [质量词]
```

**示例:**
- `oil painting with visible brush strokes, Rembrandt lighting`
- `1970s anime cel shading, vibrant colors`
- `hyper-realistic digital art, 8k details`
- `van Gogh style with swirling brushwork`
- `cyberpunk neon aesthetic, futuristic`

**推荐参数:**
- Stable Diffusion Denoising: 0.5-0.7
- Midjourney Image Weight: 1.0-1.5

---

### 局部编辑公式

**公式:**
```
[原图] + "[add/remove/change] [元素]" + [位置] + [细节]
```

**示例:**
- `Add sunglasses to the person, reflective lenses, modern style`
- `Remove the background crowd, fill with blurred cityscape`
- `Change the dress color to red, silk fabric, same lighting`
- `Add a hat, wide brim, straw texture, summer style`
- `Replace the phone with a vintage camera, maintain hand pose`

**推荐参数:**
- Stable Diffusion Denoising: 0.6-0.8
- Midjourney Image Weight: 1.5-2.0

---

### 图像增强公式

**公式:**
```
[原图] + "upscale/enhance" + [目标质量] + [细节要求]
```

**示例:**
- `Upscale to 4K, enhance facial details, sharp eyes`
- `HDR quality, improve dynamic range, vivid colors`
- `Professional retouching, smooth skin, keep natural texture`
- `Sharpen focus, fix motion blur, enhance clarity`
- `Restore faded colors, fix exposure, brighten shadows`

**推荐参数:**
- Stable Diffusion Denoising: 0.3-0.5
- Midjourney Image Weight: 1.8-2.0

---

### 创意重绘公式

**公式:**
```
[原图] + "reimagine as" + [新概念] + [风格形容词]
```

**示例:**
- `Steampunk version with brass gears and steam pipes`
- `Underwater scene with coral reef and tropical fish`
- `Made entirely of flowers and botanical elements`
- `Floating in space with galaxies in background`
- `Miniature diorama with tilt-shift effect`

**推荐参数:**
- Stable Diffusion Denoising: 0.7-0.9
- Midjourney Image Weight: 0.8-1.2

---

## 📚 关键词速查手册

### 风格迁移关键词

```
oil painting, watercolor, pencil sketch, charcoal drawing, impressionist, expressionist, surrealist, art nouveau, art deco, bauhaus, minimalist, pop art, street art, graffiti, comic book
```

### 光线关键词

```
golden hour, blue hour, magic hour, sunrise, sunset, soft lighting, hard lighting, dramatic lighting, moody lighting, rim lighting, backlight, side light, top light, cinematic lighting, studio lighting
```

### 相机/技术关键词

```
dslr, mirrorless, film camera, polaroid, 35mm lens, 50mm lens, 85mm lens, 135mm lens, 200mm lens, wide angle, telephoto, macro, fisheye, f/1.4, f/1.8
```

### 编辑操作关键词

```
style transfer, image to image, img2img, inpainting, outpainting, background removal, object removal, object addition, scene replacement, color grading, color correction, white balance, sharpening, denoising, upscaling
```

### 质量增强关键词

```
8k, 4k, high resolution, ultra detailed, masterpiece, best quality, award winning, sharp focus, crisp, clear, photorealistic, hyperrealistic, lifelike, professional, commercial quality
```

### 艺术家风格

```
van gogh, monet, renoir, degas, picasso, dali, kandinsky, mondrian, mucha, klimt, hokusai, hiroshige, da vinci, michelangelo, raphael
```

### 动漫/游戏风格

```
studio ghibli, makoto shinkai, hayao miyazaki, pixar, disney, dreamworks, laika, japanese anime, korean manhwa, chinese donghua, fortnite, valorant, overwatch, zelda, final fantasy
```

## 🛠️ 各平台操作指南

### Midjourney
```
[图片URL] 你的提示词 --iw 1.5 --s 750
```
- `--iw 0.5-2.0`: 图像权重，越高越像原图
- `--s 0-1000`: 风格化程度
- `--q 2`: 最高质量

### Stable Diffusion (WebUI)
1. 切换到 **img2img** 标签
2. 上传图片到 **Init Image**
3. 调整 **Denoising strength**:
   - 0.3-0.5: 轻微调整/增强
   - 0.5-0.7: 风格迁移
   - 0.7-0.9: 大幅重绘
4. 可选: 启用 **ControlNet** 保持姿态

### ComfyUI 工作流
```
Load Image → VAE Encode → KSampler (img2img)
                ↓
         ControlNet Apply (可选)
                ↓
         VAE Decode → Save Image
```

### Gemini API
```python
response = model.generate_content([
    '基于这张图片，添加一个日落背景',
    image
])
```

## 🎯 参数速查表

| 目标效果 | SD Denoising | MJ --iw | 备注 |
|----------|-------------|---------|------|
| 轻微调色 | 0.3-0.4 | 2.0 | 几乎保持原图 |
| 增强细节 | 0.4-0.5 | 1.8-2.0 | 修复模糊照片 |
| 风格迁移 | 0.5-0.7 | 1.0-1.5 | 油画/水彩等 |
| 场景替换 | 0.6-0.8 | 1.5-1.8 | 换背景 |
| 大幅重绘 | 0.7-0.9 | 0.5-1.0 | 创意改造 |
| 仅换脸 | 0.5-0.6 | 1.5 | 用 ControlNet |

## 🔗 推荐工具

| 工具 | 特点 | 适用场景 |
|------|------|---------|
| [AUTOMATIC1111](https://github.com/AUTOMATIC1111/stable-diffusion-webui) | 功能最全 | 本地 img2img |
| [ComfyUI](https://github.com/comfyanonymous/ComfyUI) | 节点工作流 | 复杂编辑流程 |
| [Fooocus](https://github.com/lllyasviel/Fooocus) | 简单易用 | 快速风格迁移 |
| [Leonardo.ai](https://leonardo.ai) | 在线工具 | 免安装编辑 |
| [Clipdrop](https://clipdrop.co) | Stability AI | 专业修图工具 |

---
*自动收集 by OpenClaw* 🦀

---

## 🆕 增量编辑 Prompt (2026-03-11)

### 1. 折射玻璃肖像重绘（Reeded Glass Distortion）

**Prompt:**
```
[image URL] Re-render this portrait as if photographed through thick vertically reeded architectural glass, strong vertical optical refraction, soft studio light, pale neutral background, keep subject identity recognizable --iw 1.4
```

**适用:** Midjourney / SD img2img

---

### 2. 蓝图科技风叠加（Blueprint Overlay）

**Prompt:**
```
[image URL] Transform into a sci-fi concept sheet style with subtle blueprint line overlays and technical sketch annotations around the subject, keep core silhouette and facial features --iw 1.3
```

**适用:** SDXL img2img + ControlNet lineart

---

### 3. 电影感肤质保留增强（Skin-Preserving Cinematic Grade）

**Prompt:**
```
[image URL] Apply cinematic color grading with natural skin tone preservation, shallow depth-of-field simulation, gentle bokeh background, maintain original facial structure exactly --iw 1.8
```

**适用:** 人像精修流程

---

### 4. 老片胶片化转换（35mm Portra Look）

**Prompt:**
```
[image URL] Convert this image into a 35mm Kodak Portra-style film photograph, subtle grain, realistic contrast roll-off, slight motion energy, documentary street mood --iw 1.2
```

**适用:** 人文/街拍图像

---

### 5. 赛博材质替换（Cyber Material Swap）

**Prompt:**
```
[image URL] Replace clothing and accessories with reflective black alloy cyberpunk materials, add precise mechanical detailing and neon rim light, preserve pose and composition --iw 1.5
```

**适用:** 角色风格化

---

### 6. 商业产品棚拍重构（Product Hero Relight）

**Prompt:**
```
[image URL] Rebuild this object into a premium commercial hero shot with controlled three-point studio lighting, clean gradient backdrop, crisp reflections, and ad-quality detail --iw 1.6
```

**适用:** 产品图升级/电商主图

---

## 🆕 img2img 全类型专项更新 (2026-03-11)

> 目标：覆盖“任何类型”的 img2img，用独立条目拆分，不合并。

### 7. 人像保脸 + 光线重置 (Face Lock + Relight)

**Prompt:**
```
[image URL] Keep the exact same identity and facial geometry, regenerate with cinematic side lighting, clean skin texture, subtle film grain, shallow depth of field, realistic 85mm lens rendering --iw 2.0
```

**关键词:** face consistency, relight, portrait enhancement

---

### 8. 白天改夜景 (Day-to-Night Conversion)

**Prompt:**
```
[image URL] Convert this daytime street scene into night, add neon signage reflections on wet ground, cool ambient shadows, practical light sources from shop windows, cinematic contrast --iw 1.6
```

**关键词:** day to night, relighting, environment conversion

---

### 9. 天气改造：晴天转雨天

**Prompt:**
```
[image URL] Transform clear weather into rainy atmosphere, add rainfall streaks, wet surfaces, puddle reflections, overcast sky, realistic moisture on materials while preserving original composition --iw 1.5
```

**关键词:** weather transfer, rain effect, mood change

---

### 10. 季节迁移：夏到冬

**Prompt:**
```
[image URL] Change season from summer to winter, replace foliage with sparse frosted branches, add thin snow cover, cool color temperature, soft winter haze, keep perspective and structure unchanged --iw 1.4
```

**关键词:** season transfer, environment swap

---

### 11. 写实照片转动漫

**Prompt:**
```
[image URL] Reinterpret this photo in high-quality anime style, clean linework, cel-shading, expressive eyes, controlled color blocks, keep original pose and camera framing --iw 1.3 --stylize 600
```

**关键词:** photo to anime, stylization

---

### 12. 动漫转写实

**Prompt:**
```
[image URL] Convert anime illustration into photorealistic cinematic portrait, natural skin texture, physically plausible lighting, realistic materials and depth, preserve hairstyle and outfit silhouette --iw 1.5
```

**关键词:** anime to real, realism transfer

---

### 13. 线稿上色 (Sketch-to-Render)

**Prompt:**
```
[image URL] Colorize and fully render this line art into polished concept art, retain original line composition, add material definition, global illumination, and production-quality shading --iw 1.7
```

**关键词:** sketch to render, concept art

---

### 14. 建筑旧改新（Facade Renovation）

**Prompt:**
```
[image URL] Redesign this building facade into modern minimalist architecture, replace exterior materials with concrete/glass/wood, balanced daylight, realistic construction details, keep structural proportions --iw 1.5
```

**关键词:** architecture redesign, facade remaster

---

### 15. 产品重拍：随手拍→商业图

**Prompt:**
```
[image URL] Turn this casual product photo into a premium studio advertisement shot, clean gradient background, controlled highlights, micro-detail texture, sharp edges, luxury branding aesthetic --iw 1.8
```

**关键词:** product relight, ad photography

---

### 16. LOGO/文字保留的海报重绘

**Prompt:**
```
[image URL] Recompose into a modern poster design while preserving key logo/text areas exactly, enhance typography hierarchy, cinematic background graphics, clean visual balance --iw 1.9
```

**关键词:** poster redesign, text-preserving img2img

---

### 17. 局部替换：服装材质升级

**Prompt:**
```
[image URL] Keep person identity and pose unchanged, replace clothing fabric with black silk and metallic accents, realistic folds, specular highlights, editorial fashion look --iw 1.7
```

**关键词:** outfit swap, material editing

---

### 18. 局部替换：发型与发色

**Prompt:**
```
[image URL] Keep face identity unchanged, change hairstyle to layered shoulder-length cut with silver-lavender hair color, natural strands, realistic volume, studio portrait quality --iw 1.8
```

**关键词:** hairstyle transfer, identity-safe edit

---

### 19. 背景替换：室内到科幻街景

**Prompt:**
```
[image URL] Preserve subject scale and position, replace background with futuristic cyberpunk street, holographic ads, atmospheric fog, wet pavement reflections, strong depth perspective --iw 1.6
```

**关键词:** background replacement, scene expansion

---

### 20. 景深重建：手机平图→电影感

**Prompt:**
```
[image URL] Rebuild this flat smartphone shot with cinematic depth, strong subject separation, realistic foreground/background blur falloff, subtle filmic color grading --iw 1.4
```

**关键词:** depth reconstruction, cinematic enhancement

---

### 21. 运动模糊增强（动态感重建）

**Prompt:**
```
[image URL] Keep the main subject readable but add directional motion blur to limbs/background, dynamic shutter feel, action-photography energy, realistic light streak behavior --iw 1.3
```

**关键词:** motion enhancement, action stylization

---

### 22. 老照片修复 + 上色

**Prompt:**
```
[image URL] Restore this old damaged photo: remove scratches and noise, reconstruct missing details, natural skin tones, historically plausible colorization, preserve original expression and composition --iw 1.9
```

**关键词:** restoration, colorization

---

### 23. 低清放大重绘（HQ Upscale Regeneration）

**Prompt:**
```
[image URL] Regenerate this low-resolution image into high-resolution detailed output, preserve overall composition, improve texture fidelity, clean edges, remove compression artifacts --iw 1.8
```

**关键词:** upscale, super-resolution style regeneration

---

### 24. 商品场景化（Packshot to Lifestyle）

**Prompt:**
```
[image URL] Keep the product shape and branding exact, place it naturally in a lifestyle scene (e.g., modern desk/cafe/bathroom), realistic shadows and contact lighting, commercial-grade composition --iw 1.7
```

**关键词:** packshot to lifestyle, scene integration
