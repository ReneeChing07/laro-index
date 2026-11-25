# Laro Index

Laro Index is a responsive Bootstrap website that helps visitors discover games made by Filipino creators and find the official storefront for each title.

## Project files

- `index.html` - semantic single-page website and navigation.
- `css/styles.css` - custom design system, responsive layout, and poster treatment.
- `images/sun.svg` - the Laro Index mark.
- `process-journal.html` - print-ready process journal draft for Google Docs/PDF export.
- `surname_processjournal.md` - earlier project notes and publication checklist.

## Run locally

Open `index.html` in a browser. Bootstrap 5.3.9 and the Inter font load from their public CDNs. The game cards use official artwork URLs from Steam's CDN and fall back to the project's color system if an image is unavailable.

## Publish with GitHub Pages

1. Upload the files in this folder to the root of a GitHub repository.
2. Commit them to the `main` branch.
3. In the repository, open **Settings > Pages**.
4. Select **Deploy from a branch**, choose `main` and `/(root)`, then save.
5. Copy the repository and published-site URLs into the final process journal.

## Credits

- Bootstrap: https://getbootstrap.com/docs/5.3/getting-started/introduction/
- Inter font: https://fonts.google.com/specimen/Inter
- Game listings and official artwork: the linked Steam storefront pages for each title.
- The layout and sun mark were prepared for the Laro Index project; no external site template was copied.

## Final verification checklist

- Test at 360 px, 768 px, and 1440 px widths.
- Use Tab to confirm the skip link, navigation, game cards, and footer links.
- Confirm all six Steam links and artwork load.
- Export `process-journal.html` to PDF and include the PDF in the final compressed folder.
- Replace the placeholder GitHub URLs in the journal with the actual links after publication.
