# 生图提示词模板

每张图单独生成。**如果生图工具支持参考图，务必附上 `assets/character/sheet/01-front.png`，并按动作加附对应姿势的标准照**，严格照标准照的长相和画风画。

```text
Generate one standalone 16:9 horizontal Chinese article illustration.

Visual DNA:
Pure white background. Minimalist black hand-drawn line art. Slightly wobbly pen lines. Lots of empty white space. Sparse red/orange/blue handwritten Chinese annotations. Clean absurd product-sketch feeling. No gradients, no shadows, no paper texture, no complex background, no commercial vector style, no PPT infographic look, no cute mascot poster, no children's illustration, no realistic UI.

Recurring IP character required:
小柴, a small Shiba Inu dog drawn in loose black hand-drawn line art, with a flat light-tan fill and white muzzle/cheeks, upright triangle ears, small black bean eyes, black nose, a calm faint smile, curly tail. It ALWAYS wears an orange bucket hat with a dashed stitched brim and a small button on top — the hat is its signature. (Reference images are attached: match the dog's face, fur colors, hat and hand-drawn colored style exactly.) 小柴 must perform the core conceptual action, not decorate the scene. Calm, deadpan, slightly absurd, not cute, not chibi.

Optional signature motif (use only if it serves the idea):
小柴 half-submerged in a small patch of light-blue water lines, only head and hat visible / taking off its orange hat and using it as a bucket (then its head is bare — only ONE hat in the whole image) / a small pink floating ball as the goal.

Theme:
{正文配图主题}

Structure type:
{结构类型：Workflow / 系统局部 / 前后对比 / 角色状态 / 概念隐喻 / 方法分层 / 地图路线 / 小漫画分镜}

Core idea:
{这张图要表达的核心意思}

Composition:
{具体画面：小柴在哪里、正在做什么、主要物件是什么、信息如何流动}

Suggested elements:
{元素1} / {元素2} / {元素3} / {元素4}

Chinese handwritten labels:
{标注词1} / {标注词2} / {标注词3} / {标注词4} / {可选标注词5}

Color use:
Black for main line art. Light tan fill only on 小柴's body. Orange for 小柴's hat and the main flow/path/arrows. Red only for key warnings/problems/results. Blue only for water lines, secondary notes or system state.

Constraints:
One image explains only one core structure. Keep the main subject around 40%-60% of the canvas. Preserve at least 35% blank white space. Use at most 5-8 short handwritten Chinese labels. Do not write a title in the top-left corner. Do not write the structure type on the image. Do not make it a formal diagram, course slide, or dense explainer. Invent a fresh visual metaphor for this specific article. It should be clear but not instructional, interesting but not childish, strange but clean.
```

## 图像编辑提示

去掉左上角标题：

```text
Edit the provided image. Remove only the handwritten title "{要删除的文字}" and its underline from the top-left corner. Fill that area with the same clean white background. Preserve everything else exactly. Do not add any new text or objects.
```

角色走样修正：

```text
Edit the provided image. Keep the composition, labels and line style. Redraw only the dog so it matches the reference character: Shiba Inu, light tan with white muzzle, calm faint smile, orange bucket hat with dashed stitched brim and top button. Hand-drawn line art, not cute, not chibi.
```

增强怪诞感：

```text
Regenerate this illustration with the same core meaning and simple layout, but make 小柴 more central to the conceptual action. 小柴 should be doing the strange work that explains the idea, not standing beside the diagram. Keep it clean, sparse, hand-drawn, and not cute.
```
