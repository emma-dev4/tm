# tm

Live-event ticketing demo: search by city, an interactive seat map, fee breakdown, a 10-minute hold, and a mobile ticket saved in the browser.

This is an original product. It is not Ticketmaster and it does not sell real admission. Checkout never charges a card.

## Try it

1. Search or pick a city.
2. Open a show and choose **See tickets**.
3. Tap a section, pick an offer, and continue.
4. Pay with `4242 4242 4242 4242`, any future expiry, any CVC.
5. Open **My Tickets** for the pass.

Event photos are in `media/*.b64`. Unpack them once:

```bash
node scripts/unpack-media.mjs
npm install
npm run dev
```
