# MCP Monetization Kit

*Charge per tool call on your MCP server. A commercial product by Payload.*

> **This repo is the product page.** The paid package ships to you when you buy; it is not open source. Buy links are below.

30,000+ MCP servers are indexed across directories and marketplaces — and none of those marketplaces pay their creators. If you run a useful MCP server, your only options are donations or building billing infrastructure from scratch.

This kit is the third option: wrap each tool with a price. Callers without payment get machine-readable payment requirements; callers who pay get results. Free tools stay free, and you can grant free quotas (e.g. 3 free calls, then $0.025 each).

When you're ready to run metered MCP tools in production, the path leads to **Veyline by Payload** — the production layer for x402 + MCP.

## Who it's for

Developers who run a useful MCP server and want per-tool-call revenue without building billing infrastructure from scratch or relying on donations.

## What you receive

The paid package ($69, one-time) includes:

- **Paid tool registry** — registerTool / callTool / listTools with payment enforcement
- **Per-tool pricing + free-quota logic** — e.g. 3 free calls, then $0.025 each; free tools stay free
- **Append-only usage ledger** — every paid call, recorded
- **Adapter for the official @modelcontextprotocol/sdk Server** (stdio/SSE transports)
- **Two verifiers** — HMAC dev verifier for testing, facilitator verifier for production
- **8 automated tests**, all passing, plus a commented example server
- **README with a 5-minute quick start**

Non-custodial by design: the kit never holds keys or funds. It verifies payment, then runs your tool.

## What it does NOT include

- It is not the full Veyline platform. This kit meters your MCP tools; Veyline by Payload is the production layer for x402 + MCP.
- It does not collect funds on your behalf or hold private keys. Payment travels on the x402 flow; the kit verifies it, then runs your tool.
- It does not audit or harden your server. For a 48-rule security scanner and hardened server templates, see the MCP Launch Readiness Audit by Payload.

Try the mechanic first: the [free demo repo](https://github.com/Payloadhq/mcp-monetization-demo) shows per-tool metering with a free quota in under a minute — no purchase needed.

## Buy

**$69 one-time. Yours forever. No subscriptions, no lock-in.**

[Get the MCP Monetization Kit](https://payloadtools.gumroad.com/l/mcp-monetization-kit)

Also on [Whop](https://whop.com/payload-f126/products/mcp-monetization-kit-charge-per-tool-call-on-your-mcp-server/)

Also available: [x402 + MCP Monetization Kit bundle ($119)](https://payloadtools.gumroad.com/l/x402-mcp-bundle)

**What happens after you get paid?** [RevRule by Payload](https://payloadtools.gumroad.com/l/revrule-by-payload) programs who earns what when your MCP server makes money.

**License** — Single-seat commercial license, perpetual. Full text ships inside the package (LICENSE.txt). Not open source.

## Support and updates

- Support: kylers.partners@gmail.com
- Sold and supported by Payload. Small software that earns its keep.

---

**Payload** — small, sharp tools for developers.
Developer portal: https://payloadhq.github.io/ ·
All products: https://payloadtools.gumroad.com/ ·
Contact: kylers.partners@gmail.com
