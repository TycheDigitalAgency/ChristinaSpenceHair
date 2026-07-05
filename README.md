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

## What's not yet built
Only the **homepage** is done. The nav links to the other pages (New Client, Services, Contact, My Story, Expectations, Extensions Care, Products, Hair Topics, Home Care Guide) are wired up but those pages don't exist yet — let me know if you want those built out next.
