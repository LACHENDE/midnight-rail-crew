# 真夜中の地下鉄 Midnight Rail Crew: ChatGPT prompts for the subway version

The game is now set in secret tunnels under Tokyo. The tunnels, station halls and lobby picture are drawn in code. These images would replace them.

## How to use
- **Setup:** use the same chat as before if you still have it. Otherwise attach `shiba-reference.png` and paste the style block from `prompts.md` first.
- **Naming:** save each image as PNG with the exact file name into `games/rail-crew/art/`, then tell Claude. Claude converts them for phones and puts them in the game.
- **No text:** if an image comes back with any text, letters or numbers, reply *"Same image, but remove all text."* The game writes all the Japanese itself.

---

### ★1 `key-art-subway.png`: lobby picture
Size: **landscape 1536×640**
```
Landscape 1536x640. A cosy-spooky view down an old Tokyo subway tunnel at midnight: brick arch, glowing red and amber paper lanterns along the walls, rails running to a warm light far away. The two shiba crew (red and blue bandanas, conductor caps) stand on either side of the rails in the foreground. A small friendly obake ghost peeks out of the darkness far down the tunnel. Leave the top quarter calm and dark for a title. No text.
```

### ★2 `ghost-train.png`: the ghost train
Size: **square 1024×1024, transparent background**
```
Square 1024x1024, transparent background. A spooky-cute ghost train coming straight at the viewer: a pale green-white old tram with a sleepy friendly face on its front, a glowing round headlight, wisps of ghost mist trailing behind, a little obake ghost waving from the window. Friendly, not scary for a small child. No text.
```

### 3 `station-hall.png`: a station platform (reference for the 3D halls)
Size: **landscape 1536×896**
```
Landscape 1536x896. The inside of a small forgotten Tokyo subway station at night, seen from the tracks: cream tiled walls with one coloured stripe, a blank white station name board on the wall, paper lanterns, a yellow safety line on the platform edge, two tunnel mouths leading into darkness. No characters, no text.
```

### 4 `obj-lantern.png`: lantern
Size: **square 512×512, transparent background**
```
Square 512x512, transparent background. One glowing red Japanese paper lantern hanging from a short chain, warm light. No text.
```
