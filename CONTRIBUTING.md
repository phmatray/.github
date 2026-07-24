# Contributing

Thanks for taking the time to contribute! These guidelines apply across
Philippe Matray's repositories.

## Getting started

1. Fork the repository and create a branch off the default branch.
2. Build and test locally before opening a pull request — the exact commands
   are in each repository's `README`.

## Code style

Every repository ships a shared house-style [`.editorconfig`](https://editorconfig.org).
Please keep your changes consistent with it:

- **.NET** — run `dotnet format` before committing; it applies the style
  (file-scoped namespaces, Allman braces, sorted usings, `_camelCase` fields…)
  automatically.
- **Other languages** — use the project's formatter (`prettier`, `rustfmt`,
  `swiftformat`, `gofmt`, …).

Keep each pull request focused on one logical change.

## Commit messages

Write clear, imperative messages. [Conventional Commits](https://www.conventionalcommits.org)
prefixes are appreciated: `feat:`, `fix:`, `chore:`, `docs:`, `refactor:`, `test:`.

## Pull requests

- Explain **what** changes and **why**.
- Make sure existing tests pass, and add tests for new behavior.
- Link any related issue (`Closes #123`).

Dependency updates are handled automatically by [Renovate](https://docs.renovatebot.com);
you don't need to bump versions by hand.

## Code of Conduct

By participating you agree to abide by our [Code of Conduct](CODE_OF_CONDUCT.md).
