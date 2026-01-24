# Vantage

Astronomy recommendation app for backyard stargazers.

## Setup

```bash
npm install
```

## Development

**Mac only (no HTTPS):**
```bash
npm run dev
```
Then open http://localhost:5173

**Phone testing (with HTTPS):**
```bash
npm run dev:phone
```
Then open https://[YOUR_MAC_IP]:5173 on your phone.
Your phone will warn about the self-signed certificate — tap "Advanced" → "Proceed anyway".

## Files

- `/public/vantage-app.html` — Main app
- `/public/vantage-ar-horizon.html` — AR horizon setup tool
