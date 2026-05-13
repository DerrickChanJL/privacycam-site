# PrivacyCam Static Website

This folder is a complete static website for PrivacyCam. It does not need a server, database, or backend.

## Files

- `index.html`: product landing page
- `privacy.html`: App Store Connect Privacy Policy URL
- `terms.html`: Terms of Use URL for paywall and subscriptions
- `support.html`: App Store Connect Support URL
- `404.html`: fallback page for GitHub Pages
- `assets/site.css`: shared styling
- `assets/app-icon.png`: website icon

## Deploy Without A Server

Use GitHub Pages or Cloudflare Pages and publish this `docs` folder.

After deployment, use these URLs in App Store Connect:

```text
Privacy Policy URL: https://YOUR_DOMAIN/privacy.html
Support URL: https://YOUR_DOMAIN/support.html
Terms of Use URL: https://YOUR_DOMAIN/terms.html
```

Replace `YOUR_DOMAIN` with the public URL from GitHub Pages or Cloudflare Pages.
