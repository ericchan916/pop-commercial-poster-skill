# 波普商业 · 完整提示词

## 填写模板 · Fill-in template

```
【主标题】：
【短句】：
【场景】：
【版式】：（centered-hero / poster-card，缺省 centered-hero）
【主色强调】：（红 / 黄 / 蓝 / 粉 / cyan / orange / lime（高对比组合））
【画幅】：9:16（默认）
```

> 只填主标题也可以：其余字段由模型根据主标题协调补全。

## 完整提示词 · Full prompt（复制以下全部）

```
【主标题】：{{主标题}}
【短句】：{{短句}}
【场景】：{{场景}}
【版式】：{{版式，缺省 centered-hero；可选 centered-hero / poster-card}}
【主色强调】：{{主色强调}}
【画幅】：{{画幅，默认 9:16}}

Create exactly ONE polished professional {{画幅，默认 9:16}} portrait poster, static flat artwork, Chinese-mainland cultural/creative studio portfolio concept.
Language: Simplified Chinese. Headline: {{主标题}}. Supporting phrase: {{短句}}. Tiny plain footer: 一张有戏 · 视觉习作. Exact visible text ONLY these three phrases, every character correctly formed. No English clutter, random numbers, fake events, dates, addresses, awards, offers, prices, affiliations, calls to action or status labels. All content is fictional/conceptual creative brief, no real client claim.
If any field above is empty, fill it coherently from 【主标题】 so scene, accent and layout support one clear idea — do not ask questions.

SELECTED STYLE — STRICTLY THIS VISUAL SYSTEM, DO NOT MIX OTHER STYLES:
# Pop Commercial
Intent: Create a bright, high-impact commercial poster that feels energetic, immediate, product-forward, and easy to understand.
Typography: Use bold friendly display sans-serif or chunky headline type. Make offer/product names highly readable. Use badges, bursts, labels, or repeated words only with discipline.
Palette: Bright saturated palette: red, yellow, blue, pink, cyan, orange, lime. Use strong contrast and controlled combinations. Use exactly one precise accent from 【主色强调】.
Imagery: Use product cutouts, expressive objects, halftone cues, stickers, comic-like accents, repetition, or simple character energy. Scene direction: {{场景}}.
Texture / Material: Glossy product lighting, halftone dots, screenprint texture, paper cutouts, clean vector shapes.
Composition: Put the product or offer in the first read. Use clear source-supplied price and offer placement. If action copy is supplied, render it as plain promotional typography without button styling. Keep energy high but hierarchy simple. Use repetition to amplify, not clutter. Use layout {{版式，缺省 centered-hero}} from allowed set (centered-hero / poster-card). One dominant message, one focal point; reading order headline -> focal image -> supporting copy -> footer. Confident spacing; no overstuffed layout; no UI buttons/pills for the footer.

Avoid: Unreadable sale clutter, too many badges, fake discount text, distorted packaging, muddy colors, and generic cartoon chaos. Also avoid fake extra text, logos, QR codes, decorative clutter, malformed typography, generic AI-poster noise, watermarks, UI chrome.

Do not ask questions. Do not show analysis or alternatives. Output the single finished poster only.
```

## English summary
A bright high-impact commercial poster that feels energetic, immediate, product-forward, and easy to read. One Simplified-Chinese 9:16 poster; visible text only: headline, supporting line, footer「一张有戏 · 视觉习作」. Style lock: Pop Commercial. Layouts: centered-hero, poster-card.
