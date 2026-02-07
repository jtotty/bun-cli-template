# Project Name

## Commands

```bash
bun install          # Install dependencies
bun run dev          # Run the CLI
bun run lint         # Run linter
bun run lint:fix     # Fix linting issues
```

## Stack

- **Runtime:** Bun
- **Language:** TypeScript
- **Linting:** ESLint with @antfu/eslint-config (linting + formatting)
- **Logging:** consola

## Workflow

- Trunk-based development — short-lived feature branches merged to `main`
- **NEVER commit or push directly to `main`** — all changes must go through a PR
- `bun run lint` must pass before merge
