1. Creating an EKS Cluster
To create an EKS cluster with eksctl:
eksctl create cluster --name=eksrajavarma \
  --version 1.36 \
  --region=ap-south-1 \
  --zones=ap-south-1a,ap-south-1b \
  --nodegroup-name ng-default \
  --node-type t3.small \
  --nodes 2 \
  --managed
