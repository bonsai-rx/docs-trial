# docs-trial

This minimal GitHub Pages template shows example styling and layouts to embed documentation for Bonsai workflow snippets directly in markdown using Jekyll and javascript.

## How to use

For each documented workflow snippet to include in the docs, include both the workflow (`.bonsai`) file and its vector preview (`.svg`) in the folder `assets\workflows`.

The workflow and SVG file for each snippet should have the same name for the Liquid templates to work.

For direct download use:

`[![example](assets\workflows\example.svg)](assets\workflows\example.bonsai)`

For direct copy use:

`{% include workflow.html src="example" %}`