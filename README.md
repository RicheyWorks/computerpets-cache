# Cache

**Pet Treasure Hunt** — Geocaching / AR hunt using pet instincts to find hidden world caches.

Part of the [ComputerPets](https://github.com/RicheyWorks/computerpets) universe. Map: [computerpets-ecosystem](https://github.com/RicheyWorks/computerpets-ecosystem).

> Status: **design scaffold**. Gameplay contract is frozen. Engine choice is the one in the brief. Implementation comes next.

## Loop

Desktop pets live on one machine. Cache takes a phone into Puyallup (or anywhere): Rui's nose widens the circle. No cache is inside a private home without owner opt-in.

## Genre & engine

- Genre: **Location / AR**
- Engine: **React Native**
- Stack: React Native · Expo · geofence caches · optional AR markers · instincts = search radius
- Default surface: `Expo`

## How you play

1. Pick active pet on Companion.
2. Map shows fuzzy radius, not a pin.
3. On site, AR sniff minigame.
4. Cache loot is cosmetic / treats, never someone else's NFT.

## Talks to

- computerpets-companion
- computerpets-ledger (finder's treats)
- computerpets-quests
- computerpets-telemetry (anonymous)

## Failure doctrine

Location permission denied → indoor practice map. GPS spoof → server rejects speed. Never store raw tracks longer than 24h.

Canon rules that never yield:

- 210 living kinds. No illegal hybrids.
- Overlay pets can get tired, sick, or hide. Tokens are not burned by a minigame.
- Desktop walk stays the main quest. Closing Cache must leave Rui walking.

## Layout

```
computerpets-cache/
  README.md
  LICENSE
  docs/DESIGN.md
  src/                implementation lands here
```

## Run (Windows)

```powershell
cd app; npm install; npx expo start
```

Meet Rui first via the [flagship start-here](https://github.com/RicheyWorks/computerpets/blob/main/docs/START-HERE.md). This game is optional.

## License

MIT. See [LICENSE](LICENSE).

---

*Two hundred ten living kinds. Keep them so a line does not go quiet.*
