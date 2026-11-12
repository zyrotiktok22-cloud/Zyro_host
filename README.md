<div align="center">
  <img src="assets/zyrolegend-banner.png" alt="Zyrolegend¹bot banner" width="100%" />

  # 👑 Zyrolegend¹bot
  **Multi-Function WhatsApp Bot**

  `FAST` · `SECURE` · `SMART` · `RELIABLE`

  **Owner number (branding):** `252614482546`
</div>

---

## About

Zyrolegend¹bot is a rebranded presentation of the CypherX WhatsApp bot project. The original application entry point and deployment files are preserved.

## Requirements

- Node.js 20 or newer (within the range specified in `package.json`)
- npm
- A valid WhatsApp session configured through the supported `SESSION_ID` environment variable
- FFmpeg and ImageMagick for media features that require them

## Install and start

```bash
npm install
npm start
```

## Deployment

The repository includes a `Dockerfile`, `Procfile`, `heroku.yml`, and `app.json` for deployment workflows. Configure the required `SESSION_ID` securely in your hosting provider's environment settings. Never publish your session string, QR code, or credentials.

## Important notes

- The original `index.js` is obfuscated and has been left unchanged.
- The owner number above is branding information only. It is **not confirmed as an active bot owner setting**; the owner authorization logic must be inspected and updated in the application code before it can take effect.
- Review the source and dependencies before deploying. Do not run code you do not trust.

---

<div align="center">
  **Zyrolegend¹bot — Legend Never Fails.**
</div>
