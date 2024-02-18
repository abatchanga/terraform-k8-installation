# provision-eks-cluster-with-terraform
This repository helps you provision a cluster in AWS EKS using Terraform

# After runing terraform apply connect localy your cluster with this command:
# aws eks update-kubeconfig --region us-east-1 --name utrains-eks-YLRVgE

# additional installations

# power shell as admin
# 1- Install kubernetes-cli
# choco install kubernetes-cli
# kubctl version

# 2- Install helm
# choco install helm
# helm version

# 3-Install openlens
# choco install openlens
