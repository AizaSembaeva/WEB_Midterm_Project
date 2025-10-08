# Bloom Beauty Salon — Midterm Project

**Topic:** Beauty Salon website  
**Stack:** HTML5, CSS3 (external stylesheet), Bootstrap 5, minimal JS

## What is inside
- `index.html` — Home (hero, features, pricing table)
- `about.html` — About & team
- `services.html` — Services list (uses :nth-child pseudo-class)
- `gallery.html` — Image gallery (CSS Grid)
- `contact.html` — Contact & booking form (includes form)
- `css/style.css` — main stylesheet: CSS variables, Flexbox, Grid, positioning, :hover, :focus, :nth-child
- `js/main.js` — mobile nav toggle + demo form handler
- `assets/` — put your images here (logo.png, hero.jpg, gallery-*.jpg, etc.)

## How it meets requirements
- At least 5 pages with consistent header/footer and navigation.
- External stylesheet `css/style.css` used (no inline styles).
- Semantic tags: header, main, section, article, footer, nav.
- Table present in Home page (pricing) and a contact form on Contact page.
- CSS variables defined in `:root`.
- Uses Flexbox for header and footer alignment and CSS Grid for services/gallery/team.
- Media queries at two breakpoints (992px and 700px).
- Uses Google Fonts (Montserrat).
- Images below the fold use `loading="lazy"`.
- :nth-child pseudo-class is used to style service cards.
- Includes Bootstrap grid and components via CDN.

## Deploy
1. Push project to a GitHub repo.
2. Enable GitHub Pages (Settings → Pages) or deploy on Netlify.
3. Replace `assets/*` placeholders with actual photos.

## Notes for defense
Be ready to explain:
- Why we used CSS Grid for gallery (layout flexibility) and Flexbox for header (alignment).
- How breakpoints change layouts and font sizing.
- Where positioning is used (hero background is absolutely positioned; header sticky).
