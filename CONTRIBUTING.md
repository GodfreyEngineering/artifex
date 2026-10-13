# Contributing

Artifex is a planning-stage project. Useful contributions describe a concrete workflow problem,
propose a small design change or improve the documentation and identity assets.

Open an issue before a substantial implementation. Include the expected user behaviour, proposed
scope and a way to verify the result. The [roadmap](ROADMAP.md) defines the intended first slice;
its interfaces and toolchain still need a reviewed design.

## Working on this repository

Clone the repository and create a branch for your change. The current tree contains Markdown,
configuration and static SVG artwork, with no runtime dependencies, application build or test suite.

For documentation changes, check local links and preserve the distinction between planned and
implemented behaviour. For artwork, inspect light and dark variants at desktop and narrow widths.
Keep SVGs self-contained, with accessible titles and descriptions and no scripts or externally
loaded resources.

Use British English. Keep setup and usage instructions in one authoritative place. Record notable
changes under Unreleased in [CHANGELOG.md](CHANGELOG.md).

## Public boundary

Use synthetic examples. Do not submit credentials, private account details, customer material or
internal operational records. A component proposed for generalisation needs a dependency and licence
review as well as tests that run without private infrastructure.

Contributions are made under the repository's [MIT licence](LICENSE). Preserve notices required by
third-party material.
