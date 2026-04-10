# RidgeLine Privacy Policy Site

This folder contains a standalone static privacy policy page that can be published from a separate public repository.

## What to do

1. Create a new **public** GitHub repository named `ridgeline-privacy-policy`.
2. Copy the files from this folder into the new repository.
3. Commit and push to GitHub.
4. GitHub Actions will deploy the site automatically to the `gh-pages` branch.
5. In the repo settings, go to **Pages** and set the source to the `gh-pages` branch.
6. The page will be available at:
   - `https://<your-github-username>.github.io/ridgeline-privacy-policy/`

## Example URL

If your username is `giogonz318`, the page URL will be:

`https://giogonz318.github.io/ridgeline-privacy-policy/`

## Google Play Console

Use the public page URL in Play Console under **Policy > App content > Privacy policy**.

## Publish commands

Run these commands from inside the `privacy-policy-site` folder:

```powershell
cd privacy-policy-site
git init
git add .
git commit -m "chore: add RidgeLine privacy policy site"
git branch -M main
git remote add origin https://github.com/<your-github-username>/ridgeline-privacy-policy.git
git push -u origin main
```

Then open GitHub and enable Pages for the `gh-pages` branch.

## Notes

- This repo should contain only the privacy policy site, not your app source code.
- Keeping the privacy policy in a separate public repo keeps your app repo private and hidden.
