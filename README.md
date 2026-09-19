# Eventra

Open `pages/index.html` (or run any static server in this folder, e.g. `python -m http.server`).
First visit → **Sign up**. After that → **Log in** (or Sign up again for a new person).

```
Event-Booking/
├── assets/  icons/ images/ logos/
├── css/     index, explore-events, event-details, payment, booking-confirmation, my-bookings, wishlist, auth
├── js/      common (shared), data (events), auth, + one file per page
├── pages/   index, explore-events, event-details, payment, booking-confirmation, my-bookings, wishlist, login, signup
└── download-images.py
```

## Photos
`assets/images/` ships with generated placeholder pictures. Run `python download-images.py`
(needs internet) to replace them with the real photos — same file names, no code changes.
To use your own picture for an event, save it over the file with the same name
(`<event-id>.jpg` = cover, `<event-id>-2.jpg`, `-3.jpg` … = gallery).

## Notes
Accounts, wishlists and bookings are stored in the browser's localStorage (front-end demo only).
