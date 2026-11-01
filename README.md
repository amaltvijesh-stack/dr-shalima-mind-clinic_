# Dr Shalima's Mind Clinic – Session Booking Page

A single-page booking and scheduling tool for the clinic, built as a Claude published page.

**Live page (requires Claude sign-in):** https://claude.ai/artifact/AxKC2ijgDLsFNcT65JpNoj

## What it does
- Team schedule for Habla, Varda and Sahla: booked and available slots, day by day
- 45-minute sessions, start times every 30 minutes from 10:00 AM to 7:30 PM (IST)
- Booking form with case type (Initial, Follow-up, C/o Dr, Outside) and session type (Individual, Couple therapy)
- Staff area: front desk list, edit, cancel, free a slot, WhatsApp reminders, next-session booking
- Banner 10 minutes before a session starts (while the page is open)
- Monthly report per psychologist, with Excel and PDF downloads
- Backup card that reminds staff when a backup is more than a day old
- Day and night mode, live IST clock

## Files
- `shalimas-mind-clinic.html` – the full page (HTML, CSS and JavaScript in one file, logo embedded)

## Important notes
- **This file will not work on its own.** Bookings are stored in the Claude page's own database. Opening the HTML file directly, or hosting it on GitHub Pages, shows an empty schedule and bookings will not save.
- This repository is a safekeeping copy of the page code only. It contains **no client data**.
- Keep this repository **private**.
- Back up client data from the page itself (Backup card, Excel and PDF) and store those files securely, not in this repository.

## Known limits
- Viewers need a Claude account to open the page.
- Only the page owner and Editors can see client details.
- Reminders are sent by staff through WhatsApp links; nothing is sent automatically.
- Storage is limited by the Claude page database (documents up to 256 KB each). The way bookings are grouped per login should be restructured before heavy use.
