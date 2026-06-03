---
name: ian-xiaohei-illustrations
description: Generate Ian-style Chinese article inline illustrations. Use when the user asks to generate "absurd", "Xiaohei", "hand-drawn", "inline illustration", "article illustration", "illustration suggestion", "shot list", "remove title/edit image" for Chinese articles, posts, blogs, Notion documents, workflow docs, methodologies, flows, structures, states, metaphors, or ideas; default visual style uses the Xiaohei IP, pure white hand-drawn art, sparse red/orange/blue annotations, clean and creative.
---

# Ian Xiaohei Absurd Inline Illustrations

## Core Purpose

Design and generate 16:9 landscape inline illustrations for Chinese articles. The goal is not commercial illustrations, PPT infographics, or cute cartoons — it's turning key judgments, flows, structures, states, or metaphors from the article into clean, absurd, creative, readable-but-not-instructional hand-drawn explanation images.

The default visual IP is "Xiaohei": solid black, white dot eyes, thin legs, blank expression, seriously doing something absurd but plausible. Xiaohei must participate in the core action of the image — not just stand beside the diagram as decoration.

## Read These References

Load as needed — do not load all at once:

- `references/style-dna.md`: Style DNA, colors, text, prohibitions.
- `references/xiaohei-ip.md`: Xiaohei IP appearance, personality, action library, prohibitions.
- `references/composition-patterns.md`: Structure types, original metaphor methods, anti-copy rules.
- `references/prompt-template.md`: Single-image generation prompt template.
- `references/qa-checklist.md`: Post-generation check and iteration rules.
- `assets/examples/`: Low-frequency visual calibration only — do not include in default generation path. Do not copy compositions, objects, or annotations from these examples.

## Workflow

### 1. Digest the Article

First read the user's article, link, Notion page, Markdown file, or screenshot content. Extract:

- What the core ideas are
- Which paragraphs carry cognitive turning points
- Which content is suitable for image explanation
- Which parts are text-only and don't need images

Don't illustrate everything evenly. Prioritize "cognitive anchors" such as: core judgments, two breakpoints, input/output loops, branching, before/after contrasts, one-thing-many-uses, handoff paths, common pitfalls, and character state changes.

### 2. Output Illustration Strategy First

If the user only says "analyze how to illustrate / think about which parts need images", give a shot list first. For each image specify:

- Which paragraph it follows
- Image theme
- Core meaning
- Structure type
- What Xiaohei is doing in the image
- Suggested elements
- Suggested Chinese annotation words

Default 4–8 images. For short articles, 1–3; for long articles, don't exceed 9. Enough is enough — avoid turning the article body into a picture book.

### 3. Single Image Generation

If the user explicitly says "generate / output / make / create images", don't stop to ask for confirmation — use the built-in `image_gen` to generate each image individually. Do not combine multiple images into one.

Each image explains only one core structure. Prompts must include:

- 16:9 landscape Chinese article illustration
- Pure white background
- Black hand-drawn line art
- Sparse red/orange/blue Chinese handwritten annotations
- Lots of blank space
- Xiaohei as the core action subject
- Prohibit PPT, commercial illustrations, cute/childish, complex architecture, top-left type titles

Do not copy past examples. Examples only provide style density and Xiaohei's involvement mode — do not directly reuse these existing compositions: conveyor belt breakpoints, Xiaohei pulling judgment lever inside content machine, Xiaohei becoming a funnel sorting traffic/trust/conversion, Xiaohei slicing the material fish, Xiaohei leading the handoff path, Xiaohei pulling three-layer information sources, three Xiaoheis holding megaphone/building bridge/opening door, Xiaohei stamping the handoff copy toolbox, Xiaohei holding sign watching common pitfalls path — unless the user explicitly asks to recreate a specific image. Each time, reinvent a strange-but-plausible metaphor fresh from the current article.

### 4. Review and Iterate

After generation, check `references/qa-checklist.md`. Regenerate or locally edit if:

- Xiaohei is just decorative
- Canvas is too full
- Looks like a flowchart/PPT
- Too much Chinese text or severe typos
- Top-left shows "Common Pitfalls / Flowchart / System Architecture" title
- Art style is too cute, childish, or rigid
- Background is not a clean white

### 5. Save and Deliver

If the user is working in a workspace, copy final images to:

```text
assets/<article-slug>-illustrations/
```

Name sequentially:

```text
01-topic-name.png
02-topic-name.png
```

Keep original generated files — do not overwrite existing assets unless the user explicitly requests replacement.

## Output Format

Pre-generation strategy output should be short and precise. Post-generation delivery should include:

- How many images were generated
- Purpose of each image
- Save path
- Which images are most stable, which are optional

Do not explain style theory at length — let the images speak.
