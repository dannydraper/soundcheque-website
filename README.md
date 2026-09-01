# SoundCheque website

Support, privacy policy, and features site for [SoundCheque](https://github.com/dannydraper/SoundCheque) — the invoicing app for gigging musicians.

**Live:** [soundcheque.dannydraper.co.uk](https://soundcheque.dannydraper.co.uk) — deployed via Netlify, which auto-deploys on every push to `main`. (The underlying `soundcheque.netlify.app` URL still works but isn't the canonical one.)

Plain static HTML/CSS, no build step. Pages:

- `index.html` — home / features
- `support.html` — help & FAQ (App Store support URL target)
- `privacy.html` — privacy policy (App Store privacy URL target)
- `contact.html` — contact / suggestions

## Local preview

```
python3 -m http.server 8080
```

Then open `http://localhost:8080`.
