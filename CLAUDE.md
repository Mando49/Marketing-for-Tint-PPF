# Mando Auto Film — website

Static HTML site for a window tint and paint protection film shop
in Las Vegas, NV. Owner: Mando (Armando). Sole proprietor.

The site exists to get local customers to call or text. That is the
only goal. Every change should make that easier, not harder.

## What's in the repo

- `index.html` — the whole site. HTML, CSS, and the JSON-LD block
  all live in this one file.
- `images/` — all shop photos pulled from the old WordPress site,
  named by what they show. Only four are used on the page so far.
- `README.md` — one-line description. Still uses the old business
  name; that is fine to leave or update.

No build step. To preview, open `index.html` in a browser.

## Confirmed facts — safe to use

- Business name: Mando Auto Film (formerly Armando's Custom Window
  Tint — the old name still appears in the Yelp and Google URLs,
  and that is expected)
- Phone: 702-530-8779 (`tel:+17025308779`, `sms:+17025308779`)
- Email: only1mando@gmail.com
- Serves: Las Vegas and Henderson, NV
- Appointment only
- Installers: Armando and Irma, 50+ years combined in the
  Las Vegas auto industry
- Services: automotive window tint, paint protection film,
  old tint removal, residential window tint
- Yelp: yelp.com/biz/armandos-custom-window-tint-las-vegas
- Google: g.page/armando-s-custom-window-tint
- Site URL: https://www.lasvegaswindowtintnv.com/

Anything not on this list, ask. Do not fill gaps with plausible
guesses.

## Never do these

- Never invent prices, warranty terms, film brand names,
  years in business, or certifications.
- Never state Nevada tint law limits or VLT percentages.
  The law varies by window position and vehicle type, and wrong
  info creates real liability. Say the limits exist and to ask
  the shop. The footer already does this correctly.
- Never remove or bury the phone number.
- Never add a customer review that the owner has not supplied.
  The one on the page (Jason G.) is real.

## Rules

- Mobile first. Most visitors are on phones. Check narrow
  widths before wide ones.
- The phone number must be tappable everywhere it appears
  (`tel:` links). The sticky call bar at the top of the page
  must stay visible while scrolling. Keep it.
- Keep the JSON-LD block at the bottom of `index.html` accurate.
  Google reads it for local search. If a confirmed fact changes,
  update it there too.
- Plain HTML and CSS in one file. No build step, no frameworks,
  no JavaScript unless there is no other way.
- Explain changes in plain language. Give complete files,
  not fragments. The owner is not a developer.

## Note

The old WordPress site at lasvegaswindowtintnv.com is still live,
but `index.html` does not depend on it for anything. All gallery
photos are hosted locally in `images/`.
