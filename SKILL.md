# Levy Legacy Brand Guidelines

## Colors

### Core palette

| Role | Name | Hex |
|------|------|-----|
| Base | Base navy | `#01133D` |
| Background alt | Neutral cream | `#F9F7F3` |
| Accent | Brand green | `#01FFB7` |
| Secondary | Blue 400 | `#4C4DC3` |
| Secondary light | Blue 100 | `#97B9FF` |

**Base navy `#01133D`** is the primary background and dominant color across all surfaces.

**Brand green `#01FFB7`** is used for highlights, CTAs, underlines, and key visual moments. Should feel energetic against navy, not pastel or muted.

**Text on dark:** White only. Never use off-white, cream, or light gray as the primary text color on dark navy — white provides the contrast the brand requires.

**Background usage** — Dark navy (`#01133D`) should cover roughly 25% of a document or deck, reserved for high-impact moments: cover pages, section dividers, hero slides, and full-bleed feature pages. Light backgrounds (`#F9F7F3` or white) should carry the remaining 75%, especially for long content blocks, small body text, and dense information — readability is the priority. Never use a dark background for text-heavy pages or small type. The 75/25 split is a guideline; when in doubt, default to the lighter background.

**Accessibility — WCAG AA contrast (required)** — All text must meet WCAG AA minimum contrast ratios:

- Normal text (under 18pt / under 14pt bold): minimum **4.5:1** against its background
- Large text (18pt+ or 14pt+ bold): minimum **3:1** against its background

Brand green (`#01FFB7`) **must never be used as text color on light or cream backgrounds** — it fails AA contrast at any size. Green is an accent/highlight color only: use it for decorative elements, underlines, icons, CTAs, and gradient/motion elements. Never use it as body or heading text on light surfaces.

On dark navy (`#01133D`): use white for all text — confirmed passing. Green may be used sparingly for single words or short labels (e.g. "Levy" in the logo lockup) but not for body copy.

When generating any layout, verify text contrast before finalizing. If a combination fails AA, default to white (on dark backgrounds) or navy `#01133D` (on light backgrounds).

**Prohibited:** Blurple (blue-purple) backgrounds are not part of the palette. Blue 400 `#4C4DC3` is a secondary color for accents and UI elements — it must never be used as a large background. If a shade reads as purple or violet for a background, it is wrong. Stay in the navy-to-black range for dark backgrounds.

---

### Brand ramp (navy tonal scale)

Warm-toned tonal scale derived from the base navy. Used for surfaces, dividers, and tonal UI elements that need brand warmth.

| Step | Hex | Notes |
|------|-----|-------|
| 25 | `#E6E0D5` | |
| 50 | `#F8F8F8` | |
| 100 | `#D5C9B3` | |
| 200 | `#C5B496` | |
| 300 | `#B59F78` | ⚠ see discrepancy note below |
| 400 | `#A48961` | ⚠ see discrepancy note below |
| 500 | `#94754C` | ⚠ see discrepancy note below |
| 600 | `#735B3B` | ⚠ see discrepancy note below |
| 700 | `#202160` | corrected (was `#51402A`) |
| 800 | `#1A1A4C` | corrected (was `#2F2518`) |
| 900 | `#01133D` | corrected (was duplicate `#2F2518`); matches Base navy |

> **⚠ Steps 700–900 corrected:** The previous values (`#51402A`, `#2F2518`, `#2F2518`) were wrong. Confirmed values are `#202160`, `#1A1A4C`, `#01133D`. Step 900 anchoring to Base navy `#01133D` is consistent with a tonal ramp terminating at the brand base.

> **⚠ Unresolved discrepancy — steps 300–600:** The stated hex values for these steps (`#B59F78`, `#A48961`, `#94754C`, `#735B3B`) are tan/brown tones, but the corresponding visual swatches in Figma render as blue. Either the hex codes are wrong for the swatches shown, or the swatches were incorrectly applied in the Figma file. **Do not use steps 300–600 in production until the design team confirms which is authoritative — the hex codes or the rendered swatches.**

---

### Neutral ramp (cool greys)

Structural use only — no brand meaning. Use for borders, disabled states, and layout scaffolding.

| Step | Hex |
|------|-----|
| 25 | `#F4F6F7` |
| 50 | `#F4F6F7` |
| 100 | `#E3E8EA` |
| 200 | `#CBD3D6` |
| 300 | `#A6B3BA` |
| 400 | `#7B8D95` |
| 500 | `#60727A` |
| 600 | `#4A6270` |
| 700 | `#40535E` |
| 800 | `#3A4750` |
| 900 | `#17222B` |

---

### System palette

| State | Light (background) | Full (text / icon) |
|-------|-------------------|-------------------|
| Success | `#DCFCE7` | `#16A34A` |
| Error | `#FEE2E2` | `#DC2626` |
| Warning | `#FEF3C7` | `#D97706` |

---

## Typography

> **⚠ Font discrepancy — needs confirmation:** The original brief specified **Reckless** as the headline typeface. The Figma type scale uses **Libre Bodoni**. These are documented below as-found in Figma. Confirm with the design team which is correct before treating either as final.

### Headings — Libre Bodoni

Serif. Use for hero text, section titles, and any moment that should feel authoritative or expressive.

| Level | Size | Line-height | Tracking |
|-------|------|-------------|----------|
| H1 | 64px | 110% | -2% |
| H2 | 48px | 110% | -2% |
| H3 | 40px | 110% | -2% |
| H4 | 32px | 110% | -2% |
| H5 | 28px | 110% | -2% |
| H6 | 24px | 110% | -2% |

---

### Body / Paragraph — Satoshi

Geometric sans-serif. Use for paragraphs, captions, UI labels, and supporting copy. Available in Regular and Bold.

| Size | px | Line-height | Tracking |
|------|----|-------------|----------|
| XL | 20px | 140% | 0% |
| L | 18px | 140% | 0% |
| M | 16px | 140% | 0% |
| S | 14px | 140% | 0% |
| XS | 12px | 140% | 0% |

---

### Kicker Labels — Satoshi

All-caps, Bold weight. Use for eyebrow labels, category tags, and section identifiers above headlines.

| Size | px | Line-height | Tracking | Case |
|------|----|-------------|----------|------|
| XL | 20px | 120% | 0% | Uppercase |
| L | 18px | 120% | 0% | Uppercase |
| M | 16px | 120% | 0% | Uppercase |
| S | 14px | 120% | 0% | Uppercase |
| XS | 12px | 120% | 0% | Uppercase |

---

Do not swap heading and body roles. Libre Bodoni headlines + Satoshi body/kickers is the system; mixing or substituting degrades the brand voice.

---

## Motif

The loop is a signature brand element — an organic, continuous-ribbon mark that softens the structured typography and adds a human, craft feel. It appears as underlines or emphasis marks beneath key words, decorative connectors between sections, and large-scale compositional elements over photography.

### Canonical SVG assets

Four exact loop files live in `assets/`. **Use these as-is — do not regenerate the shape from description.** All four share the same gradient fill: `#4C4DC3` → `#01FFB7` (Blue 400 to Brand green).

| File | Dimensions | Shape | Best for |
|------|-----------|-------|----------|
| [`assets/loop-wide-banner.svg`](assets/loop-wide-banner.svg) | 1885 × 371 | Single horizontal knot, very wide | Banners, headers, thin horizontal strips |
| [`assets/loop-wide-curve.svg`](assets/loop-wide-curve.svg) | 1920 × 990 | Wide single S-curve | Landscape hero images, wide photo overlays |
| [`assets/loop-wide-double.svg`](assets/loop-wide-double.svg) | 1920 × 909 | Wide figure-8 / double-loop | Large hero moments needing more visual weight and complexity |
| [`assets/loop-tall-vertical.svg`](assets/loop-tall-vertical.svg) | 1025 × 1024 | Vertical double-curve | Portrait layouts, mobile content, tall hero sections |

### Loop Mask assets

Two PNG mask files provide a distinct usage mode: **Loop as Mask**. In this mode the loop shape itself crops and reveals the photo from within it, rather than sitting on top as a graphic element. Navy fills the surrounding area; the loop openings are transparent so the photo behind shows through. The loop ribbon carries the `#4C4DC3` → `#01FFB7` gradient stroke.

| File | Dimensions | Shape | Best for |
|------|-----------|-------|----------|
| [`assets/loopmask.png`](assets/loopmask.png) | 1920 × 1080 | Single large organic teardrop loop, right side | Wide layouts where a clean, elegant single-loop photo reveal is preferred |
| [`assets/sloopmask.png`](assets/sloopmask.png) | 1920 × 1080 | Figure-8 / double-loop, right side | Wide landscape layouts where stronger brand presence and more visual complexity are needed |

**How to use — layer order, bottom to top:**

1. Photograph
2. Mask PNG (`loopmask.png` or `sloopmask.png`)
3. Text

Place the photo behind the mask file. The navy surround is built into the PNG — the left area is available for text. Position and scale the photo so the subject is centered in the loop opening(s).

**Choosing between the two:**

- `loopmask.png` — simpler, more elegant. Use when one subject or a clean architectural frame is the focal point.
- `sloopmask.png` — more visual weight, two reveal windows. Use when the hero needs stronger brand presence or when two distinct photo moments can show through each loop.

**Selecting a variant** — match the loop's aspect ratio to the available composition space:

- Wide horizontal strip → `loop-wide-banner` or `loop-wide-curve`
- Large hero needing presence → `loop-wide-double`
- Tall or portrait space → `loop-tall-vertical`

**The loop is not required on every page.** Only include it where it genuinely fits the composition — forced use is worse than omission.

### Loop Usage Rules

**Over photography**

Layer the loop over, behind, or through images — never as a frame or border around a photo. Placement must be compositionally intentional: follow a building's contour, frame an activity, or guide the eye toward a focal point. Use the navy-to-teal-green gradient to give the loop energy against the photograph.

**As a masking / cropping element**

At large scale — hoardings, banners, website heroes — the loop shape itself can crop and reveal the photo rather than overlaying a rectangular image. The navy field surrounding the masked area becomes an active part of the composition, not dead space.

**Recreating the mask in PowerPoint**

Layer order, bottom to top:

1. Photograph
2. Background mask (pre-made, transparent background)
3. Text

Place the photo behind the mask, then position and resize the photo until the composition reads correctly. Place all text above both layers.

**Compositing the loop over real photography with AI tools**

When using AI generation to composite the loop over a real photograph (rather than design software), the prompt must enforce all of the following:

- The building or photographed subject remains completely photorealistic and unaltered.
- The loop is a single continuous ribbon, maintaining its exact provided shape, color, and stroke width.
- The loop weaves naturally through the architecture — passing behind elements and re-emerging in front of them in a physically believable way.
- The original sky and background are preserved as-shot.
- No additional graphic elements are introduced beyond the single branded loop.

---

## Iconography

Icons follow the same continuous-line spirit as the Loop — each icon is a single unbroken line gesture. They avoid literal real-estate clichés (no house silhouettes, no keys, no generic skylines).

**Style rules**

- Consistent line weight across the full set.
- Each icon sits within a soft circular field filled in the brand's supporting blue.
- No fills inside the line — the mark is defined entirely by the stroke.

**Categories**

- Core Business & Strategy
- Asset Classes
- Investment & Finance
- Development Process
- Firm Identity

---

## Photography Guidelines

**Subject matter** — real projects, real places, real people. Show lived-in, active communities. Avoid generic cityscapes, posed boardroom scenes, and construction-site photography for its own sake.

**Lighting** — natural and warm, with legible detail throughout the frame. Avoid dramatic processing, heavy vignettes, or images so dark that the subject reads poorly at small sizes.

**Contrast** — moderate. Hold detail in both highlights and shadows; do not crush blacks or blow out skies.

**Color palette** — images should harmonize with the brand palette. Warm tones provide contrast against the navy-dominant brand environment without clashing.

**Mood** — candid and community-centered. Energetic without feeling staged or art-directed into unreality.

**Quality** — high resolution, professionally captured. No stock photography that reads as generic.

---

## UI Elements

### Inputs

All inputs use an **underline style only** — no full border box on any input type, on any background. The underline is the sole border treatment.

#### States

| State | Label / text | Underline | Notes |
|-------|-------------|-----------|-------|
| Inactive | Placeholder, neutral gray | Neutral gray | Default resting state |
| Active | User text, full color | Brand accent / Blue 400 `#4C4DC3` | Focused; underline switches to accent |
| Complete | User text, full color | Neutral (muted) | Value entered, not focused |
| Disabled | Muted, grayed out | Muted | Non-interactive; reduced opacity |
| Error | Red label + user text | Red `#DC2626` | Error message displays below the field |

State logic is identical on light and dark backgrounds. On dark navy, text and underlines invert — white or light-toned values replace the dark equivalents — but the same five states apply in the same order.

#### Input types

**Text field** — single-line, underline only. Placeholder in neutral gray; typed text in primary color for the background.

**Dropdown** — underline style with a chevron indicator on the right. Chevron rotates on open. Behaves as a text field in Inactive/Active/Disabled/Error states.

**Icon-prefixed input** — leading icon left of the text field, vertically centered. Icon inherits the field's state color (muted when inactive, accent when active, red when error). Underline spans the full field width including the icon zone.

**Multi-line text area** — same underline treatment, expands vertically. No box border. Resize handle (if present) should be unobtrusive.

---

## Logo

### Lockups

**Vertical lockup** — stacks the wordmark across three lines:

```
Levy
Legacy
Group.
```

Use for compact or square placements: social profile images, favicons at large sizes, space-constrained collateral.

**Horizontal lockup** — sets the full name on one line:

```
Levy Legacy Group.
```

Preferred whenever horizontal space allows — headers, email signatures, slide footers, letterheads.

### Color treatment within the wordmark

In both lockups, the typographic color split is fixed:

| Part | On light / cream | On dark / navy |
|------|-----------------|----------------|
| "Levy" | Brand accent (green or blue) | Brand green `#01FFB7` |
| "Legacy Group." | Base navy `#01133D` | White `#FFFFFF` |

**Single-color version** — available when color reproduction is limited (one-color print, embroidery, foil):

- All navy `#01133D` on light backgrounds
- All white `#FFFFFF` on dark backgrounds

Do not mix the single-color rule with the two-color treatment. When in doubt, use the two-color version.

### The period

The period after "Group" is a fixed part of the mark — **it must always be present.** Do not remove it for space, set it in a different weight, or treat it as optional punctuation.

### Clearspace

Minimum clearspace on all sides equals the height of one "G" letterform as it appears in the wordmark. This applies to both the vertical and horizontal lockups. No other logos, type, images, or graphic elements may appear within that zone.

### Co-branded and partner lockups

When Levy Legacy Group. appears alongside a partner or sponsor mark:

- Both logos must carry equal visual weight — neither should dominate.
- Separate the two marks with a vertical divider line and consistent breathing room on each side.
- Use matching logo heights, not matching bounding boxes, to calibrate visual balance.
- The result should feel intentional — a considered composition, not two logos placed near each other.

---

## Tone Summary

Navy `#01133D` + white + brand green `#01FFB7` + Reckless + Satoshi + hand-drawn marks = Levy Legacy. The palette is tight on purpose. When in doubt: dark navy background, white text, green accent, serif headline.
