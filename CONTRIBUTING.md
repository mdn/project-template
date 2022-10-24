# Contribution guide

![github-profile](https://user-images.githubusercontent.com/10350960/166113119-629295f6-c282-42c9-9379-af2de5ad4338.png)

- [Contribution guide](#contribution-guide)
  - [Ways to contribute](#ways-to-contribute)
  - [Finding an issue](#finding-an-issue)
  - [Ask for help](#ask-for-help)
  - [Pull request lifecycle](#pull-request-lifecycle)
  - [Setting up the development environment](#setting-up-the-development-environment)
    - [Forking and cloning the project](#forking-and-cloning-the-project)
      - [Prerequisites](#prerequisites)
  - [Signing commits](#signing-commits)

Welcome 👋 Thank you for your interest in contributing to our project. We are happy to have you join us! 💖

As you get started, you are in the best position to give us feedback on project areas we might have forgotten about or assumed to work well. These include, but are not limited to, the following:

- Problems found while setting up a new developer environment
- Gaps in our documentation
- Bugs in our automation scripts

If anything doesn't make sense or doesn't work as expected, please open an issue and let us know!

## Ways to contribute

We welcome many different types of contributions including:

<!-- TODO: These are not set in stone and should be reconsidered per project based on needs. -->

- New features and content suggestions.
- Identify and filing issues.
- Providing feedback on existing issues.
- Engaging with the community and asnwering questions.
- Contributing documentation or code.
- Promoting the project in personal circles and social media.

## Finding an issue

We have good first issues for new contributors and help wanted issues suitable for any contributor. Good first issues have extra information to help you make your first contribution a success. Help wanted issues are ideal when you feel a bit more comfortable with the project details.

Sometimes there won’t be any issues with these labels. That’s ok! There is likely still something for you to work on. If you want to contribute but don’t know where to start or can’t find a suitable issue, speak to us on [Matrix](https://matrix.to/#/#mdn:mozilla.org), and we will be happy to help.

Once you find an issue you’d like to work on, please post a comment saying you want to work on it. Something like “I want to work on this” is fine. Also, mention the community team using the `@mdn/mdn-community-engagement` handle to ensure someone will get back to you.

## Ask for help

The best way to reach us with a question when contributing is to use the following channels in the following order of precedence:

- [Start a discussion](https://github.com/mdn/mdn-community/discussions)
- Ask your question or highlight your discussion on [Matrix](https://matrix.to/#/#mdn:mozilla.org).
- File an issue and tag the community team using the `@mdn/mdn-community-engagement` handle.

## Pull request lifecycle

Below is guidance on how to approach pull requests and what you can expect from maintainers and other contributors.

When starting a piece of work, we use a [feature branch workflow](https://www.atlassian.com/git/tutorials/comparing-workflows/feature-branch-workflow) and [conventional commits](https://www.conventionalcommits.org).

We prefer to keep pull requests as small as possible to ease review and make incremental improvements. Generally, smaller pull requests are reviewed and merged faster, which keeps the project moving forward.

When to open a pull request is somewhat situation specific. Sometimes it can be helpful to open a pull request early to get feedback or help from others. In these situations, you should use the [draft pull request feature of GitHub](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests#draft-pull-requests). To make it clear that the intent of the draft pull request is to get feedback, use the `help wanted` label.

If you are opening a draft pull request to ensure that the work is on other contributors’ radar, there is no need to label the pull request.

Once ready for review, you can convert a draft pull request to the [ready-for-review state](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/changing-the-stage-of-a-pull-request). This is one way to use pull requests. The approach you would use more often is to find an issue, signal your interest, and start working on the issue once the issue is assigned to you.

Once you feel confident that the work is ready for review, you will open a pull request. When opening a pull request, [reference the issue or issues](https://docs.github.com/en/issues/tracking-your-work-with-issues/linking-a-pull-request-to-an-issue#linking-a-pull-request-to-an-issue-using-a-keyword) this pull request will close. This eases issue triage as it is clear that a pull request is linked to an issue, and GitHub will automatically close linked issues once the pull request is merged.

On most projects, we use auto assignment for reviews, but if you want a review from a specific person, feel free to [ask them for a review](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/requesting-a-pull-request-review).

You can expect a review from those assigned within 24-48 hours. Once the reviewers have completed their review, we encourage contributors to adhere to a similar timeframe in addressing the feedback. Once you have addressed the review feedback, you should [re-request a review](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/reviewing-changes-in-pull-requests/about-pull-request-reviews#re-requesting-a-review) from the reviewers.

If you find that a pull request has become stalled, feel free to ping the required reviewers using their GitHub username handle. You can also notify the `@mdn/mdn-community-engagement` team using this handle or contact us using [Matrix](https://matrix.to/#/#mdn:mozilla.org).

A reviewer can use GitHub’s suggestions feature when reviewing a pull request. It is the responsibility of the author of the pull request to [accept or reject these suggestions](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/reviewing-changes-in-pull-requests/incorporating-feedback-in-your-pull-request).

This brings up another topic. Suppose the pull request’s author at any time abandons the pull request. In that case, it is the assignee’s responsibility to ensure that the pull request comes to a beneficial conclusion. As a contributor, you can let us know if you can no longer complete the work on the pull request. Responsibility for the pull request then falls on the current assignee.

<!-- TODO: This will be project specific. Sometimes changes might be live instantly or within a few minutes. Update accordingly. -->

Once a pull request is merged, the changes will be live within 24 hours.

## Setting up the development environment

<!-- This is very project specific. The below is merely some guidance that might be applicable for most projects. -->

### Forking and cloning the project

The first step in setting up your development environment is to [fork the repository](https://docs.github.com/en/get-started/quickstart/fork-a-repo) and [clone](https://docs.github.com/en/get-started/quickstart/fork-a-repo#cloning-your-forked-repository) the repository to your local machine.

#### Prerequisites

- [NVM](https://github.com/nvm-sh/nvm) or [NVM for Windows](https://github.com/coreybutler/nvm-windows)
- [Nodejs](https://nodejs.org/en/) (Latest stable release or up to two versions back)

Once you have the above installed and have the repository cloned, it is time to install the project dependencies.

```bash
npm i
```

With the dependencies installed you can start the project with the following command:

```bash
npm start
```

Open `http://localhost:3000` in your browser.

To run the test suite, use the following command:

```bash
npm test
```

<!-- This section is project dependent. For some projects this can be an unnecessary stumbling block. -->

## Signing commits

We require all commits to be signed. GitHub has a detailed guide on [setting up signed commits](https://docs.github.com/en/authentication/managing-commit-signature-verification/signing-commits). If you get stuck, please [ask for help](#ask-for-help).
