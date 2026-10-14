# NeuraAgentixLabs website

A responsive, static GitHub Pages website. Based on the original NeuraAgentixLabs starter (`index.html` and `styles.css`), preserving its editorial design language, scientific agent illustration, mission, and existing external links.

## Files

- `index.html` — complete single-page website with anchor navigation
- `styles.css` — responsive hybrid dark/light styling
- `script.js` — accessible mobile navigation, reveal animations, and automatic footer year
- `assets/favicon.svg` — custom vector favicon

## Preview locally

Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Deploy to GitHub Pages

1. In GitHub Desktop, clone `NeuraAgentixLabs/neuraagentixlabs.github.io`.
2. Copy the contents of this folder **into the root of the cloned repository** (not inside another nested folder).
3. Commit and push the changes.
4. In the GitHub repository, open **Settings → Pages**. Choose **Deploy from a branch**, branch `main`, folder `/ (root)` if not already configured.
5. Visit `https://neuraagentixlabs.github.io/` after Pages finishes deploying.

## Before publishing

- Confirm lab-lead biography and ORCID details.
- Replace the publications placeholder with verified citations when ready.
- Update project cards and link them to real public repositories as projects launch.
- Confirm email and external channel URLs.

The site uses Google Fonts when online and falls back to system fonts offline. It does not require a build process, npm, frameworks, or API keys. It respects reduced-motion preferences.
