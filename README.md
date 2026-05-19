# TracePII Shield MCP

Redact PII from LLM traces and tool payloads before they leave review.

Paid remote MCP for LLM trace PII scanning, payload redaction, sensitive field classification, privacy receipts, and trace audit exports.

## Public Endpoints

- Website: https://tracepiishield.clauxel.com/?utm_source=github&utm_medium=directory&utm_campaign=sbl202605
- MCP endpoint: https://tracepiishield.clauxel.com/mcp
- Server card: https://tracepiishield.clauxel.com/server-card.json
- Registry name: `com.clauxel.tracepiishield/tracepiishield-mcp`

## Access

This is a paid hosted remote MCP. Production calls require a bearer token issued from the product website.

```http
Authorization: Bearer <token>
```

Unauthenticated browser visits to `/mcp` return a clear JSON error instead of internal details.

## Tools

- `scan_trace_pii`
- `redact_tool_payload`
- `classify_sensitive_field`
- `issue_pii_receipt`
- `export_trace_audit`

## Quick Start

1. Open the website and choose a plan.
2. Create or request an API token.
3. Add the endpoint to an MCP client that supports Streamable HTTP remote servers.
4. Send JSON-RPC requests with the bearer token.

## Useful Links

- Product page: https://tracepiishield.clauxel.com/?utm_source=github&utm_medium=directory&utm_campaign=sbl202605
- Pricing: https://tracepiishield.clauxel.com/?utm_source=github&utm_medium=directory&utm_campaign=sbl202605#pricing
- Server card: https://tracepiishield.clauxel.com/server-card.json
- MCP endpoint: https://tracepiishield.clauxel.com/mcp

## Status

This repository is a public documentation and directory-submission reference for the hosted service. It does not contain the private production source code.
