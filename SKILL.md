---
name: pop-commercial-poster-skill
description: Generate a Simplified-Chinese 9:16 poster in the 「波普商业」(pop-commercial) style by 一张有戏. Use when the user wants a 波普商业 / pop commercial poster.
---

# 波普商业 · pop-commercial poster skill

一张有戏「波普商业」风格海报技能。输出一张 9:16 竖版、简体中文的独立海报。

## 用法
1. 确定一个主标题（2–4 字）和一句短句。
2. 画面只出现三段文字：主标题、短句、页脚「一张有戏 · 视觉习作」。
3. 版式可选：centered-hero, poster-card。
4. 参照下方完整提示词模板，替换 Headline / Supporting phrase / 场景描述。

## 示例主题
- 柑橘汽水：把清爽画成鲜亮的颜色（centered-hero）— Unbranded chilled clear glass of orange soda, orange slice, cobalt/yellow halftone and one bold comic burst.
- 莓好一天：让一口甜拥有明亮的形状（poster-card）— Generic clear strawberry yogurt cup with no packaging label, fresh strawberry cutouts, bright pink and cyan graphic shapes.
- 一口脆：把酥脆的瞬间放大（centered-hero）— Golden potato chips suspended around one simple unbranded paper cone, red/yellow bold halftone commercial still-life.
- 咖啡醒醒：让清醒从画面开始（poster-card）— One clear iced coffee glass with visible ice, cobalt and bright coral fields, chunky readable Chinese lettering.
- 冰淇淋日：给日常加一点柔软（centered-hero）— One creamy soft-serve cone hero, pink and lemon fields, clean pop repetition of tiny cone silhouettes, controlled halftone.
- 吐司出炉：把暖意留在这一片里（poster-card）— One toasted bread slice and tiny butter curl, bright yellow/cobalt controlled shapes and chunky title, no factual nutritional claims.
- 糖果星球：把快乐装进一颗颜色（centered-hero）— Three brightly wrapped generic candies as one clustered focal subject, saturated coral/cyan ground and disciplined dots.
- 桃气时刻：让果香先成为画面（poster-card）— One clear peach drink with fresh peach wedge, bright peach-pink and cobalt blocks, glossy still-life with bold pop type.

## 完整提示词模板（第 1 张原文）
```
Use case: ads-marketing. Create exactly ONE polished professional 9:16 portrait poster, static flat artwork, Chinese-mainland cultural/creative studio portfolio concept.
Language: Simplified Chinese. Headline: 柑橘汽水. Supporting phrase: 把清爽画成鲜亮的颜色. Tiny plain footer: 一张有戏 · 视觉习作. Exact visible text ONLY these three phrases, every character correctly formed. No English, random numbers, fake events, dates, addresses, awards, offers, prices, affiliations, calls to action or status labels. All content is fictional/conceptual creative brief, no real client claim.

SOURCE UNIVERSAL RULES:


These rules apply to every poster. Do not repeat them in layout or style notes.

- Build around one dominant message, one clear focal point, and one communication goal.
- Establish a simple reading order: headline -> focal image -> supporting copy -> supplied details.
- Preserve required copy exactly unless the user explicitly asks for rewriting.
- Keep important text readable, high-contrast, and inside safe margins.
- Use confident spacing and avoid overstuffed layouts.
- Avoid fake extra text, random logos, QR codes, decorative clutter, malformed typography, and generic AI-poster noise.
- Treat the poster canvas as static print/editorial artwork rather than a clickable interface. If the source explicitly requests a product UI, browser window, dashboard, or device mockup, preserve that depicted content inside the poster.
- CTA copy is extractive-only: include it only when the source explicitly supplies the wording. When output language differs, verify the translated CTA against a recorded exact source quote. Never invent action or status labels.
- If no CTA is sourced, leave the action area empty. If one is sourced, render it as ordinary poster typography in a footer or text lockup. Do not place poster-level action copy inside a button, rounded rectangle, pill, chip, capsule, tab, input field, or any other clickable-looking UI container; do not decorate it with a shadow, arrow, chevron, or cursor icon.



SELECTED STYLE — STRICTLY THIS VISUAL SYSTEM, DO NOT MIX OTHER STYLES:
# Pop Commercial

## Intent

Create a bright, high-impact commercial poster that feels energetic, immediate, product-forward, and easy to understand.

## Typography

- Use bold friendly display sans-serif or chunky headline type.
- Make offer/product names highly readable.
- Use badges, bursts, labels, or repeated words only with discipline.

## Palette

Bright saturated palette: red, yellow, blue, pink, cyan, orange, lime. Use strong contrast and controlled combinations.

## Imagery

Use product cutouts, expressive objects, halftone cues, stickers, comic-like accents, repetition, or simple character energy.

## Texture / Material

Glossy product lighting, halftone dots, screenprint texture, paper cutouts, clean vector shapes.

## Composition Rules

- Put the product or offer in the first read.
- Use clear source-supplied price and offer placement. If action copy is supplied, render it as plain promotional typography without button styling.
- Keep energy high but hierarchy simple.
- Use repetition to amplify, not clutter.

## Avoid

Unreadable sale clutter, too many badges, fake discount text, distorted packaging, muddy colors, and generic cartoon chaos.


INTERNAL COMPOSITION:
# Centered Hero

## Composition Structure

- Place one dominant subject in the optical center.
- Keep headline above, below, or tightly integrated with the hero subject.
- Use symmetrical or near-symmetrical balance with subtle asymmetry for sophistication.
- Reserve the bottom area for source-supplied date, location, sponsor, or other factual details. If the source includes action copy, typeset it as a plain footer line rather than a button.

## Hierarchy Rules

1. Hero subject and headline compete as a unified first read.
2. Subheadline supports the meaning without fragmenting attention.
3. Details sit smaller in a stable footer or corner lockup.

## Text Placement

- Use large, simple headline blocks.
- Keep secondary copy outside the hero silhouette.
- Avoid placing small text over textured image areas.

## Image Treatment

Use a clean product/person/object/abstract hero with strong lighting, crisp edges, and controlled background separation.

## Spacing Rules

Use generous margins and breathing room around the hero. Do not fill every corner.

## Aspect-Ratio Behavior

Works especially well in `2:3`, `3:4`, `4:5`, and `9:16`. In `16:9`, widen the hero and shift text into side gutters.

## Avoid

Multiple competing subjects, busy backgrounds, small scattered text, and generic centered stock-poster symmetry.


SPECIFIC SUBJECT AND ART DIRECTION:
Unbranded chilled clear glass of orange soda, orange slice, cobalt/yellow halftone and one bold comic burst.

Quality: exquisite thoughtful art direction, one immediate focal point, sophisticated typographic spacing and clear reading order, original expressive composition with wide enough safe margins. Headline large and readable at phone thumbnail; secondary text restrained, not generic template. Typography adapted sensitively to real Chinese glyphs, with the visual weight demanded by style. Material/light/print treatment consistent with selected style. If any person appears, fictional mainland Chinese adult, natural anatomy and authentic face; otherwise no people. All props physically coherent unless the SPECIFIC surreal idea deliberately changes physics. No trademarks or label text on products, no fake logos/watermarks/QR. No poster mockup, wall frame, multiple-poster collage, UI buttons or decorative website components. The creative theme must determine composition; vary crop, hierarchy and negative space across the series. Output one finished poster only.
```

全部 8 条提示词见 `PROMPTS.json`，来源见 `SOURCES.md`。
