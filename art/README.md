# Galaxy Rail Crew art pack

All 25 requested PNG files from [prompts.md](prompts.md), generated with the built-in image_gen tool using shiba-reference.png as the style reference.

[Browse the gallery](https://lachende.github.io/midnight-rail-crew/art/) or open index.html locally. Each gallery image links to the full PNG.

- Room backgrounds: 1536 × 896.
- Crew, yokai, props and meteor: 1024 × 1024, transparent.
- Planet strip: 1536 × 512, transparent.
- Key art: 1536 × 1024.

The exact filenames, dimensions and SHA-256 hashes are in manifest.json. The source prompts and normalization notes are in generation.json. Matching crew, valve and lantern variants were edited from their base images. The empty seat was corrected to remove an unwanted character.

This standalone repository uses art/ instead of the original monorepo path games/rail-crew/art/. These are source art assets; index.html at the repository root still uses its existing greybox renderer. The brief leaves conversion and gameplay integration to the next art pass. Scale the assets to the existing interaction positions and retain the game-rendered Japanese labels.
