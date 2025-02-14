# OpenEBS Umbrella Contributing Guidelines
>
> [!Important]
> OpenEBS is an `Umbrella Project` whose governance and policies are defined in the [community](https://github.com/openebs/community/) repository.<br>
>This CONTRIBUTING file is applicable to every sub-project, repository and file existing within the [OpenEBS GitHub organization](https://github.com/openebs/).

# Contributing to OpenEBS

We welcome contributions to OpenEBS! Thank you for taking the time to help improve the project. This guide outlines our approach to contributions and helps you get started.

## Code of Conduct

Please review our [Code of Conduct](CODE_OF_CONDUCT.md) before contributing. Adherence to these guidelines is expected from all community members.

## Topics

* [Reporting general issues](#reporting-general-issues)
* [Reporting security issues](#reporting-security-issues)
* [Code and documentation contributions](#code-and-documentation-contributions)
* [Review process](#review-process)
* [How to engage](#how-to-engage)
* [Final notes](#final-notes)

## Reporting general issues

We appreciate your feedback and encourage every user to become a contributor. To report an issue or suggest an improvement, please follow these steps:

1. Navigate to the [OpenEBS issue tracker](https://github.com/openebs/openebs/issues) and click on **New issue**.
2. Select the appropriate issue type and click **Get started**.
3. Fill in the issue title and details as prompted by the issue template.
4. Click **Submit new issue**.

We value **clear**, **detailed**, and **explicit** issue reports. Before creating a new issue, please search existing issues to avoid duplication. If your concern has already been raised, add your details in the comments.

Examples of issues include:
- Bug reports
- Feature requests
- Performance concerns
- Design proposals
- Requests for additional tests or documentation
- General questions

*Remember:* Always remove sensitive data (passwords, secret keys, network locations, private business data, etc.) from your issue report.

## Reporting security issues

We take security issues very seriously. If you discover a security vulnerability in OpenEBS, **do not** open a public issue or discuss it openly. Please refer to [Security Guidelines](./SECURITY.md).

## Code and Documentation Contributions

Contributions that improve OpenEBS code, tests, or documentation always welcome. If you see something that can be improved or fixed, please feel free to submit a pull request (PR). Some examples include:

* Fixing typos or documentation errors
* Resolving bugs or adding missing tests
* Refactoring code for clarity and efficiency
* Enhancing existing features or adding new ones
* Removing redundant code or clarifying implicit logic

Please follow Contribution to Developer docs [here](./contribute/CONTRIBUTING-TO-DEVELOPER-DOC.md).
To avoid duplicate work, please check the community discussions or existing issues before starting your work. Review our [PR guidelines](#pr-guidelines) below for additional details.

### Contribution Setup

Please follow the [Contribution Setup Guidelines](./contribute/contribution-setup.md).

### Branch Definition

We expect that contributions via pull requests target the `develop` branch unless otherwise noted. Additional branches (such as release candidates, release branches, and backport branches) may exist for testing and maintenance purposes. Please check any project-specific guidelines if you plan to contribute outside the `develop` branch.

### Sign your work

> [!Important]
> Our Organization enforces **```Developer Certificate of Origin```** (DCO) on all Pull Requests, as an additional safeguard for the OpenEBS project. This requires all **commit messages** to contain the ```Signed-off-by``` line, with an email address that matches the commit author name.
> - This is a [well established and widely used mechanism](https://github.com/apps/dco)
> - DCO ensures contributors have confirmed their right to license their contribution under the project's license.
> - Please read [developer-certificate-of-origin](./contribute/developer-certificate-of-origin) to understand what you are `consenting` to and `agreeing` to adhere to when you create a commit and a PR.
> - ALL PR's will automatically have their status set to `FAILED` if any commits in a Pull Request do not contain a valid `Signed-off-by` line.

You must certify that your commits and PR's are your own work and authorized by you by adding a line to every git commit message. Any PR with Commits that Do Not have DCO Signoff will not be accepted.

### PR Guidelines

* Ensure your local repository is up-to-date with the upstream repository.
* Limit your PR to a single focus (e.g., one bug fix or feature) to simplify review.
* Ensure the commits are signed as defined [above](#sign-your-work).
* Push your changes to your forked repository.
* Navigate to your repository on GitHub, click New pull request, and select the branch with your changes.
* Fill in the pull request template with detailed information about your changes.
* Submit the pull request and monitor the CI results.
* If additional commits are added later, ensure they remain focused on the issue at hand. It is often best to keep your pull request as a single logical change to simplify the review process.

### Review Process

Reviewing contributions is an essential part of maintaining a high-quality project. To review someone else’s pull request:

* Browse open pull requests at the OpenEBS pull requests page.
* Click Files changed to examine the changes.
* Use inline commenting (click the + sign next to a line) to suggest improvements or ask questions. Start a review if needed, then add comments.
* Once your review is complete, click Finish your review and then Submit review.
* Your constructive feedback helps maintain OpenEBS’s quality and guides contributors.

### How to Engage

Beyond code contributions, there are many ways to support OpenEBS:

* Answer questions and provide support on GitHub issues.
* Review and comment on pull requests.
* Discuss proposals and designs to improve clarity and robustness.
* Advocate for OpenEBS within the CNCF community and beyond.
* Write blog posts or share your experience with OpenEBS.
* Every contribution—big or small—helps improve the project and supports the community.

### Final Notes

OpenEBS is one of the many projects under the `CNCF umbrella`, and our project is part of a broader ecosystem of cloud-native technologies. We invite you to explore other OpenEBS repositories and engage with the community. Together, we can make OpenEBS even better!

Thank you for your contributions!
