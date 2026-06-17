# ⚠️ This repository has moved

The public developer documentation (**docs.erdo.ai**) now lives in the main `erdo` monorepo at [`docs-public/`](https://github.com/erdoai/erdo/tree/main/docs-public).

It was colocated so that every MCP tool / REST endpoint / SDK change ships its reference update **in the same PR** as the code it documents — the "docs move with the surface" rule.

**Make all documentation changes in `erdo/docs-public/` from now on.** This repo is archived (read-only) and kept only for history.

> Note: docs.erdo.ai must be served from `erdo/docs-public/` — the Mintlify project's content directory should point there. If it still points at this repo, repoint it before relying on doc updates.
