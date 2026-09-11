# Obsidian Honor Coders — Organization Governance & Profile

This repository holds **organization-wide defaults** for **Obsidian Honor
Coders**.

## What lives here

| Path | Purpose |
|------|---------|
| `profile/README.md` | Organization profile shown on GitHub. |
| `.github/workflows/` | Shared GitHub Actions workflows. |
| `CODE_OF_CONDUCT.md` | Fallback code of conduct for every repo. |
| `CONTRIBUTING.md` | Fallback contribution guide for every repo. |
| `SECURITY.md` | Fallback security policy for every repo. |
| `SUPPORT.md` | Fallback support info for every repo. |
| `ISSUE_TEMPLATE/` | Default issue templates for every repo. |

## How it works

GitHub automatically uses these files as **fallbacks** for any repository in
the organization that doesn't provide its own:

- **Profile** → `profile/README.md` renders at
  `github.com/ObsidianHonorCoders`
- **Community files** → Shown in each repo's "Community Standards" check
- **Workflows** → Reference via
  `uses: ObsidianHonorCoders/.github/.github/workflows/...@main`

## Contributing

Changes here affect the entire organization. Open a PR and ping a maintainer.
