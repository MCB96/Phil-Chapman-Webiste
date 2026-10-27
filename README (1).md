# Phil Chapman Aerial Services website

A static, four-page website for Phil Chapman Aerial Services in Nottingham. It uses HTML, CSS and vanilla JavaScript and is designed to publish from the repository root on GitHub Pages.

## Pages and assets

- `index.html` — homepage
- `about.html` — business background
- `services.html` — service descriptions
- `contact.html` — contact details and email-draft form
- `style.css`, `script.js` — shared presentation and interactions
- `phil-chapman-aerial-services-logo.svg` — existing wordmark asset
- `aerial-installation-hero.png` — illustrative AI-generated hero image, not a photograph of Phil or a completed company job
- `assets/work/README.md` — how to add genuine work photographs

## Preview locally

From this folder, run:

```sh
python -m http.server 8000
```

Then open <http://localhost:8000>. Keep the terminal open while previewing.

## Enquiry form

The form validates required fields and opens a prefilled `mailto:` draft. It does not submit to a server and cannot confirm delivery. A direct email link is displayed as a fallback. To receive web submissions without relying on the visitor's mail app, connect a form service or backend and update the form handling deliberately; no external form service is configured.

## Photographs to request from Phil

The work gallery currently contains clearly labelled placeholders, not stock photos or claimed customer work. Ask Phil for approved, original images such as:

1. A Freeview aerial installed on a local home.
2. A satellite dish installation or repair.
3. A television installation or wall mount.

Place optimised copies in `assets/work/`, use descriptive names such as `freeview-aerial-installation.jpg`, then replace the matching placeholder in `index.html` with an `img` element and meaningful alt text. Obtain permission to use each image and avoid showing customer-identifying details without consent.

The hero image is illustrative and AI-generated. Replace it with a genuine, approved photo if one becomes available; do not describe it as work performed by Phil.

## Publish on GitHub Pages

In the repository, open **Settings → Pages** and select **Deploy from a branch**, branch `main`, folder `/ (root)`. Keep links and asset paths relative so the site works under the repository path `/Phil-Chapman-Webiste/`.
