# Artifex identity

A two-part A/chisel silhouette: a forged apex, open counter and a decisive cross-cut. Mineral green
on graphite gives the standalone identity its own character.

Independent Artifex identity. Keep the primary public lockup free of company endorsements.

## Palette

| Role           | Value     |
| :------------- | :-------- |
| Project accent | `#B9EE83` |
| Graphite       | `#0B0D10` |
| Surface        | `#14191F` |
| Primary text   | `#F1F3F5` |
| Muted text     | `#9CA6B1` |

The project accent differentiates navigation; it is not a severity or live-status colour.

## Assets

`assets/brand/` holds the source-controlled SVGs. `mark.svg` is the transparent colour mark;
`mark-mono-dark.svg` and `mark-mono-light.svg` are monochrome variants. `icon.svg` and
`icon-light.svg` are square app tiles. `wordmark-*.svg`, `lockup-*.svg`, `banner-*.svg` and
`workflow-*.svg` provide full presentation assets. `icon-micro.svg` is simplified for 16 to 24 px
use.

`workflow-mobile-*.svg` stacks the four steps for narrow screens. The README selects these at widths
up to 600 pixels.

Dark suffixes are for dark surfaces; light suffixes are for light surfaces. Banners and workflows
include their own background. Logos, wordmarks and marks are transparent.

The SVG assets include a 1280 × 640 sharing image. Export raster sizes from these vectors when
needed; keep proportions and transparent backgrounds intact.

## Construction and use

Use the square mark alone below 180 pixels of available horizontal space. At 16 to 24 pixels use the
simplified micro mark, not the full wordmark lockup. Keep clear space of at least 16% of the symbol
width around a free-standing symbol. Do not stretch, rotate or independently skew the symbol or
lettering.

Typography uses Inter Display for project names and body copy, with DejaVu Sans Mono for technical
labels. SVG lettering is outlined so no fonts need to load. Font files are not included. Letterforms
remain vector shapes; the metadata in `brand.json` preserves editable wording and colour values.

Diagrams in the branding are illustrative identity artwork, never telemetry, simulation evidence,
performance results or implementation-status proof. Keep any status wording consistent with the
current README.

## Accessibility

Keep the text title, description and operational warnings in the README, not only inside the banner.
Every SVG has a title and description; every README image has descriptive alternative text. Pair
colour with the project name or a textual status. The static designs contain no animation, tracking
or externally loaded assets.

## Source and scope

The independent Artifex identity is supplied by Godfrey Engineering and distributed under the
repository's MIT licence. No internal implementation or operational configuration is included. See
[project scope](scope.md) for the planned public toolbox.
