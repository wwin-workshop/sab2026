# SAB 2026 Workshop Website

Static GitHub Pages website for the SAB 2026 workshop:

**Wanting What is Needed: From Homeostatic Control to Adaptive Behavior**

## Contents

- `index.html` — single-page workshop website
- `styles.css` — responsive styling
- `assets/favicon.svg` — small site icon
- `assets/og-card.svg` — social preview image
- `.nojekyll` — tells GitHub Pages to serve the folder as plain static files

## Publish with GitHub Pages

1. Create a public GitHub repository, for example `sab2026-wanting-what-is-needed`.
2. Upload all files in this folder to the root of the repository.
3. In GitHub, go to **Settings → Pages**.
4. Under **Build and deployment**, choose:
   - Source: **Deploy from a branch**
   - Branch: **main**
   - Folder: **/** root
5. Save. The site will appear at:
   `https://<username-or-organization>.github.io/sab2026-wanting-what-is-needed/`

## Things to update before public launch

Search for these phrases in `index.html` and replace when the information is available:

- `Submission form: coming soon`
- `Important dates will be announced shortly`
- `Times are provisional`
- `SAB 2026, Berlin` / final room information
- Speaker photos and detailed bios, if desired
- Contact email, if the workshop will use a dedicated shared address

## Suggested repository settings

- Repository name: `sab2026-wanting-what-is-needed` or `wanting-what-is-needed-sab2026`
- Description: `SAB 2026 workshop website: Wanting What is Needed — From Homeostatic Control to Adaptive Behavior`
- Website URL after deployment: paste it into the repository's About section

## Optional custom domain

If you later want a shorter URL, add a `CNAME` file containing the custom domain and configure DNS according to GitHub Pages instructions.
