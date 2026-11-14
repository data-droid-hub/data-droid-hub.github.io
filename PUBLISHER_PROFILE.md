# Apify Publisher Profile Settings (`data-droid-hub`)

Paste these fields into **Apify Console -> Account Settings -> Profile** (Apify's public REST API does not expose a `PUT /v2/users/me` profile-edit endpoint):

- **Name:** `Data Droid` (or `data-droid-hub`)
- **GitHub Username:** `data-droid-hub`
- **Website URL:** `https://data-droid-hub.github.io/`
- **Bio (160 chars):**
  `Zero-proxy Rust Apify Actors & MCP-ready web intelligence pipelines. Sub-second HTTP/2 RPC extraction with incremental daily diffs and transparent PPE pricing.`

---

## Profile README (Markdown)

```markdown
# data-droid-hub | Zero-Proxy Rust Data Extraction & MCP Actors

**data-droid-hub** builds compiled Rust Apify Actors designed for sub-second speed, zero proxy overhead, and drop-in compatibility with AI agents (Apify MCP, Claude, Cursor, ChatGPT), Clay, and n8n.

## Published Actors

- **[Google Ads Transparency Scraper](https://apify.com/data-droid-hub/google-ads-transparency-actor)** (`data-droid-hub/google-ads-transparency-actor`) - Zero-proxy HTTP/2 Rust RPC scraper for Google Ads Transparency Center. Extracts text, image, and YouTube video creatives, ad copy, and per-country reach in under 1 second with built-in incremental daily diffs (`onlyNewSinceLastRun`) and `domain_summary` qualification.

## Engineering Focus

- **Zero-Browser HTTP/2 RPC:** Compiled Rust binaries using pooled `rustls` connections instead of heavyweight Chromium instances (`256 MB` RAM vs `2-4 GB` browser scrapers).
- **Incremental State Watermarks:** Named Key-Value Store frontier tracking stops scans at previously seen records so scheduled monitors emit and bill only new data.
- **MCP-Ready Schemas:** Flat array inputs, zero conflicting schema rules, slim typed JSON outputs, and `$0` `dryRun` pre-flight cost estimators.
- **Pay-Per-Event Transparency:** Predictable per-record pricing with zero hidden residential proxy fees.

## Links

- **Hub & Technical Specs:** [data-droid-hub.github.io](https://data-droid-hub.github.io/)
- **LLM Index:** [llms.txt](https://data-droid-hub.github.io/llms.txt)
- **GitHub:** [@data-droid-hub](https://github.com/data-droid-hub)
```
