# AWS_EKS_TF
Simple AWS EKS deployment written in Terraform

Started from [Provision an EKS Cluster tutorial](https://developer.hashicorp.com/terraform/tutorials/kubernetes/eks), containing
Terraform configuration files to provision an EKS cluster on AWS.


# ------------------------------
This example repository contains configuration to provision a VPC, security groups, and an EKS cluster with the following architecture:
![alt text](https://developer.hashicorp.com/_next/image?url=https%3A%2F%2Fcontent.hashicorp.com%2Fapi%2Fassets%3Fproduct%3Dtutorials%26version%3Dmain%26asset%3Dpublic%252Fimg%252Fterraform%252Feks%252Foverview.png%26width%3D1522%26height%3D1054&w=3840&q=75)

Set the TF_CLOUD_ORGANIZATION environment variable to your Terraform Cloud organization name. This will configure your Terraform Cloud integration.
```
aws eks update-kubeconfig education-eks-GJDSweYr
```
