# Janis Shin — personal portfolio

A responsive, dependency-free portfolio for https://janisshin.github.io/.

## Publish with GitHub Pages

In this repository, open **Settings → Pages**. Under **Build and deployment**, choose **Deploy from a branch**, select **main** and **/ (root)**, then click **Save**. GitHub will publish the site at https://janisshin.github.io/. Future commits to `main` update the site automatically.

## Edit the site

- `index.html`: biography, projects, experience, publications, education, and links.
- `styles.css`: colors, typography, desktop and mobile layouts.
- `script.js`: project filters and accessible mobile navigation.
- `favicon.svg`: browser icon.
- `.nojekyll`: serves the static files without a Jekyll build.

No build tools, package installation, or API keys are needed. For local preview, run `python3 -m http.server 8000` in this folder and open http://localhost:8000.

## Design and content

The one-page academic portfolio structure is inspired by Jackie Valeri's website (https://jackievaleri.github.io/). This implementation uses original code, styling, copy, and decorative artwork; it does not include her photographs or theme code.

Project illustrations are decorative rather than quantitative figures. Content is plain HTML and remains accessible without JavaScript; JavaScript adds filtering and a collapsible mobile menu. The site uses system fonts and no analytics or third-party scripts.

Publication links point to the original papers. The portfolio links only to public project repositories. Add a portrait, CV download, email, and LinkedIn when ready; there are no placeholder contact links or fabricated project metrics.
