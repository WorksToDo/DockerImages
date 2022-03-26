This docker image contains both doctl, argocd and kubectl together. The doctl
is the command line interface for digital ocean, argocd is a continous deployment
tool to deploy apps to k8s clusters, and kubectl is a cli for k8s servers.

The reason for merge this tools is using in CI-CD pipeline to deploy apps to k8s
cluster. General behaviour in pipeline; get cluster configs from doctl to set kubectl configs to connect the cluster, then use kubectl to apply argocd application to k8s cluster, then use argocd to deploy the application to the 
k8s server.
