# type-kart
A pub-friendly typing race game. Drive by typing. Every correct word is gas, every typo is a banana skin.

**Play:** https://ukx060.github.io/type-kart/

## Modes

| Mode | How |
|---|---|
| Solo vs CPU | CPU rival speeds up from ~22 wpm (L1) to ~58 wpm (L10) |
| Host online race | Get a 5-character room code; share the code or the copied link |
| Join | Enter the code (or open the shared link) |

- Type each word and press Space. First to 20m wins.
- A typo costs 1m and a 0.7 s spin-out.
- Online: two players, peer-to-peer (WebRTC via PeerJS public signaling server). Host controls start, level and decides the winner.
- Leaderboard is stored in each browser's localStorage.

## Run locally

Open `index.html` in a browser, or serve the folder (`python3 -m http.server`). No build step.

`vendor/peerjs.min.js` is PeerJS 1.5.5 (MIT, see `vendor/peerjs-LICENSE`).
