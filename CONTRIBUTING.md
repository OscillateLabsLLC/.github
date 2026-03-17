# Contributing to Oscillate Labs

Thanks for your interest in contributing! This document provides general guidelines for contributing to any Oscillate Labs repository. Some repositories have their own `CONTRIBUTING.md` with project-specific instructions — check the repo first.

## Before You Start

Check the repository's [support status](SUPPORT_STATUS.md):

- **Active** — PRs welcome for features, fixes, and improvements
- **Security Fixes Only** — PRs accepted for security vulnerabilities, critical bugs, and dependency security updates
- **Proof of Concept** — PRs may not receive responses; provided as-is

## Development Setup

### Prerequisites

- Git
- The toolchain for the project (check the repo's README for specifics)

### Getting Started

1. Fork and clone the repository
2. Check for a `Justfile` — if present, `just` is the task runner:

   ```bash
   # Install just: https://github.com/casey/just
   just          # List available tasks
   just install  # Install dependencies (if defined)
   just test     # Run tests
   ```

3. If no Justfile, check the README for setup instructions

## Making Changes

### Commits

We use [conventional commits](https://www.conventionalcommits.org/) to support automated releases and changelogs:

```text
feat: add new feature
fix: resolve bug in parser
docs: update installation instructions
chore: update dependencies
```

### Pull Requests

1. Create a feature branch: `git checkout -b feat-my-feature` (or `fix-` for bug fixes)
2. Make your changes
3. Add or update tests
4. Run the test suite
5. Commit with conventional commit messages
6. Push to your fork and open a pull request

PR titles are also linted for conventional commit format.

## Questions?

- Open an issue for bugs or feature requests
- Check existing issues before creating new ones

## License

By contributing, you agree that your contributions will be licensed under the same license as the repository.
