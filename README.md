# My DevOps Journey
This is a tracker of my DevOps Journey - projects & learning.
---

### Projects
**When**  
February 2019 - 

**Project Description**  
Tranquility Base is the official GFT branding for the reference architecture project that started in October 2018.
The goal of this project was to demonstrate on Google UK HQ on 7th March 2019 the following:
- How to build a modern application architecture using microservices
- How to use Google Cloud to achieve this
- How GFT can help roll this architecture out in a highly regulated industry such as financial services

**Responsibilites**
- Deploying Jenkins GKE Cluster using Terraform and Helm
- Implementing CI/CD pipeline using Jenkins:
1) automated process from code change in Google Repository, building Docker images and putting them in Google Registry to development environment (Google Kubernetes Engine Cluster) with five microservices
2) communication between different GCP projects
3) automated process of Canary Releases
4) full pipeline for Google Conference
- Implementing autoscaling and health checks (liveness and readiness probes)
- Implemented Grafana dashboard for autoscaling purpose

**Technologies Used**
- Kubernetes
- Google Kubernetes Engine
- Google Cloud Platform
- Docker
- Istio
- Jenkins
- Terraform
- Prometheus
- Grafana
- Helm
- Linux
---
**When**  
November 2018 - January 2019
<br><br>**Project Description**  
Re-engineering of the client's Trade Surveillance platform for scalability, performance and ease of implementing new features to the platform and on-boarding with new clients. The platform architecture was redefined to meet the above requirements. The system analyzed incoming market data from the fraud detection perspective and raise real-time alerts based on predefined rules.

**Responsibilites**
* Productionization of the platform
* Coordinating technical activities with the client's team
* Deploying the application platform on top of Openshift on VM / Google Cloud Platform
* Deploying the whole platform using Terraform (Infrastructure as Code) - 13 Virtual Machines, additional disks, networks interfaces, as well as an application platform on top of Openshift cluster (Cassandra, Flink, Kafka, Zookeper, Minio, MySQL)
* Describing / reviewing / deploying several types of Openshift installations (1-node deployment, 3-nodes deployment, 10-nodes deployment on Virtual Machines in Google Cloud Platform) using Ansible playbooks and configuration files
* Managing and encrypting secrets inside the cluster
* Assessing disconnected Openshift installation and preparing prerequisites for a client to deploy Openshift in disconnected environment<br>Assessed GlusterFS and heketi as Persistent Volume storage (created procedure how to do it and deployed on test cluster), as well as automatic way to restart Openshift pods in specific order
* Documenting all the work - procedures, how to articles

**Technologies Used**
* Openshift
* Kubernetes
* Docker
* Google Cloud Platform
* Git
* GitLab
* Ansible
* Terraform
* Prometheus
* Grafana
* Linux
---

### Courses

| Status   | When     | Course        | Provider      | Keywords           |     
| -------- | -------- | ------------- | ------------- | ------------------ |
|    25%           | March 2019  | [Python 3 Scripting for System Administrators](https://linuxacademy.com/cp/modules/view/id/168) | [Linux Academy](https://linuxacademy.com/) - [Keith Thompson](https://linuxacademy.com/blog/linux-academy/employee-spotlight-keith-thompson-devops-training-architect/) | Python |
|    100%           | February 2019  | [Getting Started with Google Kubernetes Engine](https://www.coursera.org/learn/google-kubernetes-engine/home/welcome) | [Coursera - by Google](https://www.coursera.org/learn/google-kubernetes-engine/home/welcome) | Google Kubernetes Engine,<br>Jenkins,<br>Spinaker,<br>Canary Deployment |
|    100%           | January - February 2019  | [Implementing a Full CI/CD Pipeline](https://linuxacademy.com/devops/training/course/name/implementing-a-full-ci-cd-pipeline) | [Linux Academy](https://linuxacademy.com/) - [Will Boyd](https://linuxacademy.com/blog/linuxacademy-com/behind-the-scenes/employee-spotlight-will-boyd-devops-training-architect/) | CI/CD,<br>DevOps,<br>Git,<br>GitHub,<br>Gradle,<br>Jenkins,<br>Docker,<br>Kubernetes,<br>Prometheus,<br>Grafana,<br>Self-Healing,<br>Autoscaling,<br>Canary Deployment |
|    60%           | December 2018 - January 2019  | [Red Hat Certified Specialist in Platform-as-a-Service Exam (EX280) Prep Course](https://linuxacademy.com/cp/modules/view/id/149) | [Linux Academy](https://linuxacademy.com/) - [Treva Williams](https://www.openstack.org/community/speakers/profile/12618/treva-williams) | Openshift |
|     100%          | December 2018 | [Beginner’s Guide to Containers and Orchestration](https://linuxacademy.com/containers/training/course/name/beginners-guide-to-containers-and-orchestration) | [Linux Academy](https://linuxacademy.com/) - [Will Boyd](https://linuxacademy.com/blog/linuxacademy-com/behind-the-scenes/employee-spotlight-will-boyd-devops-training-architect/) | Docker,<br>Kubernetes,<br>Cloud,<br>Microservices |
|       100%        | November 2018 | [Docker Quick Start](https://linuxacademy.com/devops/training/course/name/docker-quick-start) | [Linux Academy](https://linuxacademy.com/) - [Terence Cox](https://linuxacademy.com/blog/linuxacademy-com/employee-spotlight-terry-cox/) | Docker
|       100%        | November 2018 | [Git Quick Start](https://linuxacademy.com/linux/training/course/name/git-quick-start) | [Linux Academy](https://linuxacademy.com/) - [Terence Cox](https://linuxacademy.com/blog/linuxacademy-com/employee-spotlight-terry-cox/) | Git
|       100%        | October 2018  | [DevOps Essentials](https://linuxacademy.com/devops/training/course/name/devops-essentials-2018) | [Linux Academy](https://linuxacademy.com/) - [Will Boyd](https://linuxacademy.com/blog/linuxacademy-com/behind-the-scenes/employee-spotlight-will-boyd-devops-training-architect/) | DevOps,<br>Build Automation,<br>Continous Integration,<br>Continous Delivery,<br>Continous Deployment,<br>Infrastructure As Code,<br>Configuration Management,<br>Orchestration,<br>Monitoring,<br>Microservices,<br>Cloud
|       100%        | October 2018  | [GCP - Essential Cloud Infrastructure: Core Services](https://www.coursera.org/learn/gcp-infrastructure-core-services) | [Coursera - by Google](https://www.coursera.org/programs/gcp-courses-gtm-sep18-u0w20) | Google Cloud Platform,<br>IAM,<br>Data Storage Services,<br>Resource Management,<br>Resource Monitoring |
|      100%         | October 2018  | [GCP - Essential Cloud Infrastructure: Foundation](https://www.coursera.org/learn/gcp-infrastructure-foundation)       | [Coursera - by Google](https://www.coursera.org/programs/gcp-courses-gtm-sep18-u0w20) | Google Cloud Platform,<br>Virtual Machines,<br>Virtual Networking|
|       100%        | October 2018  | [GCP - Google Cloud Platform Fundamentals: Core Infrastructure](https://www.coursera.org/learn/gcp-fundamentals)       | [Coursera - by Google](https://www.coursera.org/programs/gcp-courses-gtm-sep18-u0w20) | Google Cloud Platform,<br>Virtual Machines,<br>Storage,<br>Containers,<br>Monitoring,<br>Big Data,<br>Machine Learning |
