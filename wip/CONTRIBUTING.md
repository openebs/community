# OpenEBS Contributing Guidelines 
> [!Important]
>This document is: OpenEBS Contributing Guidelines. OpenEBS is an umbrella project,  composed as a federation of individual sub projects (repositories). This document applies to both the umbrella project and to every sub project in the OpenEBS organization.
<BR>

There are many ways you can contribute to OpenEBS:
<BR>

## Ask a question
If you have questions about using OpenEBS, please use the OpenEBS Kubernetes slack channel, it is open for anyone to ask a question:
<BR>
>:arrow_forward:[OpenEBS Kubernetes Slack channel](https://kubernetes.slack.com/messages/openebs/)
## Report a product issue

If you have a problem using OpenEBS, first check the [troubleshooting guide](https://openebs.io/docs/troubleshooting), you can also ask a question in the OpenEBS Kubernetes Slack channel.

If you have an issue not solved by the troubleshooting guide or by asking a question in Slack, first check the GitHub issue list to see if the issue is already recorded, then add a New Issue. 

We use a centralized GitHub issue tracker for all product issues:
<BR>
>:arrow_forward:[OpenEBS Product Issues](https://github.com/openebs/openebs/issues)
<BR>
When raising issues, please specify the following:



* Summary of the issue
* Expected result and the observed result
* Errors and log messages
* Setup details, and steps for reproducing the issue, so a reviewer can easily replicate the issue, and confirm the fix


## Report a documentation issue

We use the same GitHub issue tracker for documentation issues, with a label for documentation:

► [OpenEBS Documentation Issues](https://github.com/openebs/openebs/labels/documentation%2Fdevel)

Issues are triaged and prioritized in the regular community meeting


## Report a security issue or vulnerability

Because of the sensitive nature of security issues (reporting a security issue also alerts bad-actors of the security issue), we ask you report these by emailing the umbrella project maintainers

► [Email security issue to OpenEBS maintainers](mailto:cncf-openebs-maintainers@lists.cncf.io)

After addressing any security issue, they will be discussed in the regular community meeting


## Contribute to Source Code and Bug Fixes

Provide PRs with appropriate tags for bug fixes to the source code. For a list of tags that could be used, see [this](https://github.com/openebs/openebs/blob/main/contribute/labels-of-issues.md).



* For contributing to K8s demo, please refer to this [document](https://github.com/openebs/openebs/blob/main/contribute/CONTRIBUTING-TO-K8S-DEMO.md).
    * For checking out how OpenEBS works with K8s, refer to this [document](https://github.com/openebs/openebs/blob/main/k8s/README.md)
* For contributing to Kubernetes OpenEBS Provisioner, please refer to this [document](https://github.com/openebs/openebs/blob/main/contribute/CONTRIBUTING-TO-KUBERNETES-OPENEBS-PROVISIONER.md).

Refer to this [document](https://github.com/openebs/openebs/blob/main/contribute/design/code-structuring.md) for more information on code structuring and guidelines to follow on the same. You can discuss contributions in our OpenEBS developer Kubernetes Slack Channel:

► [OpenEBS DEV Kubernetes Slack Channel](https://kubernetes.slack.com/messages/openebs-dev/)


## Solve Existing Issues

Head over to [issues](https://github.com/openebs/openebs/issues) to find issues where help is needed from contributors. See our [list of labels guide](https://github.com/openebs/openebs/blob/main/contribute/labels-of-issues.md) to help you find issues that you can solve faster.

A person looking to contribute can take up an issue by claiming it as a comment/assign their GitHub ID to it. In case there is no PR or update in progress for a week on the said issue, then the issue reopens for anyone to take up again. We need to consider high priority issues/regressions where response time must be a day or so. You can discuss the issue in our OpenEBS developer Kubernetes Slack Channel:

► [OpenEBS DEV Kubernetes Slack Channel](https://kubernetes.slack.com/messages/openebs-dev/)


## Sponsor a new feature or enhancement

New enhancements are referred to as OpenEBS Enhancement Proposals (OEPs). Anyone can sponsor a new OEP. Here is the process:



1. Sponsor creates and authors an OEP in the Community Repository Discussion forum (all OEPs entered into the community repo)
2. This auto-generates a GitHub issue # that is tracked against the Community repo
3. The Issue # = the OEP #
4. In the bi-weekly (fortnightly) community meeting, we review OEPs
5. The sponsor presents the OEP
6. The community votes on the OEP, maintainers have binding votes.
7. Approved OEPS's are moved (or copied) into the appropriate repository and are tracked against the OEP Community Roadmap
8. A pull request (PR) is only created after this approval. Once the PR is created, the existence of the PR means engineering work is approved and the OEP is scheduled for coding. 


---


## Sign your work

We use the Developer Certificate of Origin (DCO) as an additional safeguard for the OpenEBS project. This is a well established and widely used mechanism to assure contributors have confirmed their right to license their contribution under the project's license. Please read [developer-certificate-of-origin](https://github.com/openebs/openebs/blob/main/contribute/developer-certificate-of-origin).

Please certify it by just adding a line to every git commit message. Any PR with Commits which does not have DCO Signoff will not be accepted:

 Signed-off-by: Random J Developer &lt;random@developer.example.org>

or use the command git commit -s -m "commit message comes here" to sign-off on your commits.

Use your real name (sorry, no pseudonyms or anonymous contributions). If you set your user.name and user.email git configs, you can sign your commit automatically with git commit -s. You can also use git [aliases](https://git-scm.com/book/en/v2/Git-Basics-Git-Aliases) like git config --global alias.ci 'commit -s'. Now you can commit with git ci and the commit will be signed.


---


## Regular Community Meeting

open EBS hosts a bi-weekly (fortnightly) community meeting on Tuesday 7:00an Americas/Los Angeles time, using the [CNCF's community event platform](https://community.cncf.io/openebs-community/). Please register for the event, prior to the meeting. You'd have to register for the meeting before the actual meeting time.

► [Add agenda items for the next meeting](https://hackmd.io/tRmnyg9AQPShxFAXOyFpSA?edit)

► [Review minutes from previous meetings](https://hackmd.io/tRmnyg9AQPShxFAXOyFpSA?edit)


## Other ways to keep in touch


### Email

You can email the maintainers at any time:

► [Email OpenEBS maintainers](mailto:cncf-openebs-maintainers@lists.cncf.io)


### Mailing List

OpenEBS announces new features and enhancements to an CNCF email group

► [CNCF OpenEBS announcements](https://lists.cncf.io/g/cncf-openebs-announcements)


### Social Media

► [Twitter/X OpenEBS page](https://twitter.com/openebs)

► [LinkedIn OpenEBS page](https://www.linkedin.com/company/openebs)
