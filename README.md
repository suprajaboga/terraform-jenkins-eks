Write terraform code for Jenkins server (Do manual terraform init, plan, apply) - EC2 instance will be created and in that Jenkins & Terraform will be installed automatically using the user script

Write terraform code for EKS Cluster (don't add Configuration files folder yet)

In Jenkins dashboard -> Manage Jenkins -> Credentials -> Add AWS Access & Secret access key

Create Jenkins pipeline file (don't add last stage yet)

In Jenkins dashboard -> Pipeline -> Click on Build now -> Using Jenkinsfile EKS Cluster will be created

Create Configuration files folder in EKS Cluster

In Jenkinsfile pipeline, add the last stage

Run the pipeline then nginx will be deployed in eks-cluster
