# WEB

Static site for GitHub Pages with the public links Apple asks for in App Store Connect.

## Files

- `index.html`: landing page
- `support.html`: support URL target
- `privacy.html`: privacy policy URL target
- `styles.css`: shared styles

## Publish on GitHub Pages

1. Push the repository to GitHub.
2. In GitHub, open `Settings` → `Pages`.
3. Set the source to the branch you want to publish from.
4. If you publish from the repo root, configure Pages to serve the `/WEB` folder if available in your workflow setup, or copy these files to the publish branch root.
5. Use the resulting URLs in App Store Connect:
   - Support URL: `https://<your-user>.github.io/<repo>/support.html`
   - Privacy Policy URL: `https://<your-user>.github.io/<repo>/privacy.html`

## Before publishing

- Replace `support@dumbcals.app` with your real support email.
- If you use a custom domain, update the URLs accordingly.
