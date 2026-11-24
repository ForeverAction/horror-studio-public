# Horror Story Studio

Public information and policy pages for the personal video-production automation behind What the Night Hides. This repository contains the website only.

- [Home](https://foreveraction.github.io/horror-studio-public/)
- [Privacy Policy](https://foreveraction.github.io/horror-studio-public/privacy.html)
- [Terms of Use](https://foreveraction.github.io/horror-studio-public/terms.html)

## GitHub Pages

Publish from `main` and `/(root)` using **Settings → Pages → Deploy from a branch**. The static site has no build step. Keep HTTPS enabled.

## Google Search Console

Add the deployed HTTPS homepage as a **URL-prefix** property. Choose HTML file verification, place the unmodified file from Search Console at the repository root, then select **Verify** after deployment. The owner may also use Search Console’s HTML meta tag method. URL-prefix verification covers the site path and does not grant DNS control of the GitHub Pages domain.

## OAuth branding

The site presents the application and its legal information. It has no OAuth callback, account form or integration with the production notebook. Keep OAuth credentials, private code, private media, and account records out of this public repository. For the separate Google review workflow, consult [Google’s brand verification requirements](https://developers.google.com/identity/protocols/oauth2/production-readiness/brand-verification).
