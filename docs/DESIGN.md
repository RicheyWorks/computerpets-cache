# Cache design

Implement against this file, not folklore.

## Identity

- Product: **Cache**
- Repo: `computerpets-cache`
- Idea: Pet Treasure Hunt
- Genre: Location / AR
- Engine: React Native
- Surface: `Expo`

## Loop

Desktop pets live on one machine. Cache takes a phone into Puyallup (or anywhere): Rui's nose widens the circle. No cache is inside a private home without owner opt-in.

## Play beats

- Pick active pet on Companion.
- Map shows fuzzy radius, not a pin.
- On site, AR sniff minigame.
- Cache loot is cosmetic / treats, never someone else's NFT.

## Neighbors

- computerpets-companion
- computerpets-ledger (finder's treats)
- computerpets-quests
- computerpets-telemetry (anonymous)

## Failure doctrine

Location permission denied → indoor practice map. GPS spoof → server rejects speed. Never store raw tracks longer than 24h.

## Hard rules

1. Minigames cannot mint or burn NFTs by themselves (Minter is the write path).
2. Stats come from lived overlay care + Dojo caps, not cash shop.
3. Species kits stay inside Lore. Illegal hybrids never spawn.
4. Fail soft: the desktop overlay process is not this process.
