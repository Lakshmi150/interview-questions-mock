# interview-questions-mock
# day-1-Preparation
- **Self Intro**
  - I've been deeply involved in the architecture and management of cloud infrastructure. I've adeptly handled tasks such as provisioning storage 
    accounts, virtual networks, and VM deployments both manually through Azure Portal and automated via Terraform.
  - My expertise extends to implementing robust CI/CD pipelines utilizing a suite of tools like Git, GitHub, Jenkins, and Ansible, ensuring 
    seamless integration and deployment processes.
  - I've played a pivotal role in designing and configuring Azure network components for high availability, including load 
    balancers, NSGs, and VNet/subnet setups. Additionally, I've been instrumental in deploying and maintaining Docker container clusters managed 
    by Kubernetes, ensuring scalability and reliability.
  - Furthermore, my experience encompasses tasks like Azure SQL database management, Azure Backup 
    configuration for VMs, and facilitating the migration of on-premises applications to Azure, ensuring optimal performance and data protection 
    through Azure Site Recovery and Backup solutions.
- **What are the components of Kubernates?**
  - `Master Node Components`:
    kube-apiserver: Exposes the Kubernetes API. All operations and communications within the cluster are handled through this component.
    etcd: A distributed key-value store that stores the cluster's state. It's the backing store for all Kubernetes data.
    kube-scheduler: Assigns newly created pods to nodes based on resource availability and other constraints.
    kube-controller-manager: Runs controller processes which regulate the state of the cluster, such as nodes, replication controllers, 
    endpoints.
   - `Node Components`:
    kubelet: An agent that runs on each node and ensures containers are running in a pod as expected. It interacts with the Kubernetes API server 
             and manages containers through container runtimes (e.g., Docker, containerd).
    kube-proxy: Maintains network rules and performs request forwarding. It runs on each node and manages communication between pods and other 
                 networked resources.
   - `Add-ons`:
  DNS: Provides DNS-based service discovery for Kubernetes services.
  Ingress Controller: Manages external access to services within a Kubernetes cluster, typically through HTTP and HTTPS.
  Dashboard: A web-based user interface for managing and monitoring Kubernetes clusters.
  Storage Plugins: Integrations with various storage solutions, allowing Kubernetes to manage persistent storage volumes.
    - `Networking`:
  Pod Networking: Kubernetes uses a flat networking model where every pod can communicate with every other pod in the cluster without NAT. 
  Various networking solutions such as Calico, Flannel, and Weave provide this functionality.
  Service Networking: Enables communication between different parts of an application by exposing a stable IP address and DNS name for a set of 
  pods.
- **How to achive High Availabiity of Cluster**
  - Deploy Kubernetes across multiple nodes.
  - Configure a highly available control plane.
  - Use a clustered etcd for data storage.
  - Ensure node redundancy for application rescheduling.
  - Implement load balancing for traffic distribution.
  - Deploy applications with multiple replicas.
  - Configure network redundancy and isolation.
  - Set up monitoring and alerting for proactive issue detection.
- **Define multi cluster architecutre**
  - A multi-cluster architecture refers to a system design such as servers, virtual machines, or containers
  - Each cluster typically operates independently but may be interconnected to facilitate communication and data sharing
- **Explain contanirization**
  - Docker is a containerization platform that provides easy way to containerize your applications, which means, using Docker you can build 
     container images, run the images to create containers and also push these containers to container regestries such as DockerHub, Quay.io and so on.
- **explain ansible**
  - Ansible is an open-source automation tool used for configuration management, application deployment, and task automation. It simplifies IT 
    operations by allowing users to define infrastructure as code using YAML-based playbooks, which describe desired configurations and tasks. 
    Ansible connects to remote systems over SSH or other protocols, executes tasks in parallel, and ensures consistency and repeatability across 
    infrastructure environments.
- **explain jenkins**
  - Jenkins is an open-source automation server used for continuous integration and continuous delivery (CI/CD). It automates software building, 
    testing, and deployment processes, supports extensibility through plugins, and enables flexible pipeline orchestration with code-based 
    configurations.
- **Explain gitreset and git revert**
   - `git reset` is used to move the HEAD to a different state, altering commit history (use with caution).
     `git revert` is used to create a new commit that undoes the changes introduced by previous commits without altering existing history.
- **explain shell scrpiting**
   - Shell scripting involves writing scripts in a shell language (like Bash) to automate tasks and execute commands in a command-line 
     environment. It's used for automating repetitive tasks, system administration, and customizing system behavior.
- **Explain partitining in devops**
  - Partitioning in DevOps refers to the practice of dividing resources, systems, or workloads into smaller, manageable segments to improve 
    organization, efficiency, and isolation. It involves separating infrastructure, networks, applications, data, and workloads based on specific 
     criteria such as function, team, or environment to streamline operations and enhance scalability, security, and reliability.
- **explain head start command**
  - a "head start" command could be a script or container entry point that performs initialization tasks, such as setting up configuration files, 
   loading initial data, or preparing dependencies, before the main application components start.
- **Define Prometheus Monitoring**
   - Prometheus Monitoring is an open-source monitoring and alerting toolkit focused on gathering metrics from applications and infrastructure 
     components. It stores collected data in a time-series database, allowing users to query and visualize performance metrics, and set up alerts 
     based on predefined conditions
- **Define Virtual Machine**
  - A virtual machine (VM) is a software-based emulation of a physical computer, capable of running an operating system and applications. It 
    allows multiple virtual instances to run on a single physical machine, enabling efficient resource utilization and isolation between 
    different environments or workloads
- **Explain Virtualization**
  - Virtualization is the process of creating a virtual representation of something, such as a server, storage device, network, or operating 
    system. In computing, it typically refers to creating virtual instances of hardware or software environments, allowing multiple virtual 
    entities to run independently on the same physical hardware. This enables efficient resource utilization, scalability, and isolation between 
    different computing environments.
- **Explain SSH Inventory File**
  - An SSH inventory file is a text file that lists the details of multiple servers or devices accessible via SSH (Secure Shell). It typically 
   includes information such as the hostname or IP address, port number, username, and optionally authentication keys or passwords. This file is 
   commonly used in automation scripts or tools to perform batch operations or manage configurations across multiple remote systems via SSH.
- **Explain Ansible Tower**
  - Ansible Tower is a web-based user interface and management tool for Ansible, an open-source automation platform. It provides a centralized 
    platform for automating infrastructure tasks, including deployment, configuration management, and orchestration. With Ansible Tower, users 
   can define, schedule, and monitor Ansible jobs, manage inventories of hosts, and control access through role-based permissions. It enhances 
   the scalability, security, and ease of use of Ansible automation across organizations
- **What are Cloud Related Providers . Explain?**
- **Explain KPI’s**
  - KPIs are metrics used to measure the performance and success of specific activities or processes in achieving organizational objectives.
- **Define Terraform**
  - Terraform is an open-source Infrastructure as Code (IaC) tool developed by HashiCorp.
- **How can We Provisioning the Active Directory**
  - You can provision Active Directory using tools like PowerShell scripts, Active Directory Administrative Center (ADAC), or deployment tools 
    such as Microsoft Deployment Toolkit (MDT) or Windows Deployment Services (WDS). Additionally, you can automate the provisioning process 
    using configuration management tools like Ansible or infrastructure as code tools like Terraform
- **Explain the Working Process of Devops tools**
  - DevOps tools automate collaboration, code integration, testing, deployment, and monitoring throughout the software development lifecycle.
- **Explain Azure Infra Structure**
   - Azure infrastructure consists of data centers, regions, availability zones, resource groups, virtual machines, and networking services, 
     providing the foundation for deploying and managing cloud-based applications and services.
- **What Are Docker Containers**
  - Docker containers are lightweight, portable, and self-sufficient environments that encapsulate software and its dependencies, allowing 
    applications to run consistently across different computing environments. They package everything needed to run an application, including 
    code, runtime, system tools, libraries, and settings, into a single container. This enables developers to easily build, ship, and deploy 
    applications in a predictable and efficient manner, regardless of the underlying infrastructure
- **What Is the Use of Neo Load Tool and Tosca**
  - NeoLoad is a load testing tool for assessing application performance under various conditions. Tosca is a software testing tool supporting 
   functional testing, regression testing, and test automation.
- **Difference between Ingress and Load Balancer**
  - Ingress manages external access to Kubernetes services, acting as a traffic controller for incoming requests. Load Balancer distributes 
    incoming network traffic across multiple servers to ensure high availability and reliability of applications.
- **What Is Load Balancer**
  - A load balancer evenly distributes incoming network traffic across multiple servers or computing resources to optimize performance, maximize 
   availability, and prevent overload on any single server.
- **Define Cluster IP**
  - Cluster IP is an internal IP address assigned to a Kubernetes service, enabling communication between different parts of an application 
    within the Kubernetes cluster. It allows for inter-service communication while abstracting the underlying network details.
- 
