# mark_booth_justice_of_peace

Campaign website and plan for Mark Booth — Justice of the Peace, Ward 2, Ouachita Parish, LA. Election: November 3, 2026.

- `index.html` — single-page campaign site (deploy to Cloudflare Pages)
- `campaign-plan.md` — campaign plan and timeline

## Deploy (Cloudflare Pages)
1. Cloudflare dashboard → Workers & Pages → Create → Pages → Connect to Git → select this repo
2. No build command; output directory `/`
3. Add custom domain (e.g. votemarkbooth.com)

## Launch Plan

### Week 1 — Content & accounts (needs Mark)
- [ ] Get headshot from Mark → save as `images/mark-booth.jpg` (square crop, ≥600px)
- [ ] Get bio details from Mark → replace all `[placeholders]` in the About section of `index.html`
- [ ] Mark opens an Anedot account (needs campaign bank account) → paste donation URL into the Donate button `href`
- [ ] Create a free Web3Forms account → paste access key into the yard-sign form's hidden field, test a submission
- [ ] Confirm final campaign disclaimer wording with Mark ("Paid for by …")

### Week 2 — Domain & deploy
- [ ] Register domain (votemarkbooth.com or similar, ~$12/yr) via Cloudflare Registrar
- [ ] Cloudflare dashboard → Workers & Pages → Pages → Connect to Git → this repo (no build command, output `/`)
- [ ] Attach custom domain; verify SSL is active
- [ ] Set up email forwarding (Cloudflare Email Routing, free): info@votemarkbooth.com → Mark's inbox; update the footer address if different
- [ ] Test on phone + desktop: nav links, form submission, donate link, all voting-info links

### Launch day
- [ ] Final proofread (names, dates, phone numbers)
- [ ] Verify Ouachita-specific voting details (early voting site/hours, registrar info) against sos.la.gov before going live
- [ ] Mark announces the site on his Facebook page; ask family/supporters to share
- [ ] Add the URL to push cards and yard-sign artwork before printing

### After launch
- [ ] Check form submissions weekly; deliver requested signs
- [ ] Post updates as endorsements/photos come in (edit `index.html`, push to `main` — Cloudflare redeploys automatically)
