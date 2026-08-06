# VeVe MCP Optimizer — feature demo

Standalone build of the **MCP Optimizer** from the VeVe Collect community toolset, for review.

Paste a VeVe wallet address (VeVe app → Wallet → Send/Receive OMI → **Receive**) and the page:

1. reads that wallet's **real on-chain holdings** from the public [collectscan](https://collectscan.com) explorer,
2. recomputes **Master Collector Points** using VeVe's published formula — including set bonuses and
   comic-duplicate diminishing for Rare / Ultra Rare / Secret Rare,
3. ranks the whole catalogue by **MCP/day per $1**, priced from the live VeVe Gem market and the
   StackR OMI market, whichever is cheaper.

Read-only: no login, no signing, no keys, nothing stored. Everything runs in the browser.

Deep link with a wallet pre-filled: `?wallet=0x…`

Full toolset: https://simonjickeli.github.io/veve-collect-demo/ · Not affiliated with VeVe / Collect.
