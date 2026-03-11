# 摄影风格 (Photography Styles) Prompt 合集

*按镜头、胶片、灯光、风格分类 | 适用于 Midjourney, FLUX, Stable Diffusion, Gemini, Nano Banana 等*

---

## 目录

- [万能公式](#万能公式)
- [镜头与焦距](#镜头与焦距)
- [胶片与色彩科学](#胶片与色彩科学)
- [灯光模式](#灯光模式)
- [摄影风格](#摄影风格)
- [相机机身](#相机机身)
- [真实感增强技巧](#真实感增强技巧)
- [快速参考表](#快速参考表)

---

## 万能公式

### 基础公式

```
[主体] + [介质/媒介] + [灯光] + [宽高比]
```

示例: `woman sitting in a cafe, analog 35mm photography, golden hour window light --ar 4:5`

### 进阶公式 (Cinematic Prompt Method)

```
[主体] + [环境] + [灯光] + [相机机身 + 镜头 + 光圈] + [胶片/色彩风格] + [质量词]
```

示例:
```
candid portrait of an elderly man with deep wrinkles and kind eyes, wearing a weathered wool sweater, sitting in a dimly lit library, soft ambient light, shot on Sony A7R IV, 85mm f/1.8 lens, Kodak Portra 400 tones, sharp focus on eyes, 8k resolution, photorealistic
```

### Shot Grammar 框架 (2026)

8 要素系统，适合最精确的控制:

```
1. Subject & Action — 主体与动作
2. Emotional Energy — 情绪能量
3. Camera Optics — 镜头焦距、光圈、景深
4. Motion — 相机运动 (静态/推拉/摇移)
5. Lighting Physics — 主灯/补光/轮廓光 + 色温
6. Color Science — 胶片模拟 / LUT / 调色
7. Environment — 环境、时间、天气
8. Quality & Imperfections — 分辨率、颗粒、瑕疵
```

**完整示例:**
```
A woman in her early 30s with sun-kissed freckles, auburn hair loosely falling past her shoulders, gazing directly into the camera. Sun-drenched wheat field at golden hour. Warm backlighting from the setting sun creating a golden halo, soft fill light from a reflector. Rich amber, honey gold, and warm sienna tones. Medium close-up, shot at f/1.4 with an 85mm lens, extremely shallow depth of field. Cinematic photography, anamorphic lens quality, film grain texture. 8K resolution, ultra-detailed skin texture, hyper-realistic.
```

---

## 镜头与焦距

### 超广角 (14–24mm)

**特性:** 夸张透视、广阔空间感、前景/背景比例差异大、边缘畸变
**适用:** 建筑、风景、室内、戏剧性环境人像

```
environmental portrait of a craftsman in his workshop, 14mm ultra-wide lens, dramatic foreground-background scale, warm interior light, visible tools and materials, documentary realism, Nikon D850
```

```
interior architecture photograph of a modern cathedral, 24mm wide-angle, converging vertical lines, dramatic scale, soft diffused light from stained glass, editorial quality
```

**关键词:** `14mm`, `24mm`, `ultra-wide`, `wide-angle lens`, `dramatic perspective`, `expansive scene`, `environmental storytelling`, `converging lines`

---

### 广角 (28–35mm)

**特性:** 自然但略宽于人眼、可纳入环境背景、轻微透视、报道感
**适用:** 街拍、纪实、旅行、情侣、环境人像

```
candid street photography in a rainy Paris alley, 35mm lens, Kodak Portra 400 tones, golden hour reflections on wet cobblestones, documentary style, natural moment, slight motion blur on passersby
```

```
travel photograph of a local market in Marrakech, 28mm lens, vivid colors, bustling atmosphere, natural light, Fujifilm Superia 400, authentic candid moment
```

**关键词:** `28mm`, `35mm lens`, `street photography`, `environmental portrait`, `documentary feel`, `natural perspective`, `reportage`

---

### 标准 (50mm)

**特性:** 最接近人眼视角、无畸变、中性万能、经典 "nifty fifty"
**适用:** 通用人像、街拍、食物、日常、艺术

```
portrait of a woman reading in a cafe, 50mm f/1.8, soft natural window light from left, shallow depth of field, warm afternoon tones, Fujifilm X-T4, subtle film grain, natural skin texture
```

```
film noir portrait of a detective in a rain-soaked alley, 50mm lens, 1940s aesthetic, dramatic chiaroscuro, deep shadows, cigarette smoke, high-contrast black and white, heavy grain
```

**关键词:** `50mm lens`, `nifty fifty`, `natural perspective`, `neutral realism`, `human-eye view`, `standard lens`

---

### 人像中长焦 (85–105mm)

**特性:** 最讨喜的面部压缩、奶油般散景、主体分离、无畸变
**适用:** 头像、美妆、时尚大片、人像特写

```
close-up portrait, 85mm f/1.4, natural side window light, creamy smooth bokeh background, realistic skin pore detail, Sony A7IV, filmic color grading, Kodak Portra 400
```

```
beauty portrait of a model with flawless skin, 100mm macro lens, studio ring light, extreme close-up on eyes, catch light reflections, editorial beauty photography
```

```
8K portrait of a woman under golden hour sunlight, fine film grain texture, visible lens flare on edges, Kodak Portra 400 color tones, Canon 85mm f/1.4 depth, soft highlight roll-off, warm skin tone gradients
```

**关键词:** `85mm f/1.4`, `85mm portrait lens`, `100mm macro`, `compressed perspective`, `shallow depth of field`, `creamy bokeh`, `subject isolation`, `flattering compression`

---

### 中长焦 (135mm)

**特性:** 极佳的背景分离、强压缩效果、适合头肩像
**适用:** 头肩人像、高级人像、毕业照、局部特写

```
headshot portrait of a musician, 135mm f/2, completely blurred background, strong subject separation, natural outdoor light, warm color grading, professional studio quality
```

**关键词:** `135mm lens`, `strong background separation`, `telephoto compression`, `head-and-shoulders`, `extreme bokeh`

---

### 长焦 (200mm+)

**特性:** 极强背景压缩、远距拍摄主体放大、环境与主体完全隔离
**适用:** 野生动物、体育、远距人像、城市层叠压缩

```
wildlife photography of a tiger stalking through tall grass, 400mm telephoto lens, shallow depth of field, golden hour backlight, National Geographic style, compressed background layers
```

```
sports photography of a sprinter at the finish line, 200mm f/2.8, frozen motion, dramatic stadium lighting, rain droplets suspended mid-air, high shutter speed
```

**关键词:** `200mm`, `300mm`, `400mm`, `telephoto`, `background compression`, `wildlife lens`, `subject magnification`, `sports photography`

---

### 微距 (Macro)

**特性:** 极端近摄、极浅景深、抽象质感、细节放大
**适用:** 昆虫、首饰、花卉、水滴、纹理、产品细节

```
macro photography of a dewdrop on a spider web, 100mm macro lens, morning golden light, iridescent reflections, razor-thin depth of field, National Geographic quality
```

```
extreme macro shot of a butterfly wing, revealing scales and patterns, 100mm macro f/2.8, studio LED ring light, black background, scientific detail
```

**关键词:** `100mm macro`, `macro photography`, `extreme close-up`, `shallow depth of field`, `high detail texture`, `1:1 magnification`

---

### 鱼眼 (Fisheye)

**特性:** 严重桶形畸变、180° 视角、超现实/动感
**适用:** 滑板、极限运动、创意人像、室内全景

```
skateboarder mid-kickflip at a concrete skate park, 8mm fisheye lens, dramatic low angle, heavy barrel distortion, high contrast, gritty urban aesthetic, action frozen
```

**关键词:** `fisheye lens`, `8mm fisheye`, `barrel distortion`, `180 degree view`, `extreme wide`, `curved horizon`

---

### 移轴 (Tilt-Shift)

**特性:** 选择性焦平面、微缩/立体模型效果、梦幻虚化
**适用:** 城市航拍微缩、建筑、创意人像

```
aerial view of a European old town, tilt-shift lens, miniature diorama effect, selective focus on cathedral, vivid saturated colors, dreamy bokeh on edges, toy-world aesthetic
```

**关键词:** `tilt-shift lens`, `selective focus`, `miniature effect`, `diorama`, `blurred edges`, `toy-world`

---

### 变形宽银幕 (Anamorphic)

**特性:** 水平拉伸散景 (椭圆光斑)、标志性横向光晕、电影宽银幕比例
**适用:** 电影感人像、夜景、霓虹、叙事场景

```
cinematic portrait in neon-lit alley, anamorphic lens, horizontal oval bokeh, blue and amber lens flares streaking across frame, 2.39:1 widescreen ratio, rain reflections, Blade Runner atmosphere
```

**关键词:** `anamorphic lens`, `oval bokeh`, `horizontal flare`, `widescreen`, `cinematic`, `2.39:1`

---

## 胶片与色彩科学

### 彩色负片 — 暖调人像

#### Kodak Portra 160

**特性:** 极细颗粒、柔和低对比、微暖肤色、自然饱和
**适用:** 婚纱、棚拍人像、柔和室内

```
soft portrait of a bride in natural window light, shot on Kodak Portra 160, fine grain, delicate skin tones, low contrast, dreamy pastel whites, medium format film look
```

**关键词:** `kodak portra 160`, `fine grain`, `soft contrast`, `delicate skin tones`, `pastel warmth`

---

#### Kodak Portra 400

**特性:** 经典暖调肤色、适中颗粒、宽容度极高、百搭
**适用:** 人像、街拍、旅行、日常 — 万能胶片

```
golden hour portrait on a rooftop, shot on Kodak Portra 400, warm analog skin tones, natural film grain, soft highlight roll-off, 85mm f/1.4, documentary feel
```

```
street scene photographed on 35mm film, shot on Leica M6 with Kodak Portra 400, candid moment, warm tones, organic grain, authentic urban vibe
```

**关键词:** `kodak portra 400`, `warm analog`, `natural grain`, `flattering skin tones`, `wide latitude`

---

#### Kodak Portra 800

**特性:** 明显颗粒、可推冲、暗部细节丰富、温暖但稍粗犷
**适用:** 低光人像、室内、派对、黄昏

```
intimate indoor portrait in candlelight, Kodak Portra 800, visible grain, warm shadow detail, pushed film look, nostalgic and raw, 50mm f/1.4
```

**关键词:** `kodak portra 800`, `heavy grain`, `pushed film`, `low light warmth`, `indoor available light`

---

### 彩色负片 — 饱和风景

#### Kodak Ektar 100

**特性:** 极细颗粒、高饱和、鲜艳色彩、强对比
**适用:** 风景、产品、建筑、色彩丰富的场景

```
vivid autumn landscape with red and gold foliage, shot on Kodak Ektar 100, hyper-saturated colors, fine grain, punchy contrast, crystal sharp, 24mm wide angle
```

**关键词:** `kodak ektar 100`, `vivid colors`, `fine grain`, `high saturation`, `punchy contrast`

---

#### Fujifilm Velvia 50

**特性:** 极度饱和正片、强对比、翠绿与深蓝极突出
**适用:** 风景、自然、花卉 — 饱和度之王

```
lush tropical rainforest canopy, shot on Fujifilm Velvia 50, hyper-saturated greens and blues, extreme color vibrancy, fine grain, dramatic contrast, landscape photography
```

**关键词:** `fujifilm velvia 50`, `hyper-saturated`, `vivid greens`, `slide film`, `extreme saturation`, `chrome positive`

---

#### Fujifilm Provia 100F

**特性:** 自然饱和正片、色彩准确、中性偏冷、适中对比
**适用:** 产品、食物、通用 — 比 Velvia 更自然

```
product photography of ceramic teaware on a wooden table, shot on Fujifilm Provia 100F, accurate natural colors, balanced contrast, clean highlights, subtle cool tones
```

**关键词:** `fujifilm provia 100F`, `accurate colors`, `balanced contrast`, `neutral tones`, `slide film`

---

### 彩色负片 — 日常/休闲

#### Fujifilm Superia 400

**特性:** 中性偏冷、日常快照感、适中颗粒、自然不造作
**适用:** 街拍、旅行、日常记录

```
casual street photography of friends at a summer festival, Fujifilm Superia 400, natural neutral tones, everyday snapshot aesthetic, 35mm point-and-shoot feel
```

**关键词:** `fujifilm superia 400`, `neutral tones`, `everyday snapshot`, `casual film`

---

#### Kodak Gold 200

**特性:** 温暖金色调、经典消费级胶片、怀旧感
**适用:** 旅行、家庭、夏天 — 阳光下的黄金色调

```
summer road trip photograph, Kodak Gold 200, warm golden tones, nostalgic vacation feel, bright daylight, relaxed composition, disposable camera vibe
```

**关键词:** `kodak gold 200`, `warm golden`, `nostalgic`, `summer tones`, `consumer film`

---

### 电影胶片 — 夜景/霓虹

#### CineStill 800T

**特性:** 钨丝灯平衡、标志性红色光晕 (halation)、电影感、适合夜景
**适用:** 夜景、霓虹灯、酒吧、城市夜拍 — 最具辨识度的夜景胶片

```
night street photograph of a woman walking past a neon-lit diner, shot on CineStill 800T, characteristic red halation glow around bright light sources, tungsten color balance, cinematic grain, moody atmosphere
```

```
rainy night cityscape with neon signs, CineStill 800T, halation bleeding around streetlights, warm tungsten tones in interiors, cool blue shadows, filmic contrast, wet reflections
```

**关键词:** `cinestill 800t`, `halation glow`, `tungsten balanced`, `neon bleed`, `cinematic night`, `red halation`, `movie film`

---

#### CineStill 50D

**特性:** 日光平衡电影片、极细颗粒、自然色彩、无光晕
**适用:** 日间电影感、自然光人像

```
daylight cinematic portrait in an open field, CineStill 50D, fine grain, natural daylight colors, gentle contrast, subtle film texture, motion picture quality
```

**关键词:** `cinestill 50d`, `daylight cinema`, `fine grain`, `natural film`, `motion picture stock`

---

### 黑白胶片

#### Ilford HP5 Plus 400

**特性:** 经典黑白、用途广泛颗粒、可推冲至 1600/3200、丰富灰度层次
**适用:** 纪实、人像、街拍 — 最经典的黑白胶片

```
street scene photographed on 35mm film, shot on Leica M6, Ilford HP5 pushed one stop, high grain, black and white, raw and atmospheric urban vibe, decisive moment
```

```
black and white portrait of a jazz musician, Ilford HP5 400, rich midtones, classic grain structure, dramatic available light, contrasty shadows
```

**关键词:** `ilford hp5`, `black and white film`, `classic grain`, `pushed film`, `rich tonal range`

---

#### Ilford Delta 3200

**特性:** 极高颗粒、超高感光度、粗犷戏剧感
**适用:** 极暗环境、夜间纪实、高反差戏剧人像

```
grainy black and white night photograph, Ilford Delta 3200, extreme grain, high contrast, dark moody atmosphere, available light only, underground music venue
```

**关键词:** `ilford delta 3200`, `extreme grain`, `high contrast`, `night photography`, `lo-fi black and white`

---

#### Kodak Tri-X 400

**特性:** 经典美式黑白、略粗颗粒、高对比、新闻摄影传奇
**适用:** 新闻、纪实、街拍 — 传奇黑白片

```
photojournalism street scene, Kodak Tri-X 400, gritty black and white, high contrast, visible grain, raw documentary energy, 1960s aesthetic
```

**关键词:** `kodak tri-x 400`, `gritty`, `high contrast`, `photojournalism`, `classic american b&w`

---

### Lomography / 创意胶片

#### Lomography Color Negative 800

**特性:** 高饱和、重颗粒、鲜艳偏暖、lo-fi 个性
**适用:** 创意、派对、时尚 — 独立 / lo-fi 审美

```
high-angle photo of a woman in a white dress and gold necklace, shot on Lomography Color Negative 800, heavy grain, saturated warm colors, lo-fi analog aesthetic, fun and carefree mood
```

**关键词:** `lomography 800`, `heavy grain`, `saturated`, `lo-fi`, `indie film`, `party aesthetic`

---

#### Lomography 交叉冲洗 (Cross-Process)

**特性:** 色彩偏移、不可预测的色调、绿/黄/品红偏色、实验性
**适用:** 时尚、创意实验

```
cross-processed fashion portrait, Lomography cross-process look, unpredictable color shifts, green and magenta cast, high contrast, experimental analog aesthetic
```

**关键词:** `cross-process`, `cross-processed`, `color shift`, `experimental film`, `green cast`, `lomography`

---

### 胶片快速参考表

| 胶片 | 色彩 | 颗粒 | 对比 | 最佳场景 |
|------|------|------|------|---------|
| Portra 160 | 暖/柔和 | 极细 | 低 | 婚纱、棚拍人像 |
| Portra 400 | 暖/自然 | 细 | 中 | 万能人像、街拍 |
| Portra 800 | 暖/粗犷 | 粗 | 中 | 低光、室内 |
| Ektar 100 | 饱和/鲜艳 | 极细 | 高 | 风景、产品 |
| Velvia 50 | 极饱和 | 极细 | 高 | 风景、自然 |
| Provia 100F | 中性/准确 | 极细 | 中 | 产品、通用 |
| Superia 400 | 中性/偏冷 | 中 | 中 | 日常、街拍 |
| Gold 200 | 金色/暖调 | 中 | 中低 | 旅行、夏天 |
| CineStill 800T | 电影/光晕 | 中粗 | 高 | 夜景、霓虹 |
| CineStill 50D | 自然/电影 | 极细 | 中 | 日间电影感 |
| HP5 400 | 黑白 | 中 | 中高 | 纪实、人像 |
| Delta 3200 | 黑白 | 极粗 | 高 | 暗光、戏剧 |
| Tri-X 400 | 黑白 | 中粗 | 高 | 新闻、街拍 |
| Lomo 800 | 高饱和/暖 | 粗 | 中高 | 创意、lo-fi |

---

## 灯光模式

### 经典人像布光

#### 伦勃朗光 (Rembrandt Lighting)

**特性:** 主灯 45° 侧上方、暗面脸颊出现三角形光斑、戏剧性
**适用:** 经典人像、戏剧肖像、艺术摄影

```
dramatic portrait with Rembrandt lighting, 45-degree key light above eye level, small triangle of light on far cheek, deep shadows, low-key studio, charcoal seamless background, 85mm f/1.8, rich contrast
```

**关键词:** `rembrandt lighting`, `triangle of light`, `chiaroscuro`, `45-degree key light`, `dramatic portrait`

---

#### 蝴蝶光 (Butterfly / Paramount Lighting)

**特性:** 正面顶光、鼻下蝴蝶形阴影、显瘦、好莱坞经典
**适用:** 美妆、时尚、好莱坞经典人像

```
glamorous beauty portrait with butterfly lighting, frontal key light positioned above eyes, butterfly-shaped nose shadow, beauty dish modifier, catch lights in eyes, clean white background, editorial quality
```

**关键词:** `butterfly lighting`, `paramount lighting`, `beauty dish`, `frontal key light`, `glamour portrait`, `nose shadow`

---

#### 环形光 (Loop Lighting)

**特性:** 主灯 30–45° 侧方、鼻侧投射小环形影、柔和自然
**适用:** 商业人像、证件照、自然人像

```
natural portrait with loop lighting, key light at 30 degrees creating a soft nose shadow loop, clean and approachable feel, softbox modifier, white fill card, corporate headshot quality
```

**关键词:** `loop lighting`, `soft nose shadow`, `natural portrait`, `30-degree key`, `commercial headshot`

---

#### 分割光 (Split Lighting)

**特性:** 主灯 90° 正侧方、半张脸在明半张在暗、强烈戏剧
**适用:** 戏剧、神秘、艺术人像、黑白

```
moody portrait with split lighting, key light at 90 degrees, half face in deep shadow, dramatic contrast, low-key studio, black background, Ilford HP5 black and white aesthetic
```

**关键词:** `split lighting`, `half face shadow`, `90-degree key`, `dramatic`, `mystery`, `low-key`

---

#### 蛤壳光 (Clamshell Lighting)

**特性:** 上下两灯夹角、消除阴影、均匀柔和、美妆标配
**适用:** 美妆广告、时尚大片、商业人像

```
beauty editorial portrait with clamshell lighting, upper key light and lower fill light creating even illumination, soft shadows under chin, beauty dish above with silver reflector below, flawless skin detail
```

**关键词:** `clamshell lighting`, `even illumination`, `beauty lighting`, `upper key lower fill`, `shadow-free`, `editorial beauty`

---

### 氛围灯光

#### 黄金时刻 (Golden Hour)

```
golden hour portrait outdoors, warm rim backlight from setting sun, lens flare, 85mm f/1.4, Kodak Portra 400, glowing skin tones, dreamy bokeh, soft long shadows
```

**关键词:** `golden hour`, `warm backlight`, `setting sun`, `golden glow`, `rim light`, `lens flare`

---

#### 蓝色时刻 (Blue Hour)

```
portrait during blue hour twilight, cool ambient blue tones, city lights beginning to glow, soft even lighting, melancholic mood, 50mm f/1.8, CineStill 800T
```

**关键词:** `blue hour`, `twilight`, `cool blue tones`, `ambient`, `melancholic`

---

#### 窗光 (Window Light)

```
intimate portrait lit by single large window, soft diffused natural light, gentle shadow gradient across face, Vermeer-like quality, warm interior, 85mm, shallow depth of field
```

**关键词:** `window light`, `natural diffused`, `soft gradient`, `vermeer-like`, `indoor portrait`

---

#### 霓虹灯光 (Neon Lighting)

```
portrait in neon-lit urban alley, pink and cyan neon reflections on face, wet ground reflections, nighttime, CineStill 800T halation, moody cyberpunk atmosphere
```

**关键词:** `neon lighting`, `neon glow`, `colored light`, `urban night`, `cyberpunk`, `halation`

---

#### 烛光 (Candlelight)

```
intimate candlelight portrait, warm orange point-source light, deep shadows, Renaissance painting mood, low-key, Kodak Portra 800, 50mm f/1.4, quiet atmosphere
```

**关键词:** `candlelight`, `warm point source`, `intimate`, `low-key`, `Renaissance mood`

---

#### 上帝光 (God Rays)

```
portrait in misty forest with god rays streaming through canopy, volumetric light beams, atmospheric haze, ethereal spiritual mood, 35mm lens, golden morning light
```

**关键词:** `god rays`, `volumetric light`, `light beams`, `haze`, `ethereal`, `atmospheric`

---

#### 轮廓光 / 背光 (Rim Light / Backlight)

```
dramatic portrait with strong rim lighting, subject outlined by bright edge light, dark background, hair light creating halo effect, cinematic, 85mm f/2
```

**关键词:** `rim lighting`, `edge light`, `backlight`, `hair light`, `halo effect`, `silhouette separation`

---

### 影调控制

#### 高调 (High-Key)

```
high-key beauty portrait, bright even lighting, white background, minimal shadows, clean and airy aesthetic, overexposed highlights, fashion editorial
```

**关键词:** `high-key`, `bright`, `low contrast`, `white background`, `airy`, `minimal shadows`

---

#### 低调 (Low-Key)

```
low-key dramatic portrait, dark background, single focused light source, deep shadows, high contrast, moody and mysterious, fine art quality
```

**关键词:** `low-key`, `dark`, `high contrast`, `deep shadows`, `moody`, `dramatic`

---

## 摄影风格

### 电影剧照 (Cinematic Still)

```
cinematic still frame of a woman standing at a rain-streaked window, shallow depth of field, anamorphic bokeh, warm interior light vs cool exterior, 35mm motion picture film look, color graded teal and orange, 2.39:1 widescreen
```

**关键词:** `cinematic`, `film still`, `anamorphic`, `color graded`, `widescreen`, `motion picture`

---

### 黑色电影 (Film Noir)

```
film noir detective portrait, sharp shadows from venetian blinds, 1940s aesthetic, high-contrast black and white, cigarette smoke, fedora hat, 50mm lens, heavy grain, Kodak Tri-X, dramatic chiaroscuro
```

**关键词:** `film noir`, `1940s`, `venetian blind shadows`, `chiaroscuro`, `high contrast b&w`, `detective`, `hard-boiled`

---

### 街头纪实 (Street / Documentary)

```
decisive moment street photography, candid expression of a market vendor, 35mm lens, Ilford HP5 pushed to 1600, black and white, available light, slight motion blur, raw authenticity, Henri Cartier-Bresson inspired
```

**关键词:** `street photography`, `candid`, `decisive moment`, `documentary`, `available light`, `raw`, `unposed`

---

### 时尚大片 (Fashion Editorial)

```
high-fashion editorial photograph, model in avant-garde geometric dress, dramatic studio strobe lighting with hard shadows, 85mm lens, clean seamless background, bold composition, Vogue magazine aesthetic, sharp focus, commercial quality
```

**关键词:** `fashion editorial`, `high fashion`, `magazine`, `strobe lighting`, `avant-garde`, `bold composition`, `Vogue`

---

### 新闻摄影 (Photojournalism)

```
photojournalism image of a protest march, 35mm lens, available light, Kodak Tri-X, gritty black and white, raw emotion, dynamic composition, decisive moment, press photography
```

**关键词:** `photojournalism`, `press photography`, `raw`, `gritty`, `available light`, `decisive moment`

---

### 红外摄影 (Infrared)

```
infrared photography of a forest path, foliage glowing bright white (Wood Effect), deep black sky, surreal dreamlike atmosphere, 35mm infrared film, high contrast, ethereal otherworldly mood
```

**关键词:** `infrared photography`, `wood effect`, `white foliage`, `black sky`, `surreal`, `ethereal`, `IR film`

---

### 长曝光 (Long Exposure)

```
long exposure city street at night, car light trails forming red and white streaks, 24mm wide angle, 30-second exposure, sharp architecture, silky smooth motion, tripod-stable, CineStill 800T
```

```
long exposure seascape, silky smooth ocean water, 10-stop ND filter effect, misty horizon, minimalist composition, 24mm, golden hour, fine art landscape
```

**关键词:** `long exposure`, `light trails`, `silky smooth`, `ND filter`, `motion blur`, `tripod`, `slow shutter`

---

### 天文摄影 (Astrophotography)

```
astrophotography of the Milky Way arching over a desert landscape, 14mm ultra-wide lens, f/2.8, ISO 3200, 20-second exposure, star points, silhouetted cactus foreground, deep blue night sky, cold tones
```

**关键词:** `astrophotography`, `milky way`, `star trails`, `night sky`, `ultra-wide`, `high ISO`, `long exposure`

---

### 水下摄影 (Underwater)

```
underwater portrait photography in clear tropical water, diver silhouetted against sunlight beams filtering from surface, 16mm wide angle, blue-green caustic light patterns, bubbles rising, National Geographic quality
```

**关键词:** `underwater photography`, `caustic light`, `sunbeams`, `blue-green`, `bubbles`, `wide angle underwater`

---

### Lomography / Lo-Fi

```
lomography portrait, Lomography Color Negative 800, light leaks, vignetting, heavy grain, saturated colors, disposable camera feel, carefree summer aesthetic, slight overexposure
```

**关键词:** `lomography`, `light leaks`, `vignetting`, `lo-fi`, `disposable camera`, `indie`, `analog imperfections`

---

### 宝丽来 / 即时显影 (Polaroid / Instant)

```
polaroid instant photograph of friends at a picnic, white border frame, slightly faded colors, soft focus, warm nostalgic tones, vintage 1970s feel, candid snapshot
```

**关键词:** `polaroid`, `instant film`, `white border`, `faded colors`, `nostalgic`, `snapshot`, `retro`

---

### 双重曝光 (Double Exposure)

```
double exposure portrait, woman's face merged with forest canopy, overlapping silhouettes, ethereal blend, fine art photography, soft diffused light, dreamlike surreal composition
```

**关键词:** `double exposure`, `merged silhouettes`, `overlapping`, `surreal`, `fine art`, `ethereal blend`

---

### 产品商业摄影 (Commercial Product)

```
premium product photography of a luxury watch, brushed titanium case, sapphire crystal reflections, controlled three-point studio lighting, soft gradient background, razor-sharp focus, commercial advertising quality, 100mm macro
```

**关键词:** `product photography`, `studio lighting`, `commercial`, `sharp focus`, `gradient background`, `advertising`

---

### 建筑摄影 (Architectural)

```
architectural photography of a modern concrete museum, dramatic converging lines, 24mm tilt-shift lens, balanced daylight exposure, clean geometry, minimalist composition, editorial quality
```

**关键词:** `architectural photography`, `converging lines`, `geometry`, `minimalist`, `editorial`, `tilt-shift`

---

### 食物摄影 (Food Photography)

```
food photography of a rustic pasta dish, warm side lighting from left, shallow depth of field, steam rising, wooden table props, linen napkin, appetizing textures, overhead 45-degree angle, editorial quality
```

**关键词:** `food photography`, `side lighting`, `appetizing`, `steam`, `styling`, `editorial food`

---

### 微缩景观 (Tilt-Shift Miniature)

```
tilt-shift miniature photograph of a harbor with boats, selective focus band across center, extreme bokeh top and bottom, vivid boosted saturation, toy-world scale, aerial perspective
```

**关键词:** `tilt-shift`, `miniature`, `diorama`, `toy-world`, `selective focus`, `boosted saturation`

---

## 相机机身

不同机身在 prompt 中传递不同的视觉暗示:

| 机身 | 暗示的画面风格 | 示例关键词 |
|------|--------------|-----------|
| Leica M6 | 经典街拍、手动对焦、旁轴 | `shot on Leica M6`, 纪实/街拍 |
| Hasselblad 500C | 中画幅、方画幅、极致细节 | `shot on Hasselblad`, 人像/艺术 |
| Nikon D850 | 高像素全画幅、锐利详细 | `Nikon D850`, 风景/商业 |
| Canon EOS R5 | 现代无反、色彩准确 | `Canon EOS R5`, 万能 |
| Sony A7R IV | 高像素、科技感 | `Sony A7R IV`, 人像/产品 |
| Fujifilm X-T4 | 胶片模拟、复古外观 | `Fujifilm X-T4`, 街拍/旅行 |
| Mamiya RZ67 | 中画幅、时尚传奇 | `Mamiya RZ67`, 时尚大片 |
| Pentax 67 | 中画幅、温暖人像 | `Pentax 67`, 人像/风景 |
| Polaroid SX-70 | 即拍即得、白边 | `Polaroid`, 怀旧/创意 |
| 一次性相机 | 快照感、不完美、真实 | `disposable camera`, lo-fi |

---

## 真实感增强技巧

2026 年社区共识: 现代模型默认过于"干净完美"，需要主动添加瑕疵才能真实。

### 必加瑕疵关键词

```
subtle film grain, natural skin texture with pores, slight chromatic aberration, micro lens dust, ISO noise, imperfect composition, authentic candid moment, natural motion blur on extremities
```

### 反塑料感后缀

```
not overly smooth, not AI-generated looking, realistic imperfections, natural asymmetry, organic feel, unretouched skin detail
```

### 完整真实感 prompt 示例

```
candid portrait of an elderly man with deep wrinkles and kind eyes, wearing a weathered wool sweater, sitting in a dimly lit library. Soft ambient window light from left. Shot on Sony A7R IV, 85mm f/1.8, Kodak Portra 400 tones. Shallow depth of field, sharp focus on eyes. Subtle film grain, natural skin texture, slight chromatic aberration on edges. 8K, photorealistic.
```

---

## 快速参考表

### 场景 → 推荐镜头

| 场景类型 | 推荐焦距 | 推荐光圈 |
|---------|---------|---------|
| 室内建筑/全景 | 14-24mm | f/8-f/11 |
| 环境人像/街拍 | 28-35mm | f/2-f/4 |
| 通用人像 | 50mm | f/1.8-f/2.8 |
| 头肩像/美妆 | 85-135mm | f/1.4-f/2 |
| 野生动物/体育 | 200-400mm | f/2.8-f/5.6 |
| 产品/细节 | 100mm macro | f/2.8-f/8 |
| 创意/极限运动 | 8mm fisheye | f/3.5 |

### 场景 → 推荐胶片

| 场景类型 | 推荐胶片 |
|---------|---------|
| 人像 (日间) | Portra 400 / Portra 160 |
| 人像 (低光) | Portra 800 |
| 风景 / 自然 | Velvia 50 / Ektar 100 |
| 夜景 / 霓虹 | CineStill 800T |
| 街拍 (彩色) | Superia 400 / Gold 200 |
| 纪实 (黑白) | HP5 / Tri-X 400 |
| 暗光 (黑白) | Delta 3200 |
| 创意 / Lo-Fi | Lomography 800 |
| 电影感 (日间) | CineStill 50D |

### 场景 → 推荐灯光

| 场景类型 | 推荐灯光 |
|---------|---------|
| 经典人像 | Rembrandt / Loop |
| 美妆/时尚 | Butterfly / Clamshell |
| 戏剧/艺术 | Split / 低调 |
| 商业/证件 | Loop / 高调 |
| 户外人像 | Golden Hour / 背光 |
| 夜景/氛围 | 霓虹 / 烛光 |
| 神秘/叙事 | 窗光 / God Rays |

---

## 网红 & 病毒式自拍风格 (Influencer & Viral Selfie Styles — 2026)

> 以下为 2026 年 Instagram / TikTok / X 上最流行的 AI 自拍/人像编辑风格。
> 适用于 ChatGPT (GPT-4o)、Google Gemini、Midjourney、Nano Banana 等。

### 吉卜力风格自拍 (Studio Ghibli Selfie)

**热度:** 极高 — 2025–2026 持续霸榜，高收藏率

```
Transform this photo into a Studio Ghibli-inspired illustration. Use soft pastel colors, hand-painted textures, and gentle lighting reminiscent of classic Ghibli films. Keep the subject's face recognizable. Whimsical atmosphere, warm tones, dreamy background, Miyazaki aesthetic.
```

**关键词:** `ghibli`, `hand-painted`, `pastel`, `anime`, `miyazaki`, `watercolor textures`

---

### AI 漫画讽刺画 (ChatGPT Caricature)

**热度:** 2026 年初第一大病毒趋势 — 横扫 Instagram / TikTok / Facebook

```
Create a fun, exaggerated caricature of me based on this photo. Surround me with objects and details that represent my daily life and profession. Cartoon style with bold outlines, vibrant colors, humorous and personalized details. Keep my face recognizable but stylized.
```

**关键词:** `caricature`, `cartoon`, `exaggerated`, `personalized`, `profession`, `humorous`

---

### 电影感黄金时刻人像 (Cinematic Golden Hour Portrait)

**热度:** 2026 年 Instagram 持续病毒传播

```
Transform this selfie into a cinematic golden hour portrait. Low-angle warm sunlight with harsh side-lighting creating dramatic shadows. Natural subsurface scattering on skin. Kodak Portra 400 film emulation, soft lens flare, shallow depth of field, 85mm f/1.4 look. Warm amber and honey tones. Keep face exactly as is, do NOT alter facial features.
```

**关键词:** `golden hour`, `cinematic`, `portra 400`, `warm tones`, `lens flare`, `dramatic shadows`

---

### Y2K 千禧美学 (Y2K Aesthetic)

**热度:** TikTok 怀旧潮流持续走高

```
Turn this photo into a Y2K aesthetic style image. Use glossy metallic textures, holographic gradients, neon pinks and blues, butterfly motifs, low-rise fashion vibes, early 2000s digital camera quality. Slight overexposure, sparkle overlays, retro-futuristic feel. Keep my face exactly the same.
```

**关键词:** `y2k`, `holographic`, `metallic`, `glossy`, `neon pink`, `early 2000s`, `butterfly`, `retro-futuristic`

---

### 复古宝丽来自拍 (Retro Polaroid Selfie)

**热度:** 怀旧风持续

```
Create a Polaroid-style photo with soft film grain, muted vintage colors, light vignetting, and a nostalgic instant-camera feel. White Polaroid border frame. Slightly faded and warm tones, casual candid energy. Keep face realistic and unchanged.
```

**关键词:** `polaroid`, `instant film`, `white border`, `vintage`, `muted colors`, `nostalgic`, `film grain`

---

### 柔光韩系美学 (Soft Korean Aesthetic)

**热度:** 女性向高人气

```
Edit this portrait in soft Korean aesthetic style. Gentle diffused lighting, milky smooth skin texture (but keep it natural, not plastic), pale pink and cream color palette, minimal background, clean and airy composition. Subtle cherry blossom or petal overlay optional. Keep face features exactly the same.
```

**关键词:** `korean aesthetic`, `soft light`, `milky skin`, `pale pink`, `clean`, `airy`, `minimal`

---

### 赛博朋克霓虹自拍 (Cyberpunk Neon Portrait)

**热度:** 2025–2026 男性向持续热门

```
Transform this into a cyberpunk scene. Add vibrant neon lights (magenta, cyan, electric blue) reflecting off wet surfaces and metal. Futuristic urban background with holographic signs. Dramatic rim lighting on face. Rain effects, moody atmosphere, Blade Runner vibes. Keep my face realistic and unchanged.
```

**关键词:** `cyberpunk`, `neon`, `magenta`, `cyan`, `wet reflections`, `futuristic`, `blade runner`, `rain`

---

### 一次性相机快照 (Disposable Camera Look)

**热度:** "不完美即真实" 趋势核心

```
Make this look like it was taken on a 1990s disposable camera. Low resolution, heavy flash with red-eye effect, washed out colors, date stamp in corner, slight motion blur, light leaks, cheap lens softness. Authentic point-and-shoot snapshot energy. Do not change my face.
```

**关键词:** `disposable camera`, `flash`, `red-eye`, `date stamp`, `light leaks`, `90s`, `snapshot`, `lo-fi`

---

### Chibi Q 版表情包 (Chibi Emoji Stickers)

**热度:** 社交媒体个性化贴纸

```
Transform this photo into a 2×2 grid of Chibi-style emoji stickers. Each square should feature a simplified, cute Chibi version of me with big expressive eyes and a different emotion: happy, surprised, sad, and cool/sunglasses. Bold outlines, vibrant colors, transparent-background-ready.
```

**关键词:** `chibi`, `emoji`, `sticker`, `cute`, `big eyes`, `2x2 grid`, `expressive`

---

### 3D 手办/公仔风格 (3D Figurine / Funko Pop)

**热度:** 个性化周边热潮

**手办版:**
```
Change this photo to a 3D collectible figurine style. Recreate the subject as a small, detailed figurine with smooth textures and vibrant colors, displayed on a round base with a subtle shadow. Keep face recognizable. Studio product lighting.
```

**Funko Pop 版:**
```
Convert the person in the photo into a Funko Pop-style figure inside a branded box, shown in isometric view displaying the packaging and figure. Keep outfit and hairstyle recognizable. Bright clean background.
```

**关键词:** `3d figurine`, `collectible`, `funko pop`, `toy`, `product display`, `isometric`

---

### 皮克斯 3D 角色 (Pixar Character Style)

**热度:** 家庭/趣味向

```
Convert this image into a 3D Pixar-style character. Smooth, polished rendering with soft lighting typical of Pixar films. Exaggerated but endearing facial proportions, expressive eyes, vibrant saturated colors. Keep personality and key features recognizable.
```

**关键词:** `pixar`, `3d character`, `smooth rendering`, `expressive`, `animated`, `vibrant`

---

### 时尚大片发光人像 (Fashion Editorial Glow)

**热度:** 女性向 influencer 标配

```
Ultra-realistic fashion portrait with gentle glow lighting, smooth but real skin texture, premium magazine aesthetic. Clean background, editorial composition, subtle rim light halo. Professional studio quality. Do not change my face — keep facial features exactly as they are.
```

**关键词:** `fashion editorial`, `glow`, `magazine`, `studio`, `rim light`, `clean background`, `influencer`

---

### 柔光粉彩 Instagram 风 (Soft Pastel Instagram)

**热度:** 清新/甜美向

```
Transform this into a soft pastel Instagram aesthetic portrait. Soft diffused lighting, elegant mood, and natural beauty. Pale lavender, mint, and blush pink color palette. Dreamy bokeh background. Keep my face exactly as is, high resolution.
```

**关键词:** `soft pastel`, `instagram`, `lavender`, `mint`, `blush pink`, `dreamy`, `elegant`

---

### 戏剧电影感男像 (Dramatic Cinematic Male Portrait)

**热度:** 男性向 — "老钱风" / "黑帮大佬风"

```
Cinematic male portrait with dramatic lighting and sharp focus. Deep shadows, strong jawline emphasis, rich warm color grading. Leather or wool texture visible on clothing. Shot on 85mm f/1.8, shallow depth of field. Keep facial features exactly the same. Moody, confident, powerful energy.
```

**关键词:** `cinematic male`, `dramatic lighting`, `sharp focus`, `old money`, `mafia boss`, `moody`, `powerful`

---

### 霓虹夜景动态模糊 (Neon Motion Blur Portrait)

**热度:** TikTok 创意人像

```
Create a portrait with dramatic motion blur effects. The subject stands still wearing a white shirt while everything around them has swirling motion trails of neon pink and blue light. Long exposure feel, nighttime urban environment, sharp face amid blurred chaos. Do not change my face.
```

**关键词:** `motion blur`, `neon`, `long exposure`, `swirling light`, `still subject`, `urban night`

---

### 复古 2016 怀旧风 (2016 Nostalgia Revival)

**热度:** TikTok "2026 is the new 2016" 潮流

```
Edit this selfie to look like a 2016 Instagram photo. Heavy VSCO filter, slightly desaturated warm tones, subtle grain, natural makeup look, oversized sweater vibes, fairy lights or succulents in background. Authentic 2016 social media energy. Keep face as is.
```

**关键词:** `2016 nostalgia`, `vsco`, `desaturated warm`, `fairy lights`, `instagram vintage`, `millennial pink`

---

### 拥抱小时候的自己 (Hug My Younger Self)

**热度:** 情感向高互动

```
Create a realistic photo of my current self hugging a younger version of me (around age 8-10). Show both figures in a warm, emotional embrace with soft golden lighting. Same identity at two different ages. Nostalgic atmosphere, slightly dreamy, heartwarming. Keep my adult face exactly as in the photo.
```

**关键词:** `younger self`, `time travel`, `emotional`, `nostalgic`, `warm`, `heartwarming`, `two ages`

---

### 专业 LinkedIn 头像 (Professional Headshot)

**热度:** 职场实用向

```
Transform this casual portrait into a professional headshot suitable for LinkedIn. Adjust lighting to be soft and flattering, clean neutral background, slight color grading for warmth. Sharp focus on face, professional attire appearance, confident approachable expression. High resolution. Keep face exactly as is.
```

**关键词:** `professional headshot`, `linkedin`, `clean background`, `soft lighting`, `corporate`, `approachable`

---

### 节日主题人像 (Festival-Themed Portrait)

**热度:** 季节性病毒传播 — Holi / 新年 / 圣诞等

**Holi 节色彩人像:**
```
Transform this portrait into a vibrant Holi festival celebration scene. Colorful powder clouds (pink, yellow, blue, green) exploding around the subject. Bright vivid colors on face and clothes. Joyful expression, outdoor setting, golden hour light filtering through color powder haze. Keep face features exactly as in photo.
```

**新年主题:**
```
Create a festive New Year 2026 celebration portrait. Confetti, champagne sparkles, bokeh lights, midnight atmosphere. Elegant outfit, warm festive lighting. Party energy but keep face photorealistic and unchanged.
```

**关键词:** `festival`, `holi`, `new year`, `confetti`, `colorful powder`, `celebration`, `seasonal`

---

### 动漫鱼眼合拍 (Anime Fisheye Selfie)

**热度:** TikTok 5000万+ 总观看

```
Create a 9:16 vertical fisheye selfie of me with [CHARACTER NAME, e.g. Goku / Naruto / Gojo]. We're both making exaggerated silly faces and peace signs. Set in a bright, modern living room. Fisheye lens distortion, fun casual energy, anime character rendered in their original art style, I remain photorealistic.
```

**关键词:** `fisheye selfie`, `anime character`, `vertical`, `peace sign`, `crossover`, `fun`

---

### 名人合拍自拍 (Celebrity Backstage Selfie)

**热度:** "和明星合照" 趋势

```
Create a hyper-realistic backstage selfie of me with [CELEBRITY NAME]. Both of us smiling casually, selfie angle from slightly above, warm backstage lighting, slightly out-of-focus background with mirrors and lights. My face from the uploaded photo, celebrity rendered photorealistically. Natural authentic energy.
```

**关键词:** `celebrity selfie`, `backstage`, `selfie angle`, `casual`, `photorealistic`, `fan moment`

---

### 2026 趋势总结

| 趋势类型 | 代表风格 | 热度平台 |
|---------|---------|---------|
| 怀旧/复古 | Polaroid, 2016 Revival, Y2K, Disposable Camera | TikTok, Instagram |
| 电影感 | Golden Hour Cinematic, Film Noir, Dramatic Male | Instagram, X |
| 动漫/卡通 | Ghibli, Chibi, Pixar, Anime Fisheye, Caricature | TikTok, Instagram |
| 手办/玩具 | 3D Figurine, Funko Pop | Instagram, TikTok |
| 清新/柔光 | Korean Aesthetic, Soft Pastel, Fashion Glow | Instagram, 小红书 |
| 科幻/霓虹 | Cyberpunk Neon, Motion Blur Neon | TikTok, Instagram |
| 情感/互动 | Hug Younger Self, Celebrity Selfie, Festival | Facebook, Instagram |
| 实用 | LinkedIn Headshot, Professional Portrait | LinkedIn |

### 2026 核心趋势关键词

- **真实感 > 完美感:** Gen Z 偏好真实瑕疵 (grain, blur, imperfections)，过度修图反而掉粉
- **Mobile-First 竖屏:** 9:16 竖版格式主导一切
- **AI 辅助 ≠ AI 替代:** 最佳实践是保留真实面部 + AI 增强氛围/风格
- **个性化 > 模板化:** 职业元素、兴趣标签、个人故事融入画面
- **胶片复兴:** Portra 400, Disposable Camera, Film Grain 持续高热

---

*Sources: community research from Midjourney, FLUX, Stable Diffusion, Civitai, Reddit, Lomography, TikTok, Instagram, and photography reference guides*
