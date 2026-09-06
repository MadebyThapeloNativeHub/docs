# LICENSES

This file explains which parts of this repository are covered by which license and gives a short example of how to satisfy the attribution requirements for the Creative Commons (CC BY 4.0) licensed content.

## Repository license mapping

- Code (source files, scripts, libraries, anything intended to be compiled or executed):
  - License: MIT
  - Canonical license file: `LICENSE` (top-level)
  - Alternate copy (also present): [LICENSE-CODE](https://github.com/MadebyThapeloNativeHub/docs/blob/main/LICENSE-CODE)
  - Typical paths: `src/`, `scripts/`, `Dockerfile`, `package.json`, `src/eslint-rules/`, and other files with programming language extensions (e.g. `.js`, `.ts`, `.go`, `.py`).

- Documentation and creative content (Markdown, images, site content, reusable data):
  - License: Creative Commons Attribution 4.0 International (CC BY 4.0)
  - Full text: `LICENSE-DOCS` (top-level)
  - Typical paths: `content/`, `assets/`, `data/`, `data/reusables/`, and other documentation or media files.

## How to attribute CC BY 4.0 content (example)

When you reuse documentation, images, or other creative content from this repository, you must provide appropriate attribution. A concise example you can use is:

"Documentation: MadebyThapeloNativeHub — GitHub Docs — https://github.com/MadebyThapeloNativeHub/docs — licensed under CC BY 4.0 (https://creativecommons.org/licenses/by/4.0/)."

If you modified the content, add a phrase such as "Modified from MadebyThapeloNativeHub — GitHub Docs" and, when reasonably practicable, include a link to the original file or repository.

## Notes and recommendations

- The top-level `LICENSE` file is the canonical license for repository code and is set to the MIT license so that tooling and package metadata recognize the code license.
- `LICENSE-CODE` is an additional copy of the MIT license and is available here:
  - https://github.com/MadebyThapeloNativeHub/docs/blob/main/LICENSE-CODE

- Keep `LICENSE-DOCS` (CC BY 4.0) with the full Creative Commons text for documentation and content consumers.

- Per-file license headers are optional but can help downstream consumers quickly confirm license terms for individual files. For documentation, including a one-line attribution in the header of major content files (for example in the top of a tutorial or guide) is helpful.

- If you publish packages or create separate distributable artifacts from this repo, ensure their package manifests (for example `package.json`) reflect the intended license. This repository's top-level `package.json` license field has been set to `MIT`.

If you want different wording, additional attribution examples, or a different filename (for example `NOTICE` or `LICENSES.md`), tell me and I will update it.