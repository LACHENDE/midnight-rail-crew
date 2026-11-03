# Midnight Rail Crew (greybox)

A co-op Japanese-learning train game prototype. Two crew run around one night train: the cab (coal, firebox, coloured valves, brake), the cargo car (water pump, lamps) and the roof (junction signs + lever), plus a driver's seat (speed + 3 tracks to dodge hordes and wrecks). Spooky-cute zombies climb aboard wearing a colour word: bonk them with the matching-colour mop. Both players see and hear every single-word Japanese order; it starts calm and gets crazy busy (あか / あお / きいろ / せきたん / みず / ランプ / ブレーキ / あさひ / あおば / さくら) and must act on them. Talk to each other in any language.

- **Play:** open `index.html` from any static host (GitHub Pages works). Landscape phone.
- **Online:** Create a room → share the 4-letter code → your friend taps Join. Online play uses PeerJS (free public broker) outside claude.ai, and the claude.ai room inside claude.ai.
- **Local test:** both crew on one device, with a Switch button.
- **Controls:** joystick (or WASD/arrows) to walk, big button (or Space/E) to use the nearest thing. Hold it on the brake wheel.

Built with Phaser 3.80.1 (cdnjs) and PeerJS 1.5.4 (unpkg). No build step.
