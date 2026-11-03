# 真夜中の地下鉄 Midnight Rail Crew

A co-op Japanese-learning game for two players: the last train of the night, lost in the secret tunnels under Tokyo.

- **🚂 Driver (3D cab):** you see only as far as your headlight, and you never see the map.
  - **Controls:** hold GO, BRAKE to stop in a station. Before each fork, pick a tunnel with ◀ ▲ ▶. The signal lamps turn green over the tunnel you picked.
  - **Signs:** every tunnel and station sign is in kana (うみ, やま, きつね…).
  - **Dead ends:** stop, then ⇄ to drive from the other cab.
  - **Calling:** tap 📍 to call out the station you're in.
- **🗺 Navigator (paper map):** stations are drawn as pictures only (🗼 🌊 🗻 🌙 🦊 ⛩️ …), and **the map never shows where the train is**.
  - **Find the train:** listen to your driver, find the station's picture, and work out which way you're heading.
  - **Tools:** ✏️ draws on the map to keep track. 📡 PING (3 per wave) flashes the train's position when you're lost.
  - **Calling:** tap a picture to call out its name to the driver.
- **Passengers:** faces on the map are passengers waiting. Stop there to pick them up. Their 🎫 tickets (kana) are only on the navigator's screen.
  - **Stopping:** stop in the right station to drop them off. Stop right on the mark for ぴったり!
- **👻 The ghost train:** from wave 3, the peak of each wave is a chase.
  - **Who sees it:** the navigator sees the ghost on the map. The driver hears its bell getting closer and sees its glow down the tunnel.
  - **Escape:** get to the shrine ⛩️. A ghost that reaches you there is banished.
- **6 teaching waves**, made for players who know no Japanese yet.
  - **Each wave:** it first teaches its new stations with sound, meaning and picture, then opens their tunnels. A breather follows.
  - **Beginner help:** new words show romaji for their first wave.
  - **Swap:** you swap jobs after wave 3.
- **No shared language needed:** calls are spoken Japanese words, so partners who don't share a language can still play. Talking makes it faster.

**Play:** https://lachende.github.io/midnight-rail-crew/ (landscape phone).
- **Online:** Create a room → share the 4-letter code → Join. It uses PeerJS outside claude.ai and the claude.ai room inside it.
- **Local test:** both players on one device, with a Switch view button.
- **Keyboard:** ↑/W go, ↓/S brake, ←/→ pick a tunnel, F switches cab.

**Built with** three.js r128 (cdnjs) and PeerJS 1.5.4 (unpkg). There is no build step.
- **Code-drawn:** the tunnels, station halls and lobby picture.
- **From the art pack:** the crew portraits, the ghost and the sign board (`art/web/`).
- **New art:** `art/prompts-subway.md` has ChatGPT prompts for subway art.

**Tests:** `tests/test34_tunnel.js` in the Kotoba Shiba project covers local play, two phones over PeerJS, and the claude.ai room.
