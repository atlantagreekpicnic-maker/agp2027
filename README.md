# Atlanta Greek Picnic 2027 website

Static site for Atlanta Greek Picnic 2027 (main event Saturday, June 12, 2027, Atlantic Station, Atlanta).

## What's here

- `index.html` — the whole site in one file: Home, Tickets, Experience, AGP DJs and Taste of AGP. The top navigation switches between them without reloading.
- `assets/` — the 2027 logo, the 2026 recap video and its poster frame, and the ticket photos.

No build step. Open `index.html` in a browser, or host the folder on any static host (GitHub Pages, Vercel, Netlify).

## Still to finish before launch

- Ticket prices, section and table sizes, schedule dates, times and venues are placeholders in square brackets.
- Buy buttons go to the Easol booking pages on www.atlantagreekpicnic.com. General Admission, Weekend Pass, Sections & Tables and Sky View all point to /book-saturday and VIP to /book-vip until each has its own Easol product link (set each ticket's `url` in `index.html`).
- Tracking: Google Tag Manager container GTM-MG3SX4KS (shared with the Easol site) loads Google Analytics and the Meta Pixel. The site sends `buy_click` and `generate_lead` to Analytics and `BuyClick` and `Lead` to Meta.
- The email sign-up, vendor application and DJ registration forms show a confirmation but do not send or save anything.
- Instagram, Facebook and AGP Foundation links in the footer have no address yet.
- Photo slots marked `[Photo: ...]` need real images. Past AGP DJ cards need names and photos.
