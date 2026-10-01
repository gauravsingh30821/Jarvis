# JARVIS OS

An Iron Man-inspired personal intelligence interface built with plain HTML, CSS, and JavaScript.

## Run it

Open `index.html` in a modern browser. For microphone permissions, serve the folder from a local web server:

```powershell
cd C:\Users\10\Documents\jarvis
python -m http.server 8080
```

Then open <http://localhost:8080>.

## Included

- Responsive HUD-style interface
- Local conversation persistence via `localStorage`
- Quick protocol buttons and diagnostic-style responses
- Web Speech API microphone input where supported
- Text-to-speech responses where supported

The app is frontend-only. To make it a general-purpose AI assistant, connect `submitMessage` to a server-side AI endpoint. Keep provider API keys on that server, never in `app.js`.
