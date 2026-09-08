# Mando Auto Film — website

Static HTML site for a window tint and paint protection film shop
in Las Vegas, NV. Owner: Mando (Armando). Sole proprietor.

The site exists to get local customers to call or text. That is the
only goal. Every change should make that easier, not harder.

## What's in the repo

- `index.html` — the homepage. HTML, CSS, and the JSON-LD block
  all live in this one file. Red/black/white palette, Armando only.
  Services are shown as a two-column card grid.
- `tesla-window-tint.html` — Tesla-specific landing page.
- `sitemap.xml`, `robots.txt` — the two live pages listed for search
  engines, and an allow-all robots file that points at the sitemap.
  Add any new page to the sitemap.
- `CNAME` — tells GitHub Pages the site lives at
  www.lasvegaswindowtintnv.com. Do not remove it.
- `blog/`, `services/`, `contact-us/`, `hello-world/` — one tiny
  index.html each. They exist only because the old WordPress site had
  pages at those addresses; each one forwards visitors and Google to
  the new site (services and contact-us to their homepage sections).
  Marked noindex and kept out of the sitemap.
- `images/` — all shop photos, named by what they show. No photo
  may show the old "Action Window Tinting" sign.
- `README.md` — short description for GitHub.

No build step. To preview, open `index.html` in a browser.

## Confirmed facts — safe to use

- Business name: Mando Auto Film (formerly Armando's Custom Window
  Tint — the old name still appears in the Google URL, and that
  is expected)
- Phone: 702-530-8779 (`tel:+17025308779`, `sms:+17025308779`)
- Email: only1mando@gmail.com
- Serves: Las Vegas, Henderson, Summerlin, and North Las Vegas, NV
- Appointment only
- No street address on any page. The shop is appointment-only and
  the address is given when the appointment is confirmed.
- Installer: Armando, sole installer. 23 years installing window
  tint, 13 years installing paint protection film. Do not name
  anyone else as an installer or staff.
- Brand palette: red, black, and white. Black is the background
  and every surface, white is the text, red is the accent only
  (call button, text button border, section markers, trust row
  numbers). Red stays under 10% of the screen. No gold,
  champagne, or purple.
- Services: automotive window tint, paint protection film,
  matte paint protection film (PPF with a matte finish: same
  protection as clear PPF, but it turns the paint satin instead of
  glossy), old tint removal, residential window tint
- Warranty: lifetime warranty on window tint, 5-year warranty on
  paint protection film. No other warranty terms. (An earlier note
  here said 10 years; that was wrong. Corrected Sep 7, 2026.)
- Yelp: yelp.com/biz/mando-window-tinting-las-vegas-2
- Google: g.page/armando-s-custom-window-tint
- Site URL: https://www.lasvegaswindowtintnv.com/

Anything not on this list, ask. Do not fill gaps with plausible
guesses.

## Never do these

- Never invent prices, warranty terms, years in business, or
  certifications beyond what is in the confirmed facts list above.
- Never name a film manufacturer or brand anywhere on the site.
  Describe the film by what it does, not who makes it.
- Never state Nevada tint law limits or VLT percentages without
  verifying current law first. The law varies by window position
  and vehicle type, and wrong info creates real liability. The
  35% front-side-window figure in the automotive window tint
  block on the homepage was verified against NRS 484D.440 on
  Sep 7, 2026. Anything beyond that, verify before writing it.
- Never remove or bury the phone number.
- Never put a street address on any page, including the JSON-LD
  block. The address is given out when an appointment is confirmed.
- Never add a customer review that the owner has not supplied.
  The one on the page (Jason G.) is real.

## Rules

- Mobile first. Most visitors are on phones. Check narrow
  widths before wide ones.
- The phone number must be tappable everywhere it appears
  (`tel:` links). The sticky call bar at the top of the page
  must stay visible while scrolling. Keep it.
- Keep the JSON-LD blocks at the bottom of `index.html` and
  `tesla-window-tint.html` accurate and identical. Google reads them
  for local search. If a confirmed fact changes, update both.
- Plain HTML and CSS, one file per page. No build step, no
  frameworks, no libraries. The only JavaScript is the small vanilla
  script at the bottom of each page for the scroll reveal, the
  trust-row count-up, and the review carousel. Every page must still
  read fine with JavaScript off, and every animation must respect
  prefers-reduced-motion.
- The homepage and the Tesla page share their header, trust row,
  films line, review carousel, contact icons, and footer. When one
  of those changes on one page, make the same change on the other.
- Explain changes in plain language. Give complete files,
  not fragments. The owner is not a developer.

## Hosting and domain

The DNS switch is done as of Sep 7, 2026. lasvegaswindowtintnv.com
serves this repo from GitHub Pages over HTTPS. The www CNAME points
at mando49.github.io, four GitHub A records cover the bare domain,
and Enforce HTTPS is on in the repo's Pages settings. `CNAME` in
the repo root keeps the custom domain attached; do not remove it.

`sitemap.xml` and `robots.txt` are in the repo root, and the sitemap
has been submitted in Google Search Console. Add any new page to the
sitemap.

The four old WordPress paths (/blog/, /services/, /contact-us/,
/hello-world/) now resolve to the GitHub site and redirect correctly,
verified Sep 7, 2026. DNS no longer routes to WordPress. Whether the
WordPress install itself has been deleted from SiteGround is still
unconfirmed. Nothing here depends on it; all photos are hosted
locally in `images/`.
