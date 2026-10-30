## Tender Document Ingestion Pipeline: Hong Kong engineering firm, 2026

**Problem:** A tender-proposal multi-agent needed reliable access to 2,000+ engineering tender documents, such as contracts, specifications and drawings, which arrived in mixed formats and sizes.

**My role:** I designed and built the ingestion pipeline. I also benchmarked retrieval quality on Azure AI Foundry against Google Cloud's Agent Platform (Vertex AI Search) to choose the production platform.

**Scope**
- Normalises mixed Word and PDF documents into a clean corpus ready for retrieval.
- Fits documents within size and page limits without losing content.
- Automatically checks every document for text loss or pagination errors.

**Outcome:** the high-fidelity ingestion layer behind the enterprise tender-proposal multi-agent, which directly supports the firm's bidding and new-contract revenue.

**Stack:** Python · Docker · Azure AI Foundry · Google Cloud Agent Platform (Vertex AI Search)

_Source code is proprietary; this summarises my role and the outcome._
