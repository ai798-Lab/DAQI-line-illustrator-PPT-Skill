# Prompt Template

Use this when generating raster art with an image model. Keep it short and restrictive. This is the primary production path for this skill.

## PPT Illustration

Use this for 16:9 slide visuals.

```text
Atmospheric 16:9 PPT illustration about [THEME], clean editorial line-art style, no readable text.
Place generous blank space for slide title and body copy, preferably on the left side.
One abstract human figure or hand drawn with loose thin black continuous contour lines, slightly surreal proportions, no facial detail.
The figure interacts with one symbolic prop: [PROP].
Add one large flat [YELLOW/RED] geometric accent shape behind or crossing the figure, plus three to six tiny colored dots or short marks.
Off-white background, asymmetrical slide composition, confident modern presentation mood.
Flat colors only: off-white background, black line, red #CB3339, yellow #F5D95F, tiny indigo #4A4AA0.
No readable text, no letters, no numbers, no logo, no UI, no chart, no dashboard, no infographic, no realistic scene, no gradients, no shadows, no texture, no SVG look, no vector-export look.
```

## WeChat Article Illustration

Use this for article covers or section images.

```text
Sparse editorial article illustration about [THEME], ignoring all typography.
One abstract human figure drawn with loose thin black continuous contour lines, slightly surreal proportions, no facial detail.
The figure interacts with one symbolic prop: [PROP].
Add one large flat [YELLOW/RED] geometric accent shape behind or crossing the figure, plus three to six tiny colored dots or short marks.
Clean article-cover composition, lots of off-white or pale mint negative space, asymmetrical, modern magazine mood.
Flat colors only: off-white or pale mint background, black line, red #CB3339, yellow #F5D95F, tiny indigo #4A4AA0.
No readable text, no letters, no numbers, no logo, no UI, no chart, no dashboard, no infographic, no realistic scene, no gradients, no shadows, no texture, no SVG look, no vector-export look.
```

## Fallback Only

Use SVG only when the user explicitly asks for vector/code output, when a deterministic structural sketch is needed before raster generation, or when no image-generation tool is available. SVG is not the default final output for this style.
