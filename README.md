# Palash Bridge · Santhali ↔ Hindi

An offline-friendly classroom translation prototype inspired by Jharkhand's PALASH Mother Tongue-Based Multilingual Education programme.

## Included

- Hindi ↔ Santhali translation with a bundled offline phrase library
- Dynamic online translation for words and sentences outside the starter library
- Ol Chiki Santhali output
- Word-level fallback matching for prototype exploration
- Browser speech input and playback hooks
- Local recent translation history
- Bilingual worksheet preview
- Side-by-side source file viewer at `files.html`

## Run locally

The app is intentionally dependency-light. Serve the project folder with any static web server:

```bash
python3 -m http.server 5000 --bind 0.0.0.0
```

Then open `http://localhost:5000`.

## Prototype note

The local phrasebook keeps common classroom phrases available offline. When connected, the app can translate words and sentences outside that starter library through the dynamic translation path. A reviewed Santhali classroom corpus or on-device NLP model should still be added before classroom deployment.