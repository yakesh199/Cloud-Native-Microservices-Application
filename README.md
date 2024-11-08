# Cloud-Native Microservices Application

## Project Overview
This project, **Cloud-Native Microservices Application**, showcases a modern approach to building scalable, cloud-native applications. Two versions of this application have been developed:

1. **Version 1**: Utilizes Amazon Web Services (AWS) to create a robust, scalable cloud-based backend.
2. **Version 2**: Extends Version 1 by incorporating containerization with Docker, and orchestration with Kubernetes, to create a fully cloud-native microservices architecture.

Each version highlights specific skills in cloud infrastructure, backend development, DevOps, and modern web technologies, with a consistent focus on best practices for scalability, reliability, and maintainability.

---

## Version 1: AWS Cloud-Native Application

### Technologies Used
- **Frontend Build Tool**: Vite for fast builds and a streamlined development experience.
- **Programming Language**: TypeScript for type safety and developer tooling.
- **Backend Development**: Node.js with AWS-specific modules (`aws.ts`, `index.ts`, `pty.ts`) to interact with various AWS services.
- **Cloud Infrastructure**: Amazon Web Services (AWS) with key services such as:
  - **EC2** for compute resources
  - **Lambda** for serverless functions
  - **S3** for scalable storage solutions
- **Infrastructure as Code**: AWS-specific configuration files, with possible use of CloudFormation or Terraform for automated infrastructure management.
- **Package Management**: npm and Yarn for efficient dependency management.
- **Source Control**: Git and GitHub for version control and collaborative development.

### Key Features
1. **AWS Integration**: Seamless interaction with AWS services, providing a robust, scalable, and secure cloud-based backend infrastructure.
2. **TypeScript Codebase**: The entire project is written in TypeScript, benefiting from its static typing and tooling for a better development experience.
3. **Custom Backend Logic**: The codebase includes specific TypeScript modules to handle business logic, interact with AWS resources, and support backend functionality.
4. **Infrastructure as Code**: Demonstrates IaC by defining and managing cloud resources programmatically, promoting infrastructure consistency and reproducibility.
5. **Best Practices**: Ensures code quality through ESLint for linting and maintains code standards for a clean, readable, and efficient codebase.

### Deployment and Setup
To deploy **Version 1** of the Cloud-Native Microservices Application:

1. **Set up AWS Resources**: Configure the required AWS services, such as EC2, S3, and Lambda, as per the application needs.
2. **Install Dependencies**: Use `npm` or `Yarn` to install necessary packages.
3. **Build the Application**: Compile and package the application code for deployment.
4. **Deploy on AWS**: Use the AWS CLI or IaC tools like CloudFormation/Terraform for deployment.
5. **Manage Lifecycle**: Scale, monitor, and maintain the application through AWS tools, ensuring performance and reliability.

---

## Version 2: AWS + Kubernetes + Docker Cloud-Native Application

### Technologies Used
- **Cloud Infrastructure**: Amazon Web Services (AWS) for hosting and managing cloud resources.
- **Containerization Platform**: Docker for creating, managing, and distributing application containers.
- **Orchestration**: Kubernetes for deploying, scaling, and managing the containerized application components.
- **Programming Language**: TypeScript for consistent, type-safe code.
- **Backend Development**: Node.js with custom application modules, emphasizing service modularity.
- **Microservices Architecture**: Separate services for different functionalities, organized into distinct modules such as:
  - **frontend**: Handles the user interface and client interactions.
  - **init-service**: Likely a startup or initialization service.
  - **orchestrator-simple**: Coordinates service interactions and workflows.
  - **runner**: Executes core application logic or specific tasks.
- **Infrastructure as Code**: YAML configuration files for Kubernetes manifests, allowing programmatic resource definitions and easy automation.
- **Source Control**: Git and GitHub for version control and project collaboration.

### Key Features
1. **Microservices Architecture**: Breaks down the application into distinct, loosely coupled services, enabling independent scaling and high availability.
2. **Containerization and Kubernetes**: Uses Docker for container packaging and Kubernetes for orchestration, providing a reliable, scalable environment for the application.
3. **Infrastructure as Code**: Manages infrastructure programmatically using Kubernetes manifests, promoting consistency and simplified deployments.
4. **TypeScript Codebase**: Consistent use of TypeScript for type safety and tooling, ensuring high code quality and developer productivity.
5. **Best Practices for Cloud-Native Applications**: Follows cloud-native standards, including health checks, readiness and liveness probes, and resource limits, ensuring robust and resilient services.

### Deployment and Setup
To deploy **Version 2** of the Cloud-Native Microservices Application:

1. **Set up AWS Resources and Kubernetes Cluster**: Configure the necessary AWS resources and initialize a Kubernetes cluster.
2. **Configure Kubernetes Manifests**: Define services, deployments, and other resources in YAML configuration files.
3. **Install Dependencies**: Use `npm` or `Yarn` to install all dependencies.
4. **Build Docker Images**: Package the application into Docker containers and push them to a container registry if needed.
5. **Deploy to Kubernetes**: Apply Kubernetes manifests to deploy the containers to the cluster.
6. **Monitor and Maintain**: Use Kubernetes tools and AWS monitoring to observe application performance, manage scaling, and handle routine maintenance.

---

## Comparison of Versions

| Feature                                      | Version 1: AWS Only                                       | Version 2: AWS + Kubernetes + Docker                     |
|----------------------------------------------|-----------------------------------------------------------|----------------------------------------------------------|
| **Cloud Infrastructure**                     | AWS Services (EC2, Lambda, S3, etc.)                      | AWS + Kubernetes Cluster                                 |
| **Application Architecture**                 | Monolithic or basic service integration                   | Microservices-based                                      |
| **Containerization**                         | Not used                                                  | Dockerized application for modular deployment            |
| **Orchestration**                            | N/A                                                       | Kubernetes for service orchestration and scaling         |
| **Programming Language**                     | TypeScript                                                | TypeScript                                               |
| **Infrastructure as Code**                   | AWS Configurations (e.g., CloudFormation)                 | Kubernetes YAML Manifests                                |
| **Deployment Process**                       | AWS CLI / IaC for deployment                              | Docker + Kubernetes CLI for containerized deployment     |
| **Package Management**                       | npm, Yarn                                                 | npm, Yarn                                                |
| **Code Quality and Best Practices**          | ESLint, GitHub for version control                        | ESLint, GitHub for version control                       |
| **Scalability and High Availability**        | Limited to AWS scaling tools                              | Kubernetes with automated scaling and health management  |

---

## Conclusion
The **Cloud-Native Microservices Application** demonstrates a progression in cloud-native development skills:

- **Version 1 (AWS)**: Showcases the use of AWS services for cloud-hosted applications with an emphasis on backend integration, scalable infrastructure, and core DevOps practices.
- **Version 2 (AWS + Kubernetes + Docker)**: Expands on these foundations with containerization, orchestration, and a microservices architecture, following industry best practices for building highly available, reliable, and maintainable applications.

Both versions reflect strong expertise in cloud-native development, modern backend engineering, and DevOps, highlighting an ability to build scalable, efficient, and maintainable applications in cloud environments.
