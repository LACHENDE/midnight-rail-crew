# 銀河鉄道 Galaxy Rail Crew (greybox)

A co-op Japanese-learning game prototype. Two crew run one train flying through the stars:
- **Cab:** coal → firebox, coloured valves, brake, and the 🚂 driver's seat (speed + 3 sky lanes to dodge meteors and yokai swarms; only the driver sees what's ahead).
- **Cargo car:** water pump (みず), lamps (ランプ).
- **Roof:** junction signs (あさひ / あおば / さくら) and the lever.
- **Yokai** (おばけ, かっぱ, たぬき) sneak aboard wearing a colour word (あか / あお / きいろ). Take the お札 charm of that colour and SHOO them.

Both players see and hear every single-word Japanese order. An invisible **Director** (like Left 4 Dead's) paces it in waves: calm → build → peak → breather, holding back when the crew is swamped.

- **Play:** https://lachende.github.io/midnight-rail-crew/ (landscape phone).
- **Online:** Create a room → share the 4-letter code → Join. PeerJS (free public broker) outside claude.ai; the claude.ai room inside claude.ai.
- **Local test:** both crew on one device, with a Switch button.
- **Controls:** joystick (or WASD/arrows) to walk or drive; big button (or Space/E) to use the nearest thing. Hold it on the brake and the pump.

Built with Phaser 3.80.1 (cdnjs) and PeerJS 1.5.4 (unpkg). No build step.
