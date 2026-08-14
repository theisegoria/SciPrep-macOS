# SciPrep for macOS

SciPrep is an unofficial independent study app for macOS 26.0 or later. It is not affiliated with, endorsed by, or produced by AAMC, ACER, the MCAT, or GAMSAT. Its questions are independent exam-style practice materials, not official exam questions.

## Install

1. Download `SciPrepMac-universal-Release.zip` and compare its SHA-256 value with `SHA256SUMS.txt`.
2. Double-click the ZIP, then move `SciPrepMac.app` to Applications.
3. Open the app normally. If macOS blocks this ad-hoc baseline build, Control-click the app, choose **Open**, then confirm. Only do this after checking the checksum and trusting the download source.

Version 2.0.0 (build 5) is a universal app containing Apple Silicon (`arm64`) and Intel (`x86_64`) code.

Current public release: [SciPrep macOS 2.0.0](https://github.com/theisegoria/SciPrep-macOS/releases/tag/v2.0.0).
Published and maintained by [@theisegoria](https://github.com/theisegoria).

Cloud learning sync is unavailable in this ad-hoc build; requires a provisioned distribution build. Offline Learn, flashcards, practice, review, and progress remain available.

## What’s new in 2.0

- A broad offline preclinical medical encyclopedia with 116 medical objectives and cross-linked A–Z, system, discipline, structure, pathway, molecule, drug-class, and formula indexes.
- A 40-objective cardiovascular flagship spanning anatomy, development, electrophysiology, pump mechanics, haemodynamics, mechanisms, and pharmacological targets.
- 3,116 structured flashcards with deterministic FSRS-6 scheduling, smart decks, sibling burying, leech handling, and preserved review history.
- 304 validated native scientific diagrams plus eight original cardiovascular editorial illustrations. Exact labels, quantities, and interactions remain native and accessible.

## Release contents

- `SciPrepMac.app` — launchable macOS application bundle.
- `SciPrepMac-universal-Release.zip` — portable universal app archive.
- `SHA256SUMS.txt` — SHA-256 checksum for the archive.
- `PUBLIC_MAC_RELEASE_MANIFEST.txt` — bundle, architecture, signing, and notarization details.

This public artifact release intentionally contains no source code. A later Developer ID/notarized build will state that status in the manifest.
