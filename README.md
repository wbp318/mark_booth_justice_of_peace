# mark_booth_justice_of_peace

Campaign website and plan for Mark Booth — Justice of the Peace, Ward 2, Ouachita Parish, LA. Election: November 3, 2026.

- `index.html` — single-page campaign site (deploy to Cloudflare Pages)
- `campaign-plan.md` — campaign plan and timeline

## 🚀 LAUNCH TODAY — do these in order while Mark is here

### Step 1 — Content from Mark (~20 min, in Claude Code)
1. **Headshot**: take a photo of Mark now if he doesn't have one (good light, plain background, nice shirt). Save it as `images/mark-booth.jpg` in this folder.
2. **Bio**: ask Mark and fill in every `[placeholder]` in the About section of `index.html` — years in the parish, profession, wife's name, kids, church/community involvement, credentials.
3. **Disclaimer**: confirm the exact "Paid for by …" wording with Mark (footer of `index.html`).
4. **Email**: footer says `info@votemarkbooth.com` — if that won't exist yet, change it to an email Mark actually checks.

### Step 2 — Yard-sign form (~5 min)
1. Go to https://web3forms.com → enter Mark's email → copy the access key.
2. Paste it into the `access_key` hidden field in the form in `index.html` (replaces `YOUR_WEB3FORMS_ACCESS_KEY`).
3. Submit a test through the form after deploy; confirm the email arrives.

### Step 3 — Deploy to Cloudflare (~10 min, free)
1. Create/log into a Cloudflare account (free) at dash.cloudflare.com.
2. In the terminal here: type `! npx wrangler login` and approve in the browser.
3. Then tell Claude to deploy — or run: `npx wrangler pages deploy . --project-name votemarkbooth`
4. You get a live URL immediately: `https://votemarkbooth.pages.dev`. **The site is launched.**

### Step 4 — Domain (~10 min, ~$12/yr, optional today)
1. Cloudflare dashboard → Domain Registration → register `votemarkbooth.com` (Mark pays — campaign expense).
2. Workers & Pages → votemarkbooth project → Custom domains → add the domain.
3. Optional: Email Routing (free) → forward `info@votemarkbooth.com` to Mark's inbox.

### Step 5 — Final check before sharing the link (~5 min)
- [ ] Open the live URL on Mark's phone: photo shows, bio reads right, no `[placeholders]` left
- [ ] Test the yard-sign form; confirm Mark gets the email
- [ ] Mark posts the link on Facebook

### Deferred (fine to do later — placeholders already handle these)
- **Donations**: Mark opens an Anedot account (needs the campaign bank account) → paste the URL into the Donate button `href` in `index.html`, push to `main`. Until then the site says "coming soon / checks payable to Mark Booth Campaign."
- **Official Ward 2 map**: get it from the Clerk of Court, (318) 327-1444 (no digital version exists online). Save as `images/ward2-map.png` and swap for the OpenStreetMap embed.
- **Updates**: any push to `main` — Cloudflare redeploys automatically once connected. Or redeploy with the wrangler command in Step 3.

## After launch (ongoing)
- Check form submissions weekly; deliver requested signs
- Post endorsements/photos as they come in (edit `index.html`, push)
- See `campaign-plan.md` for the full 11-week campaign timeline
