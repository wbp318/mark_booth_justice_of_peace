# Setup Instructions — Ad Authorization (mailed code) and Meta Pixel

Two separate things. Do #1 today — it's the one with a wait.

---

## 1. Political-ad authorization (the part that gets MAILED — start now)

Meta won't run any ad about elections until the person running the ads is verified. Takes 1–5 business days because a code is sent by postal mail.

**Who does this:** whoever will actually click "Publish" on ads — you, as page admin, is fine. It's tied to a personal Facebook profile, not the Page. Mark does not need to do it.

1. Log into Facebook with the personal account that manages the campaign Page.
2. Go to **https://www.facebook.com/id** (or Settings → Accounts Center → Personal details → Identity confirmation).
3. Click **"Confirm your identity"** → choose **"Ads about social issues, elections or politics"** → country **United States**.
4. **Upload a government ID** (driver's license, front and back, clear photo). Usually approved in minutes to a day.
5. **Enter a US mailing address.** Meta mails a letter with a **confirmation code** to it. Use whatever address you can reliably receive mail at — it doesn't have to be the campaign's address. Delivery: 3–7 days.
6. When the letter arrives, go back to the same page and **enter the code**. Done — the account is authorized.
7. **Two-factor authentication** must be turned on for that Facebook account (Meta requires it). Settings → Security → Two-factor authentication.

**While waiting for the letter, do these (no code needed):**

8. **Create the Page:** facebook.com/pages/create → name "Mark Booth for Justice of the Peace" → category **Politician**. Add headshot + cover. Post 3–4 things.
9. **Create the disclaimer:** Ads Manager (adsmanager.facebook.com) → menu ☰ → **Accounts → Disclaimers** → Create → wording **"Paid for by Mark Booth Campaign"** → attach to the Page. Meta may ask for a phone/email/website for the disclaimer — use info@votemarkbooth.com and the site URL. The disclaimer can be created before the code arrives but only *activates* once authorization is complete.
10. **Add payment method:** Ads Manager → Billing → add the **campaign bank account** debit card. Never a personal card.

---

## 2. Meta Pixel ID (instant — nothing mailed)

The Pixel is a snippet on the website that lets you later show ads to people who visited the site. Optional, but free and takes 5 minutes.

1. Go to **Events Manager**: https://business.facebook.com/events_manager
2. Click **Connect Data Sources** (green + icon) → **Web** → **Connect**.
3. Name it `Mark Booth Campaign Site` → **Create Pixel**.
4. If asked "How do you want to connect your website?" choose **"Meta Pixel only"** (not Conversions API).
5. Choose **"Install code manually."** It shows a block of code — you only need the **Pixel ID**, the 15–16 digit number in it (looks like `1234567890123456`). It's also shown at the top of the Events Manager page under the data source name.
6. **Paste that number into this chat.** Claude adds the pixel code to `index.html` and pushes; the site redeploys in a minute.
7. Verify: install the **Meta Pixel Helper** Chrome extension, open the live site, and the extension icon should show 1 pixel firing with a PageView.

**After it's live**, in Ads Manager → Audiences → Create Audience → **Custom Audience → Website** → "All website visitors, last 180 days." That audience becomes usable once ~100 people have visited, which is the point of sharing the site link on the Page and in the personal-contact list.

---

## Where each thing lives

| Item | Where |
|---|---|
| Identity / ad authorization | https://www.facebook.com/id |
| Page | https://www.facebook.com/pages/create |
| Disclaimers, billing, ads | https://adsmanager.facebook.com |
| Pixel | https://business.facebook.com/events_manager |
| Public archive of every political ad you run | https://www.facebook.com/ads/library |
