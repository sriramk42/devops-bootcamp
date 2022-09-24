# Module Checklist 

## Introduction to Kubernetes
 - [ ] Watched videos
  
## Basic Concepts and Main K8s Components
 - [ ] Watched videos

## Kubernetes Architecture
 - [ ] Watched videos

## Minikube and Kubectl - Local Setup
 - [ ] Watched videos
 - [ ] Demo executed
   - [ ] Installed and setup Minikube
   - [ ] Installed Kubectl

## Kubernetes CLI - Main kubectl commands
 - [ ] Watched videos
 - [ ] Demo executed
   - [ ] Created nginx Deployment
   - [ ] Edited Deployment
   - [ ] Created mongodb Deployment
   - [ ] Inspected logs of a Pod
   - [ ] Got shell of a running container - kubectl exec
   - [ ] Deleted deployment
   - [ ] Applied configuration file

## YAML Configuration File
 - [ ] Watched videos

## Demo project: Deploying MongoDB and Mongo Express
 - [ ] Watched videos
 - [ ] Prerequisite:
   - [ ] Minikube cluster running
 - [ ] Demo executed - Deploying MongoDB and MongoExpress:
   - [ ] Created MongoDB Deployment
   - [ ] Created Secret for Mongo Credentials
   - [ ] Created MongoDB Internal Service
   - [ ] Created MongoExpress Deployment
   - [ ] Created ConfigMap for DB Server URL
   - [ ] Created Mongo Express External Service

## Organizing components with Namespaces
 - [ ] Watched videos

## Kubernetes Services
 - [ ] Watched videos

## Ingress
 - [ ] Watched videos

## Persisting Data with Volumes
 - [ ] Watched videos

## ConfigMap & Secret Volume Types
 - [ ] Watched videos
 - [ ] Demo executed
   - [ ] Created Mosquitto Deployment without any volumes
   - [ ] Created ConfigMap component to overwrite mosquitto.conf file
   - [ ] Created Secret component to add passwords file
   - [ ] Adjusted Mosquitto Deployment to include volumes

## Deploying Stateful Apps with StatefulSet
 - [ ] Watched videos

## Introduction to Managed Kubernetes Services
 - [ ] Watched videos

## Helm - Package Manager of Kubernetes
 - [ ] Watched videos

## Helm Demo: Install a Stateful Application on K8s using Helm
 - [ ] Watched videos
 - [ ] Demo executed
   - [ ] Created K8s cluster on Linode Kubernetes Engine
   - [ ] Deployed replicated MongoDB (StatefulSet using Helm Chart) and configured Data Persistence with Linode Block Storage
   - [ ] Deployed MongoExpress (Deployment and Service)
   - [ ] Deployed NGINX Ingress Controller as Loadbalancer (using Helm Chart)
   - [ ] Configured Ingress rule

## Demo: Deploy App from Private Docker Registry
 - [ ] Watched videos
 - [ ] Demo executed:
   - [ ] Logged in to AWS Container Repository | docker login and create docker config.json file
   - [ ] Created Secret component
   - [ ] Configured Deployment for demo app
 - [ ] Pre-requisites:
   - [ ] Setup a Private Docker Repository (e.g. AWS Elastic Container Registry)
   - [ ] Have a demo application

## Extending the K8s API with Operators
 - [ ] Watched videos

## Prometheus Operator Demo with Helm: Setup Prometheus Monitoring on Kubernetes
 - [ ] Watched videos
 - [ ] Demo executed:
   - [ ] Installed Prometheus Operator Helm Chart
   - [ ] Accessed Grafana UI (configured port-forward)
   - [ ] Accessed Prometheus UI (configured port-forward)

## Secure your Cluster - Authorization with RBAC
 - [ ] Watched videos

## Microservices in Kubernetes (Part 1)
 - [ ] Watched videos

## Demo Project: Deploy Microservices Application (Part 2)
 - [ ] Watched videos
 - [ ] Demo executed:
   - [ ] Created YAML file with 11 Deployment and corresponding Service manifests
   - [ ] Note: All Services’ Components are Internal Services, except the Frontend Service, which needs to be accessed from browser
   - [ ] Created a K8s cluster with 3 Worker Nodes on Linode (or any other cloud platform)
   - [ ] Connected to the cluster
   - [ ] Created a Namespace and deployed all the micro services into it
   - [ ] Accessed Online Shop with Browser

## Production & Security Best Practices  (Part 3)
 - [ ] Watched videos
 - [ ] Demo executed - Improved Microservices Config Files
   - [ ] BP 1: Added version to each container image
   - [ ] BP 2: Configured Liveness Probe for each container
   - [ ] BP 3: Configured Readiness Probe for each container
   - [ ] BP 4: Configured Resource Requests
   - [ ] BP 5: Configured Resource Limits
   - [ ] BP 6: Don’t use NodePort Service Type
   - [ ] BP 7: Configure more than 1 Replica for each Deployment

## Create Helm Chart for Microservices (Part 4)
 - [ ] Watched videos
 - [ ] Demo executed
   - [ ] Created “microservices” Helm Chart
   - [ ] Created values.yaml files for each microservice
   - [ ] Created “redis” Helm Chart and values file for it

## Deploy Microservices with Helmfile (Part 5)
 - [ ] Watched videos
 - [ ] Demo executed
   - [ ] Deployed Microservices Application with “helm install”
   - [ ] Created Helmfile
   - [ ] Installed Helmfile
   - [ ] Deployed Helm Charts with HelmFile