# Contributing Guidelines

The following is a set of guidelines for contributing to this project. We really appreciate that you are considering contributing!

#### Table of Contents

- [Getting Started](#getting-started)
- [Contributing](#contributing)
- [Code Guidelines](#code-guidelines)
- [Code of Conduct](/CODE_OF_CONDUCT.md)

## Getting Started

Follow the instructions on the README's [Blog Submission Process](/README.md#Blog-Submission-Process) section to get started!.

## Contributing

### Report a Bug

To report a bug, open an issue on GitHub with the label `bug` using the available [bug report issue form](/.github/ISSUE_TEMPLATE/bug_report.yml). Please ensure the bug has not already been reported. **If the bug is a potential security vulnerability, please report it using our [security policy](/SECURITY.md).**

### Suggest a Feature or Enhancement

To suggest a feature or enhancement, please create an issue on GitHub with the label `enhancement` using the available [feature request issue form](/.github/ISSUE_TEMPLATE/feature_request.yml). Please ensure the feature or enhancement has not already been suggested.

### Open a Pull Request (PR)

- Fork the repo, create a branch, implement your changes, add any relevant tests, and submit a PR when your changes are **tested** and ready for review.
- Fill in the [PR template](/.github/pull_request_template.md).

> [!NOTE]
> If you'd like to implement a new feature, please consider creating a [feature request issue](/.github/ISSUE_TEMPLATE/feature_request.yml) first to start a discussion about the feature.

#### F5 Contributor License Agreement (CLA)

F5 requires all contributors to agree to the terms of the F5 CLA (available [here](https://github.com/f5/f5-cla/blob/main/docs/f5_cla.md)) before any of their changes can be incorporated into an F5 Open Source repository (even contributions to the F5 CLA itself!).

If you have not yet agreed to the F5 CLA terms and submit a PR to this repository, a bot will prompt you to view and agree to the F5 CLA. You will have to agree to the F5 CLA terms through a comment in the PR before any of your changes can be merged. Your agreement signature will be safely stored by F5 and no longer be required in future PRs.

## Code Guidelines

### Blog Markdown Guidelines

- Use clear structure: start with a top-level `# Title`, then sections with `##`, `###` as needed.
- Keep headings sentence case: e.g., `## Writing Style`.
- Write concise paragraphs prefer short sentences. Aim for readability.
- Use relative links within the repo (e.g., `../path/to/file.md`); avoid absolute GitHub URLs when possible.
- Provide descriptive alt text for images: `![Alt text describing the image](path "Optional title")`.
- Store images alongside the blog post when feasible (e.g., under `blogs/<your-blog>/assets/`).
- Use fenced code blocks with language hints (e.g., `js`, `bash`, `yaml`). Avoid inline HTML for code styling.
- Prefer lists over long prose for steps; use `-` for unordered lists and `1.` for ordered lists.
- Keep line length reasonable (recommend ~120 chars). Do not hard-wrap mid-sentence unless necessary.
- Tables are fine for compact data; keep them simple and readable.
- Avoid raw HTML unless Markdown cannot express the layout you need.
- Use backticks for file paths, commands, and identifiers: `README.md`, `nginx.conf`, `kubectl get pods`.
- Include references at the end when citing external sources; link to official docs over third-party blogs.
- File names: use lowercase kebab-case for blog directories and files (e.g., `my-first-post.md`).
- Lint locally if you use markdown linters (e.g., `markdownlint`); fix common issues like trailing spaces and inconsistent headings.
- Accessibility: avoid “click here”; link meaningful text and ensure sufficient contrast in any images.

### Git Guidelines

- Keep a clean, concise and meaningful git commit history on your branch (within reason), rebasing locally and squashing before submitting a PR.
- If possible and/or relevant, use the [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) format when writing a commit message, so that changelogs can be automatically generated.
- Follow the guidelines of writing a good commit message as described here <https://chris.beams.io/posts/git-commit/> and summarized in the next few points:
  - In the subject line, use the present tense ("Add feature" not "Added feature").
  - In the subject line, use the imperative mood ("Move cursor to..." not "Moves cursor to...").
  - Limit the subject line to 72 characters or less.
  - Reference issues and pull requests liberally after the subject line.
  - Add more detailed description in the body of the git message (`git commit -a` to give you more space and time in your text editor to write a good message instead of `git commit -am`).
