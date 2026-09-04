# SMC Trader Frontend

This repository is currently a placeholder for the frontend of an SMC Trader application. The tracked tree contains only a README and does not yet include React/Vite/Next source, a package manifest, styling, or a build configuration.

## Intended integration

The repository name and project family suggest that it may eventually consume a separate SMC Trader backend. Until an API contract is committed, the frontend should not assume endpoint names, authentication behavior, market-data schemas, or signal semantics.

## Recommended first implementation

Add a package manifest and frontend scaffold, define environment variables for a non-secret backend base URL, document the authentication flow, and provide loading, stale-data, error, and paper-trading states. Keep broker credentials and privileged market-data keys on the server.

## Status

Initialization only. There is no runnable frontend code in the current revision.
