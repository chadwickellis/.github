# Contributing

Thank you for your interest in contributing! This document outlines the general guidelines for contributing to my repositories.

---

## How Can I Contribute?

### Reporting Issues

If you find a bug, have a question, or want to suggest a new feature:

- Check the repository's issue tracker to ensure your issue hasn't already been reported.
- Create a new issue and include:
  - A clear and descriptive title.
  - Steps to reproduce the issue (if applicable).
  - Expected and actual behaviour.
  - Any relevant environment details (e.g., OS, Node.js version).

---

### Suggesting Enhancements

If you have an idea for improving the repository:

- Open a new issue and provide:
  - The problem your suggestion solves.
  - A clear and concise description of the enhancement.

---

### Submitting Changes

#### Fork the Repository

1. Fork the repository on GitHub.
2. Clone your fork to your local machine:

   ```bash
   git clone https://github.com/<username>/<repository>.git
   ```

3. Add the original repository as an upstream remote:

   ```bash
   git remote add upstream https://github.com/chadwickellis/<repository>.git
   ```

#### Create a Branch

1. Create a branch for your changes:

   ```bash
   git checkout -b <branch>
   ```

#### Make Changes

- Follow the code style and conventions of the repository.
- Add comments to explain complex or non-obvious changes.
- Update documentation where necessary.
- Add or update tests to cover your changes.

#### Testing and Linting

Before submitting your changes:

1. Install dependencies:

   ```bash
   pnpm install
   ```

2. Check for linting issues:

   ```bash
   pnpm check
   ```

3. Run tests:

   ```bash
   pnpm test
   ```

#### Commit Your Changes

1. Write clear, descriptive commit messages following the [Conventional Commits](https://www.conventionalcommits.org) specification:
   - `feat: add support for advanced search filters`
   - `fix: resolve token expiration issue in authentication flow`
   - `docs: add contribution examples to README.md`
   - `chore: upgrade dependencies to improve stability`
   - `test: add unit tests for user authentication API methods`
2. Stage and commit your changes:

   ```bash
   git add .
   git commit -m <message>
   ```

#### Push Your Branch

1. Push the branch to your fork:

   ```bash
   git push origin <branch>
   ```

#### Open a Pull Request

1. Navigate to the original repository.
2. Open a pull request (PR) from your branch.
3. Provide a detailed description of your changes, the problem they address, and any additional context.

---

## Behaviour Expectations

Please ensure your interactions align with our [Code of Conduct](CODE_OF_CONDUCT.md), fostering a welcoming and inclusive environment for all contributors.

---

## Support During Contributions

If you are unsure about any part of the contribution process, need guidance, or want to share ideas, feel free to ask questions by opening an issue or discussion. Contributions of all sizes and experience levels are welcome, from typo fixes to significant features. I'm here to help!

---

## Thank You

Your contributions help make this project better for everyone. I appreciate your time, effort, and expertise. Thank you for being a part of the community!
