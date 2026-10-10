# App Policies

Privacy policies and terms and conditions for all my apps, kept in one place and hosted with GitHub Pages.

This repo is separate from my main website, so the policies here do not affect the site's own policies.

## Live links

Base URL: `https://YOUR-USERNAME.github.io/REPO-NAME/`

| App | Privacy Policy | Terms & Conditions |
| --- | --- | --- |
| App One | [Privacy Policy](https://YOUR-USERNAME.github.io/REPO-NAME/app-one/privacy-policy.html) | [Terms](https://YOUR-USERNAME.github.io/REPO-NAME/app-one/terms-and-conditions.html) |
| App Two | [Privacy Policy](https://YOUR-USERNAME.github.io/REPO-NAME/app-two/privacy-policy.html) | [Terms](https://YOUR-USERNAME.github.io/REPO-NAME/app-two/terms-and-conditions.html) |

Use these links in the Play Store / App Store listings and inside the apps.

## Folder structure

```
.
├── README.md
├── index.html                      # landing page listing all apps
├── app-one/
│   ├── privacy-policy.html
│   └── terms-and-conditions.html
└── app-two/
    ├── privacy-policy.html
    └── terms-and-conditions.html
```

## How to add a new app

1. Copy an existing app folder (for example `app-one`) and rename it, such as `app-three`.
2. Open both files inside the new folder and replace the placeholders:
   - `[APP NAME]`
   - `[YOUR NAME / COMPANY NAME]`
   - `[YOUR EMAIL]`
   - `[DATE]`
   - `[YOUR CITY, STATE]`
3. Edit the text so it matches what the app really collects and does.
4. Add a new card for the app in `index.html`.
5. Add a row for the app in the table above.
6. Commit and push:

   ```bash
   git add .
   git commit -m "Add policies for App Three"
   git push
   ```

The site updates automatically within a minute or two.

## Hosting (GitHub Pages)

1. Go to **Settings → Pages**.
2. Under **Source**, choose **Deploy from a branch**.
3. Select branch `main` and folder `/ (root)`, then click **Save**.

Optional: to use a custom subdomain such as `policies.yourdomain.com`, enter it under **Custom domain** and add a `CNAME` DNS record pointing to `YOUR-USERNAME.github.io`.

## Updating a policy

When you change a policy, update the "Last updated" date at the top of that page before you push.

## Disclaimer

These documents are templates and are not legal advice. If an app handles payments, children's data or health data, have the final text reviewed by a legal professional.

## Contact

Email: your-email@example.com
