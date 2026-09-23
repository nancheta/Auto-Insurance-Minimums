# State Minimum Auto Insurance Coverage Explorer

A public beta for comparing state minimum automobile insurance coverage requirements.

## Publish with GitHub Pages

1. Create a GitHub repository (suggested name: `state-auto-insurance-explorer`).
2. Upload the **contents of this folder** to the repository root and commit them to `main`.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment → Source**, choose **GitHub Actions**.
5. Open **Actions** and confirm the `Deploy to GitHub Pages` workflow succeeds.
6. GitHub will display the public site URL in **Settings → Pages**.

The included workflow also republishes the site automatically whenever `main` is updated.

## Important publication note

This prototype is based on the supplied state dataset. State insurance requirements can change. Before treating it as an authoritative public reference, validate each jurisdiction's requirements and official source, and preserve the methodology disclosure for derived comparison values such as Florida's $40,000 display.

## Files

- `index.html` — application entry point
- `data/states.json` — normalized state dataset
- `.nojekyll` — disables Jekyll processing for the static site
- `.github/workflows/deploy-pages.yml` — automatic GitHub Pages deployment
