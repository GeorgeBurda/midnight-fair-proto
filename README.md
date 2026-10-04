# Midnight Fair — pachinko-slot prototype

Live: https://georgeburda.github.io/midnight-fair-proto/

Tap anywhere to release a pack of 10 wisps (bet 10); tap again to skip to the result.

URL params: `?seed=N`, `?bonus=train|crypt|pumpkin|train+crypt|...|midnight`, `?jackpot=mini|minor|major|grand`,
`?turbo=1`, `?debug=1` (steering overlay), `?blind=1` (blind test: half the packs are pure physics), `?mute=1`, `?fresh=1`, `?chain=N` (test: Multiball chain length), `?recall=1`.

Single self-contained `index.html` + `assets/`. Source and test tooling live outside this deploy repo.
