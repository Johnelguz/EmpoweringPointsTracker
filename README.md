# EmpoweringPointsTracker

A static credit-card benefits and points tracker. The shared card catalog is
loaded from a published Google Sheets CSV. Each visitor's portfolio is saved
in their browser and is not synced between devices.

## Publish with GitHub Pages

1. Create a public GitHub repository and push these files to its `main` branch.
2. In the repository, open **Settings → Pages** and set the build and deployment
   source to **GitHub Actions**.
3. The workflow in `.github/workflows/deploy-pages.yml` deploys the site after
   each push to `main`. Find the live URL in the workflow run or the Pages
   settings.

The published catalog spreadsheet and any card images must be publicly
readable. The app uses browser storage for portfolios, so a visitor's saved
cards are available only in that same browser and device.
