# Speak English AI — Prototype

This is a mobile-first, offline-friendly English learning prototype.

## Included
- Tamil + English lesson groups (Beginner to Advanced)
- Vocabulary builder with spoken pronunciation using browser Text-to-Speech
- Speaking practice using browser speech recognition where supported
- Grammar quiz and sentence jumble exercises
- Translation handoff to Google Translate
- Guided demo English-teacher conversation
- Local progress saved in browser localStorage
- No login, payment, subscription, or user-managed server

## Run
Open `index.html` in Chrome on Android or a desktop browser. For microphone speech recognition, use Chrome and grant microphone permission. Speech recognition availability depends on browser/device and may use Google's online speech service.

## Important limits
This is a working front-end prototype, not a signed Android APK.
The AI Teacher is a guided demo, not live Gemini. To add live Gemini securely for a public app, use Google Firebase AI Logic (Google-managed cloud infrastructure) with App Check. Do not embed a private Gemini API key in an APK. Google Translate opens its website rather than using a private API.
