# xFUTURE

One-page brand site for **xFUTURE** — wear your intent, shape your future.

A single self-contained `index.html` built with Tailwind (CDN), GSAP + ScrollTrigger, and Lenis smooth scroll. No build step.

## Run it

Open `index.html` directly in a browser, or serve it locally:

```bash
python3 -m http.server 8000
# → http://localhost:8000
```

## Motion system

- Loader counter → clip-path page reveal → staggered hero entrance
- Hero: canvas particle dust, mouse parallax, scrubbed exit on scroll
- Kinetic marquee strips boosted by scroll velocity (two tracks, opposite directions)
- Scroll-velocity page skew, animated film grain, custom dual-ring cursor
- Giant X glyph with scroll-coupled rotation
- Scrub-highlighted quote, stamped-in graffiti headlines, split-character reveals
- Product cards: 3D tilt + glare follow, animated pattern art, staggered mask reveals
- Font-morph section scrubbed through six logo treatments with progress dots
- Magnetic CTAs

All ambient loops respect `prefers-reduced-motion`.
