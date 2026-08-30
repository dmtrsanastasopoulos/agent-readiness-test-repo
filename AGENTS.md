# Agent Instructions

Use pnpm for all package management.

This project targets Node 22.

Run these commands before completing changes:

- `pnpm test`
- `pnpm lint`
- `pnpm typecheck`
- `pnpm build`

## Generated files

Files under `src/generated/` are generated and must never be edited directly. Run `pnpm generate` after schema changes.
