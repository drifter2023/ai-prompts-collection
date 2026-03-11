# 视频生成 (Video Generation) Prompt 合集

*整合自: video-prompts.md*
*分类方式: 按主题/对象分类*
*支持平台: Runway, Pika, Sora, Luma, Stable Video Diffusion*

---

## 目录

- [城市 / 都市场景](#城市--都市场景)
- [自然 / 风景](#自然--风景)
- [人物 / 角色](#人物--角色)
- [动物](#动物)
- [产品](#产品)
- [抽象 / 艺术](#抽象--艺术)
- [微距 / 自然细节](#微距--自然细节)
- [氛围 / 情绪](#氛围--情绪)
- [历史](#历史)
- [技术 (图转视频)](#技术-图转视频)
- [公式与参考](#公式与参考)

---

## 城市 / 都市场景

### 赛博朋克城市航拍

**平台:** Runway Gen-2/3

**Prompt:**
```
A cinematic aerial shot of a cyberpunk city at night, neon lights reflecting on wet streets, flying cars, rain, 4k, photorealistic
```

**参数:** Camera: Drone / Motion: Sweeping
**提示:** Runway 擅长处理相机运动和光照效果

---

### 东京街头女人行走

**平台:** Sora (OpenAI)

**Prompt:**
```
A stylish woman walks down a Tokyo street filled with warm glowing neon and animated city signage. She wears a black leather jacket, red dress, and black boots, and carries a black purse. She wears sunglasses and red lipstick. She walks confidently and casually. The street is damp and reflective, creating a mirror effect of the colorful lights. Many pedestrians walk about.
```

**时长:** 60s
**提示:** Sora 可以生成长达 60 秒的连贯视频

---

### 曼谷夜市 POV 视角

**平台:** Luma Dream Machine

**Prompt:**
```
POV shot walking through a bustling night market in Bangkok, street food vendors, neon signs, steam rising from food stalls, handheld camera feel
```

**提示:** POV (第一人称) 创造沉浸式体验

---

### 城市天际线日转夜延时

**平台:** Luma Dream Machine

**Prompt:**
```
Time-lapse of city skyline from day to night, clouds moving rapidly, lights turning on in buildings, stars appearing
```

**提示:** Time-lapse 适合展示时间流逝

---

## 自然 / 风景

### 悬崖海浪

**平台:** Runway Gen-2/3

**Prompt:**
```
Slow motion shot of ocean waves crashing on rocky cliffs, golden hour sunlight, mist rising, cinematic color grading
```

**参数:** Camera: Low angle / Motion: Slow push-in
**提示:** 使用 slow motion 可以获得更流畅的慢动作效果

---

### 灯塔航拍循环

**平台:** Sora (OpenAI)

**Prompt:**
```
Aerial view of a lighthouse standing on a rocky cliff, ocean waves crashing, seamless loop, drone orbiting motion
```

**时长:** Loop
**提示:** 指定 seamless loop 可以创建循环播放视频

---

### 北极光 (公式示例)

**平台:** Runway / Luma / Sora

**Prompt:**
```
Aerial view of northern lights over snowy mountains, nighttime, time-lapse, ethereal and magical, 8k, highly detailed
```

**公式:** `[视角] of [自然场景], [时间/天气], [相机运动], [情绪形容词], [质量参数]`

---

### 沙漠牛仔 (公式示例)

**平台:** Runway / Sora / Luma

**Prompt:**
```
Wide shot of a lone cowboy riding through desert at sunset, golden hour lighting, drone following shot, cinematic, 4k, film grain
```

**公式:** `[镜头类型] of [主体] [动作], [环境描述], [光线条件], [相机运动], [风格/质量]`

---

## 人物 / 角色

### 仓库中的舞者

**平台:** Runway Gen-2/3

**Prompt:**
```
Medium shot of a dancer spinning in an empty warehouse, dust particles in sunlight, dramatic side lighting, motion blur
```

**参数:** Camera: Static / Subject: dancer
**提示:** 明确指定相机场位 (close-up, medium, wide)

---

### 芭蕾舞演员旋转 (公式示例)

**平台:** Pika / Runway / Sora

**Prompt:**
```
Medium shot of ballerina performing pirouette, flowing white dress, empty theater stage, dramatic spotlight, slow motion, elegant
```

**公式:** `[镜头类型] of [角色] [动作描述], [服装/外观], [环境], [情绪/氛围], [相机运动]`

---

### 法师施法

**平台:** Pika Labs

**Prompt:**
```
Wizard casting spell, magical particles exploding, dramatic lighting, particles forming into dragon shape, fantasy atmosphere
```

**参数:** `-motion 5 -camera pan_right`
**提示:** 使用 -motion 参数控制运动强度 (1-5)

---

## 动物

### 蚂蚁特写到远景

**平台:** Sora (OpenAI)

**Prompt:**
```
Extreme close-up of an ant emerging from its nest. The camera pulls back revealing a neighborhood beyond the hill.
```

**时长:** 20s
**提示:** 使用 extreme close-up 开始可以获得戏剧性效果

---

### 金毛犬播客

**平台:** Sora (OpenAI)

**Prompt:**
```
Two golden retrievers podcasting on top of a mountain, realistic fur physics, snow falling, professional podcast microphones visible
```

**时长:** 30s
**提示:** Sora 擅长处理物理效果和物体交互

---

## 产品

### 跑车旋转台

**平台:** Runway Gen-2/3

**Prompt:**
```
Sleek sports car rotating on a platform, dramatic studio lighting, reflections on polished floor, 360 degree view
```

**参数:** Motion: Turntable / Lighting: Studio
**提示:** turntable 旋转适合产品展示

---

### 奢侈手表 (公式示例)

**平台:** Runway / SVD / Luma

**Prompt:**
```
Luxury watch rotating on display stand, brushed titanium and sapphire crystal, studio lighting with softbox, gradient background, macro orbiting shot
```

**公式:** `[产品] [运动/展示方式], [材质细节], [光照设置], [背景], [相机运动]`

---

## 抽象 / 艺术

### 流体模拟抽象

**平台:** Runway Gen-2/3

**Prompt:**
```
Abstract fluid simulation, iridescent colors morphing into organic shapes, seamless loop, ethereal atmosphere
```

**参数:** Style: Abstract / Loop: Yes
**提示:** Gen-2 适合抽象和风格化内容

---

### 蝴蝶变形花朵

**平台:** Luma Dream Machine

**Prompt:**
```
Smooth morphing transition from butterfly to flower petals, intricate details, nature documentary style, macro lens
```

**提示:** Luma 擅长创建平滑的变形效果

---

## 微距 / 自然细节

### 水滴微距

**平台:** Pika Labs

**Prompt:**
```
Macro shot of water droplet falling into still pond, slow motion ripple effect, crystal clear water, sunlight refraction
```

**参数:** `-motion 2 -camera static`
**提示:** 低 motion 值适合需要稳定性的场景

---

### 烟雾/粒子效果

**平台:** Stable Video Diffusion

**Prompt:**
```
Smoke swirling and dissipating, backlit by warm sunlight, atmospheric, 4k quality
```

**说明:** 生成粒子/流体效果
**提示:** SVD 擅长处理烟雾、云、水等效果

---

## 氛围 / 情绪

### 黑暗走廊恐怖场景

**平台:** Pika Labs

**Prompt:**
```
Dark hallway with flickering lights, shadow figure at end of corridor, creepy atmosphere, film grain, found footage style
```

**参数:** `-motion 1 -camera shake`
**提示:** shake 相机运动增加手持感

---

### 动漫樱花场景

**平台:** Pika Labs

**Prompt:**
```
Anime style girl walking through cherry blossom forest, petals falling, soft pastel colors, Studio Ghibli inspired, gentle breeze
```

**参数:** `-motion 3 -camera zoom_in`
**提示:** Pika 对动漫和风格化内容效果出色

---

## 历史

### 加利福尼亚淘金热

**平台:** Sora (OpenAI)

**Prompt:**
```
Historical footage of California during the gold rush. An aerial view shows miners working in a river, panning for gold.
```

**时长:** 40s
**提示:** Sora 可以理解历史背景和时代特征

---

## 技术 (图转视频)

### Ken Burns 效果 (图像转视频)

**平台:** Stable Video Diffusion

**Prompt:**
```
[Input image] Gentle camera movement revealing more of the landscape, subtle parallax effect, depth of field shift
```

**说明:** 从静态图像生成微妙运动
**提示:** 适合给照片添加 Ken Burns 效果

---

### 角色肖像动画

**平台:** Stable Video Diffusion

**Prompt:**
```
Character portrait subtle animation, breathing motion, eyes blinking, slight head movement, realistic skin texture
```

**说明:** 让静态肖像动起来
**提示:** 适合社交媒体头像动画

---

## 公式与参考

### 5 个万能视频公式

#### 1. 电影级场景公式

```
[镜头类型] of [主体] [动作], [环境描述], [光线条件], [相机运动], [风格/质量]
```
适用平台: Runway, Sora, Luma

---

#### 2. 角色动作公式

```
[镜头类型] of [角色] [动作描述], [服装/外观], [环境], [情绪/氛围], [相机运动]
```
适用平台: Pika, Runway, Sora

---

#### 3. 自然风景公式

```
[视角] of [自然场景], [时间/天气], [相机运动], [情绪形容词], [质量参数]
```
适用平台: Runway, Luma, Sora

---

#### 4. 抽象/艺术公式

```
[抽象元素] [运动方式], [颜色/材质], [光照效果], [风格参考], [循环参数]
```
适用平台: Runway Gen-2, Pika, SVD

---

#### 5. 产品展示公式

```
[产品] [运动/展示方式], [材质细节], [光照设置], [背景], [相机运动]
```
适用平台: Runway, SVD, Luma

---

### 相机运动关键词

```
static, pan left/right, tilt up/down, zoom in/out, dolly in/out, truck left/right, pedestal up/down, orbit/arc shot, handheld, gimbal smooth, drone aerial, crane shot
```

---

### 镜头类型关键词

```
extreme close-up (ECU), close-up (CU), medium shot (MS), medium close-up (MCU), wide shot (WS), extreme wide shot (EWS), over-the-shoulder (OTS), point-of-view (POV), aerial shot, establishing shot, master shot, tracking shot
```

---

### 运动描述关键词

```
slow motion, time-lapse, hyperlapse, motion blur, fast motion, freeze frame, speed ramp, seamless loop, continuous shot, one-take, long take
```

---

### 光影效果关键词

```
golden hour, blue hour, magic hour, golden ratio lighting, rim lighting, dramatic lighting, volumetric lighting, god rays, lens flare, bloom, caustics, subsurface scattering
```

---

### 风格修饰关键词

```
cinematic, photorealistic, hyperrealistic, film grain, anamorphic lens, bokeh, depth of field, shallow focus, vintage film, noir, cyberpunk, retro aesthetic
```

---

### 质量参数关键词

```
4k, 8k, high definition, ultra HD, sharp focus, highly detailed, masterpiece, professional quality, broadcast quality, imax quality
```

---

### 各平台使用技巧

#### Runway Gen-3
- **最大时长:** 10秒 (Gen-3), 4秒 (Gen-2)
- **最佳分辨率:** 1080p
- **提示技巧:** 详细描述相机运动和光照
- **特点:** 电影级质量，强大的运动控制

#### Pika Labs
- **最大时长:** 4秒
- **Discord:** `/create` 命令
- **参数:** `-motion 1-5`, `-camera [movement]`
- **特点:** 风格化内容，动漫效果出色

#### Sora (OpenAI)
- **最大时长:** 60秒
- **分辨率:** 最高 1920x1080
- **特点:** 最长时长，物理模拟强
- **提示技巧:** 像写电影剧本一样详细

#### Luma Dream Machine
- **最大时长:** 5秒
- **特点:** 快速生成，变形效果平滑
- **最佳用途:** 第一人称视角，创意过渡

#### Stable Video Diffusion
- **最大时长:** 4秒
- **特点:** 开源，可本地运行
- **最佳用途:** 图像转视频，粒子效果

---

### 平台链接

- [Runway](https://runwayml.com) - 最专业的视频生成
- [Pika Labs](https://pika.art) - Discord 社区驱动
- [Luma Dream Machine](https://lumalabs.ai) - 快速创意生成
- [Stable Video](https://stability.ai/stable-video) - 开源方案
