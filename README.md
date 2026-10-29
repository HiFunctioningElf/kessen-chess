# 決戦 Kessen Chess

3D chess with over-the-top anime flair. Every capture gets a cut-in banner, the captured piece shatters into shards, check sets off an alarm, and checkmate swoops the camera onto the king before it explodes. An original battle track plays the whole time.

**Play:** [kessenchess.com](https://kessenchess.com), or open `index.html` in a browser.

## Modes

- **CPU**: three levels (Rookie, Rival, Final Boss). The CPU thinks in a background thread.
- **Same screen**: two players on one device, with optional auto-flip
- **Online**: click *Create game*, then *Copy invite link* and send it to a friend. If they're in the same room, they can scan the QR code under the code instead. Keep your tab open while you play.
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
- **📜 Match history**: every finished game is saved on your device, and Rude Fishy (Stockfish) grades it in the background straight away. The review has a board with coordinates and Fishy's best move as an arrow, an eval bar, an advantage graph you can tap to jump around, accuracy and average loss for each player, the opening's name, the key moments, and each move graded with the usual chess symbols: !! Brilliancy, ★ Fishy's Pick (best move), ! Sharp, ✓ Decent, ?! Sloppy (inaccuracy), ? Slip-up (mistake), ?? Howler (blunder) and ✗ Missed Chance. On a move that went wrong it shows the better move and the line after it, and **Try again** lets you replay that position and look for something better. You can also copy the game as an annotated PGN. Accuracy uses Lichess's published win-chance and accuracy formulas (no Lichess code).
- **WeLo**: Kessen's own rating (it replaced Elo), with dojo belts from White Belt to Grand Sensei. Everyone has one: online games rate you against your opponent's WeLo, CPU games against the CPU's (Rookie 800, Rival 1200, Final Boss 1700) at half the swing. Your first 15 games are placement. An online game you walk out of counts as a loss, and a CPU game where you used Undo is practice (unrated).
- **Fighter names** are checked as you type: 2–16 characters, no reserved or rude names.
- **🎬 Clips**: while you play, the game keeps the last 12 to 24 seconds (the board, the particles, the captions and the sound). Tap 🎬 Clip on the board to turn them into a video with a small Kessen Chess tag: **Share** opens your phone's share sheet (TikTok, Instagram, Messages…) and **Save video** downloads it. Clips stay on your device until you share them. The captions are redrawn from the page, so they're close to the real thing rather than pixel-perfect.
- **Trailer**: open the game with `#trailer` on the end of the address and press FIGHT! for a three-minute goofy montage, ready to screen-record: 100% free (no subscription, no fees, just vibes), 100% online, made to fundraise; captures, castling, the full en passant movie, promotion, a few seconds of each minigame against Ronin, Rude Fishy, checkmate, the game review on the Opera Game (Morphy, 1858), and the Android goal. Nothing in it is saved to your history or ratings.
- On phones, minigames go full screen, the screen stays awake during a duel, and big hits give a little buzz.

## Donations

The 💝 **Donate** button links to two charities. **Your donation goes straight to the charity. Kessen Chess never handles the money.** Each button goes to the Kessen Chess fundraiser page on the charity's own fundraising site.

**Goals.** Each fundraiser aims for $1,000 (US$1,000 for Smile Train, A$1,000 for Foodbank Queensland). A banner under the header shows both goals, and **if both are reached, Kessen Chess comes to Android**. The bars fill only from the totals the fundraising sites publish (see below); until a page's total can be read, the banner shows just its goal. The goals and the promise are set by `goal` in `CHARITIES` and `GOAL_PRIZE` in `index.html`.

| Charity | Cause | Registration | Fundraiser pages |
|---|---|---|---|
| Smile Train | Cleft surgery for kids | US charity, EIN 13-3661416 ([IRS records](https://projects.propublica.org/nonprofits/organizations/133661416)). Not tax-deductible in Australia. | [Kessen Chess: Checkmate for Smiles](https://www.mysmiletrain.org/campaigns/Kessen-Chess--Checkmate-for-Smiles) (DonorDrive) |
| Foodbank Queensland | Hunger | ABN 89 067 251 209 ([ACNC profile](https://www.acnc.gov.au/charity/charities/8800d743-39af-e811-a962-000d3ad24a0d/profile)) | [Kessen Chess on JustGiving](https://www.justgiving.com/page/kessen-chess) |

**Kessen Chess is not affiliated with or endorsed by these charities.**

**Fundraiser cover photo.** [`fundraiser/justgiving-cover.png`](fundraiser/justgiving-cover.png) is a JustGiving cover photo for the Foodbank Queensland page, in the game's own style. It is 1000×563 (16:9), the largest size JustGiving accepts; a 2× copy is next to it. To change it, edit `fundraiser/justgiving-cover.html` and screenshot its `.cover` element at 1000×563. [`fundraiser/smile-profile.png`](fundraiser/smile-profile.png) is a 1000×1000 profile photo for the Smile Train page (a smiling king with a subtle cleft lip, everything inside the middle circle so a round crop keeps it); its source is `fundraiser/smile-profile.html`.

The panel also has the 🪙 **Penny Dropper**, a Plinko board that picks a charity at random for you. It's just for fun; no money is involved.

### Live totals: only real numbers

The "$X raised by Y Kessen players" counter adds up the totals that the fundraising platforms publish for these pages. Nothing is estimated. If a page's total can't be read, that page shows **Donate** without a number. What was checked (October 2026):

| Platform | Who uses it here | Can a web page read the total? |
|---|---|---|
| Open Collective | the dev's holiday fund | **Yes.** Public GraphQL API, readable from the browser. Shows the full amount given (`totalAmountReceived`) and the number of contributors. |
| DonorDrive (mysmiletrain.org) | Smile Train | **Yes.** Public API, readable from the browser with no key (`sumDonations`, `numDonations`). Totals are in US dollars, so they show on Smile Train's card but aren't added to the AUD counter. **Not switched on yet:** it needs the page's participant ID in `CHARITIES`. |
| JustGiving | Foodbank QLD | **With a key.** The API answers browsers, but needs a free App ID from developer.justgiving.com. Counts only money donated online through the page (`totalRaisedOnline`), not offline amounts a page owner types in. Not yet tried with a real page. **Not switched on yet:** the page is set (`kessen-chess`), but `JUSTGIVING_APP_ID` is still `TODO`. |

**Donations made elsewhere.** Someone might give on a charity's own website instead of through a Kessen page. Those gifts show up in the counter only once they're listed in [`donations-ledger.json`](donations-ledger.json), the public receipts ledger. Add one entry per checked receipt: the charity's ABN, the amount in AUD, the date, and optionally how many people gave and where the (redacted) receipt can be seen. The game adds these on top of each page's live total, so never list a gift that was made through a Kessen fundraiser page, or it would count twice.

Totals are cached in the browser for 10 minutes.

### Developer's holiday fund

The 🏝️ **Developer's holiday fund** links to the developer's Open Collective, where people can shout a coffee. A penny jar fills from the collective's real total toward the goals in order: a $250 AUD CRKD Gibson Guitar, then a $3,000 AUD family holiday to Tasmania. Past both, it shows how far over budget it is. Each goal can show a receipt and a photo or video once it's done. A `SPLIT_MODE` switch can later send half of every coffee to the charity the supporter picks.

To set it all up, fill in the `CHARITIES` and `COFFEE` settings at the top of the donations code in `index.html`. Anything left as `TODO` stays hidden or shows "Coming soon".

## Leaderboard and unique names

The 🏆 **Leaderboard** shows the top 20 players by WeLo (the top 50 on request), and where you stand. To stay well inside Firebase's free daily allowance, each device keeps the board for 5 minutes, so opening it again doesn't read anything. Fighter names are unique: nobody can take a name someone else holds, capitals or not, and rude names are refused. It runs on Firebase's free plan. Until Firebase is set up, the button stays hidden and names stay per device.

**How it stays fair.** The rules in [`firebase/firestore.rules`](firebase/firestore.rules) are checked by Firebase's servers, so no browser can get around them: one name per player, names refused by the same rude-word lists as the game, and nobody can change anyone else's entry. A leaderboard WeLo starts at 1000 with a player's first rated game, and each later update may add one game, move it by at most 64 and come at least a minute after the last. Results are still reported by each player's own browser, so like WeLo itself it's for fun.

**Privacy.** Each device signs in to Firebase anonymously: no email, no password, nothing personal. The board shows your fighter name, crest, belt, WeLo and games played.

### Setting up Firebase (about 10 minutes, free, no credit card)

1. Go to [console.firebase.google.com](https://console.firebase.google.com) and **Create a project** (call it `kessen-chess`; you can turn Google Analytics off).
2. **Build → Authentication → Get started → Sign-in method → Anonymous → Enable → Save.**
3. **Build → Firestore Database → Create database.** Choose **Start in production mode** and a location near your players (for Australia, `australia-southeast1 (Sydney)`).
4. In Firestore, open the **Rules** tab, replace everything with the contents of [`firebase/firestore.rules`](firebase/firestore.rules), and **Publish**.
5. Click the **gear → Project settings → General**, scroll to **Your apps**, click the **`</>`** (web) icon, name it `Kessen Chess` (no Firebase Hosting) and **Register app**. Copy the `apiKey` and `projectId` it shows.
6. In `index.html`, find `const FIREBASE = {apiKey: 'TODO', projectId: 'TODO'};` and paste them in.
7. Recommended: lock the key to your site. In [Google Cloud console → APIs & Services → Credentials](https://console.cloud.google.com/apis/credentials), open the **Browser key**, choose **Websites**, and add `kessenchess.com/*` and `www.kessenchess.com/*`.

A Firebase web `apiKey` isn't a secret: it only says which project to talk to, and the rules decide what anyone may do. On the free (Spark) plan nothing can be charged: if the daily allowance (50,000 reads, 20,000 writes) ever runs out, the leaderboard simply pauses until the next day.

To try changes locally, `firebase/firebase.json` runs the Firebase emulator (`firebase emulators:start --only auth,firestore` in that folder).

## Online play

Online games connect the two browsers directly over WebRTC, using [PeerJS](https://peerjs.com/) and its free public matchmaking server. There's no game server and no account. If the host closes their tab, the game ends. Some strict networks, like some office or school Wi-Fi, block direct connections. If you can't connect, try a phone hotspot.

**Privacy.** Online games are a direct connection between the two browsers, so each player's browser learns the other's IP address, as with any peer-to-peer game or call. Quick match pairs you with strangers, so bear that in mind. The other player also sees your fighter name, crest, Power Level, WeLo and a random device id (used for Friends). Nothing else about you is sent, and there is no account.

**Fair play.** The host's tab checks every change from the friend: one legal move at a time with their own pieces on their own turn, takebacks and time heists only with the power-up, no taking the host's seat, resigning for the host or adding time to a clock. The friend's browser only checks that the host never moves the friend's pieces, since the host's copy is the real one. Minigame wins and clocks are reported by the players' own browsers, which no two-browser game can fully verify, so Power Level and WeLo are for fun.

The bars next to the move counter show your connection to your friend, from the round trip time of a ping sent every few seconds: 4 bars under 150 ms, 3 under 300 ms, 2 under 600 ms, 1 above that, and *Offline* when nothing has arrived for 12 seconds.

The host's tab holds the real copy of the game. The friend's moves and other changes go to the host as numbered patches, and the host applies each one once, in order, and confirms it. Until then the friend's screen shows them on top of the host's last state. Both sides re-send every few seconds, so nothing sent during a hiccup is lost.

## Built with

- [three.js](https://threejs.org/) r128 (MIT): 3D rendering
- [chess.js](https://github.com/jhlywa/chess.js) 0.10.3 (BSD-2-Clause): move rules
- [PeerJS](https://github.com/peers/peerjs) 1.5.4 (MIT): online play
- [qrcode-generator](https://github.com/kazuhikoarase/qrcode-generator) 1.4.4 by Kazuhiko Arase (MIT): draws the invite QR code.
- [Stockfish](https://github.com/official-stockfish/Stockfish) (GPLv3), through the [stockfish.js](https://github.com/nmrugg/stockfish.js) 10.0.2 browser build on cdnjs: powers the Rude Fishy eval bar. It's loaded from the CDN at runtime and isn't part of this repository; its source code is at the links above.

three.js, chess.js, PeerJS and qrcode-generator load from [jsDelivr](https://www.jsdelivr.com/)'s copy of their npm packages, each with a Subresource Integrity hash: the browser refuses a file that differs by even one byte from the published release. Stockfish can't be pinned the same way. It runs in a Web Worker, which can't see the page, your saved data or the game connection, so a tampered copy could only give bad analysis.

- Fonts from Google Fonts (SIL Open Font License): Dela Gothic One, Zen Kaku Gothic New, Noto Sans Symbols 2
- Magical Dance songs, both CC0 (public domain) from OpenGameArt, in `audio/`: ["Anime-esque Intro-Outro Theme"](https://opengameart.org/content/anime-esque-intro-outro-theme) by CleytonKauffman, and ["kawaii 8bit"](https://opengameart.org/content/kawaii-8bit) by haruta (cut and sped up 1.3×). Each round plays one of them.
- The en passant voice is the developer's own recording (`audio/en-passant.mp3`), pitched down and made a little robotic.

Apart from the Magical Dance songs, the browser generates all music and sound effects live with the Web Audio API. The battle music is an original composition written in code.

## License

MIT. See [LICENSE](LICENSE). Third-party components keep their own licenses.
