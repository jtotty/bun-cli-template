# Bun CLI Template

A minimal, opinionated starter for building CLI tools with Bun and TypeScript.

## Features

- **Bun** runtime and package manager
- **TypeScript** with [@total-typescript/tsconfig](https://github.com/total-typescript/tsconfig)
- **ESLint** with [@antfu/eslint-config](https://github.com/antfu/eslint-config) (linting + formatting)
- **consola** for elegant CLI output
- **VS Code** settings for ESLint integration
- **GitHub Actions** for linting on PRs
- **Claude Code hooks** for auto-linting after edits

## Usage

```bash
# Clone the template (clean, no git history)
bunx degit jtotty/bun-cli-template my-cli

# Navigate and install
cd my-cli
bun install

# Run the CLI
bun run dev
```

## After Cloning

1. Update `name` in `package.json`
2. Update `CLAUDE.md` with project-specific instructions
3. Initialize git: `git init && git add . && git commit -m "Initial commit"`

## Scripts

```bash
bun run dev       # Run src/index.ts
bun run lint      # Check for linting issues
bun run lint:fix  # Auto-fix linting issues
```

## License

MIT
