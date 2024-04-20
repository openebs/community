# OpenEBS Project Vision
> [!Important]
> This document is: OpenEBS Project Vision. A foundation document for the OpenEBS project. OpenEBS Project Governance. OpenEBS is an umbrella project, composed as a federation of individual sub projects (repositories). This document applies to both the umbrella project and to every sub project in the OpenEBS organization.
<br>
OpenEBS (Open-Elastic-Block-Storage) aims to provide fast, resilient, available, enterprise-grade storage; natively inside a Kubernetes cluster as Hyper-Converged storage. OpensEBS Users provision OpenEBS storgae services to Kubernetes applications running natively inside a Kubenetes cluster. 

In this document we present the project:
* Vision, Mission Statement and Scope
* Values
* Restraints
* Conformance
* Rules and governance

## Vision, Mission Statement and Scope
**Our Vision:** The Kubernetes storage standard <BR>
**Our Mission Statement:** OpenEBS is a *CNCF project* that provides fast, resilient, available, native, enterprise-grade storage to applications running in *Kubernetes clusters*. 

| Vision | Definiton and description of vision     |
| :---       | :---                                    |
| *CNCF* | OpenEBS is an open source project operating within CNCF Storage Landscape guidelines, and is focused on achieving ```Graduated Level``` status.   |
| *Persona* | Multiple storage services covering the follwing operating modes; ```Node Local```, ```Fabric Attached```, ```Replicated```, ```Non-Replicated```, ```Protected``` and ```non-protected``` storage.  |
| *Fast* | Optimized multiple storage drivers and storage media types, with a particular focus on Solid State Flash media.  |
| *Resilient* | Storage is highly resilent and self-healing. Reads and writes are protected even as containers or nodes are terminated. Volumes and Data Writes can be replicated across nodes via replication. Snapshots and cloning providing additional levelsof tolerance,  resilance & self-healing. |
| *Available* | Storage attached to one node can be made addressible to applications running on any node within the cluster through a ```“Nexus” Virtual SAN Fabric``` (i.e. Block mode Storage Area Network). |
| *Native* | Implemented as ```container native storage```, a Kubernetes netively integrated component, optimized for storage contained inside a Kubernetes cluster. (Hyper converged). |
| *Enterprise grade* | A fully featured, community proven, rigorously tested, trustworthy, Mission Critical product. |
| *Kubernetes* | OpenEBS focus is for Kubernetes on Linux. |
<BR>

> [!IMPORTANT]
> With OpenEBS users can attach an storage media (any block-mode storage device) to a node, and assign it to be managed by OpenEBS; where the system can be configurred to provide access to provisioned Storage volumes across any container within the cluster. You can address block devices across nodes and create volume snapshots/clones. You can set up Highly flexible local volumes and expand the volume and filesystem while online. You can trust OpenEBS whether you are a hobbyist programmer, small business or large enterprise. 
<BR>

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
