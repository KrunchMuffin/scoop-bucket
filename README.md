# DAB Worx Scoop bucket

[![Tests](https://github.com/KrunchMuffin/scoop-bucket/actions/workflows/ci.yml/badge.svg)](https://github.com/KrunchMuffin/scoop-bucket/actions/workflows/ci.yml) [![Excavator](https://github.com/KrunchMuffin/scoop-bucket/actions/workflows/excavator.yml/badge.svg)](https://github.com/KrunchMuffin/scoop-bucket/actions/workflows/excavator.yml)

A [Scoop](https://scoop.sh) bucket for apps by [DAB Worx Inc.](https://dabworx.com)

## Install

```pwsh
scoop bucket add dabworx https://github.com/KrunchMuffin/scoop-bucket
scoop install dabworx/simple-markdown-viewer
```

Update later with `scoop update simple-markdown-viewer`.

## Apps

| App | Description |
|---|---|
| [simple-markdown-viewer](bucket/simple-markdown-viewer.json) | [Simple Markdown Viewer](https://smv.dabworx.com/): a lightweight markdown and Mermaid viewer and editor with live preview, tabs, KaTeX math and dark mode |

The manifests update themselves: the Excavator workflow checks GitHub releases every
few hours and commits new versions and hashes.

`simple-markdown-viewer` was called `simplemarkdownviewer` until 1.7.1. If you installed it under the old name, switch with `scoop uninstall simplemarkdownviewer` then `scoop install dabworx/simple-markdown-viewer`; your settings are kept.
