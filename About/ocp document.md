Table of Contents

Welcome to the official OpenShift Container Platform 4.16 documentation, where you can learn about OpenShift Container Platform and start exploring its features.

To navigate the OpenShift Container Platform 4.16 documentation, you can use one of the following methods:

Use the left navigation bar to browse the documentation.
Select the task that interests you from the contents of this Welcome page.
Start with Architecture and Security and compliance. Next, view the release notes.

1.1. Cluster installer activities 

Explore the following OpenShift Container Platform installation tasks:

OpenShift Container Platform installation overview: Depending on the platform, you can install OpenShift Container Platform on installer-provisioned or user-provisioned infrastructure. The OpenShift Container Platform installation program provides the flexibility to deploy OpenShift Container Platform on a range of different platforms.
Installing a cluster on Alibaba Cloud by using the Assisted Installer: On Alibaba Cloud, you can install OpenShift Container Platform by using the Assisted Installer. This is currently a Technology Preview feature only.
Install a cluster on AWS: On AWS, you can install OpenShift Container Platform on installer-provisioned infrastructure or user-provisioned infrastructure.
Install a cluster on Microsoft Azure: On Microsoft Azure, you can install OpenShift Container Platform on installer-provisioned infrastructure or user-provisioned infrastructure.
Install a cluster on Microsoft Azure Stack Hub: On Microsoft Azure Stack Hub, you can install OpenShift Container Platform on installer-provisioned infrastructure or user-provisioned infrastructure.
Installing OpenShift Container Platform with the Assisted Installer: The Assisted Installer is an installation solution that is provided on the Red Hat Red Hat Hybrid Cloud Console. The Assisted Installer supports installing an OpenShift Container Platform cluster on multiple platforms.
Installing OpenShift Container Platform with the Agent-based Installer: You can use the Agent-based Installer to generate a bootable ISO image that contains the Assisted discovery agent, the Assisted Service, and all the other information required to deploy an OpenShift Container Platform cluster. The Agent-based Installer leverages the advantages of the Assisted Installer in a disconnected environment
Install a cluster on bare metal: On bare metal, you can install OpenShift Container Platform on installer-provisioned infrastructure or user-provisioned infrastructure. If none of the available platform and cloud provider deployment options meet your needs, consider using bare metal user-provisioned infrastructure.
Install a cluster on Google Cloud: On Google Cloud you can install OpenShift Container Platform on installer-provisioned infrastructure or user-provisioned infrastructure.
Install a cluster on IBM Cloud®: On IBM Cloud®, you can install OpenShift Container Platform on installer-provisioned infrastructure.
Install a cluster on IBM Power® Virtual Server: On IBM Power® Virtual Server, you can install OpenShift Container Platform on installer-provisioned infrastructure.
Install a cluster on IBM Power®: On IBM Power®, you can install OpenShift Container Platform on user-provisioned infrastructure.
Install a cluster on IBM Z® and IBM® LinuxONE: On IBM Z® and IBM® LinuxONE, you can install OpenShift Container Platform on user-provisioned infrastructure.
Install a cluster on Oracle® Cloud Infrastructure (OCI): You can use the Assisted Installer or the Agent-based Installer to install a cluster on OCI. This means that you can run cluster workloads on infrastructure that supports dedicated, hybrid, public, and multiple cloud environments. See Installing a cluster on Oracle Cloud Infrastructure (OCI) by using the Assisted Installer and Installing a cluster on Oracle Cloud Infrastructure (OCI) by using the Agent-based Installer.
Install a cluster on Nutanix: On Nutanix, you can install a cluster on your OpenShift Container Platform on installer-provisioned infrastructure.
Install a cluster on Red Hat OpenStack Platform (RHOSP): On RHOSP, you can install OpenShift Container Platform on installer-provisioned infrastructure or user-provisioned infrastructure.
Install a cluster on VMware vSphere: You can install OpenShift Container Platform on supported versions of vSphere.
1.2. Other cluster installer activities 

Install a cluster in a restricted network: If your cluster uses user-provisioned infrastructure on Amazon Web Services (AWS), Google Cloud, vSphere, IBM Cloud®, IBM Z® and IBM® LinuxONE, IBM Power®, or bare metal and the cluster does not have full access to the internet, you must mirror the OpenShift Container Platform installation images. To do this action, use one of the following methods, so that you can install a cluster in a restricted network.

Mirroring images for a disconnected installation
Mirroring images for a disconnected installation by using the oc-mirror plug-in
Install a cluster in an existing network: If you use an existing Virtual Private Cloud (VPC) in Amazon Web Services (AWS) or Google Cloud or an existing VNet on Microsoft Azure, you can install a cluster. Also consider Installing a cluster on Google Cloud into a shared VPC
Install a private cluster: If your cluster does not require external internet access, you can install a private cluster on Amazon Web Services (AWS), Microsoft Azure, Google Cloud, or IBM Cloud®. Internet access is still required to access the cloud APIs and installation media.
Installing RHCOS manually on an iSCSI boot device and Installing RHCOS on an iSCSI boot device using iBFT: You can target iSCSI devices as the root disk for installation of RHCOS. Multipathing is also supported.
Check installation logs: Access installation logs to evaluate issues that occur during OpenShift Container Platform installation.
Access OpenShift Container Platform: Use credentials output at the end of the installation process to log in to the OpenShift Container Platform cluster from the command line or web console.
Install Red Hat OpenShift Data Foundation: You can install Red Hat OpenShift Data Foundation as an Operator to provide highly integrated and simplified persistent storage management for containers.
Red Hat Enterprise Linux CoreOS (RHCOS) image layering: As a post-installation task, you can add new images on top of the base RHCOS image. This layering does not modify the base RHCOS image. Instead, the layering creates a custom layered image that includes all RHCOS functions and adds additional functions to specific nodes in the cluster.
1.3. Developer activities 

Develop and deploy containerized applications with OpenShift Container Platform. OpenShift Container Platform is a platform for developing and deploying containerized applications. Read the following OpenShift Container Platform documentation, so that you can better understand OpenShift Container Platform functions:

Understand OpenShift Container Platform development: Learn the different types of containerized applications, from simple containers to advanced Kubernetes deployments and Operators.
Work with projects: Create projects from the OpenShift Container Platform web console or OpenShift CLI (oc) to organize and share the software you develop.
Creating applications using the Developer perspective: Use the Developer perspective in the OpenShift Container Platform web console to easily create and deploy applications.
Viewing application composition using the Topology view: Use the Topology view to visually interact with your applications, monitor status, connect and group components, and modify your code base.
Create CI/CD Pipelines: Pipelines are serverless, cloud-native, continuous integration and continuous deployment systems that run in isolated containers. Pipelines use standard Tekton custom resources to automate deployments and are designed for decentralized teams that work on microservice-based architecture.
Manage your infrastructure and application configurations: GitOps is a declarative way to implement continuous deployment for cloud native applications. GitOps defines infrastructure and application definitions as code. GitOps uses this code to manage multiple workspaces and clusters to simplify the creation of infrastructure and application configurations. GitOps also handles and automates complex deployments at a fast pace, which saves time during deployment and release cycles.
Deploy Helm charts: Helm is a software package manager that simplifies deployment of applications and services to OpenShift Container Platform clusters. Helm uses a packaging format called charts. A Helm chart is a collection of files that describes the OpenShift Container Platform resources.
Understand image builds: Choose from different build strategies (Docker, S2I, custom, and pipeline) that can include different kinds of source materials, such as Git repositories, local binary inputs, and external artifacts. You can follow examples of build types from basic builds to advanced builds.
Create container images: A container image is the most basic building block in OpenShift Container Platform and Kubernetes applications. By defining image streams, you can gather multiple versions of an image in one place as you continue to develop the image stream. With S2I containers, you can insert your source code into a base container. The base container is configured to run code of a particular type, such as Ruby, Node.js, or Python.
Create deployments: Use Deployment objects to exert fine-grained management over applications. Deployments create replica sets according to the rollout strategy, which orchestrates pod lifecycles.
Create templates: Use existing templates or create your own templates that describe how an application is built or deployed. A template can combine images with descriptions, parameters, replicas, exposed ports and other content that defines how an application can be run or built.
Understand Operators: Operators are the preferred method for creating on-cluster applications for OpenShift Container Platform 4.16. Learn about the Operator Framework and how to deploy applications by using installed Operators into your projects.
Develop Operators: Operators are the preferred method for creating on-cluster applications for OpenShift Container Platform 4.16. Learn the workflow for building, testing, and deploying Operators. You can then create your own Operators based on Ansible or Helm, or configure built-in Prometheus monitoring by using the Operator SDK.
Reference the REST API index: Learn about OpenShift Container Platform application programming interface endpoints.
Software Supply Chain Security enhancements: The PipelineRun details page in the Developer or Administrator perspective of the web console provides a visual representation of identified vulnerabilities, which are categorized by severity. Additionally, these enhancements provide an option to download or view Software Bill of Materials (SBOMs) for enhanced transparency and control within your supply chain. Learn about setting up OpenShift Pipelines in the web console to view Software Supply Chain Security elements.
1.4. Cluster administrator activities 

Manage machines, provide services to users, and follow monitoring and logging reports. Read the following OpenShift Container Platform documentation, so that you can better understand OpenShift Container Platform functions:

Understand OpenShift Container Platform management: Learn about components of the OpenShift Container Platform 4.16 control plane. See how OpenShift Container Platform control plane and compute nodes are managed and updated through the Machine API and Operators.
Cluster capabilities: As a cluster administrator, you can enable cluster capabilities that were disabled before installation.
1.4.1. Manage cluster components 

Manage machines: Manage compute and control plane machines in your cluster with machine sets, by deploying health checks, and applying autoscaling.
Manage container registries: Each OpenShift Container Platform cluster includes a built-in container registry for storing its images. You can also configure a separate Red Hat Quay registry to use with OpenShift Container Platform. The Quay.io website provides a public container registry that stores OpenShift Container Platform containers and Operators.
Manage users and groups: Add users and groups with different levels of permissions to use or modify clusters.
Manage authentication: Learn how user, group, and API authentication works in OpenShift Container Platform. OpenShift Container Platform supports multiple identity providers.
Manage ingress, API server, and service certificates: OpenShift Container Platform creates certificates by default for the Ingress Operator, the API server, and for services needed by complex middleware applications that require encryption. You might need to change, add, or rotate these certificates.
Manage networking: The cluster network in OpenShift Container Platform is managed by the Cluster Network Operator (CNO). The CNO uses iptables rules in kube-proxy to direct traffic between nodes and pods running on those nodes. The Multus Container Network Interface adds the capability to attach multiple network interfaces to a pod. By using network policy features, you can isolate your pods or permit selected traffic.
Manage Operators: Lists of Red Hat, ISV, and community Operators can be reviewed by cluster administrators and installed on their clusters. After you install them, you can run, upgrade, back up, or otherwise manage the Operator on your cluster.
Understanding Windows container workloads. You can use the Red Hat OpenShift support for Windows Containers feature to run Windows compute nodes in an OpenShift Container Platform cluster. This is possible by using the Red Hat Windows Machine Config Operator (WMCO) to install and manage Windows nodes.
1.4.2. Change cluster components 

Use custom resource definitions (CRDs) to modify the cluster: Cluster features implemented with Operators can be modified with CRDs. Learn to create a CRD and manage resources from CRDs.
Set resource quotas: Choose from CPU, memory, and other system resources to set quotas.
Prune and reclaim resources: Reclaim space by pruning unneeded Operators, groups, deployments, builds, images, registries, and cron jobs.
Scale and tune clusters: Set cluster limits, tune nodes, scale cluster monitoring, and optimize networking, storage, and routes for your environment.
Update a cluster: Use the Cluster Version Operator (CVO) to upgrade your OpenShift Container Platform cluster. If an update is available from the OpenShift Update Service (OSUS), you apply that cluster update from the OpenShift Container Platform web console or the OpenShift CLI (oc).
Using the OpenShift Update Service in a disconnected environment: You can use the OpenShift Update Service for recommending OpenShift Container Platform updates in disconnected environments.
Improving cluster stability in high latency environments by using worker latency profiles: If your network has latency issues, you can use one of three worker latency profiles to help ensure that your control plane does not accidentally evict pods in case it cannot reach a worker node. You can configure or modify the profile at any time during the life of the cluster.
1.4.3. Observe a cluster 

OpenShift Logging: Learn about logging and configure different logging components, such as log storage, log collectors, and the logging web console plugin.
Red Hat OpenShift distributed tracing platform: Store and visualize large volumes of requests passing through distributed systems, across the whole stack of microservices, and under heavy loads. Use the distributed tracing platform for monitoring distributed transactions, gathering insights into your instrumented services, network profiling, performance and latency optimization, root cause analysis, and troubleshooting the interaction between components in modern cloud-native microservices-based applications.
Red Hat build of OpenTelemetry: Instrument, generate, collect, and export telemetry traces, metrics, and logs to analyze and understand your software’s performance and behavior. Use open source backends like Tempo or Prometheus, or use commercial offerings. Learn a single set of APIs and conventions, and own the data that you generate.
Network Observability: Observe network traffic for OpenShift Container Platform clusters by using eBPF technology to create and enrich network flows. You can view dashboards, customize alerts, and analyze network flow information for further insight and troubleshooting.
In-cluster monitoring: Learn to configure the monitoring stack. After configuring monitoring, use the web console to access monitoring dashboards. In addition to infrastructure metrics, you can also scrape and view metrics for your own services.
Remote health monitoring: OpenShift Container Platform collects anonymized aggregated information about your cluster. By using Telemetry and the Insights Operator, this data is received by Red Hat and used to improve OpenShift Container Platform. You can view the data collected by remote health monitoring.
Power monitoring for Red Hat OpenShift (Technology Preview): You can use power monitoring for Red Hat OpenShift to monitor the power usage and identify power-consuming containers running in an OpenShift Container Platform cluster. Power monitoring collects and exports energy-related system statistics from various components, such as CPU and DRAM. Power monitoring provides granular power consumption data for Kubernetes pods, namespaces, and nodes.
1.5. Storage activities 

Manage storage: With OpenShift Container Platform, a cluster administrator can configure persistent storage by using Red Hat OpenShift Data Foundation, AWS Elastic Block Store, NFS, iSCSI, Container Storage Interface (CSI), and more. You can expand persistent volumes, configure dynamic provisioning, and use CSI to configure, clone, and use snapshots of persistent storage.
Persistent storage using CIFS/SMB CSI Driver Operator (Technology Preview): OpenShift Container Platform is capable of provisioning persistent volumes (PVs) with a Container Storage Interface (CSI) driver for the Common Internet File System (CIFS) dialect/Server Message Block (SMB) protocol. The CIFS/SMB CSI Driver Operator that manages this driver is in Technology Preview status.
Changing vSphere CSI maximum number of snapshots: The default maximum number of snapshots in VMware vSphere Container Storage Interface (CSI) is 3 per volume. In OpenShift Container Platform 4.16, you can now change this maximum number of snapshots to a maximum of 32 per volume. You also have granular control of the maximum number of snapshots for vSAN and Virtual Volume datastores.
Volume cloning supported for Azure File (Technology Preview): OpenShift Container Platform 4.16 introduces volume cloning for the Microsoft Azure File Container Storage Interface (CSI) Driver Operator as a Technology Preview feature.
RWOP with SELinux context mount: OpenShift Container Platform 4.16 changes feature status from Technical Preview status to generally available for the access mode ReadWriteOncePod (RWOP). RWOP can be used only in a single pod on a single node. If the driver enables it, RWOP uses the SELinux context mount set in the PodSpec or container, which allows the driver to mount the volume directly with the correct SELinux labels.
1.6. Hosted control plane activities 

Support for Amazon Web Services (AWS): Hosted control planes for OpenShift Container Platform is now Generally Available on the AWS platform. For more information, see the following documentation:

Configuring the hosting cluster on AWS
Technology Preview features: Hosted control planes remains available as a Technology Preview feature on the IBM Power® and IBM Z® platforms and on non-bare metal agent machines. For more information, see the following documentation:

Configuring the hosting cluster on a 64-bit x86 OpenShift Container Platform cluster to create hosted control planes for IBM Power® compute nodes (Technology Preview)
Configuring the hosted cluster on 64-bit x86 bare metal for IBM Z® compute nodes (Technology Preview)
Configuring hosted control plane clusters using non bare metal agent machines (Technology Preview)
