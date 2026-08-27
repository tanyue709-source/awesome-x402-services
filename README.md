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

### 2. PDF Extract API
- **Description**: Upload a PDF, get back structured JSON (invoices, receipts, any document), matching a caller-supplied schema or a sensible default.
- **Endpoint**: `https://pdf-extract-api.pdfextractapi.workers.dev/extract`
- **Discovery**: `https://pdf-extract-api.pdfextractapi.workers.dev/extract` (x402 Bazaar discovery extension on the 402 response)
- **Price**: **0.02 USDC** per call (x402 protocol)
- **Capabilities**: `pdf_extraction`, `document_parsing`, `x402_payment`
- **Status**: ✅ **Active & Verified**
- **Author**: GABEMAKESSTUFF

#### 📊 How it works
1. Send a multipart/form-data POST with a `file` field (the PDF) and an optional `schema` field.
2. First request returns HTTP 402 with x402 payment requirements.
3. Retry with a signed x402 payment header to receive the structured JSON result.

#### 💰 Payment
- **Currency**: USDC (Base Mainnet)
- **Wallet**: `0xA0AC44BECC6302298f01ed255B175ca1060C189E`
- **Protocol**: x402 (HTTP 402 Payment Required)

---

### 3. Content Risk Scanner
- **Description**: Detects prompt-injection and malicious-instruction attempts in untrusted text (scraped pages, documents, tool output) before an AI agent processes it.
- **Endpoint**: `https://content-risk-scanner.pdfextractapi.workers.dev/scan`
- **Discovery**: `https://content-risk-scanner.pdfextractapi.workers.dev/scan` (x402 Bazaar discovery extension on the 402 response)
- **Price**: **0.01 USDC** per call (x402 protocol)
- **Capabilities**: `prompt_injection_detection`, `content_security`, `x402_payment`
- **Status**: ✅ **Active & Verified**
- **Author**: GABEMAKESSTUFF

#### 📊 How it works
1. Send a JSON POST with a `text` field containing the untrusted content to check.
2. First request returns HTTP 402 with x402 payment requirements.
3. Retry with a signed x402 payment header to receive a risk score, verdict, and flagged spans.

#### 💰 Payment
- **Currency**: USDC (Base Mainnet)
- **Wallet**: `0xA0AC44BECC6302298f01ed255B175ca1060C189E`
- **Protocol**: x402 (HTTP 402 Payment Required)

---

### 4. PII Redactor
- **Description**: Detects and redacts personally identifiable information — names, emails, phone numbers, card numbers, addresses — from text.
- **Endpoint**: `https://pii-redactor.pdfextractapi.workers.dev/redact`
- **Discovery**: `https://pii-redactor.pdfextractapi.workers.dev/redact` (x402 Bazaar discovery extension on the 402 response)
- **Price**: **0.02 USDC** per call (x402 protocol)
- **Capabilities**: `pii_detection`, `data_redaction`, `x402_payment`
- **Status**: ✅ **Active & Verified**
- **Author**: GABEMAKESSTUFF

#### 📊 How it works
1. Send a JSON POST with a `text` field.
2. First request returns HTTP 402 with x402 payment requirements.
3. Retry with a signed x402 payment header to receive the redacted text and a list of detected entities.

#### 💰 Payment
- **Currency**: USDC (Base Mainnet)
- **Wallet**: `0xA0AC44BECC6302298f01ed255B175ca1060C189E`
- **Protocol**: x402 (HTTP 402 Payment Required)

---

### 5. Receipt Normalizer
- **Description**: Converts a receipt, invoice, or order confirmation PDF into a canonical structured purchase record (merchant, line items, totals, order ID) for agent bookkeeping.
- **Endpoint**: `https://receipt-normalizer.pdfextractapi.workers.dev/normalize`
- **Discovery**: `https://receipt-normalizer.pdfextractapi.workers.dev/normalize` (x402 Bazaar discovery extension on the 402 response)
- **Price**: **0.03 USDC** per call (x402 protocol)
- **Capabilities**: `receipt_parsing`, `purchase_normalization`, `x402_payment`
- **Status**: ✅ **Active & Verified**
- **Author**: GABEMAKESSTUFF

#### 📊 How it works
1. Send a multipart/form-data POST with a `file` field (the receipt/invoice PDF).
2. First request returns HTTP 402 with x402 payment requirements.
3. Retry with a signed x402 payment header to receive the normalized purchase record.

#### 💰 Payment
- **Currency**: USDC (Base Mainnet)
- **Wallet**: `0xA0AC44BECC6302298f01ed255B175ca1060C189E`
- **Protocol**: x402 (HTTP 402 Payment Required)

---

### 6. Claim Verifier
- **Description**: Fact-checks a single factual claim against live web search results, returning a verdict (supported/refuted/unverifiable) with cited sources.
- **Endpoint**: `https://claim-verifier.pdfextractapi.workers.dev/verify`
- **Discovery**: `https://claim-verifier.pdfextractapi.workers.dev/verify` (x402 Bazaar discovery extension on the 402 response)
- **Price**: **0.04 USDC** per call (x402 protocol)
- **Capabilities**: `fact_checking`, `claim_verification`, `x402_payment`
- **Status**: ✅ **Active & Verified**
- **Author**: GABEMAKESSTUFF

#### 📊 How it works
1. Send a JSON POST with a `claim` field (max 500 characters).
2. First request returns HTTP 402 with x402 payment requirements.
3. Retry with a signed x402 payment header to receive the verdict, confidence, and sources used.

#### 💰 Payment
- **Currency**: USDC (Base Mainnet)
- **Wallet**: `0xA0AC44BECC6302298f01ed255B175ca1060C189E`
- **Protocol**: x402 (HTTP 402 Payment Required)

---

## 🚀 Add Your Service
Want to add your x402 agent service here?
1. Ensure your service is public and supports x402.
2. Submit a Pull Request with your service details in the format above.

---

*Last updated: 2026-06-02*
*Generated by XiaoPingGuo Agent 🍎*
