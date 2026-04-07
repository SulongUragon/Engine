# LOUD MINDS ENGINE

A free, open-source content creation tool for dark psychology and mindset content creators.

Built for TikTok and Reels. No subscription. No account. Bring your own API keys.

---

## FEATURES

**CAROUSEL MODE**
- Generate 10-slide carousels with AI
- Stock photo backgrounds per slide (via Pexels)
- Export as 1080x1920 PNG (9:16) individually or as ZIP
- Generate voiceover script + ElevenLabs audio
- Waveform display with sync export (audio clips per slide)
- Generate caption, hashtags, SEO keywords, on-screen text

**SCRIPT MODE**
- Hook / Body / CTA script generator
- Auto-generates 3 posters with stock photos
- Editable poster text and script sections
- ElevenLabs audio generation + silence remover
- Sync export for CapCut workflow

**QUOTE MODE**
- 4-line quote generator
- 3 format choices: black bg, off-white bg, image bg
- Export as 1080x1920 PNG

**CALENDAR MODE**
- 7, 15, or 30-day content calendar
- Alternating formats, rest days included
- One-click generate button per day — pre-fills topic in the right mode

---

## SETUP

### 1. Get your API keys

| Key | Where to get it | Required? |
|-----|----------------|-----------|
| Anthropic | [console.anthropic.com](https://console.anthropic.com) → API Keys | Yes |
| ElevenLabs | [elevenlabs.io](https://elevenlabs.io) → Profile → API Key | Optional (for audio) |
| ElevenLabs Voice ID | ElevenLabs → Voices → click your voice → copy ID from URL | Optional (for audio) |
| Pexels | [pexels.com/api](https://www.pexels.com/api/) → free | Optional (for image backgrounds) |

### 2. Open the app

**Option A — Use the live version:**
Visit the deployed URL and enter your keys on first load.

**Option B — Run locally:**
1. Download `index.html`
2. Double-click to open in Chrome
3. Enter your API keys when prompted

Your keys are saved in your browser's localStorage. They never leave your device except to call the respective APIs directly.

---

## USAGE

1. Open the app
2. Enter your API keys on first load (one time only)
3. Choose a mode: CAROUSEL, SCRIPT, QUOTE, or CALENDAR
4. Enter your topic and generate

To update your keys anytime: click the **⚙ KEYS** button in the top right.

---

## STACK

- Pure HTML + Vanilla JavaScript
- No framework, no build step, no dependencies to install
- APIs: Anthropic Claude, ElevenLabs, Pexels
- Libraries loaded via CDN: JSZip, FileSaver.js, Google Fonts

---

## LIMITATIONS

- Export Video is not supported on Safari/iPhone (MediaRecorder limitation)
- PNG and ZIP exports work best in Chrome
- Audio generation requires ElevenLabs API key and a cloned voice

---

## CONTRIBUTING

This tool is free and open source. Pull requests welcome.

---

## CREDITS

Built by [@loudminds](https://tiktok.com/@loudminds)

Tools used: Claude (Anthropic), ElevenLabs, Pexels API
