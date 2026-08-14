# Publishing the HaHoresh 14 site on GitHub Pages

This folder is a complete static GitHub Pages site. The repository root must contain `index.html`, `.nojekyll`, `assets/`, `robots.txt`, and `.github/workflows/deploy-pages.yml` exactly as they appear here.

## Before publishing

- GitHub Pages is public. Anyone with the URL can open it, and the repository files can be downloaded.
- `noindex` and `robots.txt` ask search engines not to index the site; they are not access control.
- Do not add bank account numbers, payer names, phone numbers, ID numbers, or bank screenshots.
- Review the legal wording and the current Ministry of Justice status before each publication.

## Publish

1. Create a new public GitHub repository, for example `ha-horesh14-info`.
2. Put the contents of this folder at the repository root and push to the `main` branch.
3. In **Settings > Pages**, set **Source** to **GitHub Actions**.
4. Open the **Actions** tab and wait for the `Deploy GitHub Pages` workflow to finish.
5. The URL will normally be `https://<account>.github.io/ha-horesh14-info/`.

For restricted access, do not use GitHub Pages. Use hosting with authentication instead.
