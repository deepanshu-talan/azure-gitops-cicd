# Azure GitOps CI/CD for Microservices

A GitOps-based CI/CD implementation for deploying containerized microservices to **Azure Kubernetes Service (AKS)**.

> **Application Note:** This project uses the [Docker Example Voting App](https://github.com/dockersamples/example-voting-app) as the sample microservices workload. The application itself is not developed as part of this project; the focus is on building the CI/CD and GitOps workflow around an existing containerized application.

The project is being developed incrementally, with the **CI workflow currently implemented**. Future stages will introduce Azure Container Registry, AKS, Kubernetes, and ArgoCD-based GitOps delivery.

* **Azure DevOps** handles the CI workflow.
* **Docker** is used to build and package the microservices.
* **Docker Hub** is currently used to store the container images.
* **Azure Container Registry (ACR)** is planned as the future container registry.
* **Kubernetes / AKS** are planned for application deployment.
* **ArgoCD** is planned for GitOps-based continuous delivery.