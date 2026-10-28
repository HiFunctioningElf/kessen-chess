# 決戦 Kessen Chess

3D chess with over-the-top anime flair. Every capture gets a cut-in banner, the captured piece shatters into shards, check sets off an alarm, and checkmate swoops the camera onto the king before it explodes. An original battle track plays the whole time.

**Play:** open `index.html` in a browser, or visit the GitHub Pages site for this repository.

## Modes

- **CPU**: three levels (Rookie, Rival, Final Boss). The CPU thinks in a background thread.
- **Same screen**: two players on one device, with optional auto-flip
- **Online friend**: click *Create game*, then *Copy invite link* and send it to your friend. Keep your tab open while you play.
- **Random opponent**: get paired with whoever else is searching at the same time

## Extras

- **Red Hands minigame** every 8 full moves. The winner earns a power-up: Sensei's Hint, Takeback, Time Heist (clock games) or Rude Fishy (an eval bar with opinions, for 3 moves).
- **Power Level (戦闘力)**: a just-for-fun rating saved on your device, with style bonuses for things like en passant and underpromotion.
- Resign with a white flag, offer a draw with a handshake (or get slapped), premove up to 6 moves, and resume a game after a reload.

## Online play

Online games connect the two browsers directly over WebRTC, using [PeerJS](https://peerjs.com/) and its free public matchmaking server. There's no game server and no account. If the host closes their tab, the game ends. Some strict networks, like some office or school Wi-Fi, block direct connections. If you can't connect, try a phone hotspot.

## Built with

- [three.js](https://threejs.org/) r128 (MIT): 3D rendering
- [chess.js](https://github.com/jhlywa/chess.js) 0.10.3 (BSD-2-Clause): move rules
- [PeerJS](https://github.com/peers/peerjs) 1.5.4 (MIT): online play
- [Stockfish](https://github.com/official-stockfish/Stockfish) (GPLv3), through the [stockfish.js](https://github.com/nmrugg/stockfish.js) 10.0.2 browser build on cdnjs: powers the Rude Fishy eval bar. It's loaded from the CDN at runtime and isn't part of this repository; its source code is at the links above.
- Fonts from Google Fonts (SIL Open Font License): Dela Gothic One, Zen Kaku Gothic New, Noto Sans Symbols 2
- The en passant voice clip plays through YouTube's official embed: "How to Pronounce En Passant" by Julien Miquel. It's credited on screen and never downloaded.

The browser generates all music and sound effects live with the Web Audio API, so the game has no audio files. The music is an original composition written in code.

## License

MIT. See [LICENSE](LICENSE). Third-party components keep their own licenses.
