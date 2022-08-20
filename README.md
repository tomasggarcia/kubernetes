Kubectl

Command line tool to run commands against Kubernetes cluster.

Intall Kubectl:
```bash
 curl -LO https://storage.googleapis.com/kubernetes-release/release/$(curl -s https://storage.googleapis.com/kubernetes-release/release/stable.txt)/bin/linux/amd64/kubectl
 chmod +x ./kubectl
sudo mv ./kubectl /usr/local/bin/kubectl
```


Docker Desktop Kubernetes

settings -> Kuberntes -> [] Enable Kubernetes

Verify Kubernetes cluster
```bash
kubectl get nodes
```
