Fibonacci Calculator: Containerized with Docker and Deployed on Kubernetes-
This project demonstrates the containerization of a simple Fibonacci calculator application using Docker and its subsequent deployment to a local Kubernetes cluster. It showcases an efficient and portable environment for microservices, highlighting key aspects of modern application deployment.

Key Features:
1.) Containerization with Docker:
    The Fibonacci calculator was encapsulated within a Docker container. A Dockerfile was meticulously defined     to manage all application dependencies and create a lightweight, portable image. This ensures consistent       behavior across different environments.

2.) Kubernetes Deployment:
    The Dockerized application was seamlessly deployed to a local Kubernetes cluster. This involved crafting       YAML configuration files to define and manage essential Kubernetes resources:
    a.) Pods: The fundamental units of deployment in Kubernetes, housing our containerized Fibonacci                         calculator.
    b.) Services: Enabling network access to the application within the cluster, providing a stable endpoint                     regardless of Pod changes.

3.) Microservices Integration & Orchestration:
    a.) Leveraging Kubernetes' robust features, the application's scalability and reliability were                     significantly enhanced.
    b.) Service Discovery: Kubernetes automatically manages how services find each other, simplifying inter-           service communication.
    c.) Load Balancing: Traffic is efficiently distributed across multiple instances of the Fibonacci                  calculator, optimizing performance and ensuring high availability.
    d.) The deployment was optimized for modularity and fault tolerance, demonstrating a resilient                     microservices architecture.


This project serves as a practical example of how Docker and Kubernetes can be used to build, deploy, and manage scalable and reliable applications.
