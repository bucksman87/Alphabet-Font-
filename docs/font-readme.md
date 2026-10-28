# Square Alphabet — technical summary

Hand-drawn monospace display font built from marker-on-grid photos (`source-glyphs/A.jpg` … `Z.jpg`).

## Files

| Path | Description |
|------|-------------|
| `SquareAlphabet.ttf` | TrueType — install on macOS & Windows |
| `SquareAlphabet.otf` | CFF OpenType — same glyphs |
| `docs/kak-ispolzovat-i-prodavat.md` | Beginner guide in Russian (install + sell) |
| `docs/font-readme.md` | This file |
| `previews/alphabet-preview.png` | A–Z grid + sample word (from bitmaps) |
| `previews/alphabet-preview-font.png` | Preview rendered with the installed TTF |
| `source-glyphs/*.jpg` | Original photos (unchanged) |

## Family & metrics

- **Family name:** Square Alphabet  
- **PostScript name:** `SquareAlphabet-Regular`  
- **Style:** Regular  
- **Units per em:** 1000  
- **Advance width:** 1000 (full em) for letters and space — monospace squares  
- **Mapped characters:** `A`–`Z`, `a`–`z` (lowercase shares the same designs), space  

## Design notes

- Each glyph is a thick square frame with unique internal marks taken from the matching photo.
- Outlines were traced from cleaned bitmaps (potrace) to keep a bold marker feel with slight irregularity.
- Letter **filename = Unicode letter** (`A.jpg` → `A`/`a`, …, `Z.jpg` → `Z`/`z`).
- Glyph designs are the original digitization; no letter-pair difference enhancements.
