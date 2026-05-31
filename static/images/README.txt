IMAGE GUIDE
───────────────────────────────────────────────────────────

HERO (homepage full-width banner)
  File:  static/images/hero.jpg
  Size:  1400 x 600px minimum, landscape
  Ideas: Tennessee campus, Nashville skyline, fiber/data center

INSTITUTION LOGOS (homepage anchor institutions strip)
  Files: static/images/institutions/tsu-logo.png
         static/images/institutions/mtsu-logo.png
         static/images/institutions/ttu-logo.png
         static/images/institutions/utc-logo.png
  Size:  200 x 80px, transparent PNG preferred

NEWS / EVENT IMAGES (per content item)
  Place inside the item's own folder alongside index.md
  Example:
    content/news/workshop-3-recap/
      index.md          ← add:  image: workshop-3-group.jpg
      workshop-3-group.jpg

  Size:  800 x 500px minimum, landscape

Until real images are provided, picsum.photos placeholders
are used automatically — the site will not break.

PARTNER LOGOS
  Folder: static/images/partners/
  Format: transparent PNG, ~180x70px
  Naming matches data/partners.yaml logo field:
    nsf-logo.png
    internet2-logo.png
    ornl-logo.png
    tbr-logo.png
    ... etc

NETWORK MAP
  Replace the placeholder SVG in layouts/index.html with:
  Option A: A real SVG file at static/images/network-map.svg
  Option B: An embedded interactive map (Leaflet.js) — discuss with dev
