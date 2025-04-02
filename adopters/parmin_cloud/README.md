### **Company**: [ParminCloud](https://github.com/ParminCloud)

### Stateful Applications that you are running on OpenEBS

* PostgreSQL (CloudNativePG)
* MongoDB
* MySQL
* OpenSearch
* MinIO
* GitLab
* Jira/Confluence
* Monitoring Stack (VictoriaMetrics)
* Apache Kafka (Strimzi)
* RabbitMQ
* Container/Application registries
* etc.

### Type of OpenEBS Storage Engines behind the above application - Mayastor, LocalPV ZFS, LocalPV LVM, LocalPV HostPath?

* LocalPV LVM
* LocalPV RawFile

### Are you evaluating or already using in development, CI/CD, production

Using in production

### Are you using for home use or for your organization

Organization and Some of our Clusters (If a local provisioner is needed [It is required most of the times])

### A brief description of the use case or details on how OpenEBS is helping your projects

We are using LVM Local PV in the clusters when we are deploying Stateful applications that are Highly Available at the Application layer
We are using `xfs` as the file system since some of the applications/databases are working better with this filesystem
Also thanks to the LVM features are having great performance and also using it's feature like Snapshotting, etc.
> At first we wanted to use Rawfile but we have decided to use LVM until the project become stable

We are using it as our local provisioner since it's production ready and feature rich
One of the good things about OpenEBS is that The community is active
And we are Contributing to OpenEBS happily