# eks-terraform-example

Example code to create, authenticate with and configure an EKS cluster using Terraform. To run, first download terraform from https://www.terraform.io/downloads.html.

Files intended for use in conjuction with the blog post **Creating, Authenticating and Configuring Elastic Kubernetes Service using Terraform** 

- **/build** - Run First - Covers the creation of the EKS Cluster (Master and Worker nodes)
- **/configure** - Run Second - Covers the authentication with the kubernetes Control Plane and via lookup of data from EKS and direct use of kubernetes resources
