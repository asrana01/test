# Test Repository

This repository demonstrates how to automatically deploy a simple static site to a development environment using **GitHub Pages**.

## Local development

The static site lives in the `site` directory. You can open `site/index.html` directly in your browser or serve it with any static file server.

## Continuous deployment

A GitHub Actions workflow in `.github/workflows/deploy.yml` publishes the contents of the `site` directory to the `gh-pages` branch whenever code is pushed to the `main` branch. Once GitHub Pages is enabled in the repository settings to serve from the `gh-pages` branch, every push automatically deploys the latest site.

After pushing changes to `main`, visit `https://<your-username>.github.io/<your-repo>` to see the dev environment.
