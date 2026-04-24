# HQ Nurseries · The Wendy House

Static marketing website for HQ Nurseries (The Wendy House), a Perth-based nursery for children aged 3 months to 5 years.

## Tech

- Vanilla HTML, CSS, JavaScript — no frameworks
- CSS Grid + Flexbox, fully mobile responsive
- Google Fonts: Fraunces (display) + Nunito (body)
- Deployed via GitHub Pages

## Structure

```
hq-nurseries/
├── index.html              Home
├── about.html              About
├── what-we-offer.html      Sessions, rooms, curriculum, daily routine
├── admissions.html         How to apply + enquiry form
├── gallery.html            Photo grid
├── contact.html            Contact info + form + map placeholder
├── css/styles.css          Design system + components
├── js/main.js              Nav, scroll reveal, form UX
├── assets/                 Logo + imagery
└── .nojekyll               Tell GitHub Pages to serve files as-is
```

## Run locally

Open `index.html` in a browser, or run a static server:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Brand palette

| Role | Hex |
|------|-----|
| Cream (background) | `#FAF4E1` |
| Brown (primary) | `#6B4423` |
| Green (primary) | `#7BA955` |
| Yellow (accent) | `#F1B434` |
| Blue (secondary) | `#B9D9E8` |
