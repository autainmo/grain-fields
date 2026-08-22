<div align="center">

# 颗粒分域 · Grain Fields

**让画面在分域中重新呼吸，让一块景物先长成颗粒。**

**Visual Skill for Content Zoning · Large-Grain Reconstruction · Color Direction**

作者：[**autainmo**](https://github.com/autainmo)  
社交账号：**独自艺人**

<p align="center">
  <b>简体中文</b> ·
  <a href="./README.en.md">English</a> ·
  <a href="#安装指南">开始使用</a>
</p>
</div>

---

**Grain Fields** 相信，一张照片里本就藏着可以重新生长的秩序。它先看见主体，再沿着空间、材质与光影寻找边界，把背景归纳为 2–3 个真实内容区域，并从中选择最适合颗粒化的一整块区域，让颗粒成为场景本身的一种材质变化，而不是覆盖在画面上的滤镜。

它默认一次生成 4 个完整方案：其中 3 个使用彼此不同但整体克制的重新配色方向，另 1 个保留原图配色与构图。颗粒区域可以是大面积连续区域，但**单颗粒尺度保持适中**：不能细到只剩噪点，也不能大到变成大方块、拼豆、大像素或巨大马赛克。

> **局部的粗粝，整体的诗意。**  
> 视觉设计不是简单的素材拼贴，而是一次关于边界、材质与想象力的再创造。

---

## 颗粒分域是什么

### 审美：让颗粒成为画面的“材质场”

Grain Fields 不把颗粒当作轻微噪声，也不追求夸张的大块效果。核心颗粒区通常占画面的约 1/4–1/2，重点是区域完整、连续、适合颗粒化；颗粒单元本身保持中等视觉尺度，在正常观看时能感知颗粒质感，近看能辨认颗粒结构，但不会压过主体与场景。

### 构图：按内容分区，而不是机械切块

背景优先按真实景物、空间层次、材质和连续结构划分。海、水面、天空、岩石、建筑、墙体、植被、地面等都可以成为独立内容区；**同一个完整主体或同一连续景物不会为了分区而被强行切成两块**。颗粒区域的选择以材质适配、主体安全和自然融合为优先，而不是简单选择面积最大的区域。

### 重构：先保主体，再选择最合适的颗粒区域

人物、动物、建筑、山川、植物、车辆、器物等都可以作为主要主体。主体保留关键外形、结构、比例、姿态和识别信息，并沿真实外缘加清晰轮廓。背景颗粒化则使用自然、适中、克制的颗粒语言；用户可以指定颗粒预设，也可以让 Skill 自动匹配。

### 配色：简洁、克制、耐看

方案 1–3 仍会明显区分，但默认控制在 2–4 个核心颜色角色，优先中低饱和、中性色、清晰明度层次和少量强调色。局部可以保留轻微印刷、材质或细节变化，但不会为了“设计感”刻意堆叠霓虹、多色渐变、贴纸和装饰。

---

## 作品档案

下面的示例展示 Grain Fields 如何把内容分区、主体轮廓、分区配色和颗粒质感组合到同一张重构图中。

### 01｜海岸游乐场：城市 / 游乐设施 / 水岸的三层关系

| 原图 | Grain Fields 重构 |
|---|---|
| ![海岸游乐场原图](assets/showcase/01-coast-amusement-original.png) | ![海岸游乐场 Grain Fields 重构](assets/showcase/01-coast-amusement-grain-fields.png) |

**重构思路：** 保留摩天轮、游乐设施与海岸结构，把城市建筑群作为连续颗粒区处理；水面保持相对干净并承担文字区，让城市颗粒与开阔水面形成呼吸。颗粒尺度控制在适中范围，不让单个网点压过建筑结构。

### 02｜潮间一刻：水面 / 礁石 / 鸟的逆光关系

| 原图 | Grain Fields 重构 |
|---|---|
| ![潮间鸟类原图](assets/showcase/02-tide-bird-original.png) | ![潮间鸟类 Grain Fields 重构](assets/showcase/02-tide-bird-grain-fields.png) |

**重构思路：** 以水面、礁石和鸟作为三种视觉角色，保留鸟的姿态与逆光轮廓；颗粒处理顺着水面和礁石原有明暗变化展开，使复杂反光被概括为更清楚、但仍自然的纹理节奏。

### 03｜Bloom / Concrete：花枝与建筑表皮

| 原图 | Grain Fields 重构 |
|---|---|
| ![樱花与建筑原图](assets/showcase/03-bloom-concrete-original.png) | ![樱花与建筑 Grain Fields 重构](assets/showcase/03-bloom-concrete-grain-fields.png) |

**重构思路：** 花枝作为完整主体保持花朵、叶片与枝条结构，并用白色轮廓整体提取；建筑墙面更适合使用矿物细粒、纸面印刷或柔和网点等中等颗粒，让墙面有材质变化但不变成夸张块面。

### 04｜One Point：竞技场地的中等网点重构

| 原图 | Grain Fields 重构 |
|---|---|
| ![乒乓球比赛原图](assets/showcase/04-table-tennis-original.png) | ![乒乓球比赛 Grain Fields 重构](assets/showcase/04-table-tennis-grain-fields.png) |

**重构思路：** 运动员和球台保持原位置与动作，轮廓线强化竞技主体；场地可使用中等半调或丝网网点形成明确材质差异，观众区保持更干净，强调色只用于少量关键位置。

### 05｜The Circle Widens：涟漪成为颗粒场

| 原图 | Grain Fields 重构 |
|---|---|
| ![水中海鸥原图](assets/showcase/05-gull-ripple-original.png) | ![水中海鸥 Grain Fields 重构](assets/showcase/05-gull-ripple-grain-fields.png) |

**重构思路：** 海鸥与倒影保持清晰，围绕涟漪选择完整水域作为颗粒区；更适合使用雾化颗粒、柔和网点或微晶颗粒，让颗粒顺着水纹与明暗自然变化，而不是把水面变成大晶块或卵石块面。

---

## 安装指南

### Codex

Codex 的用户级 Skills 默认位于 `$CODEX_HOME/skills`，通常是 `~/.codex/skills`。将整个仓库安装到该目录，并确保 `SKILL.md` 位于 Skill 根目录即可。

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

安装完成后重新启动 Codex，确保新 Skill 被发现。之后可通过 `$grain-fields` 调用。

> 若 Codex 环境提供 `$skill-installer`，也可以直接在 Codex 中输入：
>
> ```text
> $skill-installer install the skill from https://github.com/autainmo/grain-fields, using the repository root as the skill directory and naming it grain-fields
> ```

### 其他支持 Agent Skills / `SKILL.md` 的平台

1. 下载或克隆本仓库；
2. 保持 `grain-fields/` 目录结构完整；
3. 将整个目录放入平台规定的 Skills 路径，或使用平台提供的 GitHub / 本地 Skill 导入功能；
4. 确保平台能够读取根目录中的 `SKILL.md`、`references/` 与 `agents/`；
5. 平台具备图像生成 / 编辑能力即可执行四方案流程。

---

## 使用指南

最简单的使用方式：

```text
使用 $grain-fields 重构这张图片。
```

默认行为：

- 自动理解主体与场景；
- 背景按内容划分为 2–3 个完整区域；
- 先选择最适合颗粒化的背景区域，再决定颗粒与配色；
- 直接生成 4 张结果，不等待二次确认；
- 方案 1–3 使用彼此不同但简洁克制的配色；
- 方案 4 保留原图配色、构图、主体位置与景物关系；
- 颗粒区连续、成片，但颗粒单元保持适中；
- 主要主体沿真实外缘加清晰轮廓，默认纯白；
- 用户没有提供文字时，可按每个方案自动创作适配文本。

### 可选用户输入模板

所有字段都可以删除；只填写你真正希望控制的内容。

```text
【颗粒方案：自动 / 预设名称】
【配色方案：自动 / 预设名称】
【文本方案：自动 / 预设名称】
【比例 / 载体：原图 / 预设名称 / 自定义比例】
【文字：自动 / 不添加 / 使用下方文本】

【标题：】
【副标题：】
【正文：】
【地点：】
【时间：】
【相机信息：】
【镜头 / 焦段：】
【拍摄参数：】
【人物 / 主体信息：】
【事件 / 主题：】
【天气 / 环境：】
【摄影者 / 署名：】
```

**如果你希望重构后的图片完全没有任何文字，请在上传图片时明确写 `【文字：不添加】`、`不要文字` 或同等表达。**

事实信息遵循严格约束：地点、时间、相机型号、镜头、人物身份、事件、天气、署名等未由用户提供且无法可靠确认时，不得编造。

---

## 预设内容索引

### 颗粒预设

> 完整规则与适配逻辑见 [`references/presets-grain.md`](references/presets-grain.md)。

**印刷 / 网点**  
`柔和网点`、`中等半调`、`丝网网点`、`Riso 孔版颗粒`、`报纸细粗过渡`、`油墨轻缺失`

**自然 / 矿物**  
`柔砂颗粒`、`矿物细粒`、`石墨颗粒`、`纸浆纤维颗粒`、`微晶颗粒`、`釉面细粒`

**柔和 / 光学**  
`雾化颗粒`、`柔焦颗粒`、`银盐颗粒强化`、`纸面印刷颗粒`

不使用：大方块、大像素、拼豆、巨大马赛克砖、梦幻方块、玻璃方块、巨型低多边形、玩具 / 糖果式颗粒。

### 配色预设

> 完整配色库见 [`references/presets-color.md`](references/presets-color.md)。自动模式优先克制方向，如 `冷感克制`、`高级灰`、`米白极简`、`北欧清冷`、`日系清透`、`建筑极简`、`都市冷灰`、`自然中性`、`克制增强`、`局部灰调聚焦`、`原色保留强化`。

### 文本方案预设

> 完整文本库见 [`references/presets-text.md`](references/presets-text.md)。

### 比例 / 载体预设

> 完整比例与载体库见 [`references/presets-aspect.md`](references/presets-aspect.md)。

---

## 仓库结构

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

## 找到作者

**作者：**[**autainmo**](https://github.com/autainmo)  
抖音及其他内容平台统一用户名：`独自艺人`。在你常用的平台搜索这个名字，即可找到作者与后续作品。

每个 Skill 在同一段对话的前两次生成完成后，会轻量提示：`若公开分享，欢迎标注：Visual Skill by @独自艺人`；从第三次起不再重复。

---

## License

**仅限个人、非商业使用。**不允许销售、收费生成、订阅服务、代做、咨询、培训、SaaS/API、公司或客户项目及其他商业化用途。任何商业使用均须事先获得autainmo的明确书面许可。详见个人非商业许可证。

- [LICENSE](./LICENSE)：正式英文许可证
- [LICENSE.zh-CN.md](./LICENSE.zh-CN.md)：中文阅读说明
