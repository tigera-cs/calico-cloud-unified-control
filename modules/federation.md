# Cluster Federation

## Module Objectives

01. Understand how clusters are federated using Calico Cloud
02. Understand the service accounts, roles, role bindings, and cluster role bindings required to federate clusters. 


## Module Tasks

01. Create tigera-federation-remote-cluster service accounts (SA)
02. Create kubeconfig file using the token from tigera-federation-remote-cluster SA
03. Create remote cluster secrets in local clusters using kubeconfig file of remote cluster
04. Assign RBAC required for the calico-typha SA to access the remote cluster secret
05. Create RemoteClusterConfiguration resource
06. Apply RBAC required for the tigera-federation-remote-cluster SA to access cluster resources
07. Use calicoq to validate federation


## Module Tasks Overview
![Cluster Federation](images/cluster-federation.png)
