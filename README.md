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
- kubeshark

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
- [x] Learn Deployments in depth
- [x] Learn Services
- [ ] Explore ConfigMaps and Secrets
- [ ] Learn Kubernetes networking
- [ ] Explore Kubernetes volumes
- [ ] Deploy a containerized application

## 🚀 Kubernetes Deployments

Today, I learned about **Kubernetes Deployments** and how they help manage containerized applications running inside a Kubernetes cluster.

### 📌 What is a Kubernetes Deployment?

A Kubernetes Deployment is a Kubernetes resource that manages the desired state of application Pods.

It helps automate:
- Creating and managing Pods
- Maintaining the desired number of replicas
- Replacing failed or deleted Pods
- Updating applications through rolling updates
- Rolling back to previous versions when required

Instead of manually creating and managing individual Pods, we can use a Deployment to manage them.

### 🏗️ Deployment Architecture

```text
Kubernetes Cluster
       |
       v
   Deployment
       |
       v
 ReplicaSet
       |
       v
      Pods
       |
       v
   Containers
       |
       v
   Application
```

### 🛠️ Hands-on Practice

#### 1. Create a Deployment

```bash
kubectl create deployment nginx --image=nginx
```

This creates a Deployment named `nginx` using the Nginx container image.

#### 2. Check Deployments

```bash
kubectl get deployments
```

#### 3. Check Pods

```bash
kubectl get pods
```

#### 4. Describe a Deployment

```bash
kubectl describe deployment nginx
```

This command provides detailed information about the Deployment, including its configuration, replica status, and events.

#### 5. Scale a Deployment

```bash
kubectl scale deployment nginx --replicas=3
```

This changes the desired number of Pods to three.

Verify:

```bash
kubectl get pods
```

#### 6. Delete a Deployment

```bash
kubectl delete deployment nginx
```

This deletes the Deployment and the Pods it manages.

### 📚 Key Learnings

- A Deployment manages application Pods.
- Deployments use ReplicaSets to maintain the desired number of replicas.
- Deployments help maintain application availability.
- Scaling allows us to run multiple instances of an application.
- Kubernetes can replace Pods when they are deleted or fail.
- Deployments support rolling updates and rollbacks.

### 🎯 Objective

Understand how Kubernetes Deployments manage Pods, maintain the desired application state, and simplify application scaling and updates.

**Learning Kubernetes step by step through hands-on practice. 🚀**


## 📖 Resources

- [Kubernetes Official Documentation](https://kubernetes.io/docs/)
- [Minikube Documentation](https://minikube.sigs.k8s.io/docs/)
- [kubectl Documentation](https://kubernetes.io/docs/reference/kubectl/)

## 🌱 Learning in Public

I'm documenting my Kubernetes learning journey to strengthen my understanding of container orchestration, cloud-native technologies, and DevOps practices.

This repository will continue to grow as I learn new concepts and build hands-on projects.

**Learning step by step. Building practical knowledge. 🚀**

