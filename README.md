# Pangolinfo Plugins for Claude Code

Official Claude Code plugin marketplace from [Pangolinfo](https://www.pangolinfo.com/) — live Amazon data for AI agents.

## Install

In Claude Code:

```
/plugin marketplace add Pangolin-spg/pangolinfo-plugins
/plugin install pangolinfo-amazon-data@pangolinfo-plugins
```

## Setup

The plugin talks to Pangolinfo's hosted MCP server, which needs a Pangolinfo API key:

1. Get a free key at [pangolinfo.com](https://www.pangolinfo.com/amazon-data-mcp/) — the free tier includes **60 credits/month, no credit card required**.
2. Export it in your shell before starting Claude Code:

```bash
export PANGOLINFO_API_KEY="your-key"
```

## Plugins

### pangolinfo-amazon-data

Live Amazon data inside Claude Code, two ways:

- **MCP server** (`pangolinfo-amazon-data`, Streamable HTTP at `https://mcp.pangolinfo.com/mcp`): product details across 51 fields, paginated customer reviews, keyword search results, category listings, seller storefronts, Best Sellers and New Releases rankings — as native tools your agent can call.
- **Skill** (`pangolinfo-amazon-scraper`): a bundled skill for direct Pangolinfo API pipelines (products, keywords, categories, best sellers) with a Python helper and API references.

## Links

- Product: [Amazon Data MCP](https://www.pangolinfo.com/amazon-data-mcp/) · [Scraper API](https://www.pangolinfo.com/amazon-scraper-api/) · [Amazon Scraper Skill](https://www.pangolinfo.com/amazon-scraper-skill/)
- Docs: [docs.pangolinfo.com](https://docs.pangolinfo.com/)
- More code: [amazon-data-mcp](https://github.com/Pangolin-spg/amazon-data-mcp) (MCP server & npm bridge) · [openclaw-skills](https://github.com/Pangolin-spg/openclaw-skills) · [amazon-scraper](https://github.com/Pangolin-spg/amazon-scraper) (Python/Node examples)

## License

MIT
