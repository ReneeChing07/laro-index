# Laro Index

A responsive single-page index of games made by Filipino creators, recreated from the three prototype screenshots supplied for this project.

## Files
- index.html — semantic page content and Bootstrap layout.
- css/styles.css — custom design and responsive adjustments.
- images/sun.svg — original vector recreation of the prototype sun mark.
- process-journal.html — printable draft journal; complete the author details and final verification before submission.
- README.md — project and publication instructions.

There is no build step. No custom JavaScript is needed: navigation uses native section anchors and game cards link directly to Steam.

## Preview
Open this folder in Visual Studio or Visual Studio Code, then open index.html in a browser. Internet access loads Bootstrap 5.3.9 and the Inter font. Arial is the font fallback.

## Design
Warm white background, navy headings, blue links, red labels, six colored initial cards, a studio list, and the About section follow the supplied prototype. Cards use CSS artwork rather than unprovided game cover images. The six games and four studios follow the screenshot order. The footer year is 2026. Years and platform labels otherwise retain the supplied prototype wording.

Bootstrap provides the container, grid, cards, navigation, buttons, spacing utilities, and screen-reader utilities. Custom styles set the prototype proportions and responsive behavior. Relative asset paths support GitHub Pages repository subdirectories.

## Verification status
Source structure and internal section references can be checked from the saved code. Desktop/mobile browser rendering, keyboard operation, resource loading, and live-site link clicks have NOT been tested because local execution and browser tools were unavailable during preparation. GitHub publication is pending repository access. Do not describe the website as published until the actual deployment succeeds.

Before submission:
1. Check at 360, 768, and 1440 px widths; confirm no horizontal overflow.
2. Use Tab and Enter to visit the skip link, navigation, game cards, and footer.
3. Confirm all six cards open their correct Steam pages.
4. Confirm the sun mark, Bootstrap stylesheet, and font load.
5. Complete and print process-journal.html to PDF using your surname in the filename.
6. Open the published URL and repeat the navigation and asset checks.

## Publish to GitHub Pages
1. Create or choose a repository named laro-index. A public repository supports GitHub Pages on GitHub Free.
2. Upload index.html, css/, images/, README.md, and the completed journal to the repository root, then commit to main.
3. Open Settings > Pages.
4. Under Build and deployment choose Deploy from a branch.
5. Select main and /(root), then Save.
6. Wait for deployment to finish and use the actual URL displayed by GitHub Pages.

Expected URL patterns (replace YOUR-USERNAME; these are not published links):
- Website: https://YOUR-USERNAME.github.io/laro-index/
- Repository: https://github.com/YOUR-USERNAME/laro-index

## Credits
- Design reference: supplied Laro Index screenshots and Figma prototype: https://www.figma.com/make/mvcBdEOlRMuwHm2TmE8Dxm/Visual-Novel-Index-Wireframes?p=f
- Bootstrap (MIT): https://getbootstrap.com/docs/5.3/getting-started/introduction/
- Inter font: https://fonts.google.com/specimen/Inter
- GitHub Pages instructions: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
- Game names and studio names belong to their respective owners. The website is an independent index, with no storefront affiliation.
