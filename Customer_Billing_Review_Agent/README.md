# Customer Billing Review Agent (SAP Joule Studio)

Enterprise-grade autonomous AI agent engineered for **SAP Joule Studio** to analyze S/4HANA customer billing documents, sales contracts, and subsequent billing records via Model Context Protocol (MCP).

## Key Features & Safety Guardrails
- **SOX Compliance & SoD:** Operates strictly under a **Read-Only** policy.
- **Prompt Injection Defense:** Embedded detection hooks prevent prompt manipulation.
- **OData MCP Interoperability:** Clean integration with `CE_BILLINGDOCUMENT_0001`, `CE_SALESCONTRACT_0001`, and `API_SUBSQNT_BILLG_DOC_SBI_SRV`.
