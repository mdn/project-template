# Contribution roles

Community contributions help this open source project immensely. In return, contributors can use their work on this project to demonstrate their technical and writing skills as well as their ability to participate in team settings and to engage with folks from diverse backgrounds.

This page describes the different roles you, as a contributor, can assume while volunteering on the MDN Web Docs project.

There is usually a step-by-step progress from one role to the next as you take on more responsibilites. We describe here how you can move from one role to the next. You can also skip the progression and assume a role directly if you have the expertise in a particluar area. We discuss this under [Invited expert](#invited-expert). As you'll see, with the advancement in the contribution ladder, you could serve more than one role at the same time.

- [Roles](#roles)
  - [Contributor](#contributor)
  - [Organization member](#organization-member)
  - [Maintainer](#maintainer)
  - [Spotlight contributor](#spotlight-contributor)

- [Specialized roles](#specialized-roles)
  - [Invited expert](#invited-expert)
  - [Community manager](#community-manager)

- [Processes](#processes)
  - [Nominating a spotlight contributor](#nominating-a-spotlight-contributor)
  - [Stepping down voluntarily](#stepping-down-voluntarily)
  - [Gaining emeritus status](#gaining-emeritus-status)
  - [Getting demoted involuntarily](#getting-demoted-involuntarily)

- [Contacting the MDN team](#contacting-the-mdn-team)

## Roles

Irrespective of the role you take on in this project, you always are a contributor. [Contributor](#contributor) is the base role and all other roles build on top of it. As such, you must satisfy the [responsibilities of a contributor](#responsibilities) while working in any capacity on this project.

### Contributor

Contributors, also known as community participants, engage with the project and its community by contributing their time, skills, opinions, and ideas. A contributor contributes directly to the project and adds value to it. Contributions are not limited to writing or testing code examples but also include creating and updating documentation, researching, fixing bugs, and helping other community members.

You can be a new contributor, an active contributor, or someone who contributes only occasionally. If you're new here, you can check out the different [repositories in the MDN projects](https://github.com/orgs/mdn/repositories).

As a contributor, you can get involved with the project by engaging in the following acitivites:

- Participating in community [discussions](https://github.com/mdn/mdn-community/discussions) on GitHub. Check out the different [discussion categories](https://github.com/mdn/mdn-community#github-discussions) in which you can participate.
- Helping other contributors with their pull request submissions or issue resolutions or mentoring new contributors.
- Submitting bug reports. Check out the [kind of issues you can open](https://github.com/mdn/content/issues/new/choose) on MDN's `content` repository. Similarly, if you notice a platform bug, you can [open an issue](https://github.com/mdn/yari/issues/new/choose) on MDN's `yari` repository.
- Commenting on issues to move the thread along towards a fruitful resolution.
- Addressing open issues (for example, in the [`content` repository](https://github.com/mdn/content/issues)) by submitting [pull requests](CONTRIBUTING.md#pull-request-process)
- Attending community events
- Helping to promote the MDN project

#### Responsibilities

You must follow:

- [Mozilla code of conduct](CODE_OF_CONDUCT.md)
- [Contribution guidelines](CONTRIBUTING.md)

#### Privileges

As a contributor, you enjoy the following privileges:

- Invitations to contributor events.
- Eligibility to become an [organization member](#organization-member).

## Organization member

An Organization Member is an established contributor who regularly participates in the project.
Organization Members have privileges on the organization level and, as such, are expected to act in the interests of the whole project.

### Requirements to become an Organization Member

Meet one or more of the following requirements on a monthly basis:

- Two or more accepted pull requests that resolves two or more issues. (TODO: link to finding an issue)
- Must have been contributing for at least two months.
- Must be actively contributing to at least one project area.
- Have two factor authentication enabled for their GitHub account.
- Have enabled [signed commits](https://docs.github.com/en/authentication/managing-commit-signature-verification/signing-commits).

In addition to the responsibilities of a Contributor, Organization Members also have the following responsibilities:

### Responsibilities

- Continues to contribute regularly to the MDN Web Docs project.

### Spotlight contributor

Once a month, we feature a spotlight contributor on the [MDN website](https://developer.mozilla.org/en-US/).

Spotlight contributors are folks who have gone above and beyond with their contributions to MDN Web Docs. Their contributions are in the form of opening pull requests to improve the project, helping community members on GitHub [discussions](https://github.com/mdn/mdn-community/discussions) or learn forums, or providing feedback on GitHub issues and pull requests. To nominate someone, see the [process](#nominating-a-spotlight-contributor) here.

## Invited expert

Invited Experts are responsible for a specific topic area or project component smaller than an entire project.
Invited Experts are automatically assigned for review when pull requests are opened in their topic area.
If there is more than one topic expert, reviewers are assigned using a [load-balancing strategy](https://docs.github.com/en/organizations/organizing-members-into-teams/managing-code-review-settings-for-your-team#about-auto-assignment).

Invited Experts have a track record of contributions, participation, and reviews, or have proven knowledge in a certain area of expertise.
They, together with other Reviewers, are responsible for reviewing changes in their topic area and approving pull requests for merge.

### Invited Experts requirements

- Has demonstrated an in-depth knowledge of the specific area.
- Commits to being responsible for their assigned topic area.
- Is supportive of new and occasional contributors and helps to get pull requests ready to merge.
- Attends the community meeting which takes place once every two months.

#### Process for nominating an Invited Expert

- The nominator will open a pull request using the appropriate [template](https://github.com/mdn/mdn-community/roles/) against the [MDN Web Docs community repository](https://github.com/mdn/mdn-community/).
- The nominee will add a comment to the pull request agreeing to all responsibilities of becoming an Invited Expert.
- To be accepted, the pull request needs three approvals. This can be any combination of Invited Experts, or Maintainers.
- Once the pull request is approved, the new Invited Expert is added to the [invited-experts team](https://github.com/orgs/mdn/teams/invited-experts) and the appropriate topic team.

### Invited experts responsibilities

In addition to the rights and responsibilities of an Organization Member, Invited Experts are responsible for:

- Following the [review guide](REVIEWING.md).
- Reviewing pull requests in their topic area.
- Helping other contributors become reviewers.

### Invited experts privileges

- Have commit access to the repository.
- Can recommend and vote for other members to become Invited Experts.
- Will be added to the Invited Experts and appropriate topic team.

## Maintainer

Maintainers are established contributors who are responsible for one or more projects. As such, they have the ability to approve and merge pull requests, and are expected to participate in making decisions about the priorities of the project.

### Maintainer requirements

- Experience as an invited expert for at least six months.
- Demonstrates a broad knowledge of the project across multiple areas.
- Is able to exercise judgment for the good of the project, independent of the influence of other members.
- A history of mentoring other contributors.
- Can commit to spending at least 16 hours per month working on the project.
- Attends the community meeting which takes place once every two months.

#### Process for nominating a Maintainer

- The nominator will open a pull request using the appropriate [template](https://github.com/mdn/mdn-community/roles/) against the [MDN Web Docs community repository](https://github.com/mdn/mdn-community/).
- The nominee will add a comment to the pull request agreeing to all responsibilities of becoming a Maintainer.
- At least three current Maintainers must approve the pull request.
- Once the pull request is approved, the new Maintainer is added to the [maintainers team](https://github.com/orgs/mdn/teams/maintainers) and any other relevant topic or project teams.

### Maintainer responsibilities

In addition to the responsibilities of all other roles, a Maintainer has these additional responsibilities:

- Determining priorities for the project.
- Participating in community meetings.
- Mentoring new and existing contributors across all other roles.
- If appropriate, based on the skill set of the maintainer:
  - Propose, approve, or implement code and infrastructure improvements.
  - Propose, approve, or implement content improvements.
  - Propose, approve, or implement process improvements.

## Community Manager

The Community Manager role is distinct in many respects. Still, as the projects are technical, the role shares many of the same requirements and responsibilities as the Maintainer role.

In addition to the responsibilities of a Maintainer, the Community Manager has these additional responsibilities.

- Along with Maintainers, address reports where the code of conduct has been violated and decide on the appropriate action.
- Organize and run community events.
- Determine media strategies to promote the project and onboard new contributors and users.
- Define and implement the onboarding experience.
- Organize community-related project meetings.
- Meet with and ensure a healthy relationship with contributors and partners.
- Assist with issue triage as well as pull request review where appropriate.
- Responsible for monitoring all communication channels, including discussions on GitHub.
- Highlight contributors that have done exceptional work and/or have shown dedication to the project and organization.
- Ensure the health and well-being of the project and all participants.
- Identify and assist with the implementation of automation to improve project sustainability.

## Processes

### Nominating a spotlight contributor

See who can be a [spotlight contributor](#spotlight-contributor).

To nominate someone as a spotlight contributor, open an issue on GitHub:
1. Go to [`Issues`](https://github.com/mdn/mdn/issues) in the `mdn/mdn` repository.
2. Click 'New issue` button on the right.
3. Click the 'Get started' button for 'Nominate a spotlight contributor'.
4. Fill in the form with details of the contributions of the person you are nominating.

The MDN team will get in otuch with the nominated person to get their information to be published on the [website](https://developer.mozilla.org/en-US/).

### Turning inactive

Participants must be active to set an example and show commitment to the project.
Conversely, inactivity harms the project as it may lead to unexpected delays, contributor attrition, and a loss of trust in the project.

Inactivity is measured by:

- Periods of no contributions for longer than six months.
- Periods of no communication for longer than three months.

Consequences of being inactive include:

- Involuntary removal or demotion
- Being asked to move to Emeritus status

### Involuntary Removal or Demotion

Involuntary removal/demotion of a contributor happens when responsibilities and requirements aren't being met.
This may include repeated patterns of inactivity, a period of failing to meet the requirements of the role, or a violation of the Code of Conduct.
This process is essential because it protects the community and its deliverables while also opening up opportunities for new contributors to step in.

During a maintainers meeting, a participant can ask to demote or remove a contributor.
In addition, the participant is responsible for adding supporting information to the meeting agenda.
Finally, the matter will be discussed and brought to a vote by all maintainers and community managers.

Please communicate with the community team to avoid the above process should your time commitments change.
In these cases, you can instead proactively choose to step down for a while or move to Emeritus status (see below).

## Stepping Down/Emeritus Process

If and when contributors' commitment levels change, contributors can consider stepping down (moving down the contributor ladder) vs moving to Emeritus status (completely stepping away from the project).

Contact the community team about changing to Emeritus status, or reducing your contributor level.

## Contact the MDN team

- For inquiries and feedback, please reach out to:
  - mdn-web-docs-community (at) mozilla (.com)
