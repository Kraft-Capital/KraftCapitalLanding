# Kraft Capital Landing Page

Landing page for Kraft Capital Academy.

## Live Website

Once GitHub Pages is deployed, the site will be live at:
👉 **[https://kraftcapital.in](https://kraftcapital.in)**
*(Fallback GitHub Pages URL: [https://kraft-capital.github.io/KraftCapitalLanding/](https://kraft-capital.github.io/KraftCapitalLanding/))*

## GitHub Pages Deployment

This repository is prepared for GitHub Pages hosting:
- Entry point: `index.html` (at repository root)
- `.nojekyll` file included to prevent Jekyll build overhead
- Automated GitHub Actions deployment workflow configured in `.github/workflows/deploy.yml`

### Enabling in GitHub Repository Settings

1. Go to repository **Settings** > **Pages** (under the "Code and automation" section).
2. Under **Build and deployment** > **Source**:
   - Choose **GitHub Actions** (recommended, uses the automated workflow).
   - *Alternatively*, choose **Deploy from a branch**, select branch `main` and folder `/ (root)`.
3. Save settings.
