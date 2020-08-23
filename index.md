---
layout: docpage
---

## Workflow Docs

Examples for a Bonsai workflow documentation system.

### Direct Download

The simplest case. Direct download of a bonsai workflow with an SVG preview:

[![segmentation](assets\workflows\segmentation.svg)](assets\workflows\segmentation.bonsai)

### Direct Copy

Copy to clipboard on click:

{% include workflow.html src="segmentation" %}

This basically styles the workflow as a table with a button on the top-right corner that copies the workflow contents directly to the clipboard:

```html
{% include workflow.html src="segmentation" %}
```