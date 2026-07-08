# Caleb Supermarket — Student Landing Page

A single-file static landing page for Caleb Supermarket at Caleb University, Imota. Built to look like an editorial magazine layout, not a generic SaaS template.

---

## 📁 Files

| File | Purpose |
|------|---------|
| `index.html` | The entire website. One file, no build step. |

## 🚀 Host on GitHub Pages

1. Go to [github.com](https://github.com) → **New repository**
2. Name it `caleb-supermarket` → **Public** → **Create**
3. Click **Add file** → **Upload files** → upload `index.html`
4. Click **Commit changes**
5. Go to **Settings** → **Pages** → **Deploy from a branch** → select `main` / `(root)`
6. Click **Save**
7. Wait 1–2 min, refresh. Your URL: `https://yourusername.github.io/caleb-supermarket`

---

## 🎨 What Makes This Different

| Generic AI Site | This One |
|-----------------|----------|
| Purple/blue gradients | Warm paper + clay + forest green |
| Rounded pill buttons | Sharp 4px corners, editorial feel |
| Floating shadow cards | Thin grid lines, no shadows |
| "Fuel your journey" copy | "Food that doesn't eat your allowance" |
| Light gray testimonial boxes | Full dark section inversion |
| Centered everything | Asymmetric split layouts |

---

## ✏️ Customize

| Element | Where to Edit |
|---------|---------------|
| Store name / tagline | Top of `<body>`, `.hero-left` |
| Prices & deals | `.deals-grid` section |
| Address / phone / hours | `.location` section |
| Student testimonials | `.testis-grid` section |
| Colors | `:root` CSS variables at top of `<style>` |
| Google Maps | Replace `.loc-map` placeholder div with iframe |
| Hero photo | Replace `.hero-img-placeholder` with `<img>` |

---

## 📱 Responsive

- Desktop: Full split layouts, 4-column grids
- Tablet: Stacks to single column, 2-column footer
- Mobile: Single column, hamburger nav hidden (nav links collapse)

---

## 🔤 Fonts

- **Space Grotesk** — Headings, numbers, labels
- **Inter** — Body text, paragraphs

Both loaded from Google Fonts CDN. No local files needed.

---

## ⚡ Performance

- Zero JavaScript (except CSS marquee animation)
- Zero external dependencies except Google Fonts
- Single HTML file — no build step, no bundler

---

Built for Caleb University students. Free to use and modify.
