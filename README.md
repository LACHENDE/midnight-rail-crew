# 銀河鉄道 Galaxy Rail Crew

A co-op Japanese-learning game for two players: one magic train flying through the stars.

- **🚀 Driver:** flies the train through a dark nebula in 3D with rocket controls. ◀ ▶ ▲ ▼ turn the nose, THRUST pushes, and the train keeps drifting until you BRAKE. A blue marker shows where you're really drifting. There are no beacons, so you can't find anything on your own. Follow the gold ring the navigator sets, and check that the gate sign (in kana: うみ, やま…) is the right one.
- **📡 Navigator:** sits at a brass cockpit console with the only radar. The radar is heading-up, so left on the radar is the driver's left. Places show as pictures only (🌊 🗻 🌙 🦊 ⛩️ 🌸 ☁️ 🍡), with ▲/▼ for above or below. The navigator reads a passenger's 🎫 ticket in kana, then taps the matching picture to set the course. From wave 5, meteors and yokai show on the radar before the driver can see them: warn your driver!
- Setting the course works by tapping, so you can play even if you don't share a language. Talking makes it faster.
- You swap jobs after wave 3.
- **6 teaching waves**, made for players who know no Japanese yet. Each wave first teaches its new words with sound, meaning and picture. Then comes 45 seconds of play, then a breather. A hidden Director boards fewer passengers when you're swamped. The first two times a word appears, its meaning shows on the ticket by itself.

**Play:** https://lachende.github.io/midnight-rail-crew/ (landscape phone).
- **Online:** Create a room → share the 4-letter code → Join. It uses PeerJS outside claude.ai and the claude.ai room inside it.
- **Local test:** both players on one device, with a Switch view button. On a keyboard: arrow keys turn, W or Space thrusts, S or Shift brakes.

**Built with** three.js r128 (cdnjs) and PeerJS 1.5.4 (unpkg). There is no build step. The art is in `art/`, with phone-sized webp copies in `art/web/`.

**Tests:** `tests/test33_galaxy.js` in the Kotoba Shiba project covers local play, two phones over PeerJS, and the claude.ai room.
