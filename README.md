 # virtualsecretary.online (demo site)

Static marketing site in **British English (UK)** for a virtual secretary and concierge — diary, letters and appointments, plus restaurant, hotel and travel bookings.

## Run on localhost

From this folder:

```bash
npx --yes serve -l 3000
```

Then open [http://localhost:3000](http://localhost:3000).

Alternative (Python):

```bash
python -m http.server 3000
```

## Google Analytics / Tag Manager

Edit `js/config.js`:

1. Set real `measurementId` / `containerId`.
2. Set `enabled: true` for the services you use.
3. Users must accept analytics cookies via the banner before scripts load.

## Replace placeholders

- Phone: search for `0800 XXXX XXXX` and `tel:08000000000`.
- Legal: `legal.html`, `privacy.html`, `terms.html`, `cookies.html` are standard UK texts. Complete every `[square brackets]` field before publication.
