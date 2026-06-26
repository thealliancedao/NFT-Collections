# NFT-Collections

NFT data and reference for every collection tracked by the platform. One folder
per collection — aDAO is the reference build; others join as new folders, fed by
the same `platform-crons` engine. Onboarding is config, not code.

## Collections
- `aDAO/`         — Alliance DAO (10,000 NFTs, LUNA staking–backed). Reference tenant.
- `Pixel-Lions/`  — (placeholder)
- `TLA-Locks/`    — TLA Lock NFTs

## Per-collection layout
Every collection folder follows the same shape:
- `metadata/` — collection metadata and traits
- `rarity/`   — intended rarity grades + marketplace (BBL) rank data
- `lore/`     — collection story
- cron outputs (added later): floor history, listings, backing per NFT

Adding a collection = add a folder with this layout. Nothing else restructures.
