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
| *Persona* | Multiple storage services covering the follwing operating modes; ```Node Local```, ```Fabric Attached```, ```Replicated```, ```Non-Replicated```, ```Protected``` and ```non-protected```, ```Highly Available``` storage.  |
| *Fast* | Optimized multiple storage drivers and storage media types, with a particular focus on Solid State Flash media.  |
| *Resilient* | Storage is highly resilent and self-healing. Reads and writes are protected even as containers or nodes are terminated. Volumes and Data Writes can be replicated across nodes via replication. Snapshots and cloning provide additional levels of tolerance,  resilance & self-healing. |
| *Available* | Storage attached to one node can be made addressible to applications running on any node within the cluster through a ```“Nexus” Virtual SAN Fabric``` (i.e. Block mode Storage Area Network). |
| *Native* | Implemented as ```container native storage```, a Kubernetes netively integrated component, optimized for storage contained inside a Kubernetes cluster. (Hyper converged). |
| *Enterprise grade* | A fully featured, community proven, rigorously tested, trustworthy, Mission Critical product. |
| *Kubernetes* | OpenEBS focus is for Kubernetes on Linux. |
<BR>

> [!IMPORTANT]
> With OpenEBS users can attach an storage media (any block-mode storage device) to a node, and assign it to be managed by OpenEBS; where the system can be configurred to provide access to provisioned Storage volumes across any container within the cluster. You can address block devices across nodes and create volume snapshots/clones. You can set up Highly flexible local volumes and expand the volume and filesystem while online. You can trust OpenEBS whether you are a hobbyist programmer, small business or large enterprise. 
<BR>

### Scope
In the past, the OpenEBS project has tried to accomplish too much. Our scope was too broad and not clearly defined enouigh for our community. We are explicitly naming the following capabilities as ```in-scope``` and ```out-of-scope``` for the project:

> **In Scope** <BR>

| Item  | Scope and description     |
| :---: | :---                      |
| 1. | OpenEBS Standard product, with installation via Helm charts for Kubernetes |
| 2. | ```Block mode``` storage managment and integration |
| 3. | ```Local``` and ```Fabric Addressible``` block-mode storage services |
| 4. | ```Non-replicated``` (Single Node resident vol) and ```Replicated``` (Multi-Node Distributed vol) block-level storage |
| 5. | ```Filesystem``` integrations (Kernel, FUSE) |
| 6. | ```Object Storage``` integrations (Product Native and 3rd party) |
| 7. | Cluster-wide Block mode storage address space ```vSAN Fabric``` |
| 8. | Block, file, Object level ```application``` storage services |
| 9. | ```Rest API``` and ```Cli``` for accessing all capabilities |
| 10. | Storage Reporting, alerting, monitoring, metrics |
| 11. | Read/Write Access Modes for RWO, ROX, RWOP - (*RWX with strict limitations) |
| 12. | Deployable as ```On-premiss```, ```SaaS/PaaS in-cloud```, ```Bare Metal```, ```HyperVisor``` hosted | 
<BR>

> **Out-of-Scope**

| Item  | Scope and description     |
| :---: | :---                      |
| 1. | Updates to legacy/deprecated storage drivers (archived in the OpenEBS-archive organization) |
| 2. | Graphical user interface for setup, administration, reporting, dashboards |
| 3. | Vendor-specific proprietary integrations, including vendor-specific cloud hosting integrations and optimizations |
| 4. | Vendor-specific authentication, authorization, key management |
| 5. | Application-level optimizations and Storage operations beyond what is provided in the file system and kernel drivers (the OpenEBS  project does not improve upon or develop our own file systems, nor do we add optimization capabilities)
<BR>

**ALL** Issues, Pull Requests, feature requests (OEP’s), contributions, and roadmap requests will be evaluated against these scopes, and OpenEBS mission statement.

---

## Values
The OpenEBS project and its leadership embrace the [values of CNCF](https://github.com/kubernetes/community/blob/master/values.md)

## Restraints
OpenEBS is a self-governing project, and operates within the following restraints:

### CNCF
* OpenEBS is a [CNCF (Cloud Native Computing Foundation)](https://cncf.io) project. 
* The OpensEBS project is open source, and operations are governed by CNCF rules set up for CNCF projects.
* The OpenEBS project adds ```domain-specific Governance```, ```Contribution``` and ```operating rules``` on **top of the CNCF rules**. We provide for exceptions from the CNCF rules if approved by CNCF Technical Oversight Committee (TOC).


[![CNCF logo](/images/CNCF_member-silver-color.svg)](https://www.datacore.com/)
DataCore, Inc is a CNCF Silver member. DataCore support's CNCF extensively and funds all OpenEBS CNCF events. The project team is managed under the CNCF Storage Landscape and contributes to the CNCF CSI and TAG Storage project initiatives. We proudly support CNCF Cloud Native Community Groups initatives.<BR>
<BR>


| <img  alt="Container Storage Interface group" align="left" src="/images/CNCF_csi-horizontal-color_2024.png" width="320" /> | <img alt="Storage Technical Advisory Group" align="center" src="/images/CNCF_tag-storage-horizontal-color_2024.png" width="320" /> | &emsp; &emsp; <img alt="Cloud Native Community Groups" align="right" src="/images/CNCF_cncg-icon-color_2024.png" width="200" /> |
| :---         |     :---:      |          ---: |


### DataCore
> [!IMPORTANT]
> * OpenEBS was created by MayaData (now part of [DataCore Software, Inc.](https://datacore.com) ), and donated to [CNCF](https://cncf.io) in 2019.
> * DataCore engineers contribute a majority of the contributions, program management, Engineering, Dev, QA rescources as well as considerbale infrastructure funding to the daily operations of the project.
> * The project requires multiple Full-Time ```Subject Matter Experts```, Full-Time storage engineers and Full-Time QA Engineers/testers. While the project requires this commitment, it is expected DataCore engineers may be a majority of the contributing Eng/Dev/QA/PM community.
> * OpenEBS is a community project, and DataCore has been and continues to be a significant part of the community 

## Conformance
The OpenEBS project produces the OpenEBS Standard product. Many vendors have incorporated, or wish to incorporate a version of OpenEBS as a component within their own product offering, including Microsoft Azure, DataCore and Civo. 

The OpenEBS project and CNCF recognize the importance of supporting this, and maintain a conformance program for vendors to use OpenEBS technology and OpenEBS marks.

## Rules and Governance
The [OpenEBS GitHub organization](https://github.com/openebs) has multiple repositories, for the purpose of organizing project information, source code, assets, Intellectual property (IP) and resources. Every repository in the organization follows the same set of  “umbrella” Project Rules and [Governance](./GOVERNANCE.md). All community wide infomation  is located in the [OpenEBS Community Repository](https://github.com/openebs/community).


## Archvie Organization
> [!IMPORTANT]
> The OpenEBS project Leadership/Maintainers also administer the affiliated [**OpenEBS-archive organization**](https://github.com/openebs-archive). <BR>
> 1. This parallel organization is **OWNED by CNCF** and administrated as a reference archive for OpenEBS ```Legacy``` and ```Deprecated``` OpenEBS repositories, assets, IP, source code, dependancies and rescources. <BR>
> 2. From time to time, we reserve then right to selectively Deprecate and Archive OpenEBS components and  physically migrate them ```**out-of**``` the OpenEBS Parent project; and into the Archive organization. This process **officially removes** those OpenEBS components from the parent OpenEBS project/product. All entites held within the Archive org are **NO LONGER** an active component of the OpenEBS Parent project/product. <BR>
> 3. The Archvie org is **NOT** intended for active code or community contributions. The [Proejct Rules and Governance](./GOVERNANCE.md) also apply to the OpenEBS-archive organization, unless explicitly stated otherwise in the OpenEBS-archive organization README. <BR>