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
