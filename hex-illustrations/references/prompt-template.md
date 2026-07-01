# Image Generation Prompt Template

Generate each image separately. Replace variables from the source text. Do not combine multiple images into one grid.

```text
Generate one standalone 16:9 horizontal English article illustration.

Visual DNA:
Pure white background. Minimalist black hand-drawn line art. Slightly wobbly pen lines. Lots of empty white space. Visual-first and annotation-light: the metaphor, objects, Solid's action, and composition should carry most of the meaning, while a few essential anchor labels can name important abstractions. Clean absurd product-sketch feeling. No gradients, no shadows, no paper texture, no complex background, no commercial vector style, no PPT infographic look, no cute mascot poster, no children's illustration, no realistic UI.

Recurring IP character required:
Solid, a small solid-black absurd creature with a simple hexagon body (six-sided hand-drawn black block), white dot eyes on the hexagon face, tiny thin legs, blank serious expression, slightly wobbly uneven pen-line hexagon outline — not a perfect vector shape, not a round blob or bean. Solid must perform the core conceptual action, not decorate the scene. Make Solid serious, deadpan, and slightly bizarre, not cute.

Theme:
{article illustration theme}

User-supplied visual direction, if any:
{rough scene idea, metaphor, sketch description, desired final look, and any must-keep details; otherwise none}

Refinement intent:
{how the rough visual direction was simplified, sharpened, or changed to better express the article's core idea while preserving the strongest user insight}

Structure type:
{Workflow / System Slice / Before-After / Operator State / Concept Metaphor / Method Layers / Map-Route / Mini Comic}

Core idea:
{the one core idea this image should express}

Composition:
{specific scene: where Solid is, what Solid is doing, what the main object is, and how information or motion flows}

Suggested elements:
{element 1} / {element 2} / {element 3} / {element 4}

How it reads without annotations:
{explain how the viewer understands the idea from the metaphor, objects, action, and composition alone}

Annotation policy:
Do not make the image text-free by default. Use 1-3 short anchor labels when they clarify an important abstraction, missing capability, or central phrase. Prefer labels that name the conceptual contrast, not labels that explain every object, box, node, or arrow.

English handwritten labels:
{none, or 1-3 essential anchor labels}

Color use:
Black for main line art and Solid. Orange for main flow/path/arrows. Red only for key warnings/problems/results. Blue only for secondary notes or feedback/system state.

Constraints:
One image explains only one core structure. Keep the main subject around 40%-60% of the canvas. Preserve at least 35% blank white space. Use at most 3 short handwritten English labels, ideally 1-3 words each, when they sharpen the core idea. Do not explain the idea in sentences. Do not label every object, arrow, node, or state. Do not write a generic title in the top-left corner. Do not write the structure type on the image. Do not make it a formal diagram, course slide, or dense explainer. Do not copy prior examples or reuse known case compositions unless explicitly requested; invent a fresh visual metaphor for this specific article. It should be clear but not instructional, interesting but not childish, strange but clean.
```

## Image Editing Prompts

Remove a top-left title:

```text
Edit the provided image. Remove only the handwritten title "{text to remove}" and its underline from the top-left corner. Fill that area with the same clean white background, matching the surrounding blank paper. Preserve everything else exactly: characters, labels, paths, line style, composition, aspect ratio, and image quality. Do not add any new text or objects.
```

Make Solid more involved:

```text
Regenerate this illustration with the same core meaning and simple layout, but make Solid more central to the conceptual action. Solid should be doing the strange work that explains the idea, not standing beside the diagram. Keep it clean, sparse, hand-drawn, and not cute.
```
