# inrgNW — Website v3

This version intentionally stays close to the original inrgNW design while using the owner's supplied Pacific Northwest photographs.

## What's included

- `index.html` — page content and the email-reveal behavior
- `styles.css` — original site styling
- `assets/puget-sound-rainier.jpg` — user-provided photograph
- `assets/sailboats.jpg` — user-provided photograph

## Copyright / third-party assets

No stock photographs, third-party icons, icon libraries, or externally hosted image services are used.

The orca is an original inline SVG created specifically for this site. The site uses ordinary system fonts rather than downloading a web font.

The two photographs in `assets/` were supplied by the site owner.

## Email protection

The current address is `TBD@inrgNW.com`.

The email is assembled in the browser by JavaScript and is not present as a plain email address in the initial HTML. It is revealed when a visitor clicks, hovers over, or focuses the button.

This is useful against simple harvesting bots, but no browser-based technique can completely hide an address from a determined scraper.

## GitHub Pages

1. Create a GitHub repository.
2. Upload the files in this folder, keeping the `assets` folder.
3. In GitHub, go to **Settings → Pages**.
4. Choose **Deploy from a branch**.
5. Select `main` and `/ (root)`.
6. Save.
