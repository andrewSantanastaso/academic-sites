# Launch checklist

## 1. Fill in the placeholders

Search `index.html` for `FILL IN` — there are four:

| What | Where | Replace with |
|---|---|---|
| Domain | `<head>` — canonical, og:url, og:image | Your real domain, 4 places |
| Screenshot | Case study section | Save as `sarahannsinger-screenshot.png` in this folder |
| Booking link | Final CTA button | Your Cal.com or Calendly URL |
| Email | Final CTA + footer | Your real email, 2 places |

Also search for `YOURDOMAIN.com` in `robots.txt` and `sitemap.xml`.

Still placeholder: **Sarah's quote** in the case study. Ask her for two
sentences about what changed after the site went up.

## 2. Screenshot

Take it at 1600×900 or wider, from the top of her homepage. Export as PNG,
then compress at squoosh.app — aim for under 200KB. Name it
`sarahannsinger-screenshot.png` and drop it in this folder.

## 3. Favicon

`favicon.svg` is a placeholder monogram in your teal. Replace it if you have
a mark. For the `.ico` and `apple-touch-icon.png` referenced in the head,
generate them at realfavicongenerator.net, or delete those two `<link>` lines
if you only want the SVG.

## 4. Deploy

**Simplest — Netlify Drop:**
1. Go to app.netlify.com/drop
2. Drag this whole folder onto the page
3. It's live in about 20 seconds on a temporary URL

**Recommended — Cloudflare Pages:**
1. Push this folder to a GitHub repo
2. Cloudflare dashboard → Workers & Pages → Create → Pages → connect the repo
3. Build command: none. Output directory: `/`
4. Deploy

## 5. Domain

Register at Cloudflare (at cost, ~$10–12/yr for a .com). If you're on
Cloudflare Pages, adding the custom domain is two clicks and SSL is automatic.

## 6. Before you tell anyone

- [ ] Load it on your phone
- [ ] Tab through with the keyboard — focus rings should be visible
- [ ] Open every FAQ accordion
- [ ] Paste the URL into iMessage or Slack, confirm the preview card looks right
- [ ] Check the padlock (SSL) appears
- [ ] Run it through PageSpeed Insights

## 7. First week

- Google Search Console — verify the domain, submit `sitemap.xml`
- Analytics — Cloudflare Web Analytics is free and needs no cookie banner

## Open decisions

- **Hosting FAQ** still says hosting is free and the domain is ~$15/yr. True
  for static sites; not true for Sarah's WordPress.com build, which needs the
  ~$4/mo Personal plan for parts of the design to render publicly. Reword to
  scope it to your future work, or state the range honestly.
- **The case study describes five pages.** Research, Contact, and Teaching
  aren't built yet. Wait until they're live, or reframe as in-progress.
- **Designer credit in Sarah's footer** needs her sign-off before it doubles
  as a referral path.
