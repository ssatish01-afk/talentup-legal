# TalentUp Legal Site

A static GitHub Pages-ready site for TalentUp Applications.

## Publish with GitHub Pages

1. Create a new **public** GitHub repository, for example `talentup-legal`.
2. Upload all files and folders from this package to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch **main** and folder **/(root)**, then save.
6. GitHub will display the public Pages URL.

The Privacy Policy will be available at:

`https://YOUR-GITHUB-USERNAME.github.io/talentup-legal/privacy-policy/`

## Optional branded subdomain

Recommended custom domain:

`talentup.satsuntech.com`

In GitHub **Settings → Pages → Custom domain**, enter the subdomain and save.  
At GoDaddy DNS, add a CNAME record:

- Type: CNAME
- Name: talentup
- Value: YOUR-GITHUB-USERNAME.github.io
- TTL: default

After DNS verification, enable **Enforce HTTPS**.

The branded Privacy Policy URL will then be:

`https://talentup.satsuntech.com/privacy-policy/`
