# Kaaz Garrett — personal portfolio

A responsive, static portfolio based on the supplied website and brand references. Built with HTML, CSS, and a small mobile-navigation script. No dependencies or build step required.

- Website: <https://kaazgarrett.github.io/>
- Repository: <https://github.com/kaazgarrett/kaazgarrett.github.io>

## Preview

Run `python3 -m http.server 8000` and open <http://localhost:8000>.

## Content and assets

- The plum, lavender, rose, and cream palette and Playfair Display / Inter pairing follow the supplied brand concept.
- Biography, role names, and project summaries are adapted from the supplied portfolio outline. Dates and unverified impact statistics are omitted pending the actual résumé.
- `assets/kaaz-portrait.jpg` and `assets/architecture.jpg` are web-sized crops of the user-supplied JPG. The original photo remains unchanged. Metadata is not copied into the public assets.
- The HEIC attachment was not used because its JPEG conversion rendered black.
- Instagram links to <https://www.instagram.com/floweravekaaz/>.
- Google Fonts are optional; Georgia and Arial are the fallback fonts.

## Details to add

1. Real project, publication, and podcast URLs: replace the “link coming soon” text in each work card with a link.
2. Final résumé PDF: add it under `assets/` and replace “Request my résumé” with a download link.
3. LinkedIn URL: replace the noninteractive placeholder in the contact section.
4. Final biography, dates, role details, and verified impact statistics.

Missing assets are labeled honestly rather than represented by broken downloads or invented URLs. Résumé requests currently open an email to `kaazgarrett@gmail.com`.

## Deployment

GitHub Pages serves the `main` branch and `/ (root)` folder. Push changes to `main` to update the live website.
