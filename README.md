# Robomotion — Logo Assets

Press kit and brand-guide assets for the Robomotion wordmark, derived from the
original vector master. Two colourways: **white** for black/dark backgrounds and
**black** for white/light backgrounds. The orange accent is **identical in both**.

---

## Files

| Folder | File | Use |
|---|---|---|
| `svg/` | `robomotion-logo-white.svg` | Vector master — dark backgrounds |
| `svg/` | `robomotion-logo-black.svg` | Vector master — light backgrounds |
| `pdf/` | `robomotion-logo-white.pdf` | Vector, print/press — dark backgrounds |
| `pdf/` | `robomotion-logo-black.pdf` | Vector, print/press — light backgrounds |
| `png/` | `robomotion-logo-{white,black}-{500,1000,2000,4000}w.png` | Transparent raster, 300 dpi tagged |
| `preview/` | `robomotion-logo-white-on-black.png` | Reference render (background baked in) |
| `preview/` | `robomotion-logo-black-on-white.png` | Reference render (background baked in) |

**Send SVG or PDF to press and to any designer.** PNGs are for slides, web and
anywhere vector is not accepted. All PNGs have a transparent background — the
`white` PNG will look blank in a file browser on a white page; that is expected.
The PDFs are true vector (no embedded raster) and single-page.

## Colours

| Role | HEX | RGB | CMYK (FOGRA39L coated) |
|---|---|---|---|
| Accent orange | `#FA6400` | 250, 100, 0 | 0 / 71 / 100 / 0 |
| Ink (light backgrounds) | `#000000` | 0, 0, 0 | 0 / 0 / 0 / 100 |
| Ink (dark backgrounds) | `#FFFFFF` | 255, 255, 255 | paper / knockout |

sRGB HEX is authoritative. The CMYK figure is a profiled conversion against
FOGRA39L (ISO Coated v2), relative colorimetric — **confirm it against your
printer's own profile before a run**, and ask for a proof. An uncalibrated
conversion gives 0/60/100/2, which prints noticeably duller; do not use it.
No Pantone match is specified here — match to a physical guide, do not trust a
screen conversion.

## Geometry

- Master artboard: **573.3 × 106.5** units, cropped tight to the artwork.
- Aspect ratio: **5.3831 : 1** — `height = width ÷ 5.3831`.
- Baseline sits at the foot of the letterforms; the orange accent hangs below it
  and is part of the lockup. Never separate, recolour, or reposition it.

## Clear space

Keep clear on all four sides at least **half the cap height of the R**
(37 units at master scale = **0.35 × the logo's total height**). Nothing —
type, rules, image edges, or other logos — enters that zone.

## Minimum size

| Medium | Minimum | Recommended |
|---|---|---|
| Screen | 120 px wide | 160 px wide or more |
| Print | 25 mm wide | 30 mm wide or more |

Below 120 px the orange accent thins to near-invisibility and the wordmark
starts to fill in.

## Don'ts

- Do not recolour the wordmark to anything but `#000000` or `#FFFFFF`.
- Do not recolour, remove, or re-angle the orange accent.
- Do not stretch, condense, rotate, outline, or add effects (shadow, glow, bevel).
- Do not place the white version on a light background or the black version on a
  dark one — pick the colourway by contrast, not by habit.
- Do not re-typeset the wordmark; it is drawn as outlines, not live text.

## Note on the source file

The original SVG contained a second, mirrored accent shape at the top of the
canvas set to **2% opacity** (`#D8D8D8`) — invisible on screen and a liability in
print, where it can surface as a faint 2% tint patch or a banding artifact. It has
been removed from these masters. Everything else is geometrically identical to
the original, verified pixel-for-pixel at 4× scale. Removing it also freed 26
units of dead space at the top of the canvas, so these masters are cropped tight
to the artwork — set your own margins via the clear-space rule above.
