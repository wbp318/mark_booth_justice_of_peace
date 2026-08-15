# mark_booth_justice_of_peace

Campaign website and plan for Mark Booth — Justice of the Peace, Ward 2, Ouachita Parish, LA. Election: November 3, 2026.

- `index.html` — single-page campaign site (deploy to Cloudflare Pages)
- `campaign-plan.md` — campaign plan and timeline

## Deploy (Cloudflare Pages)
1. Cloudflare dashboard → Workers & Pages → Create → Pages → Connect to Git → select this repo
2. No build command; output directory `/`
3. Add custom domain (e.g. votemarkbooth.com)

## Before launch
- Replace bio placeholders and `images/mark-booth.jpg` headshot in `index.html`
- Add a Web3Forms access key to the yard-sign form
- Add the Anedot (or similar) donation URL to the Donate button
