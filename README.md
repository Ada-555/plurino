# Plurino

**Web Development & Automation for Irish Small Businesses**

🌐 Live: [plurino.com](https://plurino.com)  
📄 GitHub Pages: [ada-555.github.io/plurino](https://ada-555.github.io/plurino)

---

## About

Plurino is a landing page site for a Dublin-based web development and automation consultancy targeting small Irish businesses. It showcases services, pricing, target markets, and provides an easy way for potential clients to get in touch.

## Tech Stack

| Layer | Technology |
|-------|------------|
| **Structure** | Semantic HTML5 |
| **Styling** | Custom CSS (no frameworks) |
| **Logic** | Vanilla JavaScript |
| **Fonts** | Google Fonts — Inter, JetBrains Mono |
| **Hosting** | GitHub Pages |
| **Domain** | plurino.com |

## Site Features

### Design
- **Dark cyberpunk aesthetic** — deep black (#030308) with neon green (#00ff41) and cyan (#00d4ff) accents
- **Animated particle background** — canvas-based floating particles with connecting lines
- **Scanline overlay** — subtle CRT-style effect for atmosphere
- **Gradient borders** — glowing nav bar and accent highlights

### Sections
1. **Hero** — Irish flag badge, headline, services tags, CTA buttons
2. **Founder** — Bio for Kay with avatar and skill tags
3. **Services** — 6-card grid (Websites, Booking, Shops, CRM, Tools, AI)
4. **Pricing** — 3-tier pricing (Starter €800, Growth €1,500, Automation €200/mo)
5. **Target Market** — 8-industry grid (Trades, Beauty, Fitness, Creatives, Food, Tutors, Retail, Startups)
6. **Process** — 4-step horizontal flow (Chat → Quote → Build → Launch)
7. **Examples** — 4 case study cards with results
8. **CTA / Contact** — Email link to k@kcx.me
9. **Footer** — Logo and tagline

### Interactions
- **Scroll animations** — `IntersectionObserver` triggers `.fade-in.visible` for section elements
- **Smooth scroll** — All anchor links scroll smoothly to sections
- **Hover effects** — Cards lift with shadow, buttons transform, neon glows intensify
- **Animated h1** — Lines fade in with staggered delays

## File Structure

```
plurino/
├── index.html    # Complete single-page site (CSS + JS inline)
└── README.md     # This file
```

Everything (HTML, CSS, JS) is contained in a single `index.html` file for simplicity and fast deployment.

## Deployment

The site deploys automatically via **GitHub Pages** from the `master` branch.

1. Push changes to `master`
2. GitHub Pages rebuilds within ~30 seconds
3. Updates live at both:
   - [ada-555.github.io/plurino](https://ada-555.github.io/plurino) (GitHub Pages URL)
   - [plurino.com](https://plurino.com) (custom domain, pointed to GitHub Pages)

## Custom Domain

To update the custom domain (plurino.com):
1. Go to repo **Settings → Pages**
2. Under "Custom domain", ensure `plurino.com` is saved
3. DNS should point to GitHub Pages via A record or CNAME

## Local Development

No build step needed. Just open `index.html` in a browser.

```bash
# Clone
git clone https://github.com/Ada-555/plurino.git
cd plurino

# Open directly
open index.html
# or
python -m http.server 8000
```

## Color Palette

| Name | Hex | Usage |
|------|-----|-------|
| Deep Black | `#030308` | Page background |
| Neon Green | `#00ff41` | Primary accent, CTAs, logo dot |
| Neon Cyan | `#00d4ff` | Secondary accent, links, highlights |
| Neon Purple | `#bf00ff` | Tertiary accent |
| Neon Blue | `#0080ff` | Quaternary accent |
| Neon Pink | `#ff0080` | Quinary accent |
| White | `#ffffff` | Primary text |
| Muted | `rgba(255,255,255,0.7)` | Secondary text |

## Contact

- **Email**: [k@kcx.me](mailto:k@kcx.me)
- **Location**: Dublin, Ireland
- **GitHub**: [github.com/Ada-555/plurino](https://github.com/Ada-555/plurino)
