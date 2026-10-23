# AutoForge — Premium Car Dealership (Scroll-Scrub Hero)

A dark, cinematic one-page dealership site inspired by the viral "Buy your car Online" 3D-scroll websites. As the visitor scrolls, the hero car appears to advance through front → angle → profile → rear views while the headline changes at each stage — the scroll-scrubbed showroom effect, built with zero libraries.

## What's inside
- **Scroll-scrub hero** — a tall scroll section with a sticky stage: 4 real car photos crossfade, zoom and drift in sync with scroll progress; stage headlines swap per view, with a progress bar and clickable stage labels (FRONT / ANGLE / PROFILE / REAR).
- **Live inventory** — 8 cars rendered from a data array, filterable by type (Supercar / Muscle / Coupe / Sedan) and sortable by price, year and horsepower. Each card shows a computed "from $X/mo".
- **Car detail modal** — full spec sheet (engine, power, 0–60, mileage, transmission, drivetrain), monthly estimate, and buttons that hand off to the booking form or the finance calculator with the car's price pre-loaded.
- **Finance calculator** — price and down-payment sliders, term and APR selectors, live monthly payment + total interest.
- **Test-drive booking form** — full validation (name, email, phone, car, future date, time) with inline errors and a personalised on-screen confirmation.
- Showroom hours section, stats strip, scroll-reveal animations, fully responsive.

## Customise it for a buyer
- **Cars:** edit the `CARS` array in the `<script>` (name, price, specs, image, blurb) — cards, modal, calculator and the booking dropdown all update automatically.
- **Photos:** replace files in `images/` (same filenames) — hero stages are `hero-1.jpg` … `hero-4.jpg`.
- **Branding:** change the `AUTOFORGE` logo text, the `--acc` colour variable (hero yellow), address/hours in the Visit section.
- **Finance defaults:** APR options and slider ranges are plain HTML in the Finance section.

## Tech
Single self-contained `index.html` (embedded CSS + vanilla JS), local images only, no build step, no external requests. Open it in any browser or drop it on any static host (GitHub Pages, Netlify, Vercel).

Photos: Unsplash (free to use). Demo content — prices and inventory are illustrative.
