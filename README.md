# 決戦 Kessen Chess

3D chess with over-the-top anime flair. Every capture gets a cut-in banner, the captured piece shatters into shards, check sets off an alarm, and checkmate swoops the camera onto the king before it explodes. An original battle track plays the whole time.

**Play:** open `index.html` in a browser, or visit the GitHub Pages site for this repository.

## Modes

- **CPU**: three levels (Rookie, Rival, Final Boss)
- **Same screen**: two players on one device
- **Online friend**: click *Create game*, then *Copy invite link* and send it to your friend. Keep your tab open while you play.

## Online play

Online games connect the two browsers directly over WebRTC, using [PeerJS](https://peerjs.com/) and its free public matchmaking server. There's no game server and no account. If the host closes their tab, the game ends. Some strict networks, like some office or school Wi-Fi, block direct connections. If you can't connect, try a phone hotspot.

## Built with

- [three.js](https://threejs.org/) r128 (MIT): 3D rendering
- [chess.js](https://github.com/jhlywa/chess.js) 0.10.3 (BSD-2-Clause): move rules
- [PeerJS](https://github.com/peers/peerjs) 1.5.4 (MIT): online play
- Fonts from Google Fonts (SIL Open Font License): Dela Gothic One, Zen Kaku Gothic New, Noto Sans Symbols 2

The browser generates all music and sound effects live with the Web Audio API, so the game has no audio files. The music is an original composition written in code.

## License

MIT. See [LICENSE](LICENSE).
