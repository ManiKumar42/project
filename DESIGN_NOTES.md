# Design notes

These values are defined once at the top of `style.css` (CSS variables). Change them there.

## Colors
| Name | Value | Used for |
|---|---|---|
| Primary | `#2563eb` | Buttons, links, highlights |
| Primary dark | `#1d4ed8` | Button hover |
| Text | `#1f2937` | Headings and body |
| Muted | `#6b7280` | Descriptions |
| Background | `#ffffff` | Page |
| Background alt | `#f3f4f6` | Services, FAQ, Sign Up, Footer |
| Border | `#e5e7eb` | Cards and inputs |

## Typography
- Font: **Poppins** (400, 500, 600, 700) loaded from Google Fonts, with Segoe UI / Arial as fallback.
- Headings use `clamp()` so they scale smoothly between phone and desktop.

## Layout
- Max content width: 1200px, side padding 20px (16px on small phones).
- Section spacing: 64px (48px on mobile). Card radius: 12px. Buttons are pill shaped.
- Breakpoints: 992px (tablet), 768px (mobile menu, single column), 480px (small phones).

## Images
Everything sits in the same folder as `index.html`. Service icons are 36px and shown at their real size so they stay sharp.

## To match Figma exactly
The values above are starting points. Compare them against the Figma file (colors, font sizes, spacing) and update the variables in `style.css`.
