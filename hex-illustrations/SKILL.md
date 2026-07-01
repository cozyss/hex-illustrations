---
name: ian-solid-illustrations
description: "Generate hex-bodied Solid-style English article illustrations. Use for English articles, blog posts, Notion docs, essays, product thinking, workflows, methods, processes, structures, states, metaphors, viewpoints, illustration planning, shot lists, image generation, title removal, or image edits. Default style: hexagon-bodied Solid IP, pure white hand-drawn line art, sparse red/orange/blue English handwritten annotations, clean but strange explanatory visuals."
---

# Ian Solid Article Illustrations

## Core Purpose

Design and generate 16:9 horizontal body illustrations for English articles. The goal is not commercial illustration, a PPT infographic, or cute character art. The goal is to understand the cognitive anchor in the text, then turn one judgment, process, structure, state, or metaphor into a memorable hand-drawn explanatory image.

The recurring visual IP is Solid: a small solid-black creature with a **hexagon body**, white dot eyes, thin legs, and a blank serious expression. Same operator energy as the original Solid family — only the silhouette is hexagonal. Solid is not a mascot, sticker, or corner decoration. Solid should be the deadpan worker seriously participating in the absurd system on the page.

## Read References As Needed

Do not load everything by default. Read the relevant files for the task:

- `references/style-dna.md`: visual DNA, colors, annotation rules, and prohibitions.
- `references/solid-ip.md`: Solid character design, personality, action library, and constraints.
- `references/composition-patterns.md`: structure types, metaphor invention method, and anti-copying rules.
- `references/prompt-template.md`: single-image generation prompt template.
- `references/qa-checklist.md`: post-generation QA and iteration rules.
- `assets/examples/`: low-frequency visual calibration only. Do not copy the sample compositions, objects, or labels.

## Workflow

### 1. Digest the Source Text

Read the user's article, Markdown, Notion page, screenshot, or topic. Extract:

- the central argument
- the paragraphs that create a cognitive turn
- the parts worth explaining visually
- the parts that should remain text-only

Do not distribute illustrations evenly. Prioritize cognitive anchors such as a core claim, two breakpoints, input-output loop, sorting moment, before/after contrast, one input with many uses, handoff path, common failure mode, or change in operator state.

### 2. Plan the Illustration Strategy

If the user asks to analyze, plan, or decide where to illustrate, provide a shot list first. For each image include:

- placement after which paragraph or section
- image theme
- core meaning
- structure type
- what Solid is doing
- suggested visual elements
- suggested English annotation labels

Default to 4-8 images. Use 1-3 for short pieces. Even for long articles, avoid exceeding 9 unless the user explicitly asks. Make the illustrations selective, not a picture book version of the text.

### 3. Generate Single Images

If the user explicitly asks to generate, output, make, or create images, do not wait for confirmation. Use the built-in `image_gen` tool and generate each image separately. Do not combine multiple images into one grid.

Each image should express one core structure. The prompt must include:

- 16:9 horizontal English article illustration
- pure white background
- black hand-drawn line art
- sparse red/orange/blue English handwritten annotations
- lots of white space
- Solid as the core action subject
- no PPT, commercial illustration, childish cute style, complex architecture diagram, or top-left category title

Do not copy previous examples. Examples calibrate line density, whitespace, color restraint, and Solid's level of participation. Do not reuse known compositions such as conveyor breakpoints, Solid pulling lines, material fish, handoff toolbox stamps, or common-pit paths unless the user explicitly asks to replicate a specific image. Invent a fresh, low-tech, strange-but-legible metaphor from the current text every time.

### 4. Check And Iterate

After generation, check `references/qa-checklist.md`. Regenerate or edit first if:

- Solid is decorative
- the canvas is too full
- the image feels like a flowchart or PPT slide
- the English labels are too many, too long, misspelled, or unreadable
- a top-left title appears, such as "Workflow", "System Map", "Common Mistakes", or "Roadmap"
- the style is too cute, childish, stiff, or commercial
- the background is not clean white

### 5. Save And Deliver

If the user is working inside a workspace, save final PNGs to:

```text
assets/<article-slug>-illustrations/
```

Name files in order:

```text
01-topic-name.png
02-topic-name.png
```

Keep original generated files. Do not overwrite existing assets unless the user explicitly asks.

## Response Style

Planning output should be short and precise. After generation, include:

- how many images were generated
- what each image is for
- saved paths
- which images are strongest and which are optional

Do not write long visual theory. Let the images do the work.
