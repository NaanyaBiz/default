**To:** hello@newterritory.studio
**Subject:** Small add to thewyndhamclub.co.nz: /app page for a QR code
**Attach:** `app/index.html` (from this folder)

---

Hi Paul and team,

Hope you're well. I have a small job for the site.

We're putting a QR code on the counter and in the bays that sends customers to the GOLFZON Global app, so they can review their rounds and practice data. To keep it to one code for both phone types, it will point at a page on our site:

**https://thewyndhamclub.co.nz/app**

I've attached a finished page for that address (`index.html`). It's one self-contained file. It sends iPhones and iPads to the App Store and Android phones to Google Play, and shows both buttons to anyone else. It has no external scripts, cookies or tracking, and it uses the site's existing colours, logo and the Söhne fonts from `/assets/fonts/`.

**What I need from you**

1. Publish it at `/app`. However suits the Kirby setup is fine with me. That could be a static file at `/app/index.html` in the web root, or a page with a bare template that outputs this HTML unchanged. Please make sure both `/app` and `/app/` work, because the printed code uses `/app` with no slash.
2. Keep it out of the main navigation and the sitemap. The page already has `noindex` set.
3. Let me know once it's live. We won't print the code until then.

**Quick check once it's up**
- On an iPhone, `thewyndhamclub.co.nz/app` should go straight to GOLFZON Global in the App Store.
- On an Android phone, it should go straight to Google Play.
- On a laptop, it should show the page with two buttons.

**Optional:** if it's easy, I'd like to see how many people use the code. Adding the site's existing Google Analytics tag to this page would do it. Feel free to quote that separately.

If GOLFZON ever changes its store links, the two store URLs appear twice near the bottom of the file (in the buttons and in the script), so updating them is a quick edit. We won't need to reprint anything.

Thanks very much. Let me know if you have any questions or if this will cost anything.

Cheers,
Kirk
The Wyndham Club
