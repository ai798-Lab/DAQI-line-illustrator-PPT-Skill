---
name: poster-line-illustrator
description: Generate raster, image-model illustrations for polished PPT slides and WeChat articles using thin black continuous contour lines, large flat red/yellow accent shapes, tiny colored dots, and generous off-white space. Use when the user asks for 大气的 PPT 配图、PPT配图、PPT插画配图、微信文章配图、公众号配图, or matching red/yellow minimalist line-art illustrations. Ignore typography in references unless the user explicitly asks for full slide mockups with text.
---

# 大气的 PPT 配图

## Chinese Triggers

Use this skill when the user says phrases like:

- 大气的 PPT 配图
- 大气PPT配图
- PPT配图
- PPT插画配图
- 微信文章配图
- 公众号配图
- 海报线描插画
- 线描海报风格
- 手绘线条海报
- 红黄线描插画
- 极简线描人物插画
- 按那组三张海报风格画图
- 用那个红黄线条插画风格生成
- 用之前 OPC 那张图的风格生成
- 按这套 PPT 风格生成配图
- 用这个大气线描风格做配图

## Workflow

1. Read the user's theme, article section, or visual brief.
2. Identify the output context: PPT slide illustration, WeChat article cover, article section illustration, or poster/cover.
3. Read `references/style-dna.md`, `references/visual-grammar.md`, `references/theme-translation.md`, `references/prompt-template.md`, and `references/qa-checklist.md`.
4. Inspect `assets/examples/` for visual density, line behavior, accent scale, and composition. Inspect `examples/ppt-showcase/` when the user asks for PPT use. Ignore readable text unless the user explicitly requests a full slide mockup.
5. Convert the theme into one clear visual metaphor: one line-drawn figure or hand, one prop, and one flat red/yellow accent shape.
6. Produce a raster illustration with the available image-generation model by default. Use the prompt template to constrain the model toward sparse editorial line art.
7. Apply the QA checklist. If the result looks like a business infographic, UI, logo, or literal scene, reduce it back to a sparse poster illustration.

## Output Rules

- For PPT, default to a 16:9 landscape canvas with enough negative space for title and body copy.
- For WeChat article covers, use 16:9 or 4:3 unless the user asks for another ratio.
- For article section illustrations, use 3:2 or 1:1 with one idea per image.
- For posters or covers, use portrait 3:4 or 2:3.
- Use no readable text unless the user explicitly asks for a full slide mockup with title/copy.
- Keep the illustration sparse: one dominant contour figure, one core prop, two large accent shapes maximum, and three to six tiny dots or short marks.
- Use image generation as the primary production method. Do not substitute SVG/HTML/CSS for the final image unless the user explicitly asks for vector/code output or the image model is unavailable.
- If the user requests Imagen 2.0 and an Imagen 2.0-capable tool is available, use that model. If not, use the available image generation tool and state the limitation plainly.

## Assets

Reference images live in `assets/examples/`:

- `poster-line-01.png`
- `poster-line-02.png`
- `poster-line-03.png`

Use them for line rhythm, color placement, and poster spacing. Do not copy their text, exact figures, exact layouts, or placeholder copy.

PPT showcase examples live in `examples/ppt-showcase/`:

- `ppt-cover.png`
- `ppt-guidance.png`
- `ppt-framework.png`

Use them for 16:9 composition, white-space placement, and slide-friendly scale.
