J.A.R.V.I.S PHONE STARTER — PROTOTYPE 01

This is a starter PWA interface, not a finished AI assistant.
It includes:
- A J.A.R.V.I.S-inspired dashboard
- Browser speech input (if supported)
- Browser text-to-speech
- English (UK) and Egyptian Arabic language selections
- A few local demonstration responses

It does NOT yet include:
- An AI model/API connection
- General-purpose translation
- Real phone control, alarms, reminders, or app launching
- Always-on wake-word listening
- Background assistant service

IMPORTANT:
1. The app must be hosted on HTTPS for microphone access and PWA installation.
2. Open it in Chrome on Android and allow microphone access when prompted.
3. For installation, use Chrome menu > Add to Home screen / Install app.
4. Never put a private AI API key directly into index.html. A secure server-side endpoint is needed for the AI connection.

Next development step: publish these files to an HTTPS host, then connect a secure AI backend.
