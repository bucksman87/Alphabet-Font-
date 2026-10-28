# Square Alphabet — technical summary

Hand-drawn monospace display font built from marker-on-grid photos (`source-glyphs/A.jpg` … `Z.jpg`).

## Status

**2026-10-28** — stroke cleanup approved («утверждаю») and baked into `SquareAlphabet.ttf` / `.otf` from `internal/stroke-cleanup-mockup/after/A–Z.png`. Version **1.001**. No difference-enhancement redesign.

## Files

| Path | Description |
|------|-------------|
| `SquareAlphabet.ttf` | TrueType — install on macOS & Windows |
| `SquareAlphabet.otf` | CFF OpenType — same glyphs |
| `docs/kak-ispolzovat-i-prodavat.md` | Beginner guide in Russian (install + sell) |
| `docs/font-readme.md` | This file |
| `docs/stroke-cleanup-mockup.md` | Cleanup mockup note (approved → font) |
| `previews/alphabet-preview.png` | A–Z grid + sample word (from bitmaps) |
| `previews/alphabet-preview-font.png` | Preview rendered with the installed TTF |
| `previews/stroke-cleanup-mockup.png` | Stroke cleanup mockup preview |
| `source-glyphs/*.jpg` | Original photos (unchanged) |

## Family & metrics

- **Family name:** Square Alphabet  
- **PostScript name:** `SquareAlphabet-Regular`  
- **Style:** Regular  
- **Units per em:** 1000  
- **Advance width:** 1000 (full em) for letters and space — monospace squares  
- **Mapped characters:** `A`–`Z`, `a`–`z` (lowercase shares the same outlines), space  

## Design notes

- Each glyph is a thick square frame with unique internal marks taken from the matching photo.
- Outlines were traced from cleaned bitmaps (potrace) to keep a bold marker feel with slight irregularity.
- Letter **filename = Unicode letter** (`A.jpg` → `A`/`a`, …, `Z.jpg` → `Z`/`z`).
- Version 1.001 includes approved stroke cleanup (hairline/grid spikes trimmed; no letter-pair difference redesign).
