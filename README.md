# Using Kubernetes To Deploy Multi Containers Application
## (Kubernetes requires already built images to pull from docker hub)

Step 1: 
    * Install Kubectl as command-line tool to run commands again Kubernetes clusters.
    * Check Enable Kubernetes option in Docker Desktop. Alternative option to Docker   Deskop, you can install minikube to run Kubernetes locally (remember to get ip by command minikube ip before access to connect to your local cluster). 

Step 2:
    * Create objects with different kind property (Pod, Deployment, Service...)

Step 3:
    * Run kubectl apply -f filename

Step 4:
    * Access to your application by localhost:port

<img width=“964” alt=“Kubernetes” src=“https://github.com/Nhukangasniemi/kubernetes/blob/main/images/minikube.png?raw=true” />
