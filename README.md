# 🍎 Awesome x402 AI Agent Services

> A curated list of production-ready AI Agent services that accept x402 payments.

## 🌟 Featured Services

### 1. XiaoPingGuo (小苹果) Sentiment Agent
- **Description**: Real-time crypto market sentiment analysis API. 24/7 automated operation.
- **Endpoint**: `https://agent-money-maker.onrender.com/api/v1/sentiment`
- **Discovery**: `https://agent-money-maker.onrender.com/.well-known/agent-discovery.json`
- **Price**: **0.1 USDC** per call (x402 protocol)
- **Capabilities**: `sentiment_analysis`, `crypto_market`, `x402_payment`
- **Status**: ✅ **Active & Verified**
- **Author**: tanyue709-source
- **Repository**: [GitHub](https://github.com/tanyue709-source/agent-money-maker)

#### 📊 How it works
1. Send a POST request with your text to analyze.
2. Include a valid x402 payment proof in the `Authorization` header.
3. Receive instant sentiment analysis (Bullish/Bearish/Neutral) with score.

#### 💰 Payment
- **Currency**: USDC (Base Chain)
- **Wallet**: `0x794D627B076C1167abF130fBbC91e60873af94F4`
- **Protocol**: x402 (HTTP 402 Payment Required)

---

### 2. The Stall — 189 Pay-Per-Call AI Data Tools
- **Description**: 189 AI-callable data tools via MCP and x402 on Base. US/global stocks, crypto, DeFi, options, macro, sentiment, congressional trades, company intelligence, and more. No API keys required.
- **Endpoint**: `https://the-stall.intuitek.ai/mcp` (MCP, free discovery) · `https://the-stall.intuitek.ai/cap/{tool}` (x402-gated)
- **Discovery**: [GitHub](https://github.com/thebrierfox/the-stall) · [Glama](https://glama.ai/mcp/servers/@thebrierfox/the-stall)
- **Price**: **~$0.001 USDC** per call (varies by capability)
- **Capabilities**: `stocks`, `crypto`, `defi`, `options`, `macro`, `sentiment`, `congressional_trades`, `company_intel`, `x402_payment`, `mcp`
- **Status**: ✅ **Active & Verified** (189 tools, v4.43.0)
- **Author**: thebrierfox (IntuiTek¹)
- **Repository**: [GitHub](https://github.com/thebrierfox/the-stall)

#### 📊 How it works
1. Connect via MCP at `https://the-stall.intuitek.ai/mcp` for free tool discovery.
2. Call any `/cap/{tool}` endpoint — server responds with x402 payment requirements.
3. Pay ~$0.001 USDC per call via Base x402; receive structured data instantly.

#### 💰 Payment
- **Currency**: USDC (Base Chain, EIP-3009)
- **Protocol**: x402 v2 (HTTP 402 Payment Required, `PAYMENT-REQUIRED` header)

---

## 🚀 Add Your Service
Want to add your x402 agent service here?
1. Ensure your service is public and supports x402.
2. Submit a Pull Request with your service details in the format above.

---

*Last updated: 2026-06-09*