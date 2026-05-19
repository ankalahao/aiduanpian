# 05 · Prompt 总表

> 18 个镜头 × 2 套 Prompt（Midjourney 关键帧 + Veo 3 / Kling 视频生成）= 36 段可复制 Prompt。
> 复制到对应工具，配合 cref 角色锚定图，即可开始抽卡。

---

## 工具与版本说明

| 用途 | 工具 | 版本 | 关键参数 |
|------|------|------|---------|
| 关键帧出图 | **Midjourney v7** | 2025.05+ | `--ar 21:9 --style raw --v 7` |
| 角色一致性 | **MJ Character Reference** | `--cref [url] --cw 100` | 需先出 cref 锚定图 |
| 视频生成（首选） | **Veo 3** | 2025 当前版 | 大场面、复杂运动 |
| 视频生成（备选） | **Kling 2.5 Master** | 2025 当前版 | 中文场景、人物特写 |
| 视频生成（备选） | **Runway Gen-4 Turbo** | 2025 当前版 | 复杂运镜 |

---

## 通用风格尾缀（每个 Prompt 都加）

### Midjourney 通用尾缀

```
Warcraft 2016 movie cinematic style, painterly oil painting texture,
hyperdetailed skin pores and individual hair strands,
volumetric lighting with god rays and dust particles,
8K, octane render, Greg Rutkowski concept art influence,
shallow depth of field
--ar 21:9 --style raw --v 7
```

### Veo 3 / Kling 通用尾缀

```
Cinematic Warcraft movie style, 24fps film look,
realistic physics, hyperdetailed textures,
volumetric atmospheric lighting, no logos, no text overlay
```

---

## 镜头 #1 · 黎明全景

### Midjourney
```
Extreme wide aerial shot of Durotar dawn warcamp outside Orgrimmar,
red-orange dusty plains stretching to horizon,
massive Horde wolf-head black-red banner flapping in foreground (6 meters tall),
black tribal yurts, bone totems, wooden palisades with watch horn-tower,
silhouette of Orgrimmar massive walls and spires in distant haze,
blood-red rising sun on horizon at low angle,
volumetric morning mist clinging to ground,
warm 3800K dawn color temperature, low-angle dramatic backlight,
+ [通用尾缀]
```

### Veo 3
```
Extreme wide aerial shot of Durotar dawn warcamp,
camera slowly pushes forward 10% over 3 seconds,
massive Horde banner flapping in wind in foreground,
sun rising on horizon, mist drifting across red plains,
zero camera shake, locked tripod feel,
+ [通用尾缀]
```

---

## 镜头 #2 · 号角手

### Midjourney
```
Medium shot, low angle 15 degrees up,
female orc horn-blower standing on watchtower top at dawn,
deep green skin, wolf-tooth necklace, leather armor,
cheeks puffed blowing massive bronze ornate war horn,
white breath visible in cold dawn air,
backlit by rising sun creating rim light on her silhouette,
sky behind painted gold and pink,
+ [通用尾缀]
```

### Veo 3
```
Medium low-angle shot of female orc horn-blower on watchtower,
she takes a deep breath then blows the war horn for 2 seconds,
white breath cloud expands in dawn air,
camera completely static,
+ [通用尾缀]
```

---

## 镜头 #3 · A 线 · 苦工领斧（跟拍）

### Midjourney
```
Steadicam tracking medium shot from rear-side,
line of orc peons receiving lumber axes from camp armory at dawn,
main character Grosh (cref) in middle of line,
he extends scarred hand to take worn lumber axe with rag-wrapped handle,
weighs it, hoists onto left shoulder,
red dust kicked up by bare feet, dim torch light from armory,
queue of similar-looking peons stretching back,
+ [通用尾缀]
--cref [格罗什锚定图URL] --cw 100
```

### Veo 3
```
Steadicam tracking shot following orc peon Grosh from rear-side at 2 meter distance,
he walks forward in queue, receives an axe, hoists it onto left shoulder,
camera follows smoothly without shake for 3 seconds,
red dust particles in the air, dawn warm light,
+ [通用尾缀]
```

---

## 镜头 #4 · B 线 · 战士佩刀（跟拍）

### Midjourney
```
Steadicam tracking medium shot from front-side (mirror of #3),
line of orc warriors receiving two-handed war axes from same camp armory at dawn,
main character Lok'ra (cref) at front of line,
he takes battle-worn war axe with 4 chipped notches on blade,
swings it once, hoists onto right shoulder,
small leather pouch at his belt visible,
iron boots stomping in rhythm, dim torch light,
queue of similar warriors stretching back,
+ [通用尾缀]
--cref [洛卡锚定图URL] --cw 100
```

### Veo 3
```
Steadicam tracking shot following orc warrior Lok'ra from front-side at 2 meter distance,
he walks forward, receives a war axe, swings it once, hoists onto right shoulder,
iron boots stomping in unified rhythm,
camera follows smoothly without shake for 3 seconds,
+ [通用尾缀]
```

---

## 镜头 #5 · 镜像特写 · 双手握紧

### Midjourney 5A
```
Extreme close-up macro shot of orc peon's calloused weathered hand
gripping rag-wrapped wooden axe handle,
knuckles whitening from grip pressure,
rag fibers and wood grain visible in detail,
warm 3800K backlight from rising sun,
shallow depth of field with axe handle in razor focus,
+ [通用尾缀]
```

### Midjourney 5B（与 5A 完全相同的构图）
```
Extreme close-up macro shot of orc warrior's scarred battle-worn hand
gripping leather-wrapped war axe shaft,
knuckles whitening from grip pressure,
leather wear marks and metal rivets visible in detail,
warm 3800K backlight from rising sun,
shallow depth of field with axe shaft in razor focus,
+ [通用尾缀]
```

### Veo 3（两镜分别抽卡）
```
Extreme macro close-up of [orc peon's hand on axe handle / orc warrior's hand on war axe shaft],
fingers slowly tighten over 1 second,
camera completely static, very shallow depth of field,
+ [通用尾缀]
```

---

## 镜头 #6 · 部落出征大场面 ★ CG 高潮 1

### Midjourney
```
Massive epic wide shot of Horde army marching out of Orgrimmar gates at dawn,
camera angle starts at ground level then cranes upward to bird's eye,
thousands of orc warriors, wolf riders, raptors, wyvern flyers in sky,
red banners with black wolf head sigil flapping in wind,
red dusty plains of Durotar, blood-red rising sun on horizon,
dust trails behind cavalry charging forward,
Lord of the Rings Rohan charge composition,
Blizzard cinematic style scale,
+ [通用尾缀]
```

### Veo 3 ★ 这一镜需要砸 30+ 次抽卡
```
Epic Horde army marching out of Orgrimmar at dawn,
camera starts at ground level tracking a charging wolf rider,
then dramatically cranes upward over 4 seconds revealing
thousands of warriors stretching to horizon,
banners snapping in wind, dust trail behind cavalry,
wyvern flyers visible in upper sky,
slow motion at peak of camera ascent (60fps look),
warm orange dawn lighting, epic scale,
inspired by Lord of the Rings Rohan charge,
+ [通用尾缀]
```

---

## 镜头 #7 · 林场大场面 ★ CG 高潮 2

### Midjourney
```
High-angle bird's eye view of massive Horde lumber camp and open-pit gold mine,
hundreds of orc peons chopping giant red-bark trees in unified rhythm,
wood chips flying everywhere, sweat glistening,
stepped open-pit gold mine with wooden scaffolding,
miners hauling buckets, piles of fresh-cut logs,
gold crates with Horde sigil stacked,
god rays piercing through tree canopy creating golden dust shafts,
composition inspired by LOTR Isengard pit scene,
warm 5500K golden hour lighting,
+ [通用尾缀]
```

### Veo 3 ★ 必须与 #6 等量级，否则立意垮
```
High-angle aerial shot of massive Horde lumber camp,
camera holds static for 2 seconds then slowly pushes down toward one work zone,
hundreds of orc peons chopping trees in unified rhythm,
wood chips flying in slow motion peak,
golden god rays through tree canopy,
warm afternoon lighting,
visual rhythm matching military marching tempo,
+ [通用尾缀]
```

---

## 镜头 #8 · 镜像砍击 ★★★ 全片核心镜

### Midjourney 8A
```
Extreme close-up macro shot at the exact moment
a worn lumber axe blade bites into ancient red-bark tree trunk,
massive wood chip explosion frozen mid-flight,
golden hour backlight illuminating dust and chips,
sweat droplet flying off Grosh's face into camera,
85mm macro lens look, warm 5500K golden lighting,
motion blur on axe head only,
hyperdetailed bark texture and wood fibers,
+ [通用尾缀]
```

### Midjourney 8B（与 8A 同构图，换环境）
```
Extreme close-up macro shot at the exact moment
a battle-worn war axe blade cleaves through human soldier's plate armor,
massive blood mist explosion frozen mid-flight,
cold twilight backlight illuminating mist and dust,
sweat droplet flying off Lok'ra's face into camera,
85mm macro lens look, cold 6500K teal-rust lighting,
motion blur on axe head only,
hyperdetailed armor scratches and chainmail,
+ [通用尾缀]
```

### Veo 3 8A
```
Extreme macro close-up, 120fps slow motion,
worn lumber axe biting into red-bark tree trunk,
wood chips exploding outward in slow motion,
sweat droplet flying off face,
1.5 seconds, golden hour backlight,
+ [通用尾缀]
```

### Veo 3 8B
```
Extreme macro close-up, 120fps slow motion,
battle-worn war axe cleaving through plate armor,
blood mist exploding outward in slow motion,
sweat droplet flying off face,
1.5 seconds, cold twilight backlight,
+ [通用尾缀]
```

> 抽卡要点：8A 和 8B 必须**机位完全相同 + 慢动作速率完全相同**。
> 出来的两段视频先在剪辑软件里叠化对比，构图重合度 ≥ 90% 才合格。

---

## 镜头 #9 · 战士受伤

### Midjourney
```
Medium shot, subtle handheld feel, 50mm,
orc warrior Lok'ra on battlefield mid-battle,
horizontal sword cut bleeding through gap in dented chest plate,
he kneels on one knee, war axe shaft planted on ground for support,
face mixed with sweat, blood, and dust,
teeth clenched, eyes still sharp and defiant,
he begins to slowly rise back up,
cold 6500K twilight battlefield lighting, distant chaos blurred in background,
+ [通用尾缀]
--cref [洛卡锚定图URL] --cw 100
```

### Veo 3
```
Medium shot of orc warrior wounded on battlefield,
he kneels on one knee from injury, then slowly rises back to standing,
subtle handheld camera shake,
3 seconds total, cold blue battlefield lighting,
+ [通用尾缀]
```

---

## 镜头 #10 · 苦工受伤（镜像）

### Midjourney
```
Medium shot, subtle handheld feel, 50mm (mirror of #9),
orc peon Grosh in lumber camp,
fallen log struck his right shoulder, blood seeping through linen tunic,
he kneels on one knee, lumber axe planted on ground for support,
face mixed with sweat, dirt, and blood,
teeth clenched, eyes weary but determined,
he begins to slowly rise back up,
warm 5500K golden lumber camp lighting, blurred peons working in background,
+ [通用尾缀]
--cref [格罗什锚定图URL] --cw 100
```

### Veo 3
```
Medium shot of orc peon injured in lumber camp,
he kneels on one knee from injury, then slowly rises back to standing,
subtle handheld camera shake (matching #9 exactly),
3 seconds total, warm golden lighting,
+ [通用尾缀]
```

---

## 镜头 #11 · 雷霆萨尔（彩蛋）

### Midjourney
```
Extreme wide low-angle shot of battlefield sky,
massive vortex of dark storm clouds gathering,
giant white-blue lightning bolt striking down from clouds,
in the brief illuminated instant, distant silhouette of robed figure
on a high ridge holding up double-handed war hammer,
ONLY SILHOUETTE, NO FACE, backlit shape only,
extreme distance making figure tiny but recognizable,
cold 6500K storm lighting with bright blue lightning highlight,
+ [通用尾缀]
```

### Veo 3
```
Extreme wide low-angle shot of stormy battlefield sky,
storm clouds swirling, then a massive blue lightning bolt strikes down,
in the lightning flash, distant silhouette of figure with hammer raised
appears for 0.5 seconds on high ridge,
no face visible, only silhouette,
3 seconds total, cold storm lighting,
+ [通用尾缀]
```

---

## 镜头 #12 · 苦工抬头看雷雨

### Midjourney
```
Medium close-up low-angle shot of orc peon Grosh in lumber camp,
he has lowered his axe, looking up at sky for the first time,
distant lightning briefly flashing in his eyes,
first raindrops falling onto his weathered face,
he blinks slowly,
warm 5500K lumber camp light transitioning to cooler raincloud light,
+ [通用尾缀]
--cref [格罗什锚定图URL] --cw 100
```

### Veo 3
```
Medium low-angle shot of orc peon Grosh,
he slowly raises his head looking upward,
raindrops begin falling on his face, he blinks once,
camera tilts up gently following his gaze,
2 seconds, transitioning lighting,
+ [通用尾缀]
```

---

## 镜头 #13 · 苦工扛金箱

### Midjourney
```
Medium full-body tracking shot from side,
orc peon Grosh hoisting massive Horde-sigil gold crate larger than himself,
walking through muddy red Durotar earth from gold mine toward camp,
muscles trembling under load, every step deep into mud,
toes gripping mud, sweat soaking through linen tunic,
he does NOT look up, only heavy breathing,
warm 5500K late afternoon lighting, dust kicked up,
+ [通用尾缀]
--cref [格罗什锚定图URL] --cw 100
```

### Veo 3
```
Side tracking shot of orc peon walking with massive gold crate on shoulders,
camera tracks alongside him then slowly pans down to feet,
each step sinking deep into mud,
muscles trembling, heavy breathing,
3 seconds, warm afternoon light,
+ [通用尾缀]
```

---

## 镜头 #14 · 战士背伤兵（镜像）

### Midjourney
```
Medium full-body tracking shot from side (mirror of #13),
orc warrior Lok'ra carrying unconscious wounded comrade on his back,
walking through muddy battlefield from corpse pile toward camp,
muscles trembling under weight, every step deep into mud,
comrade's bloody arm dangling and swaying with each step,
he does NOT look up, only heavy breathing,
cold 6500K late afternoon battlefield lighting, smoke in background,
+ [通用尾缀]
--cref [洛卡锚定图URL] --cw 100
```

### Veo 3
```
Side tracking shot of orc warrior carrying wounded comrade on back,
camera tracks alongside him then slowly pans down to feet (matching #13 exactly),
each step sinking deep into mud,
comrade's arm swaying with each step,
3 seconds, cold battlefield light,
+ [通用尾缀]
```

---

## 镜头 #15 · 战士黄昏剪影 ★ 海报候选

### Midjourney
```
Wide cinematic anamorphic shot of orc warrior silhouetted against
massive orange sunset on horizon,
standing on Barrens battlefield ridge path, leaning on two-handed war axe,
long shadow cast forward toward camera,
gentle wind blowing wolf pelt and warrior topknot,
distant Kalimdor mountain ridges, sparse acacia trees,
The Last Samurai composition,
warm 4200K twilight color, 85mm long lens,
black silhouette + orange-red sky composition only,
+ [通用尾缀]
--cref [洛卡锚定图URL] --cw 100
```

### Veo 3
```
Wide static shot of orc warrior silhouetted against massive sunset,
camera completely locked off,
he stands leaning on war axe, wind blowing his topknot and pelt gently,
4 seconds of stillness, only wind movement,
warm twilight light, anamorphic cinematic feel,
+ [通用尾缀]
```

---

## 镜头 #16 · 苦工黄昏剪影（镜像）★ 海报候选

### Midjourney
```
Wide cinematic anamorphic shot of orc peon silhouetted against
massive orange sunset on horizon (SAME composition as #15),
standing on Durotar lumber camp path, leaning on worn lumber axe,
long shadow cast forward toward camera,
gentle wind blowing single thick braid,
distant Durotar mountain ridges, sparse trees,
The Last Samurai composition,
warm 4200K twilight color, 85mm long lens,
black silhouette + orange-red sky composition only,
+ [通用尾缀]
--cref [格罗什锚定图URL] --cw 100
```

### Veo 3
```
Wide static shot of orc peon silhouetted against massive sunset,
camera completely locked off (matching #15 exactly),
he stands leaning on lumber axe, wind blowing his braid gently,
3 seconds of stillness, only wind movement,
warm twilight light, anamorphic cinematic feel,
+ [通用尾缀]
```

> 出图后的检查方式：把 #15 和 #16 在 Photoshop 里叠加 50% 透明度，
> 人物位置应该几乎重合。如果不重合，重出图。

---

## 镜头 #17 · 篝火 · 递肉干 ★★★ 情感最高点

### Midjourney 17A（中景）
```
Cinematic medium shot at orc Horde campfire night,
massive 1.5m diameter stone fire pit with 1m tall flames,
embers floating upward into deep blue starry sky,
warriors and peons sitting on log benches around fire,
warrior Lok'ra walking through with wooden bowl,
he stops, half his face lit warm orange firelight, half in shadow,
warm 1900K firelight + cool 7000K background moonlight (complementary),
volumetric smoke heat distortion above flames,
+ [通用尾缀]
--cref [洛卡锚定图URL] --cw 100
```

### Midjourney 17B（双人特写）
```
Cinematic close-up two-shot at campfire,
warrior Lok'ra (left) extending hand with strip of dried jerky,
peon Grosh (right) looking up with stunned expression, eyes wet but no tears,
firelight from below illuminating both faces from beneath,
half-warm half-shadow chiaroscuro lighting on each face,
warm 1900K firelight + cool 7000K background,
shallow depth of field, 85mm portrait lens,
hyperdetailed face textures showing weariness, scars, dirt,
+ [通用尾缀]
--cref [洛卡 + 格罗什锚定图组合] --cw 100
```

### Veo 3
```
Two-part shot at orc campfire at night:
First 2s: medium shot, warrior walks past peons, stops, turns back to look,
Then 3s: close-up two-shot, warrior reaches into pouch, takes out jerky strip,
extends it slowly toward peon who looks up stunned, takes it with both hands,
camera slow push-in through both shots,
warm firelight on faces, cool blue night sky background,
embers floating, gentle heat distortion,
intimate emotional moment, no dialog yet,
+ [通用尾缀]
```

---

## 镜头 #18 · 双人台词

### Midjourney 18A
```
Side profile two-shot at campfire close-up,
peon Grosh (left) just bit into jerky, looks at warrior, grins showing tusks,
warrior Lok'ra (right) returning the smile, nodding slightly,
firelight glinting on tusks and wet eyes,
warm 1900K close intimate lighting,
85mm portrait lens, shallow depth of field,
+ [通用尾缀]
```

### Midjourney 18B
```
Side profile two-shot at campfire close-up,
peon and warrior raising their food/water-skins toward each other,
brief tap touching like brothers' toast,
firelight glinting between them,
warm 1900K, dramatic but warm,
85mm portrait lens,
+ [通用尾缀]
```

### Veo 3
```
Side profile two-shot at campfire:
peon bites jerky, looks at warrior, grins showing tusks (1.5s),
warrior smiles back, nods (1.5s),
they raise food and water-skin and tap them together (1s),
intimate firelight, no camera movement except very slow push,
no dialog audio (will be added in post),
+ [通用尾缀]
```

---

## 末段字幕

字幕用 After Effects 制作，不需要 AI 生成。

```
0:58 - 0:59  "For the Horde."        (Trajan Pro Bold, white #FFFFFF, gold stroke #C9A961)
0:59 - 1:00  "And for those who built it."

中文版：
0:58 - 0:59  "为了部落。"             (思源宋体 Heavy, white #FFFFFF, gold stroke #C9A961)
0:59 - 1:00  "也为了筑起部落的他们。"
```

---

## 抽卡操作建议

### 抽卡顺序

| 阶段 | 镜头 | 优先级 | 备注 |
|------|------|--------|------|
| 1 | cref 锚定图 | ★★★★★ | 必须先做，否则全乱 |
| 2 | #5, #8（核心主题镜） | ★★★★★ | 最难做对，先攻克 |
| 3 | #6, #7（CG 大场面） | ★★★★★ | 最贵，预算重头 |
| 4 | #15, #16（黄昏海报镜） | ★★★★ | 必须严格镜像 |
| 5 | #17（情感高点） | ★★★★ | 表演难，多抽 |
| 6 | 其他普通镜头 | ★★★ | 标准抽卡 |

### 抽卡预算预估

| 镜头类型 | 单镜抽卡次数 | 单次成本（Veo 3 估算） | 单镜成本 |
|---------|------------|---------------------|---------|
| 大场面 (#6, #7) | 30 次 | ¥30 | ¥900 / 镜 |
| 核心主题 (#5, #8, #15-#16, #17) | 20 次 | ¥30 | ¥600 / 镜 |
| 普通镜 (其他) | 8 次 | ¥30 | ¥240 / 镜 |
| **合计** | **约 200 次** | | **约 ¥6000** |

> Kling / Hailuo 比 Veo 3 便宜约 1/3，可用于普通镜头降低成本。
> 关键镜头（#6, #7, #8, #17）务必用 Veo 3。

### 抽卡验收标准

每个镜头出来后，逐项检查：

- [ ] 角色脸部与 cref 锚定图一致度 ≥ 80%
- [ ] 关键道具特征齐全（疤、纹身、武器特征）
- [ ] 运镜符合本表 Prompt 描述
- [ ] 时长接近目标（±0.5 秒可接受）
- [ ] 光照色温符合调色规范
- [ ] 没有 AI 瑕疵（多手指、扭曲面孔、透视错误）
- [ ] 镜像组（#3-#4 等）构图重合度 ≥ 80%
