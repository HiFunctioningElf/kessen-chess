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

## Donations

The 💝 **Donate** button links to fundraiser pages for six registered Australian charities. **Your donation goes straight to the charity. Kessen Chess never handles the money.** Each fundraiser page is set up on the charity's own fundraising platform.

| Charity | Cause | ABN | ACNC register |
|---|---|---|---|
| Australian Conservation Foundation | Environment | 22 007 498 482 | [profile](https://www.acnc.gov.au/charity/charities/d2e1368f-38af-e811-a960-000d3ad24282/profile) |
| Starlight Children's Foundation Australia | Sick kids | 80 931 522 157 | [profile](https://www.acnc.gov.au/charity/charities/af96203d-39af-e811-a963-000d3ad24077/profile) |
| Beyond Blue | Mental health | 87 093 865 840 | [profile](https://www.acnc.gov.au/charity/charities/8bae377e-38af-e811-a963-000d3ad244fd/profile) |
| Foodbank Queensland | Hunger | 89 067 251 209 | [profile](https://www.acnc.gov.au/charity/charities/8800d743-39af-e811-a962-000d3ad24a0d/profile) |
| Craniofacial Australia (Australian Cranio-Maxillo Facial Foundation) | Craniofacial care | 29 008 155 780 | [profile](https://www.acnc.gov.au/charity/charities/9f7e79c5-38af-e811-a95e-000d3ad24c60/profile) |
| Cancer Council Queensland | Cancer | 48 321 126 727 | [profile](https://www.acnc.gov.au/charity/charities/0655bad9-39af-e811-a963-000d3ad24077/profile) |

**Kessen Chess is not affiliated with or endorsed by these charities.**

The panel also has the 🪙 **Penny Dropper**, a Plinko board that picks a charity at random for you. It's just for fun; no money is involved.

### Live totals: only real numbers

The "$X raised by Y Kessen players" counter adds up the totals that the fundraising platforms publish for these pages. Nothing is estimated. If a page's total can't be read, that page shows **Donate** without a number. What was checked (October 2026):

| Platform | Who uses it here | Can a web page read the total? |
|---|---|---|
| Open Collective | the dev's holiday fund | **Yes.** Public GraphQL API, readable from the browser. Shows the full amount given (`totalAmountReceived`) and the number of contributors. |
| JustGiving | ACF, Beyond Blue, Foodbank QLD | **With a key.** The API answers browsers, but needs a free App ID from developer.justgiving.com. Counts only money donated online through the page (`totalRaisedOnline`), not offline amounts a page owner types in. Not yet tried with a real page. |
| GoFundraise | Starlight (Australia) | No public total API found. |
| Cancer Council QLD fundraising site / Do It For Cancer | Cancer Council QLD | No public total API found. |
| GiveNow CrowdRaiser, MyCause | Craniofacial Australia | No public total API found. |
| fundraise.beyondblue.org.au | Beyond Blue | No public total API found. |

Totals are cached in the browser for 10 minutes.

### Developer's holiday fund

The 🏝️ **Developer's holiday fund** links to the developer's Open Collective, where people can shout a coffee. A penny jar fills from the collective's real total toward the goals in order: a $250 AUD CRKD Gibson Guitar, then a $3,000 AUD family holiday to Tasmania. Past both, it shows how far over budget it is. Each goal can show a receipt and a photo or video once it's done. A `SPLIT_MODE` switch can later send half of every coffee to the charity the supporter picks.

To set it all up, fill in the `CHARITIES` and `COFFEE` settings at the top of the donations code in `index.html`. Anything left as `TODO` stays hidden or shows "Coming soon".

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
