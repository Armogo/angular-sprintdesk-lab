# SprintDesk

A practical Angular learning project that simulates
a real-world issue tracking application.

## Tech Stack

- Angular 22
- TypeScript
- pnpm 10.17.1
- Node.js 24.22.0
- Angular ESLint
- Prettier
- Vitest
- Husky + lint-staged
- GitHub Actions

## Getting Started

### Prerequisites

Install Node.js using the version in `.nvmrc`
and enable pnpm.

### Installation

```bash
pnpm install --frozen-lockfile
```

### Start the application

```bash
pnpm start
```

Open http://localhost:4200.

## Development Commands

| Command              | Purpose                  |
| -------------------- | ------------------------ |
| `pnpm start`         | Start development server |
| `pnpm lint`          | Run ESLint               |
| `pnpm format`        | Format code              |
| `pnpm format:check`  | Check formatting         |
| `pnpm test:ci`       | Run tests once           |
| `pnpm test:coverage` | Generate coverage        |
| `pnpm build`         | Production build         |
| `pnpm check`         | Run all quality checks   |

## Git Workflow

1. Select a GitHub Issue.
2. Create a feature branch from `main`.
3. Implement and test changes.
4. Commit changes (pre-commit hooks run).
5. Push and create a pull request.
6. Wait for CI to pass.
7. Review and squash-merge.

## Quality Gates

- Husky and lint-staged validate staged files.
- GitHub Actions runs formatting, lint, tests,
  and production build checks.
- Do not merge a PR with failing or pending CI.

## Project Management

We use GitHub Issues to track learning units,
features, bugs, and technical improvements.
