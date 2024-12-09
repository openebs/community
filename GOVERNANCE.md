# OpenEBS Umbrella Project Governance
>
> [!Important]
> OpenEBS is an "umbrella" project,  composed as a federation of individual sub projects (repositories). The umbrella project, every sub project, repository/repo and file in the OpenEBS organization adopts and follows the same set of umbrella policies located in the OpenEBS Community repo. This is the Umbrella Project Governance policy.
<BR>

## Key references

Please familiarize yourself with our [Project Vision](./VISION.md) and [Contributing Guidelines](./CONTRIBUTING.md). Together with this Governance document, these provide useful info on what and who we are, and how we operate.

---
<BR>

The **OpenEBS project** is managed on a daily basis by a senior governance & leadership team, that currently consists of the following OpenEBS ```Maintainers``` and ```Special Maintainers```]: https://github.com/openebs/community/blob/HEAD/MAINTAINERS
<BR>

The list of Maintainers can also be found in the MAINTAINERS file.

## Maintainers, Contributors and Adopters

The OpenEBS project has five roles. All project members operate in one (or more) of these roles:
<BR>

| Level | Role | Responsibilities |
| :---  | :--- | :--- |
| 1     | **Maintainer** | Vote, Develop roadmap, contribution guidelines; Review, Approve/Reject, Merge, Manage repos. Maintainers are elected or removed by the current maintainers. A Maintainer has authority over the OpenEBS umbrella project: the organization and every project, sub-project and repo within the organization.|
| 2     | **Special**<BR>**Maintainer**| Have special expertise in a particular domain within the OpenEBS umbrella project. The domain may be a sub-project, repo or other responsibility as defined by the Maintainers. The maintainers grant a special maintainer a set of authorities and responsibilities for the domain. A special maintainer is expected to join maintainer and community meetings when required. A special maintainer has no responsibilities for the umbrella project, or projects outside their domain.|
| 3     | **Contributor** | Contribute code, test, document the project. A contributor’s authority applies to one or more sub projects. |
| 4     | **Adopter** | Use the OpenEBS product, with or without contributing to the project. An adopter has authority to raise issues, participate in discussions on sub projects within a public forum. |

<BR>

These roles are described in more detail below:

### Maintainer

Maintainers are an elected group that share responsibility in the OpenEBS project success. They make a long-term, dedicated commitment to improve and govern the project. Maintainers are expected to be responsive, available, and to make regular and substantial contributions.
Maintainers also perform the admin non-code-related Github tasks such as updating permissions, configuring integrations and other administrative tasks.
<BR>

Maintainers work for the OpenEBS community. A maintainer is someone the community can depend on and trust to make decisions in the best interest of the project. **Anyone can become a maintainer.**
<BR>

Maintainers have authority over all projects, sub projects and repos within the OpenEBS organization, with responsibility for:

* Project roadmap
* Reviewing, approving and denying contributions
* Maintaining coding, testing and documentation standards
* Providing support and community engagement
* Project management and governance
* Adding/removing maintainers, and special maintainers
* Activities that move the project towards graduation status

#### Contributor Ladder: How to become a maintainer

The process for becoming a maintainer:

1. You need to get involved with the OpenEBS project on GitHub, and demonstrate four qualities:

   * Participation. For three months or more. For example: participation in discussions, contributions, code or documentation reviews.
   * Collaboration. Demonstrate the ability to work with others, to take on new ideas and help others succeed.
   * Availability. Be available on Slack, GitHub, email so you’re helping move the project forward in a timely way.
   * Alignment with CNCF code of conduct and guiding principles

2. Email the OpenEBS maintainers (<openebs-team@googlegroups.com>) and let them know you’re interested in becoming a maintainer
3. The maintainers set up time to meet you, and after discussion will agree a process (typically this means a special maintainer assignment for a set period)
4. At the end of the process, the maintainers review your contribution. A maintainer will nominate you for voting-in.

#### Remaining a Maintainer

If a maintainer can no longer meet their commitments, they are expected to consult with the other maintainers and either take a sabbatical from maintainership, or resign as a maintainer. It is the responsibility of all maintainers to ensure the maintainer group operates with the same level of commitment. If a maintainer is not meeting their commitments, they may be voted-out by the maintainers.

#### Voting-in and voting-out maintainers

1. Maintainers make an announcement in their weekly meeting, and this is minuted
2. During this meeting, a maintainer nominates to add a new maintainer or remove an existing maintainer,
3. The nominator opens a PR in the OpenEBS Community Repo,
4. Maintainers vote via GitHub PR comments, with a 2 week deadline. Anyone in the community is welcome to comment. Community comments will be considered, but not counted towards the vote,
5. After two weeks, any maintainer who abstains from voting will not be counted towards the vote,
6. Decision is approved with a super-majority: 66% or more of maintainers who have voted within two weeks,
7. If 66% of all maintainers have approved within two weeks, the voting is closed early.

Changes to the maintainer list (from voting-in, voting-out or resignations) are recorded in the maintainer meeting weekly minutes, and reflected in the [MAINTAINERS](./MAINTAINERS) document. For maintainers voted-in, permissions are immediately added. For maintainers voted-out permissions are immediately removed.

### Special Maintainer

A Special Maintainer is appointed by the maintainers to recognize a contributor with expertise and authority in a specific domain. Special Maintainers are appointed to have elevated privilege, authority and specific responsibilities. The special maintainer role is part of the OpenEBS contributor ladder, and is the primary path from contributor to maintainer. Special maintainers are assigned or removed by the maintainers, by vote with 66% approval, and their role
and responsibilities are scoped. A person can have one or more Special Maintainer responsibilities

OpenEBS has appointed or may appoint special maintainers for following roles:

* CNCF Liaison. To be a primary point of contact between the project and CNCF
* Project manager. To keep track of tasks, and make sure maintainers, special maintainers and contributors deliver on time
* Sub-project maintainer. To own specific project (typically an engine), and to ensure coding standards, issue resolution, documentation, roadmap is in compliance for the sub-project
* Documentation manager. To oversee and help produce the techdocs and community documentation
* Test manager. To oversee and coordinate test coverage
* Community Manager.
* Special projects. Other projects that come up from time-to-time

Special maintainers are enabled to act independently. They do not have responsibilities within the umbrella project. They do not have voting rights over the umbrella project. They are expected to participate with the community, They are not expected to participate in maintainer meetings, unless requested.

Special Maintainers are listed in the [MAINTAINERS](./MAINTAINERS) document.

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

## Changes to this document

Changes to governance policy and any supporting documents must be agreed and approved by 66% of the Maintainers either by vote, or by review and approval of a PR on the document.
