# Security Policy

## Security bulletins

For requesting any information regarding the security of this project please join:

* [Slack](https://kubernetes.slack.com/messages/openebs/)

## Reporting a vulnerability

[GitHub](https://docs.github.com/en/code-security/security-advisories/guidance-on-reporting-and-writing/privately-reporting-a-security-vulnerability)
is the preferred method for privately reporting a security vulnerability.

1. File the report on the appropriate github repository  
   This is necessary because it allows us to use [temporary private forks](https://docs.github.com/en/code-security/security-advisories/working-with-repository-security-advisories/collaborating-in-a-temporary-private-fork-to-resolve-a-repository-security-vulnerability).  
   This table should help you, but in doubt please ask the maintainers for help.

   | **Project Name**    | **GitHub Repository**                  | **Create Report**                                                                               |
   |---------------------|----------------------------------------|-------------------------------------------------------------------------------------------------|
   | Umbrella            | [openebs/openebs]                      | [Create Report](https://github.com/openebs/openebs/security/advisories/new)                     |
   | Mayastor            | [openebs/mayastor]                     | [Create Report](https://github.com/openebs/mayastor/security/advisories/new)                    |
   |                     | [openebs/mayastor-control-plane]       | [Create Report](https://github.com/openebs/mayastor-control-plane/security/advisories/new)      |
   |                     | [openebs/mayastor-extensions]          | [Create Report](https://github.com/openebs/mayastor-extensions/security/advisories/new)         |
   | LVM LocalPV         | [openebs/lvm-localpv]                  | [Create Report](https://github.com/openebs/lvm-localpv/security/advisories/new)                 |
   | ZFS LocalPV         | [openebs/zfs-localpv]                  | [Create Report](https://github.com/openebs/zfs-localpv/security/advisories/new)                 |
   | Rawfile LocalPV     | [openebs/rawfile-localpv]              | [Create Report](https://github.com/openebs/rawfile-localpv/security/advisories/new)             |
   | HostPath LocalPV    | [openebs/dynamic-localpv-provisioner]  | [Create Report](https://github.com/openebs/dynamic-localpv-provisioner/security/advisories/new) |
   | CSI Go library      | [openebs/lib-csi]                      | [Create Report](https://github.com/openebs/lib-csi/security/advisories/new)                     |
   | Linux Utils         | [openebs/linux-utils]                  | [Create Report](https://github.com/openebs/linux-utils/security/advisories/new)                 |

   You will receive a confirmation email upon submission.  

2. You may be contacted by the maintainers to further discuss the reported item.  
   Please bear with us as we seek to understand the breadth and scope of the
   reported problem, recreate it, and confirm if there is a vulnerability
   present.

## Public Disclosure Timing

We prefer to fully disclose the bug as soon as possible once a user mitigation is available. \
The Fix Lead drives the schedule using their best judgment based on severity, development time, and release manager feedback. \
If the Fix Lead is dealing with a Public Disclosure all timelines become ASAP.

## Supported Versions

OpenEBS releases follow the [semver](https://semver.org/) specification. \
Security fixes are typically merged to the HEAD branch and due for release on the next minor version. \
Upon request or if deemed necessary as part of a critical security fix we may backport the changes as a patch release.

## Security Team Membership

The security team is made up of a subset of the project maintainers who are willing and
able to respond to vulnerability reports.

[openebs/openebs]: https://github.com/openebs/openebs
[openebs/mayastor]: https://github.com/openebs/mayastor
[openebs/mayastor-control-plane]: https://github.com/openebs/mayastor-control-plane
[openebs/mayastor-extensions]: https://github.com/openebs/mayastor-extensions
[openebs/lvm-localpv]: https://github.com/openebs/lvm-localpv
[openebs/zfs-localpv]: https://github.com/openebs/zfs-localpv
[openebs/rawfile-localpv]: https://github.com/openebs/rawfile-localpv
[openebs/dynamic-localpv-provisioner]: https://github.com/openebs/dynamic-localpv-provisioner
[openebs/lib-csi]: https://github.com/openebs/lib-csi
[openebs/linux-utils]: https://github.com/openebs/linux-utils
