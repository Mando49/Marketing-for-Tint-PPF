# Mando Auto Film — website

Static HTML site for a window tint and paint protection film shop
in Las Vegas, NV. Owner: Mando (Armando). Sole proprietor.

The site exists to get local customers to call or text. That is the
only goal. Every change should make that easier, not harder.

## What's in the repo

- `index.html` — the whole site. HTML, CSS, and the JSON-LD block
  all live in this one file.
- `index-v2.html`, `index-v3.html`, `index-v4.html` — alternative
  homepage designs for comparison. `index-v4.html` is the current
  direction: v2 layout, red/black/white palette, Armando only.
- `tesla-window-tint.html` — Tesla-specific landing page.
- `images/` — all shop photos, named by what they show. No photo
  may show the old "Action Window Tinting" sign.
- `README.md` — one-line description. Still uses the old business
  name; that is fine to leave or update.

No build step. To preview, open `index.html` in a browser.

## Confirmed facts — safe to use

- Business name: Mando Auto Film (formerly Armando's Custom Window
  Tint — the old name still appears in the Yelp and Google URLs,
  and that is expected)
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
  matte paint protection film (clear film that protects the paint
  and changes the finish to matte), old tint removal, residential
  window tint
- Film brands: Global window tint film, LLumar paint protection
  film. No other brands.
- Warranty: lifetime warranty on window tint, 10-year warranty on
  paint protection film. No other warranty terms.
- Yelp: yelp.com/biz/armandos-custom-window-tint-las-vegas
- Google: g.page/armando-s-custom-window-tint
- Site URL: https://www.lasvegaswindowtintnv.com/

Anything not on this list, ask. Do not fill gaps with plausible
guesses.

## Never do these

- Never invent prices, warranty terms, film brand names,
  years in business, or certifications beyond what is in the
  confirmed facts list above.
- Never state Nevada tint law limits or VLT percentages.
  The law varies by window position and vehicle type, and wrong
  info creates real liability. Say the limits exist and to ask
  the shop. The footer already does this correctly.
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
