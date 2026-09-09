# Capstone Engineering Toolkit Practice

This repository is a practice run for the CSCE 4907 Capstone Engineering Toolkit assignment.

**Language:** TypeScript (Node.js)

## What this sets up

- A minimal TypeScript project with a sample function and unit test
- ESLint for linting, using the TypeScript ESLint plugin
- `tsc` for type-checking
- Vitest as the test runner
- A GitHub Actions CI workflow that runs lint, type-check, and tests on every push and pull request
- MIT License
- A Node-appropriate `.gitignore`

## Local setup

```bash
npm install
npm run lint       # ESLint
npm run typecheck  # tsc --noEmit
npm test           # Vitest
```

## AI use disclosure

Generated the initial project scaffold (README, .gitignore, LICENSE, package.json,
tsconfig.json, ESLint flat config, GitHub Actions workflow, and a placeholder
source file + test) with Claude, prompted with the assignment instructions from
the Capstone Engineering Toolkit lecture (GitHub Actions, branch protection,
licensing, and .gitignore hygiene for a TypeScript repo). Reviewed and adjusted
the generated config before committing.
