# Duck & Lemon Tycoon (multiplayer, Node.js)

## Run locally
1. Install Node.js (free): https://nodejs.org (v18+)
2. In this folder run:  `npm install`  then  `npm start`
3. Open http://localhost:3000 in two browser tabs to test multiplayer.

## Play with friends for free
- **Same Wi-Fi:** they open `http://YOUR-LAN-IP:3000`.
- **Online:** deploy free on Render.com / Railway / Glitch / Replit (upload this folder, start command `npm start`).
  On Render's free tier, files reset on restart - set env var `DATA_DIR` to a persistent disk path if you need permanent saves.

## Files
- `server.js` - authoritative game server (WebSocket + static files, saves to saves.json)
- `public/config.js` - balance numbers (shared by server and client). Edit to tune game length.
- `public/index.html` - the game client
