# Manyan AI: desktop app

Manyan AI is a real-time AI interview coach for students. It listens to your practice answers and shows coaching in a floating window, and it opens practice sessions created on the Manyan AI website.

## Run from source

```bash
npm install
npm start
```

Add a Gemini API key in the app (get one at <https://aistudio.google.com/apikey>).

## Build the Windows installer

```bash
npm run dist:win
```

This creates `dist/ManyanAI-Setup-<version>.exe`, a standard Windows setup wizard (install folder choice, Start Menu and desktop shortcuts, uninstall from Settings → Apps). The installed app registers the `manyan://` link used by the website's "Open in Desktop App" button.

## Licence and credits

Manyan AI is free software licensed under the **GNU General Public License v3.0**; see [LICENSE](LICENSE). It is based on [Cheating Daddy](https://github.com/sohzm/cheating-daddy) by sohzm and contributors. If you distribute this app, you must also make its source code available under the same licence.
