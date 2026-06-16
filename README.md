# signal-brand-assets

Public asset library for the Signal AI brand system. Used by the `signal-brand` Claude skill.

## Structure

```
signal-brand-assets/
├── logos/       ← Signal wordmark variants (full-colour, red, white, mono)
├── icons/       ← Product and feature icons
├── geometry/    ← Geometric background shapes and gradient overlays
└── textures/    ← Decorative image textures
```

## Usage

Reference assets directly via raw GitHub URL:

```
https://raw.githubusercontent.com/signal-ai/signal-brand-assets/main/logos/Signal-Logo-white.png
https://raw.githubusercontent.com/signal-ai/signal-brand-assets/main/icons/Dashboard.png
https://raw.githubusercontent.com/signal-ai/signal-brand-assets/main/geometry/Geometry-filled-large.png
https://raw.githubusercontent.com/signal-ai/signal-brand-assets/main/textures/Image-texture-1.jpg
```

## Updating assets

Replace the file in the relevant folder and commit. The URL structure stays the same so no updates to `signal-brand` SKILL.md are needed unless you add or rename files.
