<div align="center">

# 颗粒分域 · Grain Fields

**让画面在分域中重新呼吸，让一块景物先长成颗粒。**

**Visual Skill for Content Zoning · Large-Grain Reconstruction · Color Direction**

作者：[**autainmo**](https://github.com/autainmo)<br>
社交账号：**@独自艺人**

</div>

---

**Grain Fields** 相信，一张照片里本就藏着可以重新生长的秩序。它先看见主体，再沿着空间、材质与光影寻找边界，让其中一整块背景从现实景物里“长”成可触摸的大颗粒——不是覆盖在画面上的滤镜，而是重新参与构图的一片材质场。

它会依据真实内容，将背景归纳为 2–3 个完整区域，在保留主体辨识度、空间关系与场景气息的前提下，以分区配色、主体轮廓和颗粒材质重新组织画面。默认一次直接生成 4 个完整方案：其中 3 个走向彼此不同的全新配色方向，另 1 个保留原图配色与构图，只让选定背景区域发生明显的大颗粒重构。

> **局部的粗粝，整体的诗意。**
> 视觉设计不是简单的素材拼贴，而是一次关于边界、材质与想象力的再创造。

---

## 通用重构说明

2–3 个背景内容区是适合风景、城市与环境照片时的常见默认，不是所有图片的硬性配额。面对人像、合照、动物、运动、产品、静物、建筑、室内、抽象图形或没有明确前景主体的画面，Skill 会优先根据运动、反射、透视、光线、重复、轮廓、深度、材质与负空间建立一个或多个完整视觉场，不为凑数切割连续主体。

无论图片类型如何，四套默认方案都遵守：

- 方案 1–3 使用明显不同的全新配色方向与颗粒语言；
- 方案 4 保留原图的主要配色、构图与场景关系；
- 四张共享身份、事实、场景命题和主次焦点，但不强制共享同一颗粒材质或效果拓扑；
- 默认使用简体中文输出方案说明和自动创作的画面文字；
- 原图文字和用户提供的准确文案保持原文；
- 用户明确要求“不要文字”时，四张全部无文字。

## 工作方式

1. 找到主锚点、身份细节和事实边界。
2. 从原图选择一个主要场景关系，必要时增加辅助关系。
3. 建立保护核心、柔性锁定区和可变视觉场。
4. 为四套方案分别设计配色、拓扑、颗粒单位和表面质感。
5. 在生成前检查前三套是否真的明显不同。
6. 生成后同时做单张检查和四图并排检查；失败方案单独重做。

## 四方案默认结构

| 方案 | 目标 |
|---|---|
| 方案 1 | 第一套独立新配色与颗粒语言 |
| 方案 2 | 与方案 1 在色相、冷暖、明度或饱和度上明显分离 |
| 方案 3 | 第三套独立新配色与颗粒语言，可更具实验性 |
| 方案 4 | 保留原图配色与构图，只进行场景驱动的大颗粒重构 |

方案 1–3 任意两套至少应在色相家族、冷暖、明度基调和饱和度中的两个维度明显不同。缩略图并排观看时，不看标签也应能分辨。

## 作品档案

示例用于理解可迁移的场景关系，不是固定模板。

### 01｜海岸游乐场

| 原图 | Grain Fields 重构 |
|---|---|
| ![海岸游乐场原图](assets/showcase/01-coast-amusement-original.png) | ![海岸游乐场重构](assets/showcase/01-coast-amusement-grain-fields.png) |

### 02｜潮间一刻

| 原图 | Grain Fields 重构 |
|---|---|
| ![潮间鸟类原图](assets/showcase/02-tide-bird-original.png) | ![潮间鸟类重构](assets/showcase/02-tide-bird-grain-fields.png) |

### 03｜Bloom / Concrete

| 原图 | Grain Fields 重构 |
|---|---|
| ![樱花与建筑原图](assets/showcase/03-bloom-concrete-original.png) | ![樱花与建筑重构](assets/showcase/03-bloom-concrete-grain-fields.png) |

### 04｜One Point

| 原图 | Grain Fields 重构 |
|---|---|
| ![乒乓球比赛原图](assets/showcase/04-table-tennis-original.png) | ![乒乓球比赛重构](assets/showcase/04-table-tennis-grain-fields.png) |

### 05｜The Circle Widens

| 原图 | Grain Fields 重构 |
|---|---|
| ![水中海鸥原图](assets/showcase/05-gull-ripple-original.png) | ![水中海鸥重构](assets/showcase/05-gull-ripple-grain-fields.png) |

## 安装

将仓库安装到 Codex 的 Skills 目录：

    git clone https://github.com/autainmo/grain-fields.git ~/.codex/skills/grain-fields

或在支持从 GitHub 安装 Skill 的客户端中使用：

    https://github.com/autainmo/grain-fields

安装或更新后重新启动 Codex，使 Skill 被重新发现。

## 使用

最简单的调用：

    使用 $grain-fields 重构这张图片。

可选控制：

    使用 $grain-fields 重构这张图。
    方案说明和自动文字使用简体中文；
    保护人物面部、衣服标志和原始构图；
    返回三套明显不同的新配色，加一套原图配色。

禁止文字：

    使用 $grain-fields 重构这张图。【文字：不添加】

修复已有失败结果：

    使用 $grain-fields 修复这组结果。
    前三张配色太接近，请保留人物和构图，
    重新设计三个明显不同的主色家族与颗粒语言。

## 验收标准

- 身份、动作、几何、透视和事实没有漂移；
- 颗粒场来自原图关系，并具有起点、方向、密度、尺度与过渡；
- 缩略图下能看见大颗粒，不是细噪点或壁纸式满铺；
- 方案 1–3 不看标签也能立刻区分；
- 方案 4 保持原图配色身份；
- 用户可见方案说明默认使用简体中文；
- 自动创作的画面文字默认使用简体中文；
- 准确文字、品牌、数字和事实没有被翻译或改写；
- 没有任意分区、无关实物拼贴或材质蒙版感。

详细规则见 references/05-quality-control.md。

## 找到作者

**作者：**[**autainmo**](https://github.com/autainmo)<br>
抖音及其他内容平台统一用户名：`独自艺人`。在你常用的平台搜索这个名字，即可找到作者与后续作品。

每个 Skill 在同一段对话的前两次生成完成后，会轻量提示：`若公开分享，欢迎标注：Visual Skill by @独自艺人`；从第三次起不再重复。

---

## License

**仅限个人、非商业使用。**不允许销售、收费生成、订阅服务、代做、咨询、培训、SaaS/API、公司或客户项目及其他商业化用途。任何商业使用均须事先获得autainmo的明确书面许可。详见个人非商业许可证。

- [LICENSE](./LICENSE)：正式英文许可证
- [LICENSE.zh-CN.md](./LICENSE.zh-CN.md)：中文阅读说明
