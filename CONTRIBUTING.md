# OpenEBS Umbrella Contributing Guidelines
> [!Important]
> OpenEBS is an "umbrella" project,  composed as a federation of individual sub projects (repositories). The umbrella project, every sub project, repository/repo and file in the OpenEBS organization adopts and follows the same set of umbrella policies in the OpenEBS Community repo. This is the Umbrella Contributing Guidelines.
<BR>

There are many exciting ways you can contribute to OpenEBS ❤️ <BR>
- We are a large GitHub project that consists of many active members operating globally, across all time zones, 24 x 7 x 365.
- There are many different methods, processes, forums, and project tools to use when contributing.
- This means that contributing can be a little scary at times (like many large CNCF Open source GitHub hosted projects). <BR>
- If you are unsure or afraid of anything, just ask via Slack, Discussion, or Issue. // It’s simple.

This document will help guide [your workflow](#a-good-contributor-workflow) and experience to provide you with the best and most efficient interaction possible.


<BR>


## Ask a question :question:

| [<img src="/images/slack_icon_small.png" width="100">](https://kubernetes.slack.com/messages/openebs)  | **Try our Slack channel First** <BR>If you have questions about using OpenEBS, please use the CNCF Kubernetes **OpenEBS slack channel**, it is open for [anyone to ask a question](https://kubernetes.slack.com/messages/openebs/) <BR> |
| :---         | :---      |

<BR>


# Issues :bangbang:
```Issues``` are a standard way of working and contributing to GitHub projects. GitHub Issues are the **2nd most** common way [after Slack](https://kubernetes.slack.com/messages/openebs) that users interact and contribute to the project. Working with Issues requires you to make a few simple decisions.
- Is my issue more of a discussion topic?
- Does my Issue relate to a Product?
- Is it an issue that spans Horizontally across all products?
- Is my issue related to technology, bugs, product, code?
- Is my issue more relevant to roadmap, strategy, docs (not technology, bugs, product, code)?
```ruby
After this, you're ready to create an Issue and know where to create it.
```

<BR>

> [!NOTE]
> Issues come in 3 basic flavors
> 1. ```Organizational``` issues that aren't specifically related to individual products, technology, or code
>    - For this type of issue, [create your issue here](https://github.com/openebs/openebs/issues)
>    - You might also consider creating a discussion in the [parent org discussions area](https://github.com/orgs/openebs/discussions)
> 3. Issues that span ```multiple products```
>    - For this type of issue, [create your issue here](https://github.com/openebs/openebs/issues)
> 4. Issues focused on ```1 specific Product```
>    - For this type of issue, create your issue in the Issue tab of the correct project/product repo
>    - View the list of our [product components here](./CONTRIBUTING.md#multiple-products)
<BR>

### Reporting a product issue


If you have a problem using OpenEBS, first check the [troubleshooting guide](https://openebs.io/docs/troubleshooting), you can also ask a question in the CNCF Kubernetes **OpenEBS slack channel**.

> [!NOTE]
> - Our support and engineering teams ```primarily``` focus their support on the **OpenEBS STANDARD** (OSS) [parent project](https://github.com/openebs). <BR>
> - Questions & issues relating to the [Legacy Archived, Deprecated & Migrated OpenEBS projects](https://github.com/openebs-archive), repos, code & dependencies are **not the focus** of the parent OSS project; and may be provided on a ```best effort``` basis by the team. <BR>
> - The OpenEBS slack community provides most of the support for the **Legacy** ```Archived```, ```Deprecated``` & ```Migrated``` OpenEBS projects.
> - please **```Do Not```** post [```Deprecated & Archived project```](https://github.com/openebs-archive) Discussions, Issues or PR's into the **OpenEBS STANDARD** (OSS) parent project.


> If you have an issue not solved by the troubleshooting guide or by asking a question in Slack, first check the GitHub issue list to see if the issue is already recorded, then add a new Issue in the correct repo issue management section.

<BR>

### Multiple products
Our project spans multiple product components. Unfortunately, we ```don't``` use a single centralized GitHub issue tracker for all product  issues. We like to group product issues tightly into their specific product Issue trackers. (Please try to do this). Currently OpenEBS Unifies 5 main Storage engines...

| ID  | Data-Engines       | Where to create your issues                            |
| :---: | :---             | :---                                                   |
|     | ```Replicated PV```          | ```Replicated storage and data volumes```     |
|  1  | [Replicated PV Mayastor](https://github.com/openebs/mayastor)      | [Create your Issues here](https://github.com/openebs/mayastor/issues)   |
| &nbsp;                        |    |
|     | ```Local PV```          | ```Non-replicated node local storage and volumes```   |                                                            |
|  2. |  [LocalPV-HostPath](https://github.com/openebs/dynamic-localpv-provisioner)     | [Create your Issues here](https://github.com/openebs/dynamic-localpv-provisioner/issues) |
|  3. |  [LocalPV-ZFS](https://github.com/openebs/zfs-localpv)      | [Create your Issues here](https://github.com/openebs/zfs-localpv/issues) |
|  4. |  [LocalPV-LVM](https://github.com/openebs/lvm-localpv)      | [Create your Issues here](https://github.com/openebs/lvm-localpv/issues) |
|  5. |  [LocalPV-Raw-device-File](https://github.com/openebs/rawfile-localpv) | [Create your Issues here](https://github.com/openebs/rawfile-localpv/issues) |
<BR>

<BR>

### When creating a new issue, please use this simple template:
* Summary of the issue
* Expected result and the observed result
* Errors and log messages
* Setup details, and steps for reproducing the issue, so a reviewer can easily replicate the issue, and confirm the fix

---

## Report a documentation issue
We use the same GitHub issue tracker for documentation issues, with a label for documentation:
<BR>
:arrow_forward: [OpenEBS Documentation Issues](https://github.com/openebs/openebs/labels/documentation%2Fdevel)
<BR>
- Issues are triaged and prioritized in the regular community meeting
<BR>

---

## Report a security issue or vulnerability

> [!IMPORTANT]
> Because of the sensitive nature of security issues (reporting a security issue also alerts bad-actors of the security issue), we ask you report these by emailing the umbrella project maintainers. <BR>
> :arrow_forward: &nbsp; [Email security issue to OpenEBS maintainers](mailto:cncf-openebs-maintainers@lists.cncf.io) <BR>
> <BR>
> After addressing any security issue, they will be discussed in the regular community meeting <br>
<BR>

## Contribute to Source Code and Bug Fixes

We encourage users to engage in and contribute code. Doing this a complex and requires following the GitHub methodology that we subscribe to as a member of CNCF. In a nutshell, the GitHub methodology is: <BR>
- Discussion/Proposal :fast_forward: Create Issue :fast_forward: PR draft + code :fast_forward: PR Review(s) + code changes :arrows_counterclockwise: PR approve :fast_forward: DCO Sign-off :twisted_rightwards_arrows: Merge <BR>
<BR>

> - When creating your PR, please use appropriate tags to identify your source code. For a list of tags that could be used, see [this](https://github.com/openebs/openebs/blob/main/contribute/labels-of-issues.md).
> - For contributing to K8s demo, please refer to this [document](https://github.com/openebs/openebs/blob/main/contribute/CONTRIBUTING-TO-K8S-DEMO.md).
> - For understanding how OpenEBS works with K8s, refer to this [document](https://github.com/openebs/openebs/blob/main/k8s/README.md)
> - For contributing to K8s OpenEBS Provisioner, refer to this [document](https://github.com/openebs/openebs/blob/main/contribute/CONTRIBUTING-TO-KUBERNETES-OPENEBS-PROVISIONER.md).
> - For code structuring and guidelines, refer to this [document](https://github.com/openebs/openebs/blob/main/contribute/design/code-structuring.md)
> - Feel free to discuss developer topics in our [OpenEBS DEV Kubernetes Slack Channel](https://kubernetes.slack.com/messages/openebs-dev/)
<BR>

<BR>

## Solve Existing Issues
Head over to [Parent org issues](https://github.com/openebs/openebs/issues) to find issues where help is needed from contributors, or check the issues section of the [product component](./CONTRIBUTING.md#multiple-products) that you are interested in.

See our [list of labels guide](https://github.com/openebs/openebs/blob/main/contribute/labels-of-issues.md) to help you find issues that you can solve faster.

A person looking to contribute can take up an issue by claiming it as a comment/assign their GitHub ID to it. In case there is no PR or update in progress for a week on the said issue, then the issue reopens for anyone to take up again. We need to consider high priority issues/regressions where response time must be a day or so. You can discuss the issue in our OpenEBS developer Kubernetes Slack Channel:
<BR>
:arrow_forward: [OpenEBS DEV Kubernetes Slack Channel](https://kubernetes.slack.com/messages/openebs-dev/)
<BR>

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


### Sign your work
<BR>

> [!Important]
> Our Organization enforces **```Developer Certificate of Origin```** (DCO) on all on Pull Requests, as an additional safeguard for the OpenEBS project. This requires all **commit messages** to contain the ```Signed-off-by``` line, with an email address that matches the  commit author name.

> - This is a [well established and widely used mechanism](https://github.com/apps/dco) <BR>
> - DCO assure's contributors have confirmed their right to license their contribution under the project's license. <BR>
> - Please read [developer-certificate-of-origin](https://github.com/openebs/openebs/blob/main/contribute/developer-certificate-of-origin) ```release statement``` to understand what you are **```consenting```** to and **```agreeing```** to adhere to when you create a commit and a PR. <BR>
> - ALL PR's will automatically have their status set to to **```FAILED```** if any commits in a Pull Request do not contain a valid ```Signed-off-by``` line.



You must certify that your commits and PR's are your own work and authorized by you; by adding a line to every git commit message. Any PR with Commits that Do Not have DCO Signoff will not be accepted:<BR>
<BR>

### Examples of how to DCO Sign-off your work...<BR>
<BR>

> Example of manual DCO signoff commit signature message: <BR>
> ```Signed-off-by: Random J Developer <random@developer.example.org>```
>
> Example of automated git cli command: <BR>
> ```git commit -s -m "Sign off details and message. Does not include DCO signature line"```
> ```ruby
> NOTE: the cli -s flag will auto add your DCO sign-off signature as a extra line in your commit message
> if you have setup you git Global config correctly.
> ```
> :information_source: **```INFO```:** <BR>
> :no_entry_sign: When using the GitHub Web App, you cannot auto DCO sign-off your commits. Your DCO signature line must be manually added each time, in each commit message. This is by design and enforced by the GitHub WebApp. <BR>
> :white_check_mark: When using GitHub Desktop App, you can generate automatic DCO sign-off commits if your underlying git cli config is setup correctly. <BR>
<BR>

The generally accepted GitHub DCO policy requires that all committing users must provide their ```real name``` in their DCO signature message (sorry, no pseudonyms or anonymous contributions). <BR>
- If you set your ```user.name``` and ```user.email``` git configs, you can DCO sign your commits automatically with ```git commit -s```. <BR>
- You can also use git [aliases](https://git-scm.com/book/en/v2/Git-Basics-Git-Aliases) like: ``` git config --global alias.ci 'commit -s' ```. Now you can commit with git ci and the commit will be signed. <BR>
<BR>

---



## Regular Community Meeting

open EBS hosts a bi-weekly (fortnightly) community meeting on Tuesday 7:00an Americas/Los Angeles time, using the [CNCF's community event platform](https://community.cncf.io/openebs-community/). Please register for the event, prior to the meeting. You'd have to register for the meeting before the actual meeting time.
<BR>
:arrow_forward: [Add agenda items for the next meeting](https://hackmd.io/tRmnyg9AQPShxFAXOyFpSA?edit)
<BR>
:arrow_forward: [Review minutes from previous meetings](https://hackmd.io/tRmnyg9AQPShxFAXOyFpSA?edit)
<BR>

## Other ways to keep in touch

### Email

You can email the maintainers at any time:
<BR>
:arrow_forward: [Email OpenEBS maintainers](mailto:cncf-openebs-maintainers@lists.cncf.io)

### Mailing List

OpenEBS announces new features and enhancements to an CNCF email group
<BR>
:arrow_forward: [CNCF OpenEBS announcements](https://lists.cncf.io/g/cncf-openebs-announcements)

### Social Media
Social media links
<BR>
:arrow_forward: [TwitterX OpenEBS page](https://twitter.com/openebs/)
<BR>
:arrow_forward: [LinkedIn OpenEBS page](https://www.linkedin.com/company/openebs/)

<BR>

---

## A good contributor workflow
```ruby
The following table is a guide to help you decide which channel, method and mechanism to use when contributing.
- In most cases, consider starting at the top (post a Slack channel question)
- and then work your way down, Discussion, Issue, Projects
- Ending at a Pull Request; the most complex community contribution/interaction type.
```

| Priority | Type | Description |
| :---: | :--- | :---        |
| 1. | Global Slack | CNCF provides the **OpenEBS project** with a [```global Slack support Channel```](https://kubernetes.slack.com/messages/openebs/). All users and community members are welcome to  engage all project members via the Slack channel. |
| 2. | [Org Discussions](https://github.com/orgs/openebs/discussions) | Our GitHub Discussions are enabled at the **Parent OpenEBS** ```Org level``` and aggregate all project/repo discussions into ONE Unified Umbrella scope for the best community discussion experience. Individual projects/repos ```Do Not``` have repos level GitHub discussions enabled.  |
| 3. | [Org Issues](https://github.com/openebs/openebs/issues) | Non-Product Issues not related to technology, bugs, or product code are managed in the top-level [```Org repo```](https://github.com/openebs/openebs). You can create/submit ORG level issues as per the normal GitHub methodology & rules. Consider doing this for issues that are ```horizontal``` across [all projects/repos/products](https://github.com/openebs/openebs/issues). |
| 4. | Product Issues   | Product Issues are managed for each ```individual repo```. You can create/submit issues as per the normal GitHub methodology & rules. Please choose carefully if you are engaging the team in a [```General Discussion```](https://github.com/orgs/openebs/discussions) or need help with a very specific **Product ```Issue```**. This will help you get the best community experience. Please create your interactions in the **correct** GitHub forum/tool. |
| 5 | Our Projects | We manage some major initiatives via the **GitHub Projects tool**. Users and community members are welcome to contribute, comment and participate in Public projects. Projects are enabled and managed on a ```per-repo basis```. |
| 6. | Repo PR's | You may engage and contribute via the standard **GitHub PR** ```(Pull Request)``` methodology. PR's are low-level repo/product/component focused engineering process used to manage **```low-level changes to code```**. For the best community experience, ```Do Not``` create PR's for **Discussions**, **Issues** or **support tickets**. (such items may be migrated to the appropriate forum/tool and could become stale and/or be closed without action/comment. |


