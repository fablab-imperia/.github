**English** | [Italiano](CONTRIBUTING.it.md)

# Contributing to Fablab Imperia projects

Thank you for your interest in contributing! Fablab Imperia is a volunteer-run non-profit, and our projects grow through *peer learning* — people helping each other build and understand things. You don't need to be an expert to take part. This guide applies across all Fablab Imperia repositories.

By participating, you agree to follow our [Code of Conduct](CODE_OF_CONDUCT.md).

## Ways to contribute

There's more than one way to help:

- **Report a bug** or suggest an improvement by opening an issue.
- **Improve documentation** — fixing a typo, clarifying a step, or translating a page all count.
- **Write code, design hardware, or model parts** and open a pull request.
- **Help others** by answering questions in issues and discussions.
- **Share your build** — document what you made so the next person can learn from it.

If you're not sure where to start, look for issues labelled **good first issue**, or just ask.

## Our shared responsibilities

In the spirit of the [Fab Charter](https://fabfoundation.org/global-community/#the-fab-charter), contributing carries three responsibilities: **safety** (don't endanger people or machines), **operations** (help keep the projects and lab in good shape), and **knowledge** (document what you do so others can build on it).

## Opening an issue

Before opening a new issue, please search existing ones to avoid duplicates. When you open one, pick the template that fits — **Bug**, **Feature**, or **Task** — and fill in what you can. Good detail (what you expected, what happened, versions if relevant) makes an issue actionable.

Please don't use the issue tracker for security problems — see [SECURITY.md](SECURITY.md) instead.

## Opening a pull request

1. **Fork** the repository and create a branch from `main` (e.g. `fix/sensor-null-read`).
2. Make your change, keeping it focused — smaller PRs are easier to review and merge.
3. **Test locally** and make sure any checks pass.
4. Open the pull request, fill in the template, and **link the issue** it addresses (`Closes #123`).
5. A maintainer will review it. Expect some back-and-forth — that's normal and part of the learning.

Reviews are done by volunteers in their spare time, so please be patient.

## Language and style

- **Code, identifiers, commit messages, and code comments: English.** This keeps the codebase readable for the wider maker community.
- **User-facing documentation and READMEs: English or Italian** (Italian is welcome, and translations are especially valued).
- Follow the existing conventions of the repository you're working in (naming, structure, formatting). Each repo may add its own specifics in its README.

## Commit messages and versioning

Across Fablab Imperia repositories we follow two widely-used conventions:

- **[Conventional Commits 1.0.0](https://www.conventionalcommits.org/en/v1.0.0/)** for commit messages. Each message starts with a type, optionally followed by a scope, then a short description:

  ```
  feat(sensor): add null-read fallback
  fix: correct temperature offset
  docs(readme): document build steps
  ```

  The most common types and when to use them:

  - **`feat`** — a new feature or capability for the user.
  - **`fix`** — a bug fix.
  - **`docs`** — documentation-only changes (README, comments, guides).
  - **`style`** — formatting or whitespace changes that don't affect behaviour.
  - **`refactor`** — code changes that neither fix a bug nor add a feature.
  - **`perf`** — a change that improves performance.
  - **`test`** — adding or fixing tests.
  - **`build`** — changes to the build system or dependencies.
  - **`ci`** — changes to CI configuration or scripts.
  - **`chore`** — routine maintenance that doesn't touch source or tests.
  - **`revert`** — reverts a previous commit.

  A breaking change is marked with a `!` after the type/scope (e.g. `feat!:`) or with a `BREAKING CHANGE:` footer. Consistent commit messages make history easier to read and let us automate changelogs and releases.

- **[Semantic Versioning 2.0.0](https://semver.org/spec/v2.0.0.html)** for release numbers, in the form `MAJOR.MINOR.PATCH`: increment `MAJOR` for incompatible changes, `MINOR` for backward-compatible features, and `PATCH` for backward-compatible fixes.

## Licensing

Each repository states its own license (for example GPL-3.0 for software, or CERN-OHL-S and CC-BY-SA for hardware and documentation). By contributing, you agree that your contribution is provided under that repository's license, and that you have the right to submit it. In line with the Fab Charter, what we make should remain available for others to use and learn from.

## Getting help

- Browse the [Fablab Imperia wiki](https://wiki.fablabimperia.org/) and [blog](https://fablabimperia.org/blog/).
- Come to an [event](https://fablabimperia.org/eventi/) or visit the lab.
- Write to us at **info@fablabimperia.org**.
- Members also have access to the association's WhatsApp/Telegram groups.

Welcome aboard — *if I make, I learn.*
