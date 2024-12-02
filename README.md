# AWS-Managed EKS Cluster with Java-Based Application Deployment

## Project Overview  
This project demonstrates the deployment of a Java-based application in an AWS-managed private EKS cluster. The setup leverages a GitOps approach and incorporates best practices for scalable and secure microservices architecture. The pipeline automates the build, test, and deployment processes while integrating security tools to ensure compliance and reliability.

---

## Key Highlights  

### CI/CD Pipeline  
- Automated the build, test, and deployment workflows using **Jenkins**.  
- Integrated security tools like **OWASP Dependency Check** for vulnerability scans.  

### GitOps Workflow  
- Managed deployments using manifest files stored in a **GitHub repository**, serving as the single source of truth for all deployments and configuration changes.  

### Application Deployment  
- Deployed **stateless applications** using **Deployments** and **stateful applications** (e.g., databases) using **StatefulSets**.  
- Configured **path-based routing** for Dev and Prod namespaces using **Ingress** resources.  
- Implemented a **ClusterIP service** to facilitate communication between the frontend and the database.  

### Data Persistence  
- Utilized **Amazon EBS volumes** for persistent storage, ensuring data durability and high availability.  

### Namespace Isolation  
- Defined **network policies** to restrict communication between resources in the Dev and Prod namespaces.  
- Created user accounts with **Role-Based Access Control (RBAC)** permissions tailored to Dev and Prod environments.  

### Monitoring and Observability  
- Integrated **Prometheus** and **Grafana** for real-time monitoring and visualization of application metrics.  

---

## Tools and Technologies Used  

- **Cloud Platform**: AWS (EKS, EBS, IAM)  
- **CI/CD Tools**: Jenkins  
- **GitOps**: GitHub for manifest storage and repository management  
- **Container Orchestration**: Kubernetes  
- **Monitoring**: Prometheus and Grafana  
- **Storage**: Amazon EBS (Elastic Block Store)  
- **Networking**: Kubernetes Ingress, ClusterIP, and Network Policies  

---

### view below repo's 
   ```
    https://github.com/spring-projects/spring-petclinic.git

    https://github.com/spkumar17/k8s_deployments.git

   ```
