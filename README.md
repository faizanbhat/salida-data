# salida-data

Public data bundles + manifest consumed by the [Salida](https://github.com/faizanbhat/salida)
macOS travel app.

This repo is a thin distribution endpoint:

- `manifest.json` describes every available bundle (versions, sizes,
  SHA-256, source credits, license).
- Bundle SQLite files are attached as GitHub Release assets, one
  release per bundle-version pair (`data-core-YYYY-MM-DD`,
  `data-pois-YYYY-MM-DD`).

The app polls `manifest.json` to discover updates and downloads
assets directly from the release attached to the version it wants.

Source code, refresh scripts, and the pipeline that produces these
bundles live in the (private) Salida code repo — see the credit row
in the app's *About* panel for upstream data attribution.
