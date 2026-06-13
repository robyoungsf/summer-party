# Summer Party 🌞

A simple, single-page website to share the details of our summer party and
collect RSVPs through a Google Form.

## Stack

Plain HTML + CSS — no build tools, no dependencies. Just open the file in a
browser.

## Run it locally

Open `index.html` directly in your browser, or serve it:

```sh
# Python (built into macOS)
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Wire up RSVPs (one step)

1. Create a Google Form (https://forms.google.com) with the questions you want
   — name, number of guests, dietary notes, etc.
2. In the form, click **Send** → the **link icon** (🔗) → **Copy**.
3. In `index.html`, replace both occurrences of
   `PASTE_YOUR_GOOGLE_FORM_LINK_HERE` with that link.

Responses collect automatically in the form's linked Google Sheet.

## Customize the party details

Edit the text in `index.html`:

- **Date / time** — the "When" card
- **Location** — the "Where" card
- **What to bring** — the "Bring" card
- **Description** — the "What to Expect" section

Colors and fonts live in `styles.css` (see the `:root` variables at the top).

## Hosting later

When you're ready to put it online, this works as-is on **GitHub Pages**,
**Netlify**, or any static host — no server needed.
