# Paul Blackwood Portfolio

A responsive, single-page portfolio website built with HTML, CSS, and a small amount of JavaScript. It is designed for free hosting with GitHub Pages.

## Files

- `index.html` — website content and structure
- `styles.css` — responsive visual design
- `script.js` — mobile navigation and current footer year
- `assets/` — place your portfolio images here

## Preview locally

Open `index.html` in a web browser. The Google Fonts used by the site require an internet connection; system fonts will be used if they are unavailable.

## Publish with GitHub Pages

1. Sign in to GitHub and create a new **public** repository named `paulblackwood.github.io` (if your GitHub username is `paulblackwood`; otherwise use `USERNAME.github.io`).
2. Upload the contents of this folder to the repository's root. Make sure `index.html`, `styles.css`, and `script.js` are at the root level, not inside another nested folder.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and `/ (root)`, then save.
6. GitHub will publish the site at `https://USERNAME.github.io/`.

## Connect PaulBlackwood.com

After the GitHub Pages site is working:

1. In **Settings → Pages → Custom domain**, enter `PaulBlackwood.com` and save.
2. At your domain registrar, configure the DNS records using the exact values GitHub Pages shows in its documentation/settings. Typically this includes GitHub Pages A records for the apex domain and a `www` CNAME pointing to `USERNAME.github.io`.
3. Allow time for DNS to update, then enable **Enforce HTTPS** in GitHub Pages settings.

Do not change existing domain email/MX records when configuring website DNS.

## Before going live

- Replace the illustrated portfolio category graphics with screenshots or images of Paul's actual work.
- Confirm all dates, role titles, and contact details.
- Add a résumé PDF if desired, then link it from the hero or experience section.
- If showing work created for past employers or clients, confirm that it is approved for public display and remove confidential information.
- Consider adding descriptive alt text to portfolio images when replacing the CSS illustrations with real images.

## Editing content

Most page text is in `index.html`. Colors, typography, spacing, and mobile layout are in `styles.css`. No build tools or package installation are required.
