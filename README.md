# Apimo OpenAPI

OpenAPI 3.0 specification of the Apimo API v3, used by partners (portals, CRMs, websites, business tools).

| File | Language |
|---|---|
| `apimo-api3.yaml` | French |
| `apimo-api3-en.yaml` | English |

Both files have the same structure; only the descriptions are translated. Keep them in sync when you change one.

## Publication

Merging into `main` automatically updates the public documentation at [apimo.com/api/webservice](https://apimo.com/api/webservice).

## Contributing

- Work on a branch and open a pull request; never push to `main` directly.
- Validate both files before opening the PR, for example with `openapi-spec-validator apimo-api3.yaml apimo-api3-en.yaml`.
- This repository is public: never include tokens, client data or internal security details.
