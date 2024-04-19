# OpenEBS Project Vision
> [!Important]
> This document is: OpenEBS Project Vision. A foundation document for the OpenEBS project. OpenEBS Project Governance. OpenEBS is an umbrella project, composed as a federation of individual sub projects (repositories). This document applies to both the umbrella project and to every sub project in the OpenEBS organization.
<br>
OpenEBS (Open-Elastic-Block-Storage) aims to provide fast, resilient, available, native, enterprise-grade storage to applications running in Kubernetes clusters. 

In this document we present the project:
* Vision, Mission Statement and Scope
* Values
* Restraints
* Conformance
* Rules and governance

## Vision, Mission Statement and Scope
**Our Vision:** The Kubernetes storage standard
**Our Mission Statement:** OpenEBS is a _CNCF _project that provides_ fast, resilient, available, native, enterprise-grade_ storage to applications running in _Kubernetes _clusters. 

* _CNCF_: OpenEBS is an open source project operating within CNCF project guidelines, and is focused on achieving graduated project status.
* _Fast_: Optimized multiple storage drivers and storage media types, with a particular focus on Flash media.
* _Resilient_: Storage is fault-tolerant and self-healing. Reads and writes are protected even as containers or nodes are terminated. Volumes and Data Writes can be replicated stored across nodes, with replication, snapshots and cloning providing fault tolerance.
* _Available_: Storage attached to one node is available to applications running on any node in the cluster through a “Nexus” storage Virtual SAN fabric.
* _Native_: Implemented as “container native storage”, a Kubernetes component, optimized for storage contained inside a Kubernetes cluster. (Hyper converged)
* _Enterprise grade_: A fully featured, community proven, rigorously tested, trustworthy product.
* _Kubernetes_: OpenEBS focus is for Kubernetes on Linux.

With OpenEBS you can attach an SSD drive or SCSI drive (any block-mode storage media) to a node, and access the volume across any container in the cluster; you can address block devices across nodes and create volume snapshots; you can set up Highly flexible local volumes and expand the volume and filesystem while online. You can trust OpenEBS whether you are a hobbyist programmer, small business or large enterprise. 

### Scope
In the past, the OpenEBS project has tried to accomplish too much. We are explicitly naming the following capabilities as in-scope and out-of-scope for the project:

**In Scope**
* OpenEBS Standard product, with installation via Helm charts for Kubernetes
* Non-replicated (local) and replicated (distributed) block-level storage
* Block mode storage integration
* Filesystem integration (Kernel, FUSE)
* Object Storage 
* Container-wide storage vSAN fabric
* Block-level and file-level storage Data Mgmt capabilities
* Rest API for accessing all capabilities

**Out-of-Scope**
* Updates to legacy/duplicated storage drivers (archived in the OpenEBS-archive organization)
* Graphical user interface for setup, administration, reporting, dashboards
* Vendor-specific proprietary integrations, including vendor-specific cloud hosting integrations and optimizations
* Vendor-specific authentication, authorization, key management
* Application-level optimizations and Storage operations beyond what is provided in the file system and kernel drivers (the OpenEBS project does not improve upon or develop our own file systems, nor do we add optimization capabilities)

Any Issues, Pull Requests, feature requests (OEP’s), contributions, and roadmap requests will be evaluated against these scopes, and OpenEBS mission statement.


## Values
The OpenEBS project and its leadership embrace the values of CNCF: [https://github.com/kubernetes/community/blob/master/values.md](https://github.com/kubernetes/community/blob/master/values.md)


## Restraints
OpenEBS is a self-governing project, and operates within the following restraints:

### CNCF
* OpenEBS is a CNCF (Cloud Native Computing Foundation) project. The project is open source, and operations are governed by CNCF rules set up for CNCF projects. 
* The OpenEBS project adds domain-specific Governance, Contribution and operating rules on top of the CNCF rules. We provide for exceptions from the CNCF rules if approved by CNCF Technical Oversight Committee (TOC)

### DataCore
* OpenEBS was created by MayaData (now part of DataCore), and donated to CNCF in 2019
* DataCore engineers contribute a majority of the contributors and program management to the project
* The project requires multiple full-time engineers and full-time testers. While the project requires this commitment, it is expected DataCore engineers will continue to be the primary contributors.
* OpenEBS is a community project, and DataCore has been and continues to be a significant part of the community 

## Conformance
The OpenEBS project produces the OpenEBS Standard product. Many vendors have incorporated, or wish to incorporate a version of OpenEBS as a component within their own product offering, including Microsoft Azure, DataCore and Civo. 

The OpenEBS project and CNCF recognize the importance of supporting this, and maintain a conformance program for vendors to use OpenEBS technology and OpenEBS marks.

## Rules and Governance
The OpenEBS GitHub organization has multiple repositories, for the purpose of organizing information, source code and resources. Every repository in the organization follows the same set of  “umbrella” Rules and Governance located in the OpenEBS Community Repository.

The OpenEBs project also maintains the OpenEBS-archive organization. This is a reference archive for legacy and deprecated repositories, and is not intended for active code contributions. The OpenEBS Rules and Governance also apply to the OpenEBS-archive organization, unless explicitly stated otherwise in the OpenEBS-archive organization README. 
