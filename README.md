# 決戦 Kessen Chess

3D chess with over-the-top anime flair. Every capture gets a cut-in banner, the captured piece shatters into shards, check sets off an alarm, and checkmate swoops the camera onto the king before it explodes. An original battle track plays the whole time.

**Play:** open `index.html` in a browser, or visit the GitHub Pages site for this repository.

## Modes

- **CPU**: three levels (Rookie, Rival, Final Boss). The CPU thinks in a background thread.
- **Same screen**: two players on one device, with optional auto-flip
- **Online**: click *Create game*, then *Copy invite link* and send it to a friend. Keep your tab open while you play.
- **Friends**: after an online game, tap ☆ next to your opponent to save them. They appear under *Friends*; tap *Play* and you'll meet in your own private room (whoever taps first waits for the other). Saved on this device.
- **Quick match**: get paired with someone else searching right now who picked the same game mode (Classic or Kessen) and time control. *Find an online match* on the start screen jumps straight in.

## Extras

- **Minigames**, taking turns, each a full-screen duel of about half a minute. They come every 8 moves while the board is full, less often as pieces come off (every 12 moves at 12–19 pieces, every 18 at 7–11, not counting kings), and not at all in the endgame (6 pieces or fewer), which is pure chess:
  - **居合 Quick-draw**: wait for 斬!!, then draw first. Watch for fakes. A draw of 100 ms or less is **GODSPEED**: a cut-scene and an instant win.
  - **斬 Blade Timing**: both blades sweep at once; stop yours in the gold. Five cuts, most points wins.
  - **苦無 Kunai Storm**: race to land your kunai through a spinning ring of iron blocks. Best of 3 stages.
  - **☆ Magical Dance**: HENSHIN!! A 30-second rhythm dance-off as magical girls.

  Against the CPU you face Ronin; online, both screens get the very same challenge. On one shared screen you choose how you sit before the match: **face to face** (the screen flat between you, each half turned to its player) or **pass the phone** (one at a time, the same challenge for both). The winner earns a power-up: Sensei's Hint, Takeback, Time Heist (clock games) or Rude Fishy (an eval bar with opinions on every move, yours and theirs, for 3 moves; not in same-screen games, since both players would see it). Your next minigame and your power-ups show in the corner of the board.
- **Style meters**: every game, each player has a style meter that climbs from D (Dull) through C, B, A and S to SSS (SSSensational!!!) as they pull off stylish moves: rare and meme openings (the Bongcloud, the Grob, the Englund, Double Bongcloud…), forks, pins, skewers, discovered and double checks, underpromotions, special checkmates and minigame wins.
- **Power Level (戦闘力)**: a just-for-fun rating saved on your device (vs the CPU and online; style only counts in games of 10+ moves, and less against easier CPUs), climbing an anime rank ladder from *Background Extra* to *IT'S OVER 9000!!*. Style bonuses pop up the moment you earn them, once per game each: knight forks (*Family Fork* for king and queen), double check, en passant, underpromotion (the biggest payouts: +200 to +300, and +400 for an underpromotion checkmate), *Horse Delivery*, the king strolling into enemy land, smothered mates, mates by castling or en passant, back-rank mates, speedruns, comebacks, flawless and clutch wins, minigame wins and GODSPEED. A few taxes too, like bringing the queen out too early.
- **En passant** gets a special movie: a beret, a baguette slap, and an uncomfortably long slow-motion action replay (tap to skip). Taking a pawn any other way keeps the action but skips the banners.
- Resign with a white flag, offer a draw with a handshake (or get slapped), premove up to 6 moves, and resume a game after a reload.
- **📜 Games**: every finished game is saved on your device. Open one to step through it move by move (buttons or arrow keys). Rude Fishy (Stockfish) grades each move with names that are kinder than the usual ones: 🌌 Galaxy Brain (best move), 👨‍🍳 Chef's Kiss, 🍙 Solid Snack, 🍜 Wobbly Noodle (inaccuracy), 🌼 Oopsie Daisy (mistake) and 🍌 Banana Peel (blunder). It also shows what Rude Fishy would have played instead.
- **WeLo**: Kessen's own rating (it replaced Elo), with dojo belts from White Belt to Grand Sensei. Everyone has one: online games rate you against your opponent's WeLo, CPU games against the CPU's (Rookie 800, Rival 1200, Final Boss 1700) at half the swing. Your first 15 games are placement. An online game you walk out of counts as a loss, and a CPU game where you used Undo is practice (unrated).
- **Fighter names** are checked as you type: 2–16 characters, no reserved or rude names.
- **Trailer**: open the game with `#trailer` on the end of the address and press FIGHT! for a two-minute goofy montage, ready to screen-record.
- On phones, minigames go full screen, the screen stays awake during a duel, and big hits give a little buzz.

## Donations

The 💝 **Donate** button links to fundraiser pages for six registered Australian charities. **Your donation goes straight to the charity. Kessen Chess never handles the money.** Each button goes to a Kessen Chess fundraiser page on the charity's own fundraising platform, or, until that page exists, to the charity's official donation page.

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

**Donations made elsewhere.** Someone might give on a charity's own website instead of through a Kessen page. Those gifts show up in the counter only once they're listed in [`donations-ledger.json`](donations-ledger.json), the public receipts ledger. Add one entry per checked receipt: the charity's ABN, the amount in AUD, the date, and optionally how many people gave and where the (redacted) receipt can be seen. The game adds these on top of each page's live total, so never list a gift that was made through a Kessen fundraiser page, or it would count twice.

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
- Magical Dance songs, both CC0 (public domain) from OpenGameArt, in `audio/`: ["Anime-esque Intro-Outro Theme"](https://opengameart.org/content/anime-esque-intro-outro-theme) by CleytonKauffman, and ["kawaii 8bit"](https://opengameart.org/content/kawaii-8bit) by haruta (cut and sped up 1.3×). Each round plays one of them.
- The en passant voice clip plays through YouTube's official embed: "How to Pronounce En Passant" by Julien Miquel. It's credited on screen and never downloaded.

Apart from the Magical Dance songs, the browser generates all music and sound effects live with the Web Audio API. The battle music is an original composition written in code.

## License

MIT. See [LICENSE](LICENSE). Third-party components keep their own licenses.
