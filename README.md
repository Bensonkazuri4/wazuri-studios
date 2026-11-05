# Wazuri Studios website

A responsive React + Vite starter website for Wazuri Studios. Built with a dark charcoal and muted-gold visual identity.

## Run locally
1. Extract this ZIP.
2. Open the extracted folder in Bolt or your code editor.
3. Run `npm install`.
4. Run `npm run dev`.

## Connect the live stream
1. Copy `.env.example` and rename the copy to `.env`.
2. Set `VITE_LIVE_STREAM_URL` to your provider's **embed URL**.
   - YouTube example: `https://www.youtube.com/embed/YOUR_LIVE_VIDEO_ID`
   - Use the embed URL supplied by your streaming provider, not necessarily the public watch-page URL.
3. Restart the development server after editing `.env`.

The current player is an iframe embed. If your provider supplies an HLS `.m3u8` URL rather than an iframe embed URL, the player should be adapted to use an HLS-compatible video player.

## Before publishing
- Replace the placeholder email `hello@wazuristudios.com` with your real business email.
- Confirm the WhatsApp number in `src/main.jsx` (currently set to +254 707 739 621).
- Add real project images and portfolio examples when available.
- Connect the contact form or inquiry workflow if you want submissions stored or emailed. The current site uses WhatsApp and email links.
