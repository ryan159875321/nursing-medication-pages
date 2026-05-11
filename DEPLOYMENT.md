# GitHub Pages Deployment

This folder is ready to publish as a free GitHub Pages site.

## Cheapest first step

1. Push the project to GitHub.
2. In the GitHub repository, open **Settings > Pages**.
3. Set **Source** to **Deploy from a branch**.
4. Choose the default branch, usually `main`.
5. Choose the `/docs` folder.
6. Save.

GitHub will publish the site at a URL like:

```text
https://<github-username>.github.io/nursing-medication-app/
```

Use these app metadata URLs once the site is live:

```text
Support URL: https://<github-username>.github.io/nursing-medication-app/support.html
Privacy Policy URL: https://<github-username>.github.io/nursing-medication-app/privacy.html
Terms URL: https://<github-username>.github.io/nursing-medication-app/terms.html
```

Update `app.json` with those URLs before store submission.

## Before public launch

- Replace every `replace-before-launch@example.com` placeholder with a real support email.
- Review the privacy policy and terms for the final data model.
- Get clinical/educational review of question content and explanations.
- Consider legal review before commercial release.

## Later custom domain

When you buy a domain, add a `CNAME` file in this folder containing the domain:

```text
nursingmedication.co.uk
```

Then configure DNS with your domain provider to point the domain at GitHub Pages.
