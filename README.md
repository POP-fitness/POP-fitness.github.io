# progressoverpassion.com

Company site, privacy policy, and terms of use for **Progress Over Passion**
(PoP Fitness), published via GitHub Pages at https://progressoverpassion.com.

This repo is public only because GitHub Pages requires it on a free plan. It
holds no application code — the iOS app and backend live in a private repo.

## Don't edit these files here

The source of truth is `docs/legal/` in the app repo, so the published pages
stay reviewable alongside the code that determines what they describe. Edit
there, then copy across and push:

```bash
cp ../progressfitness/docs/legal/{index,privacy,terms}.html \
   ../progressfitness/docs/legal/style.css .
git add . && git commit -m "Update legal pages" && git push
```

`CNAME` is what binds the custom domain to this repo — do not delete it.
