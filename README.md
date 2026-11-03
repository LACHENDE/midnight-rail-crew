# 銀河鉄道 Galaxy Rail Crew (greybox)

A co-op Japanese-learning game prototype for two players: one train flying through the stars.

- **🚂 Driver:** a full-screen galaxy map with places shown as pictures only (🌊 🗻 🌙 🦊 ⛩️ 🌸 ☁️ 🍡), mostly hidden in fog. Tap a neighbouring place to go there. Every stop reveals more.
- **🧰 Crew:** runs around the train (cab, cargo car, roof) keeping it alive: coal for the fire, water, coloured valves, lamps, and yokai that sneak aboard (shoo them with the お札 charm of their colour). The crew also reads each passenger's 🎫 ticket in Japanese (うみ, やま, つき, きつね…) and tells the driver where to go.
- Only the crew can read the tickets and only the driver sees the map, so you have to talk. You swap jobs after wave 3.
- **6 teaching waves**, made for players who know no Japanese yet. Each wave first teaches its new words with sound, meaning and picture, then about 35 seconds of play, then a breather. A hidden Director holds trouble back when the crew is swamped. The first two times a word appears, its meaning shows by itself.

**Play:** https://lachende.github.io/midnight-rail-crew/ (landscape phone). **Online:** Create a room → share the 4-letter code → Join. PeerJS outside claude.ai, the claude.ai room inside it. **Local test:** both players on one device, with a Switch button.

Built with Phaser 3.80.1 (cdnjs) and PeerJS 1.5.4 (unpkg). No build step.
