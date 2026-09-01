# XXD Panel 107 | Runtime Adapter (English)

This is not a second aesthetic prompt. Read `references/original-prompt/zh-CN.md` in full before generation; it is the sole creative and aesthetic authority for Panel 107. The current archive has no Markdown heading, so use the entire source brief verbatim. If a future archive adds a purely administrative heading, omit only that heading. This file only appends the current user's runtime variables.

## Non-authoring boundary

- Do not summarize, translate, expand, polish, or “improve” the source brief.
- Do not add a palette plan, material plan, composition theory, whitespace rule, title, microcopy package, or aesthetic motive.
- Preserve the source brief's own colour behaviour exactly, whether it derives colour from the photograph or specifies a fixed family.
- Let the image model execute the source brief's existing text logic. The outer Skill does not pre-write copy.
- `TOP_BOTTOM` uses the brief's native 3:4 canvas unless the user resolves another final size, and always preserves an exact 50:50 upper/lower split. `LEFT_RIGHT` maps that equal-pair principle to an exact 50:50 left/right split. Only design-only and wallpaper modes replace the paired container.
- The transformed region must contain a genuinely readable rebus sentence. Each image word occupies the missing printed word's grammatical position, and the replaced word must not appear again in text. Reject complete sentences with decorative pictures, sticker walls, card lists, or regular grids.
- Append only the selected mode's block to each asset; never send the unused modes as alternatives.

## Common delivery preamble

```text
MODE-SPECIFIC DELIVERY OVERRIDE — CURRENT ASSET

This block is the final authority only for the current presentation mode,
reality-source visibility, final canvas and device delivery. TOP_BOTTOM uses
the brief's native 3:4 unless another final size was explicitly resolved and
always keeps equal upper/lower regions; LEFT_RIGHT maps the same equal-pair rule
to left/right regions. DESIGN_ONLY and WALLPAPER_PACK replace
the old paired container.
Every source-brief instruction about the transformation's visual language,
subject identity, colour, material, texture, internal composition, whitespace,
text character and typography remains authoritative.

REALITY VIEW means the faithful photograph or factual scene defined by the source brief.
TRANSFORMED DESIGN means the source brief's designed reinterpretation of that reality view.

FINAL CANVAS: <ratio and/or exact WIDTHxHEIGHT>
COMPOSITION METHOD: ONE COHERENT COMPLETE-CANVAS GENERATION
EXACT PANEL GEOMETRY: REQUIRED FOR TOP_BOTTOM AND LEFT_RIGHT

Colour follows the original brief's existing colour instructions exactly.
Unless the user explicitly requests a colour change, do not add, replace,
summarize, or re-plan any palette.
```

## Select exactly one mode block

```text
OUTPUT MODE: TOP_BOTTOM
Create one complete canvas (native ratio 3:4 unless another final size was explicitly resolved) with exactly two equal-height horizontal regions. REALITY VIEW occupies the upper 50%; TRANSFORMED DESIGN occupies the lower 50%. The boundary is exactly at the vertical midpoint. Do not create a third band, footer, shared title strip, border, or transition. Keep the whole rebus sentence inside the lower 50%.
```

```text
OUTPUT MODE: LEFT_RIGHT
Create one complete canvas with exactly two equal-width vertical regions. REALITY VIEW occupies the left 50%; TRANSFORMED DESIGN occupies the right 50%. The boundary is exactly at the horizontal midpoint and both regions run from top edge to bottom edge. Do not create a third band, footer, shared title strip, border, or transition. Keep the whole rebus sentence inside the right 50%.
```

```text
OUTPUT MODE: DESIGN_ONLY
Create one full-canvas artwork entirely in the TRANSFORMED DESIGN language. Use the REALITY VIEW only as the non-visible source of identity, structure, relationships, colour logic and facts. Every visible element belongs to the source brief's designed reinterpretation rather than an untransformed presentation of the source photograph.
```

```text
OUTPUT MODE: WALLPAPER_PACK
DEVICE PROFILE: <resolved PHONE, IPAD, DESKTOP or WATCH>
WALLPAPER RELATIONSHIP: <resolved INDEPENDENT or LINKED>
Create one full-canvas wallpaper for this device entirely in the TRANSFORMED DESIGN language. Use the REALITY VIEW only as a non-visible reference. Recompose for the device canvas and usable screen space; every visible element belongs to the designed result.
```

Append exactly one text block after the selected mode block. If the user has other explicit requirements, append those verbatim after the text block at the very end.

### Text generated from the original prompt

```text
TEXT MODE: ORIGINAL_PROMPT_GENERATED
TEXT LANGUAGE: <user-confirmed language or locale>

The image model generates wording by following the original brief's existing
text-generation logic. Every visible word must arise naturally from the current
source image's content, atmosphere or implied meaning. Anything presented as
factual or documentary information must come from user-supplied, visibly readable
or otherwise verified source facts; when those facts are unavailable, use poetic
non-factual wording. The runtime shell is never a source of visible copy.

First form one complete underlying sentence. Remove the words selected for
visualisation and place source-derived, consistently redrawn image words in
their exact grammatical positions. The visible result must read in sequence as
text → image word → text → image word → text. Never print a replaced word again.
```

### User-exact text

```text
TEXT MODE: USER_EXACT
TEXT LANGUAGE: <user-confirmed language or locale>
TEXT: “<user's exact characters>”

Treat the supplied sentence as the exact underlying sentence. Do not rewrite,
translate, spell-correct, or add wording. Only remove selected visualisable words
from visible text and replace them in place with image words; all remaining
visible characters stay verbatim. Typography follows the original brief.
```

### No text

```text
TEXT MODE: NONE
Render no letters, characters, numbers, titles, labels, logos, or pseudo-text anywhere.
This deliberately gives up Panel 107's rebus identity and is allowed only when
the user explicitly accepts that exception.
```

See `SKILL.md` for preflight, multi-size, multi-mode, wallpaper, execution, and output rules. Every final generation request has this order:

```text
complete verbatim source-brief body from original-prompt/zh-CN.md (all current content)
+ common delivery preamble
+ exactly one selected mode block
+ exactly one text-mode block
+ any other explicit user requirement, verbatim, at the very end
```
