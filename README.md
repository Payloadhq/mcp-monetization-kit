# MCP Monetization Kit
*Charge per tool call on your MCP server. A commercial product by Payload (v1.0.1).*
> **Payload** — small, sharp tools for developers. Developer portal: https://payloadhq.github.io/


30,000+ MCP servers are indexed across directories and marketplaces — and none of those marketplaces pay their creators. If you run a useful MCP server, your only options are donations or building billing infrastructure from scratch.

This kit is the third option: wrap each tool with a price. Callers without payment get machine-readable payment requirements; callers who pay get results. Free tools stay free, and you can grant free quotas (e.g. 3 free calls, then $0.025 each).

**What's inside the paid kit**
- Paid tool registry: registerTool / callTool / listTools with payment enforcement
- Per-tool pricing + free-quota logic + append-only usage ledger
- Adapter for the official @modelcontextprotocol/sdk Server (stdio/SSE transports)
- Two verifiers: HMAC dev verifier for testing, facilitator verifier for production
- 8 automated tests, all passing + commented example server
- README with a 5-minute quick start

Non-custodial by design: never holds keys or funds. It verifies payment, then runs your tool.

**Buy** — $69 one-time. Yours forever. No subscriptions, no lock-in.
[Get the MCP Monetization Kit](https://payloadtools.gumroad.com/l/mcp-monetization-kit)
Also available: [x402 + MCP Monetization Kit bundle ($119)](https://payloadtools.gumroad.com/l/x402-mcp-bundle)

**License** — Single-seat commercial license, perpetual. Full text ships inside the package (LICENSE.txt). Not open source.

**Support** — kylers.partners@gmail.com

Sold by Payload. Small software that earns its keep.

---

**Payload** — small, sharp tools for developers.
Developer portal: https://payloadhq.github.io/ ·
All products: https://payloadtools.gumroad.com/ ·
Contact: kylers.partners@gmail.com
