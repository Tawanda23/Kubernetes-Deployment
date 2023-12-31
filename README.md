# Kubernetes-Deploment

## Tablet of Contents
- Description
- Project Goals
- Lessons Learnt
- Installation
- Useful Commands

## Description
This project serves as my first practical project using Kubernetes to deploy a web application. The aim of this project is to put into practice the skills i have been learning to successfully deploy a javascript web app to the external domain.

## Project Goals
 - Successfully deploy a web app using Kubernetes Cluster 
 - Enhance Kubernetes ocherstration

## Lessons Learnt
1. **Kubernetes Orchestration:**
   - Gain a deeper understanding of how Kubernetes orchestrates containerized applications.
   - Learn to define and manage deployments, services, and configuration using YAML manifests.

2. **Configuration Management:**
   - Explore ConfigMaps and Secrets for managing configuration data securely.
   - Understand how to handle sensitive information, such as credentials, using Kubernetes Secrets.

3. **Monitoring and Logging:**
   - Explore tools and practices for monitoring and logging within a Kubernetes cluster.
   - Understand the importance of observability for troubleshooting and optimization.

## Installation
To perform Kubernetes deployment, you need to have followed these steps:

1. Install Minikube on your local machine
2. Install Docker desktop 
3. Install an editor of your choice.
4. Create the relate files required for the webapp deployment
5. For the purpose of the project, the following web app image - https://hub.docker.com/repository/docker/nanajanashia/k8s-demo-app
6. For mac OS users, you may experience issues connecting to the IP address generated by the K8s cluster, use:
    - minikube service webapp-service.

## Useful Commands
- `minikube start`: Starts Minikube.
- `kubectl apply -f {container name}`: Initiates all the services that have been created.
- `kubectl get all`: Displays full information regarding the deployed pods.
- `minikube ip`: Retrieves the IP address of the web app.
- `kubectl log {pod-name}`: Shows the log details of that specific pod.
- `minikube stop`: Stops the Minikube cluster.

For more information on Kubernetes, refer to the [Kubernetes official documentation](https://kubernetes.io/docs/home/).




