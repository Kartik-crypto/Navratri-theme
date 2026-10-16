# Haier IT — Digital Durga: Circuit of Shakti

A self-contained, mobile-first static website for the Haier IT Department Navratri 2026 decoration contest.

## Files
- `index.html` — webpage structure and interactions, including the three-hit Happy Dushera bow-and-arrow slingshot game with fireworks.
- `style.css` — responsive page styling.
- `assets/` — local Navratri artwork, Haier logo SVG, and the Navadurga photos used in the orbit.
- `assets/navadurga/CREDITS.txt` — image authors, sources, and licenses.
- `assets/team/` — local portrait assets for the sample team section.
- `assets/team/CREDITS.txt` — portrait sources and a reminder to replace fictional sample profiles before publishing.
- `README.txt` — this deployment guide.

No build tools, external libraries, fonts, or images are required. The rangoli is drawn as inline SVG, so the page works without third-party image dependencies.

The team section contains eleven sample profiles in a horizontally scrollable, center-snapping carousel. Replace the sample names, roles, responsibilities, and portrait assets with approved staff information before publishing.

## Preview locally
1. Extract the ZIP.
2. Open `index.html` in Chrome, Edge, or Firefox.
3. Test the page at a narrow/mobile width, click the nine capability cards, and try the Dushera game: pull the arrow back and release, land three hits on Ravan, and replay after the fireworks.

## Free hosting with GitHub Pages
GitHub Pages can publish static HTML/CSS/JavaScript from a repository. On GitHub Free, use a **public repository** for the simplest setup. Anything published on a public Pages site can be viewed by anyone, so do not include confidential company information.

1. Sign in at https://github.com/
2. Create a new repository, e.g. `digital-durga-circuit-of-shakti`. Set it to **Public** if using GitHub Free Pages.
3. Upload `index.html` to the repository root (the top-level folder). You can optionally upload this README too.
4. Open the repository's **Settings** → **Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Choose branch **main** and folder **/(root)**, then click **Save**.
7. Wait for the Pages deployment to finish. Open the URL shown in Settings → Pages. It will normally look like:
   `https://YOUR-GITHUB-USERNAME.github.io/digital-durga-circuit-of-shakti/`
8. Open the published URL on a phone using mobile data as well as Wi-Fi. Confirm that the page loads and all nine cards respond.

GitHub's documentation: https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site

## Create the physical QR poster
Do this **after** the final website URL works. Do not create a QR code pointing to a preview or temporary URL.

1. Copy the published HTTPS URL.
2. Open a reputable QR-code generator such as https://www.qrcode-monkey.com/.
3. Paste the exact URL and generate a standard URL QR code.
4. Download a high-resolution PNG or SVG.
5. Place it in a white square on your poster with the heading:
   “SCAN TO EXPERIENCE DIGITAL SHAKTI”
6. Keep the QR code dark on a plain white/light background. Leave a clear blank margin around it; do not place circuit graphics inside that margin.
7. Print at least 5–7 cm wide (larger is better for a display poster).
8. Test the printed poster with two different phones from the distance visitors will scan it. Confirm the destination URL is correct and loads without sign-in.

## Before publishing
- Replace generic innovation themes with only approved, public-safe examples if desired.
- Do not include internal system URLs, credentials, employee data, factory information, or confidential screenshots.
- Ask your company's IT/communications team whether public hosting is allowed for a company-branded contest page. If not, use approved internal hosting and create the QR only after the internal URL is accessible to intended visitors.
- `assets/haier-logo.svg` is the Haier wordmark from Wikimedia Commons, marked public domain: https://commons.wikimedia.org/wiki/File:Haier_logo.svg

## Customization
Edit `index.html` in any text editor. Search for:
- `HAIER · IT DEPARTMENT` — header label
- `Innovation in Action` — showcase section
- `Navratri 2026` — event label
- The four innovation cards — replace with approved examples of your team's projects
