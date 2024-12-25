# Contributing to Oasis-K

First off, thank you for considering contributing to Oasis-K! It's people like you that make Oasis-K such a great community.

## Code of Conduct

By participating in this project, you are expected to uphold our [Code of Conduct](CODE_OF_CONDUCT.md).

## How Can I Contribute?

### Reporting Bugs

- Ensure the bug was not already reported by searching on GitHub under [Issues](https://github.com/oasis-k/oasis-k/issues).
- If you're unable to find an open issue addressing the problem, [open a new one](https://github.com/oasis-k/oasis-k/issues/new). Be sure to include a title and clear description, as much relevant information as possible, and a code sample or an executable test case demonstrating the expected behavior.

### Suggesting Enhancements

- Check the [Issues](https://github.com/oasis-k/oasis-k/issues) page to see if the enhancement has already been suggested. If it has, add a comment to the existing issue instead of opening a new one.
- When creating an enhancement suggestion, please include as many details as possible. Fill in [the template](https://github.com/oasis-k/oasis-k/blob/main/.github/ISSUE_TEMPLATE/feature_request.md), including the steps that you imagine you would take if the feature you're requesting existed.

### Your First Code Contribution

Unsure where to begin contributing to Oasis-K? You can start by looking through these `beginner` and `help-wanted` issues:

- [Beginner issues](https://github.com/oasis-k/oasis-k/labels/beginner) - issues which should only require a few lines of code, and a test or two.
- [Help wanted issues](https://github.com/oasis-k/oasis-k/labels/help%20wanted) - issues which should be a bit more involved than `beginner` issues.

### Pull Requests

1. Fork the repo and create your branch from `main`.
2. If you've added code that should be tested, add tests.
3. If you've changed APIs, update the documentation.
4. Ensure the test suite passes.
5. Make sure your code lints.
6. Issue that pull request!

## Styleguides

### Git Commit Messages

- Use the present tense ("Add feature" not "Added feature")
- Use the imperative mood ("Move cursor to..." not "Moves cursor to...")
- Limit the first line to 72 characters or less
- Reference issues and pull requests liberally after the first line

### JavaScript Styleguide

All JavaScript must adhere to [JavaScript Standard Style](https://standardjs.com/).

### Documentation Styleguide

- Use [Markdown](https://daringfireball.net/projects/markdown/).
- Reference methods and classes in markdown with the custom `{}` notation:
    - Reference classes with `{ClassName}`
    - Reference instance methods with `{ClassName::methodName}`
    - Reference class methods with `{ClassName.methodName}`

## Additional Notes

### Issue and Pull Request Labels

This section lists the labels we use to help us track and manage issues and pull requests.

[GitHub search](https://help.github.com/articles/searching-issues/) makes it easy to use labels for finding groups of issues or pull requests you're interested in.

The labels are loosely grouped by their purpose, but it's not required that every issue has a label from every group or that an issue can't have more than one label from the same group.

Please open an issue if you have suggestions for new labels!

#### Type of Issue and Issue State

- `enhancement`: Feature requests.
- `bug`: Confirmed bugs or reports that are very likely to be bugs.
- `question`: Questions more than bug reports or feature requests (e.g. how do I do X).
- `feedback`: General feedback more than bug reports or feature requests.
- `help-wanted`: The Oasis-K core team would appreciate help from the community in resolving these issues.
- `beginner`: Less complex issues which would be good first issues to work on for users who want to contribute to Oasis-K.
- `more-information-needed`: More information needs to be collected about these problems or feature requests (e.g. steps to reproduce).
- `needs-reproduction`: Likely bugs, but haven't been reliably reproduced.
- `blocked`: Issues blocked on other issues.
- `duplicate`: Issues which are duplicates of other issues, i.e. they have been reported before.
- `wontfix`: The Oasis-K core team has decided not to fix these issues for now, either because they're working as intended or for some other reason.
- `invalid`: Issues which aren't valid (e.g. user errors).

#### Topic Categories

- `documentation`: Related to any type of documentation.
- `performance`: Related to performance.
- `security`: Related to security.
- `ui`: Related to visual design.
- `crash`: Related to application crashes.
- `network`: Related to network problems or operations.
- `build`: Related to build problems.
- `tests`: Related to tests and QA.

Thank you for contributing to Oasis-K!

