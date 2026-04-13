# Maison Dorée — 3-Page Website

A complete 3-page artisan bakery website built on the Maison Dorée design system.

## Pages

| File | Page | Purpose |
|------|------|---------|
| `index.html` | Home | Full homepage with hero, about, menu preview, process, testimonials carousel, seasonal feature, and contact form |
| `menu.html` | Menu | Tabbed full menu (Breads / Viennoiseries / Pâtisserie), seasonal feature, subscription tiers, FAQ accordion |
| `contact.html` | Visit & Contact | Visit cards, hours, map placeholder, full order/enquiry form with validation, Instagram grid |

## What to Fill In

- **Real address** — replace `14 Rue de la Paix, Old Town Quarter` throughout all 3 files
- **Phone number** — replace `+1 (555) 042-1909`
- **Email** — replace `hello@maisondoree.com`
- **Google Maps link** — replace `https://maps.google.com` with your real embed or directions URL
- **Instagram handle** — replace `@maisondoree`
- **Unsplash images** — all images load from Unsplash CDN. For production, download and host locally, or replace with your own photography
- **Prices** — update all menu prices to match your actual pricing
- **© year** — currently set to 2026

## Design System

All CSS variables live in the `<style>` block at the top of each file under `:root {}`. To change the brand palette, update these variables (they're consistent across all pages):

```css
--gold:         #B8873A;   /* primary accent */
--gold-light:   #D4A855;   /* hover/light states */
--brown:        #3A2A1A;   /* dark text, backgrounds */
--cream:        #F9F4EC;   /* page background */
--cream-dark:   #EFE6D5;   /* section alternates */
```

Fonts are loaded from Google Fonts:
- `Playfair Display` — display headings
- `Cormorant Garamond` — body/serif text
- `Jost` — sans-serif labels and UI

## How to Launch

**Quickest option — Netlify:**
1. Go to [netlify.com/drop](https://netlify.com/drop)
2. Drag the entire `maison-doree-3page` folder onto the page
3. Your site is live instantly with a Netlify URL

**GitHub Pages:**
1. Push all files to a GitHub repository
2. Go to Settings → Pages → set source to `main` branch
3. Your site is live at `https://yourusername.github.io/repo-name`

## To Add Later (requires backend/CMS)

- **Real form submission** — connect to Netlify Forms, Formspree, or EmailJS (no backend needed for basic email)
- **Live menu updates** — add a CMS like Sanity or Contentful to let staff update items without touching code
- **Online ordering/payment** — integrate Stripe or a booking system like Square
- **Real Google Maps embed** — replace the map placeholder with an `<iframe>` from Google Maps Embed API
- **Blog / news section** — add a `blog.html` index page + individual post pages
