# DONALD'S FOOTIES

A responsive static website for DONALD'S FOOTIES, a handcrafted footwear business. The site uses plain HTML, CSS, and JavaScript and can be hosted on GitHub Pages without a backend.

The visual palette uses deep navy, warm white, and muted gold, with the brand name styled in Playfair Display.

## Project files

- `index.html` — page content and sections
- `styles.css` — responsive layout, colors, and typography
- `script.js` — mobile navigation and current footer year
- `assets/` — locally stored footwear and shoemaking illustrations used throughout the page

## Preview locally

1. Download or clone this project.
2. Open the project folder.
3. Double-click `index.html` to preview it in a browser.

   For a local web server instead, open a terminal in the project folder and run:

   ```sh
   python -m http.server 8000
   ```

   Then visit [http://localhost:8000](http://localhost:8000).

The page does not require a build step or package installation. Google Fonts are an optional external font source; the site uses system font fallbacks if they are unavailable.

## Publish free with GitHub Pages

1. Sign in to GitHub and create a new **public** repository, for example `donalds-footies`.
2. Upload the contents of this folder to the repository’s root. Make sure `index.html`, `styles.css`, `script.js`, `README.md`, and `assets` are at the top level.
3. On GitHub, open the repository’s **Settings** tab.
4. Select **Pages** in the sidebar.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Select the `main` branch and `/ (root)` folder, then click **Save**.
7. Wait for the Pages deployment to finish. GitHub will show the live website URL on the Pages settings screen.

To publish changes later, upload or commit the updated files to the selected branch. GitHub Pages will redeploy automatically.

## Personalize before launch

- The site includes original illustrations, not photographs of actual products. You can keep them as brand artwork or replace the SVG files in `assets/` with your own footwear and workshop photos. Update the image `alt` text in `index.html` to accurately describe any replacements.
- Edit the sample collection names and descriptions to match your actual footwear and available designs.
- Add your real social profile links where the social placeholders appear.
- The contact form is intentionally disabled and does not send messages. Connect a form provider, configure its required form action/attributes, and remove the disabled attributes before inviting visitors to use it.
- The email, phone, WhatsApp link, and location are already set to the supplied business details.
