# Comparison

Coverage by project, as of 2026-09. `✓` means the project implements the capability, `◐` means partial or bundled inside a broader feature, and `—` means not covered. A dash is not a criticism: a single-purpose module that does one thing well is often the better choice.

**Status** reflects only what each project declares about itself. `Released` means tagged, versioned releases. `In progress` and `Experimental` are the maintainers' own words. `No stated status` means the project makes no maturity claim — it is not a criticism, and recent commit activity is a better signal than anything in this table.

Two rows cover many columns: angeo and Mirasvit. Both are suites of separate modules rather than single products, so breadth here is a packaging fact, not a quality judgement. A single-purpose module that does one column well is often the better choice.

Each project appears once in the [main list](README.md), in the section closest to its primary purpose. This table is where the cross-section coverage lives.

## Open source

| Project                         | llms.txt | Crawler policy | Schema | Feed | Checkout | MCP | Audit | License | Status       |
|---------------------------------|----------|----------------|--------|------|----------|-----|-------|---------|--------------|
| adwise/magento2-mcp             | —        | —              | —      | —    | —        | ✓   | —     | OSS     | No stated status |
| aligent/magento2-llms-txt       | ✓        | —              | —      | —    | —        | —   | —     | OSS     | No stated status |
| mage-os-lab/llms.txt            | ✓        | —              | —      | —    | —        | —   | —     | OSS     | No stated status |
| mage-os-lab/module-seo          | ✓        | ✓              | ✓      | ◐    | ◐        | —   | —     | OSS     | No stated status |
| mage2kishan/module-blog         | ✓        | —              | —      | —    | —        | —   | —     | OSS     | No stated status |
| mage2kishan/module-llms-txt     | ✓        | —              | —      | —    | —        | —   | —     | OSS     | No stated status |
| magenable (2 projects)          | —        | —              | —      | ✓    | —        | ✓   | —     | OSS     | No stated status |
| magendooro/magemcp              | —        | —              | —      | —    | —        | ✓   | —     | OSS     | No stated status |
| mageplaza/magento-2-seo         | —        | —              | ✓      | —    | —        | —   | ◐     | OSS     | Released     |
| outeredge/magento-structured-data-module | —  | —              | ✓      | —    | —        | —   | —     | MIT     | Released     |
| iamrobindhiman/magento2-module-llms-txt | ✓        | —              | —      | —    | —        | —   | —     | MIT     | No stated status |
| scandiweb/scandiweb-magento2-mcp| —        | —              | —      | —    | —        | ✓   | —     | OSS     | No stated status |
| studioraz/magento2-llms-txt     | ✓        | —              | —      | —    | —        | —   | —     | OSS     | No stated status |
| thomastx05/magento-mcp          | —        | —              | —      | —    | —        | ✓   | —     | OSS     | No stated status |
| xpaysh/agentic-commerce-for-magento| ✓        | ✓              | ✓      | —    | ✓        | —   | —     | OSS     | v0.1         |
| yuriyakishin/magento2-mcp-server| —        | —              | —      | —    | —        | ✓   | —     | OSS     | No stated status |
| angeo (11 modules)              | ✓        | ✓              | ✓      | ✓    | ✓        | ✓   | ✓     | MIT     | Released     |

## Commercial

| Project                      | llms.txt | Crawler policy | Schema | Feed | Checkout | MCP | Audit | Notes                                  |
|------------------------------|----------|----------------|--------|------|----------|-----|-------|----------------------------------------|
| Adobe Commerce Catalog Agent | —        | —              | ✓      | —    | —        | —   | —     | Part of Adobe LLM Optimizer            |
| Adobe Commerce Storefront MCP | —       | —              | —      | —    | ✓        | ✓   | —     | First-party storefront server          |
| Amasty SEO Toolkit           | ✓        | —              | ✓      | —    | —        | —   | ✓     | llms.txt is Pro and Premium tiers only |
| CodeDecorator LLMs TXT       | ✓        | —              | —      | —    | —        | —   | —     | Key-value or Markdown output              |
| Grazitti LLMs TXT            | ✓        | —              | —      | —    | —        | —   | —     | Per-store-view, SKUs/prices optional   |
| MageDelight                  | ✓        | —              | ✓      | —    | —        | —   | —     | —                                      |
| Magefan LLMs TXT Generator   | ✓        | —              | —      | —    | —        | —   | —     | Single purpose                         |
| Mageworx SEO Suite Ultimate  | ✓        | ✓              | ✓      | —    | —        | —   | —     | Bot analytics with verification        |
| Meetanshi Agentic Commerce   | ✓        | ✓              | —      | ✓    | ✓        | ✓   | ✓     | Widest single-module coverage here     |
| Meetanshi Google UCP         | —        | —              | —      | ✓    | ✓        | —   | —     | Google Pay, staged regional rollout    |
| Meetanshi LLMs TXT Generator | ✓        | —              | —      | —    | —        | —   | —     | Single purpose                         |
| Mirasvit Agentic Commerce    | ✓        | ✓              | —      | ✓    | —        | ✓   | —     | Cart building; checkout on storefront  |
| Mirasvit AI Agent Connector  | —        | —              | ✓      | ✓    | ✓        | ✓   | ✓     | Widest commercial coverage             |
| Plumrocket LLMs TXT          | ✓        | —              | —      | —    | —        | —   | —     | Store-view scoped, Hyvä support        |
| Webkul LLMs TXT Generator    | ✓        | ✓              | —      | —    | —        | —   | —     | Crawler analytics dashboard            |

Projects still in early development are not in these tables; see [WATCHLIST.md](WATCHLIST.md).
