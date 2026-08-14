# SciPrep for macOS

SciPrep is an unofficial independent study app for macOS 26.0 or later. It is not affiliated with, endorsed by, or produced by AAMC, ACER, the MCAT, or GAMSAT. Its questions are independent exam-style practice materials, not official exam questions.

## Install

1. Download `SciPrepMac-universal-Release.zip` and compare its SHA-256 value with `SHA256SUMS.txt`.
2. Double-click the ZIP, then move `SciPrepMac.app` to Applications.
3. Open the app normally. If macOS blocks this ad-hoc baseline build, Control-click the app, choose **Open**, then confirm. Only do this after checking the checksum and trusting the download source.

Version 3.0.0 (build 6) is a universal app containing Apple Silicon (`arm64`) and Intel (`x86_64`) code.

Current public release: [SciPrep macOS 3.0.0](https://github.com/theisegoria/SciPrep-macOS/releases/tag/v3.0.0).
Published and maintained by [@theisegoria](https://github.com/theisegoria).

Cloud learning sync is unavailable in this ad-hoc build; requires a provisioned distribution build. Offline Learn, flashcards, practice, review, and progress remain available.

## What’s new in 3.0

- A broad offline preclinical medical encyclopedia with 840 medical objectives, plus 183 GAMSAT/MCAT objectives and cross-linked A–Z, system, discipline, structure, pathway, molecule, drug-class, and formula indexes.
- Dual flagship depth: 50 cardiovascular objectives and 100 neuroscience objectives, including a native whole-neuroaxis spatial atlas with 158 selectable semantic entities.
- 15,297 structured flashcards with deterministic FSRS-6 scheduling, spatial-label, case-sequence, diagram, calculation, comparison, and misconception cards alongside preserved review history.
- 1,028 validated native scientific scenes, schema-6 panel and label layout, three neuroscience editorial plates, and eight cardiovascular editorial illustrations. Exact labels, geometry, quantities, and interactions remain native and accessible.

## Release contents

- `SciPrepMac-universal-Release.zip` — portable universal archive containing the verified `SciPrepMac.app` bundle.
- `SHA256SUMS.txt` — SHA-256 checksum for the archive.
- `PUBLIC_MAC_RELEASE_MANIFEST.txt` — bundle, architecture, signing, and notarization details.

This public artifact release intentionally contains no source code. A later Developer ID/notarized build will state that status in the manifest.
