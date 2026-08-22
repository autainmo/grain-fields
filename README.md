# Grain Fields

Grain Fields 是一个面向 Codex / ChatGPT 的通用图像重构 Skill。

它不会先把图片硬切成固定区域，也不会随机抽取“石头、糖果、马赛克”等材质贴到画面上。它先识别图片本身最有意义的关系——运动、反射、透视、光线、重复、轮廓、深度、材质或负空间——再把这个关系组织成可读的大颗粒视觉场。

核心命题：

> 保住原图的身份与事实，让场景中已有的关系变成可见的颗粒场。

## 适用场景

- 人像、合照、动物、运动与动作图像
- 建筑、室内、城市、风景与无明确前景主体的画面
- 产品、食物、静物、海报、插画、渲染和抽象图形
- 修复“贴图感、乱分区、材质幻觉、层级混乱、四张图互不相关”的 Grain Fields 结果

普通修图、去物、写实修复或单纯调色不属于这个 Skill 的职责。

## 工作方式

1. 找到主锚点、身份细节与事实边界。
2. 从场景中选择一个主关系，必要时增加一个辅助关系。
3. 建立保护核心、柔性锁定区和可变视觉场。
4. 先选效果拓扑，再选颗粒单位和表面质感。
5. 生成一个通过验收的主版本，再派生同一家族的变体。
6. 同时在缩略图和原尺寸下检查；失败时只修复主问题。

默认返回四个方向：

- A：编辑 / 图形
- B：材质 / 色调
- C：实验性但由场景关系支撑
- D：保留原图色彩逻辑

四张图共享原图结构、视觉命题、效果拓扑、主次关系和构图；只对质感、色调和一个受控变量做变化。

## 功能语法

| 层级 | 选择 |
|---|---|
| 关系基础 | 几何、运动、光线、材质、深度、重复、反射、透视、轮廓、负空间 |
| 效果拓扑 | 贴面、放射、流动、轮廓回声、结构网格、有机聚类、碎裂、景深递减、负形场 |
| 颗粒单位 | 点、色块、碎片、笔触、细胞、瓦片、像素、纤维、光孔、墨隙 |
| 行为参数 | 起点、方向、密度、尺度、边缘过渡、遮挡 |
| 表面质感 | 印刷、纸张、矿物、绘画、半透明、数字、纺织、工业 |

材质只决定外观，不决定结构。自动模式始终先选择场景关系和效果拓扑。

## 示例

这些示例展示的是可迁移的关系逻辑，不是五套必须照抄的模板。

### 海岸与城市重复结构

| 原图 | Grain Fields |
|---|---|
| ![海岸原图](assets/showcase/01-coast-amusement-original.png) | ![海岸重构](assets/showcase/01-coast-amusement-grain-fields.png) |

### 潮滩、鸟与光线层次

| 原图 | Grain Fields |
|---|---|
| ![潮滩原图](assets/showcase/02-tide-bird-original.png) | ![潮滩重构](assets/showcase/02-tide-bird-grain-fields.png) |

### 花与混凝土立面模块

| 原图 | Grain Fields |
|---|---|
| ![建筑原图](assets/showcase/03-bloom-concrete-original.png) | ![建筑重构](assets/showcase/03-bloom-concrete-grain-fields.png) |

### 乒乓球动作中心与空间透视

| 原图 | Grain Fields |
|---|---|
| ![运动原图](assets/showcase/04-table-tennis-original.png) | ![运动重构](assets/showcase/04-table-tennis-grain-fields.png) |

### 海鸥、水波与倒影

| 原图 | Grain Fields |
|---|---|
| ![海鸥原图](assets/showcase/05-gull-ripple-original.png) | ![海鸥重构](assets/showcase/05-gull-ripple-grain-fields.png) |

## 安装

将仓库安装到 Codex 的 skills 目录：

    git clone https://github.com/autainmo/grain-fields.git ~/.codex/skills/grain-fields

或在支持 Skill 安装的客户端中使用仓库地址：

    https://github.com/autainmo/grain-fields

安装后重新打开相关任务，使客户端重新发现 Skill。

## 使用

上传一张图片并调用：

    使用 $grain-fields 重构这张图片。

可以补充控制项：

    使用 $grain-fields 重构这张图。保留人物面部、衣服标志和原始构图；
    不加文字；返回 4 张；整体克制；D 版保持原图颜色。

也可以要求修复已有结果：

    使用 $grain-fields 修复这张重构图。现在像把石子贴在背景上；
    保留人物，改成从动作中心沿透视方向扩散的颗粒场。

用户明确指定的文字、数量、构图、配色、保护区域或旧预设名称优先。

## 验收标准

所有输出必须同时满足：

- 身份、动作、几何、透视和事实没有漂移；
- 一眼能读出主锚点、颗粒场和安静支撑层；
- 颗粒场有场景来源、起点、方向、密度和尺度变化；
- 缩略图下仍能看见大颗粒，而不是只有细噪点；
- 没有壁纸式满铺、贴材质蒙版、任意分区或无关物体幻觉；
- 文字准确，或在不需要时保持无文字；
- 多个变体属于同一视觉家族。

详细硬门槛与评分表见 references/05-quality-control.md。

## 仓库结构

    grain-fields/
    ├── SKILL.md
    ├── agents/openai.yaml
    ├── assets/showcase/
    ├── evals/cases.yaml
    └── references/
        ├── 00-style-core.md
        ├── 01-scene-analysis.md
        ├── 02-transformation.md
        ├── 03-art-direction.md
        ├── 04-generation-compiler.md
        ├── 05-quality-control.md
        ├── 06-visual-examples.md
        ├── 07-legacy-preset-aliases.md
        └── 08-legacy-v1-art-direction.md

08 文件是 v1 完整预设档案，只在用户明确指定旧预设名称时查询；自动模式不加载它。

## 设计说明

运行时文档保持短而分层：SKILL.md 只负责路由和工作流，references 承担按需展开的规则，evals 覆盖不同图像类型。README 不参与运行时提示，避免与核心规则重复。

## 作者与许可

Grain Fields by Momo Takahashi — https://momo-takahashi.com

代码与文档许可见 [LICENSE](LICENSE) 和 [LICENSE.zh-CN.md](LICENSE.zh-CN.md)。
