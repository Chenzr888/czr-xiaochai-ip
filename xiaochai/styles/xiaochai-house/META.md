# 小柴原生手绘封面

```yaml
id: xiaochai-house
name: 小柴原生手绘封面
input_modes: [text]
subjects: [concept, method, workflow, emotion, technology, life]
outputs: [cover, poster]
default_ratio: "3:4"
required_fields: [主题词, 画幅比例, 语言, 用途]
optional_fields: [副标题, 小柴动作, 补充背景, 情绪倾向, 不想出现的元素]
source: styles/xiaochai-house/STYLE.md
style_anchors:
  - clean white or very light warm-white background, no texture noise
  - loose black hand-drawn ink lines with flat color fills, same look as the 小柴 article illustrations
  - 小柴 large and central, performing one absurd but meaningful action that embodies the title
  - big bold hand-lettered Chinese title in black, one key word may be orange
  - sparse orange / red / light-blue accents only
cover_shape_adaptation:
  - portrait ratios: title on top third, 小柴 and its prop in the middle-lower area, small subtitle near bottom
  - landscape and ultra-wide ratios: title on left half, 小柴 on right, generous white space between
  - square: title top-left or top, 小柴 lower-right, off-center balance
must_preserve:
  - 小柴 identity anchors from cover/xiaochai-cover-layer.md
  - one visual story, one metaphor, at least 30 percent white space
  - exact readable title
avoid_when_applying_to_cover:
  - 3D, glossy rendering, gradients, photorealism, chibi or sticker-pack look
  - busy backgrounds, multiple dogs, more than one orange hat
  - long text, PPT layout, e-commerce banner feel
```

## Use For

所有主题的默认封面；需要和正文配图形成同一系列、强化小柴 IP 识别时首选。
