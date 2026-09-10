---
name: xxd-panel-107
description: "Create XXD Panel 107 raster artwork: a faithful photograph paired with a readable rebus-style visual sentence whose source-derived hand-drawn image words genuinely replace words in the text. Accepts one image or a directory batch and supports exact 50:50 top-bottom or left-right pairs, design-only artwork, four-device wallpaper, multiple ratios or exact sizes, and prompt-generated or user-supplied wording. Use whenever the user invokes xxd-panel-107 or asks for this image-word visual-poetry style."
---

# XXD Panel 107

Create finished PNG artwork from the current user-supplied photograph or image directory. Read `references/original-prompt/zh-CN.md` completely immediately before every generation. That Chinese source brief is the sole creative and aesthetic authority; never summarise, translate, blend, or replace it with this file, a README, a sample, or another Panel.

Read `references/soldier-runtime.md` completely immediately before building every generation request. It is the sole family runtime contract for parameters, preference reuse, directory batches, preflight, prompt assembly, bitmap execution, output isolation, and acceptance. This Skill must not write a second art direction or a second runtime.

## Panel-specific overlay

The transformed region must contain one grammatically ordered rebus sentence: printed text fragments and source-derived image words alternate along a clear reading path; each pictured word occupies the missing word's position and is essential to reconstructing the sentence. A replaced word never appears again as printed text. Reject a complete printed sentence with decorative pictures, loose illustrations beside copy, sticker walls, card lists, regular grids, or disconnected collages. Text-free delivery destroys that sentence; use it only when the user explicitly accepts that the result will no longer be an image-word rebus.

These overlay rules add to `references/soldier-runtime.md`. They never replace the source brief or the family runtime contract.

Write every selected final PNG directly inside one fresh task directory under `~/Desktop/xxd/xxd-panel-107/` (or the explicit `--out` root). Use collision-safe filenames; do not create source, mode, or size subdirectories and do not generate an automatic contact sheet.

## References

- `references/soldier-runtime.md` — family runtime contract used at generation time
- `references/original-prompt/zh-CN.md` — canonical source brief used at runtime
- `references/original-prompt/README.md` — translation index and authority note
- `references/runtime-preferences.md` — safe delivery-preference reuse
- `references/sample-workflow.md` — sample-artwork maintenance only; never a runtime prerequisite
- `references/xxd-panel-107-prompt.zh-CN.md` and `.en.md` — delivery adapter notes matching the family runtime blocks
