# GitHub Pages Deployment

This repository is ready to publish as a free GitHub Pages site for MedMath Trainer.

## Cheapest first step

1. Push the project to GitHub.
2. In the GitHub repository, open **Settings > Pages**.
3. Set **Source** to **Deploy from a branch**.
4. Choose the default branch, usually `main`.
5. Choose the repository root folder.
6. Save.

GitHub will publish the site at a URL like:

```text
https://ryan159875321.github.io/nursing-medication-pages/
```

Use these app metadata URLs once the site is live:

```text
Support URL: https://ryan159875321.github.io/nursing-medication-pages/support.html
Privacy Policy URL: https://ryan159875321.github.io/nursing-medication-pages/privacy.html
Terms URL: https://ryan159875321.github.io/nursing-medication-pages/terms.html
```

Update `app.json` with those URLs before store submission.

## Before public launch

- Confirm `support@medmathtrainer.com` forwards correctly through Cloudflare Email Routing.
- Review the privacy policy and terms for the final data model.
- Get clinical/educational review of question content and explanations.
- Consider legal review before commercial release.

## Later custom domain

To use `medmathtrainer.com` for these pages later, add a `CNAME` file in this repository containing the domain:

```text
medmathtrainer.com
```

Then configure DNS in Cloudflare to point the domain at GitHub Pages.
