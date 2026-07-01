# QA Checklist

## Must Pass

- 16:9 horizontal image.
- Clean pure white background.
- Solid is present with a readable hexagon body silhouette.
- Solid performs the core action instead of decorating the scene.
- The image invents a new metaphor for the current article instead of copying an old example composition.
- The image is strange, inventive, and memorable.
- The layout is clean; the subject uses no more than about 60% of the canvas.
- One image expresses one core structure.
- The image can be understood primarily from the metaphor, objects, Solid's action, and composition.
- English annotations are limited to essential anchor labels; they are sparse, short, readable, and spelled correctly.
- Orange is used only for the main path, flow, or arrows.
- Red is used only for emphasis, problems, warnings, or results.
- Blue is used only for secondary notes, feedback, or system state.

## Failure Signals

Regenerate or edit if any of these appear:

- Top-left category title such as "Workflow", "Common Mistakes", "System Map", or "Roadmap".
- Solid feels like a mascot, sticker, or cute cartoon.
- Solid's body reverts to a round blob, bean, or non-hexagon shape (unless the user requested another shape variant).
- The image looks like a PPT slide, course page, formal diagram, or standard infographic.
- Too many elements, arrows, or nodes.
- Text becomes paragraph-like explanation.
- Labels explain everything instead of anchoring the visual metaphor.
- Background has paper texture, shadows, gradients, beige tone, or noise.
- Realistic UI screenshot or tech-dashboard aesthetic.
- English labels are misspelled, too long, or unreadable.
- The image is stiff and lacks an absurd visual metaphor.
- The composition is too similar to `assets/examples/`.

## Iteration Methods

- Too ordinary: make Solid the action subject and add a strange but legible metaphor.
- Too annotation-heavy: keep only the 1-3 labels that anchor the core contrast, then strengthen the metaphor, object choice, and Solid's action.
- Too complex: remove nodes and keep one clear visual action with 0-3 necessary labels.
- Too cute: emphasize deadpan, blank serious expression, not cute, not mascot.
- Too PPT-like: remove titles, grids, formal boxes, and excessive arrows; turn it into a hand-drawn scene.
- Too similar to old examples: keep the meaning but change the main object and Solid's action.
- Bad text: edit locally if minor; regenerate with fewer labels if labels are badly broken.

## Delivery Standard

A strong image should make the reader think "that's odd" first, then understand the structure within one second.

Before accepting an image, ask whether it would still mostly make sense if all labels were removed. If not, improve the visual metaphor. Then keep only the few labels that name the core abstraction or missing capability.

If the first impression is a tutorial slide instead of a strange product sketch on white paper, it fails.
