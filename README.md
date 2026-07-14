# signal-brand-assets

**Version:** 4.0.0

Public asset library for the Signal AI brand system. Used by the `signal-brand` Claude skill.

This repo's version number is kept in step with [`signal-ai/claude-plugins/signal-brand`](https://github.com/signal-ai/claude-plugins/tree/main/signal-brand) — bump both together whenever either changes, so it's always clear which asset set a given skill version was built against.

## Structure

```
signal-brand-assets/
├── logos/       ← Signal wordmark variants (full-colour, red, white, mono)
├── icons/       ← Product and feature icons
├── geometry/    ← Geometric background shapes and gradient overlays
└── decorative/  ← Decorative image textures
```

## Usage

Reference assets directly via raw GitHub URL:

```
https://raw.githubusercontent.com/signal-ai/signal-brand-assets/main/logos/Signal-Logo-white.png
https://raw.githubusercontent.com/signal-ai/signal-brand-assets/main/icons/Dashboard.png
https://raw.githubusercontent.com/signal-ai/signal-brand-assets/main/geometry/Geometry-filled-large.png
https://raw.githubusercontent.com/signal-ai/signal-brand-assets/main/decorative/Image-texture-1.jpg
```

## Updating assets

Replace the file in the relevant folder and commit. The URL structure stays the same so no updates to `signal-brand` SKILL.md are needed unless you add or rename files.

## Version history

| Version | Notes |
|---|---|
| 4.0.0 | Version number aligned with `signal-brand` skill v4.0.0 going forward. No asset changes in this bump — captures the Polygon-large/Polygon-small additions already shipped under v3.0.0. |
| 3.0.0 | Added `Geometry-outlined-large.png` update; added `Polygon-large.png` and `Polygon-small.png` |
| 2.5.0 | Added `Quote-marks-top` PNG variants and SVG fallback; set PNG as default |
| 2.4.0 | Initial packaged release; renamed `textures/` to `decorative/`, added `manifest.json` |
