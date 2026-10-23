# Kubernetes 🚀

Welcome to my **Kubernetes learning repository**!

This repository documents my journey of learning Kubernetes, understanding its core concepts, and practicing container orchestration through hands-on experiments.

I'm learning Kubernetes step by step, starting with the fundamentals and gradually exploring how Kubernetes manages applications running inside containers.

## 📌 What is Kubernetes?

Kubernetes is an open-source container orchestration platform that automates the deployment, scaling, and management of containerized applications.

It helps manage applications running across multiple machines and provides features such as:

- Container orchestration
- Application scaling
- Self-healing
- Load balancing
- Service discovery
- Automated deployment and management

## 🎯 Learning Objectives

- Understand Kubernetes architecture and its components.
- Learn how Kubernetes manages containers.
- Understand Pods, Nodes, and Clusters.
- Learn how the Kubernetes Control Plane works.
- Practice deploying applications using Kubernetes.
- Explore Kubernetes using Minikube.
- Understand how Kubernetes interacts with Docker containers.

## 📚 Concepts I'm Learning

### Kubernetes Fundamentals
- What is Kubernetes?
- Why Kubernetes?
- Kubernetes architecture
- Kubernetes Cluster
- Control Plane
- Worker Nodes

### Kubernetes Components
- Pods
- Containers
- Nodes
- Kubelet
- API Server
- Scheduler
- Controller Manager
- Container Runtime

### Hands-on Practice
- Installing Kubernetes using Minikube
- Working with kubectl
- Creating and managing Pods
- Deploying applications
- Inspecting Kubernetes resources
- Understanding Pod lifecycle

## 🛠️ Tools & Technologies

- Kubernetes
- Minikube
- kubectl
- Docker
- Linux
- Ubuntu (WSL)

## 💻 My Learning Environment

I'm practicing Kubernetes using Minikube on Ubuntu through WSL2.

This environment helps me understand Kubernetes concepts locally without requiring a cloud-based Kubernetes cluster.

## 🚀 Getting Started

### 1. Check Kubernetes

```bash
kubectl version
```

### 2. Check Minikube

```bash
minikube status
```

### 3. Check Kubernetes Nodes

```bash
kubectl get nodes
```

### 4. Check Pods

```bash
kubectl get pods -A
```

### 5. Create a Test Deployment

```bash
kubectl create deployment nginx --image=nginx
```

### 6. Check Deployment

```bash
kubectl get deployments
```

### 7. Check Pods

```bash
kubectl get pods
```

## 📈 Learning Progress

- [x] Understand Kubernetes fundamentals
- [x] Install Minikube
- [x] Set up a local Kubernetes cluster
- [x] Understand Kubernetes Pods
- [x] Learn about Kubelet
- [x] Practice using kubectl
- [ ] Learn Deployments in depth
- [ ] Learn Services
- [ ] Explore ConfigMaps and Secrets
- [ ] Learn Kubernetes networking
- [ ] Explore Kubernetes volumes
- [ ] Deploy a containerized application

## 📖 Resources

- [Kubernetes Official Documentation](https://kubernetes.io/docs/)
- [Minikube Documentation](https://minikube.sigs.k8s.io/docs/)
- [kubectl Documentation](https://kubernetes.io/docs/reference/kubectl/)

## 🌱 Learning in Public

I'm documenting my Kubernetes learning journey to strengthen my understanding of container orchestration, cloud-native technologies, and DevOps practices.

This repository will continue to grow as I learn new concepts and build hands-on projects.

**Learning step by step. Building practical knowledge. 🚀**

