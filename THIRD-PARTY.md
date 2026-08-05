# Third-party materials

## 1. Ground-truth Kikuchi patterns — `app/data/rx/tiles/`

**EBSD patterns from a third-party dataset.** These are not ours and are
not covered by `LICENSE`; they are redistributed here under the source dataset's own
terms, in derived form (cropped to the showcase ROI, downsampled, and re-encoded as WebP
tiles for streaming).

| | |
|---|---|
| Source | Calvat, Anjaria, Wang, Vecchio & Stinville |
| Repository | Dryad, [`10.5061/dryad.zcrjdfnr9`](https://doi.org/10.5061/dryad.zcrjdfnr9) |
| License | CC0 1.0 Universal (Public Domain Dedication) |

Please cite the original dataset if you build on these patterns.

Only `app/data/rx/tiles` come from this dataset; other `app/data` are our own. 

## 2. Colormap lookup tables — `web/src/core/colormap.ts`

The file embeds 256-entry RGB LUTs as base64. Their provenance:

- **viridis, inferno, magma** — designed by Nathaniel J. Smith, Stéfan van der Walt, and
  (for inferno/magma) Eric Firing, and released to the public domain under **CC0 1.0
  Universal**. No conditions attach; the credit here is courtesy.
- **spectral_r** — the reverse of matplotlib's `Spectral`, which is a **ColorBrewer**
  scheme by Cynthia Brewer, Mark Harrower, and The Pennsylvania State University
  ([colorbrewer2.org](https://colorbrewer2.org)). ColorBrewer schemes are distributed under
  the *Apache-Style Software License for ColorBrewer Color Schemes, Version 1.1*, which
  permits redistribution **with attribution** — hence this entry.
- **gray** — a linear 0–255 ramp. Not authored by anyone; listed only for completeness.

The LUT *values* are reproduced from matplotlib's tables.
