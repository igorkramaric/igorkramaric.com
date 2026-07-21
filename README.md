# igorkramaric.com

Static personal website for GitHub Pages.

Open `index.html` directly in a browser to test locally, or serve the folder with any static file server.

## Publishing

This repository includes a GitHub Actions workflow at `.github/workflows/pages.yml`.

To publish:

1. Push the repository to GitHub.
2. In the repository settings, open **Pages**.
3. Set **Build and deployment** to **GitHub Actions**.
4. Push to `master` or `main`, or run the workflow manually from the **Actions** tab.

The included `CNAME` file is configured for `igorkramaric.com`. GitHub still requires the custom domain to be configured in the repository Pages settings.
