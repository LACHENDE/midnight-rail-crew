# 銀河鉄道 Galaxy Rail Crew

A co-op Japanese-learning game for two players: one magic train flying through the stars.

- **🚀 Driver:** flies the train through space in 3D (joystick to steer, BOOST to speed up). Every place is a golden ring with a station sign, and **the signs are in kana only** (うみ, やま, つき, きつね…). Fly through the right ring to drop off the passengers. Watch out for meteors and yokai later on.
- **🗺 Navigator:** has the galaxy map, with places shown as **pictures only** (🌊 🗻 🌙 🦊 ⛩️ 🌸 ☁️ 🍡). Places start as "?" and turn into pictures once the driver flies near them. The navigator also holds the passengers' 🎫 tickets in kana, so they read the ticket, find the picture, and guide the driver: "left! up! the moon is behind you!"
- Only the driver sees space and only the navigator sees the map and tickets, so you have to talk. You swap jobs after wave 3.
- **6 teaching waves**, made for players who know no Japanese yet. Each wave first teaches its new words with sound, meaning and picture. Then comes 45 seconds of play, then a breather. A hidden Director boards fewer passengers when you're swamped. The first two times a word appears, its meaning shows on the ticket by itself.

**Play:** https://lachende.github.io/midnight-rail-crew/ (landscape phone).
- **Online:** Create a room → share the 4-letter code → Join. It uses PeerJS outside claude.ai and the claude.ai room inside it.
- **Local test:** both players on one device, with a Switch view button. On a keyboard, steer with the arrow keys / WASD and boost with Shift or Space.

**Built with** three.js r128 (cdnjs) and PeerJS 1.5.4 (unpkg). There is no build step. The art is in `art/`, with phone-sized webp copies in `art/web/`.

**Tests:** `tests/test33_galaxy.js` in the Kotoba Shiba project covers local play, two phones over PeerJS, and the claude.ai room.
