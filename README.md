# AWS_EKS_TF
Simple AWS EKS deployment written in Terraform

Started from [Provision an EKS Cluster tutorial](https://developer.hashicorp.com/terraform/tutorials/kubernetes/eks), containing
Terraform configuration files to provision an EKS cluster on AWS.


# ------------------------------
This example repository contains configuration to provision a VPC, security groups, and an EKS cluster with the following architecture:
![alt text](https://developer.hashicorp.com/_next/image?url=https%3A%2F%2Fcontent.hashicorp.com%2Fapi%2Fassets%3Fproduct%3Dtutorials%26version%3Dmain%26asset%3Dpublic%252Fimg%252Fterraform%252Feks%252Foverview.png%26width%3D1522%26height%3D1054&w=3840&q=75)
```
aws eks update-kubeconfig education-eks-GJDSweYr
```


# TODO
1. Why is there a second sg group added to the master node??
    - eks-cluster-sg-danp-test-cluster-230599731	sg-027f73afc4c4c2bda (k8s security group)
    - danp-test-cluster-node-20240126220322084300000008	sg-0438c296464568791	