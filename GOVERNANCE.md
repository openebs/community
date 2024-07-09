# OpenEBS Umbrella Project Governance
> [!Important]
> OpenEBS is an "umbrella" project,  composed as a federation of individual sub projects (repositories). The umbrella project, every sub project, repository/repo and file in the OpenEBS organization adopts and follows the same set of umbrella policies located in the OpenEBS Community repo. This is the Umbrella Project Governance policy.
<BR>

## Key references:
Please familiarize yourself with our [Project Vision](./VISION.md) and [Contributing Guidelines](./CONTRIBUTING.md). Together with this Governance document, these provide useful info on what and who we are, and how we operate. 

---
<BR>

The **OpenEBS project** is managed on a daily basis by a senior governance & leadership team, that consists of the following OpenEBS ```Admins``` and ```Maintainers.``` Currently the team is...
> |   |   |   |    |
> | :--- | :--- | :--- | :--- |
> | [Vishnu Attur](https://www.linkedin.com/in/vishnu-attur-5309a333/ "Bengaluru, Karnataka, India (GMT+5:30) Timezone")| :octocat: <kbd>**[@avishnu](https://github.com/avishnu "Vishnu Govind Attur")**</kbd> | ![](/images/flags/de_je/in.png) | <kbd>**Admin**</kbd>, ```Maintainer``` |
> | [Abhinandan Purkait](https://www.linkedin.com/in/abhinandan-purkait/ "Bengaluru, Karnataka, India (GMT+5:30) Timezone") | :sunglasses: <kbd>**[@Abhinandan-Purkait](https://github.com/Abhinandan-Purkait "Abhinandan Purkait")**</kbd> | ![](/images/flags/de_je/in.png) | ```Maintainer``` |
> | [Niladri Halder](https://www.linkedin.com/in/niladrih/ "Bengaluru, Karnataka, India (GMT+5:30) Timezone") | :rocket: <kbd>**[@niladrih](https://github.com/niladrih "Niladrih Halder")**</kbd> | ![](/images/flags/de_je/in.png) | ```Maintainer``` |
> | [Ed Robinson](https://www.linkedin.com/in/edrob/ "San Francisco, USA (GMT-7) Timezone") | :dog: <kbd>**[@edrob999](https://github.com/edrob999 "Ed Robinson")**</kbd> | ![](/images/flags/ni_tn/nz.png) | <kbd>**CNCF Primary Liaison**</kbd>,```Special Maintainer``` |
> | [Tiago Castro](https://www.linkedin.com/in/tiago-castro-3311453a/ "London, UK (GMT+1) Timezone") | :zap: <kbd>**[@tiagolobocastro](https://github.com/tiagolobocastro "Tiago Castro")**</kbd> | ![](/images/flags/ni_tn/pt.png) &nbsp; ![](/images/flags/de_je/gb.png) | <kbd>**Admin**</kbd>, ```Maintainer``` |
> | [David Brace](https://www.linkedin.com/in/dbrace/ "San Francisco, USA (GMT-7) Timezone") | :star: <kbd>**[@orville-wright](https://github.com/orville-wright "Dave Brace")**</kbd> | ![](/images/flags/ni_tn/nz.png) &nbsp; ![](/images/flags/de_je/hu.png) &nbsp; ![](/images/flags/to_zw/us.png) | <kbd>**Admin**</kbd>, ```Maintainer``` |

<BR>

## Admin, Maintainers, Contributors and Adopters

The OpenEBS project has five core roles. All project members operate in one (or more) of these roles:
<BR>

| Level | Role | Responsibilities |
| :---  | :--- | :--- |
| 1     | **Admin** | Administer organization in GitHub. Add/subtract admins, invite members, manage org and repo integrations. |
| 2     | **Maintainer** | Vote, Develop roadmap, contribution guidelines; Review, Approve/Reject, Merge, Manage repos. Maintainers are elected or removed by the current maintainers. A maintainer has authority over the OpenEBS umbrella project: the organization and every proejct, sub-project and repo within the organization.|
| 3     | **Special**<BR>**Maintainer**| Have special expertize in a particular domain. The domain may be a project, sub-project, repo or other responsibility as defined by the Maintainers. The maintainers grant a special maintainer a set of authorities and responsibilities for the domain. A special maintainer is expected to join maintainer and community meetings when required. A special maintainer has no responsibilities for the umbrella project, or projects outside their domain.|
| 4     | **Contributor** | Contribute code, test, document the project. A contributor’s authority applies to one or more sub projects. |
| 5     | **Adopters** | Use the OpenEBS product, with or without contributing to the project. An adopter has authority to raise issues, participate in discussions on sub projects within a public forum. |
<BR>

These roles are described in more detail below:

### Admin
Admins perform the non-code-related Github tasks such as updating permissions, configuring integrations and other administrative tasks. Admins are informally appointed and removed by the maintainers, CNCF or other Admins.
<BR>

### Maintainer
Maintainers are an elected group that share responsibility in the OpenEBS project success. They make a long-term, full-time (or mostly full-time) investment to improve and govern the project. Maintainers spend their time doing what needs to be done. Maintainers of the project are people the community can depend on and trust to make decisions in the best interest of the project. **Anyone can become a maintainer.**

Maintainers have authority over all projects, sub projects and repos within the OpenEBS organization, with responsibility for:

* Project roadmap
* Reviewing, approving and denying contributions
* Maintaining coding, testing and documentation standards
* Providing support and community engagement
* Project management and governance
* Activities that move the project towards graduation status

#### Becoming a Maintainer
To become a Maintainer you need to demonstrate committment to the OpenEBS project. A typical committment is:

* Participate in discussions, contributions, code and documentation reviews for three months or more
* Perform reviews of and contribute to non-trivial pull requests
* Demonstrate alignment with the project vision and roadmap
* Ability to write quality code and/or documentation
* Ability to collaborate with the team
* Understanding of how the team works (policies, processes for testing and code review, etc)
* Understanding of the project's code base and coding and documentation style

The maintainers work full-time (or mostly full-time) in the project. Every new maintainer is expected to also make the same time committment, to have availability and repsonsiveness when working with other maintainers and be responsive to community issues.

Process for assigning a new maintainer:
1. Candidate is nominated by an existing maintainer at a weekly maintainers meeting
2. The candidate meets with the maintainers
3. Maintainers vote (in private), the maintainer is appointed if 50% or more of the organization maintainers approve of the appointment
4. If approved, the approval is recorded in the maintainer meeting minutes, the new maintainer will be granted necessary GitHub rights, and invited to the private maintainer mailing list and meetings.

#### Remaining a Maintainer
Maintainers are expected to operate with a full-time (or mostly full-time) committment, availability and participation in the project.
If a maintainer can no longer meet these committments, they are expected to consult with the other maintainers and either take a sabbatical from maintainership, or resign as a maintainer. It is the responsibility of all maintainers to ensure the maintainer group operates with the same level of committment.

#### Removing a Maintainer
Maintainers may resign at any time. A maintainer may request a time-bound sabbatical (during which they a released from all duties and voting rights). 
The maintainers may also vote to remove a maintainer, if they feel the person will not be able to continue fulfilling their project duties.

The process for removing a maintainer:
1. Maintainers attempt to contact the maintainer privately. Depending on the circumstances, the maintainer may be requested to re-assume their project committment, requested to resign, or advised a vote will be made to remove them from the project
2. If the maintainer chooses to resign, a record is made in the maintainer meeting minutes
3. The remaining maintainers may choose to vote to remove the maintainer. The action is approved if 66% or more of the remaining maintainers vote to remove the maintainer. A record of the vote is made in the maintainer meeting minutes
4. When a maintainer is removed: GitHub admin rights, permissions and mailing list membership are also immediately removed.

### Special Maintainer
Special Maintainers have expertise and authority in a specific domain. Special maintainers are assigned or removed by the maintainers, by vote with 50% approval, and given scoped authority for their domain. For example:
* Special maintainer for one or more sub projects (typically where the individual has specialist knowledge for a discrete area of the project), the special maintainer shares maintainership of the project with the maintainers
* Special maintainer for a task or responsibility

Special maintainers are enabled to act indepedently. The do not have responsibilities within the umbrella project. They do not have voting rights over the umbrella project. They are expected to participate with the community, They are not expected to participate in maintainer meetings, unless requested.

Special Maintainers are listed in the SPECIAL_MAINTAINERS document.

### Contributor
OpenEBS is a very welcoming community and is eager to onboard and help anyone from the open source community to contribute to the project. To facilitate onboarding of the community members, OpenEBS contributors participate in Hacktoberfest events and are responsive on the slack, community meetings and github.

Any individual with intent to contribute to open source in general or fix a specific issue they are having the OpenEBS project can contribute. If anyone is looking for ideas for contributing, the open issue backlog maintained under the OpenEBS GitHub projects is a great place to start.

A maintainer may assign a regular contributor write access to the GitHub project to allow them to directly request other organization members as reviewers for their PRs and to help them being added as reviewers for contributions coming from other contributors or OpenEBS organization members. A maintainer may also revoke the write access to the GitHub project.


### Adopter
OpenEBS welcomes people who simply want to Adopt the OpenEBS product, and welcomes them as part of our community. Adopters may use the OpenEBS product as they wish, contribute ideas or code, or create a fork of the code.

## Adding and Removing Sub Projects
The maintainers may add or remove sub projects or repositories. The maintainers take a conservative policy towards changing the sub projects: a new sub project must have a long term purpose that is distinct from existing sub projects; removed sub projects must be demonstrated to have outlived their purpose or have become unmaintainable.

When a sub project is removed, it is moved as-is to the OpenEBS-archive organization, along-with the related repositories.


## How are decisions made?
[See CONTRIBUTING guidelines and rules doc](./CONTRIBUTING.md)

## Conflict Resolution
If you have a technical dispute that you feel has reached an impasse with a subset of the community, any contributor may open an issue, specifically calling for a resolution vote of the current maintainers to resolve the dispute. The same voting quorums required (2/3) for removing maintainers will apply to conflict resolution.

## Modifying this document
Changes to this policy and any supporting documents must be agreed and approved by 66% of the Maintainers either by vote, or by review and approval of a PR on the document.
