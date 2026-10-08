<div align="center">

# Illuma Law

**Open-source Laravel packages powering [illuma.law](https://illuma.law).**

Operational health checks, AI & LLM tooling, and search infrastructure —
extracted from a production legal-tech platform.

</div>

---

## Health checks

Uniform, configurable health probes for Laravel — the same shape, every service:

| Package | Checks |
|---|---|
| [`healthcheck-redis`](https://github.com/illuma-law/healthcheck-redis) | Redis extension & connectivity |
| [`healthcheck-pgvector`](https://github.com/illuma-law/healthcheck-pgvector) | pgvector extension & connectivity |
| [`healthcheck-typesense`](https://github.com/illuma-law/healthcheck-typesense) | Typesense reachability |
| [`healthcheck-mail`](https://github.com/illuma-law/healthcheck-mail) | Mail transport connectivity |
| [`healthcheck-migration`](https://github.com/illuma-law/healthcheck-migration) | Pending database migrations |
| [`healthcheck-octane`](https://github.com/illuma-law/healthcheck-octane) | Octane server status |
| [`healthcheck-operations`](https://github.com/illuma-law/healthcheck-operations) | Pending one-time operations |
| [`healthcheck-storage`](https://github.com/illuma-law/healthcheck-storage) | Storage disk writability |
| [`healthcheck-stripe`](https://github.com/illuma-law/healthcheck-stripe) | Stripe API connectivity |
| [`healthcheck-mercure`](https://github.com/illuma-law/healthcheck-mercure) | Mercure hub connectivity |
| [`healthcheck-ai`](https://github.com/illuma-law/healthcheck-ai) | AI provider reachability |

## AI & content

| Package | What it does |
|---|---|
| [`laravel-llm-router`](https://github.com/illuma-law/laravel-llm-router) | Route requests across LLM providers |
| [`laravel-prompt-registry`](https://github.com/illuma-law/laravel-prompt-registry) | Dynamic agent prompt registration & retrieval |
| [`laravel-semantic-deduper`](https://github.com/illuma-law/laravel-semantic-deduper) | Embedding-based content deduplication |
| [`laravel-content-sentinel`](https://github.com/illuma-law/laravel-content-sentinel) | Configurable moderation pipeline |

## Search

| Package | What it does |
|---|---|
| [`laravel-hybrid-search`](https://github.com/illuma-law/laravel-hybrid-search) | Combine lexical + vector search |
| [`laravel-vector-schema`](https://github.com/illuma-law/laravel-vector-schema) | Vector column/index management |
| [`scout-lunr`](https://github.com/illuma-law/scout-lunr) | Lunar.js driver for Laravel Scout |

## Integrations

| Package | What it does |
|---|---|
| [`laravel-places-scout`](https://github.com/illuma-law/laravel-places-scout) | Google Places API with typed DTOs |
| [`laravel-edge-clear`](https://github.com/illuma-law/laravel-edge-clear) | Standalone Cloudflare cache purging |
| [`laravel-vault-cipher`](https://github.com/illuma-law/laravel-vault-cipher) | Envelope encryption via HashiCorp Vault |
| [`laravel-social-caster`](https://github.com/illuma-law/laravel-social-caster) | Broadcast social updates |
| [`laravel-wayfinder-forge`](https://github.com/illuma-law/laravel-wayfinder-forge) | Wayfinder asset building |
| [`laravel-cache-swoole-table`](https://github.com/illuma-law/laravel-cache-swoole-table) | Swoole table cache driver |

## License

MIT. Maintained by [Miguel Enes](https://github.com/miguelenes).
