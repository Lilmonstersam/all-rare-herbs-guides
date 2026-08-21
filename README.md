# All Rare Herbs Growing Guides Mock-up

Self-contained static site for the growing-guides mock-up. It includes every generated image locally, so it is ready to deploy without external image dependencies.

## Files

- `index.html`: deployed mock-up entry point.
- `assets/growing-guides/`: generated guide photography.
- `.github/workflows/deploy.yml`: GitHub Pages deployment workflow.
- `.nojekyll`: serves the files without Jekyll processing.

## Deploy to GitHub Pages

Copy the contents of this folder into the root of [`Lilmonstersam/all-rare-herbs-guides`](https://github.com/Lilmonstersam/all-rare-herbs-guides), commit, and push to `main`.

In GitHub, open **Settings > Pages** and select **GitHub Actions** as the build and deployment source. Every subsequent push to `main` deploys the static site automatically.
