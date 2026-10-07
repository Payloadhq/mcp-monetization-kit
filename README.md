> **Payload** — Developer infrastructure for x402, agent payments, and programmable revenue.
> PAYLOAD → VEYLINE (flagship) → CALLX402 (action layer) → REVRULE (separate) → developer products → free utilities.
> This repo: **MCP Monetization Engine by Payload — per-tool-call metering for MCP servers.**

<p align="center"><img src="docs/logo.png" alt="mcp-monetization-kit logo" width="200"></p>
# MCP Monetization Engine

*Charge per tool call on your MCP server. A commercial product by Payload.*

> **This repo is the product page.** The paid package ships to you when you buy; it is not open source. Buy links are below.

Thousands of MCP servers are indexed across directories and marketplaces — and none of those marketplaces pay their creators. If you run a useful MCP server, your only options are donations or building billing infrastructure from scratch.

This kit is the third option: wrap each tool with a price. Callers without payment get machine-readable payment requirements; callers who pay get results. Free tools stay free, and you can grant free quotas (e.g. 3 free calls, then $0.025 each).

**Why it exists:** MCP creators deserve revenue from their tools without becoming payments companies. The Engine is the neutral kit: paid tool registry, per-tool pricing with free quotas, append-only usage ledger, adapter for the official MCP SDK, and 15 passing tests.

**Try the mechanic free first:** the [free demo repo](https://github.com/Payloadhq/mcp-monetization-demo) shows per-tool metering with a free quota in under a minute, no purchase needed.

**Buy: [$69 one-time on Gumroad](https://payloadtools.gumroad.com/l/mcp-monetization-kit)** (also on [Whop](https://whop.com/payload-f126/products/mcp-monetization-kit-charge-per-tool-call-on-your-mcp-server/)). Yours forever, no subscriptions, no lock-in.

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
- **15 automated tests** (9 unit + 6 integration), all passing, plus a commented example server
- **README with a 5-minute quick start**

Non-custodial by design: the kit never holds keys or funds. It verifies payment, then runs your tool.

## What it does NOT include

- It is not the full Veyline platform. This kit meters your MCP tools; Veyline by Payload is the production layer for x402 + MCP.
- It does not collect funds on your behalf or hold private keys. Payment travels on the x402 flow; the kit verifies it, then runs your tool.
- It does not audit or harden your server. For a 48-rule security scanner and hardened server templates, see the MCP Launch Readiness Audit by Payload.

## Buy

**$69 one-time. Yours forever. No subscriptions, no lock-in.**

[Get the MCP Monetization Kit](https://payloadtools.gumroad.com/l/mcp-monetization-kit)

Also on [Whop](https://whop.com/payload-f126/products/mcp-monetization-kit-charge-per-tool-call-on-your-mcp-server/)

Also available: [x402 + MCP Monetization Engine bundle ($119)](https://payloadtools.gumroad.com/l/x402-mcp-bundle)

**What happens after you get paid?** [RevRule by Payload](https://payloadtools.gumroad.com/l/revrule-by-payload) programs who earns what when your MCP server makes money.

**License** — Single-seat commercial license, perpetual. Full text ships inside the package (LICENSE.txt). Not open source.

## Support and updates

- Support: kylers.partners@gmail.com
- Sold and supported by Payload. Small software that earns its keep.

---

**Payload** — Developer infrastructure for x402, agent payments, and programmable revenue..
Developer portal: https://payloadhq.github.io/ ·
All products: https://payloadtools.gumroad.com/ ·
Contact: kylers.partners@gmail.com

---

**More from Payload** · [payloadhq.github.io](https://payloadhq.github.io/) · [all Payload repos](https://github.com/Payloadhq)

Related: [mcp-monetization-demo](https://github.com/Payloadhq/mcp-monetization-demo) · [payload-sample-mcp-server](https://github.com/Payloadhq/payload-sample-mcp-server) · [mcp-readiness-check](https://github.com/Payloadhq/mcp-readiness-check)
