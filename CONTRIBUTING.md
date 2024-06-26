# Contributing Guidelines

You can contribute to the University of Adelaide Computer Science Club (CS Club) website with issues, PRs, and testing of PRs. We appreciate your efforts to make our projects better.

## Reporting issues

We always welcome bug reports, feature requests, and overall feedback. Here are a few tips on how you can make an effective issue report.

### Finding existing issues

Before creating a new issue, please search our open issues to check if it already exists. If you do find an existing issue, please add your own feedback in the discussion.

### Writing a good bug report

Writing good bug reports makes it easier for maintainers and contributors to verify and identify the root cause of the problem. The better the bug report, the faster the problem can be resolved. A bug report should contain the following information:

- Description of the Bug: What's the issue you encountered?
- Reproduction Steps: How can the issue be reproduced?
- Expected Behaviour: What do you expect to happen?
- Information on the environment: OS, Browser, Device, etc.
- Additional Notes: Add any other notes or screenshots about the bug here.

When you are ready to submit a bug report, please use the project’s bug report issue template. If there is no template for this project, please use the default [Bug Report issue template](./.github/ISSUE_TEMPLATE/bug-report.yml).

### Writing a good feature request

Writing good feature requests makes it easier for maintainers to understand the feature and see how it fits into the website. The better the feature request, the faster the feature can be discussed and possibly implemented. A feature request should contain the following information:

- Overview: Include the basic, high-level concepts for this feature here.
- Details: These may include specific methods of implementation, design considerations, or any other technical details.
- Why would this feature be useful?: A clear and concise description of why this feature would improve the project.
- Additional Notes: Add any other notes or screenshots about the feature request here.

When you are ready to submit a request, please use the project’s feature request issue template. If there is no template for this project, please use the default [Feature Request issue template](./.github/pull_request_template.md).

## Contributing changes

Project maintainers will merge changes that both improve the project and meet our code quality standards. For more information regarding specific topics, please consult the project’s documentation.

### Suggested workflow

We recommend you to use the following workflow:

1. Fork and clone the repository to your computer.
    ```sh
    git clone https://github.com/YOUR_GITHUB_USERNAME/PROJECT_NAME.git
    ```
2. Create a new branch from `main` with a relevant name for a new feature or a bug you want to work on.
    ```sh
    git checkout -b your-relevant-branch-name
    ```
3. Follow the project’s README file on how to set up the project.
4. Push your branch.
    ```sh
    git push -u origin your-relevant-branch-name
    ```
5. Once you are happy with your changes, create a pull request (PR) with a relevant title and description to merge your changes into the repository's main branch.
6. Wait for feedback and approval of your changes from the maintainers
7. When the maintainers have signed off, all checks are green, and there are no merge conflicts, your PR will be merged.

### Commit messages

Before you create a PR, please check whether your commits comply with the commit conventions used for this repository. When you create a commit, please follow the convention `<type>[optional scope]: <description>` in your commit message while using one of the following categories:

- `feat`: Adds a new feature
- `fix`: Fixes a bug (please reference an existing issue if present)
- `refactor`: Restructures code while not changing its original functionality
- `docs`: Changing existing or creating new documentation (i.e. README or other markdown files)
- `build`: Changing the build system or dependencies
- `style`: Related to code formatting (i.e. Fixing linting or Prettier errors)
- `ci`: Changing the configuration of continuous integration (i.e. Github actions)
- `chore`: Changes that do not fit into any of the above categories

For example:

```
feat(db): Add database schema

ci: Add prettier to CI workflow
```

If you are interested in the detailed specification you can visit https://www.conventionalcommits.org/.

## Pull request (PR) - CI process

Automatic tests will be performed for PRs. Builds and test runs must not contain errors or have bugs properly filed against unexpected errors that are unrelated to your change.

If the CI build fails for any reason, the PR actions tab should be consulted for more information on the error.

## Pull request (PR) feedback

The maintainers and community members will provide feedback on your change. Community feedback is highly valued. When giving feedback, please be clear and concise.

## License

By contributing your code to our repository, you agree to licence your contribution under the MIT License, unless otherwise specified in the project repository.
