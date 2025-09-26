# ChronoNAD+ Landing Page

A single-page marketing site built with plain HTML, CSS, and JavaScript. No build tools or server-side code.

## Project Structure

- `index.html` — all markup, styles, and scripts are in this file
- `assets/` — static images (e.g., testimonial photos)

## Features

- Hero section with a background grid of images and a subtle flicker effect
- 3D molecule visual with desktop mouse tilt
- Product Showcase with four stats that count up when scrolled into view
- Benefits section with a scrolling reveal that highlights parts of a human silhouette
- Testimonials slider with next/prev controls and proper layering under the header text
- Science section with an inline SVG chart and hover tooltips, plus animated flow arrows
- Global fade-in-up animations driven by Intersection Observer, with gentle stagger per card
- Mobile navigation with a toggled menu
- Custom cursor on desktop
- Responsive layout

## Run Locally

No dependencies are required. You can open the site directly:

1. Open `index.html` in your browser.

Or serve it with a simple static server (optional):

```bash
# Using Python 3
python3 -m http.server 8000
# then visit http://localhost:8000/index.html
```

## Customization Tips

- Images: replace or add images in `assets/` and update their references in `index.html`.
- Colors and timings: adjust CSS variables and animation/keyframe values inside `index.html`.
- Copy: edit headings, paragraphs, and labels directly in `index.html`.

## Notes

- All CSS and JS are inline in `index.html` for simplicity.
- Tested on modern browsers; graceful degradation on older ones is not guaranteed.

