PGPR ECO-CARE — PDF RECEIPT + COLLECTION CALENDAR ONLY

THIS VERSION KEEPS
- Downloadable PDF receipt
- Collection date calendar
- Collection time slots
- Slot capacity and booking limits
- Admin collection-slot management
- Telegram handle as ordinary contact information

THIS VERSION REMOVES
- Telegram bot connection button
- Automatic Telegram verification messages
- Telegram bot username setting
- Supabase Telegram Edge Functions
- Bot token and webhook setup

INSTALLATION

A. If you have NOT run the previous PDF/calendar/Telegram SQL:
1. Open Supabase -> SQL Editor -> New query.
2. Run supabase-pdf-calendar-only.sql.
3. Replace your GitHub index.html with the index.html inside this ZIP.
4. Commit and hard-refresh with Ctrl + Shift + R.
5. Sign in -> Admin -> Collection and add future collection slots.

B. If you ALREADY ran the previous Telegram-enabled SQL:
1. You do not need to remove the old Telegram database table.
2. Simply replace the GitHub index.html with this version.
3. The unused Telegram table and column are harmless.
4. No Edge Functions or bot token are required by this website.

Residents still enter a Telegram handle so the admin can contact them manually.
The website will not send Telegram messages automatically.
