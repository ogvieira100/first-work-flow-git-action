# first-work-flow-git-action

## Esse é o primeiro work flow de git action 

Clique na aba actions existem vários modelos pré-definidos:.


Deployment
View all
Deploy Node.js to Azure Web App
By Microsoft Azure

Deploy Node.js to Azure Web App logo
Build a Node.js project and deploy it to an Azure Web App.

Deployment
Deploy to Amazon ECS
By Amazon Web Services

Deploy to Amazon ECS logo
Deploy a container to an Amazon ECS service powered by AWS Fargate or Amazon EC2.

Deployment
Build and Deploy to GKE
By Google Cloud

Build and Deploy to GKE logo
Build a docker container, publish it to Google Container Registry, and deploy to GKE.

Deployment
Terraform
By HashiCorp

Terraform logo
Set up Terraform CLI in your GitHub Actions workflow.

Deployment
Deploy to Alibaba Cloud ACK
By Alibaba Cloud

Deploy to Alibaba Cloud ACK logo
Deploy a container to Alibaba Cloud Container Service for Kubernetes (ACK).

Deployment
Deploy to IBM Cloud Kubernetes Service
By IBM

Deploy to IBM Cloud Kubernetes Service logo
Build a docker container, publish it to IBM Cloud Container Registry, and deploy to IBM Cloud Kubernetes Service.

Deployment
Tencent Kubernetes Engine
By Tencent Cloud

Tencent Kubernetes Engine logo
This workflow will build a docker container, publish and deploy it to Tencent Kubernetes Engine (TKE).

Deployment
OpenShift
By Red Hat

OpenShift logo
Build a Docker-based project and deploy it to OpenShift.

Deployment

Vamos trabalhar com **Simple workflow**

### Simple workflow
Vamos configurar o yaml passo a passo

name:First WorkFlow 
on: workflow_dispatch
jobs:
  first-job:
    runs-on: ubuntu-latest
    steps:
      - name: Print Greeting 
        run: echo "Hello Word"
      - name: Print Goodbye
        run: echo "Done - bye!"  

