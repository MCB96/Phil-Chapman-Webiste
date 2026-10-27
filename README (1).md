# Phil Chapman Aerial Services website

A static four-page website for Phil Chapman Aerial Services in Nottingham. It uses HTML, CSS and vanilla JavaScript and is intended to publish from the repository root on GitHub Pages.

## Pages and assets

- `index.html` — homepage with Phil’s supplied photograph, services and Yell reviews
- `about.html` — business background and customer promise
- `services.html` — six verified service descriptions
- `contact.html` — contact details and email-draft form
- `style.css`, `script.js` — shared styles and interactions
- `phil-chapman-aerial-services-logo.svg` — existing logo asset
- `assets/images/phil-chapman-van.webp` — optimised display copy of the supplied photo
- `assets/images/phil-chapman-van-original.png` — untouched supplied original
- `assets/work/README.md` — guidance for adding genuine job photos later

The AI-generated aerial-installer image used by an earlier draft has been removed. The current site uses Phil’s actual supplied photo and does not show invented completed installations.

## Review attribution

The four review texts on the homepage were supplied for this project and are reproduced with their titles, reviewer names, dates and wording. They are attributed to Yell, with a link to the Yell business listing. Yell’s security page prevented confirming individual review-specific URLs, so no individual review URL is implied.

## Business details to confirm

The current business website states the company was established in 1961, is family-run and has over 25 years of aerial installation experience. Please ask Phil to confirm the time-sensitive “over 25 years” wording before publication.

## Preview locally

From this folder, run:

```sh
python -m http.server 8000
```

Then open <http://localhost:8000>. Keep the terminal open while previewing.

## Enquiry form and privacy

The contact form validates its required fields and opens a prefilled `mailto:` draft. It does not send information to a website server and cannot confirm delivery. A direct email link remains visible if the visitor’s email app does not open. The site has no analytics or tracking scripts. If a server-backed form or tracking is added later, review what data is collected and update the privacy information accordingly.

## Photographs

The supplied image of Phil and his van was preserved as a PNG original and converted to a smaller WebP for display. It is shown without cropping so Phil and the van branding remain visible. No completed-job photos were supplied, so there is no work gallery on the site. If Phil provides approved job photos, place them in `assets/work/` and add a gallery with descriptive alt text. See `assets/work/README.md`.

## Publish with GitHub Pages

In the repository, open **Settings → Pages** and select **Deploy from a branch**, branch `main`, folder `/ (root)`. The site uses relative page and asset paths so it works beneath `/Phil-Chapman-Webiste/`.