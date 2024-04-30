# JE

# Task: Setting up Rancher, k3s Cluster, and ArgoCD

## Step 1: Create 2 Virtual Machines

Use any virtualization technology like Hyper-V, KVM, VirtualBox, etc. to create 2 virtual machines.

## Step 2: Install Rancher on one of the VMs

Follow the official instructions for Rancher installation.

## Step 3: Deploy a k3s Cluster using Rancher

Use Rancher to deploy a k3s cluster on the neighboring virtual machine.

## Step 4: Deploy a Dummy Application with ArgoCD

1. Install ArgoCD on the k3s cluster deployed using Rancher.
   
   Follow the official ArgoCD installation instructions: https://argoproj.github.io/argo-cd/getting_started/.

2. Deploy the dummy application using ArgoCD and Helm charts.

   Use the Helm charts from the following GitHub repository: https://github.com/argoproj/argocd-example-apps.

