# Christina Spence Hair — Homepage Clone

A static rebuild of the christinaspence.hair homepage, matching layout, copy, colors, and typography from the live Zyro/Hostinger site.

## Design tokens pulled from the live site
- Display font: **Italiana**
- Body font: **DM Sans**
- Button/nav font: **Raleway**
- Dark accent / button color: `#3F3B34`
- Body text: `#1D1E20`
- Muted/taupe: `#7E796C`
- Light section background: `#F1F1F1`

## Images are hotlinked (by design)
Since Hostinger doesn't allow exporting/downloading the media library, the image `src` attributes point directly at the live site's CDN (`assets.zyrosite.com`). As long as christinaspence.hair stays live on Hostinger, these images will keep loading correctly here — no extra work needed. If that site ever goes down or gets rebuilt, these image links would break and need to be re-sourced (e.g. re-shot photos, or a screen-recorded/re-saved copy of each image).

## Deploying to GitHub Pages
1. Create a new repo (e.g. `christina-spence-hair-site`) and push these files to the root (or a `/docs` folder).
2. In the repo's **Settings → Pages**, set the source branch and folder.
3. GitHub will publish it at `https://<username>.github.io/<repo-name>/`.
4. To use the real domain (`christinaspence.hair`), add a `CNAME` file with that domain in it, and point the domain's DNS at GitHub Pages.

## What's built
All 10 pages from the live site's nav are now built, using the real live URLs as filenames so links match what you shared:
- `index.html` — Home
- `new-client.html` — New Client
- `hair-extension-services.html` — Services
- `contact-christina-spence-hair.html` — Contact
- `about-christina.html` — My Story
- `what-to-expect.html` — Expectations
- `hair-extension-care-guide.html` — Extensions Care
- `recommended-hair-products.html` — Products
- `hair-education-and-extension-topics.html` — Hair Topics
- `home-hair-care-guide-.html` — Home Care Guide

Plus two placeholder legal pages (`privacy-policy.html`, `terms-of-service.html`) so the footer links resolve instead of 404ing — these have placeholder text only, not the real policy language, since that wasn't part of the requested pages.

### Real links wired in
- **Book Now / Ready to Book** buttons → the real Google Calendar booking link (`calendar.app.google/LgVL6fd3cWTwTrZi7`)
- **Book Here** (footer) → the real Google Calendar link (`calendar.app.google/Bt7UDayW3P3kuvLn8`)
- **Get Yours Here** (Products page) → the real affiliate link (`usphair.com/aff/christinashaircare`)
- **Request an Appointment** → the Contact page

### Not fully built out
The **Hair Topics** page lists the 4 real blog post titles/excerpts as teaser cards, but the individual article pages themselves aren't built (that's a bigger job — happy to do it if you want). The cards currently don't link anywhere rather than pointing at a broken page.
