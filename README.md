# OpenEBS Community

[![CNCF Status](https://img.shields.io/badge/cncf%20status-sandbox-blue.svg)](https://www.cncf.io/projects/openebs/)
[![LICENSE](https://img.shields.io/github/license/openebs/openebs.svg)](./LICENSE)
[![FOSSA Status](https://app.fossa.com/api/projects/custom%2B162%2Fgithub.com%2Fopenebs%2Fopenebs.svg?type=shield&issueType=license)](https://app.fossa.com/projects/custom%2B162%2Fgithub.com%2Fopenebs%2Fopenebs?ref=badge_shield&issueType=license)
[![CLOMonitor](https://img.shields.io/endpoint?url=https://clomonitor.io/api/projects/cncf/openebs/badge)](https://clomonitor.io/projects/cncf/openebs)
[![Slack](https://img.shields.io/badge/chat-slack-ff1493.svg?style=flat-square)](https://kubernetes.slack.com/messages/openebs)
[![Community Meetings](https://img.shields.io/badge/Community-Meetings-blue)](https://us05web.zoom.us/j/87535654586?pwd=CigbXigJPn38USc6Vuzt7qSVFoO79X.1)
[![Artifact HUB](https://img.shields.io/endpoint?url=https://artifacthub.io/badge/repository/openebs)](https://artifacthub.io/packages/helm/openebs/openebs)

> [!Important]
> OpenEBS is an umbrella :open_umbrella: project, composed as a federation of individual sub-projects. The project files in this repository apply to the umbrella project and every sub-project in the OpenEBS organization.

## What is OpenEBS

OpenEBS is an open-source Container Native Storage solution that provides persistent storage for Kubernetes workloads. It enables dynamic provisioning of storage resources using containerized storage controllers, making it highly flexible and cloud-native. OpenEBS supports various storage engines, including LocalPVs for direct node storage and Replicated PV advanced data replication and resilience. It is designed to integrate seamlessly with Kubernetes, offering benefits like storage policies, resize, thin-provisioning, snapshots, and restore capabilities, making it an ideal choice for stateful applications. To read more about OpenEBS, check [here](https://github.com/openebs/openebs/).

Below are the list of sub-projects:

- [Local PV Hostpath](https://github.com/openebs/dynamic-localpv-provisioner/)
- [Local PV ZFS](https://github.com/openebs/zfs-localpv)
- [Local PV LVM](https://github.com/openebs/lvm-localpv)
- [Local PV Rawfile(_**Experimental**_)](https://github.com/openebs/lvm-localpv)
- [Mayastor](https://github.com/openebs/mayastor)

## Who we are

We are a community of innovative Data Storage engineers that contribute to this project. OpenEBS is the result of hundreds of amazing individuals, contributors and storage engineers who provide brainstorming ideas, feedback, code reviews and high-quality code to the project. Anyone who is passionate about storage and data is welcome here. <BR>

## Community

This Community repository is the ```central location``` for project info and files like our governance, contribution, code of conduct, security and vision for the OpenEBS organization laid out by the Maintainers. You'll also find a [Top level Issues List](https://github.com/openebs/openebs/issues) for Organization related issues that span across products/projects. We also provide a [main Discussions forum](https://github.com/openebs/openebs/discussions) where **```everyone```** can collaborate and discuss anything.

- Homepage: [openebs.io](https://openebs.io/)
- Mailing list: openebs-team@googlegroups.com
- Slack: [slack](https://kubernetes.slack.com/messages/openebs)
- Twitter: [openebs](https://twitter.com/intent/follow?screen_name=openebs)
- Community Meeting: OpenEBS holds a monthly community meeting via Zoom on the last Thursday of the month, at 14:00 UTC. [Meeting Link](https://us05web.zoom.us/j/87535654586?pwd=CigbXigJPn38USc6Vuzt7qSVFoO79X.1)
- Community Meeting Recordings: [Youtube](https://www.youtube.com/@openebscommunity6021)

## Documents

- [Official Documentation](https://openebs.io/docs)
- [Governance](./GOVERNANCE.md)
- [Contributing Guidelines](./CONTRIBUTING.md)
- [Security Guidelines](./SECURITY.md)
- [Vision](./VISION.md)
- [Roadmap Tracker](https://github.com/orgs/openebs/projects/78)

## Integrations with other projects

| Technology             | Integration                                      | Description                                                           |
|:-----------------------|:------------------------------------------------:|:---------------------------------------------------------------------:|
| [OpenZFS]              | [ZFS Install Guide] <br> [ZFS Code Integration]  | LocalPV ZFS integrates with OpenZFS                                   |
| [External Provisioner] | [External Provisioner Integration]               | LocalPV Hostpath integrates with the SIG Storage External Provisioner |
| [SPDK]                 | [spdk-rs] <br> [io-engine]                       | Mayastor uses SPDK to build a high-speed low-latency storage backend  |
| [gRPC]                 | [Inter Service Communication]                    | Used as internal service communication                                |
| [etcd]                 | [Persistent Store] <br> [PStor client]           | Used as persistent configuration (not volume data)                    |
| [NATS]                 | [Event bus]                                      | Used as event bus                                                     |
| [OpenTelemetry]        | [Tracing]                                        | Tracing system for observability                                      |
| [Helm]                 | [Helm Install Guide]                             | Installs/upgrades on K8s cluster                                      |
| [Grafana]              | [Grafana Dashboards]                             | Install grafana custom dashboards with OpenEBS exported metrics       |
| [Grafana/Loki]         | [Loki Support logs]                              | Collect support logs                                                  |
| [Prometheus]           | [Monitoring]                                     | Export stats                                                          |
| [Kubernetes]           | [Install Guide]                                  | Runs on K8s                                                           |

[//]: <>  (Technology Links)
[OpenZFS]: https://openzfs.github.io/openzfs-docs/
[External Provisioner]: https://github.com/kubernetes-sigs/sig-storage-lib-external-provisioner
[Grafana]: https://grafana.com/
[Grafana/Loki]: https://grafana.com/oss/loki/
[SPDK]: https://spdk.io/
[gRPC]: https://grpc.io/
[etcd]: https://etcd.io/
[NATS]: https://nats.io/
[OpenTelemetry]: https://opentelemetry.io/
[Helm]: https://helm.sh/
[Prometheus]: https://prometheus.io/
[Kubernetes]: https://kubernetes.io/

[//]: <>  (Integrations Links)
[ZFS Install Guide]: https://openebs.io/docs/user-guides/local-storage-user-guide/local-pv-zfs/zfs-installation
[ZFS Code Integration]: https://github.com/openebs/zfs-localpv/blob/HEAD/pkg/zfs/zfs_util.go
[External Provisioner Integration]: https://github.com/openebs/dynamic-localpv-provisioner/blob/develop/cmd/provisioner-localpv/app/provisioner_hostpath.go
[Grafana Dashboards]: https://openebs.io/docs/main/user-guides/observability#install-the-helm-chart
[Loki Support logs]: https://openebs.io/docs/user-guides/replicated-storage-user-guide/replicated-pv-mayastor/advanced-operations/supportability
[spdk-rs]: https://github.com/openebs/spdk-rs
[io-engine]: https://github.com/openebs/mayastor/blob/HEAD/doc/design/mayastor.md
[Inter Service Communication]: https://github.com/openebs/mayastor/blob/HEAD/doc/design/control-plane.md#internal-communication
[Persistent Store]: https://github.com/openebs/mayastor/blob/HEAD/doc/design/control-plane.md#persistent-store-kvstore-for-configuration-data
[PStor client]: https://github.com/openebs/mayastor-control-plane/blob/HEAD/utils/pstor/src/etcd.rs
[Event bus]: https://github.com/openebs/mayastor/blob/HEAD/doc/design/events.md
[Tracing]: https://github.com/openebs/mayastor/blob/HEAD/doc/design/control-plane.md#tracing-and-telemetry
[Helm Install Guide]: https://openebs.io/docs/quickstart-guide/installation#installation-via-helm
[Monitoring]: https://openebs.io/docs/user-guides/replicated-storage-user-guide/replicated-pv-mayastor/advanced-operations/monitoring
[Install Guide]: https://openebs.io/docs/quickstart-guide/installation


## Project Leadership team

This Community is managed by the OpenEBS [Maintainers](./MAINTAINERS.md) within the OpenEBS project team. We liaise with the Linux Foundation and CNCF on project, governance
and operational matters. We curate the operations of the project, product, roadmaps, initiatives, all engineering/code activities and all events (including conferences).

 [<img alt="Container Storage Interface group" src="images/CNCF_csi-horizontal-color_2024.png" width="320">](https://github.com/kubernetes/community/tree/HEAD/sig-storage)  [<img alt="Storage Technical Advisory Group" src="images/CNCF_tag-storage-horizontal-color_2024.png" width="320">](https://github.com/cncf/tag-storage)  &emsp; &emsp; [<img alt="Cloud Native Community Groups" src="images/CNCF_cncg-icon-color_2024.png" width="200">](https://github.com/cncf/communitygroups)

## How to get involved

One of the easiest ways to contribute is to participate in discussions at community engagements.

If you're looking for something to work on, read the [contribution guidelines](./CONTRIBUTING.md) and then you start by looking for GitHub issues, marked with `kind/good-first` or the `kind/help-wanted` labels.

And, we can always use more testing, have more and improved docs, or just write a blog post on what you have discovered whilst using OpenEBS.

## Code of Conduct

OpenEBS adopts the [CNCF Code of Conduct](https://github.com/cncf/foundation/blob/HEAD/code-of-conduct.md).

This open governance applies to all repos under the `openebs` org. Enjoy coding and collaboration in OSS world!

## Activity dashboard

![Alt](https://repobeats.axiom.co/api/embed/1e565d4d1fdfeacd2cf810f10bcb6cde7368c9ea.svg "Repobeats analytics image")

## License

[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Fopenebs%2Fcommunity.svg?type=large)](https://app.fossa.com/projects/git%2Bgithub.com%2Fopenebs%2Fcommunity?ref=badge_large)

## OpenEBS is a [CNCF Sandbox Project](https://www.cncf.io/projects/openebs)

![OpenEBS is a CNCF Sandbox Project](https://github.com/cncf/artwork/blob/main/other/cncf/horizontal/color/cncf-color.png)