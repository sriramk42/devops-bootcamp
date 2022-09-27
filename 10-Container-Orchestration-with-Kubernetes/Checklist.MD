# Module Checklist 

## Introduction to Kubernetes
 - [X] Watched videos
  
## Basic Concepts and Main K8s Components
 - [X] Watched videos

## Kubernetes Architecture
 - [X] Watched videos

## Minikube and Kubectl - Local Setup
 - [X] Watched videos
 - [X] Demo executed
   - [X] Installed and setup Minikube
   - [X] Installed Kubectl

## Kubernetes CLI - Main kubectl commands
 - [X] Watched videos
 - [X] Demo executed
   - [X] Created nginx Deployment
   - [X] Edited Deployment
   - [X] Created mongodb Deployment
   - [X] Inspected logs of a Pod
   - [X] Got shell of a running container - kubectl exec
   - [X] Deleted deployment
   - [X] Applied configuration file

## YAML Configuration File
 - [X] Watched videos

## Demo project: Deploying MongoDB and Mongo Express
 - [X] Watched videos
 - [X] Prerequisite:
   - [X] Minikube cluster running
 - [X] Demo executed - Deploying MongoDB and MongoExpress:
   - [X] Created MongoDB Deployment
   - [X] Created Secret for Mongo Credentials
   - [X] Created MongoDB Internal Service
   - [X] Created MongoExpress Deployment
   - [X] Created ConfigMap for DB Server URL
   - [X] Created Mongo Express External Service

## Organizing components with Namespaces
 - [X] Watched videos

## Kubernetes Services
 - [X] Watched videos

## Ingress
 - [X] Watched videos

## Persisting Data with Volumes
 - [X] Watched videos

## ConfigMap & Secret Volume Types
 - [X] Watched videos
 - [ ] Demo executed
   - [ ] Created Mosquitto Deployment without any volumes
   - [ ] Created ConfigMap component to overwrite mosquitto.conf file
   - [ ] Created Secret component to add passwords file
   - [ ] Adjusted Mosquitto Deployment to include volumes

## Deploying Stateful Apps with StatefulSet
 - [X] Watched videos

## Introduction to Managed Kubernetes Services
 - [X] Watched videos

## Helm - Package Manager of Kubernetes
 - [X] Watched videos

## Helm Demo: Install a Stateful Application on K8s using Helm
 - [X] Watched videos
 - [X] Demo executed
   - [X] Created K8s cluster on Linode Kubernetes Engine
   - [X] Deployed replicated MongoDB (StatefulSet using Helm Chart) and configured Data Persistence with Linode Block Storage
   - [X] Deployed MongoExpress (Deployment and Service)
   - [X] Deployed NGINX Ingress Controller as Loadbalancer (using Helm Chart)
   - [X] Configured Ingress rule

## Demo: Deploy App from Private Docker Registry
 - [X] Watched videos
 - [X] Demo executed:
   - [X] Logged in to AWS Container Repository | docker login and create docker config.json file
   - [X] Created Secret component
   - [X] Configured Deployment for demo app
 - [X] Pre-requisites:
   - [X] Setup a Private Docker Repository (e.g. AWS Elastic Container Registry)
   - [X] Have a demo application

## Extending the K8s API with Operators
 - [X] Watched videos

## Prometheus Operator Demo with Helm: Setup Prometheus Monitoring on Kubernetes
 - [X] Watched videos
 - [X] Demo executed:
   - [X] Installed Prometheus Operator Helm Chart
   - [X] Accessed Grafana UI (configured port-forward)
   - [X] Accessed Prometheus UI (configured port-forward)

## Secure your Cluster - Authorization with RBAC
 - [ ] Watched videos

## Microservices in Kubernetes (Part 1)
 - [X] Watched videos

## Demo Project: Deploy Microservices Application (Part 2)
 - [X] Watched videos
 - [X] Demo executed:
   - [X] Created YAML file with 11 Deployment and corresponding Service manifests
   - [X] Note: All Services’ Components are Internal Services, except the Frontend Service, which needs to be accessed from browser
   - [X] Created a K8s cluster with 3 Worker Nodes on Linode (or any other cloud platform)
   - [X] Connected to the cluster
   - [X] Created a Namespace and deployed all the micro services into it
   - [X] Accessed Online Shop with Browser

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
 - [X] Watched videos
 - [X] Demo executed
   - [X] Created “microservices” Helm Chart
   - [X] Created values.yaml files for each microservice
   - [X] Created “redis” Helm Chart and values file for it

## Deploy Microservices with Helmfile (Part 5)
 - [X] Watched videos
 - [X] Demo executed
   - [X] Deployed Microservices Application with “helm install”
   - [X] Created Helmfile
   - [X] Installed Helmfile
   - [X] Deployed Helm Charts with HelmFile