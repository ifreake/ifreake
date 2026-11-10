# ifreake — Portfolio site

This folder contains the static portfolio website and its social-sharing preview assets.

## Publish with GitHub Pages

1. Open the repository **Settings → Pages**.
2. Under **Build and deployment → Source**, choose **GitHub Actions**, then save if prompted.
3. The included workflow deploys the `docs/` folder when changes are pushed to `main`, or when manually started from **Actions → Deploy portfolio to GitHub Pages → Run workflow**.
4. Open the Pages URL from the successful deployment summary.

The project-site address for this repository is:

`https://ifreake.github.io/ifreake/`

The existing profile repository is named `ifreake`. GitHub's root user-site address `https://ifreake.github.io/` requires a separate repository named exactly `ifreake.github.io`. That repository is not currently present, and the connected GitHub action does not expose repository creation. The profile README has therefore been left intact and this site is prepared as a project Pages site.

## Social preview

The page includes Open Graph and Twitter Card metadata. The custom preview image is `og-image.png` (1200 × 630). Social platforms cache link previews, so after publishing, use the platform's link-preview debugger or wait for its cache to refresh after changes.

## Files

- `index.html` — semantic page markup and social metadata
- `styles.css` — responsive dark/light UI
- `script.js` — mobile navigation, theme switch, reveal transitions, and share button
- `og-image.png` — custom social-sharing artwork
- `favicon.svg` — matching site icon
- `404.html` — themed not-found page
- `.nojekyll` — disables unnecessary Jekyll processing
