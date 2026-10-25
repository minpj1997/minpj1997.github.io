# Pengjin Min's academic website

Personal website at **https://minpj1997.github.io/**, hosted by GitHub Pages.

The site uses plain HTML and CSS. There is no framework, package installation, or build step. All website files are owned and maintained in this repository.

## Edit the site on GitHub

1. Open the file you want to change and choose the pencil icon (Edit this file).
2. Edit the text and commit the change to `main`.
3. GitHub Pages publishes the update automatically. Allow a few minutes for it to appear.

| File | Content |
| --- | --- |
| `index.html` | Biography, job market information, education, and awards |
| `research.html` | Papers, abstracts, working projects, and presentations |
| `teaching.html` | Teaching and research experience |
| `papers/*.html` | Individual paper pages and bibliographic metadata |
| `assets/style.css` | Typography, colors, spacing, and mobile layout |
| `assets/pengjin-min.jpg` | Profile photo |
| `files/Pengjin_Min_CV.pdf` | Downloadable CV |

To update the CV, upload a replacement PDF using the same filename. When you change a paper, update both its entry in `research.html` and its individual page in `papers/`. The main paper links point to arXiv, so readers can access the current public version.

The navigation and profile sidebar are repeated in the HTML files. If you change your email or affiliation, update all HTML pages. A site search in GitHub is useful for finding these entries.

## Hosting settings

In **Settings → Pages**, select **Deploy from a branch**, choose **main** and **/(root)**, and save. Keep the `.nojekyll` file so GitHub serves the static files directly. The repository name must remain `minpj1997.github.io` for this user-site address.

## Preview locally

From this folder, run `python3 -m http.server 8000`, then open `http://localhost:8000`. Stop the server with Ctrl+C.

## Search engines

The site includes a sitemap, crawl permissions, canonical URLs, and bibliographic metadata on each paper page. Search engine inclusion and timing remain controlled by the search engines.
