# DESIGN.md — Serena

## 1. Brand Identity
- **Product**: Serena
- **Tagline**: L'assistante WhatsApp des sages-femmes
- **Voice**: Intimate, warm, trustworthy — like a letter from a colleague
- **Audience**: Independent French midwives (sages-femmes libérales)

## 2. Color Palette
| Token | Hex | Role |
|---|---|---|
| `--bg` | `#f0ebe4` | Page base (Warm Parchment) |
| `--surface` | `#faf6f1` | Cards, alternating sections (Soft Linen) |
| `--dark` | `#1e1e1e` | Dark sections, footer (Deep Charcoal) |
| `--dark-card` | `#2a2a2a` | Cards inside dark sections |
| `--accent` | `#c4724a` | CTAs, highlights, active states (Terracotta) |
| `--accent-lt` | `#d9896a` | Hover state for accent |
| `--text` | `#1a1a18` | Headings and body (Near Black) |
| `--muted` | `#8a8278` | Subtitles, supporting copy (Warm Gray) |
| `--warm-light` | `#c8c0b8` | Body text on dark backgrounds |
| `--peach` | `#fde8d8` | Chat bubble tint 1, form card |
| `--sage` | `#d8edd8` | Chat bubble tint 2 |
| `--lavender` | `#e8d8f0` | Chat bubble tint 3 |

## 3. Typography
- **Headline Font**: Playfair Display (400, 600, 700; italic variants)
- **Body Font**: Inter (300, 400, 500, 600)
- **Base Size**: 17px / 1.7 line-height
- **Headings**: h1 clamp(2.2rem, 5vw, 3.6rem) · h2 clamp(1.8rem, 3.5vw, 2.6rem)

## 4. Components
- **Buttons**: pill-shape (border-radius: 50px), terracotta fill, warm white text
- **Cards**: 16px radius, `box-shadow: 0 6px 32px rgba(100,70,50,.12)`, no harsh borders
- **Chat Bubbles**: WhatsApp-style, rounded, pastel tint backgrounds
- **Icons**: Line-art SVG, 1.5px stroke, terracotta or charcoal tones
- **Section Label**: 0.78rem, 600 weight, 0.14em letter-spacing, uppercase, terracotta

## 5. Spacing Rhythm
- Section padding: 120px top/bottom (desktop), 80px (tablet), 60px (mobile)
- Container max-width: 1120px, 32px side padding
- Card gaps: 24–28px
- Generous vertical breathing room throughout

## 6. Design System Notes for Stitch Generation
Platform: Web, Desktop-first (mobile-responsive). Theme: Light warm minimal. 
Background #f0ebe4. Surface #faf6f1. Dark #1e1e1e. Accent #c4724a. 
Text #1a1a18. Muted #8a8278. Headline: Playfair Display serif. Body: Inter sans-serif.
Buttons: pill-shaped, terracotta. Cards: 16px radius, warm shadow. 
Atmosphere: warm, humanistic, intimate — designed by a midwife with taste.
