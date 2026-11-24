# ArtVector

**ArtVector** is a pocket vector illustration and graphic design studio built for Android smartphones, developed by **Igoy Creative Lab.**

Create crisp, resolution-independent vector artwork anywhere directly from your phone, whether you are designing logos, icons, social media layouts, badges, or illustrations.

## Key Capabilities

- **Scalable Vector Shapes:** Create and customize rectangles, rounded rectangles, ellipses, triangles, polygons, stars, arrows, and lines with live parameter controls.
- **Bezier Pen & Node Editing:** Draw custom vector curves with a smartphone touch-offset precision crosshair, convert shapes to editable curves, and adjust anchor points and tangent handles directly on the canvas.
- **Freehand Vector Pencil:** Sketch naturally with automatic curve smoothing and optional path auto-closing.
- **Transform, Snap & Layout:** Smooth pinch-zoom and pan canvas, rotated selection handles, smart alignment guides, multi-select, grouping, alignment, distribution, and layer ordering.
- **Fills, Gradients & Strokes:** Independent fill (solid, linear gradient, radial gradient) and stroke controls (decimal width, caps, joins, alignment, dash patterns), opacity, and blend modes.
- **Export & Project Management:** Export artwork to SVG, PNG, JPEG, and WebP (1x to 4x), organize projects in the built-in gallery with presets, recover items from 30-day Trash, and back up your library locally.

## Download & Install

Official Android builds are published on the [Releases](https://github.com/ogibinedi/artvector-releases/releases) page.

| File | Recommended For |
| --- | --- |
| `artvector-<version>-android-arm64.apk` | Most modern Android smartphones (64-bit ARM, Android 8.0+) |
| `artvector-<version>-android-legacy-armeabi-v7a.apk` | Older 32-bit ARM Android devices |
| `SHA256SUMS.txt` | SHA-256 checksums to verify downloaded APKs |

### Verifying Checksums

```bash
sha256sum -c SHA256SUMS.txt --ignore-missing
```

### In-App Updates

ArtVector includes a built-in **Software Updates** checker (under **About -> Software Updates**) that checks this repository directly and verifies APK SHA-256 checksums before installation. Enable **Include pre-releases** if you want to test Release Candidate (`-rc`) builds early.

## About This Repository

This public repository serves strictly as the official binary release distribution channel for **ArtVector** by **Igoy Creative Lab.**
