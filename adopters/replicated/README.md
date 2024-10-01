### Company: Replicated ([replicated.com](https://www.replicated.com/))

### Stateful Applications that you are running on OpenEBS
* https://www.replicated.com/replicated-platform-overview Replicated's Embedded Cluster and kURL products use OpenEBS as the default storage provider. We use it for storing data for rqlite as well as backing store for the 'distribution' registry when operating in airgap mode.

### Type of OpenEBS Storage Engines behind the above application - Mayastor, LocalPV ZFS, LocalPV LVM, LocalPV HostPath?
* We use LocalPV HostPath today, although LocalPV ZFS and LVM are interesting as well.

### Are you evaluating or already using in development, CI/CD, production
* All three, we have customers in production using both of our Kubernetes installer products.

### Are you using for home use or for your organization
* Organization, although I use OpenEBS HostPath in CI for home use as well.

### A brief description of the use case or details on how OpenEBS is helping your projects.
* The embedded Kubernetes products target very low friction installation of Kubernetes with a Vendor's application all in one. With our new Embedded Cluster we aim to require zero Kubernetes knowledge to install and use the application. OpenEBS LocalPV HostPath provides a simple storage provider that works like people expect. They just want to store some data in a folder on their disk, no fussing around with CSI's or Kubernetes deep dive.
