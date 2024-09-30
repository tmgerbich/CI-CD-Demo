# CI-CD Workflow Documentation

## Purpose
This project demonstrates using GitHub Actions for CI and deploying a static website to GitHub Pages.

## CI Workflow
The CI workflow is triggered on every push to the `main` branch. It generates a simple HTML file and prepares it for deployment.

## CD Workflow
After the build step, the CD workflow deploys the generated HTML to GitHub Pages.

### Configurations
- The `peaceiris/actions-gh-pages` action is used for deployment.
