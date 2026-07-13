# Heart of Stone

Heart of Stone is a GitHub-ready foundation based on **"Developing 'boogerburg' — A Decentralized Video NFT Platform"**.

## Vision

Build a decentralized video platform where creators:
- upload and stream video content
- mint videos as NFTs
- monetize ownership directly
- avoid centralized platform lock-in

## Proposed Architecture

1. **Client Layer**: Android app (Kotlin + Jetpack Compose + Media3)
2. **Middleware Layer**: Auth/signature services + transcoding pipeline
3. **Storage Layer**: IPFS (metadata) + Arweave (immutable masters)
4. **Settlement Layer**: Stacks smart contracts anchored to Bitcoin

## Repository Goals

- Convert the concept document into an executable engineering plan
- Define contract interfaces for NFT minting and token-gated access
- Specify media ingestion and playback flows
- Track implementation milestones for MVP to production

## Source

Initialized from:
`Developing 'boogerburg'_ A Decentralized Video NFT Platform.pdf`

---

See [`docs/boogerburg-blueprint.md`](docs/boogerburg-blueprint.md) for the extracted technical outline and launch plan.
