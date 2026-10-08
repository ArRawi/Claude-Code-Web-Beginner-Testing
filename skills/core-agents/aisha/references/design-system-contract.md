# DESIGN.md Contract Standard

This document defines the `DESIGN.md` contract schema for Aisha to establish visual brand consistency across all web prototypes, dashboards, slide decks, and motion graphics.

---

## 🎨 Color Palette Tokens (BAMBISSELL Dark Mode)

```css
:root {
  /* Surface colors */
  --bg-primary: #0a0f1d;
  --bg-secondary: #131b2e;
  --bg-card: rgba(255, 255, 255, 0.03);
  --bg-card-hover: rgba(255, 255, 255, 0.06);
  --bg-glass: rgba(19, 27, 46, 0.7);

  /* Borders & Dividers */
  --border-subtle: rgba(255, 255, 255, 0.08);
  --border-glow: rgba(0, 242, 254, 0.3);

  /* Brand Accents */
  --accent-cyan: #00f2fe;
  --accent-purple: #7f00ff;
  --accent-gradient: linear-gradient(135deg, #00f2fe 0%, #7f00ff 100%);
  
  /* Text */
  --text-primary: #f8fafc;
  --text-secondary: #94a3b8;
  --text-muted: #64748b;

  /* Glassmorphism Filter */
  --glass-blur: blur(16px);
  --radius-card: 16px;
  --radius-btn: 8px;
}
```

---

## ✒️ Typography Hierarchy

- **Font Family Primary:** `'Outfit'`, `'Plus Jakarta Sans'`, sans-serif;
- **Font Family Code/Data:** `'Space Grotesk'`, `'Fira Code'`, monospace;
- **Title H1:** `2.5rem`, `font-weight: 700`, `letter-spacing: -0.02em`
- **Subheading H2:** `1.5rem`, `font-weight: 600`
- **Body:** `1.0rem`, `line-height: 1.6`
