---
name: xiaochai
description: 小柴 IP 视觉工具（戴橙色渔夫帽的淡定柴犬）。为中文文章、公众号、小红书、X 帖子生成"封面"和"正文配图"，所有图都以小柴为主角。触发词：小柴、柴犬、IP、封面、头图、配图、正文插图、shot list、给这篇文章做图。正文配图改编自 Ian Xiaohei Illustrations（MIT），封面改编自 Punk Skill v1.0.0-mit（MIT）。
---

# 小柴

## 先读

- `xiaochai-ip.md`：小柴是谁、长什么样、性格、禁忌。**每次都读。**
- 角色参考图：`assets/character/sheet/` 下的标准照是长相唯一标准。总附 `01-front.png`，再按动作加附对应姿势（见该目录 README）。生图工具支持参考图时必须附上。`assets/character/xiaochai-origin.png` 只是出处存档。

## 选择工作流

| 用户要什么 | 走哪条 |
|---|---|
| 封面、头图、首图、题图、cover | `cover/workflow.md` |
| 正文配图、文章插图、shot list、解释图 | `illustration/workflow.md` |
| "给这篇文章做图"、"封面加配图"、全套 | 先封面后配图，两条都走；封面默认用 `xiaochai-house` 风格以保持系列感，除非用户另选 |

## 全局铁律

1. 每张图都有小柴，且小柴在做事，不是装饰。
2. 橙色渔夫帽永远在、永远是橙色、全图只有一顶。
3. 淡定微笑，不卖萌、不 Q 版、不表情包。
5. **不画任何真实品牌的标志**（如各家 AI 产品、App 图标）。要表示"工具"就用通用的方块、齿轮、扳手、对话框等无品牌符号。
4. 生图后检查：认不认得出是小柴、帽子是否只有一顶、**数脚（只能四条腿）**；有问题就局部修或重画。

## 生图方式

- Codex：内置 `image_gen`，附角色参考图。
- Claude Code：用 `codex exec` 委派，参考图用 `-i`，提示词从标准输入传（`-i` 会吞掉后面的提示词参数）。

## 产物存放

- 封面：`assets/covers/{slug}/`
- 配图：`assets/{slug}-illustrations/`
- 满意的成品同步一份到小柴仓库的 `gallery/`，附同名 `.md` 说明。
