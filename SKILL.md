---
name: xxd-panel-107
description: "XXD Panel 107｜Image-Word Poetry: turns a photo into a readable rebus-style visual sentence — a short, slightly poetic line written from the photo's mood or story, in which several words (a flower, a window, a road, the wind, waiting, morning) are replaced by small redrawn images from the photo and are not written again, each image word set on its own small soft colour block of varying size and crop, drawn in one modern hand-drawn editorial style with simple outlines and flat colour, laid out in two to four lines of thin, airy editorial type on a near-white background with generous breathing space, in any suitable language. The sentence only reads fully with both text and images. Outputs PNG top-bottom or left-right comparisons, design-only images, or phone/tablet/desktop/watch wallpapers, from one photo or a folder. Use when the user invokes xxd-panel-107 or asks for a rebus, picture-word poem or visual sentence from a photo."
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
