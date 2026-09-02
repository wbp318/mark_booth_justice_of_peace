# mark_booth_justice_of_peace

Campaign website and plan for Mark Booth — Justice of the Peace, Ward 2, Ouachita Parish, LA. Election: November 3, 2026.

- `index.html` — single-page campaign site
- `campaign-plan.md` — campaign plan and timeline
- `facebook-ads/` — Facebook ads strategy ([strategy.md](facebook-ads/strategy.md)), ready-to-paste ad copy ([ad-copy.md](facebook-ads/ad-copy.md)), and step-by-step setup for ad authorization + Pixel ([setup-instructions.md](facebook-ads/setup-instructions.md))

**Live site:** https://votemarkbooth.com (GitHub Pages, deploys automatically on every push to `main`; wbp318.github.io/mark_booth_justice_of_peace redirects here)

## ✅ Done (as of Aug 26, 2026)
- [x] Site built, bio and headshot added, launched on GitHub Pages
- [x] Repo public, HTTPS enabled

## 📋 Remaining checklist

### Contact / yard-sign requests
- [x] `info@votemarkbooth.com` on the site (donate section, sign section, footer)
- [x] Yard-sign web form removed Sept 1, 2026 (spam) — replaced with an email CTA to info@. Web3Forms account (wbp71270@gmail.com) is unused; delete the form there if you like
- [ ] Once Mark verifies the Cloudflare destination, send a test email to info@ and confirm it lands in the campaign Gmail

### Content still needed from Mark
- [x] Family photo added to Meet Mark section (color-corrected, Sept 1, 2026)
- [ ] Confirm exact disclaimer wording with Mark — site and ad docs now all use **"Paid for by Mark Booth Campaign"** (footer previously said "the Mark Booth Campaign")
- [ ] Wife's name / any bio details Mark wants added or corrected after reading the live page

### Domain (~$12/yr, recommended before printing signs)
- [x] Register `votemarkbooth.com` (Cloudflare, campaign card — Aug 30, 2026)
- [x] DNS: A records + `www` CNAME added in Cloudflare (DNS only / grey cloud)
- [x] GitHub Pages custom domain set to votemarkbooth.com; HTTPS enforced (cert issued Aug 30, 2026 — http:// redirects to https://)
- [x] Cloudflare Email Routing activated; `info@` rule + destination added — **waiting on Mark to click the verification email in the campaign Gmail** (then send a test to info@votemarkbooth.com)
- [x] Registrar email forwarding: `info@votemarkbooth.com` → campaign Gmail
- [ ] Put the domain (not the github.io URL) on all printed material

### Donations
- [x] Open campaign bank account (needed before accepting online donations)
- [x] ~~Anedot~~ dropped Sept 2, 2026 (too much hassle — required an EIN). Going with a simple Venmo link instead.
- [ ] **Get Mark's Venmo username** → Claude replaces `VENMO-HANDLE` (2 places in `index.html`: button href + the "@" text). Button opens `https://venmo.com/u/<username>`. Tip: set the Venmo profile to a business/campaign name so donors see "Mark Booth Campaign", and keep a log of donor name/address from the payment notes for compliance.

### Site polish (Claude can do anytime)
- [x] Headshot compressed to JPG (Sept 1, 2026); Open Graph/Twitter share image + favicon added
- [ ] Official Ward 2 boundary map from the Clerk of Court, (318) 327-1444 (no digital copy online) → save as `images/ward2-map.png`, replace the OpenStreetMap embed
- [ ] Update hero tagline/values with any wording Mark prefers after reviewing

### Compliance (Mark's responsibility — see campaign-plan.md §2)
- [ ] Verify voter-registration deadlines on the site against sos.la.gov: site says Oct 5 (mail/in person) and Oct 13 (online); Louisiana's rule is 30 / 20 days before the election, which computes to Oct 4 / Oct 14 — confirm which the SOS publishes
- [ ] Qualify for the ballot with the Clerk of Court during the official qualifying period (verify dates with the Secretary of State)
- [ ] Louisiana Ethics Administration campaign finance registration + reports on schedule
- [ ] "Paid for by" disclaimer on every sign, push card, ad, and the site (site already has it)

### Promotion (see campaign-plan.md for the full timeline — key items)
- [ ] Facebook page "Mark Booth for Justice of the Peace" — matters more than the website for a local race; post the site link
- [ ] Order yard signs + push cards NOW (print shops back up before elections) — wait only for the domain to print it on them
- [ ] List of 50–100 Ward 2 people Mark knows → first sign locations
- [ ] 3–5 endorsements from well-known Ward 2 figures

## 📣 Facebook ads strategy (summary — full plan in [`facebook-ads/strategy.md`](facebook-ads/strategy.md))

**Budget $300–500. Goal: name recognition + turnout in Ward 2. Nothing else.**

| Phase | Dates | Spend | Runs |
|---|---|---|---|
| A. Warm-up | Sept 15–30 | ~$50 ($3–5/day) | Boost "why I'm running" video to Ward 2 ZIPs |
| B. Name recognition | Oct 1–19 | ~$150 ($8–10/day) | Face + name + office ads, optimize for reach |
| C. Early voting | Oct 20–27 | ~$140 ($15–20/day) | "Early voting is open" with locations/hours |
| D. GOTV | Oct 28–Nov 3 | ~$150 ($20–25/day) | "Tuesday is Election Day," peak Nov 2–3 |
| Reserve | Dec 5 runoff | $50–100 | Rerun C+D if there's a runoff |

**Setup — start now, authorization takes days:**
- [ ] Create the Facebook Page (Politician category), post 3–4 things
- [ ] **Meta political-ad authorization — start today, a code is MAILED (3–7 days):** https://www.facebook.com/id → Confirm identity → "Ads about social issues, elections or politics" → upload ID → enter a US mailing address → enter the code when the letter arrives. Turn on 2FA. Full steps: [setup-instructions.md §1](facebook-ads/setup-instructions.md)
- [ ] Create disclaimer "Paid for by Mark Booth Campaign" in Ads Manager (can do while waiting for the letter)
- [ ] Payment method = campaign bank account card; download invoices monthly for Ethics reports
- [ ] Get Ward 2 ZIP codes / pin radius from the official boundary map — **no paid ads until this is known**
- [ ] **Meta Pixel (instant, nothing mailed):** https://business.facebook.com/events_manager → Connect Data Sources → Web → name it → copy the 15–16 digit Pixel ID → paste it to Claude, who adds it to `index.html`. Full steps: [setup-instructions.md §2](facebook-ads/setup-instructions.md)

**Targeting:** Ward 2 ZIPs only, ages 30–65+, Facebook + Instagram Feed placements only. Facebook can't target by voter file or "Ward 2" — geography is all you get.

**Creative:** every ad = Mark's face + "MARK BOOTH — Justice of the Peace, Ward 2 — Nov 3." Phone video beats polished. Never negative. Five ready-to-paste ads in [`facebook-ads/ad-copy.md`](facebook-ads/ad-copy.md).

**Measure:** reach and frequency (want 3–6 by Nov 3), CPM ($5–12 normal). Ignore clicks. Reply to every comment.

## After launch (ongoing)
- Check info@votemarkbooth.com for yard-sign requests (form removed Sept 1, 2026 due to spam; replaced with email CTA); deliver requested signs
- Post endorsements/photos as they come in (edit `index.html`, push to `main` — the site redeploys automatically)
- Follow the weekly rhythm in `campaign-plan.md` §4
