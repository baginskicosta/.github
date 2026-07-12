## :handshake: Contributing Guide

Thank you for your interest in contributing to this project.

This guide describes the general workflow, expectations, and conventions
followed by the project. Adhering to these guidelines helps keep
contributions consistent, maintainable, and easy to review.

## :rocket: Getting Started

1. Fork the repository.
2. Clone your fork:

   ```bash
   git clone git@github.com:{YOUR_USERNAME}/{REPOSITORY_NAME}.git
   ```

3. Install the project's dependencies according to the instructions provided
   in the `README.md`.

## :twisted_rightwards_arrows: Branching Strategy

Always create a dedicated branch for your work instead of committing directly
to the default branch.

Example:

```bash
git checkout -b feat/your-feature-name
```

Recommended branch prefixes:

- `feat/` — new features.
- `fix/` — bug fixes.
- `docs/` — documentation.
- `refactor/` — code refactoring.
- `test/` — tests.
- `chore/` — maintenance tasks.

Use concise, descriptive branch names that clearly reflect the purpose
of the changes.

## :hammer_and_wrench: Making Changes

When contributing:

- Keep each contribution focused on a single purpose.
- Follow the existing project structure, architecture, and coding style.
- Avoid unrelated changes in the same pull request.
- Do not modify governance or administrative files (such as `LICENSE`,
  `CODE_OF_CONDUCT.md`, `CONTRIBUTING.md`, `SECURITY.md`, or similar)
  unless your contribution specifically targets those files.

## :memo: Commit Conventions

This project follows the **Conventional Commits** specification.

Format:

```text
type(scope): description
```

Common commit types:

- `feat`.
- `fix`.
- `docs`.
- `refactor`.
- `test`.
- `chore`.

Examples:

```text
feat(cli): add configuration command
fix(core): handle empty input correctly
docs: update installation guide
```

Write commit messages in the imperative mood and keep them concise
and descriptive.

## :arrows_counterclockwise: Pull Request Process

Before opening a pull request:

- Push your branch to your fork.
- Open a pull request targeting the project's default branch.
- Use a clear and descriptive title.
- Explain the motivation and scope of your changes.
- Reference related issues when applicable.
- Ensure your changes build successfully and pass any available tests.

## :books: Documentation

If your contribution changes the project's behavior, public API,
configuration, or usage, update the relevant documentation accordingly.

Documentation should remain accurate, consistent, and synchronized with
the implementation.

## :sparkles: Code Quality

Contributions should prioritize:

- Readability;
- Maintainability;
- Simplicity;
- Consistency with the existing codebase.

Whenever possible, include or update tests for new functionality or bug fixes.

## :robot: AI-Assisted Contributions

Contributions should primarily represent original work conceived, designed,
and implemented by a human contributor.

AI-assisted development tools (including code completion, code generation,
refactoring assistance, documentation assistance, and similar technologies)
may be used as productivity aids, provided that:

- The contributor fully understands the submitted code;
- All AI-generated content is carefully reviewed, validated, and tested
  before submission;
- The contributor remains solely responsible for the correctness, security,
  maintainability, and quality of the contribution;
- The majority of the design, architecture, implementation, and
  decision-making originates from the human contributor.

Pull requests consisting predominantly or entirely of AI-generated code may
be rejected without review.

Project maintainers reserve the right to reject contributions that do not
demonstrate sufficient human authorship, technical understanding, or code
quality, regardless of whether AI tools were used during development.

## :white_check_mark: Review Process

All contributions are reviewed before being merged.

Maintainers may request revisions, additional tests, documentation updates,
or other changes to ensure consistency, maintainability, and
long-term quality.

Constructive feedback is considered a normal part of the review process.

## :blue_heart: Thank You

Every contribution—whether it improves code, documentation, tests, or
discussions—is appreciated.

Thank you for helping make this project better.
