
# OpenEBS Project Governance
> [!Important]
> OpenEBS is an "umbrella" project,  composed as a federation of individual sub projects (repositories). The umbrella project, every sub project, repository/repo and file in the OpenEBS organization adopts and follows the same set of umbrella policies found in the OpenEBS Community repo. This is the Umbrella Project Governance policy.
<BR>

## Key references:
Please familiarize yourself with these documents, they outline what-openEBS-is and how-we-operate:
> [Project Vision](./VISION.md) &nbsp; | &nbsp; [Values: Mission Statement and Scope](https://github.com/openebs/community/blob/develop/VISION.md#vision-mission-statement-and-scope) &nbsp; | &nbsp; [Restraints](./VISION.md#restraints) &nbsp; | &nbsp; [Contributing: ](./CONTRIBUTING.md)
---
<BR>

The **OpenEBS project** is managed on a daily basis by a senior governance & leadership team, that is consists of the following OpenEBS ```Admins```, ```Maintainers``` and ```Senior leaders```. Currently the team is...
> |   |   |   |    |
> | :--- | :--- | :--- | :--- |
> | [Vishnu Attur](https://www.linkedin.com/in/vishnu-attur-5309a333/ "Bengaluru, Karnataka, India (GMT+5:30) Timezone")| :octocat: <kbd>**[@avishnu](https://github.com/avishnu "Vishnu Govind Attur")**</kbd> | ![](/images/flags/de_je/in.png) | <kbd>**Admin**</kbd>, ```Maintainer``` |
> | [Abhinandan Purkait](https://www.linkedin.com/in/abhinandan-purkait/ "Bengaluru, Karnataka, India (GMT+5:30) Timezone") | :sunglasses: <kbd>**[@Abhinandan-Purkait](https://github.com/Abhinandan-Purkait "Abhinandan Purkait")**</kbd> | ![](/images/flags/de_je/in.png) | ```Maintainer``` |
> | [Niladri Halder](https://www.linkedin.com/in/niladrih/ "Bengaluru, Karnataka, India (GMT+5:30) Timezone") | :rocket: <kbd>**[@niladrih](https://github.com/niladrih "Niladrih Halder")**</kbd> | ![](/images/flags/de_je/in.png) | ```Maintainer``` |
> | [Ed Robinson](https://www.linkedin.com/in/edrob/ "San Francisco, USA (GMT-7) Timezone") | :dog: <kbd>**[@edrob999](https://github.com/edrob999 "Ed Robinson")**</kbd> | ![](/images/flags/ni_tn/nz.png) | <kbd>**CNCF Primary Liaison**</kbd> |
> | [Tiago Castro](https://www.linkedin.com/in/tiago-castro-3311453a/ "London, UK (GMT+1) Timezone") | :zap: <kbd>**[@tiagolobocastro](https://github.com/tiagolobocastro "Tiago Castro")**</kbd> | ![](/images/flags/ni_tn/pt.png) &nbsp; ![](/images/flags/de_je/gb.png) | <kbd>**Admin**</kbd>, ```Maintainer``` |
> | [David Brace](https://www.linkedin.com/in/dbrace/ "San Francisco, USA (GMT-7) Timezone") | :star: <kbd>**[@orville-wright](https://github.com/orville-wright "Dave Brace")**</kbd> | ![](/images/flags/ni_tn/nz.png) &nbsp; ![](/images/flags/de_je/hu.png) &nbsp; ![](/images/flags/to_zw/us.png) | <kbd>**Admin**</kbd>, ```Maintainer``` |

<BR>

## Org Admin, Maintainers, Contributors and Adopters

The OpenEBS project has four core roles. All project functions are/must fit into (and are goverened by hese roles:<BR>

| Level | Member type | Example description, scope and role |
| :---  | :--- | :--- |
| 1     | **Org Admin** | GitHub organization administration, add/subtract admins, invite members, org and repo integrations. |
| 2     | **Maintainers** | Roadmap, contribution guidelines, Review, Approve/Reject, Merge, Manage repos. Maintainers are elected or removed by the current maintainers, appointed or removed by the steering committee. A maintainer’s authority applies to the OpenEBS organization and every sub-project in the organization; unless they have been appointed as a [special maintainer](#special-projects-and-special-maintainers) |
| 3     | **Contributors:** | Contribute code, testing, documentation to the project. A contributor’s authority applies to one or more sub projects. |
| 4     | **Adopters:** | Use the OpenEBS product without contributing to the project. An adopter has  authority to raise issues, participate in discussions on sub projects with a public forum. |

<BR>


These roles are described in more detail below:



These roles are described in more detail below:

### Steering Committee
The steering committee is in charge of setting the OpenEBS project operating procedures:
* [Project Vision](./VISION), mission statement and scope, restraints conformance guidelines as recorded in the OpenEBS Vision document
* [Product Governance](./GOVERNANCE) as recorded in this document 
* Assigning or removing maintainers

The steering committee is composed of one or more representatives from organizations with significant investment in the OpenEBS project (eligible organizations). Eligible organizations are:

* [DataCore Software (DataCore)](https://datacore.com)
* [Cloud Native Computing Foundation (CNCF)](https://cncf.io)

An eligible organization may assign one member to the Steering committee. The steering committee meets as needed, and may vote to assign or remove other members or to make changes to the operating procedures. Unless otherwise agreed by the Steering Committee, a vote is carried with a ⅔ majority of votes in favor. Voting is in private, with decisions recorded in “Appendix 1: Steering Committee Members and Decisions” section of this document.

If the Steering Committee remains deadlocked on a vote, they agree to enter mediation with a mutually agreed mediation authority, and abide by the mediator’s decision.

### Maintainers
Maintainers are an elected or assigned group that share responsibility in the OpenEBS project success. They have made a long-term, recurring time investment to improve the project, and spend their time doing what needs to be done, not necessarily what is the most interesting or fun. Maintainers of the project are people the community can depend on and trust to make decisions in the best interest of the project. Anyone wanting to become a maintainer is expected to be deeply involved in contributing code, pull request review, and triage of issues in the project for more than three months.

A maintainer has authority over all sub projects within the OpenEBS organization, and have responsibility for:

* Project roadmap,
* Reviewing, approving and denying contributions,
* Maintaining coding, testing, documentation standards,
* Providing support and community engagement,
* Administration of the OpenEBS GitHub organization and repositories,
* Activities that move the project towards graduation status


#### Becoming a Maintainer
To become a Maintainer you need to demonstrate the following:

* commitment to the OpenEBS project:
    * Participate in discussions, contributions, code and documentation reviews for three months or more,
    * Perform reviews of and contribute to non-trivial pull requests,
    * Demonstrate alignment with the project vision and roadmap,
* ability to write quality code and/or documentation,
* ability to collaborate with the team,
* understanding of how the team works (policies, processes for testing and code review, etc),
* understanding of the project's code base and coding and documentation style.

A new Maintainer is nominated by an existing maintainer, a public vote is undertaken, and a 50% vote of existing Maintainers approves the application. A new maintainer’s nomination will be evaluated without prejudice to employer or demographics.

Maintainers who are selected will be granted necessary GitHub rights, and invited to the private maintainer mailing list.


#### Removing a Maintainer
Maintainers may resign at any time if they feel that they will not be able to continue fulfilling their project duties. Maintainers may also be removed after being inactive, failure to fulfill their Maintainer responsibilities, violating the Code of Conduct, or other reasons.

A Maintainer may be removed at any time by a ⅔ vote of the remaining maintainers.

### Contributors
OpenEBS is a very welcoming community and is eager to onboard and help anyone from the OpenSource community to contribute to the project. To facilitate onboarding of the community members, OpenEBS maintainers participate in Hackathon events and are responsive on the slack, community meetings and github.

Any individual with intent to contribute to open source in general or fix a specific issue they are having the OpenEBS project can contribute. If anyone is looking for ideas for contributing, the open issue backlog maintained under the OpenEBS GitHub projects is a great place to start.

A maintainer may assign a regular contributor write access to the GitHub project to allow them to directly request other organization members as reviewers for their PRs and to help them being added as reviewers for contributions coming from other contributors or OpenEBS organization members. A maintainer may also revoke the write access to the GitHub project.


### Adopters
OpenEBS welcomes people who simply want to Adopt the OpenEBS product, and welcomes them as part of our community. Adopters may use the OpenEBS product as they wish, contribute ideas or code, or create a fork of the code.


## Special Projects and Special Maintainers
All sub projects within the OpenEBS organization abide by the common umbrella governance and policies, and a maintainer has authority over all sub projects, with these exceptions.

The OpenEBS maintainers may elect, or the Steering Committee may assign:

* A “special maintainer” for one or more sub projects (typically where the individual has specialist knowledge for a discrete area of the project)
* A “special project” that operates with deviation from the common umbrella governance and rules. The deviations are listed in the project’s README.md.

Special projects and special maintainers are appointed or removed by the Steering Committee at their discretion, or elected and removed by a Maintainers vote (requiring 50% for election, and ⅔ for removal).

Special Projects and Special Maintainers are listed in the section “Appendix 2: Special Projects and Special Maintainers”


## Adding and Removing Sub Projects
The maintainers may add or remove sub projects (repositories). The maintainers take a conservative policy towards changing the sub projects: a new sub project must have a long term purpose that is distinct from existing sub projects; removed sub projects must be demonstrated to have outlived their purpose or have become unmaintainable.

When a sub project is removed, it is moved as-is to the OpenEBS-archive organization. 


## How are decisions made?
[See CONTRIBUTING guidleines and rules doc](./CONTRIBUTING.md)
```ruby
Also see: MAINTAINERS file
```

## Conflict Resolution
If you have a technical dispute that you feel has reached an impasse with a subset of the community, any contributor may open an issue, specifically calling for a resolution vote of the current maintainers to resolve the dispute. The same voting quorums required (2/3) for removing maintainers will apply to conflict resolution.


## Appendix 1: Steering Committee Members and Decisions

Members: 


### Record of Decisions


## Appendix 2: Special Projects and Special Maintainers
