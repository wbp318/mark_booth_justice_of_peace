# mark_booth_justice_of_peace

Campaign website and plan for Mark Booth — Justice of the Peace, Ward 2, Ouachita Parish, LA. Election: November 3, 2026.

- `index.html` — single-page campaign site
- `campaign-plan.md` — campaign plan and timeline

**Live site:** https://wbp318.github.io/mark_booth_justice_of_peace/ (GitHub Pages, deploys automatically on every push to `main`)

## ✅ Done (as of Aug 26, 2026)
- [x] Site built, bio and headshot added, launched on GitHub Pages
- [x] Repo public, HTTPS enabled

## 📋 Remaining checklist

### Campaign Gmail is set up — do these now
- [ ] Replace `info@votemarkbooth.com` contact links in `index.html` (donate section + footer) with the Gmail — or keep info@ and forward it (see Domain step)
- [ ] Create free Web3Forms access key at https://web3forms.com using the Gmail; paste into the yard-sign form's `access_key` field (currently `YOUR_WEB3FORMS_ACCESS_KEY` — **the form does not send email until this is done**)
- [ ] Submit a test through the live form; confirm the email arrives in the Gmail

### Content still needed from Mark
- [ ] Family pictures — add a photo section to the site
- [ ] Confirm exact "Paid for by Mark Booth Campaign" disclaimer wording (footer + all future printed material)
- [ ] Wife's name / any bio details Mark wants added or corrected after reading the live page

### Domain (~$12/yr, recommended before printing signs)
- [ ] Register `votemarkbooth.com` (Cloudflare or Porkbun; Mark pays — campaign expense)
- [ ] DNS: A records `185.199.108.153 / .109. / .110. / .111.153` for apex; CNAME `www` → `wbp318.github.io`
- [ ] GitHub repo → Settings → Pages → set custom domain (Claude can do this via `gh`)
- [x] Registrar email forwarding: `info@votemarkbooth.com` → campaign Gmail
- [ ] Put the domain (not the github.io URL) on all printed material

### Donations
- [x] Open campaign bank account (needed before accepting online donations)
- [ ] Set up Anedot (or similar) → paste URL into the Donate button `href` in `index.html`
- [ ] Until then the site correctly says "coming soon / checks payable to Mark Booth Campaign"

### Site polish (Claude can do anytime)
- [ ] Compress `images/mark-booth-headshot.png` (currently 1.8 MB — slow on phones)
- [ ] Official Ward 2 boundary map from the Clerk of Court, (318) 327-1444 (no digital copy online) → save as `images/ward2-map.png`, replace the OpenStreetMap embed
- [ ] Update hero tagline/values with any wording Mark prefers after reviewing

### Compliance (Mark's responsibility — see campaign-plan.md §2)
- [ ] Qualify for the ballot with the Clerk of Court during the official qualifying period (verify dates with the Secretary of State)
- [ ] Louisiana Ethics Administration campaign finance registration + reports on schedule
- [ ] "Paid for by" disclaimer on every sign, push card, ad, and the site (site already has it)

### Promotion (see campaign-plan.md for the full timeline — key items)
- [ ] Facebook page "Mark Booth for Justice of the Peace" — matters more than the website for a local race; post the site link
- [ ] Order yard signs + push cards NOW (print shops back up before elections) — wait only for the domain to print it on them
- [ ] List of 50–100 Ward 2 people Mark knows → first sign locations
- [ ] 3–5 endorsements from well-known Ward 2 figures

## After launch (ongoing)
- Check form submissions weekly; deliver requested signs
- Post endorsements/photos as they come in (edit `index.html`, push to `main` — the site redeploys automatically)
- Follow the weekly rhythm in `campaign-plan.md` §4
