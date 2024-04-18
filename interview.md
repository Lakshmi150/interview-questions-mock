- **Explain Azure Infra Structure**
   - Azure infrastructure consists of data centers, regions, availability zones, resource groups, virtual machines, and networking services, 
     providing the foundation for deploying and managing cloud-based applications and services.
- **What Are Docker Containers**
  - Docker containers are lightweight, portable, and self-sufficient environments that 
    encapsulate software and its dependencies, allowing 
  - applications to run consistently across different computing environments. They package 
    everything needed to run an application, including 
  -  code, runtime, system tools, libraries, and settings, into a single container. This enables 
     developers to easily build, ship, and deploy 
   - applications in a predictable and efficient manner, regardless of the underlying 
    infrastructure
- **What Is the Use of Neo Load Tool and Tosca**
  - NeoLoad is a load testing tool for assessing application performance under various conditions. Tosca is a software testing tool supporting 
   functional testing, regression testing, and test automation.
- **Difference between Ingress and Load Balancer**
  - Ingress manages external access to Kubernetes services, acting as a traffic controller for incoming requests. Load Balancer distributes 
    incoming network traffic across multiple servers to ensure high availability and reliability of applications.
- **Define Cluster IP**
  - Cluster IP is an internal IP address assigned to a Kubernetes service, enabling communication between different parts of an application 
    within the Kubernetes cluster. It allows for inter-service communication while abstracting the underlying network details.
- **Explain Service Connection**
  - A service connection is a configuration in DevOps pipelines that allows secure access to 
    external services like Azure, AWS, or GitHub. It enables pipelines to interact with these 
    services, such as deploying applications, fetching dependencies, or accessing resources, 
    while maintaining security and authentication.
- **Explain Terraform Stages**
  - Terraform stages are divisions within a configuration that organize infrastructure provisioning steps, typically representing different 
    environments such as development, testing, staging, and production.
- **Define Helm Charts and Helm Space**
  - Helm Charts: Packages for defining and managing Kubernetes applications.
  - Helm Space":  commonly used in DevOps practices for deploying, managing, and scaling 
                containerized applications on Kubernetes clusters
- **Explains Modules**
  - Modules are like building blocks in programming. They're pieces of code that perform specific tasks or functions. You can use them to 
     organize your code, make it easier to understand, and reuse code across different parts of your project.
- **Define Availability Sets**
  - Availability Sets are a feature in Microsoft Azure that ensure high availability of virtual machines (VMs) by distributing them across 
   multiple physical servers within a datacenter. This helps to minimize the impact of hardware failures and planned maintenance events, 
    ensuring that at least one VM remains available even if others are affected.
- **Explain Azure Key Vault**
  - Azure Key Vault: Microsoft Azure service for securely storing and managing sensitive information like keys, passwords, and certificates.
- **Define Steady State File**
  - A steady state file typically refers to a file or data snapshot that represents a system or process in a stable condition without 
   significant changes over time. It serves as a reference point for comparison or analysis, often used in fields such as engineering, 
    economics, or computer science to assess system performance, behavior, or equilibrium.
- **Define Pod Scaling**
  - Pod scaling adjusts the number of pod instances in Kubernetes for optimal performance and resource utilization.
- **Explain Replica Sets and Replica Controller**
   - Replica Sets and Replica Controllers are Kubernetes resources for ensuring high availability and scalability of pods.
   - Replica Sets maintain a specified number of identical pods to ensure availability, manage scaling, and handle pod failures.
   - Replica Controllers are the older version of Replica Sets
- **Explain Docker Daemon, Docker Kill command, Docker Layer**
   - Docker objects such as images, containers, networks, and volumes. A daemon can also 
   communicate with other daemons to manage Docker services.
   - Docker Kill command: It stops a running Docker container abruptly.
   - Docker Layer: It's a part of Docker's efficient image-building system, allowing changes to 
    be cached and reused to speed up image creation and deployment.
- **Explain Ingress Controller**
   - An Ingress Controller manages external access to services in Kubernetes, routing traffic based on user-defined rules for load balancing and 
     SSL/TLS termination
- **Explain Blue Green Deployment Strategy**     
   -Blue-Green Deployment is a strategy in software development where you have two identical production environments, one active (blue) and the 
    other inactive (green). You gradually shift traffic from the blue environment to the green one after deploying updates or changes
- **Explain Dynatrace and CTL**
  - Dynatrace is an APM tool for monitoring application performance, offering real-time insights and automated problem resolution. CTL often 
    refers to Container Tools Library, encompassing tools like Docker and Kubernetes for container management.
- **What are the components of Kubernates?**
  - `Master Node Components`:
    apiserver: Exposes the Kubernetes API. All operations and communications within the cluster are handled through this component.
    etcd: A distributed key-value store that stores the cluster's state. It's the backing store for all Kubernetes data.
    scheduler: Assigns newly created pods to nodes based on resource availability and other constraints.
    controller-manager: Runs controller processes which regulate the state of the cluster, such as nodes, replication controllers, 
    endpoints.
   - `Node Components`:
    kubelet: An agent that runs on each node and ensures containers are running in a pod as expected. It interacts with the Kubernetes API 
           server and manages containers through container runtimes (e.g., Docker, containerd).
    kube-proxy: Maintains network rules and performs request forwarding. It runs on each node and manages communication between pods and other 
                 networked resources.
   Pod Networking: Kubernetes uses a flat networking model where every pod can communicate with every other pod in the cluster without NAT
container storage:
  
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
- **What Is Load Balancer**
  - A load balancer evenly distributes incoming network traffic across multiple servers or computing resources to optimize performance, maximize 
   availability, and prevent overload on any single server.

