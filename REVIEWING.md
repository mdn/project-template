# Reviewing guide

- [Reviewing guide](#reviewing-guide)
  - [The Reviewer Role](#the-reviewer-role)
  - [Values](#values)
    - [Inclusion](#inclusion)
    - [Sustainability](#sustainability)
    - [Trust](#trust)
  - [Process](#process)
    - [Maintainer edge cases](#maintainer-edge-cases)
    - [General review guidance](#general-review-guidance)
      - [Request changes](#request-changes)
      - [Comment](#comment)
      - [Approve](#approve)
  - [Checklist](#checklist)
  - [Reading List](#reading-list)

## The Reviewer Role

The reviewer role is distinct from the maintainer role. Reviewers can approve a pull request but they cannot merge it. A maintainer handles final approval and merging the pull request.

## Values

All reviewers must abide by the [Code of Conduct](CODE_OF_CONDUCT.md) and are also protected by it. A reviewer should not tolerate poor behavior and is encouraged to [report](CODE_OF_CONDUCT.md#enforcement) any behavior that violates the Code of Conduct. All of our values listed below are distilled from our Code of Conduct.

Below are concrete examples of how it applies to code review specifically:

### Inclusion

Be welcoming and inclusive. You should proactively ensure that the author is successful. While all pull requests may not ultimately be merged, we want people to have a great experience and be willing to contribute again. Please answer the questions they didn't know to ask or offer concrete help when they appear stuck.

### Sustainability

Avoid burnout by enforcing healthy boundaries. Here are some examples of how a reviewer is encouraged to act to take care of themselves:

- Authors should meet baseline expectations when submitting a pull request. Refer to the [pull request lifecycle](CONTRIBUTING.md#pull-request-lifecycle) for guidance.
- If your availability changes, you can step down from a pull request and assign or ask the community team to assign a new reviewer. You can notify the community team using the `@mdn/mdn-community-engagement` handle.
- If interactions with an author are not following the code of conduct, notify the community team (`@mdn/mdn-community-engagement`) and close the pull request. The community team will lock the pull request and engage with the contributor. It's not your job to coax people into behaving.

### Trust

Be trustworthy. During a review, your actions both build and help maintain the trust that the community has placed in this project. Below are examples of ways that we build trust:

- **Transparency** - If a pull request won't be merged, clearly say why and close it. If a pull request won't be reviewed for a while, let the author know so they can set expectations and understand why it's blocked. For first-time contributors, it will also be helpful to provide a link to the [pull request lifecycle](CONTRIBUTING.md#pull-request-lifecycle) process.
- **Integrity** - Put the project's best interests ahead of personal relationships or company affiliations when deciding if a change should be merged.
- **Stability** - Only merge when then change won't negatively impact project stability. It can be tempting to merge a pull request that doesn't meet our quality standards, for example when the review has been delayed, or because we are trying to deliver new features quickly, but regressions can significantly hurt trust in our project.

For additional guidance, this [article by Voxmedia](https://product.voxmedia.com/2018/8/21/17549400/kindness-and-code-reviews-improving-the-way-we-give-feedback) has some great advice on kindness during code reviews.

## Process

We use review auto-assignment based on a `CODEOWNERS` file but, if there is a specific person you want to request review from, please do manually [request a review](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/requesting-a-pull-request-review). If you are not able to request a review using the method mentioned, you can also ask for review by [mentioning the reviewer](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#mentioning-people-and-teams) using their GitHub username. We also use auto-labeling of issues and pull requests. Maintainers will also triage pull requests and assign any additional labels if needed based on context.

Before starting your review, ensure that all continuous integration (CI) tasks have been completed successfully and that there are no merge conflicts. If any tasks fail or there are merge conflicts, communicate this to the author. It is the author's responsibility to address these. With that said, do leave the door open to the author to ask for help. This is especially relevant for new contributors to the project.

Should an author need help with fixing merge comflicts or failing CI tasks, the reviewer can offer to fix these issues by applying fixes themselves to the branch. Sometimes it is also possible to fix the problems using GitHub's [suggestions feature](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/reviewing-changes-in-pull-requests/incorporating-feedback-in-your-pull-request).

Do keep the following in mind from the [Kubernetes guide](https://kubernetes.io/docs/contribute/review/for-approvers/):

> Do not "take over" for another person unless they explicitly ask you to, or you want to resurrect a long-abandoned PR. While it may be faster in the short term, it deprives the person of the chance to contribute.

A review from a maintainer could be needed for changes to certain files. If this is the case, the CI system will clarify this and auto-assign the maintainer's team.

### Maintainer edge cases

Unless a reviewer does not have write access, it is always the responsibility of one of the reviewers to merge the pull request once approved. In rare cases, such as when a build or a production instance is broken, a maintainer may merge their pull request without requiring review.

In these rare cases, there should ideally be a retrospective to determine where in the contribution chain the error was introduced, and measures to avoid this in the future should be put into place.

### General review guidance

Prefer a review process over individual comments on a pull request. Sometimes when reviewing a large pull request, another piece of code may provide additional context that was missed initially. The pull request review flow allows you to change previous comments before submitting the review.

When submitting your review you have three options, approve, comment, or request changes. Listed below are guidance on when to use which option.

#### Request changes

Use the request changes option when the feedback you provided _needs_ to be addressed by the author and re-reviewed by the reviewer before the pull request can be approved and merged.

#### Comment

Use the comment option when your feedback is not critical and will not require a re-review. In short, you trust the author and other reviewers to use good judgment.

#### Approve

Use the approve option when everything looks good and is ready to merge from your perspective. After submitting your review, you can safely merge the pull request if there are no other reviewers or any outstanding review comments to address.

## Checklist

Below are a set of common questions that apply to all pull requests:

- [ ] Is this pull request targeting the correct branch?
- [ ] Does the commit message provide an adequate description of the change?
- [ ] Does the pull request description [reference the issue or issues](https://docs.github.com/en/issues/tracking-your-work-with-issues/linking-a-pull-request-to-an-issue#linking-a-pull-request-to-an-issue-using-a-keyword) it will close?
- [ ] Does the pull request follow a [feature branch workflow](https://www.atlassian.com/git/tutorials/comparing-workflows/feature-branch-workflow)?
- [ ] Does the pull request follow [conventional commits](https://www.conventionalcommits.org)?
- [ ] Does this introduce breaking changes that would require an announcement or bumping the major version?

## Reading List

Reviewers are encouraged to read the following articles for help with common reviewer tasks:

- [The Art of Closing: How to closing an unfinished or rejected pull request](https://blog.jessfraz.com/post/the-art-of-closing/)
- [Kindness and Code Reviews: Improving the Way We Give Feedback](https://product.voxmedia.com/2018/8/21/17549400/kindness-and-code-reviews-improving-the-way-we-give-feedback)
- [Code Review Guidelines for Humans: Examples of good and back feedback](https://phauer.com/2018/code-review-guidelines/#code-reviews-guidelines-for-the-reviewer)
