# D Darling Design — Design System

The site is a gallery for dried floral work: the flowers lead and the interface stays out of the way.

## World
- **Mood:** a quiet, linen-walled studio in Chichester. Editorial, unhurried, collected.
- **Motif:** the arch, used for the hero video, the scroll-opening photo, the reel and the service thumbnails. It echoes vases, church windows and the curve in the logo.
- **Light:** paper sections for browsing; deep green rooms (Weddings, Enquire, footer) for drama.

## Colour
| Token | Hex | Use |
|---|---|---|
| `--paper` | `#F2ECE1` | Main background (linen) |
| `--paper-deep` | `#E7DDCC` | Alternate sections |
| `--ink` | `#1C1A14` | Text |
| `--ink-2` | `#4F493B` | Secondary text on paper |
| `--green` | `#1F4012` | Brand: sampled from the logo. Buttons, Enquire section |
| `--night` | `#122309` | Dark sections, footer |
| `--bone` / `--bone-2` | `#EDE4D3` / `#BFC4A8` | Text on dark |
| `--rust` / `--rust-glow` | `#9E421C` / `#D98A56` | Accent from the wedding astilbe; hover and focus only |

## Type
- **Display:** Bodoni Moda (optical size 96). Its high-contrast Didone shapes match the logo. Italics carry the emphasis word in each heading.
- **Body and labels:** Instrument Sans. Small labels are uppercase, 500 weight, 0.14–0.16em tracking.
- Display type is capped at 6rem.

## Motion
- **The one authored moment:** the "Crafted with intention" section. As you scroll, an arch-shaped window opens to a full-bleed photo of the wedding bouquet.
- Hero lines rise in on load. The service image follows the cursor on desktop.
- Everything respects `prefers-reduced-motion`.

## Rules
- No eyebrow labels above headings.
- No card grids for services; they use an editorial index list.
- Photos are web-sized copies in `assets/img/` (≤1400px, or ≤2400px for wedding images). Originals stay in `Images/` and `testimonial/`.
