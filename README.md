# Paper Figure Layout Tool

online usage ：https://eliauk-hcy.github.io/figmerge-studio/

A browser-based tool for arranging scientific paper figure panels.

It is designed for biomedical and bioinformatics figures such as volcano plots, heatmaps, KM curves, WGCNA panels, single-cell UMAPs, qPCR/WB/IHC validation figures, graphical abstracts, and supplementary figures.

## Features

- Drag images into the page or select images from your computer
- Arrange panels automatically with grids such as `2x2`, `2x3`, `3x3`, `4x4`, and `5x5`
- Switch to free-drag mode and manually move each panel
- Alignment guide lines while dragging
- Resize selected panels
- Move panels forward/backward by layer
- Auto panel labels: `A`, `B`, `C`, `D`...
- Transparent label background
- Custom canvas width and height
- Download the final layout as PNG
- Runs entirely in the browser; no upload and no server required

## Usage

Open `index.html` in a browser.

For GitHub Pages:

1. Upload this folder to a GitHub repository.
2. Go to repository `Settings` -> `Pages`.
3. Set the source branch and root folder.
4. Open the published Pages URL.

## Notes

- Browser preview works best with `PNG`, `JPG`, `JPEG`, and `WEBP`.
- TIFF preview support depends on the browser. If a TIFF cannot be imported, convert it to PNG first.
- Folder selection depends on the browser's File System Access API. If unsupported, the tool falls back to normal browser download.

## Local Development

This is a static single-page app. No build step is required.

```text
index.html
README.md
.gitignore
```

