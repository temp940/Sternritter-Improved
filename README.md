# STERNRITTER / DESIGN V3

A reimagined, 7-page fashion atelier website developed in **HTML and CSS only**.

## Pages
- `index.html` — editorial campaign homepage
- `collections.html` — Atelier, Vesper, Dynasty collection pages
- `shades.html` — functioning CSS-only five-shade preview
- `fit.html` — measurements, fits, and FAQ accordions
- `lookbook.html` — filterable 22-image gallery (CSS-only)
- `about.html` — brand philosophy, imagery, and process
- `contact.html` — structured demo enquiry form

## Navigation
The fixed left side rail opens a slide-out navigation drawer using a checkbox and CSS sibling selectors. On mobile, the rail becomes a compact top bar. No JavaScript is used.

## Image library
This website displays all 22 original STERNRITTER image files hosted in the **public** `temp940/Sternritter` repository. It does not modify that repository. Images are referenced by URL rather than duplicated because the GitHub integration cannot currently transfer image binaries between repositories. Keep the original repository public or transfer real image files to `images/` and update paths before taking this website into production.

## Real-world readiness
The contact form is a **demonstration only** using `contact@sternritter.example`, not a live inbox. Replace the placeholder and connect to a secure backend or form service before processing customer information. The colour studio and gallery filters work with CSS, but selections are not persisted. No payments, orders, or bookings are processed.

## Deployment
Publish `main` from the repository root under **Settings → Pages**. The homepage is `index.html`.

## Navigation and image curation update
- Desktop: persistent top navigation with active-page indicator.
- Tablet/mobile: visible scrollable page navigation under the masthead.
- Slide-out menu stays available for expanded browsing; the footer now contains one enquiry action rather than the primary links.
- Lookbook: all 22 original images grouped into Collections (3), Signature Shades (5), Fit & Measurements (7), Campaign & Craft (4), and Finishing Details (3).
- Collections banner uses collection photography; fitting-study imagery moved to the Fit Guide. Brand imagery appears with the story, not randomly in a collection.
