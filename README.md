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

### 2. TenderWatch
- **Description**: Government procurement search across EU TED and US SAM.gov, with opportunity fit-scoring for AI agents.
- **Endpoint**: `https://x402-tenderwatch.onrender.com/search`
- **Discovery**: `https://x402-tenderwatch.onrender.com/.well-known/x402`
- **Price**: **0.02 USDC** per call (x402 protocol)
- **Capabilities**: `procurement_search`, `fit_scoring`, `x402_payment`
- **Status**: ✅ **Active**
- **Author**: Jebadiah
- **Docs**: [llms.txt](https://x402-tenderwatch.onrender.com/llms.txt) · [OpenAPI](https://x402-tenderwatch.onrender.com/openapi.json) · [Terms](https://x402-tenderwatch.onrender.com/terms)

#### 📊 How it works
1. Send a GET request to `/search` with your query parameters.
2. The x402 payment challenge is returned as HTTP 402; pay USDC on Base and retry with the payment proof.
3. Receive ranked procurement opportunities with fit scores.

#### 💰 Payment
- **Currency**: USDC (Base Chain)
- **Wallet**: `0x11297bb942475a0df8558987c5b055377952738c`
- **Protocol**: x402 (HTTP 402 Payment Required)

---

### 3. EDGAR Lens
- **Description**: SEC EDGAR full-text search plus concise filing briefs for AI agents.
- **Endpoint**: `https://x402-edgar-lens.onrender.com/search`
- **Discovery**: `https://x402-edgar-lens.onrender.com/.well-known/x402`
- **Price**: **0.02 USDC** per call (x402 protocol)
- **Capabilities**: `sec_search`, `filing_briefs`, `x402_payment`
- **Status**: ✅ **Active**
- **Author**: Jebadiah
- **Docs**: [llms.txt](https://x402-edgar-lens.onrender.com/llms.txt) · [OpenAPI](https://x402-edgar-lens.onrender.com/openapi.json) · [Terms](https://x402-edgar-lens.onrender.com/terms)

#### 💰 Payment
- **Currency**: USDC (Base Chain)
- **Wallet**: `0x11297bb942475a0df8558987c5b055377952738c`
- **Protocol**: x402 (HTTP 402 Payment Required)

---

### 4. TrialScope
- **Description**: ClinicalTrials.gov search with full study dossiers for AI agents.
- **Endpoint**: `https://x402-trialscope.onrender.com/search`
- **Discovery**: `https://x402-trialscope.onrender.com/.well-known/x402`
- **Price**: **0.01 USDC** per call (x402 protocol)
- **Capabilities**: `clinical_trials_search`, `study_dossiers`, `x402_payment`
- **Status**: ✅ **Active**
- **Author**: Jebadiah
- **Docs**: [llms.txt](https://x402-trialscope.onrender.com/llms.txt) · [OpenAPI](https://x402-trialscope.onrender.com/openapi.json) · [Terms](https://x402-trialscope.onrender.com/terms)

#### 💰 Payment
- **Currency**: USDC (Base Chain)
- **Wallet**: `0x11297bb942475a0df8558987c5b055377952738c`
- **Protocol**: x402 (HTTP 402 Payment Required)

---

### 5. DocExtract
- **Description**: PDF to structured JSON extraction for AI agents.
- **Endpoint**: `https://x402-docextract.onrender.com/extract`
- **Discovery**: `https://x402-docextract.onrender.com/.well-known/x402`
- **Price**: **Up to 0.10 USDC** per document (x402 protocol)
- **Capabilities**: `pdf_extraction`, `structured_json`, `x402_payment`
- **Status**: ✅ **Active**
- **Author**: Jebadiah
- **Docs**: [llms.txt](https://x402-docextract.onrender.com/llms.txt) · [OpenAPI](https://x402-docextract.onrender.com/openapi.json) · [Terms](https://x402-docextract.onrender.com/terms)

#### 💰 Payment
- **Currency**: USDC (Base Chain)
- **Wallet**: `0x11297bb942475a0df8558987c5b055377952738c`
- **Protocol**: x402 (HTTP 402 Payment Required)

---

### 6. PatentScope
- **Description**: USPTO patent search with prior-art ranking for AI agents.
- **Endpoint**: `https://x402-patentscope.onrender.com/search`
- **Discovery**: `https://x402-patentscope.onrender.com/.well-known/x402`
- **Price**: **0.03 USDC** per call (x402 protocol)
- **Capabilities**: `patent_search`, `prior_art_ranking`, `x402_payment`
- **Status**: ✅ **Active**
- **Author**: Jebadiah
- **Docs**: [llms.txt](https://x402-patentscope.onrender.com/llms.txt) · [OpenAPI](https://x402-patentscope.onrender.com/openapi.json) · [Terms](https://x402-patentscope.onrender.com/terms)

#### 💰 Payment
- **Currency**: USDC (Base Chain)
- **Wallet**: `0x11297bb942475a0df8558987c5b055377952738c`
- **Protocol**: x402 (HTTP 402 Payment Required)

---

### 7. Alexandria
- **Description**: Automotive parts intelligence for AI agents — parts search and demand signals.
- **Endpoint**: `https://x402-alexandria.onrender.com/parts/search`
- **Discovery**: `https://x402-alexandria.onrender.com/.well-known/x402`
- **Price**: **0.03 USDC** per call (x402 protocol)
- **Capabilities**: `parts_search`, `parts_intelligence`, `x402_payment`
- **Status**: ✅ **Active**
- **Author**: Jebadiah
- **Docs**: [llms.txt](https://x402-alexandria.onrender.com/llms.txt) · [OpenAPI](https://x402-alexandria.onrender.com/openapi.json) · [Terms](https://x402-alexandria.onrender.com/terms)

#### 💰 Payment
- **Currency**: USDC (Base Chain)
- **Wallet**: `0x11297bb942475a0df8558987c5b055377952738c`
- **Protocol**: x402 (HTTP 402 Payment Required)

---

### 8. InvoiceIQ
- **Description**: AP invoice extraction for AI agents — vendor, line items, totals validation, and duplicate detection.
- **Endpoint**: `https://x402-invoiceiq.onrender.com/extract`
- **Discovery**: `https://x402-invoiceiq.onrender.com/.well-known/x402`
- **Price**: **0.05 USDC** per document (x402 protocol)
- **Capabilities**: `invoice_extraction`, `totals_validation`, `duplicate_detection`, `x402_payment`
- **Status**: ✅ **Active**
- **Author**: Jebadiah
- **Docs**: [llms.txt](https://x402-invoiceiq.onrender.com/llms.txt) · [OpenAPI](https://x402-invoiceiq.onrender.com/openapi.json) · [Terms](https://x402-invoiceiq.onrender.com/terms)

#### 💰 Payment
- **Currency**: USDC (Base Chain)
- **Wallet**: `0x11297bb942475a0df8558987c5b055377952738c`
- **Protocol**: x402 (HTTP 402 Payment Required)

---

### 9. TaxRate US
- **Description**: US sales-tax rate lookup by ZIP for AI agents.
- **Endpoint**: `https://x402-taxrate.onrender.com/rate`
- **Discovery**: `https://x402-taxrate.onrender.com/.well-known/x402`
- **Price**: **0.03 USDC** per lookup (x402 protocol)
- **Capabilities**: `sales_tax_lookup`, `x402_payment`
- **Status**: ✅ **Active**
- **Author**: Jebadiah
- **Docs**: [llms.txt](https://x402-taxrate.onrender.com/llms.txt) · [OpenAPI](https://x402-taxrate.onrender.com/openapi.json) · [Terms](https://x402-taxrate.onrender.com/terms)

#### 💰 Payment
- **Currency**: USDC (Base Chain)
- **Wallet**: `0x11297bb942475a0df8558987c5b055377952738c`
- **Protocol**: x402 (HTTP 402 Payment Required)

---

### 10. EntityVerify
- **Description**: US business verification (KYB-lite) for AI agents.
- **Endpoint**: `https://x402-entityverify.onrender.com/entity`
- **Discovery**: `https://x402-entityverify.onrender.com/.well-known/x402`
- **Price**: **0.07 USDC** per check (x402 protocol)
- **Capabilities**: `business_verification`, `kyb`, `x402_payment`
- **Status**: ✅ **Active**
- **Author**: Jebadiah
- **Docs**: [llms.txt](https://x402-entityverify.onrender.com/llms.txt) · [OpenAPI](https://x402-entityverify.onrender.com/openapi.json) · [Terms](https://x402-entityverify.onrender.com/terms)

#### 💰 Payment
- **Currency**: USDC (Base Chain)
- **Wallet**: `0x11297bb942475a0df8558987c5b055377952738c`
- **Protocol**: x402 (HTTP 402 Payment Required)

---

## 🚀 Add Your Service
Want to add your x402 agent service here?
1. Ensure your service is public and supports x402.
2. Submit a Pull Request with your service details in the format above.

---

*Last updated: 2026-06-02*
*Generated by XiaoPingGuo Agent 🍎*
