# HealthAura Pathology Laboratory — Website

Dr. Bhagwat's HealthAura Pathology Laboratory website built with **Astro 5** + **Tailwind CSS 4**. Static site optimized for SEO, local search (GEO), and Lighthouse 95+ scores.

## Quick Start

```bash
# Install dependencies
npm install

# Start dev server (localhost:4321)
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview
```

## Deploy to Vercel

### Option 1: Via GitHub (Recommended)
1. Push this folder to a GitHub repository
2. Go to [vercel.com](https://vercel.com) → "Add New Project"
3. Import your GitHub repo
4. Vercel auto-detects Astro — click "Deploy"
5. Your site is live at `your-project.vercel.app`

### Option 2: Direct CLI Deploy
```bash
npm install -g vercel
vercel
```

### Custom Domain
1. In Vercel dashboard → Settings → Domains
2. Add `healthaura.in` (or your domain)
3. Update DNS records as shown by Vercel

## Project Structure

```
src/
├── layouts/         → BaseLayout with SEO + JSON-LD schemas
├── components/      → All reusable UI components
├── pages/           → Route-based pages (/, /about, /tests-and-packages, etc.)
├── data/            → JSON data files (tests, packages, FAQ, testimonials)
├── styles/          → Global CSS with Tailwind brand tokens
└── content/         → (Phase 2) Blog markdown/Supabase content
public/
├── images/          → Logo, placeholder images
└── robots.txt       → SEO crawler instructions
```

## Image Placeholders

All images show gradient placeholders with descriptive text. Replace them with actual photos:

| Placeholder | Replace With |
|---|---|
| Hero slides (hero-lab.jpg, hero-yoga.jpg, etc.) | Professional lab photos, seasonal health banners |
| Doctor photo | Dr. Prachi Bhagwat professional headshot |
| Lab interior | Clean shots of lab equipment, workspace |
| Blog images | Health-themed stock or custom images |
| Location maps | Uncomment iframe embeds with real Google Maps URLs |

## Brand Colors

- **Primary Teal**: `#1D8A9A` (buttons, headers, accents)
- **Secondary Green**: `#2E7D32` (badges, icons, highlights)
- **White base** with `#F8FAFB` off-white sections

## SEO Features

- ✅ JSON-LD: MedicalBusiness, Physician, FAQPage schemas
- ✅ GEO meta tags (geo.region, geo.placename, ICBM)
- ✅ Open Graph + Twitter card meta on every page
- ✅ Semantic HTML5 with proper heading hierarchy
- ✅ Auto-generated sitemap.xml via @astrojs/sitemap
- ✅ robots.txt with sitemap reference
- ✅ Canonical URLs on all pages

## Phase 2 Roadmap

- [ ] Supabase backend for blog content
- [ ] Admin panel for content management
- [ ] FlutterFlow patient portal integration (Book Appointment CTA redirect)
- [ ] Individual test detail pages with pricing from database
- [ ] Health package pricing from database
- [ ] Online report viewing
- [ ] Payment gateway integration
- [ ] Edge functions for dynamic content

## WhatsApp Integration

All "Book Appointment" CTAs link to: `wa.me/917028022588` with pre-filled messages.

## Tech Stack

- **Astro 5** — Static site generation
- **Tailwind CSS 4** — Utility-first styling
- **Swiper.js** — Hero image carousel
- **Lucide Icons** — Free, MIT-licensed icon set
- **Vercel** — Hosting & CDN

---

© 2026 Dr. Bhagwat's HealthAura Pathology Laboratory. All rights reserved.
