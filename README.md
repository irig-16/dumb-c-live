# Dumb C Live

Classic dumb charades with Tamil films, one phone each. Only the actor's phone shows the film, the other team picks it for them, and everyone sees the clock and the score.

## Play

Open `index.html` in a browser, or host it with GitHub Pages or Netlify.

1. One player hosts and shares the 4-letter code, invite link or QR.
2. Everyone joins on their own phone and picks a team.
3. Take turns acting while your team guesses before the clock runs out.

## Features

- A deck of 220 Tamil films across difficulty levels, with alternate titles accepted.
- Host-run timer and scoreboard, synced to every phone.
- Voice chat, reactions, sounds and vibration on Android.

## How it works

It's one self-contained HTML file. Devices connect peer to peer over WebRTC using [PeerJS](https://peerjs.com) and its free public broker. There's no backend, and the host's phone runs the game.

## Third-party code

- PeerJS 1.5.5 (MIT)
- qrcode-generator 1.4.4 (MIT, Kazuhiko Arase)
