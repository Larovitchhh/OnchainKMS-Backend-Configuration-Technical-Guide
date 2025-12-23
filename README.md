# OnchainKMS-Backend-Configuration-Technical-Guide
OnchainKMS Backend Configuration – Technical Guide
1. Backend Architecture Overview

The OnchainKMS backend is designed as a stateless Node.js service acting as:

API layer for the frontend (Mini App / Web)

Integration point with Farcaster

Integration point with external services (Strava, blockchain providers)

Authority layer for validation, signing and mint orchestration

Core principles:

Clear separation of concerns

No frontend rendering

Deterministic behavior (no hidden state)
