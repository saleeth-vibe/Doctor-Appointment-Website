# Wellnest — Doctor appointments

A complete, responsive doctor appointment website with a browser interface and a dependency free Node.js backend.

## Run locally

1. Install Node.js 18 or later.
2. Open a terminal in this folder.
3. Run `npm start`.
4. Visit [http://localhost:3000](http://localhost:3000).

No npm packages are required. Bookings are saved in `data/appointments.json` on the server. The doctor directory is sample content; replace it in `server.js` with your clinic’s real doctors and available times before accepting real bookings.

## What’s included

- Responsive clinic homepage and doctor directory.
- Doctor and specialty search, sorting, and saved-favorite buttons.
- Booking dialog with patient details, date and time selection, validation, and confirmation.
- JSON API: `GET /api/doctors`, `GET /api/appointments`, and `POST /api/appointments`.
- Server-side booking validation and duplicate appointment protection.

This is a starter application. The included sample records do not represent real medical providers or guaranteed availability.
