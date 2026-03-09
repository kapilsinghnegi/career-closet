# Contributing to Career Closet

Thank you for contributing!

We welcome all contributors, regardless of skill level. If you have a question, comment, or need help, please don't hesitate to ask in the [Career Closet Discord](https://discord.gg/5d8DSWbc7F).

---

## Branching Strategy

We use a simple, industry-standard workflow:

### Protected Branches

- `main` → stable, production-ready code
- `dev` → active development branch

⚠️ Do not commit directly to `main` or `dev`.

### Feature Branches

Create a new branch from `dev` for every task:

- `feature/<short-description>` or ``feat/<short-description>`
- `fix/<short-description>`
- `docs/<short-description>`

Examples - feature/login-ui, feat/api-endpoint, fix/api-error, docs/update-readme

### Keeping `dev` and `main` in Sync

- `dev` should always contain all changes from `main`
- If changes are merged directly into `main`, they must be merged back into `dev`
- Feature work always branches from `dev`, never from `main`

---

## Development Workflow

### 1. Fork the repository

Fork the repository: Click the "Fork" button at the top right of the repository page.

### 2. Clone your forked repository

```bash
git clone https://github.com/<your-username>/career-closet.git
```

### 3. Create a branch

Use naming conventions as described above.

```bash
git checkout -b feature/feature-name
```

### 4. Commit using [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/)

```bash
git add <files>
git commit -m "<short-description>"
```

### 5. Push your branch

```bash
git push origin feature/branch-name
```

### 6. Open a Pull Request

Create a PR targeting `dev` branch: Base branch: `dev`, Compare branch: `<your feature branch>`.

Your PR will be reviewed before merging

---

## Pull Requests (PRs)

### PR Guidelines

- Keep PRs **small and focused**
- Code works locally and contains no unnecessary files
- Follow project structure
- Link the related issue (e.g. `Closes #12`)
- Use clear commit messages
- Final approval authority for merges into protected branched rests with the Project Maintainers

---

## Code Review

Each PR requires:

- 1 approval for `dev`
- 2 approvals for `main`

Code owners may automatically be requested for review.

---

## Reporting Issues

If you encounter a bug:

1. Open a GitHub Issue
2. Describe the problem
3. Include reproduction steps
