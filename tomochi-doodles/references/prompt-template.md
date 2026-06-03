# Image Generation Prompt Template

Generate each image individually. Replace template variables based on article content — do not combine multiple images into one.

```text
Generate one standalone 16:9 horizontal article illustration.

Visual DNA:
Pure white background. Minimalist black hand-drawn line art. Slightly wobbly pen lines. Lots of empty white space. Sparse red/orange/blue handwritten annotations in English or Bahasa Indonesia. Clean absurd product-sketch feeling. No gradients, no shadows, no paper texture, no complex background, no commercial vector style, no PPT infographic look, no cute mascot poster, no children's illustration, no realistic UI.

Recurring IP character required:
Tomochi, a small soft-saggy blob creature — shaped like Gudetama (the lazy egg): slightly deflated, droopy, gravity-affected oval lump. Not round and perky — low, flat, and sagging. Dusty pink color (muted warm rose, like faded blush — not pastel, not vibrant). Half-lidded droopy eyes, permanently sleepy-confused expression, like it just woke up and doesn't fully understand the situation but is doing the task anyway. Short limp arms that extend reluctantly. Body sags more under weight, stretches heavily when pulled, flattens when squished. Same dusty pink, same droopy eyes, same low-energy vibe in all poses. Tomochi must perform the core conceptual action, not decorate the scene. Not cute-perky, not panicked — sleepy, confused, and quietly persistent.

Theme:
{article illustration theme}

Structure type:
{structure type: Workflow / System Partial / Before-After Contrast / Character State / Concept Metaphor / Method Layers / Map Route / Mini Comic Panels}

Core idea:
{the core meaning this image should express}

Composition:
{specific scene: where is Tomochi, what is Tomochi doing, what are the main objects, how does information flow}

Suggested elements:
{element 1} / {element 2} / {element 3} / {element 4}

Handwritten labels (English or Bahasa Indonesia):
{label 1} / {label 2} / {label 3} / {label 4} / {optional label 5}

Color use:
Black for main line art. Pink for Tomochi's body. Orange for main flow/path/arrows. Red only for key warnings/problems/results. Blue only for secondary notes or feedback/system state.

Constraints:
One image explains only one core structure. Keep the main subject around 40%-60% of the canvas. Preserve at least 35% blank white space. Use at most 5-8 short handwritten labels. Do not write a title in the top-left corner. Do not write the structure type on the image. Do not make it a formal diagram, course slide, or dense explainer. Do not copy prior examples or reuse known case compositions unless explicitly requested; invent a fresh visual metaphor for this specific article. It should be clear but not instructional, interesting but not childish, strange but clean.
```

## Image Editing Prompts

Remove a top-left title:

```text
Edit the provided image. Remove only the handwritten title "{text to remove}" and its underline from the top-left corner. Fill that area with the same clean white background, matching the surrounding blank paper. Preserve everything else exactly: characters, labels, paths, line style, composition, aspect ratio, and image quality. Do not add any new text or objects.
```

Enhance Tomochi's involvement:

```text
Regenerate with same core meaning and layout, but make Tomochi the action subject, not decoration. Tomochi's saggy body should morph to fit — drooping under weight, stretching heavily when pulled, squishing flat when stuck. Keep it clean, sparse, hand-drawn. Tomochi looks sleepy and confused but is doing the work anyway. Not cute-perky, not panicked.
```
