# Midnight Rail Crew (greybox)

A co-op Japanese-learning train game prototype. Two crew run around one night train: the cab (coal, firebox, coloured valves, brake) and the roof (junction signs + lever). Each player hears their own single-word Japanese orders (あか / あお / きいろ / せきたん / ブレーキ / あさひ / あおば / さくら) and must act on them. Talk to each other in any language.

- **Play:** open `index.html` from any static host (GitHub Pages works). Landscape phone.
- **Online:** Create a room → share the 4-letter code → your friend taps Join. Online play uses PeerJS (free public broker) outside claude.ai, and the claude.ai room inside claude.ai.
- **Local test:** both crew on one device, with a Switch button.
- **Controls:** joystick (or WASD/arrows) to walk, big button (or Space/E) to use the nearest thing. Hold it on the brake wheel.

Built with Phaser 3.80.1 (cdnjs) and PeerJS 1.5.4 (unpkg). No build step.
