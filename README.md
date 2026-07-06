# Keystone Commerce Partner Integration APIs Docs

Mintlify documentation for Keystone Commerce integration APIs.

## Local preview

Install the Mintlify CLI:

```bash
npm i -g mint
```

Run the local preview from the repository root:

```bash
mint dev
```

## Structure

- `docs.json` configures the Mintlify site and navigation.
- `index.mdx` is the docs landing page.
- `getting-started.mdx` covers the base URL, response format, and health checks.
- `authentication.mdx` covers API keys and customer JWT auth.
- `catalog.mdx` covers categories, products, and search.
- `customers.mdx` covers profile and address APIs.
- `orders-payments.mdx` covers checkout and payment initiation.
- `wallet.mdx` covers wallet quote and wallet summary APIs.
- `returns-support.mdx` covers support tickets, evidence uploads, and returns.
- `errors.mdx` covers common error responses.

Pushing to `main` publishes the docs through Mintlify.
