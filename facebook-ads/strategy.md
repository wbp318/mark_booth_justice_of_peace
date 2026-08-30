# Facebook Ads Strategy — Mark Booth for Justice of the Peace, Ward 2

**Budget:** $300–500 total (from campaign-plan.md §2). Everything below fits in that.
**Goal:** name recognition + turnout among Ward 2 voters. Nothing else. JP is a down-ballot race; the ad's only job is to make "Mark Booth" a name voters recognize on the ballot and remind them to vote.
**Owner:** whoever manages the Facebook page (Meta Ads Manager on the page).

---

## 0. Do this week (setup takes days — don't wait until October)

Political ads on Facebook require authorization **before** the first ad runs. The process takes 1–5 business days.

1. **Create the Facebook Page** "Mark Booth for Justice of the Peace" (category: Politician). Profile photo = headshot; cover = campaign colors + "Ward 2 · Nov 3". Post 3–4 things before running any ad so the page doesn't look empty when people click through.
2. **Get authorized to run ads about elections** — https://www.facebook.com/id — the person running ads (Mark, or you as page admin) uploads a government ID and confirms a US mailing address. Meta mails a code to that address; this is the slow part.
3. **Create the disclaimer** in Ads Manager → Accounts → Disclaimers: **"Paid for by Mark Booth Campaign"** (match the exact wording used on signs/site once Mark confirms it — README "Content still needed" item). Every political ad must carry this; ads are also archived publicly in the Meta Ad Library for 7 years.
4. **Set up Meta Ads Manager + payment method** (campaign debit card from the new bank account — it's a campaign expense and must appear on Louisiana Ethics reports).
5. **Install the Meta Pixel on the website** — optional but cheap. Lets you retarget people who visited the site. Ask Claude to add it to `index.html` once you have the Pixel ID.
6. **Ward boundary.** Facebook cannot target by voter registration or by "Ward 2." It can only do geography (ZIP, city, or a pin + radius). Once the official Ward 2 map is in hand (Clerk of Court, 318-327-1444), list the ZIP codes / drop pins that cover the ward. Until then: **do not run paid ads** — you'd pay to reach people who can't vote for Mark.

---

## 1. Targeting

Meta removed most detailed targeting for political ads. What's still available and what to use:

| Setting | Use |
|---|---|
| **Location** | ZIP codes covering Ward 2 (fill in after map): `_____, _____, _____`. Or drop pins with 1–3 mile radius. Choose "People living in this location," not "recently in." |
| **Age** | 30–65+. Under-30 turnout in a JP race is negligible; every dollar on them is wasted. |
| **Gender** | All |
| **Detailed targeting** | Leave blank (mostly unavailable for political ads anyway) |
| **Placements** | Facebook Feed + Instagram Feed only. Turn OFF Audience Network, Reels, Stories, Messenger — they burn budget on low-intent impressions. |
| **Custom audiences (later)** | Website visitors (Pixel), people who engaged with the page, and an uploaded list of the 50–100 personal-contact emails/phones from the campaign list. Then a 1% **Lookalike** of page engagers restricted to the Ward 2 ZIPs. |

Expect the Ward 2 audience to be small — roughly 10,000–30,000 people on Facebook depending on the ZIPs. That's good: a small audience means the same voters see Mark's face 5–10 times, which is what builds recognition.

---

## 2. Phases and budget

| Phase | Dates | Daily | Total | Objective | What runs |
|---|---|---|---|---|---|
| **A. Warm-up** | Sept 15 – Sept 30 | $3–5 | ~$50 | Engagement (video views) | Boost the "Why I'm running" video and the intro post to Ward 2 ZIPs. Cheap, grows the page so October ads have social proof (likes/comments). |
| **B. Name recognition** | Oct 1 – Oct 19 | $8–10 | ~$150 | Reach (frequency cap ~2 per 7 days) | Ads 1, 2, 3 in rotation. Photo of Mark + name + office + one line. Goal: everyone in the ZIPs sees the name 3–5 times. |
| **C. Early voting** | Oct 20 – Oct 27 | $15–20 | ~$140 | Reach | Ad 4 ("Early voting is open — vote Mark Booth"). Hours/locations in the ad. |
| **D. GOTV** | Oct 28 – Nov 3 | $20–25 | ~$150 | Reach | Ad 5 ("Tuesday is Election Day"). Highest budget on Nov 2–3. Polling-place lookup link. |
| **Reserve** | Runoff Dec 5 | — | keep $50–100 | | If there's a runoff, rerun Phase C/D ads for the runoff dates. Turnout collapses in runoffs — this is where ads are most cost-effective. |

Total ≈ **$490** with reserve. Scale down proportionally if funds are short; if you have to cut, cut Phase A and B, never D.

**Campaign structure in Ads Manager:** one Campaign per phase, one Ad Set (the Ward 2 audience), 2–3 Ads inside it. Let Meta rotate the ads; after 3–4 days, turn off the worst performer.

---

## 3. Creative rules

- **Face + name + office, every single ad.** The headshot or a photo of Mark with a neighbor/at a sign. No stock images, no logos-only.
- **Text on the image:** "MARK BOOTH" big, "Justice of the Peace · Ward 2" below, "Nov 3" in the corner. Use site colors (hunter green `#1e3a2c`, gold `#d4a72c`, red `#9c2b19`, cream `#f6f4ec`).
- **Sizes:** 1080×1080 square (Feed). One square image is enough.
- **Video beats photo** for Phase A: 30–45 sec phone video of Mark, on his porch or in the ward, saying who he is and why. Captions on (most people watch muted). Keep it authentic — polished ads read as "politician."
- **Primary text:** 1–2 sentences. The first sentence is what shows before "See more" — put the name in it.
- **Call-to-action button:** "Learn More" → site for Phases A/B; "Learn More" → Voting Info section (`#vote`) for C/D.
- **Never negative.** Never mention the opponent. (campaign-plan.md §5.)
- **Disclaimer** is attached automatically once selected — verify it shows in the preview before publishing.

Ready-to-paste copy for all five ads is in [`ad-copy.md`](ad-copy.md).

---

## 4. Organic posts that ads should amplify (free)

Ads work better when the page underneath is alive. Keep the 2–3 posts/week rhythm from campaign-plan.md §3–4, and **boost** (just the Boost button, $5–10 each) the ones that get genuine comments:

- Sign deliveries (photo of Mark + the homeowner) — best performer for local races
- Endorsement posts (pastor/coach/business owner quote + photo together)
- "Am I in Ward 2?" post linking to the site's ward-check section
- Early-voting reminder with locations/hours
- Election-eve "thank you, and please vote tomorrow"

Ask the 50–100 personal-contact list to like the page and share the first post. 100 real local likes in week one is worth more than $100 in ads.

---

## 5. Measuring — what to look at, what to ignore

| Watch | Ignore |
|---|---|
| **Reach** and **Frequency** in the Ward 2 audience (want frequency 3–6 by Nov 3) | Clicks, CTR, link clicks — nobody needs to click to remember a name |
| **CPM** (cost per 1,000 impressions). $5–12 is normal for local political; above $20, tighten placements or change the image | "Engagement" from people outside the ZIPs |
| **Comments** — reply to every one, from the page, within a day. Hide only spam or abuse | Page likes after Phase A |
| **Video ThruPlays** for the intro video (Phase A) | Anything Meta's "recommendations" panel suggests spending more on |

Check Ads Manager twice a week (Mon and Thu, matches the weekly rhythm). Total time: 15 minutes.

---

## 6. Compliance checklist

- [ ] Meta ad authorization complete (ID + mailed code)
- [ ] Disclaimer "Paid for by Mark Booth Campaign" created and attached to every ad
- [ ] Ads paid from the campaign account; keep receipts (Ads Manager → Billing → download invoices monthly)
- [ ] Ad spend reported as expenditures on Louisiana Ethics Administration campaign-finance reports
- [ ] Ad disclaimer wording matches the site and printed material exactly
- [ ] Screenshot every published ad for the campaign's records

---

## 7. Calendar at a glance

```
Aug 30  - Create page, start ad authorization, set up Ads Manager
Sept 7  - Authorization done; first organic posts up; ask list to like/share
Sept 15 - Phase A: boost intro video ($3-5/day)
Oct 1   - Phase B: name-recognition ads ($8-10/day)
Oct 20  - Phase C: early-voting ads ($15-20/day)
Oct 28  - Phase D: GOTV ($20-25/day), peak Nov 2-3
Nov 3   - Election Day; pause all ads by 8 p.m.
Nov 4   - Thank-you post (organic). Download invoices for Ethics report.
Dec 5   - Runoff, if needed: rerun C + D with reserve
```
