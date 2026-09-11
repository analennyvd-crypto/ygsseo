# ygsseo

SEO and marketing tracking for YGS Brothers (ygshandymanservices.com), a
bilingual handyman company serving Port Richey, New Port Richey, Holiday,
Palm Harbor, Clearwater, Saint Petersburg, Tarpon Springs, Hudson, Tampa,
and Spring Hill, FL.

## New website

A fast, dependency-free static site replacing the current Squarespace site,
built for local SEO: `index.html`, `services.html`, `service-areas.html`,
`gallery.html`, `about.html`, `contact.html`, plus `css/style.css`,
`js/main.js`, `robots.txt`, and `sitemap.xml`.

Before going live:

- **Photos:** every image is a labeled gray placeholder. See
  [`images/README.md`](images/README.md) for how to drop in real photos.
- **Contact form:** `contact.html` posts to FormSubmit — replace
  `YOUREMAIL@example.com` in the form's `action` with a real email, then
  submit the form once live to receive FormSubmit's confirmation link.
- **Facebook link:** replace the `#` placeholders in the footer/contact page
  with the real Facebook page URL.

To preview locally: `python3 -m http.server 8000` from this folder, then
open `http://localhost:8000`.

To deploy: drag-and-drop this folder onto Netlify, or connect the repo to
Netlify/Vercel/GitHub Pages, then point `ygshandymanservices.com`'s DNS at
it (replacing Squarespace).

## Contents

- [`docs/website-punch-list.md`](docs/website-punch-list.md) — prioritized
  audit and fix list for the previous Squarespace site (trust/conversion +
  local SEO) — kept for reference.
- [`docs/marketing-plan.md`](docs/marketing-plan.md) — weekly lead-gen routine
  across Google Business Profile, Facebook groups, and Craigslist.
- [`templates/lead-tracker-template.xlsx`](templates/lead-tracker-template.xlsx) —
  spreadsheet to log leads by source and track conversion rate.
