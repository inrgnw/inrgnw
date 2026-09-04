# inrgNW — v2

A simple static website for **inrgNW**, a Washington State energy management consulting business.

## Files

- `index.html` — website content and email-reveal behavior
- `styles.css` — site styling
- `assets/puget-sound.jpg` — supplied photo, optimized for web
- `assets/sailboats.jpg` — supplied photo, optimized for web

## What changed

- The hero now uses the supplied Puget Sound / mountain / ferry photograph.
- A small original SVG orca illustration has been added to the water.
- The headline now reads **“Smart Buildings. Sustainable Future.”**
- The supplied sailboat photograph is used in the Experience section.
- The standalone “Get in touch” button in the CTA was removed.
- The CTA now has a **Reveal Email Address** button.
- A temporary email address is configured in the client-side reveal script.
- The address is assembled client-side only after click, hover, or keyboard focus, reducing exposure to simple email-harvesting bots.

### Important email note

No client-side website technique can guarantee that an email address will be hidden from a determined scraper. This version is intended to keep the address out of the initial HTML text and deter basic harvesting bots.

## Copyright / image-use note

The two photographs in `assets/` are the photographs supplied by the site owner in this project. The orca is an original SVG illustration created for this website.

No stock photo was added.

The site uses system fonts and has **no third-party image, font, or JavaScript dependency**.

## Publish with GitHub Pages

1. Create a GitHub repository.
2. Upload the contents of this folder, including the `assets` folder.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and `/ (root)`.
6. Save.

GitHub will then provide the published site address.
