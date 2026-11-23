# ContactHub — Smart Contact Manager

Simple contacts website (HTML + CSS + JS, no build step).

## How to run (easy)

1. Open the `contact-hub` folder.
2. Double-click **`index.html`** — it opens in your browser. Done.

> No install, no server, no build needed. Internet is only used for fonts/icons/SweetAlert2 CDN.

## Features

- ✅ **Add / Update / Delete** contacts (modal with `display:none` toggle)
- ✅ **Search** by name, phone, or email (live) + group filter
- ✅ **Favorites** — star any contact, shown in Favorites sidebar
- ✅ **Emergency** list — flagged contacts with quick-call access
- ✅ **Call / Email action buttons** — `href="tel:..."` and `href="mailto:..."`
- ✅ **Validation**:
  - Name: letters + spaces only, 2–50 chars
  - Phone: valid Egyptian number (`010/011/012/015` + 8 digits)
  - Email: optional, but must be valid if entered
- ✅ **localStorage** — data persists after reload (`contacthub_contacts` key)
- ✅ **SweetAlert2** — success alerts + delete confirmation
- ✅ Photo upload per contact (stored as base64 in localStorage)

## Files

- `index.html` — structure + modal
- `style.css` — all styling (matches ContactHub design reference)
- `app.js` — logic: CRUD, search, favorites, validation, localStorage
