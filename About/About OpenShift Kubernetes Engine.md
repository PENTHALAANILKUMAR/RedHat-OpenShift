Red Hat has decided to rename Red Hat OpenShift Container Engine to Red Hat OpenShift Kubernetes Engine to better communicate what value the product offering delivers.
Red Hat OpenShift Kubernetes Engine is a product offering from Red Hat that lets you use an enterprise class Kubernetes platform as a production platform for launching containers. You download and install OpenShift Kubernetes Engine the same way as OpenShift Container Platform as they are the same binary distribution, but OpenShift Kubernetes Engine offers a subset of the features that OpenShift Container Platform offers.

**4.1.1. Core Kubernetes and container orchestration**

OpenShift Kubernetes Engine offers full access to an enterprise-ready Kubernetes environment that is easy to install and offers an extensive compatibility test matrix with many of the software elements that you might use in your data center.

OpenShift Kubernetes Engine offers the same service level agreements, bug fixes, and common vulnerabilities and errors protection as OpenShift Container Platform.** OpenShift Kubernetes Engine includes a Red Hat Enterprise Linux (RHEL) Virtual Datacenter and Red Hat Enterprise Linux CoreOS (RHCOS)** entitlement that allows you to use an integrated Linux operating system with container runtime from the same technology provider.

The OpenShift Kubernetes Engine subscription is compatible with the Red Hat OpenShift support for Windows Containers subscription.

**4.1.2.  Enterprise-ready configurations **

OpenShift Kubernetes Engine uses the same security options and default settings as the OpenShift Container Platform. Default security context constraints, pod security policies, best practice network and storage settings, service account configuration, SELinux integration, HAproxy edge routing configuration, and all other standard protections that OpenShift Container Platform offers are available in OpenShift Kubernetes Engine. OpenShift Kubernetes Engine offers full access to the integrated monitoring solution that OpenShift Container Platform uses, which is based on Prometheus and offers deep coverage and alerting for common Kubernetes issues.

OpenShift Kubernetes Engine uses the same installation and upgrade automation as OpenShift Container Platform.

4.1.3. Standard infrastructure services 

With an OpenShift Kubernetes Engine subscription, you receive support for all storage plugins that OpenShift Container Platform supports.

In terms of networking, OpenShift Kubernetes Engine offers full and supported access to the Kubernetes Container Network Interface (CNI) and therefore allows you to use any third-party SDN that supports OpenShift Container Platform. It also allows you to use the included Open vSwitch software defined network to its fullest extent. OpenShift Kubernetes Engine allows you to take full advantage of the OVN Kubernetes overlay, Multus, and Multus plugins that are supported on OpenShift Container Platform. OpenShift Kubernetes Engine allows customers to use a Kubernetes Network Policy to create microsegmentation between deployed application services on the cluster.

You can also use the Route API objects that are found in OpenShift Container Platform, including its sophisticated integration with the HAproxy edge routing layer as an out of the box Kubernetes Ingress Controller.

4.1.4. Core user experience 

OpenShift Kubernetes Engine users have full access to Kubernetes Operators, pod deployment strategies, Helm, and OpenShift Container Platform templates. OpenShift Kubernetes Engine users can use both the oc and kubectl command-line interfaces. OpenShift Kubernetes Engine also offers an administrator web-based console that shows all aspects of the deployed container services and offers a container-as-a service experience. OpenShift Kubernetes Engine grants access to the Operator Life Cycle Manager that helps you control access to content on the cluster and life cycle operator-enabled services that you use. With an OpenShift Kubernetes Engine subscription, you receive access to the Kubernetes namespace, the OpenShift Project API object, and cluster-level Prometheus monitoring metrics and events.

4.1.5. Maintained and curated content 

With an OpenShift Kubernetes Engine subscription, you receive access to the OpenShift Container Platform content from the Red Hat Ecosystem Catalog and Red Hat Connect ISV marketplace. You can access all maintained and curated content that the OpenShift Container Platform eco-system offers.

4.1.6. OpenShift Data Foundation compatible 

OpenShift Kubernetes Engine is compatible and supported with your purchase of OpenShift Data Foundation.

4.1.7. Red Hat Middleware compatible 

OpenShift Kubernetes Engine is compatible and supported with individual Red Hat Middleware product solutions. Red Hat Middleware Bundles that include OpenShift embedded in them only contain OpenShift Container Platform.

4.1.8. OpenShift Serverless 

OpenShift Kubernetes Engine does not include OpenShift Serverless support. Use OpenShift Container Platform for this support.

4.1.9. Quay Integration compatible 

OpenShift Kubernetes Engine is compatible and supported with a Red Hat Quay purchase.

4.1.10. OpenShift Virtualization 

OpenShift Kubernetes Engine includes support for the Red Hat product offerings derived from the kubevirt.io open source project.

4.1.11. Advanced cluster management 

OpenShift Kubernetes Engine is compatible with your additional purchase of Red Hat Advanced Cluster Management (RHACM) for Kubernetes. An OpenShift Kubernetes Engine subscription does not offer a cluster-wide log aggregation solution or support Elasticsearch, Fluentd, or Kibana-based logging solutions. Red Hat OpenShift Service Mesh capabilities derived from the open-source istio.io and kiali.io projects that offer OpenTracing observability for containerized services on OpenShift Container Platform are not supported in OpenShift Kubernetes Engine.

4.1.12. Advanced networking 

The standard networking solutions in OpenShift Container Platform are supported with an OpenShift Kubernetes Engine subscription. The OpenShift Container Platform Kubernetes CNI plugin for automation of multi-tenant network segmentation between OpenShift Container Platform projects is entitled for use with OpenShift Kubernetes Engine. OpenShift Kubernetes Engine offers all the granular control of the source IP addresses that are used by application services on the cluster. Those egress IP address controls are entitled for use with OpenShift Kubernetes Engine. OpenShift Container Platform offers ingress routing to on cluster services that use non-standard ports when no public cloud provider is in use via the VIP pods found in OpenShift Container Platform. That ingress solution is supported in OpenShift Kubernetes Engine. OpenShift Kubernetes Engine users are supported for the Kubernetes ingress control object, which offers integrations with public cloud providers. Red Hat Service Mesh, which is derived from the istio.io open source project, is not supported in OpenShift Kubernetes Engine. Also, the Kourier Ingress Controller found in OpenShift Serverless is not supported on OpenShift Kubernetes Engine.

4.1.13. OpenShift sandboxed containers 

OpenShift Kubernetes Engine does not include OpenShift sandboxed containers. Use OpenShift Container Platform for this support.

4.1.14. Developer experience 

With OpenShift Kubernetes Engine, the following capabilities are not supported:

The OpenShift Container Platform developer experience utilities and tools, such as Red Hat OpenShift Dev Spaces.
The OpenShift Container Platform pipeline feature that integrates a streamlined, Kubernetes-enabled Jenkins and Tekton experience in the user’s project space.
The OpenShift Container Platform source-to-image feature, which allows you to easily deploy source code, dockerfiles, or container images across the cluster.
Build strategies, builder pods, or Tekton for end user container deployments.
The odo developer command line.
The developer persona in the OpenShift Container Platform web console.
