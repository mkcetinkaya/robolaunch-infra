# robolaunch Infrastructure Deployment
Following steps are for deploying **robolaunch kubernetes infrastructure** to cloud providers. It can be deployed to both **cloud providers (AWS, Azure, GCP)** and **on-premise**. Currently supported cloud provider is **AWS** and following steps are applicable for deploying robolaunch kubernetes infrastructure to **AWS**. 

**robolaunch kubernetes infrastructure** is a collection of awesome open source projects and below are list of these components.

- **Containerd (CRI) -** An industry-standard container runtime
- **kube-ovn (CNI) -**  Advanced Kubernetes Network Fabric
- **Rook (CSI) -** Open-Source, Cloud-Native Storage for Kubernetes
- **Virtual Cluster -** Enabling Kubernetes Hard Multi-tenancy
- **Prometheus and Graphan a-** Monitoring infrastructure
- **ELK Stack -** Collecting, storing and analyzing Kubernetes telemetry data

Apart from above main components, 
- **kubeone -** automating cluster operations
- **terraform -** creating cloud infrastructure components are used for deploying all components.

There are two ways to deploy **robolaunch kubernetes infrastructure", **hard-way** and **easy-way**. **Hard way** is deploying all componenets step by step. **Easy way** is using **robolaunch-infra** script.

**robolaunch-infra** is a python script and it takes only required input as a yaml file and then deploy whole infrastructure automatically.

Followings are links for each deployment methods.

- [Hard Way](https://github.com/mkcetinkaya/robolaunch-infra)

- [Easy Way](https://github.com/mkcetinkaya/robolaunch-infra)






