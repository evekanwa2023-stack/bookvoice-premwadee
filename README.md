# Bookvoice Premwadee

A copy of [Bookvoice](https://evekanwa2023-stack.github.io/bookvoice/) (EPUB reader with text-to-speech) that reads **Thai text with the Thai voice Premwadee** and everything else with the English voice.

- Single self-contained `index.html`, no build step.
- Needs a TTS server URL (a Google Colab notebook running Flask + edge-tts behind a Cloudflare tunnel), pasted on the first screen.
- Uses its own storage names (`bvp:` localStorage prefix, `bookvoice-premwadee-db`, `bookvoice-premwadee-saves.json`) so it does not mix with the original Bookvoice app on the same github.io domain.
- Based on Bookvoice v3.3.47.
