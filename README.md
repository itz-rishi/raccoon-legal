# Raccoon — Anonymous Devs Website

A single-page website for Raccoon, a Discord server companion by Anonymous Devs. It includes:
- Interactions Endpoint URL guidance
- Linked Roles Verification URL guidance
- Terms of Service
- Privacy Policy

## Publish with GitHub Pages

1. Create a new public GitHub repository, for example `raccoon-legal`.
2. Upload `index.html` to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Choose branch `main` and folder `/ (root)`, then save.
6. Wait for GitHub Pages to publish the site. The URL will look like:
   `https://YOUR-GITHUB-USERNAME.github.io/raccoon-legal/`

## Discord Developer Portal fields

After the page is published, use the same page with section anchors:

- **Terms of Service URL:** `https://YOUR-GITHUB-USERNAME.github.io/raccoon-legal/#terms`
- **Privacy Policy URL:** `https://YOUR-GITHUB-USERNAME.github.io/raccoon-legal/#privacy`
- **Interactions Endpoint URL:** Leave blank for a normal Discord Gateway bot (such as a typical `discord.py` bot).
- **Linked Roles Verification URL:** Leave blank unless you have implemented a real Linked Roles verification endpoint.

Replace `YOUR-GITHUB-USERNAME` and `raccoon-legal` with your actual GitHub username and repository name.

## Important before publishing

Review the Terms and Privacy Policy and make sure they accurately match Raccoon's actual commands, data storage, logging, hosting, and deletion practices. Add a real support/contact link. The page is informational; it does not implement Discord interaction or Linked Roles endpoints.
